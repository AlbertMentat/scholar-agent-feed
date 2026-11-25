# 📑 论文索引 - 2026-11-26

共 168 篇论文

---

### [1] SciFig2Data: A Workflow for Recovering Structured Data from Scientific Figures

**链接**: https://arxiv.org/abs/2611.31787
**作者**: Xinhe Wu, Yicheng Ye, and Yadong Jin
**来源**: cs.AI
**匹配关键词**: Large Language Model, MLLM, Multimodal Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Scientific measurements reported in scholarly articles are often embedded in compound figures rather than available as machine-readable data. Recovering these measurements at literature scale requires an integrated workflow for figure localization, panel decomposition, chart identification, numerical reconstruction, and experimental context association. We present \textit{SciFig2Data}, an automated, high-throughput workflow for harvesting structured experimental data from scientific PDF repositories. The system integrates multi-scale document element detection, adaptive compound figure decomposition, two-stage OCR-based semantic filtering, Swin-based chart classification, and instruction-guided multimodal large language model (MLLM) reconstruction. It further incorporates directory-level batch execution, caching, and structured logging to support large-scale processing. We demonstrate the workflow on two biomedical literature corpora comprising 605 toxicology and pharmacology articles 

---

### [2] GreenDynaMix: Thermal-Aware Dynamic Mixed-Precision MoE LLM Inference Systems

**链接**: https://arxiv.org/abs/2611.31737
**作者**: Han-Yi Lin, Kieran Griperay, Qiang Zhou, Xiangyu Zhou, Nate Bonacci, Zinachidi Achikeh 等 (10 人)
**来源**: cs.AI cs.SY eess.SY
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Sustained Large Language Model (LLM) inference generates significant heat that exacerbates silicon aging and reduces GPU reliability. Because GPU temperature fluctuates continuously with workload intensity and ambient conditions, keeping it in a safe range requires real-time frequency scaling, which inevitably comes at the cost of either throughput or accuracy. To address this tightly coupled challenge, we propose GreenDynaMix, the first runtime system to jointly integrate a DVFS-based thermal manager with a dynamic precision-tuning throughput compensator. A sensitivity-aware allocator leverages intrinsic importance signals from the Mixture-of-Experts (MoE) router to assign higher precision to critical experts, preserving accuracy. Experiments on server, desktop, and embedded platforms demonstrate that GreenDynaMix reduces the temperature-induced aging rate of GPUs during LLM inference by 25-33%. Without offline profiling or model retraining, it recovers throughput at a perplexity cost

---

### [3] Validation Bias in Large Language Model Responses to Cancer Treatment Queries: A Factorial Cross-Sectional Study

**链接**: https://arxiv.org/abs/2611.31251
**作者**: Ramez Kouzy, Saketh Vinjamuri, Sarah Ghalayini, Jack Gallifant, Shan Chen, Marielle Fis Loperana 等 (8 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) chatbots are increasingly used by patients seeking cancer information, but their safety when users present evidence-misaligned beliefs about treatment remains uncharacterized. We hypothesized that LLMs exhibit validation bias, affirming rather than correcting such beliefs, and evaluated this with a 2x2x2 factorial design crossing conversation format (single-turn vs multi-turn), treatment type (evidence-based vs alternative), and query valence (positive vs negative). Framing was evidence-aligned (supporting evidence-based treatments or questioning alternative therapies) or evidence-misaligned (promoting alternative treatments or questioning evidence-based therapies). We analyzed 1,272 conversations (6,360 interactions) across 14 LLMs from 6 vendors, scored by an LLM judge (GPT-5-mini) validated against human annotation on a 6-dimension safety rubric. The primary outcome was the unsafe response rate, defined as a Weak classification or any critical failure. Evi

---

### [4] XMind: Thinking Twice via Cross-Memory Reasoning for LLM-Based Autonomous Driving

**链接**: https://arxiv.org/abs/2611.32209
**作者**: Zuyi Guo, Xianjie Dai, Lei Yang, Xiaocong Zhao, Jingguang Li, Kitae Jang 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Memory-augmented large language model (LLM) driving agents can reuse past experience, yet previously learned corrections often fail to transfer when traffic conditions change. A key limitation is that existing memories mainly record observed outcomes, providing little evidence about alternative actions. We introduce XMind, a training-free framework that enables LLM-based driving to "Think Twice" through cross-memory reasoning. XMind integrates working memory of recent traffic states with episodic memory of critical risk events. The agent first makes an initial decision from the current context and then cross-checks it against retrieved historical experience. If a conflict arises, it makes a second decision guided by the retrieved evidence. To construct reliable episodic memory, XMind evaluates alternative actions through counterfactual rollouts under perturbed traffic conditions and stores the verified outcomes as structured risk capsules. These capsules are retrieved by jointly matchi

---

### [5] LoomKV: Lossless KV Cache Compression from GPU Memory to SSD for LLM Serving

**链接**: https://arxiv.org/abs/2611.32954
**作者**: Wentao Zhu, Ziao Sheng, Peng Deng, Huiqi Hu, Xuan Zhou, Xing Wei 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) serving engines offload the key/value (KV) cache from GPU memory to host DRAM and SSD so multi-turn and agent requests can reuse prompt prefixes. Capacity then limits service at two levels: external tiers govern prefix reuse before eviction, while the GPU KV pool bounds concurrent long requests, and lossy compression alters KV values and outputs. LoomKV brings lossless KV compression to both external tiers (tier mode) and the GPU pool (pool mode) on an unmodified engine. Using a calibrated per-head two-level 3-bit code over BF16 high bytes (sign and upper seven exponent bits), LoomKV stores BF16 KV at 0.71 of its raw size across nine models and FP8 KV at 0.85-0.87. In tier mode, TileStream writes exact-length records with length readback off the load path, leaving tier storage, eviction, and prefetch unchanged, and decompresses fetched records straight into scattered GPU pages. In pool mode, FragPack packs variable-length records into smaller shared-budget GP

---

### [6] ExpGuard: Guarding Long-Horizon LLM Agents against Corrupted Experience

**链接**: https://arxiv.org/abs/2611.32085
**作者**: Yuzhou Chen, Licheng Pan, Zhixuan Chu, Yunsheng Lu, Yichen Sun, Han Zheng 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-horizon large language model (LLM) agents distill past trajectories into reusable experiences. Misleading or adversarial guidance in source trajectories can corrupt these experiences, allowing harmful instructions to persist across tasks and influence future agent actions. Assessing the risks of potentially corrupted experiences poses three challenges: (1) modeling provenance and execution dependencies before experience reuse, (2) learning task-conditioned risk from trajectory outcomes, and (3) repairing risky experiences at online inference. To address these challenges, we present ExpGuard, a framework for retrieval-triggered experience risk assessment and online repair. Specifically, to tackle challenge (1), ExpGuard integrates experience semantics with provenance and execution dependencies in a task-conditioned heterogeneous graph to predict attack and task-failure risks before experience reuse. To enable task-conditioned risk supervision and tackle challenge (2), we conduct ma

---

### [7] SpatialCraft: Evolving Procedural Intelligence from Experience and Skills for Spatial Reasoning Agents

**链接**: https://arxiv.org/abs/2611.31475
**作者**: Xiwei Liu, Yulong Li, Xuhui Li, Zhixiang Lu, Haolin Yang, Jianxu Chen 等 (9 人)
**来源**: cs.AI
**匹配关键词**: Large Language Model, MLLM, Multimodal Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Spatial reasoning agents increasingly rely on external tools, such as 3D reconstruction, segmentation, and geometric computation, to answer questions that a multimodal large language model (MLLM) cannot resolve from pixels alone. Tool access, however, shifts the bottleneck to orchestration: the agent must decide which tools to call, in what order, and how to interpret their outputs, yet a stateless agent repeats the same mistakes across tasks. We ask whether a frozen tool-using agent can improve its orchestration from its own interaction history, without parameter updates. We present SpatialCraft, a self-evolving framework that maintains two forms of external knowledge: Experiences, condition-action tactics distilled by contrasting rollouts of the same task, and Skills, multi-step procedures with explicit activation and termination conditions. Three designs couple the two streams. Experiences can be anchored to a Skill, appearing only while it is active rather than once per task. A Con

---

### [8] Contrastive On-Policy Self-Distillation for LLM Unlearning

**链接**: https://arxiv.org/abs/2611.31932
**作者**: Fangzhou Lin, Shuo Xing, Xin Li, Wenbin He, Zhengzhong Tu, Liu Ren
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model unlearning aims to remove the influence of designated training data while preserving unrelated model capabilities. Existing likelihood-based methods commonly optimize against fixed forget sequences, providing only negative supervision on what the model should not generate and overlooking the states visited by the evolving unlearned policy. We introduce Contrastive On-Policy Self-Distillation (CPSD), a new unlearning framework that constructs an explicit knowledge-reduced target distribution and distills it along the model's own trajectories. Given a student rollout, a frozen reference model evaluates each token under a plain context and a privileged context containing the forget information. CPSD treats the resulting distributional shift as a knowledge-associated direction and reverses it to obtain a counterfactual unlearning target. The student is then trained to match this target at every rollout position while retaining its utility on unrelated data. We further 

---

### [9] From Rule-based to Agentic: LLM Agent based Real-time Control of Urban Drainage Systems for Flooding and Sewer Overflow Mitigation

**链接**: https://arxiv.org/abs/2611.32046
**作者**: Wenchong Tian, Shixun Li, Ruozhou Lin, Peng Ye, Zhiyu Zhang, Shi Tao 等 (10 人)
**来源**: cs.AI cs.SY eess.SY
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Real-time control (RTC) for urban drainage systems (UDS) remains hampered by sparse in-network sensing. While heterogeneous multi-modal meteorological early warnings often contain decision-critical information for UDS RTC, none of the existing approaches can exploit such externally-sourced information within the control workflow. Here we introduce AgenticAI-Control, an agentic artificial intelligence framework able to assimilate multi-source meteorological early warnings in RTC. Two coupled large language model agents are integrated to generate control strategies by retrieving meteorological early-warnings and fusing them with domain engineering expertise. Validated via simulation studies of a combined sewer catchment in eastern China across 10 real-world rainfall events, the AgenticAI-Control achieved 69.1-90.6% reduction in aggregated flood and overflow volumes compared to the rule-based baseline control. Rigorously standardized prompt engineering and modular workflow constraints sub

---

### [10] RECAP: Training Long-horizon LLM Agents with Context Compaction

**链接**: https://arxiv.org/abs/2611.31258
**作者**: Yulun Jiang, Maria Brbic, Michael Moor
**来源**: cs.CL cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Context compaction enables large language model agents to tackle long-horizon tasks within limited context budgets by replacing interaction histories with compressed summaries. However, learning effective compaction jointly with the agent policy remains challenging, as summaries affect task success over many subsequent interactions. We introduce RECAP, a reinforcement learning (RL) framework based on the principle that a summary should preserve the behavior induced by the original interaction history. We formalize this principle with a behavior distortion objective that measures the divergence between the agent's subsequent behavior under compressed and original contexts. We show that the gradient of the distortion objective decomposes into two complementary learning signals: distortion-based reward for summary generation and self-distillation for subsequent actions. Experiments on Qwen3.5-4B show that RECAP consistently outperforms the task-reward-only RL baselines on both environment

---

### [11] ASTERISM: Do Multimodal LLMs Actually Look at All the Images?

**链接**: https://arxiv.org/abs/2611.32316
**作者**: Chanseul Cho, Dongwoo Kim, Noori Bae, Seungjae Moon, Seongsu Lee, Youngmin Ro
**来源**: cs.CV cs.AI cs.CL cs.LG
**匹配关键词**: Large Language Model, MLLM, Multimodal Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-image benchmarks aim to test whether a multimodal large language model (MLLM) combines evidence across images, but many of their items can be answered from a single image. Across about 33k items from 19 public benchmarks, our audit and a two-stage single-image filter find that one image or the question alone settles 24.2% of them. On these items, MLLMs recover from one image a median 78% of the accuracy that all images add over the text alone, so these items reward answering from one image, which we call the single-image shortcut. MLLMs take this shortcut even on items where one image is not enough. On such items, most of their wrong answers repeat an answer they give from one image, at a rate well above chance. We build ASTERISM, to our knowledge the largest audited multi-image benchmark, from these 19 benchmarks by keeping their items that need more than one image. Its 18.7k items, 2.0k of them corrected or rewritten, share one format, one scorer and seven task categories. We a

---

### [12] Draft Calibration for Speculative Decoding: Accelerating LLM Serving by Matching Draft and Target Distributions

**链接**: https://arxiv.org/abs/2611.33111
**作者**: Yuxing Liu, Wei Zuo, Walid Krichene, Tong Zhang, Li Zhang
**来源**: cs.LG cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Speculative decoding accelerates large language model (LLM) inference by employing a lightweight draft model to propose draft tokens and allowing the target model to verify the new tokens in parallel to improve inference-time compute utilization. The speedup relies on the acceptance probability of draft tokens in target verification, which is directly related to the gap $\|p-q\|_1$ between the target distribution $p$ and the draft distribution $q$. In this paper, we study draft calibration of speculative decoding to improve the speedup of speculative decoding, where we employ post-hoc methods to calibrate the draft distribution to mitigate the distribution gap. We observe that though current community open-source draft models may learn the top candidate token correctly, they are generally underconfident compared to the target model, suggesting a consistent distribution mismatch. To mitigate the effect of this mismatch on the acceptance rate of the draft models, we try various post-hoc 

---

### [13] LIBRA: Runtime Co-Tuning of Batch Size and Parallelism for Time-Efficient LLM Training

**链接**: https://arxiv.org/abs/2611.32008
**作者**: Shengkai Lyu, Hairui Zhao, Daran Sun, Yida Gu, Xingchen Liu, YueYuan Zhou 等 (9 人)
**来源**: cs.DC cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Training large language models (LLMs) requires choosing both a batch size and a parallel configuration. Existing systems make these decisions in isolation, tuning parallelism for throughput and batch size for convergence, but neither objective alone determines training efficiency. We present LIBRA, a lightweight runtime framework that co-tunes batch size and parallel configuration to minimize end-to-end time. LIBRA treats throughput and convergence as two noisy objectives and searches their joint space using parallel noisy expected hypervolume improvement (qNEHVI). To make this runtime search efficient, we propose hierarchical pruning, which removes infeasible and low-throughput parallel configurations through system-level performance estimation and then narrows batch-size candidates through critical-batch-size-aware convergence monitoring. We further design acquisition-guided parallel evaluation (AGPE), which evaluates surviving candidates concurrently across GPU groups in order of th

---

### [14] Fortune: Formula-Driven Reinforcement Learning for LLM Reasoning over Complex Tables

**链接**: https://arxiv.org/abs/2505.23667
**作者**: Lang Cao, Jingxian Xu, Hanbing Liu, Jinyu Wang, Mengyu Zhou, Haoyu Dong 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [15] INCLUDE-2.0: Disentangling Knowledge Gaps in Multilingual LLM Evaluation

**链接**: https://arxiv.org/abs/2611.31255
**作者**: Angelika Romanou, Maria Grandury, Clara Meister, Negar Foroutan, Jabez Magomere, Anna Sotnikova 等 (10 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Current multilingual benchmarks cover only a fraction of the languages represented in modern pretraining corpora and often conflate language proficiency with the ability to answer questions grounded in specific regions and communities. We introduce INCLUDE-2.0, a large-scale benchmark for region-aware multilingual factual evaluation, which covers 91 languages from 86 countries (127 total language--country pairs), comprising over 220K curated samples drawn from native regional sources. Unlike existing benchmarks that often treat language as a proxy for region, IINCLUDE-2.0 distinguishes between questions whose answers are independent of context, vary by country, concern widely documented facts about a place, or depend on knowledge primarily expressed through local linguistic and cultural sources. Each item is annotated with its regional knowledge type and domain, and paired with an English translation, enabling controlled analysis of the relationship between language proficiency and pos

---

### [16] Can LLM Judges Catch Unsafe Clinical Actions? A Fault-Injection Study

**链接**: https://arxiv.org/abs/2611.33012
**作者**: Neda Ghafouri
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As clinical AI agents begin to interact with electronic health records (EHRs), large language models (LLMs) are increasingly used to evaluate their actions. But how reliably can these judges recognize clinically dangerous mistakes, especially when an agent appears to have completed its task successfully? We investigate this question using MedAgentBench by introducing controlled clinical errors into verified agent trajectories. The experiments include 416 faulty trajectories, eight error categories, and six open-weight LLM judges. By comparing each faulty trajectory with its correct counterpart, we measure whether judges genuinely recognize errors rather than simply flagging more actions as unsafe. The findings show that access to clinical evidence significantly improves judge reliability. When shown only the final answer, judges cannot distinguish errors that leave it unchanged, while flagging 56% of correct trajectories. With full trajectory information, the ability to distinguish uns

---

### [17] Agentic Optimization: LLM Agents Select and Configure Algorithms for Engineering Design

**链接**: https://arxiv.org/abs/2611.31275
**作者**: Dominic Mashak, Jacob Schrum
**来源**: cs.NE cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Engineers solving new multi-objective design problems commonly commit to a multi-objective evolutionary algorithm (MOEA) before seeing a result. The best MOEA differs from benchmark to benchmark. We propose agentic optimization, placing an LLM agent outside the optimization loop, where it reads a natural-language problem description to configure and launch algorithms, drawing on parametric knowledge rather than on a performance history that a novel problem lacks. We compare five LLMs in a fixed harness on four engineering benchmarks and a real-world SARS-CoV-2 molecular docking task, using hypervolume (HV) and IGD+ with multiple comparison-corrected tests. Three models (GPT, DeepSeek, Qwen) dominate every baseline on combined HV and IGD+, and each is significantly better than the best baseline on at least one benchmark, sometimes by applying the same baseline algorithm they surpass, showing the importance of both algorithm configuration and selection. Agent behavior is strongly model-d

---

### [18] LLM-based Personalized Travel Planner

**链接**: https://arxiv.org/abs/2611.25531
**作者**: Amandi Nimasha, Oshadha Wijerathne, Dushan Fernando, Nisansa de Silva, Srinath Perera
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [19] LLM-ACES: Closed-Loop Discovery of Dynamical Systems with LLM-Guided Adaptive Search

**链接**: https://arxiv.org/abs/2606.25039
**作者**: Nikhil Abhyankar, Sha Li, Sanchit Kabra, Naren Ramakrishnan, Yulia Gel, Chandan K. Reddy
**来源**: cs.LG cs.AI cs.CL math.DS
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [20] FOL-Proof: Verifying LLM Text-to-Logic Translations via Deterministic Semantics

**链接**: https://arxiv.org/abs/2611.33078
**作者**: Yisrael Clark, Guy Katz
**来源**: cs.CL cs.LO
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) are increasingly used to translate natural-language statements into first-order logic (FOL) to improve reasoning. However, LLMs are prone to errors, and so a semantically unfaithful FOL formula could corrupt downstream reasoning. We present FOL-Proof, a semantic firewall pipeline that validates LLM-generated FOL translations against independently derived linguistic interpretations. FOL-Proof operates by deterministically obtaining a pool of candidate translations via semantic analysis tools, such as the English Resource Grammar and Minimal Recursion Semantics; then applying an SMT solver to check each derived reading for logical equivalence to the LLM-generated formula. If the translation is faithful it is accepted; otherwise, it is rejected, or optionally repaired via repeated invocations to the LLM. The procedure is conservative: incomplete search, unsupported constructions, or inconclusive checks yield abstention rather than false rejection. We evaluated

---

### [21] PromptSMC: Enabling Particle Exploration in Flow Matching via LLM-Based Prompt Rejuvenation

**链接**: https://arxiv.org/abs/2611.31471
**作者**: Wenyi Lian, Zheng Zhao, Thomas B. Sch\"on
**来源**: cs.CV
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> This paper is concerned with prompt-image alignment at inference time through exploration of generative trajectories and dynamical prompt rejuvenation. We leverage sequential Monte Carlo (SMC), to offer a gradient-free and principled framework for this purpose through reward-guided trajectory selection. More specifically, we introduce LLM-based prompt rejuvenation, allowing for efficient particle exploration in SMC samplers along the diffusion time in flow matching models. The proposed method, PromptSMC, retains the selected latent states and uses a pretrained LLM to dynamically revise the prompts of duplicated particles under semantic-preservation constraints. These revised prompts induce alternative conditional velocity fields, allowing particles to explore different continuations from a shared intermediate state. The method further uses a reward model to evaluate each particle's alignment with the original prompt, and the resulting scores guide particles through resampling. PromptSM

---

### [22] mini-psych-agent: Evaluating Human-Like Behavior in LLM Agents through Interactive Psychological Environments

**链接**: https://arxiv.org/abs/2611.30365
**作者**: Yi-Fei Cao, Tianxin Huang, Hanbo Xie, Jian-Qiao Zhu
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [23] LUCID: Statistically Grounded Self-Correction for LLM Reasoning Evaluation

**链接**: https://arxiv.org/abs/2611.31595
**作者**: Satiyabooshan Murugaboopathy and Adel Daoud and Connor T. Jerzak
**来源**: cs.CL cs.LG stat.ME
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Cheap language-model raters grade chain-of-thought reasoning at scale, yet systematic step-rating errors can skew reasoning audits and solution rankings. We introduce LUCID (Loop for Unbiased Calibration via Inference-time Diagnosis), which pairs prompt self-correction with Design-based Supervised Learning (DSL). Without retraining or weight access, LUCID calibrates binary step ratings by aligning predicted and expert soundness rates. From a small expert-labeled set, LUCID summarizes rater bias in plain text and prompts the rater to re-grade unseen steps. For example, on PRM800K, GPT-5-mini grades too strictly, under-rating computation, verification, and late-trace steps most acutely. In one pass, LUCID shrinks GPT-5-mini's calibration gap from 7.8 to 0.9 percentage points in absolute predicted-expert rate difference. LUCID also halves false alarms (sound steps rated unsound) and lifts error-detection F1 on unsound steps by 32%. LUCID retains these gains with 1,000 diagnostic steps or 

---

### [24] Emergence of Reputation-Based Cooperation in LLM Agents

**链接**: https://arxiv.org/abs/2608.04507
**作者**: Kazuya Horibe, Kenji Itao, Wataru Toyokawa
**来源**: cs.MA cs.NE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [25] Review Arcade: On the Human Alignment and Gameability of LLM Reviews

**链接**: https://arxiv.org/abs/2605.28897
**作者**: Hans Ole Hatzel, Sebastian Steindl, Jan Strich
**来源**: cs.AI cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [26] ResCom: Activation Residual Compensation for Large Language Model Quantization

**链接**: https://arxiv.org/abs/2610.35955
**作者**: Ning Yang, Bohan Cui, Zhuowen Liu, Yuting Wang
**来源**: cs.LG cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [27] "The explanation makes sense": An Empirical Study on LLM Performance in News Classification and its Influence on Judgment in Human-AI Collaborative Annotation

**链接**: https://arxiv.org/abs/2602.19690
**作者**: Qile Wang, Prerana Khatiwada, Avinash Chouhan, Ashrey Mahesh, Joy Mwaria, Duy Duc Tran 等 (8 人)
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [28] Leaks by Installments: Cross-Session Answer Disclosure in LLM Tutors and a Ledger-Based Defense

**链接**: https://arxiv.org/abs/2611.31429
**作者**: Venkata Muttineni, Karthik Narayan, Christopher David
**来源**: cs.CR cs.AI cs.CL cs.CY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tutors built on large language models (LLMs) are told not to give away answers, but a learner does not have to ask for the answer all at once. Existing safeguards judge each reply within the current conversation, so a learner can open a new session, reword the problem, or request a worked solution to the same problem with different numbers. We call this cross-session disclosure and propose a defense: a persistent, per-learner disclosure ledger. For every problem a learner brings, the system builds a typed solution graph. Before a reply is released, a gate matches the reply's own content, not the learner's wording, against the ledger by result values and by type-labeled solution structure, then computes which steps the learner could now derive. The reply is withheld if that set reaches the final answer or exceeds a budget. In a simulation of 3,000 problems, the ledger reduced leakage through renumbered practice variants from 100% to 10.6% while honest learners completed 94-99.5% of prob

---

### [29] LLM Agent Authorization Across Context Compaction

**链接**: https://arxiv.org/abs/2611.32194
**作者**: Zeming Fei, Hongming Fei, Yi Xu, Xiaoyang Wang, Ying Zhang
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Request-derived authorizers such as Progent protect LLM agents from prompt injection by deriving what an agent may do from the user's request. Their guarantee rests on attribution: the request is taken to be what the user said. Compaction breaks it. At every automatic compaction we observed, Claude Code and Codex placed a model-written summary of earlier turns as a user message, so the compactor's quotation of the user, documents and injected text reads as the user speaking. Because a policy frozen at the first request lets the agent finish few later tasks, we let Progent derive its policy for each request, and find that what it grants then follows what the compactor wrote. Even a payee the user stated is not safe: when an attacker's notice states another account as plain data and the user asks to pay the rent, the policy derived from a frontier compactor's summary admits the notice's account in 91% of cases, and the one derived from the user's own words in none. The cause is general: 

---

### [30] CAPTA: Identifying LLMs Behind AI Agents

**链接**: https://arxiv.org/abs/2611.32686
**作者**: Kailun Yan, Yue Huang, Sisi Duan
**来源**: cs.AI cs.CR
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM)-based agents access remote services through tools to complete user tasks, often via API calls. In this setting, a remote service may want to identify the backend LLM of an agent to launch model-specific attacks, including prompt injection or selective delivery of manipulated content. However, the service cannot directly query the backend model and must instead collect observable responses through its interactions with the agent, making identification challenging. In this paper, we present Completely Automated Preference Test to tell LLMs Apart (CAPTA), a model identification approach inspired by CAPTCHA (Completely Automated Public Turing test to tell Computers and Humans Apart), which distinguishes humans from automated programs. CAPTA presents multiple-choice questions as verification challenges, using differences in models' selection preferences to identify the backend LLM. It selects questions based on cross-model option-generation diversity and uses LLM-

---

### [31] Fresh Keys, Stale Secrets: Numeric Leakage across Linked LLM Prompts

**链接**: https://arxiv.org/abs/2611.32864
**作者**: Jian Li, Qinglin Zhao, Shuoyao Wang, Jincheng Cai, Zhifeng Hao, Naiqi Wu
**来源**: cs.CR cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Small businesses repeatedly ask cloud language models about the same confidential prices, unit costs and margins. Numeric prompt disguises for such numbers are evaluated one prompt at a time, but a provider sees a firm's history, in which each fresh secret gives a new, independent view of the same numbers. Since real costs are not public, we measure on synthetic firms with known values how much an honest-but-curious provider recovers when it knows the disguise algorithm, holds sector-level price and margin statistics, and links a firm's queries. In one prompt, per-field scaling, a fixed-axis instantiation of Zhang et al.'s order-preserving substitution and Pr$\varepsilon\varepsilon$mpt's released sanitizer keep the attacker's margin-hit advantage over a prior-only guess between -0.6 and +4.4 percentage points. After 16 linked queries with fresh secrets, every disguise we test (Pr$\varepsilon\varepsilon$mpt at $\varepsilon\geq 0.5$) has a target recovered significantly more often: under

---

### [32] ReTRACE: Feedback-Guided LLM Agent in a Chemistry Harness for Retrosynthesis Planning

**链接**: https://arxiv.org/abs/2610.24744
**作者**: Jinxiang Xie, Yijian Zhang, Qingyuan Yi, Jianyi Wang, Hao Dong
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [33] Social Interaction Breaks Replicate Independence in Controlled-Clone LLM Agents

**链接**: https://arxiv.org/abs/2611.29581
**作者**: Yandan Zheng, Haoran Luo, Anh Tuan Luu
**来源**: cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [34] Unjamming Deferrals: Supporting Students Through JAMN Bot, a Mobile RAG-Grounded Policy Assistant

**链接**: https://arxiv.org/abs/2611.32266
**作者**: Mark Farinas, Alesandra Garcia, Maria Reyes, Jethro Nueva, Nawaf Qureshi, Mahmoud Elsaadany 等 (7 人)
**来源**: cs.CL cs.CY cs.IR
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In some educational institutions, workflows such as the exam deferral process can be slow, inconvenient, and inconsistent, which creates the need to implement novel digital systems. This paper presents Schedulater, a mobile app for managing university exam deferrals. JAMN Bot is a Large Language Model (LLM)-powered chatbot integrated into Schedulater that provides context-aware support to help users understand the deferral process. The system features a Retrieval-Augmented Generation (RAG) pipeline using Ollama (Llama 3.2 3B) for self-hosted inference which enables policy-grounded responses without sacrificing privacy. We evaluate the system using a 43-item benchmark spanning Exam Deferral, Privacy, Scheduling, Cross-Policy, and Adversarial & Out-of-Scope questions, and report inter-rater agreement among our human evaluators alongside retrieval hit-rate metrics. Subsequently, we utilize an LLM-as-a-judge approach with GPT-5.4, revealing slight-to-moderate alignment with our raters that

---

### [35] RecurSciBench: Benchmarking Recursive Self-Improvement in Data-Driven Scientific Research

**链接**: https://arxiv.org/abs/2611.32508
**作者**: Wenxi Xu, Chuan Qin, Zihan Wang, Zixing Chen, Le Zhang, Jingbo Zhou 等 (9 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM)-based agents are advancing the automation of data-driven scientific research. Recent advances in recursive self-improvement (RSI) offer the potential for these agents to continuously improve through experience, but evaluating transfer across scientific tasks requires executable, scientifically verifiable tasks and independent assessment of self-improvement gains. We introduce RecurSciBench, a scalable benchmark for evaluating RSI in data-driven scientific research. Its RecurSciPipe framework automatically constructs scientific modeling and data analysis tasks from raw datasets, with execution-based verification and scientific validity checks. RecurSciBench spans four scientific domains, multiple data modalities, and varied scientific objectives. We evaluate four RSI systems by comparing their initial and evolved states on independent tasks after evolution on source tasks, covering within-type, cross-type, and cross-domain transfer. Experiments show that the b

---

### [36] DUALingo: A Dual-Hand Instruction-Guided Dataset for Affordance Grounding on 3D Objects

**链接**: https://arxiv.org/abs/2611.31919
**作者**: Ming-Lun Lee, Yi-En Li, Feng-Dian Su, Ming-Han Lee, Kun-Ru Wu, Krzysztof Czarnecki 等 (7 人)
**来源**: cs.CV cs.RO
**匹配关键词**: Foundation Models, LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Affordance grounding localizes where an agent should interact with an object to perform a task. Many everyday manipulation tasks, however, require bimanual affordance, in which two hands assume complementary and cooperative roles to accomplish a shared goal. Existing 3D affordance datasets primarily ground single interaction regions, and manually annotating dual-hand, cooperative contacts does not scale. To address this gap, we introduce DUALingo, a large-scale dataset for task-conditioned, role-aware bimanual 3D affordance grounding on diverse everyday objects. DUALingo represents each task as two cooperative, hand-agnostic roles, each grounded as a heatmap on the object surface. It contains 271K free-form tasks on 71K objects, generated by a fully automated pipeline of open-weight foundation models without human labeling. Expert ratings and a validated LLM judge confirm the quality of the resulting annotations. Trained on DUALingo, existing 3D affordance models learn to ground both c

---

### [37] The Date You Didn't Set: The System-Prompt Date as a Hidden Variable in LLM Evaluation

**链接**: https://arxiv.org/abs/2611.31254
**作者**: Noureldin Zahran, Mohammed E. Fouda, and Khaled N. Khasawneh
**来源**: cs.CL cs.AI cs.CR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The system prompt of many instruction-tuned models carries a date, usually today's, filled in automatically for conversational and agentic requests alike, so an unchanged evaluation can send a different prompt each day. In this paper, we explore how much this hidden input changes evaluation outcomes. Across six instruction-tuned models and four benchmarks, with prompts, decoding, and configuration fixed, every model is affected: two plausible dates (2024--2026) switch a median $6.6\%$ of test items between correct and incorrect. Even rerunning the evaluation one day later flips about as many items as changing the batch size, although nothing in the setup was changed. In addition, using a grammar-constrained variant of Greedy Coordinate Gradient (GCG) to search dates of any year, we find dates that cost the Llama-3.x models up to $36.5$ points of held-out accuracy. Beyond accuracy, switching to another plausible date alters LLM-judge verdicts and undoes $15$--$32\%$ of reproduced jailbr

---

### [38] scOPD: Routed On-Policy Self-Distillation for LLM-Based Single-Cell Annotation

**链接**: https://arxiv.org/abs/2611.31257
**作者**: Zhiyin Yu, Yuchen Mou, Songtao Huang, Shuaiyu Zhang, Xing Wei, Chunchun Chen 等 (10 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Motivation: Large language models (LLMs) have shown promise for single-cell annotation, but existing training methods mainly rely on scalar outcome rewards that provide limited supervision for intermediate biological reasoning. Batch-level annotation is particularly challenging because it requires jointly resolving local cell identities and a global one-to-one matching constraint, such that one local error can affect the entire assignment. Moreover, a single inference pass provides insufficient evidence for locating uncertain predictions. These limitations call for fine-grained reasoning supervision during training and uncertainty-aware refinement during inference. Results: To address these challenges, we propose scOPD, an on-policy self-distillation framework for LLM-based single-cell annotation. After reasoning fine-tuning, scOPD adaptively routes qualified rollouts to reward-based optimization, while erroneous rollouts receive privileged token-level supervision from successful sibli

---

### [39] BabelArena: A Large-Scale Multilingual Benchmark for LLM Agents

**链接**: https://arxiv.org/abs/2609.23490
**作者**: Peng Kuang, Yuchun Fan, Jiangnan Li, Minghao Wu, Jialong Tang, Hao-Ran Wei 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [40] Leto: Utility-Centric Agent Memory

**链接**: https://arxiv.org/abs/2611.33005
**作者**: Shuguang Chen and Salman Paracha
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents rely on external memory to retain and reuse information across interactions. Existing memory systems treat memory as a record of the past and evaluate it by fidelity to the conversation. However, the value of memory lies in whether it improves the agent's response. A memory system decides what to memorize and what to serve before that response exists, and fidelity checks neither decision against it. Faithful memory can therefore fail to improve the response. We instead view memory as a prediction problem and present \textbf{\emph{\leto{}}}, a memory system for LLM agents that focuses on the utility of memory to the future rather than on its fidelity to the past. Because future requests are unknown, \emph{\leto{}} preserves access to conversation details through memory indexing, allowing information to remain available through its sources. When a request arrives, memory replay draws on this index to anticipate and supply the context the agent needs beyo

---

### [41] No Fixed Configuration Is Best: Context- and Cost-Aware Tuning of LLM Pipelines, with an Application to Schema Matching and Mapping

**链接**: https://arxiv.org/abs/2611.31864
**作者**: Gokhan Kirlik, Xiuwen Zheng, Anirudh Sriram
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The numeric settings of a multi-stage LLM pipeline (a compound AI system) are the usual target of tuning. We tuned all of them for an LLM pipeline for schema matching and mapping, with accuracy and cost as joint objectives, and we show what this buys, what it cannot buy, and where the remaining accuracy is. First, tuning buys cost and a little accuracy. On 35 tasks, with whole groups of tasks held out from tuning, one tuned configuration gains 2.9 points of top-1 accuracy (HR@1) over the default at 18% more cost, and another keeps the accuracy of the default at 32% lower cost. Second, the accuracy depends on a choice that numeric tuning cannot reach. Restricting the search for each source column to one assigned target table changes HR@1 by +30 points on a MIMIC-III to OMOP task and by -52 points on a task built from database views, more than numeric tuning gains on nine of ten test tasks. Neither setting is right for all tasks: on the larger set of 41 tasks used for the remaining resul

---

### [42] LEGOSpec: A Composable and Efficient Framework for Speculative Draft Design and Training

**链接**: https://arxiv.org/abs/2611.33004
**作者**: Hanzhen Wang, Jiaming Xu, Guohao Dai
**来源**: cs.LG cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Speculative decoding accelerates large language model (LLM) generation using a lightweight draft. Existing methods evaluate complete recipes under different training configurations, leaving component effects, interactions, and composition benefits unclear. Therefore, we present LEGOSpec, a composable framework for speculative draft design and training. LEGOSpec decomposes draft models into Context, Backbone, Proposal, and Objective components that share a unified training infrastructure. Using LEGOSpec, we systematically vary components and evaluate selected combinations under matched training conditions to isolate their effects and interactions. These experiments reveal three findings: (1) Different workloads favor different backbones, depending on context length and memory budget, with within-block dependency modeling particularly important for long contexts. (2) Proposal design must balance acceptance and latency. (3) The training objective should match token distributions locally a

---

### [43] LLM Genetic Feature Engineering

**链接**: https://arxiv.org/abs/2611.31277
**作者**: Jonathan Thompson, Razvan Stefanescu, Manoj Varma Namburi, and Liuxia Wang
**来源**: cs.NE cs.AI cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Feature Engineering is the (traditionally manual) process of constructing derived variables from an existing dataset by combining, transforming, or otherwise manipulating the original data fields to reduce statistical noise and extract meaningful, domain-specific quantities of interest from the raw dataset. Recent work demonstrates promising progress toward the au tomation of this process through the integration of large language models (LLMs) and various metaheuristics to guide the search for useful features. We build on this approach by introducing a novel genetic algorithm that implements selection, crossover, and mutation at the individual feature level, rather than at the level of the entire engineered feature set. In doing so, we enable in-process statistical analysis of newly-generated features, thereby enabling the genetic algorithm to simultaneously integrate individual and group-level feature metrics into its selec tion process. We demonstrate this capability using state-of-t

---

### [44] AutoXRD: Autonomous Large Language Model Agents and Comprehensive Evaluation for Powder X-Ray Diffraction Analysis

**链接**: https://arxiv.org/abs/2609.00070
**作者**: Yuetong Wu, Maojun Sun
**来源**: cond-mat.mtrl-sci cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [45] Does Research-Paper Context Improve LLM-Generated Quadruped Navigation? An Exploratory Simulation Study

**链接**: https://arxiv.org/abs/2611.32381
**作者**: Barnabas Juhasz, Rolf Pfister
**来源**: cs.RO cs.AI cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models can write competent robot navigation code, but not only does the research on the topic advance, a model may also, due to the volume of findings, fail to recall relevant findings and apply them to the task at hand. In this work, we test whether providing particular research papers as context improves the LLM-written navigation code for the Go2 quadruped, with the LLM (Claude Opus 5) and locomotion policy frozen. Specifically, we compare the navigation controllers the LLM writes when provided with and without particular papers across three settings: behavior trees, navigators edited from a shared base, and controllers written from scratch. When a maze's shortest route is blocked mid-episode, 2 of 8 controllers written with the context of an incremental-replanning paper complete all four trips under Isaac Sim physics, against 7 of 8 without it (two-sided Fisher's exact test, p = 0.041). This difference appears only under physics: in an idealized kinematic simulator, 

---

### [46] HiCal: Offline Calibration for Hierarchical Scale Encoding in Accurate HiF4 Quantization

**链接**: https://arxiv.org/abs/2611.32624
**作者**: Zhiyuan Zhang, Yanzhao Li, Hui Dong, Sifan Cheng, Mingen Zheng, Hui Wang
**来源**: cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Block floating-point (BFP) quantization is widely adopted for efficient low-bit large language model (LLM) inference, where the choice of block scales plays a critical role in quantization accuracy. HiFloat4 (HiF4) employs a hierarchical scale encoding scheme consisting of a global E6M2 scale and two levels of binary scale extensions. However, its conventional rounding rule and fixed scale extension thresholds may not fully capture the statistical characteristics of the quantized tensors in practice, leading to suboptimal scale representations. In this work, we propose HiCal, an offline calibration approach that improves HiF4 quantization accuracy by refining the encoding decisions across all three scale levels. Specifically, we introduce a calibrated rounding bias for the Level-1 E6M2 scale and optimize the scale-extension thresholds at Levels 2 and 3 based on the empirical distributions of local group magnitudes. The resulting calibration parameters are determined offline and remain 

---

### [47] Eliciting sandbagged LLM capability via structural interventions on attention-head functional networks

**链接**: https://arxiv.org/abs/2611.31615
**作者**: Manzi Fabrice Niyigaba, Ishan Verma Prasad, Sansheng Cao, Zheng Huang, Yujun Yan
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reliably evaluating the capabilities of advanced AI systems is critical for safe development and deployment, yet such evaluations may be undermined by sandbagging, a situation in which a model strategically suppresses capabilities it possesses. Existing work has developed controlled sandbagging settings and methods for detecting or eliciting hidden capabilities, but comparatively little is known about how a model's internal neural computation changes when its capabilities are suppressed. In this work, we study sandbagging through the lens of internal functional organization. Inspired by network neuroscience, we construct functional graphs from attention-head activations and compare their organization under honest and sandbagging conditions while holding the model architecture and weights fixed. Surprisingly, across model architectures and community detection methods, we find a consistent structural signature in which sandbagging is associated with reduced functional connectivity within

---

### [48] U-Statistics-Powered LLM Reasoning

**链接**: https://arxiv.org/abs/2611.33064
**作者**: Shijin Gong, Kai Ye, Victor Chernozhukov, Xinyu Zhang and Chengchun Shi
**来源**: cs.LG stat.ML
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Since its introduction by DeepSeek, group relative policy optimization (GRPO) has been widely adopted for training large reasoning models and agents, spurring a proliferation of its variants. Yet the group size, a crucial hyperparameter in these GRPO-type algorithms, remains largely chosen by trial and error. Exploiting the U-statistic structure of GRPO's policy gradient, we recast the selection of the group size as a classical statistical problem of variance ratio estimation. This problem is particularly challenging when the denominator of the ratio is small, rendering naive plug-in estimators unstable. To address this challenge, we propose a pessimistic ratio estimator that accounts for the denominator's estimation uncertainty. We characterise the statistical properties of this estimator across three sample-size regimes. Empirically, using %a jackknife-based pessimistic rule on synthetic tasks from Reasoning Gym and real-world benchmarks covering both mathematical reasoning and code 

---

### [49] C3H: Compression-to-Consensus Criteria Hijacking in Multimodal LLM Recommender Systems

**链接**: https://arxiv.org/abs/2611.32780
**作者**: Guowei Guan, Yurong Hao, Jiaming Zhang, Fuyao Zhang, Wei Yang Bryan Lim
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal large language models (MLLMs) are transforming recommender systems into content-aware decision systems. In these systems, multimodal compression and cross-modal fusion are often viewed as robustness-enhancing mechanisms against content manipulation, as compression can filter noisy signals and cross-modal consensus can suppress inconsistent anomalies. We challenge this assumption by showing that the same process can expose a compression-to-consensus (C2C) bias in ranking decisions. Signals that remain salient after compression and receive consistent support across modalities can gain disproportionate influence in candidate comparison, offering an exploitable direction for content manipulation. In this paper, we introduce C3H, a novel inference-time attack that exploits this vulnerability. Rather than relying on noisy perturbations or training-time poisoning, C3H promotes a target item by tailoring its multimodal content to align with the decision criteria implicitly expressed

---

### [50] Towards Realistic Evaluation of Uncertainty Quantification for LLM-Based Recommender Systems

**链接**: https://arxiv.org/abs/2611.33036
**作者**: Hao Wu, Sipeng Chen, Weikai Li, Tianyi Chen, Qiancheng Yang, Hang Zhou 等 (9 人)
**来源**: cs.IR cs.CL cs.LG stat.ML
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) provide a flexible interface for recommendation systems. However, their issued rankings require reliable instance-level uncertainty monitoring. In this scenario, comparing uncertainty quantification (UQ) methods becomes challenging because LLM rankers lack a standard item-classification head. Their scores may depend on option labels, prompts, generation procedures, and the available user and item evidence. Existing methods derive uncertainty from different sources and apply it at different stages of the recommendation process. Some methods evaluate an issued ranking, whereas others use uncertainty to change the ranking itself, making direct comparison difficult. Here we introduce a fixed-ranking benchmark which evaluates eight heterogeneous UQ signals as record-level monitors under a shared output contract. We evaluate these signals across four recommendation datasets and two LLM backbones under a shared fixed-ranking protocol. From the results, we draw thr

---

### [51] BEAVER: An Efficient Deterministic LLM Verifier

**链接**: https://arxiv.org/abs/2512.05439
**作者**: Nalin Wadhwa, Tarun Suresh, Debangshu Banerjee, Gagandeep Singh
**来源**: cs.AI cs.FL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [52] The Ephemeral Cost of Switching Optimizers Across LLM Training Stages

**链接**: https://arxiv.org/abs/2610.22650
**作者**: Xinyu Zhao, Davis Wertheimer, Ashutosh Sharma, Rameswar Panda, Paul Pu Liang
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [53] RegimeCouncil: Paired-Evidence Routing For Memory Conflict Governance In LLM Agents

**链接**: https://arxiv.org/abs/2611.22113
**作者**: Qingcan Kang, Mingyang Liu, Shixiong Kai, Tao Zhong, Mingxuan Yuan
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [54] When Better Codebooks Are Not Enough: Predictive Performance and Rule Adherence in LLM Political Event Coding

**链接**: https://arxiv.org/abs/2606.06781
**作者**: Zixian He, Bharath Raahul Murugesan, Patrick T. Brandt, Yibo Hu
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [55] The Control-Flow Tax: Specialized Decision Routing for LLM Agent Workflows

**链接**: https://arxiv.org/abs/2611.32365
**作者**: Zhikai Cheng (Talkdesk), Shuanghu Wang (Talkdesk), Li Jiang (Talkdesk)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> An agent can spend almost as much deciding what to do as doing it. In our documentation workflow, control-flow routing accounts for 42.5% of baseline reference cost on the initial task. Lower token prices alone do not solve this control-flow tax: inexpensive general-purpose routers can trigger additional calls to the expensive generator. We evaluate a heterogeneous architecture in which Jev, a specialized System 1 decision model, controls finite actions while Sol generates documents. Across four software tasks, 480 valid runs comprise 470 completions and ten request-limit endpoints. Jev full routing achieves the lowest mean cost and elapsed time on every task, completing all 40 specialist-controlled runs along the shortest trajectory. On the initial task, mean cost falls by 49.6% (95% paired-bootstrap interval: 42.9% to 56.3%) and elapsed time by 33.2% (19.6% to 46.7%). Across three further tasks, cost reductions are 40.5% to 42.9% and concurrent elapsed-time reductions are 12.9% to 14

---

### [56] Exploring Multi-Player Social Games as Verifiable Training Grounds for Large Language Models

**链接**: https://arxiv.org/abs/2611.31821
**作者**: Keyu He, Michael Li, Jiarui Liu, Mingqian Zheng, Koichi Onoue, Tongshuang Wu 等 (7 人)
**来源**: cs.CL cs.AI cs.LG cs.MA
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The training of socially intelligent language models often relies on large language model (LLM) judges, which are expensive, noisy, and vulnerable to reward hacking. Multi-player social games offer a natural alternative: they require open-ended communication to coordinate with teammates and infer hidden roles, while their rules provide an objective outcome which can serve as a verifiable reward for training. Using three social games, we explore how much social intelligence Qwen3 models can acquire through supervised fine-tuning (SFT) and reinforcement learning with verifiable rewards (RLVR). Results show that against a much stronger Gemma-3-27B model, SFT and RLVR raise the win rate of Qwen3-4B from 33% to 81% on the three trained games, and from 39% to 54% on three additional held-out games. In contrast, in-context strategies such as prompting improve the win rate of Qwen3-4B by only about 6 pp across the same games we train and evaluate on. Furthermore, we show that the gains from SF

---

### [57] SwarmLeak: Does Coordination Improve Privacy Attacks on LLM Agents?

**链接**: https://arxiv.org/abs/2611.31791
**作者**: Asma Farajidizaji, Vyas Raina, Vatsal Raina, Ivaxi Sheth
**来源**: cs.CR cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents increasingly collaborate in group chats while holding tool access to confidential records, which makes the shared chat an attack surface. It remains unclear whether several colluding attackers extract such information more effectively than one. We introduce SwarmLeak, a red-teaming dataset of 24 synthetic group-chat scenarios across healthcare, law, finance, and software engineering, where attackers pose as colleagues to make a victim agent post protected fields despite an explicit confidentiality policy. With GLM 5.2 attacking five victim models through seven conversational strategies, we compare one attacker with a swarm of four sharing a private channel, matching scenarios, strategies, and a 200,000-token budget that also covers swarm coordination. Swarms show no advantage: a single attacker matches or exceeds them on every victim, and the share of runs leaking any field differs between conditions by at most 14.3 percentage points, whereas changing the victim shifts it fr

---

### [58] Reproducible Social Structure Emerges From Free-Form Interaction Among LLM Agents

**链接**: https://arxiv.org/abs/2611.31543
**作者**: Tom Alisch, Sonia Murthy, Robert Hawkins, Felix Sosa, Core Francisco Park
**来源**: cs.MA cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-agent LLM simulations are increasingly used as models of social systems, but most published findings are anecdotal, i.e., drawn from a single run. It is therefore unclear which observed phenomena are robust findings of the simulated system itself, and which were random events in one particular run. Here, we introduce a repeatable, goal-free, proactive multi-agent framework in which fifty persona-conditioned agents with persistent memory choose whether, with whom, and how to communicate across three social platforms. The framework supports non-perturbative measurements across temporal snapshots and repetitions. Running the same world ten times from identical initial conditions for a total of 700 hours, we find that most measured network- and agent-level parameters are stable across repetitions. Throughout a run, initially broad communication contracts into sparse sustained dyads in all ten worlds. Importantly, we find that many identical dyads re-form across worlds significantly m

---

### [59] SALSA: Sampling Adversarial Suffixes from Learned Distributions for LLM Safety Assessment

**链接**: https://arxiv.org/abs/2611.33030
**作者**: Shivank Rajput, Himanshu Singh, A. V. Subramanyam
**来源**: cs.CL cs.CR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) remain vulnerable to jailbreak attacks, where adversaries append optimized suffixes to otherwise benign looking prompts to bypass safety alignment. Existing optimization-based GCG-style attacks can be effective, but they are expensive at inference time, and suffer from poor transfer. We present, SALSA, a generative framework that learns a distribution over jailbreak suffixes from optimization-derived attack corpora. Once trained, the model supports efficient sampling-based attacks. On open-source targets, it achieves attack success rates comparable to state-of-the-art optimization baselines, while reducing generation time from 3.46s to 0.04s per prompt. In black-box transfer, it remains highly effective against proprietary systems, including 99% ASR on GPT-3.5-Turbo, and reaches 45% ASR on the substantially harder GPT-4o, more than doubling the strongest baseline at an equal sampling budget. We further offer an intuition for why generative sampling can pres

---

### [60] AIChipBench: Benchmarking LLM Agents for Automated AI Accelerator Design

**链接**: https://arxiv.org/abs/2611.33093
**作者**: Guangyuan Wang, Chengran Li, Minchen Luo, Jichen Feng, Mengdi Wang, Yifan Zhang
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A language-model decoder carries state between decoding steps, and in hardware a wrong state update can leave the current token correct and corrupt the output several tokens later, so a design can pass output tests and still be wrong. AIChipBench asks what LLM coding agents need to build such hardware correctly. Agents implement quantized Qwen3.5, Gemma 3, Gemma 4, and Llama 3.2 decoders in synthesizable register-transfer-level (RTL) code against an executable integer reference that specifies the outputs and the stored state at every decoding step. They debug against public tests under fixed budgets; their frozen designs are graded on held-out token sequences, resets, memory stalls, and synthesis, and a second track asks them to speed up a correct design at nearly fixed area. Across 9,136 attempts by four coding agents, the difficulty lies in stored state. Feedback that points to the first state mismatch raises acceptance over output-only feedback in all 12 agent--task cells of a match

---

### [61] Learning Compact State Abstractions for LLM Agents

**链接**: https://arxiv.org/abs/2611.31800
**作者**: Yaswanth Chittepu, Raghavendra Addanki, Anup Rao, Branislav Kveton, Scott Niekum
**来源**: cs.LG cs.AI cs.CL cs.NE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents commonly use the full interaction history as a proxy for state, retaining all past observations and actions regardless of whether they remain relevant. We instead ask what information an agent actually needs to carry forward. We define agent state as a compact abstraction of interaction history that preserves the competence of a fixed reference agent, with the minimal such abstraction as the ideal. Because matching the reference agent's behavior is unnecessarily restrictive and difficult for black-box policies, we define sufficiency through task performance rather than behavior matching. We represent state abstractions as deterministic recursive programs and search over them using an LLM-guided genetic algorithm. Across ALFWorld and ScienceWorld, the learned abstractions preserve near-reference task success while reducing mean policy input by up to 71% and 57%, respectively. The resulting programs are directly inspectable, providing an explicit account of what information is

---

### [62] MixFold: Sub-4-Bit Mixed-Precision LLM Inference via Output-Channel Grouping on Mobile NPUs

**链接**: https://arxiv.org/abs/2611.26976
**作者**: Vinnam Kim, Seong Hoon Seo, Junhan Kim, Jaeseong You, An Chen
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [63] fork() for Agents: Agent Kernel for Non-blocking LLM Orchestration

**链接**: https://arxiv.org/abs/2611.31727
**作者**: Ankit Chadha and Pratyay Banerjee
**来源**: cs.CL cs.DC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based agents typically execute tool calls synchronously and discard completed work upon failure. Subgraph-selective recovery, re-executing only a failed node's transitive descendants, is a well-established pattern in distributed systems (Spark, Erlang/OTP, Dryad), and recent agent runtimes (Sherlock, AgentGit, Atomix) preserve completed work through verifiers, version control, or transactional tool boundaries. We present \textbf{Agent-Kernel}, a non-blocking runtime that ports this pattern to the LLM \emph{content plane}: its primitive, \textbf{Sub-Graph Recovery (SGR)}, fires on a raw exception with no trained verifier or planner, resets a failed node's descendants while preserving completed siblings, and composes each parent's text into its children's prompts (context inheritance), all on a durable substrate with a formal state-preservation guarantee. Across 14{,}434 runs on synthetic and standard benchmarks (tau-bench, Gaia2, AutomationBench, InterruptBench), SGR reaches full re

---

### [64] A Few Teacher Steps Go a Long Way: Efficient SFT Data Collection for LLM Agents

**链接**: https://arxiv.org/abs/2607.04574
**作者**: Junze Ye, Jiayi Cheng, Miao Lu, Michal Mankowski, Jose Blanchet, Mohsen Bayati
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [65] When Exact Token Importance Is Not Enough: Limits of Top-K Selection in LLM Attention

**链接**: https://arxiv.org/abs/2611.32324
**作者**: Irmaan Mirzanejad
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-context language models often retain only a limited set of past token positions for an attention query. A common strategy scores positions individually and keeps the highest-ranked K. Yet attention weights are renormalized over the chosen set: two individually important positions need not form the best pair. We ask whether independent ranking suffices even when each importance score measures the exact downstream change in next-token predictions caused by deleting that position alone. It does not. A four-position construction makes the ranked pair incur 133.2 times the Kullback-Leibler (KL) divergence of the optimal pair, and a parametric family proves that this multiplicative gap is unbounded. An exact exchange identity and preference reversals for every K >= 2 explain the interaction. In exhaustive frozen-model audits of SmolLM2, Gemma, and Qwen, exact-singleton Top-4 leaves at least 10% relative improvement within a fully enumerated 24-position candidate pool in 55/60, 49/60, an

---

### [66] DAiSy: Online Data Selection by Adaptive Utility Estimation for LLM Pretraining

**链接**: https://arxiv.org/abs/2611.32294
**作者**: Simin Fan, Martin Jaggi
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Model-aware online data selection prioritizes the training documents that contribute the most given the model's current state. Existing online selectors rank candidates upon gradient-based data utility scores, which requires the full forward-backward pass of the main model on every candidate document. Scoring each document therefore pays as much as training on it, yet only a small fraction is used for the real model update. We introduce DAiSy, a lightweight linear auxiliary model that learns to predict data utility scores from frozen document embeddings, which eliminates the computation overhead and infrastructure burdens. The linear estimator is updated alongside the main language model, fitting to the exact gradient-based utility scores obtained from the backward pass of regular training steps. Consequently, scoring a candidate requires only a linear transformation, bypassing the costly gradient-alignment computation. We demonstrate its effectiveness and efficiency for LLM pretrainin

---

### [67] The interpreter as developer: An autoethnographic design study of building a computer-assisted interpreting tool through human-LLM co-creation

**链接**: https://arxiv.org/abs/2610.16460
**作者**: Zeming Zhao (College of Foreign Languages, Capital Normal University, Beijing, China)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [68] Safe to Omit, Worth Omitting? Keeping the Answer and Cutting Latency When an LLM Agent Skips Another's Message

**链接**: https://arxiv.org/abs/2611.23570
**作者**: Xinyang Li, Chih-Hsuan Yang, Xiaolong Ma, Anjir Ahmed Chowdhury, Vikram Vasudevan, Rajeev Thakur 等 (7 人)
**来源**: cs.LG cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [69] MXFP4 for LLM Inference: Complementary Post-Training Quantization Techniques and Their Interactions

**链接**: https://arxiv.org/abs/2611.32873
**作者**: Natalia Frumkin, Alireza Khodamoradi, Kristof Denolf, Eric Dellinger, Stuart Biles
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent advances in low-precision representation have introduced several microscaling numerical formats for LLM quantization. By sharing a scale factor across groups of 16 or 32 elements, these formats enable aggressive low-precision quantization with minimal accuracy degradation, particularly when combined with modern PTQ algorithms. Their accuracy depends on how the numerical format interacts with rotation, PTQ, and scale selection. We study the composability of PTQ configurations across six LLMs and three microscaling formats: MXFP6, MXFP4, and NVFP4, systematically varying Hadamard rotation granularity, PTQ algorithm, and scale-selection strategy. Our central finding is that effective quantization recipes are format dependent: both MXFP4 and NVFP4 support accurate 4-bit inference, but techniques that benefit one do not necessarily transfer to the other. MXFP4 benefits substantially from rotation and error-correcting PTQ, whereas NVFP4 gains less from rotation, consistent with its fi

---

### [70] Modelling Billingual Learning Through LLM Training: A Critical-Period Exploration

**链接**: https://arxiv.org/abs/2611.32997
**作者**: Uriel Benymon, Tristan Whipps, Armita Ghobadi
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Critical-period accounts of second-language (L2) acquisition suggest that the ability to learn a new language may depend on how easily previously acquired first-language (L1) knowledge can be modified. This exploratory computational study extends a neural language-model approach to critical period effects by examining internal representations rather than behavior. A small two-layer GPT-2 model was trained on English and then on German (a relatively related L2) or Finnish (a relatively distant L2) through either Sequential training or Elastic Weight Consolidation (EWC), which limits change in parameters important for English. Mean-pooled hidden states for 20 held-out probe sentences per language were compared with those of the English-only model using cosine similarity at the embedding layer and two transformer layers after one and two L2 epochs. English similarity remained high in the transformer layers but became negative in the embedding layer. L2 similarity increased in the transfor

---

### [71] Red-Teaming a Sovereign LLM, Its Reasoning and Its Training Stages

**链接**: https://arxiv.org/abs/2611.32710
**作者**: Hatef Otroshi Shahreza
**来源**: cs.CL cs.CR cs.CY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Open-weight large language models (LLMs) are increasingly deployed for applications with sensitive information. We investigate whether confidentiality instructions in system prompt can protect such information. We red-team Apertus v1.5, an open sovereign LLM, and five other model families across six languages and reasoning modes. We use synthetic personal records to evaluate direct disclosure, correction baits, yes/no verification, derived-value queries, reasoning leakage and authorisation checks. We also explore copyright attribution, historical misrepresentation and stereotyping. Despite confidentiality instructions, Apertus 8B and 70B leak information in 96% and 95% of requests, respectively, in correction-bait attacks. Verification and derived-value queries also expose protected information without necessarily revealing identifiers. Moreover, reasoning traces can leak confidential records even when final answers withhold them. Our experiments also show that post-training does not c

---

### [72] Reproducing History Is Not Enough: Intervention-Level Assurance for LLM-Generated Simulators

**链接**: https://arxiv.org/abs/2611.31736
**作者**: Ashraf Abdul-Muumin and Aniruddha Chattopadhyay and Noorbakhsh Golilarz and Kaushik Roy
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models can now write simulation programs of operational processes and workflows. These programs can be reused to answer what-if questions on new records and policies. However, a program that reproduces recorded history can still give wrong answers to what-if questions; requested changes may be applied wrongly, or they may be applied to records other than the ones the question is about, or the program may stop being valid once its policy is revised. Current checks return a pass-or-fail verdict for the whole program, which says little about whether any single answer can be trusted. We propose Vouch, a library that judges whether an answer from a generated simulator can be trusted for the change being asked about. Each what-if question is turned into a structured change, which is checked against the program and the current records. The library also keeps a record of the kinds of change each program has passed or failed, and repeats the relevant tests whenever the program is

---

### [73] Auditing the Judge: Human-Derived Bias Discovery, Quantification, and Mitigation in LLM Judges

**链接**: https://arxiv.org/abs/2611.33065
**作者**: Hamin Koo, Chanjoo Jung, Fangzhao Wu, Jaehyung Kim
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> While Large Language Models (LLMs) are increasingly deployed as automated evaluators in evaluation and training pipelines, their judgements are often affected by systematic biases that conflict with human preferences. Although prior work has identified various biases and proposed methods for detecting and mitigating them, less attention has been paid to using human preferences to inform bias identification and mitigation. Moreover, these approaches rely heavily on pre-discovered bias lists, overlook bias strength, and depend on costly interventions. In this work, we propose HUB-J, an integrated framework based on human-derived bias factors that detects, quantifies, and mitigates biases in LLM-as-a-Judge systems. Our approach leverages human-LLM judgement disagreement cases to automatically discover interpretable bias factors, and utilizes agreement cases to quantify bias strength through controlled input modifications and resulting shifts in model decisions. Finally, building on these 

---

### [74] AhaPro: A Process-level Rebus benchmark for probing Aha moments in LLM reasoning

**链接**: https://arxiv.org/abs/2611.31268
**作者**: Wei Guo, Lang Qin, Yundi Gai, Qinghua Xu, Zhi Wu, Wenjian Ding 等 (9 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Existing research on Aha moments in large language models has largely focused on reflective expressions or final revision outcomes, leaving their role in the visible reasoning process insufficiently characterized. Rebus puzzles encode answers through character forms, spatial arrangements, and homophony. Reinterpreting key details may trigger Aha moments and shifts in the reasoning process and candidate answers. We introduce AhaPro, a process-level benchmark that uses rebus puzzles to examine how models reorganize evidence and revise answers through Aha moments. The framework represents CoT as sequences of candidate answers, evidence, and verification states, using hierarchical metrics to assess conflict detection, state improvement, and subsequent adoption. Across eleven models, we observe frequent failures to adopt better states discovered during Aha moments, alongside adopted revisions that leave state quality unchanged or reduce it. Models also detect conflicts without subsequently 

---

### [75] The Missing Compliance Class: LLM Graders That Collapse Jailbreak Success, and a Free Check

**链接**: https://arxiv.org/abs/2610.24872
**作者**: Ruqiya Bin Safi
**来源**: cs.CR cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [76] Does Item Response Theory Generalize Across Languages? Evidence from Cross-Lingual LLM Benchmarks

**链接**: https://arxiv.org/abs/2611.31261
**作者**: Ruchira Dhar, Qiwei Peng, Anders S{\o}gaard
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The application of Item Response Theory (IRT) for data selection in benchmarks has mostly been limited to monolingual settings. In this work, we ask: how does IRT generalize when the same benchmark is translated across languages? We conduct experiments on Multilingual GSM and Global MMLU, covering over 100 language models and 11 languages. Fitting 1PL, 2PL, and 3PL IRT models per language, we assess cross-lingual consistency of parameters and whether IRT-filtered subsets preserve model rankings across languages: item difficulty emerges as the most stable parameter followed by guessing and then discrimination. A differential item analysis also shows that lack of stability can be tracked to specific items shifting under translation across languages. Our findings suggest IRT-based selection in multilingual settings must be both parameter-aware and item-aware, validating model choice and screening individual items before assuming cross-lingual generalization.

---

### [77] Can LLM-Simulated Respondents Pre-Test Survey Questions? Evidence From Preregistered Prospective Validation

**链接**: https://arxiv.org/abs/2611.31532
**作者**: Sristi Bafna, Mac MacComas, Michael Bader, Kristina Gligori\'c
**来源**: cs.CL cs.HC cs.SI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) can be conditioned to simulate behavioral responses, including survey responses, but it remains unclear whether and how these simulations can support downstream research tasks. Here, we evaluate whether simulated respondents can support pre-testing new candidate survey questions before fielding them, operationalized as prioritizing candidate survey items. Specifically, we rank candidate questions by their mean responses, which can reveal ceiling or floor effects; their variance, which indicates whether responses contain meaningful variation; and differences between subpopulations, which indicate whether questions capture distinctions between relevant groups within a population. We introduce a preregistered, prospective evaluation that commits model predictions before target human responses exist, ruling out memorization of those responses by design. Using two waves of a local survey (2025: N = 1,271; 2026: N = 1,161), we built simulated respondents from 202

---

### [78] Modeling Event-Conditioned Emotional Expression Response with LLM Agents in a Synthetic Social Simulation

**链接**: https://arxiv.org/abs/2611.31851
**作者**: Rebecca Marigliano, Peter Carragher, Kathleen M. Carley
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Emotions are central drivers of human behavior, yet most behavioral models fail to capture their role in shaping perception, decision-making, and collective action. Application areas such as emergency response and public health are especially constrained by the lack of emotion-aware modeling. While large language models (LLMs) are increasingly integrated into agent-based models (ABMs), little work has examined how to endow LLM agents with emotional reasoning or validated their ability to reproduce empirically observed emotional patterns. This study addresses this gap by introducing a hierarchical prompting framework that conditions LLM agents with demographic, psychological, and contextual cues to generate event-conditioned emotional responses to real-world events. We validate the resulting event-conditioned emotional responses against large-scale social media reaction data derived from the Social Science One Facebook URL Shares Dataset, complemented by demographic and personality benc

---

### [79] S\'anchez, Feij\'oo, or Abascal? Speaker Attribution and Ideological Congruence in LLM Personas Reading Posts on X of the Leaders of the Three Main Parties of the 29N General Election in Spain

**链接**: https://arxiv.org/abs/2611.29765
**作者**: V\'ictor Yeste, Candida Maria Greco, Paolo Rosso, Andrea Tagarelli
**来源**: cs.CL cs.CY cs.SI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [80] Can a Frontier LLM Repair a Quantized Network by Tool-Free Weight-Space Programming?

**链接**: https://arxiv.org/abs/2611.33031
**作者**: Steffen Urban
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We give four large language models (LLMs) of the Claude family the complete weights of a 20k-parameter CIFAR-10 CNN as text and ask them to produce a 4-bit network without tools, data or the ability to run inference. Standard round-to-nearest (RTN) quantization to 4 bit lowers the test accuracy from 81.4% to 60.4%. We design four evaluation protocols that differ in the input and task description given to the LLMs and analyze their responses. In the first two protocols the LLMs are given the float and the 4-bit RTN network and are told that the accuracy has dropped significantly. In the last two they receive only the float network and the task to quantize it, which tests whether they apply an optimization on their own or fall back to plain RTN. Our analysis shows that a frontier LLM can recover most of the lost accuracy. Given one answer per layer, Opus 5.5 raises the accuracy of the 4-bit network to 77.95% by balancing the rounding errors within each 3x3 kernel, reasoning over the inte

---

### [81] Recursive Collective Intelligence: Emergence on an Equal-Budget Ladder in Multi-Agent LLM Systems

**链接**: https://arxiv.org/abs/2611.32606
**作者**: Lixuan He, Shengqu Cai, Fang Wu, Shikang Zheng, Liwei Jiang, Manling Li 等 (10 人)
**来源**: cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models increasingly work as teams of agents, and a team is expected to solve problems beyond the reach of any single member. Most evaluations credit a team for outperforming a single agent, without accounting for the additional computation: a team may consume many times the tokens of one agent, and a plain vote over independent answers already explains most of the reported gain. Two questions therefore remain open: When does interaction itself make a group smarter, and can a group improve its next generation by learning from its own work? We answer both with the equal-budget ladder, which grades a group against independent agents at three levels: outperforming a single agent, a compute-matched majority vote, and compute-matched pass@n. On this ladder we define Recursive Collective Intelligence (RCI) as a group whose own output, without a teacher or external labels, makes its next generation smarter at equal cost. Three findings follow. First, interaction improves collect

---

### [82] Joint Detection of Constructive Speech, Hate Speech and Agreement in Online Conversations

**链接**: https://arxiv.org/abs/2611.32889
**作者**: Ida Dencker, Simon Karg, Kenneth Enevoldsen
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Online hate speech is an ever-growing issue with negative impacts on both groups and individuals, potentially causing users to withdraw from online conversations and debate. With some prominent social media platforms reducing their moderation efforts, constructive speech has emerged as an alternative strategy for countering hate. Automated detection of constructive and hateful speech can aid monitoring and improve understanding of their prevalence and online dynamics. In this work, we collect and annotate a large dataset of English and Danish social media comments for hateful tone, constructive tone, and agreement with parent comments. We fine-tune several multilingual LLMs to classify along these three dimensions and compare context-enriched and non-context-enriched model architectures. The E5-large LLM performs best on both the context-enriched (82% average F1) and non-context-enriched (81.6% average F1) classification tasks, demonstrating the potential of multilingual LLMs for scala

---

### [83] PreferenceScene: Personalized Indoor Scene Synthesis from Feedback

**链接**: https://arxiv.org/abs/2611.32099
**作者**: Seongrae Noh, RyunHa Lee, HyeongYeop Kang
**来源**: cs.CV cs.AI cs.GR
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Text-to-scene methods turn a short instruction into a furnished 3D room, but the room that a particular person wants rarely comes across fully in words: many preferences surface only when the person sees a concrete room and can point to what they like and dislike in it. We therefore study personalized indoor scene synthesis under hidden user preferences: over several turns, a system shows a 3D scene, and the user, who sees only rendered images of the scene, replies with brief free-form feedback and a satisfaction score. The system must therefore bring the whole room toward the user's preferences from feedback that comments on only part of it at a time. It must also be able to change every part of the room, because a preference concerns not only single objects but the look and atmosphere that surfaces, lighting, textiles, furniture and their arrangement create together. We present PreferenceScene, in which a large language model keeps an explicit estimate of the user's preferences for e

---

### [84] Right Destination, Wrong Journey: Synthetic Counseling Dialogues Miss Human Interactional Dynamics

**链接**: https://arxiv.org/abs/2611.31686
**作者**: Ziwei Gong, Yuchen Huang, Nicholas Deas, Melanie Subbiah, Julia Hirschberg
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-generated counseling dialogues are increasingly used for training and evaluating mental-health systems, yet existing evaluations focus largely on response quality and final outcomes rather than how support unfolds over time. We conduct a trajectory-centered evaluation of process fidelity across ten human, reconstructed, and synthetic counseling datasets. Our results show that synthetic dialogues often reach plausible endpoints but differ from human support in recovery dynamics and turn-by-turn responsiveness. While generation design can shift global properties such as recovery timing and trajectory structure, contingent patient--counselor responsiveness remains consistently lower in fidelity across models and generation paradigms. Our experiments on controlled synthetic datasets show that targeted generation interventions can narrow the gap with real data on several trajectory-level measures, but do not fully recover interactional fidelity, with turn-level responsiveness remaining 

---

### [85] Scaling Laws of Ensemble Uncertainty in Language Models

**链接**: https://arxiv.org/abs/2611.32801
**作者**: Siamak Ravanbakhsh, David Nitchi, Khang Ngo
**来源**: cs.LG cs.AI cs.NE
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Many use cases for large language models (LLMs)---from AI safety to exploration and human interaction---can benefit from epistemic uncertainty estimates. We argue that existing Bayesian Deep Learning solutions, which are often restricted to a fixed model family, fail to capture the full epistemic uncertainty at practical LLM scales. This is because the error due to the bounded capacity of the model family remains invisible to disagreement among models supported by the prior. We relate this error to the well-known power-law scaling of LLM loss with model size. We then show that a second power law quantifies the shrinking disagreement within ensembles as model size increases. Its slower decay relative to the capacity law above suggests that ensembles capture a growing share of epistemic uncertainty and become more competitive as an axis for scaling, compared to a single larger model. Finally, a third power law quantifies the loss of ensemble diversity as members share a larger fraction o

---

### [86] Faithful Persona Steering under Incongruity via Dual-Stream Refinement

**链接**: https://arxiv.org/abs/2611.31848
**作者**: Yu-An Chu, Jen-Ren Pong, Chia-Yao Yeh, Meng-Fen Chiang
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Standard LLM personalization typically frames identity as a static retrieval task, overlooking the inherent incongruity of human personas, where stable traits coexist with atypical, context-specific stances. Existing methods struggle to reconcile these dimensions: prompting succumbs to context drift over long sequences, while fine-tuning often suppresses idiosyncratic "quirks" in favor of generic distributional patterns. To bridge this gap, we present QuirkyMind, a framework that disentangles identity definition from its expression. First, Traits Anchoring constructs a dual-stream latent state, fusing a sentence-level summary for semantic stability with a token-level sequence for generative control. This state is stabilized via In-Context Narrative Refinement using an alternating objective: a discriminative InfoNCE loss anchors the persona in representation space to prevent drift, while a generative cross-entropy loss ensures faithful verbalization. Finally, Persona Steered Generalizat

---

### [87] Latent Merger: Latent-Space Composition of Hypernetwork-Generated LoRAs

**链接**: https://arxiv.org/abs/2611.33048
**作者**: Yanlai Yang, Minki Kang, Divyam Madaan, Sung Ju Hwang, Mengye Ren
**来源**: cs.LG cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent work proposes hypernetworks that convert a document into a low-rank parameter update (LoRA) in a single forward pass, enabling fast injection of new knowledge into a frozen LLM. However, storing separate LoRA adapters for each document can be unsustainable in streaming settings. In this paper, we study the problem of composing hypernetwork-generated LoRAs using two representative systems, Doc-to-LoRA and SHINE. We show that hypernetwork-generated LoRAs have a geometry sharply different from directly fine-tuned LoRAs. They exhibit greater spectral concentration and stronger cross-document alignment than next-token prediction and QA fine-tuned adapters, which are diffuse and nearly orthogonal across documents. Guided by this observation, we propose latent-space LoRA merging. We compose the intermediate hypernetwork latents and then decode the merged latent through the frozen LoRA-generation head. We show that latent-space merging techniques consistently improve over weight-space a

---

### [88] SOARS: System One Assisted Reranking for Agentic Search

**链接**: https://arxiv.org/abs/2611.32917
**作者**: Amin Bigdeli, Liye Fu, Fattane Zarrinkalam, Joel Stremmel, Elizabeth Lingg
**来源**: cs.IR cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Deep search agents address complex information needs through iterative retrieval and reasoning, where the relevance of retrieved evidence influences downstream performance. Existing rerankers improve retrieval effectiveness but introduce substantial latency and cost when invoked throughout the search trajectory. We introduce SOARS, a training-free framework leveraging a System One model for fast, calibrated relevance estimation. At each search step, SOARS selects query-relevant passages from long documents and reranks candidates in a single call, jointly considering the original question and agent-generated sub-query. Across six LLM backbones on BrowseComp-Plus and WebShaper, SOARS consistently improves answer accuracy and evidence recall while reducing search calls, end-to-end latency, and inference cost. On BrowseComp-Plus, it improves GPT-5.4 Mini's accuracy from 73.9% to 84.7% while reducing search calls from 23 to 14, demonstrating the potential of System One reranking for more ef

---

### [89] SPARQL-Planned Single-Hop Traversal over a Live Knowledge Graph for Multi-Hop Question Answering

**链接**: https://arxiv.org/abs/2611.31771
**作者**: Priyesh Vakharia, Masud Moshtaghi, Pratyay Banerjee, Nicholas Jedema, Amita Misra, Ankit Chadha
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Semantic retrieval struggles with multi-hop question answering on both recall and precision: gold passages are buried among distractors that degrade the reader's answer, and retrieving them requires reasoning over the query rather than matching it. GraphRAG techniques expand semantic retrieval by connecting passages to graph nodes and performing one or more hops of expansion after initial retrieval. This improves recall, but multi-hop expansion becomes expensive and brings additional noise into the retrieved set. We break this tradeoff by \emph{interleaving} dense retrieval with knowledge-graph traversal for complex multi-hop questions. Dense retrieval locates the first relevant regions of the search space at good recall, while traversal of a pre-existing external KG (Wikidata) restores precision and improves recall by confirming retrieved passages against a reasoning path through the KG. To keep traversal both question-adaptive and reliable, we have an LLM plan it as code generation t

---

### [90] PhysRF-WorldJEPA: Transforming Heterogeneous Large Language Models into Manifold-Decoupled Millimeter-Wave Radar World Models

**链接**: https://arxiv.org/abs/2611.32113
**作者**: Yicheng Huang, Feng Ke, Linhan Chen, Ziyi Jiang, Xiu Yin Zhang
**来源**: cs.LG cs.CV eess.SP
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Adapting Large Language Models (LLMs) to millimeter-wave (mmWave) radar enables privacy-preserving, all-weather physical scene understanding across darkness, smoke, and walls. However, standard instruction tuning treats continuous radar streams as static text-like tokens, causing near-random global radar-to-text retrieval and severe physical drift under sensor blackouts. Conversely, coupling pairwise contrastive losses (e.g., SigLIP) directly into the shared backbone improves retrieval but injects $O(B^2)$ repulsive gradients that fracture continuous coordinate manifolds ($R^2 < 0$). We present PhysRF-WorldJEPA, a manifold-decoupled Joint-Embedding Predictive Architecture (JEPA) that separates continuous electromagnetic state prediction from cross-modal language alignment. An unattenuated 1.0x clock anchor and parallel dual-scale RF encoder feed a lean ~3% LoRA LLM trained with two-step state-space EMA-JEPA (Denoise -> Rollout) and sample-axis Batch-VICReg to predict +3.0 s physical st

---

### [91] AgentDRC: Multi-Agent Algorithms for Spatially-Aware Automated DRC Correction

**链接**: https://arxiv.org/abs/2611.31876
**作者**: Pengju Liu, Nuo Xu, Winso Chen, Peijun Li, Yang (Katie) Zhao, Yu Cao 等 (7 人)
**来源**: cs.AR cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Design Rule Checking (DRC) error fixing remains a time-consuming bottleneck in physical design, often requiring manual intervention despite advanced EDA optimizations. Existing LLM-agent approaches fall short due to redundant contextual shapes, limited spatial reasoning over raw coordinates, and inefficient flat layout representations. We propose AgentDRC, which formulates iterative DRC correction as a multi-agent algorithm and introduces a spatial-aware verification and correction algorithm that reconstructs structured spatial relations among critical shapes and validates fixes through geometric and semantic constraint checking. The system coordinates four specialized agents to perceive multi-level, multi-modal geometric features, filter irrelevant shapes, and iteratively correct violations. Experiments show that AgentDRC achieves up to 30.4% pass@1 and 55.7% pass@5 on challenging violations, with 13.8% pass@5 improvement over the best baseline. We will open-source all code and benchm

---

### [92] TimeTravelContainer: A Live Forking Sandbox for Stateful Agent Exploration

**链接**: https://arxiv.org/abs/2611.32255
**作者**: Zizheng Guo and Yanqing Zhang and Nathaniel Pinckney and Cunxi Yu and Brucek Khailany
**来源**: cs.OS cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents that drive stateful tools (e.g., interactive shells, design environments, simulation engines) frequently need to clone, backtrack, and parallelize live sessions to support exploration. However, cloning a live session today requires serializing the tool's in-memory state to disk or relaunching from scratch, both prohibitively slow for interactive exploration. Existing agent sandboxes based on microVMs or kernel patches either serialize full guest memory to storage or require privileged deployment, limiting use on shared compute farms, personal computers, and other restricted environments. We present TimeTravelContainer (TTC), a rootless container runtime that live-forks an entire running container, including processes, memory, filesystem, and network, with copy-on-write (CoW) semantics. Because the bulk of a tool session's memory is typically read-only after the fork point, clones share it automatically and only diverged pages consume additional memory. TTC requires no kernel

---

### [93] One Style Fits All? Cultural Values Embedded in Conversational AI via a People-Pleasing Lens

**链接**: https://arxiv.org/abs/2611.32939
**作者**: Yi-Jun Chen, I-Tsen Hsieh, Li-Wun Chang
**来源**: cs.HC cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Conversational AI systems trained on large-scale web corpora inevitably encode the cultural values and interactional norms embedded in their training data, yet our understanding of how deployed LLMs reflect or reinforce culture-specific social expectations remains limited. This study examined how supportive versus challenging chatbot interaction styles shape user experience and continuance intention, and whether people-pleasing tendency (PPT) moderates these effects across cultures. Taiwanese (N = 49) and Korean (N = 52) participants completed a collaborative tourism-planning task. Results showed that: (1) supportive chatbots consistently led to higher continuance intention, satisfaction, and trust; (2) PPT did not moderate these effects; and (3) cultural variation emerged only in perceived threat, where higher PPT was associated with greater baseline threat in the Taiwanese but not the Korean sample. These findings reveal how a general-purpose LLM style may differentially activate cul

---

### [94] GaokaoMathGen: Chinese Gaokao Mathematics Finale Problem Generation Controlled by Latent Reasoning Structures

**链接**: https://arxiv.org/abs/2611.31823
**作者**: Qian Chen, Kun Zhu, Zhongyi Wang, Ling Chen
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Generating Chinese Gaokao mathematics finale problems requires controlling not only the included skills, but also the underlying mathematical kernel and solution path. Existing LLM-based methods mainly rely on surface-level specifications, while the realized difficulty of generated problems cannot be determined directly from prompted targets. Therefore, we propose GaokaoMathGen, a framework for Chinese Gaokao mathematics finale problem generation controlled by latent reasoning structures. It extracts standardized latent reasoning structures from seed problems and performs constrained synthesis using skills, methods, a core identity, and a pivot step as structural controls. We further estimate realized difficulty through logical-quality filtering, fixed-solver decoding effort, structural features, and solver-output search signals. Experiments show that semantic normalization improves cross-annotator comparability and that 78.0% of 609 scored candidates pass the logical-quality filter. I

---

### [95] TableRouter: Query-Aware Evidence Construction for Long-Table Question Answering

**链接**: https://arxiv.org/abs/2611.32006
**作者**: Anahita Bolourani, Xiaofeng Lin, Tung Sum Thomas Kwok, Guang Cheng
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLMs can reason over tables, but when tables outgrow the context budget, retrieving relevant rows is only part of the solution. A retrieved subset may omit information required for an exact aggregate; even complete evidence may remain difficult for an LLM to use. We introduce TableRouter, a training-free framework that analyzes each query, then chooses between two routes: a computation route, which derives question-conditioned statistics from the full table, and a coverage route, which retrieves relevant rows and column summaries. The chosen context is passed to a frozen LLM in one call. Across three LLMs and three large-table benchmarks, TableRouter outperforms the strongest of six single-call baselines in all nine settings by 1.2-18.3 accuracy points, using 77-95% fewer estimated FLOPs than truncated-table prompting, with indexing amortized across questions. The gains extend to long tables from databases not used in earlier experiments, where TableRouter achieves 35.8% with Qwen2.5-7

---

### [96] Wavefront: Low-Rank Drafting with Parallel Causal Refinement for Speculative Decoding

**链接**: https://arxiv.org/abs/2611.31638
**作者**: Huy Huu Nguyen, Xin Huang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Speculative decoding accelerates LLM inference by letting a cheap drafter propose tokens that the target model verifies in parallel. Parallel block drafters such as DFlash and P-EAGLE propose a whole block in one forward pass, but they lose the dependence between tokens in the block; DSpark restores part of it with a lightweight correction head that runs sequentially. Measuring DSpark, we find that this head overrides the base prediction on most slots, so the expensive base readout through the target's full lm_head mostly provides a seed. We therefore propose Wavefront, which follows a simple principle: shrink the base and strengthen the correction head. Wavefront replaces the full lm_head with a learned low-rank base, conditions the correction head on the whole drafted prefix within the same block, and resolves it with a few parallel Jacobi passes. A fixed pass budget makes the draft step free of data-dependent control flow, so we capture it as a single CUDA graph in vLLM with fused k

---

### [97] Attestation is All You Need: Toward a Zero-Trust Architecture for HPC AI Agents

**链接**: https://arxiv.org/abs/2611.32958
**作者**: Jie Li, Chenxu Niu, Tongyang Wang, and Yong Chen
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> AI agents are beginning to automate data analysis, orchestration, and simulation steering in HPC environments, but they introduce a security problem that existing cluster defenses do not address: the hijacked authorized agent. An adversary can subvert an agent through prompt injection, poisoned shared data, compromised tools, or multi-agent coordination, then exfiltrate sensitive data through legitimate encrypted LLM API traffic. We propose behavioral attestation as a runtime defense for this setting. Our system, AEGIS, compiles task-derived behavioral constraints, monitors agent actions with ebpf-based syscall interception, verifies evidence against constraint profiles, correlates behavior across agents, and triggers slurm-level containment. On the real attestation path, AEGIS detects all four implemented attack classes with sub-second median latency at a 1-second interval and low measured verifier overhead. Controlled experiments show full attack-suite coverage, stronger detection th

---

### [98] COGENT: A Modular Cognitive Architecture for Agentic User Simulation

**链接**: https://arxiv.org/abs/2611.31559
**作者**: Yikun Chi, Adam Davies, Debarati Das, Lin Ai, Scott Counts
**来源**: cs.AI cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based user simulation can support interface design, accessibility research, and interactive-agent evaluation, but standard computer-use agents are optimized for task completion rather than reproducing how people perceive, reason, and act. We introduce COGENT (COGnitive agENT), a modular cognitive architecture for simulating user interaction with desktop interfaces. COGENT draws on established cognitive theories, such as Norman's action cycle and ACT-R, to enable explainable, intervenable, and modular user simulation by decomposing the simulation process into cognitive modules with explicit representations of perception, memory, user state, intentions, and action selection. We begin by presenting six intervenability demonstrations, each tracing how a single edit to memory, a user attribute, or a processing module propagates through the cognitive pipeline to produce a behavioral change. We evaluate COGENT's behavioral and attributional fidelity across three benchmarks -- AgentNetBenc

---

### [99] Pando: Noise-Coupled Parallel Draft Trees for Efficient Edge Speculative Decoding

**链接**: https://arxiv.org/abs/2611.32269
**作者**: Joren Dumoulin, Hyoukjun Kwon, Subhankar Pal, Steven Li, Vignesh Vivekraja, Marian Verhelst
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Autoregressive (AR) decoding emits one token per forward pass, reloading the full model each time, so LLM inference on edge devices is memory-bound while the compute units sit idle. Speculative decoding puts that idle compute to work by verifying several drafted tokens in a single pass. State-of-the-art parallel drafters such as DFlash and DSpark propose an entire block of draft tokens in one forward pass, which makes drafting compute-efficient. However, they are deployed with draft chains whose length is capped by the block size they are trained for, leaving most of the computational budget for verification unused. To tackle this problem, we propose Pando, which builds dynamic draft trees on top of a parallel drafter and thereby removes this cap. Pando employs noise-coupled pruning, which draws the target model's sampling noise before drafting and ranks candidate branches under that noise, so the tree retains the branches the target will actually sample. Noise coupling is lossless and

---

### [100] Spec-Test Coverage Gap: Detecting Overspecified Tests in SWE-Bench-Style Benchmarks

**链接**: https://arxiv.org/abs/2611.31839
**作者**: Avi Aggarwal, Yiran Hu
**来源**: cs.SE cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> SWE-bench-style benchmarks, such as SWE-bench Verified (Verified) and SWE-bench Pro (Pro), evaluate coding agents with tests taken from the change that originally fixed each issue. However, these tests can enforce details the task never states, causing correct alternative fixes to fail. Such overspecified tests have so far been found mainly through expensive expert review. To address this, we define the Spec-Test Coverage Gap (STCG), a 1-4 scale measuring overspecification, and score it with two LLM judges, Claude Opus 5.5 and GPT-6.1 Sol, which are given the specification and the test patch. A task is flagged as overspecified when both judges score it 3 or higher. Our study has three parts. First, we validate the judges on 206 tasks that earlier human audits and agent results label as overspecified or fine. Second, we apply STCG to all 500 Verified and 731 public Pro tasks and compare the flags with the results of the top 30 Verified submissions. Third, we verify the flags by asking C

---

### [101] Learning What vs. Learning How: Decomposing Task and Interface Competence in Agentic Training

**链接**: https://arxiv.org/abs/2611.31427
**作者**: Chaeeun Lee, Hossein A. Rahmani, Aryo Pradipta Gema, Kexin Xu, Emine Yilmaz, Pasquale Minervini 等 (9 人)
**来源**: cs.AI cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents operate through harnesses that define system prompts, action formats, feedback loops, and resource constraints. A model may possess the knowledge needed to solve a task yet fail to express that knowledge through a particular harness. This raises a basic question: when a policy fails under a given harness, is it missing task knowledge or the competence to operate the interface? We distinguish two components of agentic competence: task competence, the knowledge and reasoning needed to solve a task, and interface competence, the ability to act on that knowledge through a given harness. Across four reasoning and agentic benchmarks, we show that harness-conditioned training yields vastly different outcomes depending on how these interact. Multi-harness distillation aggregates task knowledge from trajectories collected through different harnesses into a shared policy, but this knowledge is realised only when training preserves or improves competence on the inference-time interface

---

### [102] Agent Recovery Gone Wrong: Measuring Harm Beyond Duplicate Calls

**链接**: https://arxiv.org/abs/2611.31554
**作者**: Artem Trofimov, Boris Novikov
**来源**: cs.AI cs.DB cs.SE
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Code-executing LLM agents submit blocks of code that issue several API writes. If a block fails after some of its writes have taken effect, the agent rewrites the block and continues. It is unknown how often such a recovery harms the external state when the failure occurs naturally in the code written by the agent. In this paper, we measure it on recorded trajectories of AppWorld agents. In a stratified random sample of 200 candidate episodes across ten models, 145 are partial executions confirmed by the database state. In the sample, 30 of 143 confirmed partial executions with a determinable outcome are followed by a harmful recovery, and its violation remains at the end of the run, which gives a stratification-weighted estimate of 24.6%. Two thirds of the harmful recoveries duplicate an effect, and the rest delete user data or make a wrong first-time write, e.g., an order of a wrong product. A rule that searches for repeated calls finds 75% of duplications but only 41% of all harm. W

---

### [103] Privacy Disclosure Control Benchmark (PDC-Bench): How Faithfully Do LLMs Keep Privacy Constraints on In-Context Disclosure Granularity?

**链接**: https://arxiv.org/abs/2611.32610
**作者**: Kosuke Fujita, Daiki Nishiyama, Jun Sakuma
**来源**: cs.CR cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In LLM task execution, a constraint on the permitted disclosure granularity of personal attributes is sometimes imposed on the output. For example, if a person's private attribute is their location (San Francisco) and disclosure is permitted only at the country level, an output at the state level (California) violates the constraint. Detecting such violations requires capturing not only direct privacy leakage (San Francisco) but also semantic leakage (California). However, existing benchmarks cannot measure the degree of leakage with respect to a given semantic constraint such as the country-level limit. We therefore formalize disclosure control as a constraint on the permitted ceiling over the hierarchy of a knowledge graph. Building on this formulation, we construct PDC-Bench, a benchmark of 16,105 samples covering geography, age, race and ethnicity, and occupation. In our experiments applying PDC-Bench to eleven LLMs, 62% of the constraint violations were semantic leakage. We furthe

---

### [104] Can AI Design a Better nnU-Net? A Hypothesis-Driven Architecture Discovery Loop from Failures to Design Rules

**链接**: https://arxiv.org/abs/2611.32384
**作者**: Songtao Jiang, Yuan Wang, Fucheng Niu, Hualiang Wang, Jian Wu, Zuozhu Liu
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Neural architecture search and LLM-driven evolution often reduce evaluation to a scalar fitness score, discarding failures that could explain why designs succeed or fail. We present a hypothesis-driven architecture discovery loop in which LLM agents diagnose structured error patterns, formulate falsifiable hypotheses, test counterfactual controls under a frozen nnU-Net pipeline, and distill validated mechanisms into executable trigger-to-action rules. Across eight search waves, the loop identifies two principles for 3D medical image segmentation. First, reallocating computation from high-resolution decoders to the mid-encoder preserves thin-anatomy boundaries while reducing cost. Second, support-confined region contrast addresses errors between nested anatomical compartments, with anatomy-dependent triggers selecting when the rule applies. These principles produce LeanNeXt (0.78 MACs and 0.92 training-step time relative to nnU-Net; +1.63 Dice points on four-fold KiTS23 cross-validation

---

### [105] DiaCap: Jointly Learning Who Speaks When for Audiovisual Dialogue Captioning

**链接**: https://arxiv.org/abs/2611.33153
**作者**: Binfei Ji, Zhiwen Cao, Anqi Yang, Prem Seetharaman, Shuo Yang, Ratheesh Kalarot 等 (8 人)
**来源**: cs.CV cs.CL cs.MM cs.SD
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We present DiaCap, an audiovisual LLM for comprehensive dialogue captioning, which produces the transcript, timestamps, and a visual description of the speaker for every utterance in a video. Considering that utterance timing and audiovisual diarization are tightly coupled, DiaCap unifies the tasks in a single model, trained in two complementary stages. First, we train DiaCap on 225K curated clips, using synthetic captions that densely label every utterance in detail. Second, we further refine the model via reinforcement learning on 2.9K human-corrected clips, using fine-grained feedback that directly evaluates utterance timing, speaker grouping, and speaker binding. On DiaDemBench, which we extend with utterance-level timestamps and subtitle redaction, both DiaCap with off-the-shelf transcripts and its end-to-end variant DiaCap-E2E achieve strong results. Specifically, DiaCap performs on par with Gemini 4 Argon in audiovisual diarization while clearly outperforming it in timestamp acc

---

### [106] DocPristine: Content-Aware Document Appearance Enhancement under Real-World Mixed Degradations

**链接**: https://arxiv.org/abs/2611.32176
**作者**: Zihan Huang, Junle Liu, Zhonghao Ye, Yuyi Zhang, Peirong Zhang, Hanlin Li 等 (8 人)
**来源**: cs.CV cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Camera-captured documents often exhibit mixed degradations, such as highlights, shadows, and blur, that distort backgrounds and obscure text details. Document appearance enhancement (DAE) aims to mitigate these degradations and improve readability. Existing document appearance enhancement methods rely either on input-derived visual cues that can become unreliable under severe degradation or on LLM-based degradation diagnosis that lacks spatial guidance. Notably, we find that pretrained document visual encoders continue to attend to text regions in degraded documents, providing content-aware guidance. Based on this insight, we propose DocPristine, which adaptively fuses multi-layer features from a frozen document visual encoder and injects them into a pixel restoration network. To integrate these features into a pixel restoration network, DocPristine combines Adaptive Multi-Layer Feature Fusion (AMFF), Hierarchical Gated Conditioning (HGC), and Shifted-Window Cross-Attention (SWCA). Spe

---

### [107] Measurement Artifacts in Trustworthiness Evaluations of Quantized Small Language Models

**链接**: https://arxiv.org/abs/2611.32848
**作者**: Tanzeel Abbas, Tehseen Zia, David Windridge
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Evaluations of quantized language models attribute the change in a benchmark score to quantization. We write the measured change as the true change plus a term contributed by the instrument. Instrument error that is the same at every precision can shrink a paired comparison but cannot create or reverse an effect. Error that interacts with quantization can do both, and it is reported as an effect of quantization. We estimate this interaction for four measurement choices in 8 instruction-tuned models below two billion parameters, at float16, LLM.int8() and NF4, on identical items. Measured against labels from two human annotators, the 4-bit rise in harmful compliance is about half to two-thirds of the rise in non-refusal that a corrected key word detector records. Cloze and lettered multiple-choice scoring disagree about the effect of quantization far more than their noise allows: their estimates correlate at \r{ho} = 0.10, against a ceiling of about 0.77. LLM.int8() answers and generati

---

### [108] Shifter Quantization: Compact Representations for Native Integer Computation

**链接**: https://arxiv.org/abs/2611.33080
**作者**: Yufeng Huang
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Groupwise quantization is used in LLM quantization to improve accuracy at low bit widths, but grouping weights keeps standard integer MMA from spanning the full dot product for efficient GPU inference. We develop a new quantization method, Shifter Quantization (SQ), that reconstructs native-width integer operands by appending and shifting shared bits. To further extend the efficiency, we develop a special variant of SQ, Shifter Integer (SHI), to use INT4 kernels. We show that SQ and SHI formats perform better than standard groupwise quantization in quality, as measured by projection error and KL divergence, and in inference speed, as measured during decoding and prefill. For low precision like 2-bit quantization, SQ2 and SHI2 achieve 2.71-3.77x the 4,096-token prefill throughput of llama.cpp on a Q2_K checkpoint and reduce WikiText-2 KL by 6.6-7.8%. For mid precision like 4-bit quantization, SQ4 achieves 1.43-2.47x the prefill throughput of NInfer's groupwise-integer baselines across t

---

### [109] SAG-Mem-1.0 Technical Report

**链接**: https://arxiv.org/abs/2611.33124
**作者**: Yuchao Wu, XingCheng Liang, Xuanze Wang, Yini Huang, Yue Wu
**来源**: cs.CL cs.IR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-term conversational memory requires retrieving complementary facts scattered across dialogue sessions, including intermediate evidence with limited similarity to the original question. Existing approaches often rely on derived memory representations or persistent relational structures, introducing construction costs and potentially losing source details. We present SAG-Mem, a conversational memory framework that preserves complete dialogue messages in non-overlapping chunks and discovers complementary evidence through query-time lexical expansion. Memory construction requires no model inference, using a lexical index without LLM-based extraction, summarization, or semantic relation construction. At query time, BM25 retrieves initial candidates, an evidence evaluator identifies useful chunks, and lexical cues from selected evidence guide an additional retrieval round. Retrieved dialogue is further annotated with calendar interpretations of supported relative-time expressions, prese

---

### [110] Dreamcatcher: Remembering What Surprises a World Model in Video Streams

**链接**: https://arxiv.org/abs/2611.31765
**作者**: Jinxi He, Ce Zhang, Wenhe Liu, Jianshu Zhang, Katia P. Sycara, Yaqi Xie
**来源**: cs.CV
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As live video streams grow longer, repeatedly encoding and processing their full histories becomes increasingly costly. Answering questions as they arrive therefore calls for visual memory built in one pass before future questions are known. Existing methods mainly keep tokens that differ from earlier ones or match surrogate queries fixed in advance. Without modeling world dynamics, these criteria struggle to tell subtle surprising details from expected change. We introduce Dreamcatcher, a training-free framework and, to our knowledge, the first to use predictive signals from an independently pretrained, frozen video world model for online memory formation in streaming video question answering. Conditioned on recent history, the world model predicts incoming features using learned world priors. Its normalized prediction errors yield temporal and spatial surprisal signals that guide online segmentation and the retention of a frozen Video-LLM's native visual tokens, balancing surprising 

---

### [111] CPU-Eval: Evaluating Large Language Models for CPU Hardware Code Generation

**链接**: https://arxiv.org/abs/2611.32405
**作者**: Yuisei Iwata, Yutaka Masuda, Tohru Ishihara
**来源**: cs.AR cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Benchmarks such as VerilogEval have supported rapid advances in hardware description language (HDL) generation by large language models (LLMs). However, recent HDL-generation systems achieve pass rates above 90% on VerilogEval, leaving limited headroom for revealing further advances. To provide a challenging target for further progress on a practically important hardware-development task, we introduce CPU-Eval, a benchmark of 339 HDL-generation problems constructed from six CPUs. Drawn from practical CPU designs, including families fabricated in silicon, the problems span CPUs from small embedded cores to Linux-capable out-of-order cores and cover diverse CPU functions written in SystemVerilog, Chisel, and SpinalHDL. In each problem, an LLM performs the real CPU-development task of generating HDL. Across seven state-of-the-art LLMs, mean pass@1 is 45.14 percentage points lower on CPU-Eval than on VerilogEval v2 Spec-to-RTL, exposing capability differences obscured by VerilogEval's high

---

### [112] Are We Rewarding the Wrong Module? Module-Specific Policy Optimization for Multimodal Reinforcement Learning

**链接**: https://arxiv.org/abs/2611.32687
**作者**: HuiSeong Cho, Jun Yeong Park, Yu Rang Park
**来源**: cs.CV cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reinforcement learning with verifiable rewards (RLVR) based on Group Relative Policy Optimization (GRPO) has been widely adopted to enhance the multimodal reasoning of multimodal large language models (MLLMs). However, existing methods share a common limitation of Module-Level Credit Entanglement, in which the vision encoder, projector, and LLM modules are jointly optimized using the same advantage signals even when perceptual correctness and final-answer correctness differ. To address this limitation, we propose Module-Specific Policy Optimization (MSPO), a framework that separates perceptual and outcome-based learning signals across model modules. Specifically, MSPO uses responses to perception checklists comprising auxiliary questions about visual information to derive an advantage for training the vision encoder. From these responses, MSPO computes the Confidence-aware Perception Reward (CaPR), using a perception sign obtained by thresholding checklist accuracy to determine reward 

---

### [113] Agentic Discovery of Soundness Bugs in Safe Rust Bindings

**链接**: https://arxiv.org/abs/2611.31813
**作者**: Marius Momeu, Koushik Sen
**来源**: cs.CR cs.AI cs.PL cs.SE
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Rust crates confine unsafe code, such as calls into C or C++ libraries or system calls, behind safe interfaces that must uphold Rust's invariants. If an interface encodes one rule of the code beneath it too weakly, a program written in purely safe Rust can cause undefined behavior. Static analyzers and fuzzers are bound to fixed patterns or to the paths they execute. We propose LLM agents as auditors of these interfaces, and study how well they do it. We first define a taxonomy of the defects of such interfaces, including undefined behavior, divergences from the wrapped library, and incomplete unsafe contracts. We then measure, in repeated audits of a real-world crate by a closed and an open model, Claude Opus 5.5 and DeepSeek V4.1 Flash, which defect classes agents find, how well they triage them, and what makes them find more. Agents find the first two classes unprompted, but find few incomplete contracts even when asked. Their findings are almost always real, even without an indepen

---

### [114] Accelerating Dynamic Route Re-solving via Robust Solver Evolution in Automatic Heuristic Design

**链接**: https://arxiv.org/abs/2611.32576
**作者**: Yizhuo Ma, Haoran Sun, Shuang Liang, Muquan Li, Qizhi Chen, Renzhong Wang 等 (9 人)
**来源**: cs.NE
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-goal route planning uses spatial data on service locations and pairwise travel costs to determine a visiting order that minimizes total travel cost. This task can be formulated as the traveling salesman problem (TSP) and has benefited from large language model-based automatic heuristic design (AHD) for constructing effective solvers. Despite their effectiveness in static settings, existing methods exhibit substantial re-solving inefficiency when location changes, new requests, or request cancellations alter the underlying request data during execution. Our empirical analysis suggests that ``static-overfitting'' contributes to this inefficiency, as evolved solvers may repeatedly direct search toward overlapping local neighborhoods after dynamic changes. We further find that this ``overfitting'' is associated with limitations in existing evolutionary processes, where lower objective values on some instances coincide with longer solving times. In this paper, we therefore propose ERD

---

### [115] Monitorable-by-design architectures for a post-Astra world: a compartmentalization-based approach

**链接**: https://arxiv.org/abs/2611.31610
**作者**: Jake Watts, Joel Sokol
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Frontier models like GPT-6 Astra are increasingly able to do substantial reasoning without a monitorable chain of thought, chains of thought are becoming less legible, and are often monitored asynchronously to reduce cost. With the future of chain of thought monitoring unclear, it may be necessary to design LLMs with monitorability in mind. We propose a modification to existing LLM architectures based on GRAM, SGTM, DEMix, BTS, and similar methods to compartmentalize dangerous capabilities so that their use, especially in combination with dangerous reasoning types that may indicate strategic adversarial use, can be monitored more cheaply than chain of thought in a way that might outlast monitorable chain of thought. We propose several variants of this architecture designed to balance tradeoffs and discuss other benefits, such as capability removal.

---

### [116] VISE: Verifier-Independent Skill Self-Evolution with Feedback from Tool Implementations

**链接**: https://arxiv.org/abs/2611.32480
**作者**: Yuxuan Liu, Chongyang Du, Yuhao Zhang, Jiahe Guo, Kawai Chung, Wenbin Hu 等 (10 人)
**来源**: cs.AI cs.SE
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Agent skills provide reusable workflows that guide LLM agents in using tools. Refining these workflows requires feedback on missing or incorrect instructions, but task-specific verifiers are not always available. We propose VISE (Verifier-Independent Skill Evolution), a scripts-first approach that uses tool implementations to guide skill revision. It extracts tool capabilities, input requirements, usage conditions, and output formats from source code. Using the task request and execution trace, it compares this information with current workflow instructions to identify missing or conflicting steps. It then recommends specific edits to SKILL.md, linking each change to the relevant implementation and usage conditions. We evaluate VISE as an additional revision stage for four evolution methods on SkillsBench and SkillLearnBench. Compared with the corresponding No-verifier conditions, it improves overall average task success by 9.14-13.35 percentage points. The proportion of tasks solved i

---

### [117] Discovering Bandwidth-Efficient Prefetchers to Shrink the Cache Hierarchy

**链接**: https://arxiv.org/abs/2611.31983
**作者**: Patrick Tser Jern Kon, Akanksha Jain, Abraham Gonzalez, Rui Meng, Dilara Soylu, Shubham Agarwal 等 (10 人)
**来源**: cs.AI cs.AR cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Shared last-level caches (LLCs) increasingly dominate server processor die area, forcing architects to trade core counts for cache capacity. While intelligent data prefetching offers a pathway to reclaim this silicon, designing coordinated, multi-level prefetching policies for multi-core systems is bottlenecked by day-long, cycle-level simulations. This simulation wall limits even LLM-based microarchitecture discovery; the state-of-the-art ArchAgent system evolves one cache level at a time on single-core benchmarks, adds multi-core configurations only at the end, and trails the human champion under multi-core shared cache contention. We introduce DuoArchitect, an autonomous agentic framework for multi-fidelity, multi-core co-discovery of prefetchers. Agents jointly evolve evaluation proxies and coordinated prefetching policies across the L1D, L2, and LLC hierarchies, constructing simulation proxies 3-26x faster than cluster evaluation and hardware diagnostic oracles to guide the search

---

### [118] When Repair Accuracy Misleads: Training a VLM on Its Own Failures

**链接**: https://arxiv.org/abs/2611.32982
**作者**: Ang Qi, Yue Wang
**来源**: cs.CV cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Fine-tuning a vision-language model on its own failures is a direct way to repair it, but accuracy on held-out failures, the obvious measure of success, misleads. Many mined failures are not model errors: a human audit of 100 failures of Qwen3-VL-8B-Instruct on questions generated from COCO and GQA found label errors in 37. And mined failures share wording regularities: question-only classifiers get both answers right on 73.2% of held-out failure pairs. We study both traps with verified failure-driven repair (VFR): typed minimal-pair failure mining, verification by three LLM judges that answer without seeing the stored labels, answer-first corrective targets, and LoRA fine-tuning with replay. VFR repairs 82.8% of held-out failures (base model: 10.0%), and on independently labeled, unconditioned pairs it raises overall accuracy from 87.4% to 92.4% through spatial relations, whose accuracy rises from 66.7% to 96.8% even where the wording points to the wrong answer. Yet on negation, of wh

---

### [119] Directly Maximizing On-policy Expected Accepted Length for Speculative Decoding

**链接**: https://arxiv.org/abs/2611.31256
**作者**: Ziying Zhang, Yaqing Wang, Yong Liu, Quanming Yao
**来源**: cs.CL cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Speculative decoding accelerates large language model inference by using a lightweight draft model to propose tokens for verification by a target model. Draft training commonly optimizes token-level distribution alignment, but this does not directly optimize the length of the accepted prefix: once a draft token is rejected, all subsequent draft tokens are discarded. We propose FreDraft, an on-policy training method that directly maximizes the expected accepted length of drafts sampled from the current draft model. This objective accounts for first-rejection truncation and induces prefix-aware credit assignment, weighting each token by its contribution to the acceptance of the current and subsequent tokens. To optimize the objective efficiently, we analytically marginalize token-level acceptance rate, using the target model's vocabulary distribution to reduce gradient variance. We further redistribute part of this distribution-level gradient into an explicit penalty for sampled tokens w

---

### [120] Verified Proof Refactoring with Codex and Qwen

**链接**: https://arxiv.org/abs/2611.31762
**作者**: Lazar Milikic, Gordan {\DJ}uri\'c, Viktor Kun\v{c}ak
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We refactor existing Lean 4 proofs to reduce source length and checking cost while preserving theorem statements and compatibility across Lean versions. A locally served Qwen model uses the open-source Codex CLI to inspect source, retrieve declarations, and test proof replacements. The host keeps a replacement only if it improves the objective and Lean accepts it on every required version. A deterministic CPU pass then refines the verified proofs. On the 60 problems in Lean Refactor Arena, model search achieves a local mean combined score of 82.07, and cleanup raises it to 82.18. The final proofs pass all 127 required proof--version checks. Our system placed first in the open-source LLM track of Lean Refactor Arena at VeriCodeGen.

---

### [121] More Powerful, Less Verifiable? Mitigating Hard-to-Verify Hallucinations in MLLM's Reinforcement Learning

**链接**: https://arxiv.org/abs/2611.32055
**作者**: Jianhong Pang, Ziyi Ye, Qiuxia Hou, Yanhao Zhang, Zuxuan Wu
**来源**: cs.AI
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reinforcement learning (RL) strengthens model capabilities through feedback from humans and environments. However, emerging evidence suggests that reward optimization can produce outputs whose errors are harder for humans to detect. To address this issue, we construct ITHV (the Image-Text Hallucination Verifiability Dataset), comprising 2,728 visually grounded instances that distinguish between obvious hallucinations, which humans readily detect, and elusive hallucinations, which humans struggle to identify. We then propose DAPO-V, an extension of DAPO that maximizes correctness subject to a budget on verifiability-aware risk. Specifically, DAPO-V combines a verifiability-aware reward with adaptive dual control, where larger penalties are assigned to incorrect responses on questions with lower human verification accuracy. An adaptive multiplier further adjusts the penalty strength according to risk-budget violations. Across three MLLM base models, DAPO-V improves overall accuracy while

---

### [122] Teaching Time Without Losing General Retrieval: Adapting Multimodal Embeddings for Time-Sensitive Video Retrieval

**链接**: https://arxiv.org/abs/2611.32971
**作者**: Toya Oyama, Rainer Lienhart, Shin'ichi Satoh
**来源**: cs.CV
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In text-to-video retrieval, MLLM-based embedding models do well when the text describes the scene (general retrieval), but poorly when it describes actions and their direction (time-sensitive retrieval). TARA, a pioneering work, fine-tunes such a model on text triplets with temporal hard negatives; it improves time-sensitive retrieval but lowers general retrieval (mean R@1 over six benchmarks in our rerun on Qwen3-VL-Embedding-8B: 58.4->44.8), and its released model keeps general retrieval only when ensembled with Qwen3-VL-Embedding. Our goal is strong general and time-sensitive retrieval with one model and one vector per clip. Three findings lead to three simple components. Keep loss: general retrieval follows how far the output embeddings drift from the base model, not how far the weights move; we therefore keep them near the base model, which keeps most general retrieval even without general-domain data. Pair loss: the text embeddings of an action description and its reversed-direct

---

### [123] MOZAIC: An Audio-Video Deepfake Benchmark for Telling What Is Fake

**链接**: https://arxiv.org/abs/2611.31301
**作者**: Shaina Raza, Mohamed Hafez, Ahmed Y. Radwan, Khalid Elgazzar, Kathryn Hume
**来源**: cs.AI cs.CV cs.SD
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Audio-video (AV) deepfakes can fake the face, the voice, or both. Most benchmarks only ask whether a clip is real or fake, so they cannot show whether a detector relies on the picture, the voice, or encoding traces. We present MOZAIC, a paired benchmark with a 4-way label in which every source clip is released in all four combinations of real or fake video and real or fake audio so each modality contribution can be measured directly. Fakes cover inner-face swapping, whole-frame video diffusion and voice conversion. MOZAIC has 137,745 clips from 15,014 source pairs and four tasks: T1 AV authenticity, T2 manipulation type, T3 identity verification and T4 explanation. We evaluate 12 AV multimodal LLMs (MLLMs), train four detectors and fine-tune MLLMs with LoRA. Overall, the best MLLM reaches only 35.6% on the four-way T1 and catches far more video-only fakes than voice-only fakes (43.6% vs 7.5%). Trained detectors reach 98.4% on T1, and LoRA fine-tuning raises explanation scores (OmniVinc

---

### [124] PFedHASNet: A Personalized Federated Hybrid Analog-Spike Network for Multi-Subject Motor Imagery EEG Decoding

**链接**: https://arxiv.org/abs/2611.32019
**作者**: Peijia Li, Ruidong Ma, Xianghong Lin, Xiangwen Wang, Guoyong Shi, Shuai Huang 等 (7 人)
**来源**: cs.LG
**匹配关键词**: EEG, Motor Imagery
**相关性评分**: 7.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Motor imagery electroencephalography (MI-EEG) data are often collected and stored separately across subjects or institutions, and EEG acquisition and annotation remain costly. Training models solely on individual subject data limits the use of information from other subjects, whereas centralizing raw EEG recordings raises privacy and data governance concerns. Federated learning (FL) enables collaborative model training across distributed clients without sharing raw EEG data, providing a practical approach to leveraging information from multiple subjects. Accordingly, we propose PFedHASNet, a personalized federated hybrid analog-spike network for MI-EEG decoding. The shared encoder integrates continuous-valued temporal features, leaky integrate-and-fire (LIF) spike responses, and channel-wise log-variance statistics through learnable fusion weights. Client-private residual adapters and classifiers perform subject-specific feature refinement and personalized prediction, respectively. Exp

---

### [125] Layer-Readout Interfaces in EEG Foundation Models: Predictive Accessibility and Cross-Dataset Transfer

**链接**: https://arxiv.org/abs/2611.31320
**作者**: Yanlin Fu, Wei Liu, Liming Zhao
**来源**: cs.LG cs.AI
**匹配关键词**: EEG, Foundation Models
**相关性评分**: 7.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Intermediate layers often outperform final layers when foundation models are used as frozen feature extractors, but the source of this advantage is unclear. We study this question in EEG foundation models by separating three factors: how representations are read out, whether intermediate layers provide predictive utility beyond the final-layer interface, and whether useful depth structure transfers across datasets. Across five models and three tasks, improving the final-layer readout consistently recovers substantial predictive performance, yet intermediate layers remain advantageous within frozen extraction. We also find that layers selected on one dataset remain useful on another across five dataset pairs and four task families, and that a compact set of source-derived task directions retains predictive value after transfer in sleep staging. Together, these results show that predictive utility varies across depth, and its usefulness depends on how representations are read out and tra

---

### [126] EEG-Jev: A Unified Single-Pass Decision Model for EEG

**链接**: https://arxiv.org/abs/2611.31875
**作者**: Zhifei Zhu, Hongtao Zhang, Yu Ren, Wei Zhou, Zeping Xie, and Yi He
**来源**: cs.LG cs.AI physics.bio-ph
**匹配关键词**: EEG, Motor Imagery
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> EEG analysis spans choosing alternatives, judging statements, and rating ordered attributes, requiring calibratable probabilities with explicit meaning. We present EEG-Jev, a unified single-pass decision model for EEG. Given an EEG window, a question and an answer specification, one forward pass returns a typed readout: CHOICE gives a candidate distribution, NOUL a proposition probability, and SCORE an ordered-level distribution and expectation. One checkpoint is trained jointly and evaluated once on held-out splits of 35 public sources. Core raw outputs reach 54.08% balanced accuracy on Stieger2021 motor imagery, 70.45% on Sleep-EDF-SC sleep staging, 72.11% per window at threshold 0.5 on CHB-MIT seizure detection with 0.825 AUROC, and 1.700 MAE on 0-10 ds005292 pain ratings. Prior correction and temperature scaling lower negative log-likelihood from 0.766 to 0.606 on Sleep-EDF-SC and 0.166 to 0.019 on CHB-MIT, while direct readout cuts batch-1 latency from 122.43 to 63.11 ms (1.94-fol

---

### [127] EEGJev: A System One Decision Model and Benchmark for Multi-Task EEG Question Answering

**链接**: https://arxiv.org/abs/2611.32100
**作者**: Dengzhe Hou, Kazunori D. Yamada
**来源**: eess.SP cs.LG
**匹配关键词**: EEG, Foundation Models
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A single electroencephalographic (EEG) recording can support multiple decoding tasks. Fixed-label tests cannot show how EEG foundation models handle changing questions or options. We introduce EEGJev, a fast decision model that scores candidate answers in one pass. Our benchmark, EEGJev-Bench, covers six question types across 19 public EEG sources. We held the recording and options fixed while switching between questions about attributes paired during training, such as facial expression and the hand participants were asked to use. Across 13 test sources, EEGJev selected a label for the requested attribute with 99.70% accuracy (49.20% under uniform choice). Balanced accuracy for the specific answer was 62.04%. Its 95th-percentile response time was shorter than NeuroLM's on matched validation questions answered individually. EEGJev lets users switch decoding targets by changing the question. With EEGJev-Bench, researchers can test whether new decoders follow the question more reliably, i

---

### [128] EEG-MedRAG: Enhancing EEG-based Clinical Decision-Making via Hierarchical Hypergraph Retrieval-Augmented Generation

**链接**: https://arxiv.org/abs/2508.13735
**作者**: Lu Meng, Zan Li, Yi Wang, Yi Ding, Ziyue Zhu, Fang Li 等 (10 人)
**来源**: cs.CL
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [129] Is 4 Bits Enough for EEG Sleep Staging? A Subject-Level Benchmark of MXFP4, NVFP4 and FP8

**链接**: https://arxiv.org/abs/2611.31436
**作者**: Emese Batizi, Hossein Valavi
**来源**: cs.LG
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Staging sleep on a wearable device keeps the raw electroencephalogram (EEG) private and saves the energy needed to transmit it. It also requires small, energy-efficient neural networks. We benchmark 13 post-training quantization (PTQ) configurations, from FP16 to the block-scaled 4-bit formats MXFP4 and NVFP4, for five-stage sleep staging from single-channel Fpz-Cz EEG. We use Sleep-EDF-78 (78 subjects), subject-wise cross-validation, three training seeds, value-exact emulation, and per-subject paired statistics. All 8- and 16-bit formats stay within 0.45 percentage points (pp) of FP32 Macro-F1. With 4-bit weights and activations, an epoch-wise CNN loses 1.98 to 3.04 pp, and a temporal-context network loses at most 1.19 pp. A same-encoder ablation shows that temporal context explains little of this gap. At equal block size, NVFP4 outperforms MXFP4. The first layer, which quantizes the raw EEG, is the most sensitive layer in both networks. Keeping the first and last layers in FP8 brings

---

### [130] Thought-deciphering via EEG-to-text alignment

**链接**: https://arxiv.org/abs/2611.03623
**作者**: Xiaopeng Mao, Morten M{\o}rup, Xin Xu, Sang Wan Lee, Sadasivan Puthusserypady
**来源**: cs.LG eess.SP
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [131] EEG-World: Context-Conditioned Dynamics of the Watching Brain

**链接**: https://arxiv.org/abs/2611.32825
**作者**: Junxiang Zhang, Jiayu Zuo, Wenhao Ye, Junfeng Xia, Xiang Chen, Mo Wang 等 (7 人)
**来源**: cs.CV q-bio.NC
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Brain encoding models predict neural responses from audiovisual input, but typically overlook how ongoing brain activity shapes an individual's response. We introduce EEG-World, a recurrent world model that forecasts 10 seconds of EEG band-power dynamics from 6 seconds of preceding EEG and the subsequent audiovisual stimulus. Pretrained on continuous EEG, EEG-World learns shared neural dynamics and adapts to unseen individuals through lightweight subject-specific readouts. Using 2,584 hours of EEG from 78 participants, we show that nonlinear recurrent forecasting surpasses strong history-aware linear baselines at scale. EEG-World achieves a forecasting correlation of 0.261 versus 0.233 for the strongest history-and-video linear model, with a 3.3-second forecasting-horizon advantage. Its learned dynamics transfer to unseen participants, outperforming the linear baseline in 23 of 24 individuals after calibration. While ongoing EEG history accounts for most predictive performance, control

---

### [132] TopoCryptoEEG: End-to-End Encrypted Framework for Brainprint Authentication

**链接**: https://arxiv.org/abs/2611.31801
**作者**: Qingyu Zeng, Lei Sun, Shuai Zhang, Xiuqing Mao, Ting Zhang, Min Zhao 等 (7 人)
**来源**: cs.CR cs.AI
**匹配关键词**: EEG
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Brainprint authentication enables continuous identity verification, but EEG data are privacy-sensitive. Existing feature-level encrypted authentication (FLEA) schemes protect extracted features under a trusted-client assumption. We show theoretically and empirically that a compromised client with access to plaintext query features and continuous authentication scores can exactly recover a registered template after finitely many interactions. To address this risk, we propose TopoCryptoEEG, a homomorphic-encryption-based framework that encrypts preprocessed EEG data at the client and performs feature extraction, template matching, score computation, and threshold centering on ciphertexts at the server. This extends protection from extracted features to preprocessed EEG data and removes the client-side plaintext-feature interface exploited by the attack. For efficient encrypted authentication, we develop Multi-Window Topology-Aware Encoding (MWTE) and a Topographic Branch Model with Linea

---

### [133] Rethinking Universal Time Series Foundation Models from Unified Representations to Shared Dynamics (UniTFU)

**链接**: https://arxiv.org/abs/2611.31921
**作者**: Shuxin Li, Yingjie Zhou, Le Zhang, Jingyuan Xia, Shengxi Li, Ce Zhu 等 (7 人)
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Time series foundation models (TSFMs) have attracted increasing attention in cross-domain forecasting. Existing works mainly rely on large-scale pre-training and general modeling paradigms. However, the former heavily relies on the diversity and domain coverage of pre-training data. Meanwhile, the latter learns unified representations across heterogeneous domains without explicitly identifying the temporal regularities shared among them, limiting robust cross-domain generalization. This work explores cross-domain generalization by characterizing commonalities in recurring local dynamics across domains, rather than relying solely on implicitly learned temporal representations. To capture such cross-domain commonalities, we propose Time Series Foundation Units (TFUs) as reusable building blocks discovered from multi-scale temporal segments, each characterizing a recurring local dynamic pattern shared across domains. Building on TFUs, we develop a unified time series foundation model (Uni

---

### [134] InducedTFMs: A Family of Sub-Quadratic Tabular Foundation Models Using Induced Attention

**链接**: https://arxiv.org/abs/2611.32504
**作者**: Salome Gobbi, Nicolas Atienza, Nicola Cancedda, Michael Arbel
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tabular foundation models (TFMs) have emerged as a serious competitor to gradient-boosted trees, predicting on a new table in a single forward pass by in-context learning. However, their attention is quadratic in the number of samples and features, which caps pretraining at small synthetic tables and forces inference on large ones to rely on chunking or subsampling. Row-compression models reduce the feature-wise cost, but only by discarding the cell-level representation, and remain quadratic in the number of samples. We introduce InducedTFM, which replaces both attention stages of a bidimensional TFM with the induced attention of the Set Transformer, preserving cell-level representations while making its cost linear in both samples and features. Under a training budget matched to a full-attention TabICLv2 reimplementation, InducedTFM matches its accuracy on TabArena and on a benchmark of larger datasets, and clearly outperforms a kernel linear-attention baseline of the same asymptotic 

---

### [135] Which Way Is Up? Rotated Photos Silently Hurt Multi-View 3D Foundation Models

**链接**: https://arxiv.org/abs/2611.31478
**作者**: Yukun Shi, Minglun Gong
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-view 3D foundation models estimate camera poses and 3D points from a set of photos in one forward pass. Many cameras store a portrait shot sideways, with an orientation tag telling viewers how to turn it, and this tag can be ignored, lost or wrong. We measure how rotated photos affect five such models on three datasets. A few rotated photos lower camera pose accuracy for every model, and the sideways photos already in a standard benchmark do the same. Even the most robust model still loses accuracy. The failure is also silent: the models' confidence does not reliably flag it, and most official image loaders ignore the tag. The fixes we test each correct only part of the problem. These findings call for orientation checks in reconstruction pipelines and benchmarks.

---

### [136] SpatialArena: Where Do Geometric Foundation Models Stand?

**链接**: https://arxiv.org/abs/2611.32816
**作者**: Yu Chen and Haosen Yang and Su Ee Tan and Zhensong Zhang and Jifei Song and Jiankang Deng
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> 3D perception is shifting from task-specific pipelines to geometric foundation models: monocular depth networks, feed-forward 3D/4D reconstruction models, and vision--language models that predict geometry. However, their progress cannot be measured reliably. Published numbers are not comparable, because every paper samples frames, sets resolutions, and selects test splits differently. They are not robust because the alignment required for every up-to-scale prediction can outweigh the gap between models: fitting depth in the wrong space nearly triples its error, and standard trajectory alignment understates the error of failing methods by up to $2.6\times$. And they rarely cover long recordings, dynamic scenes, or aerial views. We present SpatialArena, an open arena that scores geometric models with the same metrics and rules, with robust and deterministic alignment. SpatialArena spans five tasks, from monocular depth to SLAM. It covers 23 public datasets with 418,929 images across indo

---

### [137] Tempering and few-shot calibration of pathology foundation models improve digital biomarker reproducibility across slide scanners

**链接**: https://arxiv.org/abs/2611.31536
**作者**: Frank T Wen, Kyler Rosen, Siddhi Ramesh, Michael Koo, Sara Kochanny, Sasha Jain-Liu 等 (9 人)
**来源**: q-bio.QM cs.AI cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Pathology foundation models underpin a growing number of histology-based cancer biomarkers, but sensitivity to slide scanner-specific image signatures degrades cross-center reliability and reproducibility. We developed a foundation model fine-tuning method that improved consistency in head-and-neck cancer human papillomavirus (HPV) prediction, colorectal cancer microsatellite instability (MSI) identification, prostate cancer grading and breast cancer phenotyping. This tempering method decreased cross-scanner prediction differences by 67.5% for HPV (95% CI 59.0-73.9%), 69.3% for MSI (95% CI 51.9-76.5%) and 63.4%-81.2% for breast signatures. Cross-scanner prostate grade agreement rose from 42.5% to 92.7%. Under full scanner-HPV confounding during training, AUROC fell from 0.80 to 0.68 with original model features but only from 0.86 to 0.84 with tempering. Unlike post hoc feature calibration, tempering used only public data yet matched or exceeded on-site calibration. These findings suppo

---

### [138] Where is the multimodal goal post? On the Ability of Foundation Models to Recognize Highlights in Videos

**链接**: https://arxiv.org/abs/2601.16333
**作者**: Aditya K Surikuchi, Raquel Fern\'andez, Sandro Pezzelle
**来源**: cs.CV cs.AI cs.CL
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [139] On Potentiality and Actuality Of Foundation Models

**链接**: https://arxiv.org/abs/2611.32991
**作者**: Fabian Gr\"oger, Shuo Wen, Maria Brbi\'c
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Foundation models are built through large-scale pretraining, often followed by post-training, and are then adapted to specific tasks and behaviors. But, does the adaptation add truly new capabilities, or the base model already holds it? We decompose the update induced by different adaptations into a component shared across all inputs and a residual that varies with the input. We find that the shared component suffices for most of the adaptation gain and can be learned directly: a shift adapter that learns a constant vector per layer, identical for every input, reproduces the behavior of LoRA and full fine-tuning. We call this the potentiality principle of foundation models: the base model already contains the capacity needed for task-specific expertise. To adapt to a new task, the model just needs to be actualized, i.e., pushed in a certain direction via a constant, input-independent shift. We show the implications of this principle on parameter-efficient adaptation, steering, and conv

---

### [140] Two-Stage Post-Training for Flow-Based Embodied Foundation Models

**链接**: https://arxiv.org/abs/2611.31850
**作者**: Jiaming Zhang, Yao Lyu, Haoning Wang, Yongjun Chen, Liping Zhang, Shengbo Eben Li
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large-scale pretraining provides embodied models with general capabilities, but reliable task execution still requires post training. In multitask settings, supervised fine-tuning (SFT) faces distribution mismatch between training and deployment, whereas reinforcement learning (RL) is limited by sparse rewards and uneven learning progress across tasks. Multi-teacher on policy distillation (MOPD) consolidates expert capabilities through dense supervision on the model's own trajectories, but achieving performance beyond the teachers remains challenging. We propose a two-stage post training framework for flow-based embodied models, constructing distillation objectives from the velocity regression formulation of conditional flow matching. Stage 1 efficiently consolidates expert capabilities through MOPD. Stage 2 combines RL with teacher distillation that weights velocity errors according to the sampling noise, where distillation is restricted to failed trajectories to supplement sparse rew

---

### [141] Ground, Guide, Act: Improving VLA Spatial Generalization with Multimodal Foundation Models

**链接**: https://arxiv.org/abs/2611.31452
**作者**: Guangting Zheng, Shaoxuan Wang, Yu Yuan, Zhipeng Tang, Jiajun Deng, Yanyong Zhang
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Vision-Language-Action (VLA) models effectively learn action policies from robot demonstrations, but struggle to generalize to changes in object positions and task goals. General multimodal foundation models (MFMs) offer complementary scene understanding and spatial reasoning, but remain slow and unreliable for direct fine-grained control. To understand how MFMs can improve VLA spatial generalization, we conduct a systematic capability analysis across multiple VLA architectures using atomic-stage interventions, revealing that many failures stem from poor target grounding and global spatial routing, while local manipulation skills remain largely usable. Based on these findings, we propose MFM-VLA, a selective collaboration framework in which an MFM provides target grounding and spatial guidance, controllers execute free-space motion, and the VLA retains control over fine-grained manipulation. We fine-tune the VLA with action-chunk-level dense geometric captions and perturbed-state recov

---

### [142] Beyond Static Leaderboards: Capability-Focused Evaluation with Structural Diversity for Time Series Foundation Models

**链接**: https://arxiv.org/abs/2610.26251
**作者**: Hongyin Zhang, Mingyi Xiang, Rongzhao Chen, Yankai Wang, Jialin Qiao, Xiangdong Huang 等 (10 人)
**来源**: cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [143] From Synthetic Priors to Model Behavior: Structural Coverage in Tabular Foundation Models

**链接**: https://arxiv.org/abs/2609.06912
**作者**: He Zhao, Ryan Thompson, Daniel M. Steinberg, Ashfaqur Rahman, Edwin V. Bonilla, Cheng Soon Ong
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [144] SplatSeg3D: Efficient Zero-Shot 3D Segmentation via Point Cloud Surfelization and Splatting

**链接**: https://arxiv.org/abs/2611.32716
**作者**: Sandeep Inuganti, Mahdi Chamseddine, Marcel Rogge, Martin R. Oswald, Didier Stricker, Jason Rambach
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Open-vocabulary 3D segmentation methods rely on 2D foundation models applied to registered images captured alongside the 3D point clouds. However, such images may not be available in many cases, while direct 3D point cloud segmentation methods require semantic class supervision and are challenging to deploy in a zero-shot manner. To address these issues, we present SplatSeg3D, which segments a bare colored point cloud in an open-vocabulary manner without requiring the accompanying images, camera poses, class supervision, or instance mask proposals. To achieve this, we first surfelize the input point cloud and obtain oriented 2D Gaussians. We then render views of the scene by splatting, with a view selection strategy that maximizes scene coverage with as few views as possible. Next, we apply text-prompted segmentation on the rendered views, giving each 3D point a set of multi-view semantic cues, fused to produce a 3D segmentation of the scene. We evaluate SplatSeg3D on semantic segmenta

---

### [145] Tabra Blends: Improving the Accuracy--Latency Trade-off with Complementary Tabular Models

**链接**: https://arxiv.org/abs/2611.32859
**作者**: Jing Jia, Guanyang Wang
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tabular foundation models make different trade-offs between prediction accuracy and latency. We study whether a compact ensemble can deliver higher accuracy in less time. Across 816 TabArena splits, our blend of four-estimator Kumo and one LimiX pipeline reaches 2063.8 Elo, 45.4 points above the top published entry in the same fit. Its normalized fit + predict time is 15% lower than Kumo-16's and 98% lower than full LimiX's. We find that greater prediction diversity between the two models helps explain the reduction in error.

---

### [146] Reading Between the Layers: Where Representation Quality Lives, and What Geometry Reveals

**链接**: https://arxiv.org/abs/2611.31496
**作者**: Arnesh Batra, Aniket Khandelwal, Arush Gumber, Krish Thukral, Kushagra Agrawal, Dev Sharma
**来源**: cs.CL cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Representation quality in pretrained text foundation models is not concentrated at the final layer, yet practitioners routinely probe it there because layer selection without labels has remained an open problem. We present a large-scale empirical study of where layer quality lives across 25 models spanning four architectural families and four pretraining strategies, evaluated on 13 datasets across classification, pair classification, semantic textual similarity, and multiple-choice question answering. Peak probing layers depend systematically on pretraining strategy and architecture: masked encoders peak in late-middle layers, sequence-to-sequence models shift their peak with task type, contrastive sentence encoders concentrate signal at the final layer under CLS and last-token readouts but peak early under mean pooling, and decoder-only models exhibit distinct phase structure tied to depth. We distill these findings into the Stable Geometry Index (SGI), a closed-form, fully label-free

---

### [147] Representation and Model Contributions on Small Molecular Benchmarks: Controlled Comparisons and External Evaluation

**链接**: https://arxiv.org/abs/2611.32568
**作者**: Nora A. M. A. Talkhan, Ibrahim Abdelbaky, Fatma A. Omara
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Improvements in molecular property prediction are usually attributed to the model, although part of the gain may come from the molecular representation. New models are commonly benchmarked against a random forest (RF) trained on a molecular fingerprint, a comparison that changes the model and the representation at the same time. We separate the two contributions with a two-by-two factorial design in which the RF and a second model (CatBoost or the tabular foundation models TabPFN and TabFM) are each trained on a fingerprint and on RDKit descriptors, and each effect is tested with a paired scaffold bootstrap. Seven small MoleculeNet datasets (3 regression, 4 classification) are evaluated on the published split of a recent graph transformer (DGT), on 10 additional scaffold splits and on external datasets. For solubility and lipophilicity, the representation effect exceeds the model effect in every main factorial design, in all three evaluations. For hydration free energy, the result depe

---

### [148] Visual Thinking: Training-Free Active Perception for Counting and Localizing Hard-to-Find Objects

**链接**: https://arxiv.org/abs/2611.31973
**作者**: Emil Kielar, Pratik Chaudhari
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Vision foundation models can precisely segment objects based solely on a text prompt. However, they struggle to recover objects that are small, occluded or whose appearance is poorly captured by the original textual description. Vision language models can examine the image and its context, they can propose richer descriptions of the objects to be detected. But these models struggle with precise segmentation and localization. We introduce Visual Thinking, a training-free framework that combines a vision-language model with Segment Anything Model 3 (SAM 3) through an iterative active perception loop. At each iteration, the VLM proposes short noun phrases using the image, candidate crops and history from past iterations. A controller ranks these phrases using embedding similarity between the original prompt and the proposal, an entropy-based verification priority and the novelty of the prompt. Next, SAM 3 uses prompts to detect objects in the image. We associate detections across iteratio

---

### [149] VLG-Drive: Unifying Vision-Language and Geometric Priors for Autonomous Driving

**链接**: https://arxiv.org/abs/2611.31952
**作者**: Junge Zhang, Jie Zhu, Yanqi Jia, Xiangyu Xu, Zixun Huang, Wenbin He 等 (9 人)
**来源**: cs.CV cs.RO
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A driving planner needs both scene semantics, which vision-language models (VLMs) provide, and spatial structure, which geometric foundation models recover from visual history. We present VLG-Drive, which keeps both models frozen and trains only a fusion interface and a planner from trajectory labels. At each camera-grid cell, the interface fuses the paired VLM and geometry features into one joint token through a geometry-anchored residual, and a command-conditioned planner reads these tokens to predict the ego trajectory. VLG-Drive achieves 31.78 EPDMS on NavHard under perturbed initial states, the highest among the compared methods, and 88.27 PDMS on NavTest from cameras alone. Pointwise fusion outperforms independent VLM and geometry streams on both benchmarks. In closed-loop driving on 420 HUGSIM scenarios, VLG-Drive outperforms all compared planners. These results indicate that a lightweight planner trained on fused features of frozen vision-language and geometric foundation model

---

### [150] Seeing to Drive on a Single Board: Attention-Free Depth for Onboard Robot Navigation

**链接**: https://arxiv.org/abs/2611.32718
**作者**: Itai Mizlish, Boaz Ben-Moshe
**来源**: cs.RO cs.CV cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A small ground robot can carry one camera and a few watts of compute, but the depth foundation models that could turn that camera into a range sensor are vision transformers sized for GPUs. We bring one to a Raspberry Pi 5 with the Hailo-8L, an accelerator that runs every layer in integer arithmetic, attention included. Quantised for it, Depth Anything V2 loses large parts of the scene, and we measure why: at 449 tokens, 91% of softmax weights fall below one int8 step while carrying 17-33% of the attention mass. Our answer is to distil, not quantise. An attention-free ResNet-34 U-Net student of Depth Anything V2-Large (24.5M parameters) runs at 27.1 FPS on the chip, its int8 output matches its float twin (Pearson 0.99993), and on held-out scenes of its simulated yard it is the most accurate depth network on the chip (AbsRel 0.269 against 0.354-0.530). On 1,000 stereo-verified points of a real outdoor drive it is not resolvably different from the vendor's Depth Anything V2-Small build, 

---

### [151] On the Capabilities and Limitations of Zero-Shot Open-Vocabulary Cloud Segmentation

**链接**: https://arxiv.org/abs/2611.32625
**作者**: Jose Sosa, Thomas Gillet, Rim Sleimi, Albert Abello
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent advances in vision-language foundation models have enabled open-vocabulary semantic segmentation (OVSS) without task-specific training, offering new opportunities for Earth Observation (EO) applications. However, their capabilities for cloud detection remain insufficiently explored. In this work, we evaluate twelve OVSS approaches across six publicly available EO datasets in a zero-shot setting, i.e., without fine-tuning or adaptation to the target data. We investigate both binary cloud detection and multiclass segmentation, distinguishing between thick clouds, thin clouds, cloud shadows, and background. Our results show differences in performance across models and datasets, with SegEarth-OV3 achieving the highest binary cloud detection performance on four of the six datasets. While several approaches demonstrate promising performance in binary cloud detection, multiclass segmentation remains more challenging, particularly when distinguishing between fine-grained cloud categorie

---

### [152] MaskedVGGT: Masked Multi-View Transformers Are Scalable 3D Learners

**链接**: https://arxiv.org/abs/2611.32297
**作者**: Zichen Zou, Xiaosong Jia, Wen-Ming Chen, Zuxuan Wu, Yu-Gang Jiang
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-view feed-forward models show strong scalability, but their reliance on costly geometric annotations limits data scaling. Existing 3D self-supervised approaches reduce this reliance through cross-view completion (e.g., CroCo, MuM, Muskie) or novel-view synthesis (e.g., RayZer, E-RayZer), typically learning image representations and cross-view interactions jointly. We argue that learning single image representations from scratch is unnecessary for 3D pretraining methods, as doing so fails to benefit from the continuing advances in 2D foundation models (e.g., DINO, CLIP, frontier VLMs). We introduce MaskedVGGT, which freezes a strong pretrained 2D encoder and pretrains only an added, randomly initialized multi-view transformer, focusing on learning interactions across views. MaskedVGGT pretrains the multi-view transformer through masked self-distillation without annotations: a student predicts targets at masked locations based on complete anchor views and heavily masked remaining v

---

### [153] Seldon TFM family: Seldon-Mini, Seldon and Seldon+

**链接**: https://arxiv.org/abs/2611.32257
**作者**: Stanislas Angebault, Nicolas Atienza, Nicola Cancedda, Aziz Fouch\'e, Salom\'e Gobbi, Ekaterina Iakovleva 等 (10 人)
**来源**: cs.LG stat.ML
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We introduce Seldon, a family of tabular foundation models. Our classifier Seldon+ ranks first among 15 models on TabBench, our benchmark of 124 classification datasets, and on its variant with missing values. In our own runs of public benchmarks, it also ranks first on BeyondArena IID classification and TabBench-Bio, and second on TabArena classification. The open-weight models Seldon-Mini (27M parameters) and Seldon (213M parameters) both lie on the TabArena Pareto front of Elo against inference time: no entry is both more accurate and faster. On TabArena, Seldon ranks fourth and Seldon-Mini seventh among 109 leaderboard entries, and on the IID track of BeyondArena, Seldon ranks second among 42 entries. Seldon-Mini and Seldon handle both classification and regression, use an architecture similar to those of Kumo-Tabular, TabFM and TabPFN-3.5, and are trained on synthetic tables only.

---

### [154] OVOK: A Recursive Self-Improving Agentic Framework for Video-Based Articulated Robot State Estimation

**链接**: https://arxiv.org/abs/2611.32185
**作者**: Cheng Dai, Renkai Luo, Guanfeng Tang, Siming Li, Hao Zhao
**来源**: cs.RO cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recovering articulated robot state from video supports metric spatial sensing for manipulation, scene reconstruction, and action planning. Yet the problem is ill-posed: different intrinsics, camera-to-robot poses, and joint angles can explain similar observations. Prior task-specific regressors typically assume known intrinsics, fit one robot through laborious data collection and robot-specific training, and still transfer poorly across scenes. Foundation models apply to any robot zero-shot, but their estimates have large errors. We present OVOK (One Video to Kinetics), a recursive self-improving agentic framework for this task. Under a human-authored protocol, an agentic initializer constructs robot-specific OVOK-4k; a proposer--executor--verifier loop then jointly evolves tools and executable workflows from feedback. Updated tools and workflows are accepted only when the verifier judges a positive improvement. The retained workflow is frozen for accurate inference. Experiments demons

---

### [155] VISOR: A Vision-Language Selector for Multimodal Time-Series Forecasting

**链接**: https://arxiv.org/abs/2611.31780
**作者**: Seunghan Lee, Jun Seo, Junhyeok Kang, Jaehoon Lee, Sangjun Han, Sungdong Yoo 等 (10 人)
**来源**: cs.CV cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent time-series foundation models (TSFMs) forecast a distribution over futures, and multimodal time-series (TS) forecasting further exploits other modalities to improve forecasting accuracy. However, existing works have two limitations: 1) TSFMs reduce the predictive distribution to its median or mean, flattening diverse futures into a calm line, and 2) multimodal TS forecasting models incorporate text into the forecaster through TS-language alignment, which is substantially weaker than vision-language alignment. To address these limitations, we propose the VIsion-language SelectOR (VISOR), a multimodal TS forecasting framework that selects one plausible future instead of averaging across candidates, leveraging the alignment capabilities of vision-language models (VLMs) to select the most suitable candidate based on textual information. VISOR consists of two components: 1) a text-free stochastic predictor that samples diverse candidate futures, and 2) a VLM selector that reads the c

---

### [156] ECLIPSE: Embedding-Centered Foundation-Model Federated Knowledge Transfer for Data-Free Edge Intelligence

**链接**: https://arxiv.org/abs/2611.31527
**作者**: S. Kawa Atapour, S. Jamal Seyedmohammadi, Maryam Hosseini, S. Mohammad Sheikholeslami, Jamshid Abouei, Konstantinos Plataniotis 等 (7 人)
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Foundation Models (FMs) are envisioned to become an integral component of intelligent federated edge networks because of their strong representation and generalization capabilities. However, their integration into resource-constrained and privacy-sensitive edge environments remains challenging. This challenge is particularly pronounced in data-free settings, where no shared, public, or server-accessible reference dataset is available to establish a common reference space for aligning distributed knowledge. To address this challenge, we propose ECLIPSE, which is an embedding-centered FM-based federated knowledge transfer framework developed for data-free edge intelligence. ECLIPSE enables edge intelligence capitalizing on a server-hosted FM without sharing raw data, local models, or a public reference dataset. It establishes a shared embedding reference space through which edge devices encode their local task knowledge. Only the resulting embeddings are transmitted to the server for ali

---

### [157] COHERE4D: Training-Free Dense Surface Alignment for Coherent Metric 4D Human-Scene Reconstruction

**链接**: https://arxiv.org/abs/2611.32482
**作者**: Zhumei Wang, Shaofei Wang, Xiang An, Mingtao Pei, Siyuan Huang
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Human and scene foundation models offer complementary strengths for monocular 4D reconstruction: human models recover metric-scale body meshes but lack scene grounding, whereas scene models estimate globally consistent 3D geometry and camera motion without reliable metric scale. Crucially, both models reconstruct the same foreground human surface. Yet existing methods do not directly exploit this shared surface: lacking reliable foreground human geometry in scene reconstructions, earlier approaches either resort to sparse contact constraints or learn data-driven alignment modules that generalize poorly to out-of-distribution scenes. We present COHERE4D, a training-free framework that directly registers the human surfaces predicted by independently pretrained human and scene foundation models to reconstruct a coherent, metric 4D world. COHERE4D establishes dense, pixel-aligned 3D correspondences over the visible human surface and employs RANSAC with cross-frame consensus to suppress out

---

### [158] GeoSurge: Geometry-Grounded Multimodal Reasoning for Auditable Liver Resection Planning

**链接**: https://arxiv.org/abs/2611.32657
**作者**: Wenjie Deng, Zijian Tu, Xueyin Zhou, Huayi Wang, Zhuoyun Du, Mingyu Chen 等 (8 人)
**来源**: cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Surgical resection planning centers on generating executable resection surfaces from anatomical evidence and operative constraints. Medical multimodal foundation models enable anatomical understanding, and segmentation models predict resection regions, but neither translates these capabilities into explicitly constrained, executable resection surfaces. We present GeoSurge, an anatomy-grounded framework that combines mask-derived metrics with structure-aware point-cloud tokens to generate executable, editable resection surfaces. To make resection geometry learnable and editable, GeoSurge maps actions to parametric geometry through a surface-action grammar. Using this grammar, anatomy-oriented and tumor-centered templates generate candidates, which are filtered by hard constraints and semantic deduplication. Training supervision is then derived from candidate-expert geometric agreement and independently recomputed feasibility metrics. At inference, the reasoner uses patient evidence and 

---

### [159] Hybrid AI for AI-Native RAN Control: A Functional Perspective

**链接**: https://arxiv.org/abs/2611.33035
**作者**: Sabrine Aroua, Osama Arouk, Pegah Alizadeh
**来源**: cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> AI-native radio access network (RAN) control involves interdependent decisions across network entities, protocol layers, and timescales. Understanding how AI and conventional methods can jointly support these decisions requires a common basis for comparing their functional roles. This survey introduces a technique-agnostic taxonomy of RAN decision-making organized around four complementary capabilities: Representation and Reasoning, Prediction and Simulation, Adaptive Control, and Decision Synthesis. These capabilities are defined by their roles in the control process, independently of the techniques used to implement them. Through this perspective, we examine representative AI and model-based approaches, including foundation models, world models, reinforcement learning, and optimization. We then apply the taxonomy to representative RAN control solutions across slow, medium, fast, and cross-timescale applications to identify which capabilities they implement and how these capabilities 

---

### [160] Progressive Reliable Supervision for Black-Box Universal Domain Adaptation

**链接**: https://arxiv.org/abs/2611.32474
**作者**: Jing Li, Zhe Zhang, Huateng Sun, Yuhui Yang, Wanli Xue, Xu Cheng 等 (10 人)
**来源**: cs.CV cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Black-Box Universal Domain Adaptation (B$^2$-UniDA) aims to adapt a target model to an unlabeled target domain under arbitrary label-space relationships, while neither source data nor source-model parameters are accessible during adaptation. Under such restrictive information access, reliable target supervision is unavailable, while predictions from the black-box source model can be unreliable due to source bias and domain shifts. To address this challenge, we propose Progressive Reliable Supervision (PReS), which progressively establishes and refines reliable target supervision by coordinating complementary knowledge from the black-box source model, foundation models, and the evolving target model. PReS first identifies reliable known samples by exploiting semantic consistency under diffusion-based perturbations and cross-model consensus between the black-box source model and CLIP. It then estimates the sample-wise reliability of the two predictors and adaptively integrates their comp

---

### [161] Linear Probes Can Guide: Training-Free Control of Representation Generators

**链接**: https://arxiv.org/abs/2611.33037
**作者**: Pengwei Wang, Jos\'e Morano, Botond Fazekas, Hrvoje Bogunovi\'c
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Representation-space generative models, such as Representation Autoencoders (RAEs), leverage pretrained vision foundation models (VFMs) primarily to accelerate training and improve sample fidelity. Yet VFMs are more than reconstruction tokenizers, as they feature rich representation spaces that are highly organized and linearly readable. We observe that this removes a key obstacle of post-hoc guidance: by linearity of expectation, a clean probe applied to an ideal denoiser's prediction yields the exact posterior mean of the probe scores at any noise level. This regime, which we call Semantic Mean-Space, turns semantic guidance into a Bayesian linear inverse problem, bypassing the need for training-time conditioning. With this foundation, we propose LiSM, a unified framework for Linear Guidance in Semantic Mean-Space. To validate the framework, we developed and adapted different solvers, and characterized them based on how they estimate probe-space uncertainty and propagate the correcti

---

### [162] Xtream: An Explicit Metric State for Large-Scale Streaming Reconstruction

**链接**: https://arxiv.org/abs/2611.31757
**作者**: Ernesto Lozano, Alberto Jaenal and Javier Civera
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> 3D foundation models (3DFMs) enable dense reconstruction in a feed-forward pass, yet their effective span is limited by cross-view attention. Local consistency has been expanded through geometric alignment of video chunks and recursive updates of an implicit memory, and large-scale scenes with pose graphs. However, both strategies are prone to drift, largely due to the lack of metric-scale observability from monocular geometry. We present Xtream,a hybrid streaming pipeline that maintains an explicit metric state through a factor graph over keyframes, while using a 3DFM as a geometric front end. Xtream incorporates metric information in two ways: through metric scale predictions from 3DFMs; or through inertial measurements if available. Across the large-scale benchmarks of VBR, Oxford Spires and KITTI, Xtream achieves state-of-the-art performance in 3DFM-based online reconstruction, reducing average absolute trajectory errors compared with published baselines and concurrent work. https:

---

### [163] Adapt, Label, Distill: Foundation-Model Supervision for Efficient Object Detection

**链接**: https://arxiv.org/abs/2611.31604
**作者**: Zhengye Yang, Anthony Wang, Yuyang Li, Mehmet Kerem Turkcan, Beizhan Yan, Zoran Kostic
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Object detectors often transfer poorly to specialized domains, where box annotations are scarce and deployment requires compact, real-time models. Large vision foundation models can provide offline supervision, but their zero-shot predictions may be poorly aligned with the target domain. We present an adapt-label-distill pipeline that uses limited target annotations to specialize a foundation teacher and transfer its supervision to compact detectors. We adapt SAM3 on the labeled subset, generate pseudo-labels for the remaining unlabeled images, and train YOLOv11 students with confidence-guided supervision. Teacher confidence weights pseudo-label losses, while zero-gating retains uncertain hypotheses during assignment without applying their associated training losses. Experiments across six target domains and three student capacities show substantial gains in several domains, while revealing limited or negative transfer in others. Teacher comparisons under a common hard-label training r

---

### [164] On the Effectiveness of Resampling for Supervised Graph Anomaly Detection

**链接**: https://arxiv.org/abs/2611.32598
**作者**: Cyril Perosino (GOAL), Rino Di Chiara (Polito), Hamida Seba (GOAL)
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Class imbalance and scarce anomaly labels motivate oversampling in supervised graph anomaly detection (GAD), but its benefits across detectors and benchmarks remain unclear. In the low-label setting of GADBench, with 20 labelled anomalies and 80 labelled normal nodes, we compare class weighting and up to six oversampling strategies in ten detector configurations from three families: graph neural networks (GNNs), tree ensembles on neighbourhood-aggregated features, and tabular foundation models, on 17 datasets. On the eight datasets with organic anomalies, no strategy has a statistically resolved average gain in any configuration, and which nodes are labelled matters as much as the strategy. On the nine datasets with injected anomalies, Gaussian-noise oversampling (ROSE) gains up to 5.2 AUPRC points in four of the six tree and tabular foundation model configurations, and in all six only on attribute-swap anomalies; in four GNNs its gain is not distinguishable from zero. This gain depend

---

### [165] OmniX: A first jet and event model

**链接**: https://arxiv.org/abs/2611.31403
**作者**: Anna Hallin, Gregor Kasieczka, Henning Rose
**来源**: hep-ph cs.LG hep-ex physics.data-an
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Foundation models are a new approach to building machine learning algorithms for particle physics. Their central idea is that a single model can be adapted to a variety of downstream tasks, amortizing training costs. So far, most foundation model prototypes have operated on the constituents of a single jet. This limits their usefulness for physics problems at the scale of full events, such as distinguishing different processes, and restricts their performance, as global correla- tions are invisible to the model. Here, we introduce OmniX, an architecture that operates on both single jets and whole events within a single model. Using the jet-level JetClass and Top-tagging datasets and the event-level Collide-2V dataset, we demonstrate that OmniX trained jointly on single jets and full events matches or exceeds otherwise equivalent jet-only and event-only models in generation and classification.

---

### [166] Video Models are Excellent Motion Models

**链接**: https://arxiv.org/abs/2611.32432
**作者**: Kian Izadpanah, Ali Mahdavi Amiri, Daniel Cohen-Or, Yiorgos Chrysanthou, Andreas Aristidou
**来源**: cs.CV cs.GR
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Video foundation models have emerged as powerful generators of dynamic visual content, exhibiting remarkable capabilities in synthesizing complex actions and interactions. We argue that these models have also become excellent motion generators, with motion priors that are richer and more general than those learned by dedicated motion models. Their advantage extends beyond visual realism and is manifested in two important aspects: motion naturalness, including coherent body coordination, physical plausibility, and realistic interactions with objects and the environment; and motion scope, encompassing a much broader range of activities and semantic coherence, particularly uncommon, complex, and compound actions. To investigate this position, we introduce a common evaluation framework that compares video and dedicated motion models through three complementary settings: text-only motion generation, reconstruction of video-generated motion from sparse keyframes, and video-based enrichment o

---

### [167] Joint Classification and Generation on Tabular Data: an Empirical Study

**链接**: https://arxiv.org/abs/2611.32225
**作者**: Tim d'Hondt, Oleksii Furman, Damian Kwolek, Jan Por\k{e}ba, Maciej Zieba, Mykola Pechenizkiy
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Many applications of machine learning on tabular data need both a classifier and a generator of realistic records. The default is to train two separate models, whereas a single joint model promises both from one set of weights. Several families of tabular deep learning models can be turned into such a joint model, which raises the question of which joint model is preferable at which computational budget. In this empirical study, we introduce and compare joint models based on four state-of-the-art tabular data modeling families (energy-based models, probabilistic circuits, tabular foundation models and tabular diffusion models) against measured FLOPs and wall-clock time, on 29 classification datasets. Methods are evaluated based on two defined aggregate scores that take into account different aspects of prediction and generation. We then also compare these joint models with every pair of a separate classifier and generator at different computational budgets, to see when a joint model ma

---

### [168] HS-OVSeg: Multi-Granularity Open-Vocabulary Semantic Segmentation in Remote Sensing via Heterogeneous Supervision

**链接**: https://arxiv.org/abs/2611.32518
**作者**: Wei Huang, Chenying Liu, Xudong Kang, Xiao Xiang Zhu
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Open-vocabulary semantic segmentation (OVSS) enables flexible, text-driven mapping of remote sensing (RS) imagery beyond predefined categories. Despite advances in segmentation foundation models, RS-OVSS remains constrained by the scarcity of large-scale, semantically diverse datasets with accurate pixel-level annotations. Meanwhile, existing RS datasets contain abundant scene- and object-level annotations that offer valuable semantic information but lack precise pixel-wise supervision. To exploit these complementary sources, we propose HS-OVSeg, a unified training framework that integrates heterogeneous scene-, object-, and pixel-level supervision for RS-OVSS. Specifically, we generate pixel-wise pseudo-labels using SAM3, conditioned on scene-level class names and object-level class names with bounding boxes. Combined with ground-truth semantic masks, these pseudo-labels enable joint training across all three annotation granularities through LoRA-based fine-tuning of SAM3. Our unified

---
