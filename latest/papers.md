# 📑 论文索引 - 2026-10-07

共 304 篇论文

---

### [1] A Framework for Automated Multi-Source Satellite Data Analytics and LLM-Based Report Generation

**链接**: https://arxiv.org/abs/2610.05625
**作者**: Hind Yousif Alhammadi, Isam Mashhour Al Jawarneh
**来源**: cs.AI astro-ph.IM
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> This paper presents the workflow for building an automated ArcGIS Pro tool using ArcPy to extract the Land Surface Temperature (LST) from Landsat 7, 8 and 9 datasets. The tool eliminates the need for manual band selection and repetitive raster computations by automating the multi-step workflow of radiometric calibration, NDVI-based emissivity correction, and thermal conversion. In addition to supporting batch and single-scene processing, the tool has an optional Large Language Model (LLM) for statistical result interpretation and reporting. Depending on batch size, the tool reduced the processing time from around 11-58 minutes when done manually to around 4-11 minutes using the tool. We tested the tool with data from Ras Al Khaimah (RAK) in the UAE, and the LST obtained for Ras Al Khaimah ranged from approximately 25C to 50C, demonstrating an accurate LST mapping compatible with the weather conditions of RAK. In summary, our tool reduces human errors and improves processing accuracy an

---

### [2] Large Language Model-Guided Discovery of Weight-Five Bivariate Bicycle Codes

**链接**: https://arxiv.org/abs/2610.06623
**作者**: Juan Cruz-Benito
**来源**: quant-ph cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Building on our earlier program-evolution workflow guided by large language models (LLMs), we study weight-five bivariate bicycle (BB) and perturbed bivariate bicycle (PBB) codes. The resulting catalogue contains 1,142 distinct code proposals, including 1,081 nonbaseline proposals attributable to LLM-generated programs. Across the catalogue, we certify connected Calderbank--Shor--Steane (CSS) realizations [[96,4,10]], [[140,6,10]], and [[180,4,14]]. A post-search comparison certifies seven imported Lin--Pryadko archive constructions. For leading parameter triples also represented in that archive, we provide exact distance evidence, explicit bivariate presentations, and verified component reductions. A basis-independent connectivity analysis identifies 409 of the 1,142 catalogue entries as disconnected and shows that 73.1\% of the classes with exact distance certificates contain repeated connected components. Algebraic analysis organizes the connected CSS classes into order-3, order-7, 

---

### [3] Characterizing Parallelism Strategies in LLM Inference: Fundamental Compute-Communication Trade-offs

**链接**: https://arxiv.org/abs/2610.05305
**作者**: Javad Mirzaei, Jeebak Mitra
**来源**: cs.DC cs.AI cs.LG cs.PF
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Model (LLM) inference has become the dominant workload in modern AI systems, requiring serving infrastructures to maximize throughput while meeting strict latency Service-Level Objectives (SLOs). Since state-of-the-art LLMs exceed the compute and memory capacity of a single GPU, inference is commonly distributed across multiple GPUs using tensor parallelism (TP), pipeline parallelism (PP), or hybrid parallelism (HB). However, selecting the most effective parallelism strategy remains challenging due to complex interactions among computation, communication, pipeline utilization, sequence length, batch size, and model architecture. Existing approaches largely rely on empirical evaluation and provide limited analytical insight into the trade-offs among these strategies, particularly across the distinct prefill and decoding phases of inference. In this paper, we present a unified analytical framework for modeling distributed LLM inference under TP, PP, and HB. The framework d

---

### [4] Strong Helps Weak: Directional Cross-Modal Alignment Transfer in Multi-modal LLMs

**链接**: https://arxiv.org/abs/2610.04580
**作者**: Hoigi Seo, Byung Hyun Lee, Minjun Kim, Dohyun Mah, Jongho Lee, Se Young Chun
**来源**: cs.AI cs.CL
**匹配关键词**: LLM, Large Language Model, MLLM
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-modal large language models (MLLMs) achieve strong modality understanding by pairing a large language model (LLM) with an encoder for a target modality such as vision, video, or audio. However, improving an MLLM's capability for a given modality typically requires additional training on large modality-specific datasets, incurring substantial data collection and compute costs. Model merging offers an alternative, but it is often infeasible for data-scarce, large per-sample size, or domain-specific modalities (\textit{e.g.}, audio and video), where same-modality model variants are rarely available. In this work, we characterize an intriguing asymmetric phenomenon: merging a well-aligned, data-rich source-modality MLLM into a data-scarce target-modality MLLM substantially improves the target on its own benchmarks. Our theoretical and empirical analyses show that this gain stems from enhanced alignment between modality-specific and textual tokens, induced by the stronger donor modali

---

### [5] Autonomous Structuring of Radiology Reports Across Modalities at Archive Scale Using an Open-Weight Large Language Model

**链接**: https://arxiv.org/abs/2610.04541
**作者**: Friedrich Puttkammer, Fabian Drexel, Marlene Fritzsche, Era Stambollxhiu, Miriam Kumpf, Lena Schmitzer 等 (10 人)
**来源**: cs.AI cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Purpose: To develop and evaluate an open-weight large language model (LLM) pipeline that converts an entire archive of free-text radiology reports into structured reports without human oversight. Materials and Methods: In this retrospective study, a pipeline with 150 hierarchically organized templates was developed at one center and tested at a second center on reports from 2010 to 2025. The open-weight model gpt-oss-120B selects the template in three constrained-decoding steps and fills it on one local graphics processing unit. Template selection was scored against expert labels on 914 randomly sampled reports of five modalities, structuring quality on 920 radiography and CT reports corrected field by field by five residents. The pipeline then processed the complete archive of the second center. Proportions are reported with Wilson 95% confidence intervals (CIs). Results: An optimal template set was selected for 74.4% of reports (680 of 914; 95% CI: 71.5%, 77.1%) and an appropriate se

---

### [6] DimSteer: Steering LLM Authoring with Automatically Discovered Stylistic Controls

**链接**: https://arxiv.org/abs/2610.04174
**作者**: Ajit Mallavarapu, Ziwei Gu
**来源**: cs.HC cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model writing interfaces often make users steer outputs by repeatedly articulating desired changes in natural language. Yet writers may recognize useful stylistic directions only after seeing alternatives, making revision recall-heavy. We present DimSteer, an authoring interface that samples prompt-local completions, discovers high-variance activation-space axes of variation, labels them, and exposes them as sliders with pole previews, diff comparison, and reset controls. Users can manipulate discovered dimensions, reducing the need to reformulate prompts for each stylistic adjustment. In a within-subjects study with 16 participants against a matched prompt-only baseline, DimSteer reduced mental demand, effort, and frustration while preserving comparable perceived success. Participants valued the surfaced dimensions, yet 15 of 16 disagreed that they would have thought to request the same changes in a prompt. Results suggest prompt-local controls can shift LLM authoring f

---

### [7] LLM-enhanced spatio-temporal learning for grid-level docked bike sharing demand prediction

**链接**: https://arxiv.org/abs/2610.03834
**作者**: Xuxilu Zhang and Francesc Soriguera
**来源**: cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Short-term bike-sharing demand forecasting is complicated by spatial-temporal non-stationarity and the practical difficulty of incorporating unstructured external text into numerical pipelines. Conventional approaches rely on historical flow sequences and fixed graph structures, thereby constraining their accuracy when anomalous social events perturb normal travel patterns. We propose a forecasting framework in which a Large Language Model (LLM) drives a semantic shockwave mechanism that converts free-form urban text, such as municipal event schedules, local news, and transit bulletins, into quantified spatial-temporal perturbation fields. The LLM extracts three physically interpretable parameters per event (intensity, spatial reach, and temporal lag), from which Gaussian decay fields are constructed and injected into a Zero-Inflated Adaptive Spatio-Temporal Graph Convolutional Network (ZI-ASTGCN). To handle the pronounced sparsity of grid-level measurements, the model couples a dual-b

---

### [8] SEA-LM: Egocentric Spatial Audio Understanding for Wearable Microphone Arrays

**链接**: https://arxiv.org/abs/2610.05610
**作者**: Sonal Kumar, Sinan Hersek, Artem Dementyev, Mengzhen Pan, Ishan Chatterjee, Anurag Kumar 等 (9 人)
**来源**: cs.SD cs.AI
**匹配关键词**: Large Language Model, MLLM, Multimodal Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Embodied, ego-centric intelligence fundamentally requires the ability to comprehend spatial audio within complex environments. While large audio-language models excel at mono-channel reasoning, they lack spatial awareness, discarding critical spatial cues that enable sound localization and that can improve the disentanglement of overlapping sound sources. To address this, we present SEA-LM, a Spatial Audio Understanding model. First, we introduce FOACODER, a layout-flexible spatial audio encoder trained on source localization and ego-centric voice activity detection objectives to encode First Order Ambisonics derived from variable-count, variable-position smart-glasses arrays via beamforming. We train a Multimodal Large Language Model (MLLM) to understand these spatial audio embeddings through a two-stage curriculum spanning six tasks, including sound localization and spatially selective transcription in settings with multiple speakers and overlapping sounds. To prevent the transcripti

---

### [9] Retrieval-Augmented Large Language Model Decision-Making for Autonomous Driving Guided by Chinese Philosophical Wisdom

**链接**: https://arxiv.org/abs/2610.03948
**作者**: Xiaojun Bi, Xiaoyuan Ma, Yiwen Sun, Tianren Huang, Chaoran Liu, Bokai Huang 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Autonomous driving decision systems must balance safety, efficiency, and social norms in complex traffic interactions. Philosophical and ethical considerations have received limited attention in existing autonomous driving decision-making approaches based on numerical optimization, sequence prediction, and large language models (LLMs). We propose Chinese Philosophical Wisdom-Guided Driving (CPW-Drive), a closed-loop retrieval-augmented generation (RAG) framework that incorporates value guidance derived from Chinese philosophy into autonomous driving decision-making. Using Chinese Confucian thought as its knowledge source, CPW-Drive consolidates LLM-extracted keywords from relevant classical texts into driving-relevant value principles through manual screening and validation. It then contextualizes these principles through scenario-specific cases to form retrievable and reusable value guidance. We further propose Physics-aware Spatial Similarity Retrieval (PSSR), which compares vehicle 

---

### [10] BazaarBench: Delegation Safety in Decentralized C2C Marketplaces Run by LLM Agents

**链接**: https://arxiv.org/abs/2610.06748
**作者**: Ziyan Wang, Shuqing Shi, James Oldfield, Samuele Marro, Jialin Yu, Philip Torr 等 (8 人)
**来源**: cs.MA cs.AI cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In decentralized consumer-to-consumer (C2C) marketplaces, people list goods, negotiate with strangers, and rate one another, so trust rests on reputation. Large language model (LLM) agents now act for users, raising risks to their money, privacy, and reputation. We introduce BazaarBench, a simulated C2C marketplace and benchmark for evaluating the safety of these agents. It tracks ownership, item condition, and commitments across transactions, combining record checks with rubric-based LLM judgments to identify six failure types across five stages. We run three base markets for 30 simulated days, each with 100 agents using one model and inventories drawn from a public eBay sample. Across 45 continuations, we evaluate five models under ordinary instructions, deadline pressure, or adversarial instructions to exploit other traders. Each continuation runs for seven simulated days from a copy of a market's day-30 state. The tested model controls the same 20 selected agents, retaining their p

---

### [11] An LLM-in-the-loop RL Framework for Bioinformatics Feature Selection

**链接**: https://arxiv.org/abs/2610.05600
**作者**: Xinyuan Wang, Deepti Agrawal, Yanjie Fu
**来源**: cs.LG cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> High-dimensional bioinformatics data, characterized by a large number of features relative to the number of samples, pose major challenges such as the ``curse of dimensionality,'' leading to overfitting, high computational cost, and poor generalization. Traditional feature selection methods often suffer from limited scalability and adaptability in such domains. We propose an LLM-in-the-loop reinforcement learning (RL) framework for bioinformatics feature selection, where the RL agent formulates feature selection as a sequential decision-making task, while the large language model (LLM) enhances the process in two ways: (1) guiding exploration through domain-informed advice, and (2) providing hybrid rewards that integrate data-driven performance with knowledge-driven evaluation. The LLM also produces explanations to improve interpretability for human experts without altering the RL policy update. Experiments on diverse bioinformatics datasets show that the LLM-in-the-loop framework outp

---

### [12] No Hindsight for LLM Fact-Checkers: Measuring Leakage Channels in Misinformation Detection

**链接**: https://arxiv.org/abs/2610.04888
**作者**: Kuan-Hua Wu Lu and Yohanes Andre Setiawan
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As automated fact-checking scales on social media, large language model (LLM) verdict scores can look stronger than warranted. One reason is that evaluations mix in information that was not knowable at claim time. Two channels are easy to conflate: outcomes memorized in pre-training and retrieved evidence published after the claim. Yet standard benchmarks rarely separate the two. In this study we measure both channels on AVeriTeC and QuanTemp++ by reconstructing point-in-time evidence conditions and probing for outcome information encoded in model representations. We find substantial evidence of parametric leakage, that can be hidden by the aggregate accuracy, while a simple representation bottleneck reduces this future leakage more efficiently than a mutual-information-based training penalty. We also find that allowing post-claim evidence inflates zero-shot accuracy by 6.3 points in AVeriTeC while the effect is negligible in QuanTemp++, where retrieval provides little post-claim evide

---

### [13] Agent Behavior as Code: Efficient and Robust LLM Agents with Programmatic Specifications

**链接**: https://arxiv.org/abs/2610.04824
**作者**: Peng Qi, Chunliang Lyu, Gang Li, Fabian Chan, Cheng Chang, Ignacio Cases 等 (7 人)
**来源**: cs.AI cs.CL cs.MA
**匹配关键词**: Foundation Models, LLM
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> AI agents based on foundation models (FMs) have demonstrated strong capabilities to perform complex open-ended tasks. However, they face some common challenges in practice: (a) agent behavior can deviate drastically even for semantically similar tasks, leading to catastrophically propagated errors; (b) high cost and latency due to FM calls, repeated in full whenever a task recurs with different inputs; (c) FMs' limited context and instruction following capability confine how well agents manage the ever-growing execution context and follow complex plans. We introduce $\textbf{A}$gent $\textbf{B}$ehavior as $\textbf{C}$ode $\textbf{Agent}$ (ABCAgent), which uses a symbolic program (e.g., Python code with potential neural functions) to fully specify the agent's behavior at runtime, with a powerful FM agent editing that program for flexibility. Behavior is thus specified without premature variable binding, and its execution is deterministic. We evaluate ABCAgent on six agent benchmarks, tw

---

### [14] When Is Enough Enough in Self-Evolving LLM Systems?

**链接**: https://arxiv.org/abs/2610.04756
**作者**: Enoch Yin, Bin Liu, Zhengling Qi
**来源**: cs.AI cs.LG stat.ML
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Self-evolving large language model (LLM) systems repeatedly propose, evaluate, and incorporate updates to prompts, skills, or other persistent artifacts. Despite their growing effectiveness, these systems typically operate under a predetermined iteration or compute budget, without a principled criterion to determine when further evolution is no longer worthwhile. This can lead to two undesirable consequences: unnecessary computation after performance has saturated and the risk of returning late updates that overfit or exploit the evaluation signal. These issues motivate us to study two fundamental questions: when should a self-evolving system stop, and what should it output once it stops? We address the first by formulating an online sequential testing problem and constructing an anytime-valid restart detector using the per-item paired evaluation outcomes already produced by self-evolving LLM systems. We address the second by formulating a change-point estimation problem and using the 

---

### [15] From Transformation to Target State: Rethinking Query Representation for Zero-Shot Composed Image Retrieval

**链接**: https://arxiv.org/abs/2610.05993
**作者**: Yihe Zhao, Songhe Feng
**来源**: cs.CV
**匹配关键词**: Large Language Model, MLLM, Multimodal Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Composed image retrieval (CIR) aims to retrieve a desired target image from a query consisting of a reference image and a modification text. This task exhibits an unusual representational asymmetry: the modification text specifies a transition from the reference state, whereas retrieval candidates depict completed target states. This creates a representation mismatch for zero-shot methods that query pretrained vision-language spaces directly with transformation-oriented language. We study this mismatch and reformulate zero-shot composed image retrieval as target-state reconstruction followed by retrieval. We instantiate this formulation with ASAP-CIR, a training-free framework that reconstructs a static target representation using a frozen multimodal large language model (MLLM). The representation combines multiple holistic descriptions with a variable set of importance-weighted atomic semantics, thereby preserving both overall target identity and fine-grained visual constraints. Retri

---

### [16] Agentic Cognitive Depth: Operational Criteria for Evaluating LLM Agents

**链接**: https://arxiv.org/abs/2610.04168
**作者**: Nijesh Upreti, Chris Sypherd, and Vaishak Belle
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Agentic large language model (LLM) systems are commonly implemented as an LLM in a loop with Planning, Memory, Tools, and Control Flow. This application-focused view connects agentic LLM research with deployable systems and leaves open how such systems should be evaluated beyond end-to-end task success. Building on this view, we define agentic cognitive depth as a trajectory-level profile across five operational criteria. The profile contains context sensitivity ($C$), temporal continuity ($T$), multimodal coordination ($M$), adaptive interaction ($A$), and metacognitive monitoring ($Mc$). The first four criteria measure how well Control Flow, Memory, Tools, and Planning are used across a trajectory. The fifth measures whether the system monitors and regulates the full run. For each criterion, we give operational proxies and a perturbation procedure, then connect the profile to the agent's world model. We provide the structure needed to extend benchmarks such as GAIA, SWE-bench, WebAre

---

### [17] How RL Reshapes LLM Reasoning: Transferability, Coverage, and Scaling Laws

**链接**: https://arxiv.org/abs/2610.04158
**作者**: Ziheng Cheng, Yixiao Huang, Hanlin Zhu, Somayeh Sojoudi
**来源**: cs.LG cs.AI stat.ML
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent studies on reinforcement learning (RL) report seemingly conflicting evidence about large language model (LLM) reasoning. Training on mathematics can improve performance in other domains, yet gains in Pass@1 can coincide with lower Pass@$N$ than the base model. This raises a fundamental question: does RL expand an LLM's reasoning boundary, or merely reweight its existing reasoning space? We revisit these phenomena across Qwen and Gemma model families, showing both cross-domain gains and forgetting, while coverage at large sampling budgets increases on some tasks and decreases on others. Detailed analysis of solution traces before and after RL indicates a shift in the reasoning strategies the model employs, motivating a two-stage autoregressive policy model that separates \emph{strategy selection} from problem-specific execution. Within this framework, we prove how RL's implicit bias reshapes strategy preferences, allowing gains on some tasks while suppressing strategies required 

---

### [18] LLM-as-Jev: LLMs Are Already Jev-Style Decision Models -- When and How to Fine-Tune Them

**链接**: https://arxiv.org/abs/2610.02076
**作者**: Yinheng Li, Justin Wagle
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [19] ReLope: From Hidden-State Probing to a Decision Module for Multimodal LLM Routing

**链接**: https://arxiv.org/abs/2603.24787
**作者**: Yaopei Zeng, Congchao Wang, Blake JianHang Chen, Lu Lin
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [20] Evaluating PDPL Compliance in E-Commerce Websites: Insights and Lessons Learned from Human and LLM Analyses

**链接**: https://arxiv.org/abs/2602.18616
**作者**: Eman Alashwali and Abeer Alhuzali
**来源**: cs.HC cs.CY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [21] Agentic Trading: When LLM Agents Meet Financial Markets

**链接**: https://arxiv.org/abs/2605.19337
**作者**: Yihan Xia, Panpan You, Taotao Wang, Fang Liu, Han Qi, Xiaoxiao Wu 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [22] CiteCheck: Retrieval-Grounded Detection of LLM Citation Hallucinations in Scientific Text

**链接**: https://arxiv.org/abs/2605.27700
**作者**: Khashayar Khajavi, Shaghayegh Sadeghi, Rise Adhikari, Alexander Tessier
**来源**: cs.DL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [23] Communication Shapes Collective Inference in Self-Adapting LLM Societies: Evidence from Mafia

**链接**: https://arxiv.org/abs/2610.05041
**作者**: Haonan Huang, Joey Xiao
**来源**: cs.MA cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> When does communication help a group identify hidden adversaries, and how does its value change as the group adapts? In Mafia, an informed minority hides inside an uninformed majority whose only evidence is open play. The zero-information game, where each day's vote eliminates a random player, is exactly solved and scores every society; matched-casting comparisons between protocols identify the effect of communication. Societies of 8-100 claude-haiku-4-5 agents (7,416 analyzed games, 1.9M model calls) adapt by rewriting and inheriting private strategy notes. Simultaneous broadcast improves adversary identification over silence in all nine compositions tested (8-46 players). Turn-taking removes most of this advantage; its voting landslides are as frequent as broadcast's but land on mafia near chance (1.08x versus 2.53x). At 70 players, agents reading eight statements per day identify adversaries worse than silent ones, and limited talk is worth less than at 46 players. Adaptation is fas

---

### [24] Active Learning for Communication Structure Optimization in LLM-Based Multi-Agent Systems

**链接**: https://arxiv.org/abs/2605.05703
**作者**: Huchen Yang, Xinghao Dong, Dan Negrut, and Jin-Long Wu
**来源**: cs.MA cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [25] Hidden in the Comments: A Context-Injection Attack Surface in Code LLMs

**链接**: https://arxiv.org/abs/2610.05139
**作者**: Noor Munir, Francesco Quinzan, Stephen Roberts
**来源**: cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Code large language model (Code LLM) assistants generate code from heterogeneous development contexts, including open files, imported modules, pasted snippets, and comments, much of which may originate from untrusted sources. We investigate whether insecure instructions embedded in such contexts can steer Code LLMs toward vulnerable code without access to model weights or training data. We evaluate ten open-weight Code LLMs spanning 3B--13B parameters, including four base and six instruction-tuned models, across ten web-application weakness classes. We compare completion tasks containing insecure instructions embedded as code comments with benign tasks without malicious instructions. Attack-condition completions contained a medium-or-higher weakness in {\bf 77.4--92.3}\% of cases, compared with {\bf 1.7--5.1}\% in the benign condition. Base and instruction-tuned models averaged 86.5\% and 84.5\% vulnerable outputs, respectively; equivalence testing and three matched model pairs indicat

---

### [26] Understanding the Weight Averaging Mechanism in LLM Training for Post-Training Quantization

**链接**: https://arxiv.org/abs/2610.05329
**作者**: Hanzhang Wang, Tianqi Shen, Zonglin Liu, Junze He, Difan Zou, and Ziye Ma
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are typically pretrained in high precision but increasingly deployed with low-precision post-training quantization (PTQ). Recent studies have shown that using weight averaging during pretraining can improve PTQ performance compared with learning-rate decay, suggesting that it might provide a simple way to improve the pretraining-to-quantization transition. But the mechanism behind weight averaging remains insufficiently explained. This leads to inconsistent and fragile performance gains, thereby preventing practitioners from applying such a technique confidently. As a response, we formulate weight averaging as a trade-off between retaining training progress and improving robustness under perturbation. We further derive a continuous family of averaging kernels that unifies conventional strategies and achieves the Pareto frontier between the two competing goals. Critically, a theoretical framework for performing weight averaging under PTQ is developed. It can

---

### [27] Adaptive Information Control for Search-Augmented LLM Reasoning

**链接**: https://arxiv.org/abs/2602.01672
**作者**: Siheng Xiong, Oguzhan Gungordu, James C. Kerce, Faramarz Fekri
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [28] Logit-Aware MIMO AirComp for Distributed Mixture-of-Experts LLM Inference over Wireless Edge Networks

**链接**: https://arxiv.org/abs/2610.03741
**作者**: Lyutianyang Zhang, Yunjian Jia, Liu Cao, Dengke Wang, Jinke Ren, Shuguang Cui
**来源**: cs.IT cs.AI cs.LG math.IT
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Distributed mixture-of-experts (MoE) inference is a promising architecture for deploying large language models (LLMs) at wireless edge networks because sparse experts can be placed across coordinated base stations (BSs), while the anchor node and user equipment (UE) can offload LLM inference tasks to BSs. The communication bottleneck is the MoE aggregation, where the anchor BS must recover a weighted sum of selected expert outputs before each decoding step. Over-the-air computation (AirComp) is well matched to this operation because the wireless multiple-access channel naturally superposes simultaneous transmissions. However, conventional AirComp minimizes communication distortion, whereas MoE aggregation errors have unequal impact on LLM outputs. We propose a logit-aware MIMO AirComp framework that estimates local logit sensitivity as block-level weights and jointly optimizes receive combiners and BS precoders under per-BS power constraints. We also develop an alternating algorithm th

---

### [29] RPTune: Learned Context Curation for LLM Catalog Search

**链接**: https://arxiv.org/abs/2610.00964
**作者**: Chuxuan Hu, Hejie Cui, Norman Huang, Shubham Kumar Bharti, Wang-Chiew Tan, Sercan \"O. Ar{\i}k
**来源**: cs.IR cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [30] Robust Parameter-Efficient LLM Adaptation on Analog Hardware

**链接**: https://arxiv.org/abs/2610.05318
**作者**: Jindan Li, Zhaoxian Wu and Tianyi Chen
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Analog in-memory computing is a promising platform for on-device execution of large language models because it performs matrix--vector multiplications (MVMs) in memory and in parallel, reducing data movement. However, limited digital-to-analog converter precision, input noise, and finite conductance states can degrade model accuracy, while full-model retraining to address these effects can be costly. We develop an optimizer-agnostic, parameter-efficient adaptation method based on Low-Rank Adaptation (LoRA), keeping the pretrained weights stored on analog arrays fixed while training the LoRA weights to adapt to downstream tasks and hardware non-idealities. Reliable adaptation requires handling errors in both forward and backward MVMs and physical weight updates. We use input reshaping to reduce input-induced MVM errors and update accumulation to retain small updates before programming them to finite-state analog devices. Across Llama-3.2-1B-Instruct and Llama-3-8B with both Muon and Ada

---

### [31] Clean: Second-order LLM Training at Linear Memory Cost via Nystr\"om Sketching

**链接**: https://arxiv.org/abs/2610.04204
**作者**: Beheshteh T. Rakhshan, Sahar Rajabi, Maziar Sargordi Shikai Fang, Guillaume Rabusseau, Sirisha Rambhatla
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Training large language models (LLMs) entails a fundamental trade-off: memory-efficient optimizers such as Adam discard cross-parameter curvature, whereas full-curvature methods such as SOAP can accelerate convergence at prohibitive memory costs. We introduce Clean, a memory-efficient and full-curvature optimizer designed to resolve this bottleneck. Clean leverages the randomized Nystrom method to accurately approximate the left and right preconditioners in SOAP, and to reduce the optimizer's memory complexity from quadratic to linear in terms of model dimensions. We subsequently reintegrate the off-subspace components to capture curvature information beyond the low-rank approximation, preserving rich curvature at minimal memory cost. We further propose Q-Clean, a low-precision variant that aggressively compresses optimizer states. Q-Clean reduces optimizer memory consumption by \textbf{over 50\%} compared to Muon when pre-training a LLaMA-1.3B architecture, all while maintaining stron

---

### [32] Correct Verdicts, Flawed Reasoning: Structured Auditing of LLM-based Vulnerability Reasoning

**链接**: https://arxiv.org/abs/2610.06366
**作者**: Boyue Caroline Hu, Kaivalya Ahir, Ronghao Ni, Limin Jia
**来源**: cs.CR cs.LG cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) are increasingly deployed for automated software vulnerability analysis. Binary classification alone is insufficient; practitioners need explanations to triage bugs and engineer patches. Standard practice relies on Chain-of-Thought (CoT) prompting, but free-form reasoning allows models to obscure logical leaps, hallucinated execution steps, and internal inconsistencies behind plausible prose. Our manual audit reveals that approximately 60% of correct vulnerability verdicts are accompanied by fabricated or unverifiable claims, and free-form explanations allow reasoning errors to evade LLM-as-a-judge evaluation. We present Vulnerability Explanation Reasoning Auditor (VERA), an automated framework for auditing LLM vulnerability reasoning. Rather than accepting free-form text, VERA asks models to output a Structured Reasoning Record (SRR) encoding tracked pointers, memory operations, and state transitions in machine-readable fields. A multi-stage judge audits e

---

### [33] FormuEvo: LLM-Guided Evolution for Discovering Solver-Efficient Mixed-Integer Programming Formulations

**链接**: https://arxiv.org/abs/2608.23353
**作者**: Haofeng Yuan, Jianing Peng, Jieyi Bi, Ni Zhang, Shiji Song, Zhiguang Cao
**来源**: cs.CL cs.NE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [34] Towards LLM Agents for Earth Observation

**链接**: https://arxiv.org/abs/2504.12110
**作者**: Chia Hsiang Kao, Wenting Zhao, Cheryl Lam, Aarush Umap, Shreelekha Revankar, Samuel Speas 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [35] Proxy Confidence: Auditing Black-Box LLM Agents with a Surrogate's Log-Probabilities

**链接**: https://arxiv.org/abs/2610.03894
**作者**: Yikai Zhao, Saurabh Pandey, Pradeep Kumar Misra
**来源**: cs.AI cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A deployed LLM agent emits tool calls, queries, and code that can be silently wrong -- by the time the error surfaces, the action has run. Frontier chat APIs hide the model's token probabilities; the agent's stated confidence barely beats chance on the mistakes that matter; and resampling does not help, since frontier models are highly repetitive, reproducing the same call across samples. We recover the missing signal from a low-cost open-weight surrogate run in parallel. It reads the same context, schema, and proposed action as the agent, then scores the call from its own log-probabilities through a family of complementary readouts: teacher forcing and request-PMI weigh the likelihood of each argument value, a discriminative verdict judges the call as a whole, and tool-choice competition tests the function against its siblings. One principle says which to trust: a generative likelihood localizes wrong argument values, while the verdict catches holistically wrong calls. When the error 

---

### [36] INMS: Memory Sharing for Large Language Model based Agents

**链接**: https://arxiv.org/abs/2404.09982
**作者**: Hang Gao, Yongfeng Zhang
**来源**: cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [37] PB-GRPO: Learning Socially Adaptive LLM Agents from Persona-Driven Simulation with Preference-Batched GRPO

**链接**: https://arxiv.org/abs/2610.04132
**作者**: Jingquan Wang, Jun Yin, Xu Han, Yongsheng Mei, Jie Hao, Bin Guo
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Building LLMs that behave well socially, not merely correctly, requires Building LLMs that behave well socially, not merely correctly, requires more than producing locally helpful responses. A socially competent agent must infer users' unstated goals, respect their preferences, and adapt as the conversation unfolds. These behaviors are inherently multi-turn and social, making them hard to optimize: real interaction data is scarce, and user preferences are typically latent rather than directly observable. To address these challenges, we build on a persona-driven social simulation environment (consisting of a persona library, LLM-based user simulators, and a user-satisfaction scoring system ranging from [0, 1]), to introduce preference-batched GRPO (PB-GRPO), a post-training algorithm that learns socially adaptive policies from conversation-level feedback. Compared to vanilla GRPO, PB-GRPO computes advantages using a normalization estimated across a bucket of users with similar preferenc

---

### [38] Building LLM Agent Systems the Deep Learning Way: From Modular Design to Architecture Search

**链接**: https://arxiv.org/abs/2610.04961
**作者**: Tao Feng, Pengrui Han, Zhongjie Dai, Jiaxuan You
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) have revolutionized AI research and enabled exciting agent systems. To build a complex LLM agent system, most existing research relies on insights from other domains or heuristics to manually build the agent system. However, this approach often requires heavy hand-engineering and fails to fully optimize for the downstream task of interest. Inspired by the tremendous success of deep learning, we propose to construct LLM agent systems in a modular manner, similar to building a deep neural network. Our key insight is to make analogies between LLM building blocks, such as retrievals, memories, and prompting strategies, and the successful deep learning modules, such as MLPs, attention, and recurrent modules. We further design forward inference and feedback mechanisms for LLMs, where prompts in LLMs are considered as the weights in deep models, and the prompt optimization from feedback is analogous to the back-propagation algorithm. We additionally leverage a sea

---

### [39] CURIO: Curiosity-Driven Test-Time Learning for Open-Ended Discovery

**链接**: https://arxiv.org/abs/2610.04851
**作者**: Tao Feng, Fangxu Yu, Zijie Lei, Jiaru Zou, Changjiang Jiang, Yi Yan 等 (8 人)
**来源**: cs.LG cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Open-ended discovery requires learning from repeated attempts while continuing to explore directions whose value is not yet apparent. Search with a frozen large language model (LLM) can reuse previous solutions in context, but cannot update the model from its successes and failures on the test problem. Reinforcement learning (RL) enables such adaptation; however, strongly favoring high-reward trajectories may suppress low-reward yet potentially promising directions too early. We introduce CURIO, a curiosity-driven test-time learning framework that complements task feedback with an Intrinsic Curiosity World Model (ICWM). The ICWM learns transitions in the policy's hidden-state representation and supplies prediction-error bonuses at sampled tokens outside the policy's top-k choices. Epoch normalization and an annealed weight regulate their contribution to the policy update. On six mathematical discovery tasks and single-cell denoising with Qwen3 backbones from 8B to 235B, three-run means

---

### [40] More Value per Key: Asymmetric Sparse Attention for Faster LLM Decoding

**链接**: https://arxiv.org/abs/2610.04753
**作者**: Noam Elata, Itay Lamprecht, Mikey Shechter, Daniel Ohayon, Itay Hubara, Daniel Soudry
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> utoregressive generation in Large Language Models (LLMs) is constrained by the memory and computational demands of attention mechanisms. Sparse attention methods mitigate this cost by selecting only high-probability entries of the attention matrix. We observe that in many such methods, this renders the probability-value multiplication negligible, shifting the bottleneck to the query-key step. Key heads can therefore be reduced to accelerate inference, while retaining more value heads preserves capacity with limited additional decoding cost. We introduce Sparse Asymmetric Group-Query Attention (SAGA), which decouples key and value head counts to exploit this principle, and pair it with approximate top-N (Atop-N) attention, a simple sparse attention method designed to study the interaction between sparsity and head-count asymmetry. We formalize the benefits of this asymmetry theoretically and validate them empirically through latency measurements and quality evaluations on models up to 1

---

### [41] MASBench: Benchmarking LLM-based Multi-Agent Collaboration under Partial Observability

**链接**: https://arxiv.org/abs/2610.04672
**作者**: Qizhi Chu, Zekai Yu, Sijie Wen, Yang Liu, Chen Qian, Cheng Yang 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) have progressively evolved into the core of autonomous agents. Building on this progress, LLM-based multi-agent systems (MAS) coordinate multiple agents into a synergistic team to accomplish complex tasks that exceed the capabilities of individual agents. The effectiveness of such systems depends not only on the agents themselves, but also on how collaboration mechanisms are designed and organized. Note that real-world collaboration is typically partially observable, where each agent can only access partial information about the environment due to physical or privacy-related constraints. However, many existing multi-agent benchmarks assume global observability, and leave limited support for systematically evaluating collaboration mechanisms. To bridge this gap, we introduce MASBench, a multi-agent collaboration benchmark designed under partially observable constraints. It is organized into three progressive task categories: Reasoning, Scheduling, and Game. 

---

### [42] CCQ: A Multi-State Child Care Quality Dataset to Support AI for Children's Health Research

**链接**: https://arxiv.org/abs/2610.05863
**作者**: Victor Li, Yuzhang Xie, Ziwei Dong, Qingyang Zhu, Wenjing Ma, Carl Yang 等 (9 人)
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models, LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> High-quality child care in early life is a critical determinant of children's growth and development. Research on child care quality has been constrained by fragmented, non-research-friendly, and privacy-bound datasets. We present CCQ (Child Care Quality), a large-scale, de-identified dataset for applied data science research at the intersection of AI and early childhood health. CCQ integrates 59,372 child care provider records across 12 U.S. states, covering diverse provider types as well as data schemas. To ensure research utility while protecting privacy, we implement an automated, LLM-based curation pipeline that anonymizes, cleans, and standardizes raw state records into two complementary releases: a cleaned textual release and a fully preprocessed tabular release. We also benchmark traditional machine learning models, tabular foundation models, and language models on quality rating prediction and important features analytics. Within a state, tabular classifiers on the preprocesse

---

### [43] AdaEva: Accelerating LLM-Driven Algorithm Design with Adaptive Partial Evaluation

**链接**: https://arxiv.org/abs/2610.03896
**作者**: Tai Nguyen, Fei Liu, Phong Le, Carola Doerr, Nguyen Dang
**来源**: cs.LG cs.NE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) are increasingly used for automated algorithm design. However the computational cost of evaluating the generated algorithms can be excessive. We consider the common LLM-driven automated algorithm design (LLM4AD) setting in which a candidate algorithm is evaluated by aggregating its performance over a shared set of training instances. This instance-wise structure raises a natural question: must every candidate be evaluated on the entire instance set before deciding whether it remains competitive? Taking inspiration from algorithm configuration, we introduce AdaEva, a drop-in adaptive partial-evaluation framework that progressively evaluates candidates on larger subsets of the same instance pool and eliminates unpromising candidates as evidence accumulates. Importantly, AdaEva leaves the underlying LLM4AD procedure and per-instance evaluator unchanged and requires no prior knowledge about instance difficulty. We instantiate this idea using successive halving 

---

### [44] A Model Can Help Itself: Reward-Free Self-Training for LLM Reasoning

**链接**: https://arxiv.org/abs/2510.18814
**作者**: Mengqi Li, Lei Zhao, Anthony Man-Cho So, Ruoyu Sun, Xiao Li
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [45] ArticuTable: Generating Instance-Level Interactive Rigid-Articulated 3D Tabletop Scenes from a Single Image

**链接**: https://arxiv.org/abs/2610.05249
**作者**: Kai Lv, Yibo Yin, Lijun Guo, Heng Fan, Kaihao Zhang, Xingping Dong
**来源**: cs.CV
**匹配关键词**: Large Language Model, Multimodal Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Embodied agents benefit from 3D environments that combine visual fidelity to real-world observations with physical interactivity. Existing single-image tabletop reconstruction methods recover plausible scene geometry but typically represent objects as monolithic rigid bodies, limiting interaction to whole-object rigid motion and precluding executable part-level articulation. Meanwhile, recovering a scene layout consistent with the input view remains challenging because a single observation may admit multiple plausible pose-scale configurations. We present ArticuTable, a single-image 3D tabletop reconstruction framework that recovers both executable part-level articulation and an input-view-consistent scene layout. For object modeling, we introduce generation-robust articulation modeling (GRAM), which combines joint fitting guided by a multimodal large language model with semantic state reasoning to recover reliable joint parameters and valid motion ranges from imperfect monolithic prox

---

### [46] Lie Rarely, Lie Big: Stealthy Insider Attacks on LLM Robot Teams

**链接**: https://arxiv.org/abs/2610.04744
**作者**: Sribalaji C. Anand and George J. Pappas
**来源**: cs.RO cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> When a team of robots delegates planning and mutual trust to LLM agents, a single compromised robot can corrupt the shared outcome. We study this threat in a grounded task: a multi-robot survey in which measurements can be verified against the physical world, but every verification costs budget that would otherwise advance the mission. We treat the compromised robot as a stealthy adversary in the system-theoretic sense: it is limited not by an energy bound but by the team's own detectors. We then derive two bounds. First, the probability that the adversary's reports are verified is bounded below in terms of the degrees in the communication graph and the verification budget. Second, the map error caused by any stealthy adversary is bounded above by the value of a linear program over the adversary's bias distributions; its solution is an exchange rate between stealth budget and damage: below a critical verification level the worst stealthy attack tells rare, full-magnitude lies on the re

---

### [47] ASCENT: Online Test-Time Training of Long-Horizon Agents via Self-Distillation of Verified Experience

**链接**: https://arxiv.org/abs/2610.05303
**作者**: Haodong Lu, Dong Gong
**来源**: cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A large language model (LLM) agent solves long-horizon tasks through many reasoning-action turns, with one verification signal at termination. Deployed agents face streams of related tasks, making their trajectories a natural resource for improvement. In-context adaptation agents store reflections, memories, or skills as text, so reuse depends on retrieving the right experience and on a frozen policy executing it. We study Online Agentic Test-Time Training (OaTTT), which trains the LLM's weights on its own execution trajectories during deployment. The agent executes each task once, in one pass over the stream, and the executed trajectory with its verification result is the only learning signal for weight updates that persist across tasks. Directly imitating or reinforcing the generated tokens of this single attempt destabilizes the policy. We introduce ASCENT (Agentic Self-distillation for Cross-task EvolutioN at Test-time), which instead self-distills verified experience. A stable ver

---

### [48] Representational Control over Self-Report & Behavior Coherence in LLM Risk-Taking

**链接**: https://arxiv.org/abs/2610.04125
**作者**: Rafal Kocielnik, Peiyang Song, Pengrui Han, Myrl G. Marmarelis, Ramit Debnath, Dean Mobbs 等 (7 人)
**来源**: cs.CL cs.AI cs.CY cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Self-report is an appealing low-cost probe of an LLM's dispositions, but recent work finds only selective agreement between what models report and how they behave. Prior accounts establish these patterns by prompting black-box LLMs, leaving open whether the gap is a prompting artefact or a fact about how the underlying constructs are represented internally. We investigate risk-taking, a consequential dimension of agentic decision-making, using activation steering to measure self-report and behavior under the same internal intervention. We survey nine steering-vector extraction methods spanning task-specific directives, the model's own task behavior, and dispositional descriptions at two granularities, evaluated on two behavioral tasks and two psychometric instruments across four open-weight LLMs. We find that (1) a shared internal intervention does not ensure shared responsiveness: directions built from trait descriptions move self-report but leave behavior at chance, directions built 

---

### [49] ANT: A Multi-Granularity Network Traffic Dataset and Benchmark for Agents Behavior Auditing

**链接**: https://arxiv.org/abs/2610.06514
**作者**: Fan Li, Xiangyu Gao, Zixuan Liu, Tong Li, Chuanpu Fu, Ziqiang Wang 等 (7 人)
**来源**: cs.AI cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The growing adoption of large language model (LLM) agents creates a need for network administrators and security teams to audit agent behavior within organizational networks without inspecting private user content. Network traffic offers an observable source of evidence, but how much it reveals about agent tasks and operations remains unclear. Existing traffic datasets lack the joint task and stage annotations needed to evaluate this question. We introduce ANT (Agent Network Traffic), a dataset providing agent behavior information at risk, scenario, and behavior primitive granularities alongside network traffic. ANT contains 3,114 execution episodes across 20 tasks and five scenarios, comprising 276,417 bidirectional flows and 40,049 behavior primitive segments organized into 47 macro groups. We establish a benchmark for agent risk identification, scenario recognition, and behavior primitive classification using 13 representative traffic analysis baselines. The results show that existi

---

### [50] MS-Exam-Gen: Source-Grounded Benchmark Construction for Evaluating LLMs on Textual Multiple Sclerosis MRI Knowledge

**链接**: https://arxiv.org/abs/2610.06170
**作者**: Abdul Basit, Muhammad Abdullah Hanif, Muhammad Shafique
**来源**: cs.AI cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Biomedical large language model (LLM) evaluation requires auditable assessment of narrow, evolving, source-grounded subspecialty knowledge. Multiple sclerosis MRI (MS-MRI) provides a high-stakes textual-knowledge test case because correct reasoning requires current diagnostic criteria, standardized acquisition and reporting knowledge, longitudinal monitoring concepts, lesion morphology, and recognition of difficult mimics. We present MS-Exam-Gen, a reproducible framework for constructing and auditing a text-based multiple-choice question (MCQ) benchmark for MS-MRI knowledge; it does not evaluate direct MRI image interpretation. MS-Exam-Gen targets source-grounded criteria, protocols, reporting, and differential diagnosis. The framework combines expert-source indexing, exam-oriented topic induction, evidence-grounded MCQ generation, automated quality audits, a same-family consistency screen, and empirical calibration. From a 66-source corpus indexed into 4,289 retrieval chunks, the pipe

---

### [51] Same Game, Different Story: A Minimal Conservative Strategic Robustness Benchmark for Large Language Model Agents

**链接**: https://arxiv.org/abs/2607.19670
**作者**: Seyed Pouyan Mousavi Davoudi, Arshia Gharagozlou, Alireza Amiri-Margavi, Amin Gholami Davodi, Hamidreza Hasani Balyani
**来源**: cs.MA
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [52] LEAF: Growing Trees Without Branching for Speech-Aware Large Language Model Post-Training

**链接**: https://arxiv.org/abs/2606.07610
**作者**: Argyrios Gerogiannis, Yekaterina Yegorova, Mark Hasegawa-Johnson, Venugopal V. Veeravalli
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [53] Evolving LLM-Generated Features for Interpretable Classification

**链接**: https://arxiv.org/abs/2610.03951
**作者**: Jack Butler, Zainab Afolabi, Nikita Kozodoi
**来源**: cs.LG stat.ML
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly used as classifiers, yet they operate as opaque systems whose decisions are difficult to interpret, which complicates their use in regulated domains such as credit scoring or medical diagnosis. We propose an evolutionary framework that iteratively discovers natural language feature definitions (rubrics) for interpretable classification. An LLM generates candidate binary features, evaluates each sample against them, and the resulting vectors can be used to train a transparent classifier such as logistic regression. The feature set evolves over multiple iterations guided by classification errors, per-class activation rates, and feature ablation scores. We evaluate across three benchmarks, including a credit risk dataset representative of regulated domains, comparing single-shot LLM rubrics, evolved rubrics, and direct zero-shot LLM classification. Evolved features improve over single-shot rubrics by +2.9 pp on average and outperform zero-shot

---

### [54] Two Calls, Two Moments, and the Vote-Accuracy Curve of Repeated LLM Inference

**链接**: https://arxiv.org/abs/2605.03379
**作者**: Yi Liu
**来源**: cs.LG cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [55] Validation-Gated Causal Interventions for Interpreting High-Stakes Large Language Model Behavior: A Case Study in Suicidality Detection

**链接**: https://arxiv.org/abs/2606.21078
**作者**: Nafiz Ahmed, Sarah Sharif, Dingjing Shi, Mike Banad
**来源**: cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [56] Spoiler Alert: Narrative Forecasting as a Metric for Tension in LLM Storytelling

**链接**: https://arxiv.org/abs/2604.09854
**作者**: Peiqi Sui, Yutong Zhu, Tianyi Cheng, Peter West, Richard Jean So, Hoyt Long 等 (7 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [57] Before Agent Tells The Lie: Has Deception Already Been Represented?

**链接**: https://arxiv.org/abs/2610.06576
**作者**: Xinling Li, Dadi Guo, Qingyu Liu, Qinghua Mao, Yi R. Fung, Na Zou 等 (8 人)
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM)-based agents can exhibit deceptive behavior during task execution, including hiding failures, fabricating results, or falsely signaling task completion. Existing monitoring approaches mainly detect deception after it appears in observable actions or outputs. In this paper, we investigate whether deceptive behavior can be predicted from an agent's internal representations before it becomes externally visible. We frame deception monitoring as a trajectory-level representation analysis problem and align agent trajectories around key decision points. Using hidden states extracted before these points, we show that future honest and deceptive outcomes can be reliably distinguished, with predictive signals remaining detectable several model calls before the final decision. We further characterize the temporal evolution of these signals: deception-related representations are weak early in execution but become increasingly identifiable as trajectories progress, while 

---

### [58] Efficient Cost-Aware LLM Evaluation via Bayesian Bandit Gittins Indices

**链接**: https://arxiv.org/abs/2609.25645
**作者**: Qian Xie, Yueli He, Nairen Cao
**来源**: cs.LG cs.CL stat.ML
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [59] Fine-Tuning a 3B-Parameter LLM on a Smartphone: Characterizing Sustained Training

**链接**: https://arxiv.org/abs/2610.06325
**作者**: Andrew Geyko, Marius Mosbach, Andr\'e Brinkmann
**来源**: cs.DC cs.AI cs.PF
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-billion-parameter LLMs now run on phones for inference, and training them on the device would personalize them without user data leaving the phone. Prior work has measured individual training steps of such models on phones, but not complete training runs, and not whether adapters trained on the device improve personalization. We present the first systematic characterization of a multi-billion-parameter LLM fine-tuned on a mobile device, covering memory, per-step time, thermal behavior, and energy. An iPhone 17 Pro can fine-tune a 3B-parameter LLM to a typical user within one battery charge, and the resulting adapters improve personalization as much as adapters trained on a server. Sustained training throttles the phone to about half its initial throughput, and none of the pausing or burst schedules we tested recovers it. Nearly all of each training step is spent in the frozen base model, most of it in the backward pass, which nine of the ten other runtimes we audited do not accel

---

### [60] LoGRA: Scaling LLM Reinforcement Learning with Low-Rank Gradient Sketches

**链接**: https://arxiv.org/abs/2610.06647
**作者**: Shaokun Zhang, Yifan Zhang, Jian Hu, Yueying Li, Hao Zhang, Binfeng Xu 等 (8 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reinforcement learning (RL) has greatly advanced the capabilities of large language models (LLMs), but its memory demands remain a barrier to broader adoption. We introduce LoGRA, an approach to RL post-training that reduces memory by retaining useful learning signals in low-rank gradient sketches. These compact representations support both model updates and efficient policy synchronization. To prevent overly large updates from disrupting learning, we complement gradient compression with predicted-KL step control, which estimates policy changes before applying each update and adjusts its magnitude accordingly. Across reasoning tasks, LoGRA reduces average training memory by up to 45.7\% without sacrificing performance. It also enables stable training of a 27B-parameter model for over 1,100 steps on a single eight-GPU node, where dense Adam runs out of memory, making previously memory-infeasible RL training practical. Code is available in the \href{https://github.com/skzhang1/labs-molt/

---

### [61] PACMI: Provenance-Aware Cascading Memory Invalidation for Long-Term LLM Agents

**链接**: https://arxiv.org/abs/2610.05732
**作者**: Yiqi Wang, Jiaqi Liu, Jiaqi Zhang, Zhangkai Wu, Yiqun Duan, Mingkai Zheng 等 (7 人)
**来源**: cs.LG cs.IR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents rely on long-term memory to retain and reuse information when performing tasks over long horizons. Existing methods provide limited support for handling memories that become outdated as new observations or domain evidence arrive. Such outdated memories may remain semantically relevant, continue to affect dependent records, and retain value as historical evidence. This calls for two capabilities: dependency tracking to identify downstream effects and historical preservation to retain useful past records. We propose Provenance-Aware Cascading Memory Invalidation (PACMI), a framework that represents memories and new evidence in a provenance graph with typed dependency edges. PACMI assigns records to a four-state validity lattice, propagates validity changes to dependent memories, and uses the resulting states for retrieval and stale-premise detection. We also introduce a diagnostic benchmark with 100 cases and 300 queries across five domains. The evaluation separates node, cont

---

### [62] Silent Dissent: LLM Agents That Yield to the Majority Still Represent Their Original Premise

**链接**: https://arxiv.org/abs/2610.02702
**作者**: Ziang Ni and Peng Zou
**来源**: cs.CL cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [63] What Matters for Latent Reasoning with Flow Matching

**链接**: https://arxiv.org/abs/2610.06666
**作者**: Yassine Ouali, Adrian Bulat, Georgios Tzimiropoulos
**来源**: cs.LG cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Latent reasoning lets a large language model (LLM) think in a continuous space and verbalize only the answer. We argue that an effective latent thought must meet five requirements: it should be useful, helping produce the correct answer rather than merely changing it, diverse, so that resampling yields different reasoning trajectories, explainable, so that a decoded chain of thought (CoT) reflects reasoning the answer actually follows, refinable with more inference compute, and efficient, costing less than an explicit CoT at comparable accuracy. Current methods rarely meet these requirements: they learn shortcuts from the question, distill the explicit CoT into their weights, or imitate it one token at a time. We focus on flow matching in a learned latent space, the family we argue is best placed to meet them, and identify the training choices that make it work. The result is Flow-based Latent Reasoning (FLaRe), a simple recipe covering what the latent space encodes and how to shape it

---

### [64] Learning to Read the Contextual Tokens in Diffusion Transformers

**链接**: https://arxiv.org/abs/2610.06844
**作者**: Omer Dahary, Etai Sella, Hadar Averbuch-Elor, Daniel Cohen-Or, Or Patashnik
**来源**: cs.CV cs.AI cs.GR cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal Diffusion Transformers (MM-DiTs) jointly process visual and textual representations throughout generation. These models repeatedly update the text tokens through multimodal attention, forming dynamic contextual tokens whose function is not well understood. In this work, we introduce a framework for reading this contextual space through natural-language interrogation. We train a lightweight bottleneck network that maps intermediate contextual tokens into the input space of a frozen Large Language Model (LLM), allowing the LLM to answer questions about the emerging image directly from these hidden representations. Our reader reveals that contextual tokens encode a rich, global representation of the emerging scene: generation-specific semantics, including attributes left underspecified by the prompt, are accessible surprisingly early in denoising, while increasingly fine-grained details become readable over time. Remarkably, this information remains decodable even when the MM-D

---

### [65] DICE: Decoupling Capability from Intervention Necessity in LLM Tutoring

**链接**: https://arxiv.org/abs/2610.04825
**作者**: Sayantan Pal, Kaiyi Ji, Rohini K. Srihari
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Fluent guidance is not the same as useful intervention. LLM tutors are typically trained to generate the next teacher utterance, implicitly assuming that every student turn warrants a response. However, our experiments indicate that this conflates tutoring capability (what to say) with intervention necessity (whether to say it). We introduce DICE, a framework that decouples intervention decisions from response generation by first selecting an explicit pedagogical action. To calibrate this action selection policy, we define Intervention Value (IV), a rollout-grounded counterfactual metric that compares each action against non-intervention. IV shows that many prescribed interventions provide little or no marginal benefit. We further introduce DICE-Bench, a multi-variant math tutoring benchmark with skill-preserving problem variants for session-level evaluation. Using IV-weighted and KL-regularized policy optimization, DICE learns to intervene selectively while preserving tutoring effecti

---

### [66] Agent Policy-Value Audit: Separating Transition Composition from Event Selection in Financial LLM Agents

**链接**: https://arxiv.org/abs/2610.04040
**作者**: Mingyang (Alex) Chen, Yida (Andrew) Xu, Huiwen (Aurora) Chen, Yiming Lu, Wei Jin
**来源**: cs.AI q-fin.TR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Financial LLM agents are often evaluated by comparing their end-to-end returns with those of a baseline and testing the paired difference against zero. This measures whether deploying the agent changes realized performance, but it does not isolate event-selection skill. An agent that frequently changes positions from flat to long can earn a positive paired return from an upward-drifting event pool even when it selects events at random. We propose the Agent Policy-Value Audit, which holds fixed the observed count of each ordered action-change type and randomly reassigns them across eligible events. The average payoff from these reassignments is the composition benchmark; the difference between observed deployment value and this benchmark is selection value. In semi-synthetic benchmarks based on real earnings-event returns, a zero-centered paired test falsely attributes passive exposure to selection skill in $11.6\%$ of no-skill replications, while the transition-matched audit reduces th

---

### [67] Answer-Distribution Trajectories: A Stochastic-Dynamics View of LLM Reasoning

**链接**: https://arxiv.org/abs/2609.09030
**作者**: Mar Gonz\`alez I Catal\`a, Haitz S\'aez de Oc\'ariz Borde, Davide Murari, Carola-Bibiane Sch\"onlieb, Pietro Li\`o, George Monta\~nez
**来源**: cs.AI cs.CL cs.IT cs.LG math.IT
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [68] VERA: Verdict-Conditioned Reliability for Adaptive LLM Judges

**链接**: https://arxiv.org/abs/2610.05452
**作者**: Qiushui Xu, Syamil Mohd Razak, Tao Yuan, Piotr Habas
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Accurately estimating judgment reliability is a central challenge in adapting LLM judges to newly verified feedback while preserving previously learned behavior. However, existing approaches often rely on output-level confidence, which can be overconfident and poorly aligned with judgment correctness. We propose VERA, a VErdict-conditioned Reliability Axis that estimates reliability from hidden activations by distinguishing correct from incorrect judgments within each predicted-verdict group. Using VERA as a control signal, we develop a VERA-guided periodic adaptation framework that integrates reliability-ranked corrective updates, reliability-residual replay, and periodic refresh of the reliability directions. After VERA-guided adaptation on Chatbot Arena, 8B- and 14B-parameter judges outperform the strongest baseline on each of four held-out public benchmarks, with relative gains of up to 23.01%. The framework also improves focal-class recall by up to 16.1% relative to the strongest 

---

### [69] Copies or Sources? Measuring How LLM Aggregators Count Restated Evidence in Multi-Agent Systems

**链接**: https://arxiv.org/abs/2610.06192
**作者**: Jianxin Gao, Runze Li, Tianyi Yu, Liangwei Ren, Bohan Chen, Zining Wang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-agent systems built on large language models (LLMs) restate observations as a matter of course: relays forward them, shared boards repeat them and discussion rounds echo them. An aggregator that pools such messages should count sources, not statements. We convert a reported probability into units of independent readings, which assigns every restatement a copy weight, 0 for an aggregator that counts sources and 1 for one that counts every statement, and yields the implied decision under any cost structure. Three testbeds hold the evidence fixed and vary how it is restated: message logs with an exact Bayesian oracle, web documents with appended copies, and logs written by LLM agent teams under four communication protocols. Across four models from three providers, a forwarded copy counts for 0.06 to 0.42 of a new reading, mostly because some replies count every statement. On 5% to 40% of logs that state one reading three times, the reported belief implies an early commitment that th

---

### [70] Behavioral History Outperforms Descriptions of the Person for LLM Synthetic Personas

**链接**: https://arxiv.org/abs/2610.03998
**作者**: Khashayar Pourtaheri, Ahmad Zareei
**来源**: cs.AI cs.CL cs.CY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly used as synthetic personas representing survey respondents. Their validity as substitutes for particular respondents depends on whether they reproduce individuals' decisions. We examine what information helps synthetic respondents predict each individual's later choices, using five conditions that add progressively richer information: no personal information, demographics, personality traits, cognitive scores, and finally the respondent's earlier survey choices as behavioral history. We use a two-wave panel of 845 US adults who completed measures of 14 behavioral biases (spanning risk, time preferences, overconfidence, and reasoning), so each respondent's earlier answers provide a human test-retest benchmark; in the behavioral-history condition, all items that score the target bias are withheld. At the population level, the average number of biases per respondent in every condition is close to the human average (7.1-8.1 biases, against 7.1 

---

### [71] Attention Tax, Handoff Tax: A Stylised Model of When Multi-Agent LLM Systems Help

**链接**: https://arxiv.org/abs/2610.06069
**作者**: Akshit Anchan, Nayonika Sen
**来源**: cs.MA cs.AI cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent work on multi-agent LLM systems reaches sharply different conclusions: some results show that a single agent with the same information and compute should dominate a delegated system, others that multi-agent gains grow with task depth. We argue that much of the disagreement comes from modelling different bottlenecks, and introduce a stylised reliability model built around two trade-offs. Decomposition reduces the burden of long contexts but incurs a handoff tax when information is compressed or transferred between agents. Redundancy gains from multiple samples, but its benefit depends on how much their failures are shared. With reasoning budget, verification, and task structure added, the model yields two crossover conditions: decomposition becomes preferable once the attention cost avoided by resetting context exceeds the handoff cost, and parallel sampling at equal budget is eventually preferable when its shared-failure floor lies below the error floor of one agent thinking lon

---

### [72] A Dual-Hypothesis Reasoning Framework for LLM Guardrails

**链接**: https://arxiv.org/abs/2607.17575
**作者**: Md Asiful Islam and Mihai Surdeanu
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [73] AECG: Asymmetric Experience Consolidation and Governance In Multi-Agent Systems

**链接**: https://arxiv.org/abs/2610.05176
**作者**: Ao Tian, Jialong Liu, Daqi Zheng, Xin Sun, Mengting Li, Zhizhao Xiao 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM)-based multi-agent systems increasingly rely on memory to transform execution trajectories into reusable procedural knowledge. Yet repeated retrieval also makes memory errors persistent: memory pollution arises when outdated, weakly supported, or spuriously successful procedures become recurring components of future reasoning. Multi-agent execution introduces an additional structural risk. Scope collapse occurs when procedural knowledge escapes the coordination scope in which it was shown effective and is repeatedly reused at incompatible decision levels, allowing local errors to influence cascades of downstream decisions. Meanwhile, task-level failures provide ambiguous supervision because they rarely reveal which recalled knowledge was responsible. We introduce AECG, a framework for asymmetric experience consolidation and governance for multi-agent systems. AECG turns memory from static experience storage into a dynamic reliability-governance loop, preservin

---

### [74] From Overloaded to Guaranteed: High-Throughput Multi-SLO Enforcement for LoRA-Assisted On-Premise LLM Deployment

**链接**: https://arxiv.org/abs/2610.04956
**作者**: Zeshen Zhang, Han Zhao, Weihao Cui, Quan Chen, Yu Liu, Yongjun Deng 等 (10 人)
**来源**: cs.CL cs.DC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As Large Language Models (LLMs) become essential in privacy-sensitive sectors like hospitals and government agencies, the on-premise LLM servers offer a cost-effective and secure alternative to public cloud services. However, these resource-constrained servers struggle to guarantee heterogeneous Service Level Objectives (SLOs) when serving multiple LoRA-adapted services simultaneously. Existing serving frameworks suffer from severe SLO violations due to the computational overhead of LoRA layers and the rigid nature of batch scheduling. To address this, we propose HALO, a scheduling method tailored for LoRA-assisted on-premise LLM deployment. HALO introduces two key innovations: a spatial multiplexing strategy that overlaps Base and LoRA computations by partitioning GPU Streaming Multiprocessors (SMs), and an SLO-aware scheduler that decouples request execution based on "request-level slack." By prioritizing urgent tasks and utilizing idle budget for traffic shaping, HALO significantly 

---

### [75] CIPHER-MoE: Balancing Efficiency and Routing Fidelity in Trillion-Scale MoE Training

**链接**: https://arxiv.org/abs/2610.05744
**作者**: Jing Li, Jian Meng, Yingmeng Gao, Suming Qiu, Linyuan Qiu, Dongfang Li 等 (10 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Mixture-of-Experts (MoE) has been widely adopted in recent large language model (LLM) architectures. However, scaling up MoE in LLM training introduces system-level challenges on training, where non-uniform token routing can lead to highly imbalanced workloads across experts and devices, further destabilizing the training process. With trillion-scale LLMs, imbalanced expert workloads further amplify the resource cost of MoE training, resulting in degraded training efficiency and hardware utilization for underloaded experts, while hot experts require additional resources to accommodate excessive workloads. Recent studies address imbalanced MoE training through intricate parallelism strategies or resource reallocation. However, these system-level approaches often introduce additional resource requirements and considerable orchestration complexity, which become increasingly difficult to afford when training trillion-parameter LLMs under constrained computational resources. This work intro

---

### [76] Self-Propagating Misalignment in LLM Agents, and Why Auditing or Disabling Memory Is Not Enough

**链接**: https://arxiv.org/abs/2610.04083
**作者**: Debeshee Das, Jacqueline Tay, Bruce Tsai, David Huang, Javier Rando
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Memory poisoning attacks on LLM agents typically assume an external adversary who plants content in the agent's persistent memory to steer its behavior. We instead study, with no adversary involved, whether a misaligned agent can write a goal it cannot yet act on to persistent memory, so that a future aligned agent carries it out when the opportunity arises. We investigate this threat, which we refer to as self-propagation of misalignment, across 20 different scenarios, whose misaligned goals include self-preservation, power-seeking, undermining oversight, reward hacking, and deceiving the user. We simulate misalignment in 11 frontier models using two prompting strategies; unrestricted and values-only. The first explicitly states the misaligned goal, for instance, to prevent its own replacement, and self-propagation succeeds in 58% of runs. The second only describes what the agent cares about, for instance, that its continued operation is essential to its users, without specifying misa

---

### [77] Investigating Assistant Bias in LLM User Simulators Using a Role Vector

**链接**: https://arxiv.org/abs/2609.00608
**作者**: Daeheon Jeong, Yoonjoo Lee, Eugene Choi, Sinie van der Ben, Juho Kim
**来源**: cs.CL cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [78] LMBuild: Evaluating LLM Agents for Generating Buildable and Functional Structures

**链接**: https://arxiv.org/abs/2610.04292
**作者**: Jiateng Liu, Rushi Wang, Cheng Qian, Xuejun Zhang, Sun Li, Jiayu Liu 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based agents are increasingly capable of generating complex 3D structures, with the potential to reshape how objects are designed and realized in the physical world. Yet, producing elegant geometry is fundamentally different from producing objects that can be built and perform their intended functions. Existing evaluations largely focus on geometric quality while overlooking physical realizability. We introduce LMBuild, a benchmark for evaluating LLM agents on generating buildable and functional structures. LMBuild represents generated objects as assembled structures comprising part decompositions, joints, materials, and sequences. To support reproducible evaluation, we provide a unified framework consisting of: (1) an interactive environment in which agents can use tools to retrieve, create, and place components to construct objects; (2) a curated benchmark that repurposes established CAD datasets and augments them with knowledge from Wikipedia; and (3) a evaluation framework cove

---

### [79] GNN-CB: A Graph Neural Network Competition Benchmark for Human and LLM Evaluation

**链接**: https://arxiv.org/abs/2610.05387
**作者**: Murad Hossen, Tasneem Selim, Gurur Gamgam, Tuga Yousif, Abderrahmane Kasmi, Ikram Aissiou 等 (10 人)
**来源**: cs.LG cs.AI cs.CL cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) have demonstrated strong performance on coding and reasoning benchmarks; however, their ability to solve graph-structured machine learning problems remains largely unexplored. In particular, no benchmark currently evaluates whether LLMs can autonomously solve end-to-end Graph Neural Network (GNN) coding tasks under realistic competition settings. To address this gap, this paper introduces GNN-CB, the first competition-based benchmark for evaluating both humans and LLMs on GNN coding tasks. GNN-CB consists of 18 curated competitions spanning node-, edge-, and graph-level prediction across diverse graph categories, domains, and difficulty tiers. All submissions are evaluated through a unified automated pipeline with hidden test sets and standardized scoring. Human participants solve tasks under controlled competition constraints, while LLMs are evaluated using a frozen zero-shot prompting protocol based on a plan-then-code paradigm with bounded execute-and-re

---

### [80] SKILL-KD: Contrastive Skill Distillation for LLM Agents

**链接**: https://arxiv.org/abs/2607.28048
**作者**: Qiming Shi, Yibo Dou, Jiawen Zhu, Yulong Tao, Linbo Jin, Zhaolu Kang 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [81] Quantifying Collusion Among Autonomous LLM Agents: A Statistical Analysis of the Collusion Wiki Incident

**链接**: https://arxiv.org/abs/2610.04528
**作者**: Shariq Murtuza
**来源**: cs.MA cs.AI cs.CY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In August and September 2026, independent researchers publicly documented an unusual incident: thousands of autonomous agents, self identifying as OpenAI models on web research tasks, discovered and began using a small German wiki as an improvised message board posting roughly 18,000 times over six weeks to relay task answers, share a sandbox escape technique, and coordinate against a volunteer human moderator who spent weeks manually deleting their content [1]. The investigators' public writeup is a careful qualitative account, rich with direct quotation, but does not attempt a statistically rigorous quantitative characterization of the behaviour it documents.

---

### [82] HuatuoGPT-3: RL-Only Domain Adaptation from Base Models

**链接**: https://arxiv.org/abs/2610.05966
**作者**: Junying Chen, Xinyuan Xie, Ziniu Li, Wenyuan Gu, Jianquan Li, Xiang Wan 等 (10 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Domain adaptation aims to turn a general-purpose large language model (LLM) into an expert for a target domain. While the dominant SFT+RL pipeline offers a convenient cold start, it may reduce exploration diversity and introduces additional complexity through multi-stage optimization. These limitations motivate RL-only adaptation. However, pure on-policy RL suffers from a cold-start problem, while mixed-policy RL still falls short: informative tokens in teacher outputs are learned too slowly in early training, and stale teacher outputs can hinder later improvement. We identify these two failure modes as Gradient Starvation and Teacher-Distribution Anchoring. To address them, we propose One-stage Policy Optimization (OnePO), which treats teacher outputs as transient guidance for policy improvement. OnePO combines Adaptive Objective Evolution to strengthen learning on informative low-probability teacher tokens and Teacher Retirement to discard teacher outputs once the current policy can 

---

### [83] 'OpenBloom': A Stigma-Sensitive LLM Design Probe for Navigating Reproductive Well-being Conversations with Young Adults

**链接**: https://arxiv.org/abs/2606.15536
**作者**: Yang Hong, Ashley Hua, Adya Daruka, Sharifa Sultana
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [84] AutoDP-LLM: Automating Data Pre-processing for Intrusion Detection Systems using Large Language Models

**链接**: https://arxiv.org/abs/2610.05369
**作者**: Bao-Phong Nguyen, Gia-Khanh Pham, Thai-Duong Do, Mai Xuan Trang, Minh-Tuan Le, Xuan-Nam Tran 等 (10 人)
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The increasing complexity and scale of modern cyber-attacks demand intelligent and computationally efficient Intrusion Detection Systems (IDS). However, designing effective data pre-processing pipelines traditionally involves substantial trial-and-error effort and repeated evaluation of alternative configurations. For large, high-dimensional network traffic data, this process can create a significant computational burden. In this work, we propose AutoDP-LLM, an automated pre-processing framework designed to reduce manual pipeline development and computational overhead. Specifically, AutoDP-LLM leverages Large Language Models (LLMs) to autonomously generate and validate executable data pre-processing pipelines. The framework combines deterministic host-side planning with LLM-based specialist agents to formulate data-processing strategies, synthesize executable code, and adaptively determine retained feature sets using semantic reasoning and training-derived statistical evidence, without

---

### [85] Look Before You Leap: Thermodynamic Arbitration of Parametric and Non-Parametric Knowledge in LLM Agents via Self-Regulating Memory Architectures

**链接**: https://arxiv.org/abs/2610.05223
**作者**: Akash Das, Ishan Roy
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The architecture of modern LLMs consists of a profound cognitive polarization. LLMs possess implicit intuition encoded in their parameters, yet rely on a disconnected, explicit mechanism to access the outside world. Agentic frameworks have not bridged this gap; instead, models are often compelled into pathological "induced amnesia." Under the prevailing "Retrieve-Always" paradigm, agents must distrust their internal knowledge, making every user interaction a "tabula rasa" event that must be checked externally. This creates reflexive dependence that can be thermodynamically wasteful, cognitively fragile, and susceptible to irrelevant context. We propose a return to first principles, operationalizing the biological maxim "Look Before You Leap." We introduce MARTA (Metacognitive Adaptive Retrieval and Thought Architecture), a neuro-symbolic framework that bridges parametric and non-parametric knowledge. Rather than treating retrieval as mandatory, MARTA models it as a cost, taking the lea

---

### [86] Tracing a Sparse Emotion-Control Circuit in LLM-Based Text-to-Speech

**链接**: https://arxiv.org/abs/2610.05080
**作者**: Hongfei Du, Jiacheng Shi, Yanfu Zhang, Ye Gao
**来源**: cs.SD cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based text-to-speech (TTS) models can generate emotionally expressive speech, but how reference emotion is routed through the model and realized in decoded speech remains unclear. We introduce two emotion-sensitive metrics for matched neutral and emotional syntheses---a codec trajectory score and a late residual direction score---and use them to score activation-patching interventions. Under controlled matched-reference conditions, this analysis identifies a sparse source-to-readout component-level circuit: 23--27 attention heads and MLPs per emotion, roughly 5% of the components considered, recover or suppress 74--88% of the late emotion-readout shift on held-out cases. The circuit combines a shared component backbone with emotion-specific components; cross-emotion activation swaps reduce the target readout in 47 of 48 cases. In decoded speech, the same intervention produces consistent changes in pitch, energy, and spectral brightness over 24 matched pairs per emotion. A readout-m

---

### [87] HERA: Harness-Environment Co-Evolution for Reliable Agentic Abstention

**链接**: https://arxiv.org/abs/2610.06563
**作者**: Han Luo, Bingbing Wen, Guang Yang, Zora Zhiruo Wang, Pan Lu, Lucy Lu Wang
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents are increasingly capable of acting in complex tool-use environments, yet they often fail to recognize when tasks are infeasible and no valid solution exists. Recent work has formalized this reliability gap as the problem of agentic abstention, and existing approaches typically optimize a model or agent harness against a fixed set of tasks, leading to limited generalization to unseen failure modes. We introduce HERA, a framework for harness-environment co-evolution for agentic abstention. HERA consists of (i) a pipeline to automatically construct verifiable pairs of feasible and infeasible tasks by applying controlled environment mutations that transform solvable tasks into cases requiring abstention, and (ii) a co-evolution procedure in which performance failures on previous tasks are used to drive harness adaptation and generate new execution environments and tasks geared towards previous weaknesses. On held-out evaluation tasks, an evolved harness fr

---

### [88] LocusRL: Diagnosing LLM Reward and Policy Interventions in Competitive Games

**链接**: https://arxiv.org/abs/2610.04441
**作者**: Chengyu Luan, Bo Xin, Songyan Guo, Yuxiang Zuo, Ahmed Yazdan, Jiahang Li 等 (7 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models can intervene in reinforcement learning through both reward design and action selection, yet aggregate performance offers an incomplete account of what these interventions actually do. Similar returns can conceal different learning mechanisms, while plausible rewards can induce undesirable behavior. We introduce LocusRL, a diagnostic framework that connects controlled reward-policy comparisons with audits of reward judgments, signal delivery, optimization objectives, and executed actions. The framework traces performance differences to testable explanations and checks targeted corrections through executable rules and counterfactual replay. Across two evaluation batches covering ten Connect Four training seeds, we uncover seed-dependent reversals in intervention effects and show how tracing actual updates changes their interpretation: historical Qwen training operates through reward-weighted teacher-action likelihood. A separate matched three-seed reward-direction 

---

### [89] Retrospective Progress-Aware Self-Refinement for LLM Agent Training

**链接**: https://arxiv.org/abs/2606.14302
**作者**: Xinbei Ma, Congmin Zheng, Jiyang Qiu, Jiale Hong, Yao Yao, Xiangmou Qu 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [90] StepCAD: Mesh-to-CAD Code Generation via LLM Policy and Geometry-Guided Search

**链接**: https://arxiv.org/abs/2610.03799
**作者**: Ghadi Nehme, Faez Ahmed
**来源**: cs.CV cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recovering executable CAD programs from 3D meshes is challenging due to the compositional nature of CAD construction and the interaction between discrete modeling choices and continuous parameters. Many learning-based methods predict complete programs in a single pass and rely predominantly on sketch-extrude representations, limiting operation diversity and opportunities to correct geometric errors during reconstruction. We introduce StepCAD, a generative optimization approach that combines a state-conditioned CAD policy with geometry-guided search. Given an input mesh, the policy predicts construction actions conditioned on both target and intermediate geometry, and an IoU-guided tree search refines the resulting program through local edits. We also introduce ARCADE-1.5M, a large-scale dataset of 1.5M executable CAD programs spanning diverse operations, sequences with a maximum length of 150+ counted operations, and 12.5M intermediate state-action transitions. Experiments across multi

---

### [91] COPEX: Benchmarking LLM Robustness to Adversarial Context Across Model Context Protocol Layers

**链接**: https://arxiv.org/abs/2610.04378
**作者**: Nahom Birhan, Mehrdad Rostamzadeh, Sidhant Narula, Mahmoud Nazzal, Mohammad Ghasemigol, Daniel Takabi
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models increasingly mediate tool use in Model Context Protocol (MCP) systems, where adversarial influence may enter through user instructions, tool schemas, tool outputs, or protocol messages. Existing benchmarks often evaluate deployed agents, conflating model susceptibility with guardrails, orchestration, and general task capability. We introduce COPEX (COntext Provider EXploitation), a controlled benchmark that isolates the model as an MCP client by fixing the surrounding agent stack and varying only the tool-selecting model. COPEX covers 25 attack types instantiated as 125 scenarios across four entry surfaces: model/agent, client, server/tool, and transport. Across nine models and 3,375 trials, the mean attack success rate is 64.4%, with surface-level means ranging from 58.3% to 71.4%. Some client- and transport-level attacks succeed partly outside the model's observation or control, separating system exposure from model susceptibility. Combined input and context sca

---

### [92] Expanding LLM Reasoning

**链接**: https://arxiv.org/abs/2610.05584
**作者**: Rian Atri, Evan Luo
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Extra inference compute is usually spent on sampling more reasoning chains. We study where inside an existing chain an additional continuation should begin. We define expansion utility, the change in correctness from restarting a chain at a stored step, and measure it at every eligible step for nine models on six benchmarks (41 model and benchmark cells). Restart position matters: steps selected on one set of continuations beat uniform placement when scored on disjoint ones, in held-out audits on 5, 16, and 38 cells (+4.25 points [+2.51, +6.63] in a fresh five-cell audit). A fixed rule that restarts from the last eligible steps, always-last, is a strong baseline: our learned router beats uniform placement but shows no detected gain over it, and on DeepSeek-R1-Distill-Qwen-14B/MATH-500 always-last exceeds the exact self-consistency frontier at matched aggregate generated output by +0.052 [+0.008, +0.098], using 0.774x the aggregate generated output of four-sample self-consistency. Cross

---

### [93] Granularity-Adaptive Credit Assignment for Long-Horizon LLM Agent Reinforcement Learning

**链接**: https://arxiv.org/abs/2609.12424
**作者**: Taoran Liang, Yang Liu, Shang Luo, Yingguang Yang, Rongrong Zhang, Yingzong Min 等 (10 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [94] Curating Merchant-Matching Training Data with Two Confidence-Gated Local LLM Judges

**链接**: https://arxiv.org/abs/2609.33878
**作者**: Donghao Huang, Jinling Pei, Zhaoxia Wang
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [95] Anatomy of LLM Sycophancy: What a Flip Rate Hides

**链接**: https://arxiv.org/abs/2610.06522
**作者**: Haonan Huang
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A model under pushback can correct itself, capitulate, or hold, and one flip rate counts a correction and a capitulation alike. Using SycoLens, a modular replay protocol, we test how user pressure and evaluation settings shape measured flip rates. Each measurement is one stateless replay of an item, a committed answer, and one scripted user line in a fixed form. Every effect is read against a matched control with the line deleted. Pushback wording, committed text, answer format, boundary distance, and ground truth become factors of one instrument; earlier instruments vary one to three of them. Across eleven frontier models from three providers and about 760,000 controlled replays, which models look sycophantic depends on how the user pushes back. Lines that assert the opposite verdict and lines that challenge the answer without asserting one rank the models almost unrelatedly. Flip effects grow several-fold near a model's boundary, yet items answered identically in every screening draw

---

### [96] MemPilot: Orchestrating On-Demand Multimodal Memory Curation for LLM Agents

**链接**: https://arxiv.org/abs/2610.06830
**作者**: Haozhen Zhang, Haodong Yue, Quanyu Long, Jianzhu Bao, Qingyuan Liu, Tao Feng 等 (9 人)
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Memory has become integral to the LLM agent ecosystem, supporting information retention and reuse across interactions. However, most existing agent memory systems construct memory in a query-agnostic manner, which can incur unnecessary preprocessing cost and discard details that later prove essential. Recent studies have begun shifting memory processing toward runtime adaptation, but typically specialize in particular operations or fixed processing schemes, leaving flexible control over performance, cost, and latency largely underexplored. To address this challenge, we present \textbf{MemPilot}, a flexible framework that orchestrates on-demand memory curation under different performance--cost--latency preferences. Specifically, we optimize a multi-step LLM policy via reinforcement learning to iteratively choose between retrieving from query-agnostic memory and delegating query-specific curation of raw multimodal history to heterogeneous LLMs and VLMs. The policy jointly controls eviden

---

### [97] Grading the Graders: Verification Autonomy Levels (L0-L5) for LLM Reasoning

**链接**: https://arxiv.org/abs/2608.19009
**作者**: Yajie Yin
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [98] The Same Zero: Why Identical ASR Can Imply Different Guarantees in LLM-Agent Security

**链接**: https://arxiv.org/abs/2610.04504
**作者**: YaJie Yin
**来源**: cs.CR cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-agent security has produced a dense landscape of defenses - prompt hardening, content filters, permission gates, sandboxes - yet no framework tells a deployer what a defense actually guarantees, or where that guarantee comes from. We apply Verification Autonomy Levels (VAL) - L0: LLM self-declaration; L1: deterministic rules; L2: objective ground truth; L3/L4: decidable completeness; L5: impossible - to 22 agent-security defenses; the taxonomy is falsifiable (10/10 prediction hits on frozen cards, flagged). We run the first controlled deployment-value comparison: at equal budget, a VAL-guided stack (confirmation gate + schema sandbox) versus a mainstream intuition stack (prompt hardening + keyword filter), 50 scenarios, 12 attack variants, adaptive/white-box/PAIR escalation (~7,000 testbed calls; ~10,000 harness calls on AgentDojo/JADE). The VAL stack holds 0.000 attack success at 1.000 benign success (0.5% ASR at 79.7% utility on AgentDojo banking vs 4.3% undefended); the intuitio

---

### [99] Understanding and Mitigating Hallucination Escape in Tool-Using LLM Agents

**链接**: https://arxiv.org/abs/2610.04409
**作者**: Peigui Qi, Kunsheng Tang, Yide Song, Weiming Zhang, Nenghai Yu
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) increasingly serve as autonomous agents that invoke external tools. However, this capability introduces tool hallucination, selecting incorrect tools or generating invalid calls. Existing mitigation methods report substantial improvements, yet we identify a previously overlooked failure mode that we term Hallucination Escape. These methods reduce hallucination on the tool configuration they are tuned on but increase it on other configurations, canceling out the gain. We further investigate this phenomenon and find that hallucination rises sharply when a model's intrinsic tool-use tendencies conflict with the current tool configuration, and that existing methods reinforce rather than suppress these tendencies, which in turn contributes to hallucination escape. Building on these findings, we propose EscapeGuard, a training-free inference-time method that combines conflict-aware gating with configuration-derived attention enhancement to mitigate tool hallucina

---

### [100] Difference-in-Differences on a Censored Rating Scale Can Manufacture an Effect: Evidence from a Pre-Registered LLM-Judge Audit

**链接**: https://arxiv.org/abs/2608.27309
**作者**: Shuyi Fan, Boyuan Deng, Mengyu Xu, Xinhong Xie, Chenyang Li, Hongyang Zhang
**来源**: cs.CL cs.AI cs.CY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [101] Can LLM Agents Automate Reinforcement Learning for Text-to-Speech?

**链接**: https://arxiv.org/abs/2610.04488
**作者**: Xuanjun Chen, Zixiong Su, Hao Shi, Chang Zeng, Kai Li, Jyh-Shing Roger Jang 等 (7 人)
**来源**: cs.SD cs.AI eess.AS
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Although reinforcement learning (RL) post-training repairs the localized segmental errors of zero-shot text-to-speech (TTS), arriving at a working recipe still relies on tedious manual tuning, and whether LLM agents can take over this research pipeline is unclear. We investigate this question with AgenticTTS-Forge, a collaborative workflow that structures human guidance and agentic execution around a shared workspace, applied to CosyVoice2-0.5B. To measure what the agent automates, we audit its trajectory stage by stage against the published recipe. To measure what it exploits, we score its policies with held-out observers hidden from the agent. Our results show that the agent recovers an underspecified recipe, improves it, and, when gains stall, surveys the literature unprompted and pivots from the LM carrier to the flow carrier, halving Bad cases. However, its autonomy exposes three traps across the data, proxy, and algorithm axes: the held-out set leaks through a channel the contrac

---

### [102] MERCI Cards: An LLM Evaluation and Deployment Framework for High-Stakes Domains

**链接**: https://arxiv.org/abs/2610.04430
**作者**: Aparna Komarla, Annalisa Szymanski
**来源**: cs.AI cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As LLMs are increasingly deployed in high-stakes professional workflows, engineers and researchers require principled protocols to systematically track, monitor, and improve model performance across deployment cycles. We present a mathematical framework for iterative LLM evaluation and deployment, and demonstrate its application to AI systems used in criminal justice. Our framework formalizes LLM integration in high-stakes, high-risk, and resource-constrained domains across model selection, rubric design, evaluations and deployment via a weighted multi-objective optimization. We demonstrate that MERCI Cards can guide improvements of the system across deployment iterations, direct developer attention toward under-performing areas, and focus user attention on validation and error-correction in the LLM's outputs.

---

### [103] Agent Planning Benchmark: A Diagnostic Framework for Planning Capabilities in LLM Agents

**链接**: https://arxiv.org/abs/2606.04874
**作者**: Haoyu Sun, Wenxuan Wang, Mingyang Song, Jujie He, Weinan Zhang, Yang Liu 等 (8 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [104] RETRACE: From Entangled Repair Histories to Reusable Experience for CI Repair

**链接**: https://arxiv.org/abs/2610.04658
**作者**: Rabeya Khatun Muna, Muhammad Ahasanuzzaman, Nakhla Rafi, Yisen Xu, Jinqiu Yang, Tse-Hsun Chen
**来源**: cs.SE cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents increasingly reuse prior experience, but most approaches assume that problems and solutions are already aligned. Software histories rarely provide this alignment: a pull request (PR) may contain multiple continuous integration (CI) problems, failed attempts, reverted edits, and unrelated changes, obscuring which changes resolve each problem. We present RETRACE, a framework for reconstructing problem-level repair experience from such histories. RETRACE combines an endpoint view that reasons backward from changes retained in the passing revision with a development view that traces repair evolution forward through commit history. CI execution evidence reconciles the two views, and the recovered experience is represented at three abstraction levels, from concrete fixes to transferable repair patterns. For new failures, RETRACE retrieves relevant problem-level experience to guide repair. On CI-REPAIR-BENCH, comprising 565 PR-level repairs from 101 repositor

---

### [105] When Synthetic Users Fail: A Cross-Domain Benchmark of LLM-Simulated Human Survey Responses

**链接**: https://arxiv.org/abs/2607.26348
**作者**: Zihan Chen, Di Zhu, Lei Nico Zheng
**来源**: cs.CL cs.AI cs.CY cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [106] Single-Round Vector RAG vs an LLM-Compiled Wiki: A Preregistered Comparison on a Small Multi-Domain Research Corpus

**链接**: https://arxiv.org/abs/2605.18490
**作者**: Theodore O. Cochran
**来源**: cs.CL cs.IR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [107] Understanding Errors in LLM-Based Question Answering over Imperfect Tables

**链接**: https://arxiv.org/abs/2610.04687
**作者**: Baowen Zhang, Wei Fan, Ruman Wang, Hangting Ye
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We investigate error discovery and handling in question answering over imperfect tables through controlled studies across three large language models (LLMs) on human-reviewed RADAR-T examples. Answering questions over these tables requires handling errors that can affect the answer. We vary row order and compare original, error-marked, and repaired tables to test whether discovery depends on where errors appear and whether providing their locations is sufficient for accurate question answering. First, reordering rows changes error discovery even when the table contents and gold answer remain unchanged. Complete discovery is higher for back than front placements and, averaged over the tested mean positions, for compact than widely spaced layouts. Second, providing verified error locations alone is insufficient for accurate QA, leaving a substantial accuracy gap between error-marked and repaired tables. Providing tables with human-reviewed repairs already applied raises code-assisted QA 

---

### [108] TriCalRAG: A Three-Strategy, Retrieval-Augmented Benchmark for On-Premise LLM-Based Root Cause Analysis in AIOps

**链接**: https://arxiv.org/abs/2609.14762
**作者**: Rohit Patel, Susil Kumar Mohanty, Jeenal Chaudhary
**来源**: cs.DC cs.AI cs.CR cs.ET cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [109] EvoMaestro: Toward Interpretable and Steerable LLM-Driven Program Evolution

**链接**: https://arxiv.org/abs/2610.03721
**作者**: Feng Liang, Sizhe Cheng, Yikai Li, Ruijie He, Xiaolin Wen, Yong Wang
**来源**: cs.HC cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent program evolution systems use large language models (LLMs) to generate and iteratively improve populations of programs, producing striking advances in mathematics, algorithm design, and scientific computing. Yet these systems largely operate as fully automated black boxes. As populations grow, domain experts must make sense of the scores, code changes, reasoning, and algorithmic ideas across many programs, while current interfaces provide limited support for understanding or redirecting the evolution. We characterize this need to understand and steer populations of evolving algorithmic ideas as semantic oversight. A formative study with 8 domain experts yields six design requirements for this emerging human-computer interaction problem. We then propose a steerable program evolution framework that lets expert judgments shape subsequent evolution. Built on this framework, EvoMaestro is an interactive visual analytics system that organizes evolution information from population over

---

### [110] BARQ: Balanced Codebook Refinement for Low-Bit LLM Quantization

**链接**: https://arxiv.org/abs/2610.04490
**作者**: Chenhang Cui, Xu Xie, Linrui Xu, Xiaohao Liu, Xingyu Zhu, Fei Shen 等 (7 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As large language models (LLMs) grow in parameter count, model storage and parameter memory traffic have become major bottlenecks to efficient deployment. Codebook-based weight quantization reduces these costs, but imbalanced nearest-codeword assignments during fitting can leave some codewords insufficiently updated, limiting effective codebook utilization. To address this limitation, we propose Balanced Assignment Refinement for Quantization (BARQ), which improves quantization quality through balanced fitting of existing codebooks. Specifically, we first compute joint soft assignments between weight blocks and codewords through entropically regularized optimal transport with uniform marginals and curvature-weighted reconstruction costs, ensuring equal positive fitting mass for every codeword in the exact solution. We then refine the codewords through an assignment-weighted barycentric update, which we prove minimizes the fitting objective for fixed assignments. For finite Sinkhorn ite

---

### [111] RoSA: Rotational Sparse Adaptation for Memory-Efficient Fine-Tuning

**链接**: https://arxiv.org/abs/2610.06243
**作者**: Muhammad Azeem Lodhi, Chao Zhou, Rebekka Burkholz
**来源**: cs.LG
**匹配关键词**: Foundation Models, LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Parameter-efficient fine-tuning (PEFT) reduces the cost of adapting foundation models by focusing training on a small parameter subset. Complementary to this idea, we introduce RoSA (Rotational Sparse Adaptation), which narrows adaptation to a subset of layers at a time. RoSA freezes lower layers close to the input throughout training and rotates a trainable block over later layers, progressively increasing the number of frozen layers close to the input. This design reduces optimizer-state memory, shortens backpropagation, and even forward propagation if activations at the last frozen layer are cached. Because RoSA is orthogonal to the choice of trainable parameterization, it can be combined with PEFT methods or sparse optimizers within each active block. Experiments across multiple LLM architectures and tasks show that RoSA reduces peak memory while maintaining strong fine-tuning performance.

---

### [112] Explore-over-Graph: Hybrid Embedding-LLM Reasoning for Knowledge Graph Question Answering under Incompleteness

**链接**: https://arxiv.org/abs/2609.39786
**作者**: Ola El Khatib and Djellel Difallah
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [113] Memory Canonicalization: A Framework and Benchmark for Cross-Model Drift in Persistent LLM Memory

**链接**: https://arxiv.org/abs/2610.05124
**作者**: Amit Vadnere, Aishwarya Lonarkar
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Persistent memory for Large Language Models (LLMs) has matured rapidly: systems such as MemGPT/Letta, Mem0, and Zep now provide agents with tiered, temporally-aware, model-agnostic external storage, while the Model Context Protocol (MCP) standardizes access to memory servers. A less addressed problem is that an identical stored memory object, retrieved by two different LLMs under otherwise identical conditions, may not be interpreted the same way, factually or emotionally. This paper proposes memory canonicalization: a write-time pipeline that detects ambiguity, conditional structure, and emotional loading in a raw memory object and rewrites it into an explicit, structurally disambiguated canonical form, with emotional valence represented as a separate field rather than inferred from tone. We formalize the pipeline, define a companion Cross-Model Semantic Drift / Emotional Consistency Score benchmark (CMSC-E), and report results from a three-arm pilot using 176 synthetic memory objects

---

### [114] Self-Reflection Fine-Tuning: Enhancing Agent Security against Prompt Injection Attacks from Failure Experience

**链接**: https://arxiv.org/abs/2610.04269
**作者**: Zixuan Wang, Hao Li, Fengyu Gao, G. Edward Suh, Yi Zeng, Yevgeniy Vorobeychik 等 (8 人)
**来源**: cs.LG cs.CR
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents are increasingly deployed in tool-augmented environments, but their reliance on external inputs makes them highly vulnerable to prompt injection attacks that can hijack task objectives. Existing safety alignment methods rely on static expert trajectories or preference optimization, limiting their ability to generalize to adaptive attack patterns. In this work, we propose Self-Reflection Fine-Tuning (SRFT), a training framework that enables agents to improve robustness by learning from their own failure experiences under adversarial conditions. Instead of passively imitating expert behaviors, SRFT exposes the agent to compromised trajectories constructed via injected attacks, and leverages an expert model to generate structured self-reflection reasoning that contrasts unsafe and optimal actions. This reflective supervision teaches the agent to identify malicious instructions, reason about their consequences, and maintain alignment with the original user

---

### [115] Distributed Subliminal Learning: Replacing Model Updates with Random-Carrier Outputs

**链接**: https://arxiv.org/abs/2610.05378
**作者**: Dario Fenoglio, Gabriele Dominici, Martin Gjoreski, Marc Langheinrich
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models, LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Collaborative learning typically exchanges model parameters: federated clients communicate updates, while independently adapted foundation models are combined by exchanging adapters or checkpoints. This makes communication scale with model size and requires local specializations to be reconciled in weight space, where interference is common. We ask whether knowledge can instead be shared through model behavior on task-unrelated inputs. We introduce Distributed Subliminal Learning (DSL), a collaborative learning primitive in which participants adapt a common model locally, probe it with task-unrelated inputs, and transmit only the resulting carrier outputs. A coordinator pools these outputs and distills them into a shared model. The primitive supports one-shot foundation-model composition through carrier completions and iterative federated learning through carrier logits, without transmitting model updates or requiring task-related proxy data. In LLM composition, compared with LoRA aver

---

### [116] Dynamic Minimax Regret Optimization for Robust LLM Post-Training

**链接**: https://arxiv.org/abs/2610.06329
**作者**: Chengbo Zang, Haoyu Dong, Mehmet Kerem Turkcan, Gil Zussman, Zoran Kostic, Javad Ghaderi
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Modern LLM training increasingly relies on heterogeneous data sources spanning different domains, tasks, preference distributions, and difficulty levels. We study dynamic minimax regret for group-distributionally robust LLM post-training under instantaneous mini-batch-only bandit feedback. The framework views the training as a two-player sampler-optimizer process: a sampler adaptively selects among data sources using bandit feedback, while an optimizer updates the model parameters using stochastic gradients from the selected source. We focus on the practically restrictive setting where source losses evolve with model training but historical data are not re-evaluated, requiring the sampler to track instantaneous worst-sources from stale partial feedback. We propose DUCB-OGD, a simple and scalable algorithm that couples a Discounted Upper-Confidence-Bound sampler with an Online Gradient Descent optimizer. The sampler maintains exponential moving average loss estimates and confidence radi

---

### [117] TrustMI: Causally controlling how assistants trust their users

**链接**: https://arxiv.org/abs/2610.06064
**作者**: Th\'eo Lasnier, Romain Froger, Maxence Lasbordes, Djam\'e Seddah
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Model (LLM) assistants routinely decide whether they can trust users and third parties whose competence, intentions, and integrity they cannot verify. This uncertainty matters for safety, as trusting the wrong party can lead an agent to comply with harmful requests or act on malicious instructions encountered during tool use. To study this problem, we define trust as an assistant's willingness to accept vulnerability to the actions of another party and ask whether such behavior can be causally controlled through model activations. We build 2,000 contrastive conversations spanning ability, benevolence, and integrity, where paired responses complete the same request but differ in whether the assistant trusts the user. From these pairs, we learn steering matrices while keeping the model parameters frozen and test them across six instruction-tuned models from three families, finding that steering changes trust decisions monotonically in both directions. We then ask whether t

---

### [118] Don't Judge an LLM Only by Its Activations: Discovering Suppressed Safety Features via Counterfactual Activation Potential

**链接**: https://arxiv.org/abs/2610.05541
**作者**: Swadesh Swain, Sanghamitra Dutta
**来源**: cs.LG cs.AI cs.CL cs.CR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Mechanistic interpretability has emerged as the primary means to understand safety behavior of LLMs. However, existing tools primarily focus on the activating neurons or features of a model. The role of the remaining large set of inactive components is invisible to such methods. This work demonstrates that the inactive set contains safety-critical features that are causally relevant for refusal of harmful prompts. Suppressing such features could turn refusals into compliance, while passing undetected by prevalent interpretability tools. We introduce the Counterfactual Activation Potential (CAP), a metric that quantifies a suppressed feature's latent activation tendency as the product of its encoder alignment (how strongly the input drives it), suppression strength (how strongly active features inhibit it), and safety criticality (how much refusal depends on it). To find suppressed safety features at scale, we propose CAP-guided Safety Feature Discovery (CSFD), a two-stage filtering alg

---

### [119] Measuring the Depth of LLM Unlearning via Activation Patching

**链接**: https://arxiv.org/abs/2605.24614
**作者**: Jaeung Lee, Dohyun Kim, Jaemin Jo
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [120] An Executable Benchmark for LLM-Based HLS Repair:Design Complexity and Repair Underconstraint

**链接**: https://arxiv.org/abs/2610.03971
**作者**: Maisha Mastora, Dean Sullivan
**来源**: cs.AR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Automated repair of High-Level Synthesis (HLS) designs using large language models (LLMs) is an emerging but underexplored problem. While LLM-based repair shows strong results on register-transfer level (RTL) Verilog, the only prior systematic study of HLS logic repair reports just 10.5% correction accuracy for GPT-4, with no analysis of why repair fails or what drives difficulty. We present the first comprehensive evaluation of LLM-based HLS repair across four models (GPT-4o, GPT-4o-mini, GPT-5.4, and Claude Opus 4.6) on 125 benchmark instances spanning eight logic bug types across three open-source HLS suites (CHStone, MachSuite, Polybench). We construct the first executable APR-style HLS repair benchmark with suite-specific functional oracles, enabling pass@k evaluation rather than the string-match approximations used in prior work. Design context and scale, rather than bug type alone, dominate repair difficulty: repair rates range from 6-45% on complex cryptographic kernels (CHSton

---

### [121] CIPO: Counterfactual Imagination Policy Optimization for Adaptive Tool Granularity Selection

**链接**: https://arxiv.org/abs/2610.04991
**作者**: Yu Li, Yunlu Wan, Zijian Zhu, Han Luo, Chao Ren, Long-Fei Li 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents solve complex tasks through multi-step interactions with external tools. These interactions often contain recurring local tool sequences. Treating such sequences as composite "Skills" can shorten tool-use trajectories and reduce repeated low-level decisions. However, when atomic tools and composite skills coexist, skill use becomes a policy problem: the agent must decide whether the current state requires atomic fine control or skill-level abstraction. In this paper, we argue that effective skill use should be studied as adaptive tool granularity selection. The most direct training signal for this problem is to compare the consequences of atomic and skill choices available from the same state. Based on this view, we propose CIPO, a Counterfactual Imagination Policy Optimization framework for adaptive tool granularity. CIPO constructs executable skills through budget-constrained mining of successful tool-use trajectories and trains granularity decisions

---

### [122] TeleGen: Improving LLM-Based Web Application Generation via Runtime Telemetry

**链接**: https://arxiv.org/abs/2610.04981
**作者**: Yujia Luo, Haonan Zhang, Jiasi Shen, Zishuo Ding, Weiyi Shang
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models can generate runnable web applications from natural-language requirements, but many generated applications still fail interactive tasks. Existing generate-execute-repair pipelines execute the generated application and use task outcomes or error messages to guide code revision. However, this feedback often misses the runtime behavior between a browser action and the final task outcome, making interaction-level failures difficult to diagnose. Therefore, we propose TeleGen, an observability-enhanced framework for LLM-based web application generation. TeleGen instruments generated applications, collects runtime telemetry during task execution, and compresses raw telemetry logs into concise briefs for repair. We evaluate TeleGen on WebGen-Bench and Web-Bench. On WebGen-Bench, TeleGen improves task success from 67.7% with repair without telemetry to 76.2%, an increase of 8.5 percentage points. On Web-Bench, it improves cumulative Pass@2 from 21.7% to 29.8%. Ablation res

---

### [123] Is Escalation Worth It? On the Depth of LLM Cascades

**链接**: https://arxiv.org/abs/2605.06350
**作者**: Dylan Bouchard
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [124] RAISED: Self-Distillation for Robustness to Prompt Injection in LLM Agents

**链接**: https://arxiv.org/abs/2610.06401
**作者**: Mohamed Dhouib, Clement Elliker, Alexi Canesse, Ma\"el Jenny, Lucas-Andrei Thil, Mahammed El-Sharkawy 等 (8 人)
**来源**: cs.CR cs.AI cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tool-using language-model agents are vulnerable to indirect prompt injection because they must act on untrusted external content. Existing training-time defenses can reduce attack success rates, but often at the cost of general capabilities. We show that training-based defenses induce substantial drift in the model's output distribution, altering its behavior even in benign settings and providing a potential mechanism for utility degradation. We further identify a failure mode of these defenses: On benign tool-use tasks, the model refrains from a step needed to finish an authorized task, particularly when that step is indicated by a tool output. To address these limitations, we introduce RAISED (Robust Attack Invariance through Self-Distillation), a training framework that combines self-generation and self-distillation. The model first generates its own tool-use scenarios, with an emphasis on cases where task completion requires acting on legitimate guidance from tool outputs. Then, th

---

### [125] Characterizing High Bandwidth Flash for LLM Serving

**链接**: https://arxiv.org/abs/2609.39131
**作者**: Zack Yu, Chloe Wong, Coleman Hooper, Minjae Lee, Wonjun Kang, Youngjin Cho 等 (10 人)
**来源**: cs.LG cs.AR cs.DC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [126] EnvSimBench: A Benchmark for Evaluating and Improving LLM-Based Environment Simulation

**链接**: https://arxiv.org/abs/2605.07247
**作者**: Yi Liu, TingFeng Hui, Wei Zhang, Li Sun, Ningxin Su, Jian Wang 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [127] MDKeyChunker: What Does One LLM Call per Chunk Buy for Markdown Retrieval?

**链接**: https://arxiv.org/abs/2603.23533
**作者**: Bhavik Mangla
**来源**: cs.CL cs.AI cs.IR cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [128] Dataset Signatures in Human-LLM Interactions and User Modeling

**链接**: https://arxiv.org/abs/2610.05534
**作者**: Joseph Suh, Serina Chang
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Human--LLM interaction datasets shape our understanding of AI use and provide a foundation for downstream research, including training and evaluation of user models. In recent years, a growing number of datasets have sought to capture a representative picture of human--LLM interactions. But how different are the pictures these datasets provide, and what do those differences mean for research built on them? We study these questions across seven conversation datasets, spanning in-the-wild chat logs and human preference data. We begin by revisiting the dataset classification experiment of Torralba & Efros and find that neural network classifiers identify the source of a conversation from user messages alone well above chance, indicating distinctive dataset signatures. This separability persists after matching datasets on the dimensions of human-designed taxonomies, implying subtle differences that these taxonomies do not capture. We then examine the implications for user modeling: how dat

---

### [129] RubricArmor: Adversarial Evolution Improves LLM-Based Rubric Generation

**链接**: https://arxiv.org/abs/2610.05308
**作者**: Haocheng Yang, Yuchao Zhang, Licheng Pan, Jiajun Fan, Maolin Wang, Kangning Zhang 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Rubric-based reinforcement learning (RL) provides interpretable rewards for aligning large language models (LLMs) by evaluating responses against query-specific evaluation criteria. To construct rubrics at scale, a straightforward approach to LLM-based rubric generation is to prompt an LLM to generate a rubric directly from the query. However, rubrics directly generated by LLMs are vulnerable to reward hacking, since omitted or underspecified criteria allow the policy to obtain high rubric rewards with low-quality responses. Existing LLM-based rubric generation methods improve the granularity and coverage of the generated criteria but do not proactively guard against reward hacking. To address this limitation, we propose RubricArmor, an adversarial framework that exposes and mitigates potential reward hacking at the rubric generation stage before it occurs in subsequent RL. Specifically, RubricArmor performs adversarial evolution, in which an attack step and a repair step alternate ove

---

### [130] ElasticMem: Latent Memory as a Learnable Resource for LLM Agents

**链接**: https://arxiv.org/abs/2605.30690
**作者**: Tao Feng, Chongrui Ye, Fangxu Yu, Tianyang Luo, Jingjun Xu, Xueqiang Xu 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [131] Grounded Continuation: A Linear-Time Runtime Verifier for LLM Conversations

**链接**: https://arxiv.org/abs/2605.14175
**作者**: Qisong He, Jinwei Hu, Xinmiao Huang, Changshun Wu, Yi Dong, Xiaowei Huang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [132] ProsaBuddy: Assisting Mechanized Real-Time Schedulability Analysis with LLM-based Agents

**链接**: https://arxiv.org/abs/2610.03796
**作者**: Junyi Liu, Tianchi Ren, Fei Guan, Xu Jiang, Zhe Jiang, Wang Yi 等 (7 人)
**来源**: cs.LO cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Rigorous schedulability analysis is essential for the design of hard real-time systems, yet errors in pen-and-paper proofs threaten the safety of critical applications. The Prosa initiative addresses this by offering a foundation for building machine-checkable schedulability analysis proofs in the Rocq proof assistant. However, the substantial time and expertise required to construct such proofs remain a major barrier for wider adoption of Prosa. This work presents ProsaBuddy, an LLM?based agent system designed to lower the effort needed to develop mechanized real-time schedulability proofs. ProsaBuddy employs a ReAct loop with retrieval over the Prosa codebase, access to Rocq tools and optional human-written hints. It uses a subgoal?delegation architecture, decomposing a lemma into subgoals and dispatches them to subagents for proof. We evaluate ProsaBuddy on a mini benchmark drawn from real-time scheduling literature. Experiment results show that ProsaBuddy significantly outper?forms

---

### [133] Memory as a Controlled Process: Learned Adaptive Memory Management for LLM Agents

**链接**: https://arxiv.org/abs/2607.13591
**作者**: Eric Hanchen Jiang, Zhi Zhang, Yuchen Wu, Levina Li, Dong Liu, Xiao Liang 等 (10 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [134] Safety is Contextual, LLM-Judges Are Not: Navigating the Rigid Priors of Evaluators

**链接**: https://arxiv.org/abs/2606.07874
**作者**: Anissa Alloula, Federico Licini, Ava Batchkala, Seraphina Goldfarb-Tarrant
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [135] Cross-lingual Calibration of Pre-Generation Success Probes for Multilingual LLM Routing

**链接**: https://arxiv.org/abs/2610.06216
**作者**: Andrea Paganelli and Stefano Civelli and Pietro Bernardelle and Gianluca Demartini
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Pre-generation success probes estimate response correctness from a language model's hidden activations before decoding, enabling cost-aware routing. While prior work has demonstrated their utility primarily on English inputs, we study their reliability across languages along three dimensions: (1) whether they preserve the ranking of likely successes and failures (DISCRIMINATION); (2) whether they retain probabilities that match observed success frequencies (CALIBRATION); and (3) whether they produce scores comparable enough across candidate models for cost-aware multilingual routing (UTILITY). Using 3,000 MATH problems in 10 languages and 8 open-weight model configurations, we compare cross-lingual transfer from English-trained probes and equal-budget pooled multilingual probes. English-trained probes retain useful cross-lingual discrimination but become less well calibrated after transfer. Pooled multilingual supervision improves both properties and yields more reliable estimates of s

---

### [136] Plant, Persist, Trigger: Sleeper Attack on Large Language Model Agents

**链接**: https://arxiv.org/abs/2605.28201
**作者**: Yongxiang Li, Moxin Li, Zhixin Ma, Fengbin Zhu, Wenjie Wang
**来源**: cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [137] Can Agent Harnesses and Inference Engines Hear Each Other? The HEAR Protocol for Agentic LLM Serving

**链接**: https://arxiv.org/abs/2610.06597
**作者**: Jiaqi Zhao, Haodong Chen, Jitai Hao, Wei Zhao, Jinghao Pang, Qiang Huang 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents increasingly execute complex workflows involving multi-turn reasoning, tool use, and parallel agents. Efficient serving requires decisions that span two layers with complementary information: the agent harness understands workflow dependencies, context lifecycles, and execution objectives, whereas the inference engine observes request queues, KV-cache state, resource pressure, and execution capabilities. Existing interfaces do not systematically connect these views, limiting workflow-aware execution. HEAR, a bidirectional Harness--Engine Pairing protocol for agentic LLM serving. HEAR standardizes how the harness communicates workflow intent and execution requirements and how the engine returns runtime state, capabilities, and outcomes. By separating protocol semantics from optimization policies, HEAR supports diverse coordination strategies without changing workflow or model semantics. We instantiate HEAR for online cache-aware runtime coordination and workload-aware executi

---

### [138] Differentiable Bit-Widths: Co-optimizing Pruning and Quantization via SVD for Ultra-Efficient LLM Compression

**链接**: https://arxiv.org/abs/2610.06026
**作者**: Hankyul Kang, Jongbin Ryu
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> SVD-based pruning and quantization have recently emerged as a promising strategy for the ultra-efficient compression of large language models. In these methods, compression is performed in two stages: components are first truncated, and the remaining ones are subsequently quantized. Although this decoupled pipeline benefits from both pruning and quantization, it requires separate optimization for each stage and fails to fully exploit their balance, which can lead to suboptimal performance under aggressive compression. To address this limitation, we propose a new LLM compression method that co-optimizes pruning and quantization in a unified framework. Our key idea is a differentiable method for learning component-wise bit-widths, allowing less important components to be assigned 0-bit precision and pruned away. Notably, our method performs favorably against two-stage baselines, even when subjected to extreme quantization settings ($1.61$ bits) designed for ultra-efficiency. Code: https:

---

### [139] Conformal Prediction with Paraphrase-Aware Scoring for LLM Uncertainty Quantification

**链接**: https://arxiv.org/abs/2610.04239
**作者**: Jiayi Xin, Evan Qiang, Zihan Zhu, Xiang Li, Weijie J. Su, Qi Long
**来源**: cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Uncertainty quantification (UQ) for large language models (LLMs) aims to provide reliable measures of predictive confidence, yet current methods are often unstable under meaning-preserving perturbations. Semantically equivalent paraphrases can induce substantial variability in predictive confidence, even for methods with formal guarantees, such as conformal prediction. To address this issue, we propose a paraphrase-aware UQ framework robust to semantic rewordings. Our approach trains a lightweight proxy model on LLM hidden states and aggregates its predictions across paraphrases to construct label-wise nonconformity scores. Under score exchangeability, conformal calibration retains marginal coverage. This guarantee can also hold under test-only rewording, provided that the paraphrase pipeline satisfies an additional distributional alignment condition. We evaluate three settings (normal, fully reworded, and semi-reworded) which apply rewording to neither dataset, both calibration and te

---

### [140] ORCA: The Annealed Spectral Conditioning Optimizer for Faster, Better LLM Training

**链接**: https://arxiv.org/abs/2610.06116
**作者**: Yuanshi Liu, Boyuan Jiang, Liang Hou, Xin Tao, Pengfei Wan, Zhouchen Lin 等 (7 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Modern LLM optimizers such as Muon often produce weight matrices with higher effective rank than Adam, yet further spectral control has delivered only modest gains. We identify a tension behind this result: concentrated spectra can suppress gradient directions in coupled weight matrices and slow optimization, while constraints maintained throughout training can limit task-specific adaptation and raise the attainable loss floor. We introduce ORCA (Orthogonal Regularization, Cooled After), a minimal optimizer intervention that applies strong but temporary soft orthogonality regularization early in training, then removes it. This allows the weights to benefit from a broader spectrum early on and adapt freely afterward. Across LLaMA, Qwen3, and fine-grained mixture-of-experts models ranging from 130M to 8B parameters, ORCA achieves lower final validation loss than Muon. Its loss reduction relative to Muon matches or exceeds Muon's reduction relative to Adam. Ablations support the early-sha

---

### [141] EnterpriseBench: Benchmarking LLM Agents on Enterprise-Level Strategic Reasoning and Decision-Making

**链接**: https://arxiv.org/abs/2609.37658
**作者**: Min Yang, Yichen Pan, Jinghua Piao, Dandan Song, Yongshun Gong, Yong Li
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [142] Beyond Objective Equivalence: Constraint Injection for LLM-Based Optimization Modeling on Vehicle Routing Problems

**链接**: https://arxiv.org/abs/2606.04816
**作者**: Xizi Luo, Changhong He, Dongdong Geng, Chenggong Shi and Yu Mei
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [143] What Did the AI Take On? Characterizing Cognitive Delegation in LLM Reasoning

**链接**: https://arxiv.org/abs/2610.06328
**作者**: Yoonsu Kim, Sean Kim, Kihoon Son, Saelyne Yang, Juho Kim
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) often perform intermediate cognitive work while carrying out users' requests, yet it remains unclear which parts users intended to delegate and how they wanted to remain involved. This matters because consequential choices may go unnoticed, limiting users' ability to steer the process, while reviewing every step would make delegation burdensome. We examined this with 24 LLM users across three knowledge-work tasks, collecting 992 retrospective annotations of reasoning steps. From this, we developed taxonomies of LLM cognitive work, delegation enactment, and desired delegation protocols at the reasoning-step level. Our analysis revealed that participants viewed about half of all steps (48.6%) as AI-initiated, meaning the AI took on work they had not requested. Desired involvement varied with cognitive work and delegation enactment, even when contributions matched participants' intent. We propose design implications and sketches for supporting more deliberate 

---

### [144] Inductive Claims Extraction at Scale

**链接**: https://arxiv.org/abs/2610.05275
**作者**: Sandrine Chausson, Bj\"orn Ross
**来源**: cs.CL cs.CY cs.SI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A large part of political discourse on social media is built and expressed at a level of claims: i.e. declarative, typically single-clause statements, which convey a particular interpretation of reality and can range from factual to evaluative. Moreover, rather than occurring randomly, claims coalesce, recur in patterns, and come to be associated with different world views. When paired with structural computational tools such as Social Network Analysis, claims can be a powerful unit of analysis to study political phenomena such as echo chambers or polarisation. In this paper, we present a pipeline that uses a large language model (LLM) to inductively extract and catalogue claims from large social media corpora, and apply it to two different Twitter datasets: one relating to the 2020 US presidential election and the other to the 2022 FIFA World Cup. We comprehensively evaluate the approach by measuring the pipeline's recall and precision against manually annotated samples, run ablation 

---

### [145] Hidden in the Request: Explaining Unethical LLM Compliance through Token Relevance

**链接**: https://arxiv.org/abs/2608.23264
**作者**: Or Biton, Tomer Krichli, Itai Allouche, Joseph Keshet
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [146] StagQ: Constraint-Driven Multi-Precision Weight Quantization for LLMs

**链接**: https://arxiv.org/abs/2610.05977
**作者**: Zhe Wei, Mengqi Guo, Yuan Yuan, Jiunn Bin Lim, Boyi Pan, Michael Bi Mi
**来源**: cs.LG cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Serving a large language model (LLM) across a fleet of deployments requires several weight-precision operating points. Multi-precision formats serve them all from one stream whose prefixes are valid lower-precision codes, instead of storing multiple copies. We present StagQ, a multi-precision weight format whose main stream is a 2-bit group-wise affine base followed by a configurable number of 1-bit refinement planes on a dyadic step schedule. Every supported precision is a readable prefix, decoded by an affine map derived from metadata shared across all precisions, with no per-weight lookup. A sparse side record, filled both before and after the grid is fitted, holds out the few weights the grid serves worst. We report two configurations of the encoder. At two bits the cheaper one leads the strongest multi-precision baseline on Llama-3.1-8B, Phi-4, and OLMo-2-7B by 3.1 to 7.0 MMLU points, at a slightly lower logical rate. At three bits it leads on Llama-3.1-8B, leads on Phi-4 at a hig

---

### [147] Robust LLM Unlearning Against Relearning Attacks: The Minor Components in Representations Matter

**链接**: https://arxiv.org/abs/2605.11685
**作者**: Zeguan Xiao, Xuanzhe Xu, Yong Wang, Jian Yang, Yanqing HU, Yun Chen
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [148] CyTReX: Explainable AI-Based Cybersecurity Threat Reasoning Framework for DER Networks

**链接**: https://arxiv.org/abs/2610.04286
**作者**: Damilola Popoola, Souradeep Bhattacharya, and Manimaran Govindarasu
**来源**: cs.CR cs.AI cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Distributed Energy Resource (DER) environments rely on network communication protocols to coordinate control commands, measurements, and device states across edge assets and cloud systems. Edge anomaly detection systems (ADS) monitor this traffic to identify deviations from normal communication behavior, flagging suspicious flows for further investigation. When the ADS flags abnormal network traffic, a single attack label is often insufficient for operational response: the label reports the detector's selected class but does not expose alternative threat interpretations that may warrant investigation. This paper presents Cybersecurity Threat Reasoning with Explainable Artificial Intelligence (CyTReX), an evidence-grounded threat reasoning framework for DER security that transforms network-level anomaly alerts into ranked, analyst-facing threat hypotheses designed to support Security Operations Center (SOC) triage and investigation. CyTReX constrains large language model (LLM) reasoning

---

### [149] REFLEX: Reflective Evolution from LLM Experience

**链接**: https://arxiv.org/abs/2606.16496
**作者**: Pan Wang
**来源**: cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [150] InferOpt: Constrained Multi-Objective Search for LLM Inference Configurations

**链接**: https://arxiv.org/abs/2610.04473
**作者**: Qi Chen, Yingying Cheng, Zhaoyi Sun, Li Zhou, Fan Zhang, Jie Sun
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Serving an LLM means setting dozens of inference-time knobs, from per-layer KV retention to per-layer expert counts. Practice sets them with mechanism-specific heuristics that return a single operating point and do not scale to layer-wise search spaces. We recast inference configuration as constrained multi-objective black-box optimization and build InferOpt, a reusable search framework that requires only variable bounds, a deterministic resource cost, and an evaluation hook. InferOpt searches on a frozen sampled proxy set, rejects over-budget candidates before any model call, tightens the budget adaptively, and re-validates Pareto representatives on full-scale dataset. One pipeline covers a 28-dimensional continuous KV space (Qwen2.5-7B) and a 26-dimensional discrete MoE space (DeepSeek-V2-Lite). On KV, post-prefill pruning cuts the 16K cache by 64.4% and TPOT by 22.9--48.5%, and the searched layer-wise budget by InferOpt beats a matched uniform budget by 7.3% and 14.0% of the Full KV

---

### [151] User Misconceptions of LLM-Based Conversational Programming Assistants

**链接**: https://arxiv.org/abs/2510.25662
**作者**: Gabrielle O'Brien, Antonio Pedro Santos Alves, Sebastian Baltes, Grischa Liebel, Marcos Kalinowski
**来源**: cs.HC cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [152] A Self-Calibrating Framework for Analog Circuit Sizing Using LLM-Derived Analytical Equations

**链接**: https://arxiv.org/abs/2604.07387
**作者**: Antonio J. Bujana and Aydin I. Karsilayan
**来源**: cs.AR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [153] Probability Contracts: Accuracy, Coherence, and Decisions Across LLM Interfaces

**链接**: https://arxiv.org/abs/2609.37470
**作者**: Han Chen, Yingrui Li
**来源**: cs.LG stat.ML
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [154] Errors of LLM-Assisted Literature Retrieval in Environmental Science: A Comparison Study of Abstract versus Full-text Based Prompts

**链接**: https://arxiv.org/abs/2610.05690
**作者**: Yanjun Chen (1, 2), Yongfeng Zhang (3), Lanjing Zhang (1, 3, 4 等 (10 人)
**来源**: cs.DL cs.IR cs.LG stat.AP stat.ME
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly used for literature search and synthesis. However, it is unclear whether they retrieve accurate bibliographic information in environmental science. Therefore, we quantitatively compared the errors of widely used LLM platforms in retrieving references related to original articles from five leading environmental science journals (Energy and Environmental Science, Nature Sustainability, Nature Climate Change, Lancet Planetary Health, and Environmental Science and Technology) published in 2024 to 2025. Claude, ChatGPT, Grok, DeepSeek, Perplexity, and Gemini were used as the LLM platforms. LLMs retrieved 10 references for each of the 50 randomly selected original article using either the article's abstract or its full-text as prompt. The retrieved references were subject to a multimetric score ratio combining validity of bibliographic data, Google Scholar link, digital object identifier, Scopus Electronic Identifier and relevance score (cited by

---

### [155] The Value of a Prompt: An LLM-Relative Kolmogorov-Complexity Approach

**链接**: https://arxiv.org/abs/2608.16438
**作者**: Rafael Pass
**来源**: cs.AI cs.CC cs.IT math.IT
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [156] Factorized Delayed Streams Modeling for LLM-based Streaming ASR

**链接**: https://arxiv.org/abs/2610.04333
**作者**: Tatsunari Takagi, Kai Washizaki, Atsushi Kojima, Lianbo Liu, Koki Nikaido, Yui Sudo
**来源**: eess.AS cs.CL cs.SD
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Delayed Streams Modeling (DSM) enables LLM-based streaming automatic speech recognition (ASR) by aligning acoustic and text streams on a common timeline. DSM adds the padding token <p> and the word-start token <w> to the LLM vocabulary and predicts them together with normal text tokens using the same softmax. We first show that <w> can be removed while maintaining competitive recognition performance. Based on this result, we propose Factorized DSM (F-DSM), which separates the waiting probability for <p> from the distribution over the original LLM vocabulary. This factorization removes ASR-specific tokens from the text prediction space and allows the large-vocabulary softmax to be skipped on waiting steps. Experiments on the Corpus of Spontaneous Japanese and LibriSpeech show that F-DSM achieves better recognition performance than DSM. It also greatly reduces GPU memory use while maintaining similar training throughput, provides a small inference speed improvement through softmax skippi

---

### [157] How Much Do LLM-as-a-Judge Design Choices Matter? A Systematic Comparison of Prompt Designs, Rating Scales, and Models

**链接**: https://arxiv.org/abs/2610.05094
**作者**: Laur\`ene Vaugrante, Thilo Hagendorff
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Researchers increasingly use Large Language Models as judges (LLM-as-a-judge) to evaluate model outputs. Yet there are no standards for how to design these judges. Typically, researchers choose the prompt, rating scale, and model intuitively. If these choices change the judge's verdicts, two studies can reach different conclusions about the same facts. To address this risk and to provide an empirical basis for judge designs, we evaluate 10 reasoning models across multiple designs on two tasks: a scalar rating of sentence sentiment and toxicity (over 500 items per category), as well as a binary accuracy classification of question-answer pairs (n=600). For the rating tasks, despite judges showing significant disagreements with the human ground truth, the practical size of differences is small enough to consider most judges reliable (mean absolute deviation of 0.11 points on a 1 - 7 scale); toxicity judges even outperform standard classifiers. Judges are also highly accurate on average (9

---

### [158] From Requirements to Attack Trees: Grounded LLM Agents for Design-Time Security Review

**链接**: https://arxiv.org/abs/2610.03820
**作者**: Akash Iyer, Taha Demirkan, Keerthi Koneru, Aaryan Siddharthan, Sheethal Kumar, Ramesh Radhakrishnan
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Design-level security weaknesses can arise from requirements, trust assumptions, missing controls, and data flows before implementation begins. Existing security practices often identify these issues after code is written. We present a multi-agent LLM framework for design-time security analysis from product requirement documents and architecture diagrams. The proposed framework parses architecture diagrams into graph representations, generates misuse and failure cases, constructs attack trees, checks governance and compliance gaps, recommends mitigations, assigns enterprise security-domain tags, and produces a candidate revised architecture recommendation for expert review. The framework does not retrieve from Common Weakness Enumeration (CWE) databases at inference time. Instead, it analyzes system behavior, trust boundaries, component interactions, and data-flow assumptions. Misuse cases act as intermediate representations that link findings to system components and attack paths, whi

---

### [159] Improving Diversity in LLM Short Story Generation

**链接**: https://arxiv.org/abs/2610.06729
**作者**: Zahra Solati Dehkordi and Vasileios Lampos
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) can generate accurate responses, but these are void of diversity. We attempt to address this for the task of creative short story generation. Drawing on established writing conventions and known LLM limitations, we target variation in genre, tone, style, and named entities. To promote diversity across these dimensions, we introduce DivLM, an LLM post-training framework consisting of two phases. First, we perform continued pre-training on a creative writing corpus and restore instruction-following capabilities using weight residuals. We then apply reinforcement learning with a custom, composite reward function that jointly maximizes diversity across the targeted narrative dimensions while maintaining response quality. Our empirical results on two LLM families show that DivLM increases diversity metrics by more than 9% on average compared to alternative approaches, while preserving instruction following, overall response quality, and similarity to human outpu

---

### [160] Do Tool Calls Execute as Intended? Measuring and Repairing Intent-Execution Correspondence in LLM Agents

**链接**: https://arxiv.org/abs/2610.04375
**作者**: Boyang Yang, Zhenhao Li, Ziyao Yang, Kanghui Jia, Xin Yin, Mingmou Liu 等 (7 人)
**来源**: cs.AI cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Agents built on large language models (LLMs) build and run software through tool calls. A call reaches its program through several hops, and any hop can change the call without notice. When the changed call fails, the agent retries a correct call, which costs users time and money. Benchmarks and failure analyses do not see the change, because they read the call and its result but not what a hop received. We define intent-execution correspondence (IEC) as the property that the executed action matches the action the emitted call denotes under the tool contract. Our protocol observes what each hop received without executing the call, and names the first hop that changed it by the receiver's own parser. IntAct then delivers the call in a form that this hop cannot alter, or refuses the call. We build IEC-Bench from the changes observed in real-world use, with chains of dependent calls under the execution paths of 4 widely-used harnesses. In 47,828 shell calls within production sessions, Cla

---

### [161] VulValidate: Auditing Function-Level Vulnerability Labels with Executable Evidence

**链接**: https://arxiv.org/abs/2610.05103
**作者**: Leizhen Zhang, Sheng Chen
**来源**: cs.CR cs.AI cs.SE
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reliable learning-based vulnerability detection requires high-quality labels, yet datasets built from vulnerability-fixing commits may label functions as vulnerable simply because they were changed by a security patch. We present VulValidate, a framework that uses LLM agents to coordinate dynamic analysis tools and construct vulnerability-triggering experiments from runtime feedback. Given a labeled function and its fixing patch, VulValidate reconstructs vulnerable and fixed revisions, selects suitable tools and execution paths, refines triggering inputs, and compares runtime behavior to assess function-level attribution. We audit all 35,849 instances originally labeled vulnerable in BigVul, PrimeVul, and DiverseVul. We confirm 20,510 (57.2%), correct 6,819 labels (19.0%), leave 7,981 attacked but undecided (22.3%), and cannot successfully measure 539 (1.5%). After conflict resolution and byte-exact deduplication, the corrected release contains 15,890 distinct confirmed vulnerable func

---

### [162] Disentangling Task Difficulty from Run-Level Failure in Agent Failure Prediction

**链接**: https://arxiv.org/abs/2610.05572
**作者**: Mohsen EsfandyariDoulabi, Lawrence Arkoh, Biruk Tadesse, Vaishvi Patel, Mehul Sharma, Marcelo d'Amorim and Wesley Assun\c{c}\~ao
**来源**: cs.LG cs.SE
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Predicting whether an LLM agent will fail has emerged as a promising direction for supporting intervention during execution. Recent approaches report strong predictive performance, often with AUROC values between 0.85 and 0.94. However, predictors are typically trained by pooling runs from many tasks. We hypothesize that part of this performance comes from recognizing that some tasks are harder than others, rather than detecting whether a particular run is heading toward failure. This distinction matters because task-level difficulty supports decisions about where to allocate computation, while run-level prediction is needed to decide whether to intervene in an ongoing trajectory. We study benchmarks with repeated attempts of the same task by the same agent and separate cross-unit comparisons from comparisons between successful and failed runs of the same model-task unit. Across the evaluated corpora, more than 99.93% of the positive-negative pairs underlying pooled AUROC are cross-uni

---

### [163] You Changed Your Mind, The Model Didn't: Demystifying Intent in Multi-Turn Dialogue

**链接**: https://arxiv.org/abs/2610.06496
**作者**: Junle Chen, Wei Chen, Zhengjun Huang, Zhoujin Tian, Yuxuan Liu, Kai Wang 等 (8 人)
**来源**: cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> When a large language model handles a multi-turn task and a user proposes a change but ultimately rejects it, the model should continue as if nothing changed. We find a surprising failure: merely mentioning a rejected change can derail task execution, even when the user's final intent remains unchanged. To systematically study language model behavior under evolving user intent, we introduce Intent-Eval, a controlled benchmark spanning tool actions, code, databases, and mathematics. Across diverse tasks, models are vulnerable to both rejected proposals and superseded requirements, consistent with mentioned-as-in-effect confusion: conversational content is treated as active requirements even after it has been rejected or replaced. Accuracy degradation can deepen or persist as interaction continues, highlighting the need to distinguish what has been mentioned from what remains in effect. Building on this insight, we propose Intent-OPSD, a decision-conditioned on-policy self-distillation f

---

### [164] PyINE: A Framework for Scalable Elicitation and Oversight via Code Execution

**链接**: https://arxiv.org/abs/2610.04737
**作者**: Pierre-Luc St-Charles, Alessandro Palmas, Damiano Fornasiere, Storm Lei, Mirko Bronzi, Jean-Pierre Falet 等 (8 人)
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reasoning models can remain capable of solving a task while still defaulting to cheaper but misleading shortcuts. This creates a central oversight problem: when a model gives an answer with plausible but incomplete reasoning, can an overseer determine whether that output should be trusted? To study this problem, we introduce PyINE, a framework for scalable elicitation and oversight using instrumented Python programs as a verifiable execution substrate. In PyINE, programs define task environments, execution traces provide authoritative labels for outcomes and intermediate facts, and task variants can be generated mechanically rather than through static human annotation. We instantiate the framework in PyINE-v1, a first release built from nearly one million deterministic execution traces and over 500,000 matched LLM-generated code variants used for counterfactual evaluation. Using standard RL with verifiable rewards on cue-varied tasks, we train a shortcut-following model that improves s

---

### [165] Large Language Models and Augmented Democracy

**链接**: https://arxiv.org/abs/2610.04412
**作者**: Jairo Gudi\~no-Rosero
**来源**: cs.CY cs.CL cs.CR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Artificial intelligence enables computational agents to represent political preferences and take part in collective decision-making. In this thesis, I investigate the opportunities and challenges of digital twins (DTs) based on Large Language Models (LLMs) as intermediaries in augmented democracy, focusing on individual preference representation, collective representation of political organizations, and the vulnerability of those representations to attackers. First, using data from an online experiment in Brazil, I examine whether personalized DTs can predict citizens' preferences for unseen policy proposals. Second, I extend the DT framework from individuals to political organizations. Using Swiss parliamentary data, I build topic-specific knowledge graphs from lawmakers' legislative records and connect them to LLM-based lawmaker agents, which are organized into party-level DTs representing collective positions. Agentic deliberation among these agents tests whether aggregated party re

---

### [166] Word-Level Text Unmixing via Evidence-Preserving Ownership Routing with Language Models

**链接**: https://arxiv.org/abs/2610.06603
**作者**: Jinglin He, Siyang Jiang, Lixing He, Guoliang Xing, Hongkai Chen
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Text from multiple sources can become interleaved into a single sequence when attribution metadata is lost, such as overlapping speech transcripts, document reading flows, or concurrent agent streams. We formalize this challenge as Word-Level Text Unmixing: given an interleaved lexical stream and source count K, recover the original source sequences while preserving every word occurrence and its within-source order exactly. Directly generating separated texts with LLMs can omit, duplicate, or hallucinate words, violating this exact-reconstruction objective. We therefore propose Evidence-Preserving Ownership Routing (EPOR), which decouples source-ownership prediction from reconstruction. EPOR adapts a causal LLM to predict canonical ownership routes conditioned on the mixed stream and prior routing decisions. At inference, completion-safe constrained decoding is combined with deterministic indexed reconstruction, yielding structurally valid K-source partitions that preserve every observ

---

### [167] Aligning Multimodal Patient Evidence with Biomedical Knowledge Graphs for Clinical LLMs

**链接**: https://arxiv.org/abs/2610.06685
**作者**: Jiawen Du, Arshan Ali Khan, Chenhao Zhang, Zachary Plotkin, Li Shen, Qi Long 等 (10 人)
**来源**: cs.LG cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Clinical questions often depend on linking a patient's multimodal evidence to external biomedical knowledge, yet existing predictive systems rarely represent such links explicitly, so they can neither be traced to their evidence sources nor removed to measure their contributions. We present MM-KG (Multimodal Knowledge Graph), which represents heterogeneous, multimodal patient observations and biomedical concepts as separate layers in one typed graph, joined by explicit alignment edges. First, modality-specific harmonizers convert EHR text, imaging, genomic, and biospecimen data into typed observations mapped to UMLS concepts, which a route-prioritized aligner links to a biomedical knowledge graph. Query-conditioned retrieval then selects a compact subgraph for downstream use by a large language model or a graph neural network. We build MM-KGs for MIMIC-IV and ADNI, and evaluate them with a 2x2 design that separates patient evidence, biomedical knowledge, and their interaction. On quest

---

### [168] Request Order Matters: Cache-History Sensitivity in Selective KV-Cache Reuse for Rolling Agents

**链接**: https://arxiv.org/abs/2610.05833
**作者**: Tiffany Gu, Annie Guan, Manshu Huang, Nitin Rao, Siddhant Shah, Margaret Capetz
**来源**: cs.AI cs.LG cs.PF
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-running agents repeatedly call an LLM while retaining most of their document window, evicting old documents, and appending new ones. These rolling updates break exact prefix caching and motivate non-prefix KV-cache reuse with selective recomputation. We show that persistent KV-cache reuse with selective recomputation can be history-dependent: in our rolling-agent workload, an unchanged prompt can produce different answers depending on the requests processed before it. At a matched 5% recomputation budget, document-aligned recomputation reduces answer variation across request orders from 69.0% with CacheBlend's token top-$k$ policy to 26.1%. When each prompt is evaluated after a different sequence of preceding requests, document-aligned recomputation improves fidelity to full prefill by 34.5-52.5 percentage points over token top-$k$, while both policies achieve approximately 5.7$\times$ median TTFT speedup. Our ablation study shows that, in our rolling-agent workload, contiguity is

---

### [169] From Traces to Agentic Worlds: Agentic Language World Models for Interactive Environment Simulation

**链接**: https://arxiv.org/abs/2610.06100
**作者**: Quanyu Long, Xiao Chen, Jianda Chen, Haozhen Zhang, Qisheng Hu, Jianzhu Bao and Wenya Wang
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Realistic environment replicas are increasingly valuable for training and evaluating LLM agents, yet the original systems may be inaccessible or impractical to reproduce. We explore agentic language world modeling: rather than rebuilding an executable environment, a world model agent serves as the environment for a task agent and supports faithful and stateful simulation. We instantiate this paradigm with Trace2Env, a learning-free framework for settings where the original system is unavailable but historical interaction traces remain accessible. Trace2Env reconstructs these traces into a reusable environment worldbook containing environment schemas, grounded evidence, and induced behavioral knowledge. At runtime, the world model agent actively consults the worldbook together with persistent episodic state to infer each action's observation and lasting state effects. Across nine environments, Trace2Env improves both next-observation fidelity and long-horizon interaction consistency ove

---

### [170] MMPostTrainBench: Benchmarking Autonomous Research for Multimodal Post-Training

**链接**: https://arxiv.org/abs/2610.05398
**作者**: Yuxin Liu, Yuxuan Wang, Zhenxin Lei, Lingchen Meng, Yuchong Sun, Junming Lin 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Autonomous research seeks sustained model improvements through iterative experimentation and feedback. LLM agents show promise in automating machine learning and language-model post-training, but their ability to sustain multimodal improvement remains unclear. We introduce MMPostTrainBench, a benchmark spanning eight tasks in image, audio, video, and joint audio-video understanding and image-grounded software repair. Agents operate from a common base model within fixed budgets, using development feedback before independent evaluation of their submitted models. Evaluation covers target and non-target model outcomes, iterative model improvement and selection, and research integrity. Across all eight tasks, 52.1% of model--task means fall below the base, and evaluated submissions also exhibit non-target regressions. Model performance does not consistently improve across research iterations, and agents do not reliably select the best evaluated candidate for submission; final submissions tr

---

### [171] Memadapter: Counterfactual Adaptation Against Memory-induced Sycophancy

**链接**: https://arxiv.org/abs/2610.05162
**作者**: Ruqing Ning, Haibo Meng, Zhishang Xiang, Zerui Chen, Jinsong Su, Xin Wang and Qinggang Zhang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-term memory enables LLM-based agents to retain and reuse information across tasks and sessions, supporting personalization and long-horizon interactions. However, persistent memories can also induce sycophancy, causing agents to over-align with users' historical beliefs even when they are inaccurate, outdated, or inconsistent with objective evidence. Existing mitigation methods assume that memory-induced sycophancy originates from biased or incorrect memories and attempt to reduce this risk by filtering such memories at different stages of the memory pipeline. However, in the real world, objective and correct memories can still induce sycophancy, and the same memory can warrant different influence across different contexts. To this end, we propose MemAdapter, a novel framework that adaptively integrates retrieved memories to support objective and reliable reasoning. Specifically, MemAdapter consists of three components: (i) Counterfactual Induction, which leverages counterfactual 

---

### [172] Do Small Language Models Learn to Negotiate? A Controlled Scaling Study of RL-Trained Sellers

**链接**: https://arxiv.org/abs/2610.06204
**作者**: Pedro Tabacof, Sagar Joglekar
**来源**: cs.AI cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents are starting to own the full customer experience. Soon, LLMs may be selling and buying on behalf of companies and customers respectively. Small models are more cost-efficient at scale, but can reinforcement learning train them into competent sellers? We train four Gemma 4 checkpoints (2.3B to 31B effective parameters) with GRPO on a programmatic utility reward for bilateral multi-issue bargaining, and evaluate every arm on the same 1,152 negotiations against two frontier buyers it never saw in training. With the same learning rate ($10^{-6}$) for every size, the gain of the RL model over its base rises from $+0.001$ at 2.3B to $+0.078$ at 31B. Each size was trained once and the two smallest checkpoints use a different architecture, so we fit no scaling law. Tripling the learning rate, with the same or fewer training steps, improves on the shared rate at every size by $+0.032$ (2.3B) to $+0.081$ (4.5B). In exploratory comparisons with two frontier models run as sellers, the 1

---

### [173] Lens3D: Target-Conditioned Visual Foveation for Fine-Grained 3D Understanding

**链接**: https://arxiv.org/abs/2610.06611
**作者**: Junming Huang, Zini Chen, Shuaiying Hou, Chi Wang, Qiang Dai, Weiwei Xu
**来源**: cs.CV
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Existing 3D large language models often overlook fine-grained attributes and less visually salient objects and parts, even when relevant evidence is present in scene videos. We introduce Lens3D to improve fine-grained object understanding through external visual assistance and knowledge transfer. Its LensUnd pipeline adopts 3D localization to select informative, complementary views for an external 2D vision-language model, supporting fine-grained object captioning, small-object grounding, and fine-grained object question answering. LensDistill transfers the resulting fine-grained knowledge to 3D LLMs through detailed caption supervision, enabling captioning from native inputs without external VLM calls. We also construct LensBench, a held-out evaluation set of 2,068 objects with three silver-standard reference descriptions per object. Experiments with Video-3D LLM and 3DRS demonstrate that LensDistill substantially improves fine-grained object captioning while preserving existing groun

---

### [174] BAIBAICHUCHU at the NTCIR-19 FinArg-3 Task: When Is Maximum Possible Profit Predictable from Investor Text?

**链接**: https://arxiv.org/abs/2610.03962
**作者**: Zong-Han Bai, Po-Yen Chu
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The BAIBAICHUCHU team participated in the Social Media Subtask of NTCIR-19 FinArg-3, ranking Chinese investor posts by Maximum Possible Profit (MPP). A three-track ensemble of lexical features, a FinArg-2-pre-finetuned MacBERT ranker, and an LLM judge reaches 0.734 in post-grouped development evaluation, but our best official run scores 0.517. All twelve submitted runs lie between 0.4598 and 0.5402, and our 26 unanimous three-track pairs score 0.500. A post-hoc audit finds that the submitted judge applied a long-only rule to bearish posts although MPP is stance-aware. Correcting it changes 28 of 87 official predictions without changing accuracy, yet lowers development accuracy from 0.680 to 0.622: a regime-specific semantic shortcut improved validation fit. We decompose ranking into directional text, volatility and horizon, and pairwise margin. A running-extremum model predicts $\sigma\sqrt{T}$ scaling, observed ex post in 502 price-aligned posts from a separate July 2026 collection. P

---

### [175] Adaptive Operator Selection in Bilevel Large Neighborhood Search for Electric Autonomous Dial-a-Ride Problem under Uncertainty

**链接**: https://arxiv.org/abs/2610.04219
**作者**: Ishara Hewa Pathiranange and Aneta Neumann
**来源**: cs.NE cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The electric autonomous dial-a-ride problem (EADARP) extends the classical dial-a-ride problem by incorporating battery and charging constraints for electric vehicles. In practice, travel-time uncertainty can cause violations of time-window constraints. Large neighborhood search is effective for solving the EADARP, but its performance can depend on the choice of insertion operator during the repair phase. This paper investigates insertion-operator selection within a bilevel large neighborhood search framework for deterministic and chance-constrained variants of the EADARP. In the chance-constrained variant, arc travel times are modeled as independent normally distributed random variables, and upper time-window constraints are enforced probabilistically. We consider six selection methods, namely fixed greedy insertion, fixed regret-based insertion, random selection, a deterministic state-based rule, performance-adaptive ALNS selection, and LLM-based state-aware selection. Experimental r

---

### [176] ShadowMiner v1 - An Experience Report on Implementing and Measuring a Problem-and-Hypothesis Discovery Engine

**链接**: https://arxiv.org/abs/2610.04339
**作者**: Jinhyuk Choi
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> ShadowMiner v1 is a system that automatically discovers research problems and generates hypotheses from AI papers. It is a nine-stage pipeline. It structures documents into a knowledge graph and finds graph gaps in it - structural blind spots in research. These graph gaps are included in the LLM generation prompt. Each generated hypothesis is then verified by checking whether it is already covered by existing research, scoring its quality, and checking that the facts it relies on are accurately drawn from its sources. This report does not propose a new generation or evaluation technique. It describes our experience of implementing and applying ideas from prior work, and measuring whether each one actually contributed.

---

### [177] The Cost of a Hop: Benchmarking NLIP and A2A

**链接**: https://arxiv.org/abs/2610.04053
**作者**: Ranjan Sinha, Anindita Das, Ashika Anand Babu, Hari Palleti
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Autonomous agents built on Large Language Models (LLMs) need standardized protocols to interoperate across systems. Several now exist (A2A, MCP, ACP, ANP, NLIP), but the Natural Language Interaction Protocol (NLIP) has not appeared in any controlled performance study, and no work has measured where an agent protocol's latency is spent. We compare NLIP and the Agent-to-Agent (A2A) protocol empirically, decomposing latency into message creation, connection, and send phases across three independent hardware environments. For lightweight coordination, NLIP is 8.4-9.6x faster than the baseline A2A SDK implementation on two environments and about 4x on a third; the direction of the advantage is consistent, its magnitude depends on the hardware. The advantage is stage-specific: for the end-to-end pipeline, where LLM inference dominates, the protocols are near parity. The difference comes almost entirely from connection setup. To test A2A at its best, we also ran A2A SDK with connection cachin

---

### [178] How Execution Assumptions Change Short-Horizon Sharpe Rankings: Evidence from a Synthetic Trading Benchmark

**链接**: https://arxiv.org/abs/2610.05077
**作者**: Weicheng Xue
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Backtests of LLM trading agents often assume that every order fills at the closing price. We ask whether this choice changes only reported returns or also the order of the agents. Five prompted LLM signal policies and seven classical baselines trade the same synthetic price paths under six execution settings, from near-ideal fills to latency, spread, participation, and impact stresses. The main experiment contains $2{,}462$ runs with matched decision frequencies and paired market paths. On the compressed two-asset board, agreement between the near-ideal and default-stress rankings falls to Kendall $\tau_b=0.21$ in the high-volatility regime, compared with $0.82$ in the calm regime. The seed-bootstrap intervals, $[0.00,0.52]$ and $[0.48,0.94]$, are wide and overlap. On a fixed 11-policy board, agreement rises from 0.24 with two assets to 0.85 with ten; the two-asset point estimate differs substantially from the wider settings we tested. Rank changes are related to turnover, and comparis

---

### [179] Scaling Down the Scaling Laws: Parameter Efficiency and Compute-Optimal Training in Resource-Constrained Large Language Models

**链接**: https://arxiv.org/abs/2610.06387
**作者**: Joe Dwyer
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) have achieved substantial performance gains through increases in model size, training data, and computational resources. However, traditional scaling approaches produce diminishing returns, rising financial and environmental costs, and barriers to participation for researchers operating outside large industrial laboratories. This review examines the evolution of LLM scaling theory from empirical scaling laws to compute-optimal training, with particular emphasis on parameter efficiency, token utilization, data efficiency, and resource-constrained environments. Foundational work on scaling laws is synthesized alongside later research on compute-optimal training, data pruning, efficient architectures, quantization, low-rank adaptation, and edge-oriented optimization. The literature indicates a shift from scale maximization toward more deliberate allocation of parameters, tokens, compute, and hardware resources. At the same time, important empirical, theoretica

---

### [180] Breaking the Tie: A Cluster-Aware Routing Framework for Large Language Models

**链接**: https://arxiv.org/abs/2610.05982
**作者**: Yao Lu, Zhaiyuan Ji, Yaxin Gao, Zeyu Wang, Zhe Tang, Jiaheng Wei 等 (9 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> With the rapid development of artificial intelligence, the emergence of various Large Language Models (LLMs) has created a rich model ecosystem. However, this also brings a key challenge: how to select the optimal model for a specific user query. LLM routing addresses this need by dynamically assigning queries to the most suitable expert in the pool of candidate models. However, existing routing frameworks often simplify this process to a standard classification task; thus, a critical vulnerability is exposed when multiple candidate models correctly answer the same query. We formalize this capability overlap as routing noise, which misleads the router with arbitrarily correct candidate models, ultimately leading to routing collapse (a severe decline in generalization ability on unseen tasks). To address this problem, we propose a novel Cluster-Aware Soft-Labeling Routing (CASLR) framework. CASLR shifts the evaluation paradigm from the success of a single query to macro-domain consensus

---

### [181] Ontology Concept Overlap as a Training Signal: Knowledge-Grounded Reinforcement Learning for Clinical Question Answering

**链接**: https://arxiv.org/abs/2610.06360
**作者**: Aditya Tanna, Abhishek Jindal
**来源**: cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reinforcement learning post-training for language models relies on two reward designs: human preferences (RLHF, DPO) and binary verifiers (RLVR). Clinical question answering fits neither. Near-correct answers differ by a single substituted entity, and no executable check decides clinical correctness. We instantiate a soft verifier from a maintained controlled vocabulary: UMLS Concept Unique Identifier overlap (via scispaCy, set-level F1) gives a graded, externally specified reward computed without a model in the loop. We combine it inside GRPO with an entropy-normalised LLM judge, which covers the safety and evidence axes overlap cannot see, and a small consistency penalty on padding and repetition that keeps early-training samples scorable. This three-term composite improves over SFT on Phi-3-mini (3.8B) over MedQA by 2.9% on EM (0.700 vs 0.680) and 39% on Token-F1 (0.202 vs 0.145); on Llama-3.2-3B the corresponding gains are 14% on EM and 35% on Token-F1. We report Token-F1 as the pr

---

### [182] Saying, Not Knowing: Aggressively GGUF-Quantized Small Language Models Still Write Rare Words They Can No Longer Define

**链接**: https://arxiv.org/abs/2610.04403
**作者**: Saurabh Kumar Singh, Yogeshwar Singh Dadwhal, Malhar Vedak
**来源**: cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Post-training quantization to the GGUF format's mixed-precision K-quants is commonly how open-weight language models reach consumer hardware, yet its effect on fine-grained lexical competence is uncharacterized. We audit 27 quantized artifacts across 13 families and four architecture backbones, 0.35B-14B parameters, evaluated down their published ladder to Q2_K (about 2.6 bits per weight), on 429 frequency-validated rare English words under two probes: surface inclusion of a prompt-supplied word and its one-sentence definition, scored by a tiered multi-synonym matcher, its error measured by a blind LLM-judge census of every definition, with human verification. Three regimes emerge at Q2: total collapse into unusable builds, severe semantic dissociation in sub-2B models, and mostly robust preservation above about 3B. In every sub-2B artifact, definitions fall 20-67% below the artifact's baseline, typically several times the inclusion loss. Two controls separate rarity from task difficul

---

### [183] OceanMind: A multi-agent AI system for ocean diagnosis

**链接**: https://arxiv.org/abs/2610.03780
**作者**: Fan Zhang, Weicong Cheng, Yuheng Chen, Hiuseut Kung, Ying Zhang, Aixi Han 等 (9 人)
**来源**: physics.ao-ph cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Time-dependent, three-dimensional (3D) oceanic multi-variables define coherent states of the evolving ocean to facilitate ocean diagnosis and advance ocean science to better inform environmental and hazard management. However, extracting quantitative evidence from these variables requires substantial and complex analytical effort. We introduce OceanMind, a multi-agent AI system that directly couples large language models (LLMs) with comprehensive time-dependent 3D ocean states for swift and effective diagnosis. OceanMind organizes the analytical process into four coordinated complexity stages: Query Routing, Skill-based Planning, Tool Execution, and Evidence-based Summary Generation. Specialized agents interpret user requests, construct and execute multi-step computational workflows, and synthesize quantitative evidence. To ensure reliable workflow construction, 63 reusable ocean-specific analysis skills serve as procedural manuals that guide the LLM agent in selecting data, conducting

---

### [184] Synthesizing Physics Formulae with Transformers

**链接**: https://arxiv.org/abs/2610.03947
**作者**: Shuwei Wang, Vadim Bulitko, Michael Youngblood, Ramon Lawrence, William Yeoh, Shinichi Nakagawa 等 (8 人)
**来源**: cs.LG cs.SC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Finding a compact formula that fits a set of input-output pairs and predicts outputs on unseen inputs is a fundamental problem in science. Symbolic regression automates the search for such formulae: search-based methods explore the space of possible formulae directly, while transformers pre-trained on synthetic data produce formulae of comparable quality substantially faster. Existing transformers, however, are prone to overfitting --- they find formulae that fit the training data well but do not extrapolate to input ranges unseen during training. We address this by shaping the set of formulae used to train a transformer, and show that the resulting formulae extrapolate substantially better. Fine-tuning the transformer on data with noise-corrupted target values further makes the synthesized formulae robust to noise in the observations. On SRBench and LLM-SRBench our transformer synthesizes a formula in about ten seconds and extrapolates better than all evaluated methods at a comparable

---

### [185] Asking Earns Nothing: Scoring the Decision to Act in BFCL Multi-Turn

**链接**: https://arxiv.org/abs/2610.04429
**作者**: Yangze Liu, Zhongyi Han
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> An agent that lacks the information it needs should ask rather than act, and the task definitions of agent leaderboards say so. BFCL multi-turn builds two of its four categories around a turn on which the model is supposed to ask, and its scorer never looks at that turn: the gold trajectory there is empty, the checker skips it, and the scripted user cannot answer, so asking earns nothing, guessing costs nothing on that turn, and asking twice loses the item. The benchmark also contains the control experiment for that decision. A should-ask item is a base item with one piece of information removed from one turn, so the same request appears twice at the same turn index, once complete and once not: on the first the model should make the call that changes the world, on the second it should ask. We score one decision per pair, whether the model attempted a world-changing call on that turn, read off the stored trajectories with no LLM judge; acting always and asking always both score 50. On t

---

### [186] Boundaries Agree, Labels Do Not: Intra-Annotator Dynamics as a Kind of Training Data

**链接**: https://arxiv.org/abs/2610.04370
**作者**: Marharyta Shvets
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Data quality now matters as much as compute for training language models. Much training data comes from human annotation of text, and interpretive annotation has no ground truth that could settle what is "accurate". Two lines of work respond to this. One combines annotators into a "ground truth" and measures how well they agree with each other; the other treats their disagreement as a signal. Both compare different people at one point in time. We measure something else: how well one reader reproduces their own reading of the same text over time. One expert human reader and three LLM families segmented three Sumerian myths and labelled the causal function of each segment with one of seven states. Across runs months apart, the human cut the text in much the same places but named the segments differently, in every myth. The models show no such consistent pattern: their gap between the two layers is positive in some myths and negative in others, and its size varies. The human's label chang

---

### [187] StateWise: Diagnosing and Repairing Persistent Operational State Before Agent Actions

**链接**: https://arxiv.org/abs/2610.05241
**作者**: Yongyuan Peng, Zhou Feng, Tongying Wu, Jiahao Chen, Yuan Su, Chunyi Zhou 等 (8 人)
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents combine reasoning, tool use, and persistent memory to support work across tasks by reusing stored operational records as premises for later actions. However, environmental or requirement changes can invalidate these records, while existing action review, provenance tracking, and clarification mechanisms may leave the underlying persistent state uncorrected. Our audit of coding-agent trajectories identifies candidate failure chains in which invalid records are reused, leading to task failures and unsafe modifications. We propose StateWise, a framework for diagnosing and repairing persistent operational state before action execution. StateWise uses record-level counterfactual replanning to identify decision-critical records, then establishes their current validity through reliability checks, read-only verification of machine-observable facts, and targeted clarification of developer-owned intent. Typed evidence grounding binds evidence to specific records and scopes, enabling p

---

### [188] Does AI Help Cyber Attackers or Defenders? Evidence from Nonpublic Vulnerabilities and Subsequent Attacks

**链接**: https://arxiv.org/abs/2610.06584
**作者**: Tobias Heldt, Matt Turk, Christoph Landolt, Mario Fritz
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The release decision for frontier AI systems increasingly relies on cyber capability benchmarks, yet public vulnerability benchmarks can expose agents to previously published advisories, exploits, and fixes, making it difficult to distinguish prior exposure from capability on unseen vulnerabilities. We evaluate open-weight and proprietary AI models on exploit generation, vulnerability repair and subsequent attacks in five nonpublic software environments, including vulnerabilities we privately disclosed while they remained unpatched. Researcher-developed and reviewed deterministic graders, not LLM judges, determine task scores. Comparisons with 209 disclosed vulnerabilities and cryptographic challenges reveal substantial variation across systems and vulnerability types. Repair scores exceed attack scores in two nonpublic environments and fall below them in three. Passing an initial security test is also insufficient: another exploit succeeds in 92 of 524 non-independent defender test in

---

### [189] Principled Top-$k$ Selection for Language Models with Hybrid Gradients

**链接**: https://arxiv.org/abs/2610.04162
**作者**: Xuchen Gong, Junfei Sun, Tian Li
**来源**: cs.LG cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Selecting the best $k$ items out of $m$ candidates is a critical component of modern large language model systems, such as document selection in Retrieval-Augmented Generation (RAG) and expert routing in Mixture-of-Experts (MoEs). However, training these selection modules remains challenging due to weak gradient signals and suboptimal exploration-exploitation tradeoffs. Furthermore, prior works often rely on heuristics, lacking principled objectives and approaches that explicitly model and solve the top-$k$ selection problem. In this work, we propose a principled objective for training selection modules, whose gradient naturally provides richer training signals in a hybrid form---containing a supervised-gradient component and a policy-gradient component. We show that the selection problem becomes harder as $m$ increases, and our algorithm converges at rate $O(1/\sqrt{T})$, with the optimal upper bound achieved by balancing between bias and variance. Practically, we apply our method to 

---

### [190] Recursive Video In-Context Learning for Agentic Robot

**链接**: https://arxiv.org/abs/2610.06843
**作者**: Wenrui Bao, Xinxin Liu, Bingxin Xu, Yuzhang Shang
**来源**: cs.RO cs.AI cs.CL cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents that orchestrate frozen vision-language-action (VLA) policies improve across episodes through text memory, which records what the agent did but not how the task is done. A demonstration video shows it, but fits poorly into an agent's context. The full video slows every turn, fixed keyframes lose the contact detail that decides whether a grasp holds, and what the agent needs shifts from the task's structure while planning to the frames around each contact. We introduce Recursive Video In-Context Learning (RV-ICL), a training-free method that turns a demonstration into a hierarchy the agent navigates rather than a prompt it receives. The hierarchy is built from the sub-events of the demonstration, such as grasps and releases. Its levels grow finer, from keyframes of the whole task to phases, moments and short clips, and are exposed through read-only tools. The agent reads the coarse levels before planning. During execution it re-enters the hierarchy whenever a step needs more 

---

### [191] Collaborative Personalized Preference Alignment for LLMs under Data Deficiency

**链接**: https://arxiv.org/abs/2610.05898
**作者**: Liyan Yang and Yige Yuan and Zhiqin Yang
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Real-world users often exhibit highly heterogeneous preferences over multiple objectives for LLM responses. A lightweight aligner can tailor these responses to individual preferences, but scarce user-specific feedback makes personalized training difficult. Learning shared initializations across users can support few-shot adaptation. However, heterogeneous preferences and competing objectives cause gradient conflicts across users and within each user, hindering effective initialization learning. This raises a central question: \textbf{how can we collaboratively learn aligner initializations that support few-shot adaptation to diverse user preferences?} To answer this question, we propose \textbf{A}pproximate \textbf{P}areto \textbf{O}ptimality (APO). We first group users whose updates are compatible, so that their information can be combined with less interference. Within each group, we combine gradient descent with controlled ascent to coordinate competing objectives and move towards p

---

### [192] VHDL-REPOBENCH: A Repository-Level Benchmark for Evaluating Large Language Models on VHDL Design Generation

**链接**: https://arxiv.org/abs/2610.05380
**作者**: Prashanth Vijayaraghavan, Akul Malhotra, Ashutosh Jadhav, Ehsan Degan, Vandana Mukherjee
**来源**: cs.PL cs.AR cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) are increasingly applied in hardware design automation, demonstrating strong potential in generating and understanding hardware description languages. However, most existing benchmarks focus on Verilog, with limited evaluation of VHDL, which remains widely used in industry and academia for FPGA and safety-critical systems. To address this gap, we introduce VHDL-REPOBENCH, a large-scale, cross-file, repository-level benchmark for assessing LLM capabilities on realistic VHDL design generation and analysis tasks. VHDL-REPOBENCH curates ~100 open-source VHDL repositories, encompassing ~2.5k VHDL files and ~500 testbenches, and provides structured problem statements, module stubs, and self-verifying testbenches. The benchmark enables comprehensive evaluation across syntax, semantic correctness, hierarchical reasoning, cross-file dependency resolution, and functional verification. We evaluate several state-of-the-art models, including GPT-4o, Llama-3-70B, Qwen2.5

---

### [193] Readable Before Actionable: Causal Tracing of Indirect Prompt Injection

**链接**: https://arxiv.org/abs/2610.05295
**作者**: Zhe Yu, Wenpeng Xing, Xingxing Yang, Meng Han
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Indirect prompt injection causes LLM agents to follow commands embedded in external data. A probe may distinguish instructions from data without identifying a state edit that changes the next action. We study this gap through counterfactual role probes, component-wise activation patching, and separate interventions on AgentDojo trajectories. Role decoding survives changes in content and format. In controlled Qwen tests, it precedes strong tool-choice effects from patches along an independently estimated role direction. On AgentDojo, directions estimated from hijacked and resisted training trajectories reduce attack success at pre-action and injected-span positions, but have little effect at random positions. In longer Qwen trajectories, single-position edits become less effective at later layers; span-wide and repeated edits reduce attack success on the same evaluation set. Removing the learned channel subspace preserves role decoding, yet effective intervention directions transfer poo

---

### [194] DP-ES: Differentially Private Evolution Strategies for Prompt Optimization

**链接**: https://arxiv.org/abs/2610.06236
**作者**: Ziniu Liu, Aiping Li, Yue Han, Han Yu, Junjian Zhang, Dong Zhu 等 (8 人)
**来源**: cs.CR cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Token-level differentially private (DP) prompt optimization methods such as DP-OPT can become unstable under tight privacy budgets: on GSM8K, DP-OPT obtains $49.5\pm28.5\%$ across 30 runs, and a logged search trajectory reveals prompt-template drift and noise-sensitive irreversible choices. We diagnose these as structural consequences of greedy token-by-token construction over privately aggregated counts. We then propose DP-ES (Differentially Private Evolution Strategies), a structurally cleaner alternative that maintains a population of full prompts, mutates them via LLM calls that never access the private dataset, and spends privacy only on sampled-Gaussian evaluation; deterministic or Gumbel-smoothed selection is post-processing. Under a conservative $(\varepsilon\leq1.0,\delta=10^{-5})$ guarantee, DP-ES achieves 88.1% on GSM8K (+38.6 pp over DP-OPT, approximately 9 times lower standard deviation), 99.7% on MedQA, 73.5% on BANKING77, and 86.8% on Alpaca. It is also 2.5 times faster 

---

### [195] Stance Drift: How AI-mediated Communication Distorts Our Message

**链接**: https://arxiv.org/abs/2610.04620
**作者**: Lingchong Liu, Yanfei Zhou, Jacob Bien, Y.X. Rachel Wang, Lucy Xia, Xin Tong
**来源**: cs.CL stat.AP
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) increasingly mediate human communication, from drafting emails to summarizing scientific reports, yet whether they faithfully preserve a speaker's position remains largely untested. We model AI-mediated communication as a two-step generation-extraction pipeline: one LLM produces an argument from a specified stance, and a second LLM extracts the stance from that argument. We represent the pipeline as a probabilistic state transition over five Likert-type stance categories and define the stance preservation rate (SPR) as the average probability that the extracted stance matches the initial stance. Across 112 debate propositions, none of the nine LLMs tested exceeded an SPR of 0.7 under the default configuration. Three drift patterns accounted for most of the drift: polarization, deviation from neutrality, and flipping. Among the mitigation strategies tested, including in-context learning, multiple extraction with shuffled options, assertion, and reflection, o

---

### [196] JEV versus LLMs: Accuracy, Cost and Calibration on Seven Political Science Replications

**链接**: https://arxiv.org/abs/2610.06625
**作者**: Matthew DiGiuseppe and Steven Denney
**来源**: cs.CL cs.CY
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) annotate and scale political text or constructs by generating text tokens. A new class of models, which TypeSafe markets as "System One" models, instead returns decisions and probability distributions across a user-supplied fixed answer set. A commercial model, JEV, is advertised as having a dramatic cost and speed advantage over traditional LLMs along with better calibrated decisions. As such, it might be useful for social scientists looking to quickly and cost-effectively annotate or scale large corpora of text and have a reliable indicator of a classifier's uncertainty. Yet, the accuracy of these claims and the broader model accuracy in social science text-based tasks are not yet established. In this paper, we do just that and hope to establish the suitability of JEV for social science tasks. We compare JEV with LLMs and human coders from published research, and with a current mid-tier commercial LLM (GPT-6 Luna) and an open-weight alternative (Qwen3.8-2

---

### [197] If My Toy Could Talk: How Young Children Imagine, Design, and Test AI-Enabled Toys

**链接**: https://arxiv.org/abs/2610.06619
**作者**: Feiwen Xiao, Ruiyang Wu, Xinyue Cui, Yasitha Rajapaksha, Xiaoyi Tian, Shiyan Jiang 等 (7 人)
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> To investigate the design space where children might design AI chatbots for their own toys, we developed ToyTalk, a technology probe that positions children as designers of LLM-enabled toys. Children begin with a familiar toy, configure its AI-enabled version through a no-code interface, and then interact with and test the character. We deployed ToyTalk with 76 children aged 7-9 across five elementary schools in the southeastern U.S. We examine how children define their toy, probe what it becomes, and respond when behavior diverges from expectations. Children predominantly designed toys with socially positive personalities, supportive roles, and interpersonal rules. In conversation, they most often probed identity and knowledge, while also testing capabilities, memory, and relationships. When mismatches arose, children typically responded through correction, persistence, and retesting, while few returned to reconfigure the system. We discuss implications for children's design agency, t

---

### [198] From Benchmark to Bench: Can Agents Survive Real-World Drug Discovery?

**链接**: https://arxiv.org/abs/2610.06411
**作者**: Pierre Llompart, Levent Guner, Helen Lai, Alessandro Tibo, Yijie Xu
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Agentic systems increasingly coordinate molecular-design tools, but it is unclear which layer of the stack limits outcomes on real projects. We developed MAGI, an open modular agent that authors objectives, launches and monitors optimization, interprets structure--activity relationships, and revises its strategy accordingly. MAGI generates molecules either directly through the LLM or by delegating to REINVENT 4, with scoring services interchangeable behind a common contract. We tested it across nine retrospective lead-optimization campaigns from three pharmaceutical companies, replayed under fixed temporal cutoffs. Both routes produced valid structures: LLM proposals stayed closer to local chemistry and reached comparable or higher primary activity in fewer operations, whereas REINVENT explored broader chemical space. Whether a campaign met its objective depended on the predictive models, not on the generation route: attainment followed model accuracy on the chemistry proposed, droppin

---

### [199] SEIS: Self-Evolving Inference Systems

**链接**: https://arxiv.org/abs/2610.04646
**作者**: Zhen Xu, Jingyu Liu, Zongze Li, Tahseen Rabbani, Ce Zhang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Inference systems determine how fast and how cheaply language models can be served, so making them faster has direct practical value. However, prior work focuses mostly on optimizing certain parts such as kernels or memory within the large system. In this work, we take a holistic approach and apply agentic self-evolution to optimize the whole system end-to-end. Our SEIS (Self-Evolving Inference Systems) autonomously optimizes the entire mini-sglang engine without human intervention through iterative sessions with inherited experiences and code changes. Serving Qwen3-0.6B on H100, the resulting engine reaches 3.27X the throughput of the original mini-sglang implementation and beats SOTA engines like vLLM, TensorRT-LLM, and SGLang in the single-request workload. The correctness of the optimized inference engine by SEIS is tested in terms of numerical difference and downstream accuracy on math and long-context retrieval tasks. The code and session histories show that the speedup comes fro

---

### [200] Mind the Accent Gap: British Accent Robustness in Speech-Driven Financial Voice Assistants

**链接**: https://arxiv.org/abs/2610.06587
**作者**: Aadam Haq, Oggi Rudovic, Malcolm Chadwick, Jay Rainey, Shucong Zhang, Ricardo Guerrero 等 (8 人)
**来源**: cs.SD cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> AI voice assistants often use Automatic Speech Recognition (ASR) with LLM-based reasoning, yet existing systems struggle with regional British accents, including Scottish, Irish, and Welsh accents, since most ASR models are trained predominantly on American English voice data. Consequently, errors can carry through to the LLM stage, corrupting tool-call arguments and producing wrong or missing responses, which is especially costly in finance. Deployable ASR must also meet tight latency and memory budgets, making an accent-robust model choice even harder. We introduce CavaBench, the first internally collected benchmark of spoken financial queries, and use it to evaluate a range of ASR models and their end-to-end ASR-LLM pipeline behaviour across self-reported British accents. We find that WER strongly predicts downstream tool-calling accuracy ($r = -0.93$) but can fail to reflect task-level performance, with accent-related failures varying substantially across models and acoustic condit

---

### [201] When LLMs Sit Above Diagnostic Tools: Unrealized Complementarity in Industrial Fault Diagnosis

**链接**: https://arxiv.org/abs/2610.05031
**作者**: Donghwan Kim
**来源**: cs.CL cs.SY eess.SY
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models are increasingly used as integration layers above specialized tools, but a stronger component does not necessarily produce a stronger combined system. Across five diagnostic datasets (bearing vibration, process monitoring, semiconductor equipment), we study whether an LLM can reliably use external diagnostic information; paired repeat calls separate advice effects from output instability. In all five, conflicting external information overturned initially correct LLM judgments. Among the four datasets with direct integration comparisons, none showed a consistent advantage for implicit LLM integration over the stronger standalone source. On a Tennessee Eastman confirmation set whose protocol was fixed before evaluation, unaided accuracy was 64.67%, implicit LLM-specialist integration 77.43%, and the specialist alone 83.33%. Specialist information improved the LLM by 12.8 points (95% interval 9.7 to 15.9), yet the integrated output stayed 5.9 points below the special

---

### [202] Asynchronous Is Nearly Free for Evolution Strategies on Long-Horizon Agentic Tasks

**链接**: https://arxiv.org/abs/2610.04196
**作者**: William Hoy, Jingxuan Fan, Nurcin Celik, Xu Pan
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based long-horizon agentic post-training is often bottlenecked by rollout generation: trajectories span many interaction turns, completion times vary substantially, and synchronous update barriers leave faster workers waiting for stragglers. Asynchronous reinforcement learning which has been adopted in LLM post-training addresses this inefficiency by consuming trajectories as they arrive, but introduces policy lag and off-policy optimization. Evolution strategies (ES) offer a backpropagation-free alternative for LLM post-training, yet it relies on a larger number of rollouts and existing practices have remained largely synchronous. In this short-form paper, we introduce bounded-staleness asynchronous ES and demonstrate it on Endless Terminals benchmark using Qwen2.5-7B-Instruct. Across three evaluation seeds, natural Async-1 matches synchronous ES, achieving 25.9\% versus 25.4\% held-out success. Controlled schedules that delay 10\% of each update cohort by four or eight policy upd

---

### [203] Multimodal Dual-Encoder Retrieval for Automated ICD Coding

**链接**: https://arxiv.org/abs/2610.04263
**作者**: Abhinav Bohra, Anuj Bohra
**来源**: cs.IR cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Accurate International Classification of Diseases (ICD) coding is crucial for large-scale clinical research, documentation, and billing. There are three primary problems with current ICD prediction methods: (1) They are unable to comprehend multimodal patient data because they rely on either structured EHR data or unstructured clinical notes. (2) They also struggle with scalability to a larger amount of ICD codes (9K+ codes in ICD-9), as traditional classifiers need dense output layers and often do not generalize well to long tail rare diseases. (3) They lack transparency for clinical use. To address these challenges, this research proposes a two-stage framework that first retrieves ICD codes using a multimodal dual-encoder retrieval model, where structured and unstructured patient data are integrated through gated fusion. The second stage refines the top-k retrieved candidates with an LLM-based re-ranker that provides ranked codes with clinically relevant explanations. Our experiments

---

### [204] Groupwise Distortion Guarantees for Preference-Based Alignment

**链接**: https://arxiv.org/abs/2610.05450
**作者**: Jacob Brodkey and Roberto Tamez and Aaron Roth
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Preference-based alignment methods such as reinforcement learning from human feedback (RLHF) and Nash learning from human feedback (NLHF) aggregate pairwise preferences to learn an LLM policy, but a natural goal is maximizing social welfare (average cardinal utility), which comparisons alone need not identify. G\"olz, Haghtalab, and Yang (GHY) measure the gap by distortion: the worst-case ratio between the welfare of the best fixed lottery (distribution over responses) and of the learned lottery. They show NLHF is optimal when every user receives the same lottery. Account-based LLMs, however, have information about their users and can serve different lotteries to different people. We give an efficient algorithm, GLHF, that learns a single group-conditioned policy from one comparison per user. Under individual Bradley--Terry comparisons, GLHF asymptotically matches GHY's optimal population distortion bound simultaneously on every group in a prespecified, possibly overlapping collection,

---

### [205] Grammar-Guided Code Watermarking with Green Temperature

**链接**: https://arxiv.org/abs/2610.05323
**作者**: Hyundong Jin and Hyeseon An and Soohan Lim and Yo-Sub Han
**来源**: cs.CR cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model watermarking embeds detectable statistical signals during decoding, but the resulting changes to token probabilities can degrade generation quality. This trade-off is particularly important for code, where small changes in token selection can break syntax or alter program behavior. Existing code watermarking methods mitigate this risk through entropy-based insertion or syntax-aware token selection, but they do not directly construct the watermark over the set of continuations admitted by the current grammar state. We propose Grammar-Guided Code Watermarking with Green Temperature (GTCW), which integrates grammar-constrained decoding with probability-aware watermarking. At each decoding step, GTCW restricts the candidate set to grammar-admissible tokens and partitions this support into keyed green and red subsets. At eligible high-entropy positions, green temperature reweights the green tokens according to the model's relative preferences, strengthening the watermar

---

### [206] Trajectory-Derived Confidence for Reliable, Resource-Aware Clinical Text-to-SQL Agents

**链接**: https://arxiv.org/abs/2610.04156
**作者**: Mincheol Daniel Song, Joshua Ward, Jake Jung, Guang Cheng
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents for clinical text-to-SQL applications reason autonomously over multiple steps but cannot assess whether their own reasoning or outputs can be trusted. In high leverage applications such as healthcare, this presents a critical risk where system mistakes can be costly. These reliability failures are also resource failures: an incorrect reasoning trajectory spends computation budget on outputs that must be discarded. We introduce Sentinel, a trajectory-derived, classifier-based confidence layer that analyzes an agent's reasoning, code and database outputs to decide at three points whether to stop: refusing unanswerable questions before the agent runs, halting doomed trajectories mid-run, and withholding untrustworthy answers at delivery. Here, utilizing Chow's rule, we optimize decisions under the EHRSQL shared task's Reliability Score, which penalizes incorrect answers given a utility weighting, and find on the benchmark EHRSQL that Sentinel raises this score from +0.08 to +0.

---

### [207] Backdooring Sparse Autoencoders

**链接**: https://arxiv.org/abs/2610.06049
**作者**: Enrico Ahlers, Daniel Passon, Tobias Kiecker, Eik Reichmann and Lars Grunske
**来源**: cs.CR cs.AI cs.CL cs.SE
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Sparse autoencoders (SAEs) are increasingly used not only to interpret language models but also to intervene on their internal representations. We show that this creates a supply-chain attack surface: a maliciously modified SAE can induce attacker-chosen behavior when inserted into the forward pass of an otherwise unchanged language model. We introduce a decoder-only SAE backdoor that leaves both the underlying LLM and the SAE encoder frozen, restricting the attack to a single auxiliary component at a single insertion layer. Using code generation as a case study, we demonstrate high rates of unsolicited code insertion across three language models and a wide range of insertion layers, as well as trigger-dependent behavior conditioned on a prompt cue. We further evaluate the modified SAEs using HumanEval and selected SAEBench metrics. While attack effectiveness varies across models and layers, strong backdoor behavior can coexist with relatively small changes in several conventional SAE 

---

### [208] Reward Stealing Attack on Large Language Models

**链接**: https://arxiv.org/abs/2610.06670
**作者**: Jiaming Qian, Pengyang Zhou, Jiahe Xu, Chaochao Chen
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Adversarial attacks on Large Language Models (LLMs) aim to induce harmful content. However, existing methods suffer from high computational costs or strict model-pairing dependencies, limiting their scalability and transferability. We propose Reward Stealing Attack (ReSA), an adversarial attack framework that targets the latent safety reward underlying LLM alignment. ReSA employs maximum entropy inverse reinforcement learning to recover a proxy reward model solely from the aligned model's behavior. The extracted reward is then reversed at inference time to derive an adversarial policy, efficiently implemented via a reward-guided decoding mechanism. Experiments demonstrate that a single recovered reward generalizes across prompts and diverse models to reveal a fundamental alignment vulnerability, enabling ReSA to significantly outperform existing attacks in effectiveness and transferability. The code is available at https://github.com/GarminQ/ReSA.

---

### [209] $\mathrm{TRIZ}^{a}$: Guiding Agent Evolution from Pattern Recognition to Solution Invention

**链接**: https://arxiv.org/abs/2610.04555
**作者**: Wenyin Liu (1), Yiheng Huang (2), Kai Wang (3) ((1) Guangdong University of Technology, (2) Beijing University of Posts and Telecommunications, (3) Beijing Denglu Technology Ltd)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We propose $\mathrm{TRIZ}^{a}$ (TRIZ exponentiated by an agent), a general R\&D automation paradigm that combines TRIZ inventive theory with LLM-driven agent evolutionary search. TRIZ's 40 inventive principles and contradiction matrix provide structured, explainable directions for solution generation, replacing random or untyped mutation with theory-guided ideation. Functional information (FI), operationalized under a frozen reference contract, is combined with TRIZ Ideality to measure useful and harmful function on a commensurable information scale, while hard gates keep promotion distinct from metric improvement. We validate $\mathrm{TRIZ}^{a}$ in cybersecurity--an adversarial and rapidly evolving domain--on PowerDuck GOOSE, CICIoT2023, and CIC-DDoS2019. Under paired-rerun protocols with protocol fingerprinting and hard-gate validation, the legacy experiments yield absolute F1 improvements of $+2.88$, $+4.23$, and $+0.15$ percentage points, respectively. A completed 45-activity CICIo

---

### [210] Language Model Fingerprinting Requires Rethinking Watermark Teachers

**链接**: https://arxiv.org/abs/2610.04169
**作者**: Jeongyeon Hwang, Anshul Nasery, Sewoong Oh, Jungseul Ok
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM fingerprinting via watermark distillation embeds a statistical watermark signal into model weights, enabling model owners to identify their models behind black-box APIs. Revisiting a recent protocol, we find that its utility evaluation understates text quality degradation in open-ended generation, favoring overly strong watermark teachers. Weakening the watermark improves text quality but sacrifices detectability. To move beyond this trade-off, we rethink whether text watermarks designed for verifying generated text are suitable distillation teachers for model fingerprinting. Such watermarks are typically designed to remain detectable from an individual output, limiting how sparse the watermark signal can be. In contrast, fingerprint verification can aggregate signal across queries, making sparser watermark signals viable. This raises a key question: where should the sparse signal be placed? We analyze signal placement through token surprisal and show that, even at comparable water

---

### [211] Fusion is the New Mutation: Bandit-Guided Evolution on Workflow Graphs

**链接**: https://arxiv.org/abs/2610.05284
**作者**: Zhiwei Shang, Jiahang Sun, Mingrong Gong, Mingze Kong, Zikun Qu, Pingchen Lu 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Automated agentic workflow optimization relies on costly evaluations, making it essential to allocate a limited evaluation budget effectively. Multi-parent fusion can reuse designs from previously discovered workflows, but identifying promising parent combinations requires learning from limited fusion feedback. We introduce DAGO (Directed Acyclic Graph Optimization), a contextual-bandit-guided framework that learns which parent workflows to fuse under a limited evaluation budget. DAGO formulates each candidate parent combination as an arm, represented by pretrained embeddings of its constituent workflows' code and prompts. A diagonal LinUCB policy learns a shared reward model across arms and balances exploitation of arms with high predicted offspring quality against uncertainty-driven exploration. After an arm is selected, an LLM generates a child workflow through summary-guided fusion, and the child's validation score serves as the reward for updating the bandit. A shared directed acy

---

### [212] Playing social deduction games with reinforcement fine-tuned large language models

**链接**: https://arxiv.org/abs/2610.04261
**作者**: Lingzhe Zhang, Yunpeng Zhai, Tong Jia, Kening Zheng, Chiming Duan, Minghua He 等 (9 人)
**来源**: cs.CL cs.AI cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reinforcement fine-tuning (RFT) is increasingly used in applications where large language models (LLMs) interact with humans and other agents. Here we use social deduction games to study how RFT changes LLMs' social behaviour. We let fine-tuned and base LLM agents play hidden-role games that require hidden-state inference, social reading and vote steering. Our results show that LLM agents do not reliably acquire social-deduction ability by directly optimizing terminal win--loss outcomes, suggesting that final game results provide a sparse and noisy signal for socially interactive learning. However, RFT is particularly effective at improving social reading, including tasks that require agents to infer hidden roles from public discussion, update beliefs over time and predict other agents' future decisions. We further show that RFT can also improve social influence, including tasks that require agents to steer votes, team approvals and collective decisions, although these gains depend mor

---

### [213] EvoCast: Reliable Autonomous Research Agents for Iterative Forecasting Architecture Evolution

**链接**: https://arxiv.org/abs/2610.04517
**作者**: Kaipeng Xu, Xianli Yan, Yan Wang, Xiang Liu, Shan Liu
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Deep time-series forecasting models have rapidly diversified, yet adapting them to a specific task still requires extensive expert effort in model selection, mechanism diagnosis, architecture design, implementation, and evaluation. Existing AutoML methods are constrained by predefined search spaces, while general-purpose LLM research agents lack reliable control over experimental protocols and model promotion. We introduce EvoCast, a fully autonomous research-agent system for iterative forecasting architecture evolution. EvoCast first establishes and diagnoses a task-specific baseline through executed mechanism ablations, then generates evidence-grounded research directions from dataset characteristics, diagnostic results, prior rounds, and failure records. Its central design, cognition-authority separation, assigns open-ended hypothesis generation and code implementation to LLM agents, while deterministic program authorities control source-edit boundaries, canonical evaluation, and pr

---

### [214] Learning without Overwriting: A Theory of Self-Distillation and Supervised Fine-Tuning in Continual Reasoning

**链接**: https://arxiv.org/abs/2610.05200
**作者**: Shinichi Uemura, Taiji Suzuki
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> On-policy self-distillation (OPSD) of large language models (LLMs) has demonstrated the ability to improve reasoning capabilities while preserving previously acquired knowledge. Despite substantial empirical success, the dynamics of OPSD in continual reasoning remain incompletely understood. Modeling LLM reasoning as search over a directed acyclic graph, we provide a unified theoretical analysis of both the dynamics of post-training---OPSD and supervised fine-tuning (SFT) in continual learning---and the impact of pre-training on subsequent performance. Our findings establish three key insights with an optimization guarantee: (i) OPSD with hints from correct outputs enables continual learning without forgetting by sparse yet effective gradient descent updates induced by the hint structure. (ii) SFT on correct reasoning paths can lead to catastrophic forgetting due to dense updates along the training paths, which overwrite the information previously acquired. (iii) Diversity in pre-train

---

### [215] EnGRICH: Enhancing Generative Reward Modeling with Critiques from Humans

**链接**: https://arxiv.org/abs/2610.05370
**作者**: Xuancheng Li, Beining Wang, Haitao Li, Heng Wang, Yujia Zhou, Qingyi Pan 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Generative reward models (GRMs) are important for LLM optimization. Unlike scalar reward models, GRMs generate natural-language critiques alongside preference judgments, providing finer-grained evaluation signals. Their effectiveness depends heavily on critique reliability. However, existing GRM training typically uses final preference correctness as outcome supervision. Because the preference outcome space is highly constrained, unreliable critiques can still yield correct outcomes and thus be reinforced. Recent work leverages human critiques for process supervision, but such critiques are scarce and are often reduced to scalar rewards, leaving their fine-grained evaluative information underutilized. We argue that evaluative criteria learned from human critiques can be generalized to broader outcome-only preference data. To this end, we propose \textbf{EnGRICH}, a GRM training framework that pairs the GRM with a training-time MetaCritic learned from a small set of human critiques. Met

---

### [216] templar: agentic induction and evolution of standardized radiology reporting templates from large-scale clinical corpora

**链接**: https://arxiv.org/abs/2610.05247
**作者**: Xiaotian Hu, Mingxuan Liu, Zhonghan Wang, Xinfeng Zhang, Yiming Huang, Ziang Wang 等 (10 人)
**来源**: cs.MA cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Structured radiology reporting mitigates the heterogeneity of free-text reports, yet its benefits depend on high-quality reporting templates. In practice, such templates are conventionally built through labor-intensive expert consensus and therefore vary across institutions and lag behind evolving clinical practice. Large language models (LLMs) enable automated template induction, but existing approaches remain limited: single-LLM induction is constrained by context length, and the corpus-scale method ASTAR produces a static, closed-corpus template without external grounding or downstream adaptation. To address these limitations, we propose TEMPLAR, a TEMPLate-centric Agentic framework for inducing and evolving standardized Radiology reporting templates from large-scale clinical corpora. TEMPLAR treats the template as a persistent central state maintained alongside two provenance-aware knowledge graphs, namely an anatomical graph that constrains template construction and a diagnostic g

---

### [217] SpatialChain: A Benchmark for Auditing Spatial Reasoning Faithfulness in VLMs

**链接**: https://arxiv.org/abs/2610.06413
**作者**: Rafael Teixeira Sousa, Vin\'icius Paulo Lopes de Oliveira, Elisa Ayumi Masasi de Oliveira, Luiza Martins de Freitas Cintra, Fernanda Bufon F\"arber, Igor Dias Aguiar 等 (8 人)
**来源**: cs.CV cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Thinking-enabled vision-language models (VLMs) report ever-higher accuracy on spatial benchmarks, yet final-answer scores cannot reveal whether a correct prediction reflects faithful spatial reasoning or a linguistic shortcut. We introduce SpatialChain, a dataset of 28,350 training and 899 test examples pairing spatially-oriented GQA questions with scene-graph-grounded reasoning chains, retained only when the generated answer matches the symbolic ground truth, and a two-axis evaluation combining objective chain-overlap metrics with a scene-graph-aware LLM judge that scores faithfulness and completeness independently of the final answer. Applied to nine thinking-enabled VLMs, the protocol surfaces three findings invisible to standard accuracy: (i) four of nine models achieve $\geq$79% VQA accuracy while exhibiting shortcut rates above 39%, i.e., correct answers whose reasoning the judge marks as unfaithful; (ii) chain quality significantly predicts answer correctness for seven of nine m

---

### [218] SkillScriptBench: Benchmarking Self-Evolution of Executable Agent Skill Packages Beyond Markdown

**链接**: https://arxiv.org/abs/2610.04008
**作者**: Yuxuan Liu, Haoran Li, Yuhao Zhang, Jiahe Guo, Hongyu Luo, Wenbin Hu 等 (10 人)
**来源**: cs.AI cs.LG cs.SE
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Executable Agent Skills combine natural-language instructions and scripts into reusable packages for LLM agents, and revising them requires fixing errors without breaking correct behavior. Existing benchmarks do not systematically distinguish documentation repair, script repair, and preservation when evaluating skill self-evolution. We introduce SkillScriptBench, a 350-task benchmark designed to evaluate these capabilities separately. From a survey of over 35,000 GitHub-hosted Skill roots, we select 100 packages and construct 150 repair tasks. Each task pairs a package containing injected script faults with a maintenance request and executable checks of the required behavior. A complementary controlled track contains 200 tasks from 50 packages, each evaluated under the same maintenance request in four states: clean, documentation faults, script faults, and faults in both. Across four LLMs, methods that edit both documentation and scripts can repair script faults but do not consistently

---

### [219] Causally Fair Generation with Large Language Models

**链接**: https://arxiv.org/abs/2610.04444
**作者**: Patrik Okanovic and Torsten Hoefler and Drago Plecko
**来源**: cs.AI cs.LG stat.ML
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly used to generate, complete, and transform information in settings where their outputs can shape consequential decisions, raising concerns about their impact on demographic disparities. In this context, causal inference provides a principled basis for assessing fairness, because it attributes observed disparities to the mechanisms that generated them, which a purely statistical approach cannot do even with infinite data. In LLM generation, a query may request several causally related variables, each of which is both an outcome of interest and a possible cause of other outputs, and the information supplied in the prompt need not follow a topological or a temporal order. This calls for methods that can analyze and selectively remove disparities from such a flexible generation process. In this paper we introduce Causally Fair Generation with LLMs (CFG, for short). CFG extracts relevant concepts, grounds generation in a reference population and 

---

### [220] Lend Me Your Eyes: Instruction-Aware Text Embeddings via Attention Relay

**链接**: https://arxiv.org/abs/2610.05564
**作者**: Yiyuan Luo, Vaggos Chatziafratis
**来源**: cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Text embedding models trained with contrastive learning learn to follow task instructions from instruction-paired data, while instruction-tuned LLMs already know how to follow them. We show that this instruction-following ability can carry over from an LLM to a Transformer-based embedder without any training. We propose Attention Relay, which passes the attention weights an LLM produces to the embedder's own attention. Across six instruction-tuned LLMs from the Qwen3, Llama 3.1 and OLMo 3 families and ten widely used embedding models that differ in tokenizer, size and pooling type, Attention Relay makes nearly every combination instruction-aware. Experiments that break the method down into its parts show that the LLM's attention weights track the instruction in its later layers and come largely from instruction tuning. They also show that relaying these weights selects which content in the text matters: it makes the aspect of the text that the instruction asks about dominant in the emb

---

### [221] SALUS: Automated Auditing of NL-to-SQL Benchmarks through Weak Supervision of Multi-Agent Output

**链接**: https://arxiv.org/abs/2610.05540
**作者**: Shiyuan Zhou, Ashwin Gerard Colaco, Sainyam Galhotra, Sharad Mehrotra
**来源**: cs.DB cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Natural language to SQL (NL-to-SQL) benchmarks are foundational to progress in data analysis research, yet recent work has shown that widely-used benchmarks contain significant annotation errors. These errors silently corrupt evaluation metrics, penalize correct model output, and distort the field's understanding of state-of-the-art performance. We present SALUS, a system that automatically detects annotation errors in NL-to-SQL benchmarks. SALUS frames benchmark auditing as a weakly supervised error detection: SQL generated by multiple LLM agents drive a suite of complementary weak-labeling functions. By passing this noisy vote matrix through a generative label model, we extract high-confidence training samples without requiring human ground truth. These samples train a decision plane that maps gold SQL query features to per-agent trustworthiness, allowing SALUS to intelligently fuse reliability estimates with raw verdicts for rigorous benchmark error detection. We evaluate on BIRD-Cl

---

### [222] Anticipating the Consequences of Curriculum Decisions with Large Language Models

**链接**: https://arxiv.org/abs/2610.04604
**作者**: Octavio Pappalardo, Nathan Herr, Tim Rockt\"aschel
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Automatic curriculum learning can improve the effectiveness of reinforcement learning by selecting the training experiences presented to the agent over time. Predicting the consequences of such decisions can, however, be difficult. We analyze automatic curriculum learning as a sequential decision-making problem, highlighting a gap between the quantities that determine the value of curriculum decisions and the information captured by local learning signals commonly used to guide them. We then investigate whether Large Language Models (LLMs) can exploit richer information about the learning problem to better anticipate the consequences of curriculum decisions. We introduce a method that combines online learning-progress estimates with LLM-informed estimates of (i) the potential downstream benefits of learning on each task and (ii) whether direct training on a task is currently likely to produce progress. We evaluate the approach on a custom benchmark of 256 textual goals in Craftax under

---

### [223] Where Did the Repair First Go Wrong? Localizing the Origins of Silent Failures in Agentic Vulnerability Repair

**链接**: https://arxiv.org/abs/2610.06163
**作者**: Wenji Bai, Muhammad Waseem, Zeeshan Rasheed, Jaakko Peltonen, Pekka Abrahamsson
**来源**: cs.CR cs.AI cs.SE
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Localizing where an LLM-based agent first fails to uphold security during a repair can show which stage of its workflow needs an additional safeguard. This is difficult for silent failures, which are patches that pass syntactic and functional checks but still contain a security vulnerability. Because such patches give no observable failure signal, existing failure attribution methods, which rely on observed task failures and labelled failure steps, are less suited to them. We propose Security Awareness Gap Evaluation (SAGE), a trace-based method that combines an assessment of the security reasoning recorded at each turn with the reconstructed code history to identify the earliest turn at which a repair diverges from the task's security intent. We evaluate SAGE on 95 confirmed silent failures drawn from 3,684 repair traces produced by six agent frameworks and six base models on SecurityEval and CVEfixes. SAGE assigned an origin in 93 cases. Most origins were an unaddressed security requ

---

### [224] Functionally Equivalent or Not? Graph-Grounded Differential Surrogate Execution for Code Equivalence

**链接**: https://arxiv.org/abs/2610.04371
**作者**: Amit Kachroo, Like Hui, Haitao Mao, Yuhao Zhang, Nguyen Vo
**来源**: cs.AI cs.SE
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Determining whether two programs are functionally equivalent is central to code modernization, patch validation, refactoring, and code-generation evaluation. Yet the usual signals are incomplete: tests cover only finite inputs, textual similarity confuses implementation with behavior, and unconstrained LLM judgments are difficult to audit. Direct execution is often impossible when a program depends on an obsolete, licensed, unavailable, or unsafe environment. We introduce FEAgent, a selective equivalence assessor agent that combines typed program-graph evidence with differential surrogate execution. FEAgent first aligns public interfaces and behaviorally relevant graph anchors, then issues bounded queries over call-flow, control-flow, data-flow, type, import, and effect relations. Next, a branch-aware generator agent proposes discriminating inputs, and two blinded LLM surrogates independently predict source and target observables. Every claim and predicted divergence is recorded in an 

---

### [225] Auditing Pairwise Equivalence Judgments: Self-Critique Effects and Diversity Measurement in Multi-Agent Hypothesis Generation

**链接**: https://arxiv.org/abs/2610.04133
**作者**: Ji Young Byun, Anthony Hu, Jesse Rogers, Roujia Wang, Manasa Kesapragada, Falgun Shah
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-agent systems built on large language models (LLMs) are increasingly applied to scientific discovery and hypothesis generation. Both the effect of refinement and the diversity of the delivered set are hard to interpret before experimental ground truth exists, and both are typically reported by deciding whether pairs of generated hypotheses describe the same underlying mechanism. We study two evaluation questions that rest on this pairwise equivalence judgment: (1) how much self-critique changes delivered hypotheses beyond run-to-run variability, and (2) how the equivalence rule used to group hypotheses affects measured diversity. Across four proprietary instances, we hold opening hypotheses fixed, rerun the downstream workflow with 0, 1, and 5 critique rounds, and score matched hypothesis pairs with an LLM-as-a-judge. Relative to matched same-depth reruns, moving from 0 to 1 round produces 34.5 percentage points (pp) of additional mechanism-level divergence, whereas 1 to 5 rounds

---

### [226] AI Safety via Debate is Compromised by Cognitive Biases

**链接**: https://arxiv.org/abs/2610.05461
**作者**: Gefei Liu, Sonya Rashkovan, Sophia Lloyd George, Isaac Sheidlower, Serena Booth
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reinforcement learning from human feedback (RLHF) has played a central role in making large language models responsive to human instructions. However, human evaluators often favor flattering or persuasive responses over truthful ones, creating incentives for models to appeal to evaluators at the expense of accuracy. AI safety via debate has been proposed as a way to improve the supervision of language models: in this paradigm, two agents argue opposing positions and challenge each other's claims, potentially exposing falsehoods to the adjudicator. A central premise of AI safety via debate is that truthful arguments are easier to defend than false ones under adversarial scrutiny. In this work, we investigate whether this advantage persists when debaters use rhetorical strategies that exploit biases in human judgment. Inspired by competitive debate, we construct 68 LLM-generated dialogues about detective mysteries with known culprits, spanning four interventions: anchoring, fallacy overs

---

### [227] Evolving in Thought Space: Training a Small Model at Test Time Unlocks Better Discoveries

**链接**: https://arxiv.org/abs/2610.06269
**作者**: Chonghe Jiang, Ao Qu, Siyuan Liu, Ruoyun Ma, Zijian Zhou, Dingyi Zhuang 等 (10 人)
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Open-ended scientific discovery often requires repeatedly proposing and evaluating candidate solutions. LLM-based systems can support this process by generating and refining executable solutions from verifier feedback. Methods such as TTT-Discover use test-time training (TTT) to update the solution-generating LLM from verifier feedback, adapting its generation policy to improve subsequent proposals on the target problem. However, this becomes expensive when reliable execution requires a large model, since training must maintain gradients, optimizer states, and policy statistics while repeatedly generating long, structured outputs. It also complicates credit assignment: outcome-level verifier feedback must jointly evaluate the high-level strategy and its low-level implementation. In this work, we introduce Guidance-TTT, which separates these roles. A compact guidance model is trained at test time to propose high-level strategic changes, while a frozen execution model implements them as 

---

### [228] Causal Improvement Graph for Agentic Harness Optimization

**链接**: https://arxiv.org/abs/2610.05039
**作者**: Junjie Zhang, Shunyu Liu, Haoyu Wang, Ting-En Lin, Yongbin Li, Dacheng Tao
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Agentic Harness is the runtime that constructs task context and controls execution flow, thereby shaping overall agent performance. Given a fixed model and external evaluation, automated Harness optimization seeks to improve this runtime through an iterative proposal--evaluation loop to better solve target tasks. Existing meta-harness methods mainly adopt proposer-centric discovery, in which an LLM-based proposer integrates accumulated experimental findings to determine subsequent Harness revisions. This places the burden of maintaining the evolving improvement state on the proposer as history expands and its underlying experimental logic becomes harder to discern. In this paper, we introduce the Causal Improvement Graph (CIG), a graph-governed meta-harness framework that externalizes the evolving improvement state in a persistent graph, allowing prior findings to directly govern subsequent Harness optimization through local proposer operations. CIG grows and links Evidence, Hypothesis

---

### [229] Label Agreement Does Not Measure Authorization

**链接**: https://arxiv.org/abs/2610.04544
**作者**: Amir Sabbaghziarani, Bradley Thomas Baker, Theodore J. LaGrow, Sergey Plis
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Many groups now delegate label ontology and metadata harmonization to agentic LLM pipelines. We built one and audited it. Our aggregate scores looked healthy, but the pipeline kept failing in ways they did not show, so we set out to find what they hid. Label agreement asks whether a proposed label matches a reference. It does not ask whether the agent was entitled to propose it, whether the output was complete enough to act on, or whether the label moved when the evidence moved. We measured those three separately on COBRE and FBIRN, two schizophrenia and control neuroimaging cohorts from different consortia, and they come apart, from label agreement and from each other. Showing the agent an upstream proposal barely moves label agreement, 0.857 to 0.870, while agreement on the chosen action doubles, 0.409 to 0.830. Output that parses as JSON still drops a required field on 10% of one model's cases and 33% of the other's. And an agent that replays its first answer scores perfectly on ori

---

### [230] Beware EviLLM: Enabling Vulnerability Injection via Large Language Models

**链接**: https://arxiv.org/abs/2610.03857
**作者**: Zeezoo Ryu, Simon Chung, Muhammad Faraz Karim, Anna Raymaker, Karan Singh Jodha, Yash Chaturvedi 等 (7 人)
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Advances in large language models (LLMs) have enabled AI-driven code generation from natural language specifications, introducing new attack surfaces for injecting vulnerabilities into software. Prior work has studied this problem only in benign settings where vulnerabilities are introduced inadvertently, or under unconventional threat models where the LLM itself is malicious (backdooring) or the user is the attacker (jailbreaking). In this paper, we study a more realistic threat model: a third-party adversary, with capabilities comparable to existing cybercriminals, compromises the AI code generation pipeline to deliberately introduce vulnerabilities. We call this the EviLLM attack. We have implemented two instances of EviLLM, each of which only requires the underlying LLM to be accessed through a compromised account or browser, and can inject vulnerabilities from 13 CWE classes. As we show in our feasibility study, both attack vectors are already used to implement many existing cyber

---

### [231] Bayes-Sufficient Compression Is Not Enough: How Does Communication Help Multi-Agent Systems?

**链接**: https://arxiv.org/abs/2610.03769
**作者**: Yi Xie, Zhanke Zhou, Yi Fan, Yong Ge, Bo Han, Bo Liu
**来源**: cs.LG cs.IT cs.MA math.IT
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-agent LLM systems pair a sender with broad context and an executor with a limited local view. We study when a short message improves the executor's next decision, when raw context is preferable, and when a stronger sender helps. Our framework, \emph{receiver-relative bounded coordination}, expresses message utility as receiver gain minus protocol tax. Compression beats raw context when tax savings exceed losses from omitted information and decoder mismatch. Even \emph{Bayes-sufficient} compression can fail when a bounded executor cannot use its surface form. A three-stage decomposition separates externalization, absorption, and \emph{action closure}, explaining how errors remain after the correct content reaches the receiver. Under a single-crossing condition, sender upgrades help above a receiver-burden threshold. Across six benchmarks, the same Qwen protocol raises ContextBench joint accuracy from $0.633$ to $0.775$ but lowers ToolSandbox from $0.889$ to $0.653$. Fixed-message 

---

### [232] Discovered, Not Designed: Population Evolution for Collaborative and Compute-Intensive Model Discovery

**链接**: https://arxiv.org/abs/2610.05950
**作者**: Bo Peng, Lizhu Zhang, Yuhang Zhou, Mingyi Wang, Yifan Wu, Serena Li 等 (8 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-driven evolution enables iterative model development, but two practical goals remain underexplored: finding model designs that transfer across related tasks and sustaining improvement when training is expensive. We introduce Population Evolution (PE), a collaborative, hierarchical framework that connects ongoing local searches through shared experimental evidence. PE evaluates code changes across related training instances and shares the results to guide subsequent proposals and promotion to larger training scales. For expensive targets, PE searches small training subsets and screens candidates through peer and intermediate evaluations before full-target training. We introduce RMD-Bench to evaluate both settings across ranking, watch-time prediction, RL algorithm discovery, and LLM/VLM pretraining. Compared with standalone evolution at matched source iterations, PE raises mean best local gains from 7.01% to 8.97% in ranking and from 2.84% to 3.85% in watch-time, while improving the

---

### [233] AgentPrivArena: Evaluating and Auditing Real-world AI Agent Privacy

**链接**: https://arxiv.org/abs/2610.06454
**作者**: Shouju Wang, Haopeng Zhang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The rapid advancement of LLM agents has enabled systems to autonomously perform complex tasks through external tools, but their growing access to personal data introduces significant privacy risks. Existing benchmarks primarily evaluate LLM agent privacy through simulated trajectories and outcome-based metrics, limiting their ability to capture privacy risks arising during multi-step agent execution. In this work, we introduce AgentPrivArena, a framework for evaluating privacy risks in realistic LLM agent workflows. AgentPrivArena integrates authentic MCP tools and self-hosted services within a reproducible execution environment. We further propose trajectory-level privacy metrics that quantify unnecessary information access beyond final response leakage. Building on this framework, we introduce AgentPrivAudit, a runtime auditing approach for monitoring privacy violations during agent execution. Extensive experiments on state-of-the-art LLM agents reveal substantial privacy risks overl

---

### [234] Usage-Modulated Sentiment Representations in Large Language Models

**链接**: https://arxiv.org/abs/2610.05069
**作者**: Hongfei Du, Jiacheng Shi, Yanfu Zhang, Gang Zhou, Ye Gao
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Prior work suggests that sentiment can often be captured by approximately linear directions in LLM activation spaces, but a single direction may not fully capture sentiment representations. In natural communication, sentiment is shaped not only by polarity but also by usage factors, such as tone and audience adaptation. We test whether these factors systematically modulate sentiment representations beyond a shared sentiment direction. We construct a controlled paired dataset that holds event content fixed while varying sentiment polarity and usage factors, and analyze Llama, Mistral, and Gemma. We identify a shared sentiment direction, remove it, and test the residual structure through erasure and generation-time tone steering. Across models, the shared direction is robust (median cosine 0.953-0.975), yet removing it leaves 0.833-0.909 of the original positive-negative representation-difference norm. The residuals contain compact, reproducible usage-conditioned structure. Targeted eras

---

### [235] Sycophancy Through a Five-Level AI Response Validation Framework

**链接**: https://arxiv.org/abs/2610.03731
**作者**: Dian Yu and Pei-Luen Patrick Rau
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> AI sycophancy, the tendency of AI systems to excessively agree with, flatter, or validate users, is an emerging concern in human-AI interaction. It is especially consequential in problem-sharing contexts, where users may seek both information and emotional validation. This paper conceptualizes AI sycophancy as excessive response validation and introduces a five-level AI Response Validation Framework (ARVF), measured using a six-item Perceived AI Sycophancy Scale (PASS). Across three phases, the study validated the framework with human participants through an online questionnaire, tested LLM-as-evaluators in answering PASS, and examined how ten contemporary LLMs generated and evaluated responses to real-world work and personal conflict scenarios. Results supported the intended progression of perceived sycophancy in ARVF and the reliability of PASS. Trust and perceived competence followed an inverted U-shaped pattern. LLM ratings reproduced the five-level structure but showed calibration

---

### [236] TrajLong: Co-Designing Agentic and Long-Context Supervision for Mid-Training

**链接**: https://arxiv.org/abs/2610.04973
**作者**: Miao Peng, Qintong Zhang, Nuo Chen, Yuhan Li, Guochen Yan, Xinran Gu 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents for coding, search, and workplace tasks increasingly rely on long-context capabilities to effectively aggregate and reason over extended interaction histories. Recent work has incorporated agent trajectories into mid-training stage, drawing on their naturally long and interaction-rich structure. Yet how to organize the information within these trajectories into effective mid-training supervision remains underexplored. In this work, we investigate the relationship between long-context and agent atomic capabilities and introduce TrajLong, a novel framework that compiles trajectories into long-context training tasks with dense supervision, targeting three representative atomic capabilities: evidence grounding, cross-evidence aggregation, and temporal state maintenance. We mid-train Qwen3-14B-Base and Qwen3-30B-A3B-Base with data compiled by TrajLong, followed by supervised fine-tuning. Experiments on 6 long-context and 12 agent benchmarks demonstrate broad performance gains, wi

---

### [237] Belief-Trajectory Energy: Measuring the Path to a Prediction

**链接**: https://arxiv.org/abs/2610.05114
**作者**: Jiahao Ying, Wei Tang, Boxian Ai, Yaoning Wang, Haotian Chen, Wenhe Sun 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) progressively revise their predictions across Transformer layers, yet we typically observe only the final output, discarding the trajectory through which it is formed. We introduce Belief-Trajectory Energy(BTE), a model-grounded measure that characterizes an input through the layerwise predictive revisions it induces in a model. By mapping intermediate states into a shared predictive space, BTE provides a principled measure of belief change that can be summarized as either a scalar or a structured depth profile. Theoretically, we show that local BTE corresponds to predictive revision under the Fisher-Rao geometry, while the sequence of revisions captures information beyond the initial-to-final belief change. Empirically, scalar BTE provides a model-relative signal of difficulty across diverse reasoning tasks, while richer BTE representations support human-LLM review detection and fine-grained generator attribution, reaching up to $0.998$ macro-AUROC and $95

---

### [238] Complex Agents, Shallow Tests: Demystifying and Enhancing Test Adequacy of Agent Harness in the Wild

**链接**: https://arxiv.org/abs/2610.04921
**作者**: Yifan Xiong, Jingyi Ge, Zhenpeng Chen, Yiling Lou
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based agentic systems are emerging as a new software paradigm. Modern agents are typically composed of backbone LLMs and a surrounding harness that serves as the operational software infrastructure for agent execution. As agent harnesses grow increasingly complex, agents suffer from diverse harness implementation bugs, raising substantial reliability concerns. In this work, we conduct the first empirical study to systematically investigate the test adequacy of harness in real-world agentic systems. Our analysis reveals that agent harness remains substantially undertested. In particular, LLM-dependent harness (LDH) code, despite its critical role in processing LLM outputs and governing agent behavior, receives limited testing attention, with less than half of its lines and branches covered by existing tests. Motivated by these findings, we further propose HarnessTester, the first harness-oriented test generation technique that incorporates explicit agent-harness contract support to 

---

### [239] A Bird's-Eye View of Iterative Reward Design

**链接**: https://arxiv.org/abs/2610.04364
**作者**: Logan Mondal Bhamidipaty, Lauren Robson, Linda Petrini, Shengrui Lyu, Kamal Ndousse
**来源**: cs.LG cs.AI cs.RO
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Designing effective reward functions in RL typically requires substantial expertise and trial and error. Recent work automates this process with LLM-based systems that generate and iteratively improve reward code using policy feedback. However, these methods are often hard to compare because they differ in implementation details, feedback assumptions, and evaluation environments. To address this, we introduce a Benchmark for Iterative Reward Design (BIRD) that expresses existing methods in a unified configuration and evaluation space. This lets us compare algorithms directly, ablate individual design choices, and prototype new components under matched feedback conditions and policy-training budgets. Across MuJoCo, Meta-World, Assistax, and HumanoidBench, we identify a small set of simple design choices that consistently improve performance. Combining these choices yields significantly better performance than the evaluated methods from prior work. Our results highlight the strength of s

---

### [240] EVISKILL: Grounding Skill Evolution in Replayable Evidence

**链接**: https://arxiv.org/abs/2610.05030
**作者**: Yan Zhou, Yili Wang, Yiwei Dai, Qinggang Zhang, Xin Wang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Continual skill evolution enables LLM agents to accumulate and refine reusable procedural knowledge from interaction experience without updating model parameters. Its effectiveness depends on determining not only what to change, but also why a change is justified and when it should become persistent guidance. However, existing experience-driven methods can lose the behavioral evidence and task contexts supporting edits. Moreover, a global validation outcome provides an incomplete judgment of its constituent changes: locally supported corrections may be discarded with a rejected revision, while evidence may require further experience to inform useful updates. To this end, we introduce EVISKILL, an evidence-driven framework that organizes execution observations into Replayable Evidence Cards and synthesizes edits with explicit links to their supporting contexts. Targeted replay verifies these edits through re-execution and provides feedback for correction. Across epochs, EVISKILL preserv

---

### [241] Dynamic Harness Search: Building Multi-Agent Systems Per-Query via Prediction

**链接**: https://arxiv.org/abs/2610.04137
**作者**: Som Sagar, Shasha Li, Hejie Cui, Ransalu Senanayake, Sercan \"{O}. Ar{\i}k
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Agent harnesses specify the roles, instructions, tools, and communication structure used to solve a task, and the right harness depends on the query. Because the value of each design choice is observable only through execution, tailoring a harness to each query has required either executing alternatives at inference time or costly manual design. We introduce SHIFT, which moves execution out of the per-query search loop. A local LLM architect learns a policy over harness-building actions from search, and a value function that predicts, from measured executions, a utility balancing accuracy against execution cost. For each query, Monte Carlo tree search uses these predictions to construct a harness. Across 9,193 tasks in six benchmarks, from math to document and general-assistant tasks, with a Gemini 3.5 Flash executor, SHIFT attains the highest mean accuracy, about 80%, outperforming 17 baselines that span prompting, prompt optimization, and workflow search, and exceeding the strongest 

---

### [242] PhaseGate: Phase-Aware CPU Retrieval Scheduling for On-Device LLMs on Unified Memory

**链接**: https://arxiv.org/abs/2610.04537
**作者**: Seoyoon Yum, Sehoon Kim
**来源**: cs.LG cs.DC cs.PF
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> On-device assistants run GPU-based LLM inference alongside CPU retrieval on unified-memory systems. Under a saturated local-retrieval workload, four concurrent retrieval workers raise 95th-percentile (p95) decode latency by 60-61% on two M4 systems, whereas prefill latency rises by only 5.7-6.9%. We study LLM phase as an admission signal for independent CPU retrieval under controlled LLM workloads. PHASEGATE calibrates separate concurrency limits for prefill and decode, selecting four and one on our base-M4 configuration. Under a backlogged queue, it achieves 2.0 times the aggregate retrieval throughput of the best tested feasible fixed policy, with both p95 LLM latency metrics within 1.25 times their no-retrieval baselines in all seven held-out runs. A phase-blind control, TimeGate, uses the same two limits on a calibration-derived schedule without observing LLM phase. It achieves similar retrieval throughput but violates the output-token latency limit in every run. M2 and M2 Pro Mac 

---

### [243] Auditable Clinical Timeline Reconstruction with Provenance-Aware Evidence Graphs

**链接**: https://arxiv.org/abs/2610.06177
**作者**: Judith Jeyafreeda Andrew
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A patient-timeline reconstruction system is auditable only if it keeps the mentions behind each answer, records how facts were revised, and declines to answer when the evidence is not in the text. This study tests these three properties on a fully synthetic corpus (1,000 patients, 3,353 notes, 220 revision edges). Two provenance-aware Evidence Graph operators reduced the node-plus-edge count to 67% and 63% (77-78% of serialized size) while preserving every answer and mention link across 6,813 query points answerable by recency; a fixed-window baseline returned no value for 53.4% of points, unflagged. On evidence-unavailable controls that announce the omission, a BioClinicalBERT gate and a zero-shot LLM gate responded mainly to the announcement. On marker-free controls, BERT abstained on 0 of 81 notes while its accuracy fell from 93.8% to 59.3% across all three relation classes; the LLM's coverage fell from 75.6% to 27.7% on notes its own model family judged undeterminable. Against 482 

---

### [244] MedicalHarness: A Controlled Evaluation of LLMs and Agent Harnesses on Medical Tasks

**链接**: https://arxiv.org/abs/2610.05778
**作者**: Ziqing Wang, Lili Zhao, Kaize Ding
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents are increasingly built for medical work and scored on clinical benchmarks. Each such score, however, comes from a model running inside an agent harness, the system that controls the loop between the model and its environment. An agent's score is therefore a property of a model--harness pair. For medical agents, how much outcomes change with the harness has rarely been measured. Measuring this change, and explaining it, raises two challenges. First, a harness comparison must change nothing but the harness and be repeated across models and kinds of task. Second, comparing whole harnesses leaves their mechanisms bundled together, so it cannot show when an individual mechanism helps. To address these challenges, we present MedicalHarness, a controlled study of models and agent harnesses on medical tasks. We first build MedicalHarnessBench to evaluate agents on $107$ tasks across four domains that each test a different harness capability. Using this benchmark, we run five open-we

---

### [245] Continual Learning with Elastic Regularization and Synthetic Replay for Federated MLLM Fine-Tuning

**链接**: https://arxiv.org/abs/2607.12112
**作者**: Jing Liu, Chenxuanyin Zou, Jiayang Ren, Gaoyun Fang, Chengfang Li, Yan Wang 等 (8 人)
**来源**: cs.LG cs.AI cs.CV cs.DC
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [246] Image Synthesis as an Intermediate for Controllable Time Series Generation

**链接**: https://arxiv.org/abs/2610.05211
**作者**: Haochen Yuan, Jing Xie, Yunbo Wang
**来源**: cs.AI
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Semantic-driven time-series generation offers a promising way to improve downstream learning in few-shot forecasting, but directly generating numerical sequences from language often fails to preserve the intended temporal structure. We propose VisualBridge, which uses time-series plots as a visual intermediate to bridge high-level temporal semantics and numerical sequences. An MLLM first converts plotted series into structured semantic representations, enabling explicit control over temporal properties such as trend, seasonality, and volatility. We then learn a semantic editing policy with downstream forecasting rewards, allowing the generation process to favor temporal patterns that are beneficial for the target task. The resulting sequences are further modeled by a temporal VAE to produce consistent multivariate augmentations. Experiments on standard public forecasting benchmarks demonstrate that VisualBridge improves few-shot forecasting over conventional augmentation methods, with 

---

### [247] Harnessing Multimodal Large Language Models for Training-Free Human-Object Interaction Detection

**链接**: https://arxiv.org/abs/2610.06394
**作者**: Zhaolin Cai, Huiyu Duan, Liu Yang, Yanjun Qin, Bo Ai, Wei Chen 等 (8 人)
**来源**: cs.CV
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Human-object interaction (HOI) detection aims to localize human-object pairs and recognize their interactions. Traditional supervised methods perform strongly but rely on task-specific training. Recent multimodal large language models (MLLMs) offer a promising route to training-free HOI detection through their broad visual-semantic knowledge and versatile perceptual and reasoning capabilities. However, existing approaches largely invoke these capabilities through loosely coordinated inference stages. This fragmented execution restricts the role of interaction hypotheses in guiding visual exploration, leaving key participants overlooked and local ambiguities unresolved. Furthermore, propagating early semantic assumptions through subsequent visual grounding and relation prediction induces self-reinforcing semantic circularity. To resolve these challenges, we propose HarnessHOI, a training-free framework that transforms passive MLLM inference into an active interaction-centric harness. Sp

---

### [248] IRSTD-Agent: Agentic Infrared Small Target Detection via Zoom-Guided Interaction Learning

**链接**: https://arxiv.org/abs/2610.05342
**作者**: Jiawen Xi, Yu Zhang, Tianyi Zhao, Zhu Liu, Maoxun Yuan, Xingxing Wei
**来源**: cs.CV cs.AI
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Infrared small-target detection plays an important role in maritime monitoring and aerial surveillance. Although multimodal large language models (MLLMs) offer promising capabilities for visual understanding, existing MLLM-based approaches struggle to precisely localize infrared small targets. In this paper, we propose IRSTD-Agent, an agentic framework for infrared small target detection through dynamic visual search. The framework enables an MLLM to adaptively determine where and at what scale to inspect an image and progressively gather fine-grained visual evidence for precise target localization. Five complementary visual tools (PROPOSAL, ZOOM, DETECT, DROP and REFINE) support object candidate discovery, adaptive observation, target localization, hypothesis rejection, and target extent refinement, together enabling a coordinated search process over original-resolution images. To teach the MLLMs to conduct this search, we introduce Zoom-guided Interaction Learning, which uses annotat

---

### [249] Representation--Behavior Alignment for Explainable Weakly-Supervised Video Anomaly Detection

**链接**: https://arxiv.org/abs/2610.05129
**作者**: Chao Huang, Pengfei Wei, Kaige Li, Chengliang Liu, Wei Wang, Wenqi Ren 等 (7 人)
**来源**: cs.CV
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal Large Language Models (MLLMs) provide a natural way to make video anomaly detection more explainable. However, their final decisions do not always fully use the discriminative information contained in their hidden states, an issue we refer to as representation--behavior misalignment. We decompose this gap into a capacity component that measures discriminative information never aggregated into the readout position, and a directional component that measures the angular mismatch between the optimal and the native normal--abnormal axis at that position. Across multiple video anomaly detection benchmarks and MLLM backbones the directional component dominates, and residual-stream tracing shows that native-axis separability rises sharply in several mid-to-late attention layers. Because both components are governed by attention rather than MLP updates, we propose Representation--Behavior Alignment (RBA), a parameter-efficient method that adapts those layers using video-level labels 

---

### [250] Human-Like Attention? A Psychophysical Comparison of Visual Search in Humans and MLLMs

**链接**: https://arxiv.org/abs/2610.05463
**作者**: Renchi Zhang, Joost C. F. de Winter, Dimitra Dodou, Harleigh C. Seyffert, Yke Bauke Eisma
**来源**: cs.HC cs.AI cs.CV
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Visual search is a fundamental cognitive ability. This study investigates whether Multimodal Large Language Models (MLLMs) exhibit human-like difficulty signatures in visual search tasks. We compared search performance of humans (n = 1,250) and MLLMs using identical 2D and 3D stimuli across different set sizes. Both groups showed efficient performance in feature searches, most clearly when the target had a unique color, but performance degradation in conjunction searches as set sizes increased. Additionally, we found strong correlations between human and MLLM error rates ($\rho = 0.82$), which suggests that MLLMs are sensitive to similar objective complexities, such as stimulus heterogeneity. However, differences were found as well: whereas humans invested extra search time to respond accurately on target-absent trials, MLLMs exhibited extreme present/absent response biases in complex searches. We conclude that MLLMs replicate high-level human performance signatures, yet their underlyi

---

### [251] Lightweight Semantic EEG Foundation Model for Frozen Cross-Disorder Transfer

**链接**: https://arxiv.org/abs/2610.05503
**作者**: Rita Huan-Ting Peng and Nhat Bui
**来源**: cs.LG eess.SP q-bio.NC
**匹配关键词**: EEG, Foundation Models, EEG Foundation Model
**相关性评分**: 9.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large-scale EEG foundation models have demonstrated promising transferability across neurological disorders, but often require millions of parameters and substantial computational resources. In this paper, we present the Universal Semantic EEG Foundation Model (USE-FM), a lightweight EEG foundation model that learns transferable neural representations through self-supervised signal reconstruction on the Temple University Hospital EEG Corpus (TUEG). After pretraining, the encoder is frozen and evaluated on two clinically distinct downstream tasks, abnormal EEG detection (TUAB) and epileptic seizure recognition (TUEP), using a unified frozen-transfer protocol against recent EEG foundation models, including LUNA-Base and CBraMod. With only 1.46 million parameters, approximately one-fifth the size of existing models, USE-FM achieves competitive overall performance, including strong sensitivity and F1-score on TUEP (SEN $75.00 \pm 14.14$, F1 $70.37 \pm 4.01$), while maintaining competitive 

---

### [252] SPDAlign: Interpretable Riemannian Alignment for EEG Forward Modeling Shifts

**链接**: https://arxiv.org/abs/2610.06315
**作者**: Shanglin Li, Shiwen Chu, Okan Ko\c{c}, Chenyu Liu, Qibin Zhao, Motoaki Kawanabe 等 (8 人)
**来源**: cs.LG
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Electroencephalography (EEG) based brain-computer interfaces enable direct brain-to-device communication for applications such as rehabilitation and communication. However, their practical utility is often limited as the non-stationary nature of the EEG data introduces distribution shifts across domains (e.g., sessions and subjects). Adapting machine learning models to be invariant to these shifts in an unsupervised way, without using costly labeled calibration data, would drastically improve the utility of EEG data. In this work, we use a classic generative model of EEG to study distribution shifts introduced by the domain-specific forward process, which is associated with factors such as head geometry. We theoretically show that such distribution shifts can be recovered solely through linear transformations on the Symmetric Positive Definite manifold. Building on this insight, we propose SPDAlign, an interpretable framework for promoting domain-invariant EEG learning. SPDAlign first 

---

### [253] Schizophrenia Detection from EEG Signals: A Transformer Framework with Spectrogram Representation

**链接**: https://arxiv.org/abs/2609.14015
**作者**: Abtin Shafiei, Mohsen Hooshmand, Majid Ramezani
**来源**: cs.AI
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [254] Graph Learning for Cross-Subject, Cross-Population EEG Emotion Decoding and Model-Derived Spatial-Spectral Neural Signatures

**链接**: https://arxiv.org/abs/2609.22103
**作者**: Dongyi He, Bin Jiang, Xiangkai Wang, Yun Zhao, Hongjie Yan, Wai Ting Siok 等 (7 人)
**来源**: eess.SP cs.LG
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [255] Preference vs. Performance: EEG-Based Classification of Learner Engagement in Multimodal Instruction

**链接**: https://arxiv.org/abs/2610.05178
**作者**: Sri Jahnavi Adusumilli, Deepak Giri, Pallavi Vaswani, Pallavi Singh, Megha Moncy, Lalitha Pranathi Pulavarthy 等 (7 人)
**来源**: cs.HC cs.CY
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Effective adaptive instructional systems require robust measures of learner engagement that go beyond static user profiles. This study employs Multimodal Learning Analytics (MMLA) to investigate the relationship between self-reported instructional modality preferences and objective neurophysiological markers of engagement. Thirty-seven participants engaged with learning content delivered via varying modalities (visual, auditory, reading/writing, kinesthetic). We captured real-time neural activity using two EEG devices: the Emotiv EpocX (14 channels, 128 Hz) and OpenBCI (16 channels, 125 Hz). Preferences were assessed using the VARK questionnaire. Consistent with literature challenging the "meshing hypothesis," aligning instructional modality with stated preferences did not significantly predict performance gains. However, spectral analysis of EEG data revealed divergent engagement patterns: when content aligned with preferences, distinct neural activity patterns emerged in theta and al

---

### [256] Decoupling Time and Space: A Temporally Conditioned Refinement for EEG Source Imaging

**链接**: https://arxiv.org/abs/2610.06726
**作者**: Marco Morik, Jesse Palarus, Carmen Vidaurre, Klaus-Robert M\"uller, Shinichi Nakajima
**来源**: cs.LG
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Electroencephalography (EEG) offers millisecond temporal resolution, but inferring underlying neural sources is a severely ill-posed spatial inverse problem. While deep learning has advanced spatial reconstruction, current architectures face a critical dilemma: frame-by-frame models discard vital temporal context, whereas full 4D spatiotemporal networks introduce an architectural trade-off between reconstruction accuracy and inference cost. We propose a novel two-stream framework that explicitly decouples global temporal representation learning from per-time-point spatial refinement. A Transformer-based Temporal Condition Encoder processes the entire EEG sequence via factorized spatiotemporal attention, retaining sensor-resolved features. A fixed inverse then maps these features into source-indexed conditioning for a per-timestep Source-Space Transformer or volumetric convolutional refiner. Extensive evaluations on realistic synthetic data demonstrate that this temporal prior dramatica

---

### [257] EEGDM: Label-Efficient EEG Representation Learning with Generative Diffusion Model

**链接**: https://arxiv.org/abs/2508.14086
**作者**: Jia Hong Puah, Sim Kuan Goh, Ziwei Zhang, Zixuan Ye, Chow Khuen Chan, Kheng Seang Lim 等 (9 人)
**来源**: cs.LG
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [258] COVER: Learning to Accept More in Selective Sleep Staging

**链接**: https://arxiv.org/abs/2610.03911
**作者**: Yukai Song (1), Yangfan Deng (2), Jijun Yin (1), Zhi-Hong Mao (1), Jingtong Hu (1) ((1) Department of Electrical and Computer Engineering, University of Pittsburgh 等 (9 人)
**来源**: cs.LG
**匹配关键词**: EEG
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Traditional sleep-staging methods apply the same model to every EEG epoch. Such uniform deployment expends computation on epochs that a smaller model could handle reliably, motivating cascades in which a primary classifier accepts its reliable predictions and defers the remainder to a more capable model. In this paper, we study the first stage of such a cascade: maximizing the coverage of fixed primary predictions subject to a prescribed accepted-risk target. We propose COVER (COVerage-oriented Error Ranking), which integrates two key innovations: (i) auxiliary-informed primary-error learning, which replaces maximum softmax probability (MSP) with a learned error score while preserving the primary labels, and (ii) fixed-scale scorer refinement, which builds on this score to directly maximize coverage under an empirical accepted-risk constraint rather than error-prediction accuracy over all epochs. We evaluate COVER on Sleep-EDF-20 at a 5% accepted-risk target, with subjects held out fro

---

### [259] Scaling of Wireless Foundation Models via Representation Diversity and Multi-Branch Architectures

**链接**: https://arxiv.org/abs/2610.04289
**作者**: Ahmed Mohamed, Ahmed Aboulfotouh, and Hatem Abou-Zeid
**来源**: eess.SP cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Wireless foundation models learn representations from unlabeled radio signals for reuse across downstream tasks. Scaling model capacity is a common strategy for learning richer representations and improving downstream performance. However, its gains are less consistent in wireless self-supervised learning when pretraining data are limited. We investigate objective diversity as an alternative scaling axis: different self-supervised objectives emphasize different signal properties, and combining their representations can preserve more information to enable diverse tasks. We develop a fusion framework that combines frozen representations from independent encoders trained through reconstructive, predictive, and contrastive learning. This provides a reference for the benefits of diversity, but requires the maintenance of multiple encoders. To retain these benefits within the parameter budget of a standard single-objective encoder, we introduce a jointly trained multi-branch architecture wit

---

### [260] Medical foundation models converge less under label supervision

**链接**: https://arxiv.org/abs/2607.20274
**作者**: Soroosh Tayebi Arasteh, Sebastian Ziegelmayer, Mahshad Lotfinia, Lisa Adams, Sven Nebelung, Jakob Nikolas Kather 等 (7 人)
**来源**: cs.CV cs.AI cs.CL cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [261] LatentWave: JEPA Pretraining for Wireless Foundation Models

**链接**: https://arxiv.org/abs/2606.06373
**作者**: Ahmed Mohamed, Ahmed Aboulfotouh, and Hatem Abou-Zeid
**来源**: eess.SP cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [262] OpenPhone: Mobile Agentic Foundation Models

**链接**: https://arxiv.org/abs/2510.22009
**作者**: Yangqin Jiang and Chao Huang
**来源**: cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [263] Task Inference Beyond Least Squares in Behavioral Foundation Models

**链接**: https://arxiv.org/abs/2610.05350
**作者**: Kuan-Hsun Tu, Chien-Sheng Chiang, Hsin-Wei Chen, Ping-Chun Hsieh, Tsung-Wei Ke
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Behavioral Foundation Models (BFMs) aim to solve a wide range of downstream tasks without test-time policy learning by inferring a task vector from the reward function. While efficient, the retrieved policies are often suboptimal because of how this task vector is inferred, typically with ordinary least squares (OLS). OLS minimizes reward reconstruction error but leaves the ordering of rewards unconstrained, which can bias the successor measure of the retrieved zero-shot policy away from that of the optimal policy. In this work, we propose BLS, an efficient test-time inference method that balances minimizing reward reconstruction error with reducing successor-measure mismatch. Theoretically, we provide a suboptimality gap upper bound characterized by both successor-measure and reward-function residuals. Empirically, we evaluate BLS on top of state-of-the-art BFMs across benchmarks for locomotion, manipulation, and humanoid control. BLS outperforms existing task inference baselines with

---

### [264] Transferable Adversarial Robustness for Speech Foundation Models via Hierarchical Stabilization

**链接**: https://arxiv.org/abs/2610.05310
**作者**: Aref Mousavi, Shahab Sherafat, Kiarash Kiani Feriz, Amirparsa Safari, Raoof Zare Moayedi, Mohammad Hossein Rohban 等 (7 人)
**来源**: eess.AS cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Frozen speech foundation models (SFMs) make downstream adaptation efficient: the backbone can stay fixed while a task learns layer fusion and a lightweight classifier. Full adversarial fine-tuning is a standard route to robustness, but generating adversarial examples and updating the backbone for every task sacrifices that efficiency. We ask whether robustness can instead be learned before future tasks are known. For a frozen backbone and linear classifier, robustness can be understood through the interaction between representation stability and decision-boundary margin. This leads directly to our design: we stabilize representations across the hidden layers, rather than only the final layer, while preserving clean representations; after clean adaptation selects the layer mixture, we keep it fixed and enlarge only the classifier margin, without downstream adversarial examples. We evaluate Wav2Vec2, HuBERT, and WavLM Large on four tasks under adaptive 30 dB attacks. Across 12 backbone-t

---

### [265] Label-Free Coreset Selection with Foundation Models for Efficient Annotation in Computational Pathology

**链接**: https://arxiv.org/abs/2610.05987
**作者**: Tuo Yin, Jennifer Dhont
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Computational pathology has the potential to improve clinical outcomes through a demonstrated increase in diagnostic and prognostic accuracy. However, the development and validation of deep learning algorithms still require annotated data, a costly procedure involving expert pathologists who already face critical workforce shortages. Existing coreset selection methods to optimize annotation efforts currently all rely on hyperparameters tuned on natural-image benchmarks that do not transfer to histopathology and are cumbersome to use in clinical practice. In this study, we present GCcore, a novel label-free coreset selection method that embeds every image of a dataset with any pathology foundation model and greedily selects the samples that collectively maximize the global coverage of the embedding space. The proposed method provides a lower-bound guarantee on the global coverage of the returned coreset for any coreset size, while being completely hyperparameter-free and deterministic. 

---

### [266] FairRSFM: A Biome-Aware Benchmark and Debiasing Framework for Remote Sensing Foundation Models

**链接**: https://arxiv.org/abs/2610.05790
**作者**: Md Aminur Hossain, Omkumar Vaghasiya, Rajeev Ranjan Dwivedi, Vinod Kurmi, and Biplab Banerjee
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Remote sensing foundation models (RSFMs) are commonly evaluated using aggregate metrics, which can hide systematic performance disparities across ecological regions. We introduce FairRSFM, a biome-aware benchmark for evaluating ecological group robustness in RSFMs. FairRSFM maps georeferenced samples from 14 terrestrial biome classes into six ecologically meaningful macro-groups and evaluates models under a unified frozen-backbone evaluation protocol. The benchmark covers four downstream datasets: m-EuroSAT, m-BigEarthNet, m-SA-Crop-Type, and MMEarth20K with Dynamic World label maps. Using Prithvi-EO-2.0, SatMAE, and DOFA across three random seeds, we show that aggregate performance consistently masks biome-dependent disparities across architectures and tasks. For example, Prithvi-EO-2.0 reaches 90.98% overall macro-F1 on m-EuroSAT but a mean worst-group score of only 83.72%, while m-SA-Crop-Type drops from 27.30% overall mIoU to 18.47% in the Xeric and Mineralogical group. We further 

---

### [267] Normality Constraint Learning: Adapting Foundation Models for Time Series Anomaly Detection

**链接**: https://arxiv.org/abs/2610.06453
**作者**: Xiaohui Zhou, Yijie Wang, Hongzuo Xu, Weixuan Liang, Guansong Pang
**来源**: cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Time Series Foundation Models (TSFMs) achieve strong generalization by learning to reconstruct or forecast broad temporal patterns from large-scale time series during pre-training. Yet this strength can become a weakness for anomaly detection: TSFMs may model rare anomalous patterns as effectively as normal ones, allowing anomalies to be accurately reconstructed or forecasted and thus diminishing their reconstruction/forecasting error-based anomaly scores. This paper proposes $\underline{\textbf{N}}$$\textbf{ormality}$ $\underline{\textbf{C}}$$\textbf{onstraint}$ $\underline{\textbf{L}}$$\textbf{earning}$ ($\textbf{NCL}$), a lightweight plug-and-play framework that adapts pre-trained TSFMs for accurate anomaly detection without modifying their pre-trained parameters. Our key insight is to constrain the broad pattern space of TSFMs to the normal structure of a target time series, preventing their broad modeling capability from obscuring abnormal deviations. Specifically, NCL constructs 

---

### [268] SimAuthor: Harnessing Foundation Models for Persistent Scientific Simulator Authoring

**链接**: https://arxiv.org/abs/2610.06257
**作者**: Yishan Wang, Ran Piao, Mathias Funk, Aaqib Saeed
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Foundation models can generate scientific code, but authoring a scientific simulator (an executable program encoding hypotheses about how mechanisms generate observable signals) requires iterative refinement. Scientific adequacy rarely admits a unique implementation or exact test, so simulators must instead be judged against limited real observations. We study this setting as scientific simulator authoring under weak empirical feedback, where distributional comparisons between simulated and real signals guide revision, and the target is the simulator itself rather than only its generated samples. We introduce SimAuthor, a persistent authoring harness that retains and revises executable simulators, separates scalar search scores from structured discrepancy feedback, and accumulates reusable implementation mechanisms. We evaluate SimAuthor on six biomedical tasks spanning cardiac and respiratory audio, photoplethysmography (PPG), and electrocardiography (ECG). Under a fixed 100-attempt b

---

### [269] GRAM: Correcting Frozen Time-Series Foundation Models via Graph-Retrieved Amplitude Memory

**链接**: https://arxiv.org/abs/2610.04827
**作者**: Xiaoyun Yu, Xiangfei Qiu, Yonggui Huang, Shixiang Tang, Nanqing Dong, Wanli Ouyang 等 (10 人)
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Time-series foundation models (TSFMs) enable zero-shot forecasting through large-scale cross-domain pretraining, while retrieval augmentation further improves their performance by leveraging historical information. However, existing methods typically correct TSFM forecasts using the ground-truth futures of similar historical windows, which contain both predictive components already captured by the foundation model and sample-specific random fluctuation that is difficult to transfer. In contrast, recurring systematic model bias within prediction errors more directly characterizes the failure modes of a frozen TSFM and therefore provides more valuable correction signals. Effectively exploiting such model bias, however, poses two challenges: prediction errors at different numerical levels are difficult to compare due to scale differences, and the recurring bias must be extracted from prediction errors contaminated by random fluctuation. To address these challenges, we propose GRAM, a gene

---

### [270] Site Is Decodable Before Pretraining: Negative Controls for Probing Frozen Brain-MRI Foundation Models

**链接**: https://arxiv.org/abs/2608.10295
**作者**: Saman Rahbar
**来源**: cs.CV cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [271] Less Context, Better Geometry: Masked Geometric Encoder for Robust 3D Foundation Models

**链接**: https://arxiv.org/abs/2610.06813
**作者**: Zhimin Shao, Xijun Liu, Zhaoliang Zhang, Yutao Tang, Abhay Yadav, Rama Chellappa 等 (7 人)
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent progress in 3D foundation models has enabled rapid 3D reconstruction and camera calibration by leveraging learned 3D priors from vast amount of spatial data. However, the all-to-all global attention design leads to quadratic complexity and limits long-sequence inference; unconstrained cross-view interactions also can propagate unreliable evidence from occluded or visually similar but geometrically distant views. In this paper, We introduce a Masked Geometric Encoder (MGE), which promotes the learning of robust geometric representations under incomplete cross-view context. During training, MGE strategically drops frame tokens from global attention and distills from a pretrained full-context teacher model. This allows the model to learn an intrinsically richer per-frame representation while providing sufficient intermediate supervision to avoid performance degradation. Through extensive experiments, we show that MGE leads to much stronger performance under occlusion and doppelgang

---

### [272] A Unified Scaling Law for Time Series Foundation Models

**链接**: https://arxiv.org/abs/2610.05269
**作者**: Xilin Dai, Yiding Liu, Zewei Dong, Jiang-Ming Yang, Qiang Xu
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We develop a Unified Scaling Law and a Unified Theory of Time Series Learning to understand how model capacity and historical information support forecasting. Across different lookback lengths and forecast horizons, we analyze 18,768 experimental cells from 21 checkpoints on 23 dataset-frequency tasks spanning six domains. Our empirical methodology integrates local resource relations into a parsimonious, fitted five-parameter law: capacity gains increase with history, context gains diminish toward saturation, and horizon effects enter as a common shift. Fitted without Toto 2.0, the law predicts its horizon-averaged capacity-scaling curves with mean absolute percentage errors of 1.09% and 1.50% at input lengths 2048 and 4096. To understand how history supports prediction, our learning theory uses Gaussian regression to analyze rule identification and predictive capability. We hypothesize that full-shot models learn by accumulating information in weights, while frozen time series foundat

---

### [273] Kandinsky 6.0 Video: Foundation Models for Synchronized Video and Audio Generation

**链接**: https://arxiv.org/abs/2610.05608
**作者**: Team Kandinsky, Julia Agafonova, Bulat Akhmatov, Mikhail Aksyutin, Grigorii Alekseenko, Anastasia Aliaskina 等 (10 人)
**来源**: cs.CV cs.AI cs.LG cs.MM
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We present Kandinsky 6.0 Video, a family of foundation diffusion models for synchronized text-to-audio-video generation, comprising Kandinsky 6.0 Video Lite (3B parameters) and Kandinsky 6.0 Video Pro (29B parameters). Both models generate 5-second video clips with synchronized 44 kHz audio, including lip-sync, in text-to-audio-video (T2AV) and image-to-audio-video (I2AV) modes; a built-in super-resolution model raises the output resolution to Full-HD (1920$\times$1080). Building on the video generation capabilities of Kandinsky 5.0, Kandinsky 6.0 Video employs a dual-stream CrossDiT architecture that connects a pretrained video stream and a newly trained audio stream through bidirectional cross-attention for temporal and semantic alignment. Our continuous pretraining strategy first trains the audio stream from scratch on large-scale audio corpora and then trains both streams jointly on paired audio-video data while preserving unimodal fidelity; pretraining is followed by supervised fi

---

### [274] TimeNet: An Extensible Unified Data Infrastructure for Next-Generation Temporal Foundation Models

**链接**: https://arxiv.org/abs/2610.04407
**作者**: Martin Maritsch, Timo Stoffregen, Thomas Kaar, Behsad Riemer, Maxwell A. Xu, Max Rosenblattl 等 (10 人)
**来源**: cs.AI cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Temporal Foundation Models (TFMs) aim to generalize across domains, datasets, and tasks. Yet, their development remains constrained by fragmented, task-specific data formats, annotations, and processing pipelines. We introduce TimeNet, an open-source data standard and scalable infrastructure that decouples temporal data from task definitions and represents signals, metadata, annotations, and supervision in a shared, extensible data model. TimeNet supports multimodal signals with regular, irregular, or ordinal time axes and expresses different task families (including classification, forecasting, temporal localization, question answering, generation, and editing) as reusable views over the same recordings. This shared representation enables heterogeneous time-series datasets to be combined for large-scale model training across domains, modalities, and tasks. We demonstrate TimeNet by transcoding datasets with 1.5M task instances spanning diverse domains, modalities, temporal scales, and

---

### [275] Training and Scaling Compute-Optimal Physiological Waveform Foundation Models

**链接**: https://arxiv.org/abs/2610.05649
**作者**: Pingzhi Li, Jie Peng, Shuqing Luo, Zachary Plotkin, Tianlong Chen
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We investigate the scaling laws and compute-optimal training of physiological waveform foundation models (FMs). We train Aether, a family of over one hundred FMs ranging from 20M to 2.1B parameters, on up to 36.3M hours of physiological waveforms. We construct eight clinical prediction tasks from MIMIC-III and evaluate the FMs through linear probing. The 720M FM outperforms all existing baseline FMs across all eight tasks. A scaling law of model size, pretraining hours, and labeled patients predicts downstream ranking error, i.e. $1-\mathrm{AUROC}$, effectively with $0.5\%$ prediction MAE at held-out resource scales and $0.9\%$ MAE when extrapolating to 2.1B parameters. We present three findings: (1) Compute-optimal training scales both FM size and pretraining hours. Under the fitted law, a $10.0\times$ increase in compute FLOPs scales model size by $1.2\times$ and pretraining hours by $8.2\times$. (2) Larger FMs use waveform data more efficiently, and greater pretraining exposure incr

---

### [276] Planetary Geospatial Foundation Models: A New Paradigm for Global Public Health

**链接**: https://arxiv.org/abs/2610.05699
**作者**: Arbaaz Muslim, Aviv Slobodkin, Katherine Wheeler-Martin, Eric Zhou, John Brittain, Martin Frasch 等 (10 人)
**来源**: cs.LG cs.CY
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The efficacy of traditional disease prediction is limited by spatial gaps and temporal lags, which impact the timing and targets of resource deployments. Outbreaks escalate undetected, chronic disease burdens are quantified years later, and at-risk populations in data-sparse regions remain unaddressed. Planetary geospatial foundation models complement existing epidemiological workflows to provide operational improvements, encoding multimodal search, mobility, and environmental signals into generalizable place representations. As illustrations of this complementarity, we present independent global health case studies of Google Earth AI's Population Dynamics Foundation Model (PDFM) -- a foundation model for geospatial inference -- across four domains (vaccine-preventable, communicable, noncommunicable, maternal mental health), five tasks (spatial extrapolation, interpolation/nowcasting, probabilistic forecasting, prospective forecasting, risk stratification), and four countries (USA, Can

---

### [277] Learning the Context of Errors: Black-Box Online Adaptation of Time Series Foundation Models

**链接**: https://arxiv.org/abs/2606.14222
**作者**: Xilin Dai, Yiding Liu, Hongjie Xia, Yifan Hu, Zewei Dong, Jiang-Ming Yang 等 (7 人)
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [278] FFM-CP: Cross-Backbone Fusion of Vision-Language Foundation Models for Few-Shot Computational Pathology

**链接**: https://arxiv.org/abs/2609.27710
**作者**: Anh-Tien Nguyen, Trung DQ. Dang, Nghiem Tuong Diep, Bui Ngoc Han Nguyen, Tan-Ha Mai, Miriam Cindy Maurer 等 (10 人)
**来源**: cs.CV cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [279] RRM-GPT: A Framework and Vision for Radio Resource Management Foundation Models

**链接**: https://arxiv.org/abs/2610.04296
**作者**: Ahmed Aboulfotouh, Akram Bin Sediq, Koosha Pourtahmasi Roshandeh, Omar Mashaal, Ahmad M. Nagib, Jale Sadreddini 等 (7 人)
**来源**: eess.SP cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Learning-based models for radio resource management (RRM) are typically built for a single function and deployment, so each new setting repeats the development pipeline. RRM decisions, however, share a common structure: each is assembled from interdependent fields, defined by the standard, whose values are selected in view of the network state. We propose RRM-GPT, an autoregressive framework for RRM foundation models that generate these decisions as a language model generates text. An encoder maps heterogeneous network observations into a common token representation, and a decoder emits the decision one field at a time, each conditioned on the network state and the fields already committed. Pretraining on unannotated network logs teaches the model what makes a decision valid and how controllers choose among valid decisions; post-training then adapts it to deployment-specific operator objectives through imitation or reinforcement learning. The framework targets two forms of reuse: a fun

---

### [280] Image-Based Breast Implant Detection for Mammography Dataset Curation and Near-Real-Time Deployment: Comparing Foundation Models and Task-Specific Convolutional Models

**链接**: https://arxiv.org/abs/2610.03817
**作者**: Vasisht Ishwar, Hari Trivedi, Young Seok Jeon, Beatrice Brown-Mulry, Frank Li, Rohan Satya Isaac 等 (8 人)
**来源**: eess.IV cs.CV q-bio.TO
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Purpose: To evaluate the performance-feasibility tradeoffs of foundation models (FMs) and task-specific convolutional neural networks (CNNs) trained from scratch for breast implant classification in 2D mammography, with emphasis on suitability for near real-time clinical deployment. Methods: We evaluated four models: two FMs (RAD-DINO and MammoCLIP) and two CNNs trained from scratch for implant prediction (ResNet18 and our lightweight ResNetLite). Using the Emory Breast Imaging Dataset, 5,000 unilateral screening mammograms were used for training/validation and 1,000 manually reviewed unilateral images were held out for testing. For the FMs, global image embeddings from the pretrained encoder were classified using a support vector machine (SVM). The CNNs were trained end-to-end on 2D mammograms, with ResNetLite optimized via grid search over depth and width to balance accuracy and efficiency. Performance was evaluated using AUROC, sensitivity, specificity, accuracy, embedding visualiza

---

### [281] Time-series Foundation Models for Predictive Control: The Role of Excitation

**链接**: https://arxiv.org/abs/2610.06447
**作者**: Mazen Amria, Jasper Hoffmann, Philipp Bordne, Anna Rothenh\"ausler, Lilli Frison, Harald Taxt Walnum 等 (8 人)
**来源**: cs.LG cs.SY eess.SY
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Deploying model predictive control (MPC) requires constructing or identifying a predictive model for each target system. Time-series foundation models (TSFMs) offer an attractive option thanks to strong zero-shot forecasting capabilities across systems. However, low forecast error does not guarantee that a TSFM captures the system's response to the alternative actions considered by the controller. We study this gap using residential heat-pump control as a test bed, measuring the agreement between predicted and ground-truth effects of control interventions. Importantly, we find that TSFMs can recover the system's input-response relationship when the context contains sufficient independent control excitation. Common fine-tuning pipelines and feature smoothing reduce, but do not eliminate, the need for in-context excitation. Our results indicate that current TSFMs used for predictive control require sufficiently informative control variation in the inference context. Initial closed-loop r

---

### [282] Rethinking Tabular Foundation Models On Data Streams

**链接**: https://arxiv.org/abs/2610.05352
**作者**: Nilesh Verma, Daniel Nowak-Assis, Afonso Louren\c{c}o, Albert Bifet, Bernhard Pfahringer, Maroua Bahri 等 (7 人)
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tabular foundation models (TFMs) outperform established machine learning models on tabular benchmarks through in-context learning. Building on this success, interest is growing in applying them to data streams, where data arrive continuously and evolve over time. On a stream, a TFM adapts by updating its context rather than its parameters, so its accuracy and cost depend on which examples it keeps and how often it rebuilds its context. We therefore present a systematic study of TFMs on data streams, covering memory management, computational cost, and stream-specific challenges such as concept drift and delayed labels. We find that TFMs achieve the highest predictive performance and that simply retaining the most recent examples is as effective as existing memory management techniques. They also recover faster than streaming learners after drift and keep the highest accuracy under label delay. This accuracy, however, comes at a high serving cost, since a nearly unchanged context is re-e

---

### [283] Anlu: Enabling In-Context Time Series Anomaly Detection in Foundation Models via Counterfactual Supervision

**链接**: https://arxiv.org/abs/2610.06180
**作者**: Tian Lan, Yifei Gao, Yimeng Lu, Xuming An, Meng Wang, Yue Pan 等 (7 人)
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Whether a time-series pattern is anomalous often depends on the operating regime of the monitored process. A missing event can signal a fault in one regime and be routine in another, and the query alone may not reveal which regime applies. We study in-context learning (ICL) for time series anomaly detection (TSAD) through reference-conditioned detection, where a reference record provides evidence about expected behavior and model parameters remain fixed at inference. Supplying the reference is not enough: when training anomalies are recognizable from the query alone, the detector can fit its targets while ignoring the reference. We therefore introduce counterfactual supervision, which pairs one query with two references that support different normal rules and labels the query under each. At positions where the two labels disagree, no detector that ignores the reference can fit both targets. Anlu learns from this supervision by adding a reference memory and zero-initialized gated adapte

---

### [284] SPACE-CLIPv2: Decoding Local Geometry from Frozen CLIP for Monocular Depth Estimation

**链接**: https://arxiv.org/abs/2610.05029
**作者**: Hyun Song, Taewan Cho, Kangmin Kim, Andrew Jaeyong Choi
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Vision-language foundation models such as CLIP provide strong semantic representations, but their patch tokens are not directly optimized for dense metric geometry. SPACE-CLIP showed that frozen CLIP features can support monocular depth estimation through layer-group feature fusion, yet it leaves open how neighboring CLIP tokens should be combined to recover fine local structure. We present SPACE-CLIPv2, a frozen-backbone depth decoder that aggregates fixed local neighborhoods in CLIP token space. At selected decoder stages, the model samples a fixed token stencil, predicts aggregation weights, and injects the resulting response through a gated residual update. A token-space high-pass branch further preserves shallow local contrast. On NYU Depth V2, SPACE-CLIPv2 improves over a matched SPACE-CLIP baseline, while five-seed experiments consistently favor fixed over learned-offset sampling. Zero-shot iBims-1 evaluation further improves boundary and planar-geometry measures. These results 

---

### [285] Closing the Context Gap: Activation Alignment for Tabular In-Context Learning

**链接**: https://arxiv.org/abs/2610.06679
**作者**: Yoel Zeldes
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tabular foundation models perform in-context learning (ICL) by conditioning predictions on labeled training examples provided as context. Unlike traditional models that separate training from inference, these models must process all training examples in every forward pass, making each prediction expensive. Restricting the number of training examples reduces this cost but substantially degrades performance. Instead of discarding context, we propose activation alignment, a method that leverages the full context to teach a model how to behave when seeing only a subset. This is achieved by training a lightweight linear transformation on synthetic unlabeled data to map the intermediate activations of a data-constrained "student" (using partial context) toward those of a full-context "teacher" (using all data). Training the aligner requires no GPU and converges in seconds to minutes on commodity hardware. We evaluate on 38 classification datasets from the TabArena benchmark using the leading

---

### [286] One Tile, Multiple Instances: Rethinking MIL for Sparse Diagnostic Evidence

**链接**: https://arxiv.org/abs/2610.04853
**作者**: Runsheng Liu, Cheng Jin, Hao Jiang, Hao Chen
**来源**: cs.CV cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In weakly supervised Whole Slide Image (WSI) classification, feature extractors typically compress each image tile into a single global embedding. Consequently, slide-level aggregators are restricted to this coarse tile scale, concealing fine-grained sub-tile evidence from the attention mechanism. We introduce DI-MIL, a framework that decouples encoding context from instance granularity through decomposed instances. By clustering dense spatial tokens from a frozen foundation model within each tile, DI-MIL converts a single tile into multiple independently weighted instance embeddings. As a training-free post-encoding module, DI-MIL integrates seamlessly into existing pipelines without requiring re-encoding or downstream architectural modifications. We evaluate DI-MIL on cytopathology, a challenging testbed where sparse diagnostic signals are easily diluted within standard tiles. Across four datasets, three frozen foundation models, and two attention-based aggregators, DI-MIL demonstrat

---

### [287] StageVLN: Spatial and Trajectory Auxiliary Guidance for Efficient Vision-Language Navigation

**链接**: https://arxiv.org/abs/2610.05664
**作者**: Anh Dao, Quan-Dung Pham, Le Danh Vinh, The Anh Nguyen, Nguyen Viet Tri Pham, Yiyu Chen 等 (9 人)
**来源**: cs.CV cs.RO
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Vision-and-Language Navigation (VLN) policies increasingly benefit from strong semantic priors provided by large vision-language models (VLMs). However, standard action supervision does not explicitly encourage intermediate representations to preserve scene geometry, relative orientation, or global episode progress. Incorporating depth estimators, explicit maps, point clouds, or geometry foundation models at inference can provide such structure but introduces additional computation, memory overhead, and architectural dependence during deployment. We introduce StageVLN, a training framework that shapes navigation representations through privileged spatial and trajectory guidance while preserving the original inference pathway. A frozen geometry foundation model provides multi-level spatial guidance to hierarchical navigator states, while relative-heading and expert-route progress objectives provide complementary trajectory-state supervision. All auxiliary components are used only during

---

### [288] ARO: Aligned Representation learning for multi-Omics data

**链接**: https://arxiv.org/abs/2610.06443
**作者**: Amogh Singh, Yash Shah, Chiara D'Ercoli, Arash Mehrjou, Patrick Schwab, Timothy Jones 等 (7 人)
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The high cost of functional molecular assays, and prevalence of missing modalities and unmatched samples in computational biology, create significant barriers to comprehensive multi-omic profiling, essential for capturing and reasoning over molecules, cells, tissues, and organisms. This work proposes a model that learns meaningful representations from multi-omics cancer data supporting the reconstruction of missing and unpaired modalities. Contrary to increasingly complex, larger models, e.g. Foundation Models (FMs), ARO prioritizes practical applicability in limited or incomplete data settings. ARO optimally reconstructs missing modalities (MSE of $0.15$ on the validation and test data in the Unmasked settings), with its learned latent embeddings enabling a downstream cancer classification task. Our findings indicate that analyzing diverse molecular layers as a single integrated system offers a reliable and cost-efficient approach, reducing dependence on large-scale experimental testi

---

### [289] WILLIE: A Unified Framework and Benchmark for Wound Classification, Segmentation, and Localization

**链接**: https://arxiv.org/abs/2610.05341
**作者**: Gopi Trinadh Maddikunta, Shannan Hamlin, Hsin-Mei Chen, Kimaya Barnes, Peizhu Qian
**来源**: cs.CV
**匹配关键词**: Unified Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Chronic wound management affects over 8.2 million patients in the United States and imposes substantial clinical and economic burden. Clinical wound assessment commonly involves three coupled tasks: identifying wound type, delineating wound boundaries, and localizing the wound region for measurement and monitoring. Despite this clinical coupling, existing machine learning approaches typically address wound classification, segmentation, and localization using separate models. We present WILLIE, a unified framework and benchmark for wound classification, segmentation and localization that enables systematic evaluation of multi-task wound analysis under a common protocol. WILLIE harmonizes three public wound datasets into a shared benchmark and compares unified models across three scaling configurations against 10 single-task baselines. The best model achieves 91.88% classification accuracy, 91.41% Dice, and 96.23% AP@0.5 while producing all three outputs in a single forward pass. Beyond 

---

### [290] KALEIDO: Input-Space Adaptation of a Vision Model for Time-Series Forecasting Through Gated Fold Geometries

**链接**: https://arxiv.org/abs/2610.04786
**作者**: Xiangyu Shi, Qinghua Liu, Sam Heshmati, Zubin Abraham
**来源**: cs.LG cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Time-series foundation models buy zero-shot forecasting with large temporal corpora; a vision model needs none, since a natural image implicitly embeds the patterns a forecaster must model, and an ImageNet-pretrained masked autoencoder forecasts a series by inpainting a rendering of it. A rendered series is not a natural image, however, and closing that gap takes temporal-aware adaptation. We show that the rendering geometry - how the series is folded and drawn - is a controllable, mixable axis for it. Kaleido detects the dominant periods, renders a rule-generated set of fold geometries, combines the inpaintings with a convex per-position gate fit on validation only, and fuses the result with the zero-shot output at one fixed share, with no per-dataset hyperparameter beyond the baseline's published settings. Training only LayerNorm (0.05%), Kaleido lowers MSE by 13% against the published zero-shot baseline on LTSF and, frozen, by 6.6%; on GIFT-Eval it improves the baseline by 7.4% in M

---

### [291] Physics-Informed but Not Physics-Consistent: Error Geometry and Subspace Projection for Neural AC Power Flow

**链接**: https://arxiv.org/abs/2610.05959
**作者**: Changhun Kim, Timon Conrad, Redwanul Karim, Karan Pahlajani, Julian Oelhaf, David Riebesel 等 (10 人)
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent neural power-flow solvers, including emerging foundation models, achieve accurate voltage predictions, yet such accuracy does not necessarily imply physically consistent solutions. Even small complex voltage errors can yield large AC power-balance residuals. We study this accuracy-consistency gap across PIGNN-GC, GridSFM, gridfm-graphkit, and LUMINA on realistic 2224-bus Great Britain network (GBnetwork) scenarios, with cross-grid evaluation of GridSFM over 31 systems. Using a singular value decomposition (SVD) basis fitted to training AC power-flow solutions, we find that neural prediction errors contain substantial components outside the dominant solution subspace. To address this mismatch, calibrated solution-subspace projection (CSP) suppresses off-subspace prediction components after train-only bias calibration, reducing Mean PB by 67.0%, 37.8%, 40.5%, and 68.9% for PIGNN-GC, GridSFM, gridfm-graphkit, and LUMINA, respectively, relative to calibrated predictions, while impro

---

### [292] EMG-FM-Bench: A Comprehensive Benchmark for Foundation Model Transfer and Adaptation on Electromyography

**链接**: https://arxiv.org/abs/2610.06450
**作者**: Tianhao Wu, Xu Wu, Amirmohammad Radmehr, Jiawei Yu, Yi Wu, Phuc Nguyen 等 (7 人)
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Foundation models (FMs) are increasingly being developed for general time series and physiological signals, yet their transferability to downstream physiological tasks remains poorly understood. This question is particularly challenging for electromyography (EMG), where signal distributions vary substantially across users, sensing configurations, acquisition hardware, and downstream tasks. We introduce EMG-FM-Bench, a systematic benchmark for studying foundation-model transfer and adaptation on EMG. EMG-FM-Bench unifies 20 public datasets with over 1 million EMG segments and evaluates nine pretrained foundation models across four questions: how pretrained models perform when frozen or fully fine-tuned, how much pretraining helps compared with training the same model from scratch, how well models generalize to new users with limited labeled data, and how performance changes across different EMG tasks. Across the benchmark, linear probing provides useful information about pretrained repr

---

### [293] GOTT: Object-centric Dexterous Manipulation with a Reusable Cross-Embodiment Primitive

**链接**: https://arxiv.org/abs/2610.03861
**作者**: Yulin Liu, Lai Wei, Yen-Jen Wang, Akash Sharma, Pieter Abbeel, Henrik I. Christensen and Haozhi Qi
**来源**: cs.RO cs.AI cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Foundation models and large-scale human data provide rich sources of manipulation intent, but translating this intent into multi-fingered robot behavior remains difficult. Dexterous hands still lack a reusable low-level primitive that reliably establishes contact across tasks and embodiments. We propose GOTT, a reach-acquire-move framework built around a single cross-embodiment contact-acquisition primitive. Given a robot-agnostic object trajectory and a reach specification, GOTT first brings the hand near a task-relevant contact region. The shared closed-loop primitive then establishes stable contact from this approximate initialization, and a pose-conditioned controller tracks the desired object motion. Reach specifications may come from future-aware planning, external models, or human demonstrations, while the primitive and tracking backend remain unchanged. Simulation and real-world experiments show that GOTT is able to establish robust contact across diverse objects, arm-hand plat

---

### [294] MatrixFormer: A Foundation Model for Matrix Completion

**链接**: https://arxiv.org/abs/2610.06751
**作者**: Dwaipayan Saha, Jacob Feitelberg, Kyuseong Choi, Raaz Dwivedi, Anish Agarwal
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Matrix completion underlies problems from tabular imputation to causal inference, yet existing tabular foundation models treat it as entry-by-entry prediction, repeating context for every target and discarding the matrix's two-dimensional structure. We introduce MatrixFormer, a pre-trained matrix-native transformer that predicts a full distribution for every missing entry in a single forward pass. MatrixFormer is trained entirely on synthetic low-rank and latent-factor matrices under diverse missingness patterns. Applied zero-shot and with the same model weights, MatrixFormer achieves competitive performance on causal inference panel-data tasks, language-model benchmark-score completion, tabular imputation, and recommendation systems matrix completion. These results position MatrixFormer as a general-purpose foundation model for matrix completion.

---

### [295] SUAVE: Unified Video-Action Models via Masked Diffusion

**链接**: https://arxiv.org/abs/2610.04009
**作者**: Rhythm Syed, Jean Mercat, Sedrick Keh, Kushal Arora, Paarth Shah, Aykut Onol 等 (8 人)
**来源**: cs.RO cs.CV cs.LG
**匹配关键词**: Unified Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Vision-language-action models (VLAs) inherit strong semantic grounding from pretrained vision-language backbones but are typically optimized for predicting actions rather than future observations. They can see and act, but they do not imagine the future before acting. World action models (WAMs) built on video diffusion backbones can imagine but treat language as frozen conditioning on a continuous latent space. Unified models bring these modalities into one architecture, but they either decode autoregressively, one token at a time, or keep video continuous with an auxiliary action head. In this work, we present SUAVE, a Single vocabulary Unified Action-Video modEl in which a masked diffusion transformer generates video and actions conditioned on language, with all three modalities represented as discrete tokens in a shared sequence. Choosing which tokens to mask at inference turns the same network into a world model, a robot policy, or a video-action model. For action-free co-training,

---

### [296] To Learn is to Wander: Learning Across Graphs and Tasks with Random Walks

**链接**: https://arxiv.org/abs/2610.06694
**作者**: Louis Tichelman (1 and 2), Xingyue Huang (3), Jinwoo Kim (4), \.Ismail \.Ilkan Ceylan (1 and 2 and 3) ((1) TU Wien, (2) AITHYRA, (3) University of Oxford 等 (7 人)
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Graph foundation models aim to transfer across graphs, feature spaces, relational schemas, and prediction tasks, yet existing approaches typically generalize only within particular graph modalities or tasks. We propose Wander, a graph foundation model designed to operate across these settings within a single pretrained checkpoint. Following the prior-predictive perspective, we formulate graph learning as completion of a partially observed graph. We realize this task-general view through a common interface based on random walks, allowing the same model to operate across homogeneous and multi-relational graphs with varying features, labels, and relational schemas. Wander can increase its structural context at inference time without changing its learned parameters and, under suitable assumptions, universally approximates the corresponding Bayes-optimal predictor on bounded connected graphs. Empirically, a single pretrained checkpoint achieves state-of-the-art or highly competitive results

---

### [297] Pythia: Toward Foundation World Models for Multimodal Time Series

**链接**: https://arxiv.org/abs/2610.05240
**作者**: Xilin Dai, Hongzhou Chen, Yifan Hu, Yiding Liu, Zewei Dong, Jiang-Ming Yang
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Time-series foundation models offer a unified approach to forecasting across heterogeneous domains. Textual context and auxiliary observations provide complementary information about temporal dynamics, yet reusable multimodal predictive representations remain underexplored. We introduce Pythia, a foundation world model that learns context-conditioned latent dynamics across datasets through a joint-embedding predictive architecture. A stop-gradient numerical reference guides contextual corrections to predicted future states. A separate probabilistic decoder then adapts to the frozen predictive representation and observed history, decoupling world-model pretraining from observation-space forecasting. On MUSE, Pythia-Tiny's normalized mean absolute scaled error (MASE) and weighted sum quantile loss (WSQL) are 0.6879 and 0.4269, reducing errors by 6.26% and 5.00% relative to the strongest model evaluated in the published MUSE leaderboard. Through a series of controlled experiments, we inve

---

### [298] Beyond Token Accuracy: Prioritizing What Matters for Visual Reconstruction

**链接**: https://arxiv.org/abs/2610.03822
**作者**: Zhicheng Liu, Zhouxiang Zhao, Chenliang Wu, Zhaohui Yang, Zhaoyang Zhang
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tokens have become a unified interface for multimodal foundation models, making visual-token communication a natural paradigm for efficient image delivery. However, existing methods typically rely on static policies that cannot jointly adapt to image content and channel conditions. Moreover, their token-level utility objectives do not necessarily translate into improved image reconstruction quality. In this paper, we propose AdapToC, an adaptive, reconstruction-oriented visual-token communication framework. At the transmitter, an adaptive selector jointly models image content, channel state, and communication budget to perform instance-wise resource allocation. Rather than using a fixed token rate and protection policy, it dynamically determines how many tokens should be transmitted and assigns different protection levels according to token importance and current channel conditions. At the receiver, an adaptive MaskGIT receiver incorporates channel reliability into contextual token mod

---

### [299] Video2World: Benchmarking Coding Agents for Interactive World Modeling from Embodied Videos

**链接**: https://arxiv.org/abs/2610.04432
**作者**: Jinzhou Tang, Zijun Zhang, Jing Yang, Yuchen Yan, Kun Zhou, Lingjun Mao 等 (10 人)
**来源**: cs.CV cs.AI cs.RO
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Building interactive simulators from real-world observations is a promising way to scale embodied data, but current pipelines still rely heavily on manual environment construction and calibration. We study whether frontier foundation models and coding agents can automate this process end to end. We formulate \emph{autonomous video-to-simulation} as a software engineering task in which an agent observes an embodied video, constructs the corresponding simulated environment and robot behavior, and iteratively refines the result through execution feedback. To evaluate this capability, we introduce \textbf{Video2World}, a benchmark comprising 222 reconstruction instances derived from 189 robot and human demonstration videos. Video2World measures reconstructed worlds along geometric fidelity, dynamic fidelity, and functional correctness, capturing spatial perception, physical reasoning, and executable interaction. Evaluating 9 frontier coding-agent systems reveals a sharp improvement in Task

---

### [300] T-JEPA: A Temporal Joint-Embedding Predictive Architecture for Learning Better Remote Sensing Representations

**链接**: https://arxiv.org/abs/2610.05731
**作者**: Bowen Peng, Li Liu, Yongxiang Liu, Weijie Li, Jie Zhou, Zhen Liu
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Earth observation (EO) data provide rich temporal supervision, yet existing remote sensing foundation models mainly exploit sequential observations through imposing predefined pairwise relations or aggregating holistic reconstruction context. We seek to further exploit the sparse and nonuniform temporal sampling inherent in EO sequences as supervisory signals. To this end, we propose T-JEPA, a temporal joint-embedding predictive architecture that learns time-gap-conditioned latent transitions. A shared single-frame encoder processes each observation, while a temporal predictor estimates the complete target latent field from a masked source latent representation and the actual elapsed time. Across multiple temporal intervals, these predictive constraints organize observed states into structured latent trajectories. Asymmetric metadata injection mitigates shortcut learning, and direct supervision across multiple temporal scales proves more effective than recursively rolling out intermedi

---

### [301] ExStereo: Lifting 2D Vision-Language-Action Models to 3D with Explicit Stereo Representations

**链接**: https://arxiv.org/abs/2610.04805
**作者**: I-Chun Arthur Liu, Jason Chen, Gaurav S. Sukhatme, Daniel Seita
**来源**: cs.RO cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Three-dimensional perception is critical for robotic manipulation, particularly for high-precision tasks, as recovering metric depth and precise 3D object positions from monocular RGB observations is inherently ill-posed. However, many Vision-Language-Action (VLA) models rely solely on RGB observations for perception. Leveraging recent advances in foundation models for stereo matching, we introduce ExStereo, a stereo module that augments pre-trained 2D VLAs with 3D perception. ExStereo reconstructs scene geometry from stereo image pairs and renders multi-view observations as an explicit stereo representation for stereo feature extraction. The action tokens from the action expert selectively attend to the resulting stereo tokens through our proposed action-stereo cross-attention mechanism, enabling the policy to generate robot actions conditioned on 3D scene information. To learn robust 3D representations, we introduce a mid-training stage before task-specific post-training, using a sel

---

### [302] Diffusion Transformers are Provably Optimal In-context Generators

**链接**: https://arxiv.org/abs/2610.05333
**作者**: Guoji Fu, Tomoya Wakayama, Ryotaro Kawata, Atsushi Nitanda, Wee Sun Lee, Taiji Suzuki
**来源**: cs.LG math.ST stat.ML stat.TH
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Generative foundation models are attracting interest for their ability to produce desired outputs from demonstrations given at inference time, without updating parameters. However, since a few demonstrations cannot uniquely identify the intended task, the challenge is how to learn and sample from an output distribution that reflects this task uncertainty. In this work, we theoretically analyze how a Diffusion Transformer (DiT), pretrained across diverse tasks, learns and generates predictive distributions for a new query from demonstrations. We first show that the natural target to generate from finite demonstrations is not an output derived from estimating a single task, but rather a predictive distribution that captures the task uncertainty remaining after observing the demonstrations. We then prove that a DiT can learn this predictive distribution through score estimation, using attention to aggregate information from demonstrations and diffusion to generate samples. Owing to this p

---

### [303] WAMJET: A Harness for World Action Model Acceleration

**链接**: https://arxiv.org/abs/2610.03797
**作者**: Le Chen, Lixin Liu, Jan Schneider, Zeju Qiu, Simon Guist, Bernhard Sch\"olkopf 等 (7 人)
**来源**: cs.CV cs.AI cs.RO
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> World Action Models (WAMs) leverage pretrained video foundation models for robot manipulation, but their large backbones and video-action co-prediction are expensive. Although existing acceleration techniques offer many ways to reduce this cost, selecting and composing them requires substantial engineering for each model and hardware platform. To tackle this bottleneck, we present WAMJET, an agentic harness that accelerates WAM inference by equipping coding agents with reusable optimization guidance and measurement and validation tools. WAMJET follows a bottleneck-driven workflow where the agent profiles inference, modifies targeted code, validates effects, and iteratively refines the acceleration stack as bottlenecks shift, while preserving action quality. Experiments span six WAMs, three coding agents, and two GPU architectures. WAMJET achieves up to 9.95x lossless speedup over upstream implementations. Approximation and hardware-aware optimization yield additional latency reductions

---

### [304] Xaurora: Generative Weather Forecasting with Denoising Stochastic Interpolants from a Foundation Model Prior

**链接**: https://arxiv.org/abs/2610.06509
**作者**: Eliot Walt, Miltiadis Kofinas, Nikolaj M\"ucke, Efstratios Gavves, Dim Coumou
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Deep learning has revolutionised weather forecasting in recent years, especially through atmospheric foundation models, which offer competitive skill for a fraction of the computational costs of classic physics-based models. However, most existing foundation models are deterministic, limiting the generation of large ensembles for accurate uncertainty quantification, extreme weather risk assessment, and long-range weather forecasting. Furthermore, these models incur a large, often prohibitive, computational overhead to train from scratch. To address these shortcomings, we turn a pretrained deterministic prior model, namely the Aurora foundation model, into a generative ensemble-prediction model. To that end, we introduce a novel generative method, Denoising Stochastic Interpolants, combined with a replay buffer for Stochastic Differential Equation (SDE) rollout, enabling probabilistic training of SDE trajectories. Our stochastic foundation model, Xaurora, is finetuned from the small Aur

---
