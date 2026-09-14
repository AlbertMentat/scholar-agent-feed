# 📑 论文索引 - 2026-09-15

共 135 篇论文

---

### [1] The Battery Price of edge AI: A study of the Environmental Impact of LLM Inference on Mobile Devices

**链接**: https://arxiv.org/abs/2609.11940
**作者**: \'Edouard Gu\'egain, Tristan Coignion
**来源**: cs.PF cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The rapid diffusion of generative artificial intelligence raises privacy, latency, and performance concerns that motivate a shift toward "local-first" AI, where inferences are performed on the user's device instead of on remote cloud servers. This paradigm also places a significant computational load on battery-powered smartphones, potentially shortening battery life and increasing the overall replacement rate of mobile devices. This paper presents a systematic study of the energy consumption, performance, and accuracy of on-device large language model (LLM) inference. We evaluate 18 models from different model families, sizes, and quantization levels, on two modern smartphones and on a server, using the respective state-of-the-art for such deployments. We measure the energy per generated token, inter-token latency, model accuracy, and battery-cycle consumption. Our results show that (i) on-device inference is on average 3 times less energy-efficient than batched server inference; (ii)

---

### [2] Chopthin-Consensus Power Sampling: A Diversity-Preserving Approach to LLM Decoding

**链接**: https://arxiv.org/abs/2609.12243
**作者**: Minoo Ahmadi, Seyedarmin Azizi, Erfan Baghaei Potraghloo, Mehdi Kamal, Massoud Pedram
**来源**: cs.CL cs.AI stat.ML
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Inference-time power sampling via Sequential Monte Carlo (SMC) can substantially improve large language model (LLM) reasoning without requiring post-training. However, many existing SMC approaches rely on equal-weight resampling, which can aggressively prune low-weight trajectories, discarding potentially correct reasoning paths and degrading the genealogical diversity of the search space. To address this, we introduce Chopthin-Consensus Power Sampling (CCPS). Our method applies the Chopthin resampler to LLM decoding: rather than equalizing weights and forcing unnecessary particle duplication, it enforces an upper bound on the ratio between the largest and smallest weights and carries the unequal weights forward. This targeted intervention preserves a richer set of distinct reasoning paths, keeps the weighted SMC approximation unchanged in conditional expectation, and guarantees a lower bound on the post-resampling effective sample size (ESS). To fully exploit this enriched population,

---

### [3] NDT Factory: Synthesizing Verified Network Digital Twins from Semantic Models via Multi-Agent LLM

**链接**: https://arxiv.org/abs/2609.12170
**作者**: Sudipta Acharya, Petar Djukic, Burak Kantarci
**来源**: cs.NI cs.AI cs.MA cs.SE
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Autonomous network management requires systems that can evaluate Network Service Intents (NSIs) under varying conditions without manual implementation of analysis logic, as envisioned in TM Forum Level~4 (L4) autonomy. Behavioral Network Digital Twins (NDTs) enable such evaluation, but existing NDTs rely on pre-defined analytical logic, limiting adaptability for evolving closed-loop control. This paper introduces the NDT factory, a multi-agent software system that synthesizes executable behavioral NDTs on demand from semantic models using Large Language Model (LLM). We validate the system using a Call Admission Control (CAC) case study, where deterministic what-if analysis serves as the admission decision process. The NDT factory generates a complete CAC NDT through parallel synthesis and orchestration, achieving 100% compilation and test pass rates across multiple runs. Simulation over 300 NSIs shows 99.3% decision agreement with a reference implementation, 90% admission rate, and cor

---

### [4] LifeMem: Enabling Lifelong Experience Reuse for LLM Agents

**链接**: https://arxiv.org/abs/2609.12655
**作者**: Yuli Qiu, Yutong Li, Wei Su, Zeming Liu, Wanxiang Che, Heyan Huang 等 (8 人)
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model agents are expected to continuously adapt to new tasks and environments over their lifetime by reusing past experience. However, existing memory-based agents struggle to transfer reusable experience across environments and suffer from catastrophic forgetting as experience accumulated. To address these challenges, we propose LifeMem, a lifelong learning framework that enables agents to transfer knowledge across multiple environments. During learning, LifeMem clusters accumulated interaction trajectories based on underlying workflows to extract reusable skills. When solving a new task at inference time, the agent recalls relevant skills and trajectories to guide actions. To validate our method, we conduct experiments across 10 environments and over 13k tasks with 2k newly annotated interaction trajectories. Results show that LifeMem enables effective experience reuse in lifelong learning, achieving both reduced forgetting on learned tasks and superior cross-task tran

---

### [5] Explainable Prediction from Mobile Sensing Data through LLM-guided Concept Integration

**链接**: https://arxiv.org/abs/2609.11995
**作者**: Yuning Wang, Iman Azimi, Amir M. Rahmani, Pasi Liljeberg
**来源**: cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Mobile sensing enables longitudinal monitoring of behavioral and physiological patterns in everyday settings. However, accurate prediction remains challenging in small-cohort health-sensing studies, where task-specific outcome supervision is limited relative to heterogeneous sensing data. Interpretability is also important, as model outputs should reflect meaningful behavioral and physiological patterns rather than predictive scores alone. We develop a Concept-Integrated Transformer (CIT) with LLM-guided concept supervision for explainable prediction from mobile sensing data. CIT uses a pretrained large language model to generate baseline-aware concept abnormality targets with confidence weights without manual concept annotation. Across two longitudinal datasets, CIT achieves the highest F1 score on AFFECT (0.756) and ties for the highest on a PHQ-9 dataset (0.765). The learned concept scores also reveal interpretable behavioral and physiological patterns; in AFFECT, sleep quantity and

---

### [6] Diverse Minds, Divided Networks? Personality Composition, Polarization, and Collective Intelligence in LLM-Based Social Simulations

**链接**: https://arxiv.org/abs/2609.12444
**作者**: Raad Bin Tareaf
**来源**: physics.soc-ph cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Simulated societies of large language model agents are used to study online polarization, and separately to study collective intelligence, but the two are rarely measured in the same system. It is therefore difficult to say whether a society's personality composition shapes both, or whether reducing polarization costs collective competence. We present TraitMix, an experimental design in which the Big Five composition of a simulated social network, both trait levels and trait heterogeneity, is a controlled experimental variable, and in which polarization and collective performance are measured in the same runs. Across 991 simulations of hundred-agent societies, spanning six contested topics and six language models, trait heterogeneity has the largest measured effects, acting in opposite directions on two faces of polarization: varied societies hold more dispersed opinions while being less segregated into camps, so homogeneous societies are not moderate but consensual echo chambers. Trai

---

### [7] Extracting Dataset Mentions in Forced Displacement and FCV Documents: A Weakly Supervised Framework with LLM-Based Label Refinement

**链接**: https://arxiv.org/abs/2609.12107
**作者**: Rafael Macalaba, Aivin V. Solatorio, Patrick Michael Brock, Olivier Dupriez
**来源**: cs.CL cs.AI cs.IR econ.EM
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Development and humanitarian organizations produce and support surveys, administrative registries, and other data resources to inform research, policy, and operations, yet systematically identifying where these datasets are referenced remains difficult. Such references are dispersed across research papers, project documents, humanitarian reports, and other unstructured text, limiting both the ability to trace data use and to identify potential gaps in data availability or dissemination. We present a weakly supervised framework for adapting dataset extraction to forced displacement and Fragile, Conflict, and Violence (FCV) documents without first constructing a large manually labeled training corpus. A lightweight model trained on general research literature generates candidate dataset mentions from unlabeled domain documents, which a frontier large language model (LLM) reviews in context, validating or rejecting candidates and correcting their extraction boundaries. The resulting annot

---

### [8] Granularity-Adaptive Credit Assignment for Long-Horizon LLM Agent Reinforcement Learning

**链接**: https://arxiv.org/abs/2609.12424
**作者**: Taoran Liang, Yang Liu, Shang Luo, Yingguang Yang, Rongrong Zhang, Yingzong Min 等 (10 人)
**来源**: cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reinforcement learning is now the standard way to train large language model agents on long-horizon tasks, where dozens of interdependent actions precede a single sparse reward. Critic-free, group-relative methods such as GRPO suit this regime, but they broadcast one trajectory-level scalar to every step and cannot say which decision drove the outcome. GiGPO recovers a step-level signal by grouping time steps that share an anchor state, yet it merges the step- and episode-level estimates under one fixed weight, spending the same resolution on a pivotal branching decision as on a routine, near-deterministic transition. We argue that the right resolution is state-dependent, and propose GACA, a critic-free estimator whose granularity follows an uncertainty-based criticality proxy. GACA scores every step by the negative log-likelihood its own rollout already records, then blends the two advantages with a per-step weight that grows with that score, so the gradient places more weight on the 

---

### [9] TraceMind: Predicting User Information Uptake from Low-Cost Interaction Traces during Human-LLM Content Co-Generation

**链接**: https://arxiv.org/abs/2609.12600
**作者**: Yu Mei, Fengyou Zu, Ruiwen Zhang, Jie Cai, Chang Liu, Zhoutong Ye 等 (8 人)
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In human-LLM content co-generation, AI-generated information can enter final artifacts without being adequately processed by users, creating risks when artifacts are shared or acted upon. We study whether recognition-level uptake of atomic information units can be assessed in open-ended co-generation and predicted from low-cost interaction traces. We collected data from 62 participants across three tasks. For each final draft, we extracted atomic information units and generated post-task recognition questions, yielding 1187 unit-level uptake labels. We present TraceMind, which tracks units across Chat and Draft histories, aligns interaction traces with changing on-screen layouts, and models spatial, temporal, and workflow-informed evidence. TraceMind outperformed all learned baselines across AUROC, AUPRC-non, balanced accuracy, and macro-F1. We found that uptake unfolds throughout interaction, with sustained active engagement providing informative evidence beyond isolated signals. Our 

---

### [10] BodhiPromptShield: Pre-Inference Prompt Mediation for Surface-Form Privacy Propagation in LLM Agent Pipelines

**链接**: https://arxiv.org/abs/2604.05793
**作者**: Bo Ma, Jinsong Wu, Weiqi Yan
**来源**: cs.CR cs.CV
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [11] Look Before You Leap: Pre-Action Verification for LLM Agents

**链接**: https://arxiv.org/abs/2609.11957
**作者**: Asaad Althoubi
**来源**: cs.LG cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> An LLM agent acts on the world by emitting actions: shell commands to run, edits to apply. A wrong action does not always fail loudly; it can fail silently, producing a plausible but incorrect effect that raises no error. We argue that a cheap deterministic check, run before an action takes effect, is an effective and underused form of agent oversight, and we study it across two action modalities in one framework. The idea is to fix an action's correct effect by construction, before any executor runs, so that silent failure is measured directly and the verifier may abstain rather than guess. For shell commands, a static verifier over 9930 commands and 482 tools catches 95.8% of invalid commands at a 10.0% false-positive rate. Its syntax and binary checks are oracle-exact, giving zero false positives while catching half of all errors; the flag check is bounded only by help-text coverage and accounts for every false positive. For code edits, a benchmark of 640 edits over 224 files isolat

---

### [12] A Hybrid Fuzzy- LLM Decision Support System for Lifecycle-Oriented Supply-Chain Strategy

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S0957417426030824&hl=zh-CN&sa=X&d=6055663485866601369&ei=bu6nauWvHcOuieoP-djIkQ0&scisig=AIVdB-zh15nU3ogeoH0gZJW5Un7z&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=1&folt=kw-top
**作者**: A Molina, JI Méndez, AL Bárcenas-Cortés - Expert Systems with Applications, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> LLM serves as a replaceable rendering component. This division of labour is the architectural bridge between structured prioritisation and generative explanation. This paper addresses that challenge by proposing and evaluating a hybrid fuzzy– LLM

---

### [13] SAGE-Loop: Reliable Closed-Loop LLM-Driven AutoML with Trial-and-Correction and Adaptive Ensembling

**链接**: https://arxiv.org/abs/2609.12455
**作者**: Junquan Gu, Shibo Cui, Xiangfeng Luo, Hang Yu
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Automated machine learning (AutoML) is reshaping data-driven science and industrial practice, and as large language models are introduced into AutoML, pipeline reliability becomes as important as automation efficiency. However, existing AutoML still struggles to realize instant feedback and adaptive optimization during execution, so once a run drifts into a suboptimal or failed state, it lacks a process-level correction mechanism. The fundamental pathology lies in its one-way pipeline: intermediate failures are typically terminated or bypassed, while fixed paradigms often strengthen model generation but leave ensemble decisions static, weakening both execution reliability and the controlled use of structural diversity. This indicates that LLM-driven AutoML needs a closed-loop ability for trial-correction-improvement together with evidence-based use of model diversity. To this end, we propose SAGE-Loop, a reliable closed-loop, self-adaptive, LLM-driven AutoML framework that performs mul

---

### [14] Limits of LLM Text Detectors in Education

**链接**: https://arxiv.org/abs/2508.08096
**作者**: Lukas Gehring and Benjamin Paa{\ss}en
**来源**: cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [15] Measuring Pragmatic Influence in Large Language Model Instructions

**链接**: https://arxiv.org/abs/2602.21223
**作者**: Yilin Geng, Omri Abend, Eduard Hovy, Lea Frermann
**来源**: cs.CL cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [16] Simulating Disengaged Students to Evaluate LLM-based Tutors

**链接**: https://arxiv.org/abs/2609.12331
**作者**: Xianghui Meng, Jionghao Lin
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Simulated students generated by computational models provide a practical way to evaluate tutoring strategies and pedagogical approaches used by human and AI tutors. However, such simulations should account for disengaged behaviors, including gaming the system, wheel-spinning, and off-task behavior, because tutors may need different responses for different learner states. We present Disengagement-Aware Student Simulators (DAS2), a reproducible pre-deployment protocol that models five learner-engagement states: engaged, gaming, wheel-spinning, off-task, and mixed, and evaluates AI tutor performance across these states. Using ASSISTments09, two coders independently labeled 100 sampled tutoring sessions based on anonymized interaction-log summaries. They achieved 84% agreement (Cohen's kappa = 0.78), and among agreed cases, human consensus labels matched DAS2 rule-based labels in 81% of cases (kappa = 0.75). Conditioning simulations on intended learner states reduced the correctness-rate g

---

### [17] Judging by the Cover: Cleaning LLM Truthfulness Benchmarks to Avoid Surface-Level Feature Leakage

**链接**: https://arxiv.org/abs/2609.13003
**作者**: Foad Namjoo, Remy Ogasawara, Amirali Abdullah, Cullen Anderson, Narmeen Fatimah Oozeer, Jeff M. Phillips
**来源**: cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Binary-choice truth benchmarks ask models to choose between a correct and an incorrect answer, but if the two answers differ systematically in surface-level features, models can exceed chance without performing the intended reasoning. We show that this failure mode is detectable and can be exploited by downstream classifiers. In TruthfulQA, a simple six-feature logistic classifier achieves substantial accuracy in separating correct from incorrect answers. We further show that similar surface-level artifacts are present in additional benchmarks. To counteract this, we developed a general mechanism to clean them by removing the most leakage-reinforcing pairs. We release a version of TruthfulQA with surface-feature leakage reduced close to chance and provide a mechanism, Audit-Prune, so that the datasets can be cleaned before release.

---

### [18] NS-Copilot: An LLM-Driven Agent System for Autonomous Neuroscience Analysis

**链接**: https://arxiv.org/abs/2609.01971
**作者**: Wuche Liu, Yiran Qiao, Linlin Hou, Rui Yang, Shusen Pu, Song Wang 等 (7 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [19] How AI Coders Discuss, Disagree, and Reach Consensus: Challenges and Opportunities for LLM -Based Qualitative Coding

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2609.11109&hl=zh-CN&sa=X&d=14287433084364858904&ei=bu6nauWvHcOuieoP-djIkQ0&scisig=AIVdB-zZ870jRw1DiZkUZCaPGUNT&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=5&folt=kw-top
**作者**: J Kim, J Mitchell - arXiv preprint arXiv:2609.11109, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> LLM performance makes it difficult for system developers and designers to optimize LLM … Our study seeks to bridge this gap by performing a statistical analysis of LLM capabilities in … and LLM performance, our work offers a

---

### [20] LatentMD: Benchmarking Markdown Boundary Failures in LLM-Generated Text

**链接**: https://arxiv.org/abs/2609.06993
**作者**: Sungjune Lee, Myungjoo Kang
**来源**: cs.SE cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [21] K-Bench: A Benchmark for LLM Unlearning in Agentic Deployments

**链接**: https://arxiv.org/abs/2609.12808
**作者**: Guangsheng Yu and Yanna Jiang and Qin Wang and Baihe Ma and Xu Wang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Unlearning benchmarks such as TOFU and MUSE certify forgetting by reading the model's final answer, where a model that refuses to answer already counts as having forgotten. We show that this model-level certificate does not transfer once the model is deployed as an agent. We introduce K-Bench, a benchmark that scores LLM unlearning under agentic deployment. K-Bench inspects all six channels a ReAct agent exposes, including its chain-of-thought (CoT), tool calls and tool observations, and elicited summary. A query counts as leaked if the secret appears in any of them. Each experiment places the secret in exactly one of the agent's three sources (the weights, the prompt, or the retrieval store). The K-Score is computed separately for each source and credits forgetting only when the agent remains usable. Clearing the answer channel does not make the secret unrecoverable. On structured retrieval, the secret stays verbatim in the tool-observation channel and the aggregate leak rate is uncha

---

### [22] FastE: Readout-Triggered Token Compression for LLM Embedding Inference

**链接**: https://arxiv.org/abs/2609.08407
**作者**: Jinsong Shu, Jinyong Wen, Baokun Wang, Zhongle Xie, Lidan Shou, Weiqiang Wang 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [23] AsyncFlow: An Asynchronous Streaming RL Framework for Efficient LLM Post-Training

**链接**: https://arxiv.org/abs/2507.01663
**作者**: Zhenyu Han, Ansheng You, Haibo Wang, Kui Luo, Guang Yang, Wenqi Shi 等 (10 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [24] EduFair-Bench: Evaluating Pedagogical Fairness of LLM Tutors Across Student Demographics

**链接**: https://arxiv.org/abs/2609.12949
**作者**: Jiaxu Zhao, Bahar Radmehr, Fares Fawzi, Tanya Nazaretsky, Tanja K\"aser
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly deployed as tutors, but it is unclear whether they support all students equally well. We introduce \textbf{EduFair-Bench}, a benchmark for auditing the pedagogical fairness of LLM tutors---whether tutoring quality varies systematically with student demographics. EduFair-Bench pairs a multi-domain question bank (mathematics, physics, chemistry) with a controlled simulation in which a fixed LLM student interacts with each tutor across nine demographic levels spanning four dimensions: gender, immigration background, first language, and socioeconomic status (SES). Tutoring quality is scored on five turn-level pedagogical metrics and four conversation-level dimensions, using an LLM judge validated against three-annotator consensus on 180 tutor turns. Bias is measured via paired Wilcoxon signed-rank tests and bootstrap effect-size confidence intervals. Two ablations (demographic cues conveyed through names; conflicting demographic information bet

---

### [25] Information Specialization and Constrained Synthesis in Multi-Agent LLM Forecasting: A Prospective Live-Study of the 2026 FIFA World Cup

**链接**: https://arxiv.org/abs/2609.12495
**作者**: Julian Varghese, Lucas Bickmann, Sarah Sandmann
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models are being organized into multi-agent systems with specialized roles, but whether such specialization produces distinct forecasts and whether subsequent synthesis improves utility remains unclear. In this study, we carried out a live, prospective evaluation over the final 56 matches of the information-dense 2026 FIFA World Cup, keeping a frontier foundation model constant while assigning two primary forecasting agents contrasting specialist roles: a quantitative specialist focusing on structured performance statistics and a news specialist focusing on current injuries, tactics and information from press conferences. Their forecasts were then reviewed by a separate critic before being combined by a meta-agent, resulting in a sequential four-agent model. Forecasts from the betting market served as an external benchmark. The news specialist obtained the highest mean probability-weighted Top-3 utility and matched the betting market in Top-3 exact-score hits. Neverthele

---

### [26] RecGPT: A User Intent-Centric Next-Generation LLM -Powered Recommender System in Industrial Practice

**链接**: https://scholar.google.com/scholar_url?url=https://dl.acm.org/doi/pdf/10.1145/3846382&hl=zh-CN&sa=X&d=7885179366728319338&ei=bu6nauWvHcOuieoP-djIkQ0&scisig=AIVdB-wr_57_7Tk_2vwzmy7x_5mP&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=3&folt=kw-top
**作者**: J Tang, W Chen, D Chen, C Yi, G Guo, W Yang 等 (8 人)
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> from LLM -generated item tags, which captures user intent through reasoning-based analysis rather than surface-level feature matching. By integrating these LLM … Here, we prompt the LLM to compress detailed item information while preserving core

---

### [27] "I Felt Very Seen, But Still Very Alone": Longitudinal Trajectories of General-Purpose LLM Use for Socioemotional Support

**链接**: https://arxiv.org/abs/2609.12314
**作者**: Meryl Ye, Briana Vecchione, Livia Garofalo, Ranjit Singh
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> People increasingly use general-purpose chatbots such as ChatGPT, Claude, and Gemini for mental health and emotional support. We report a multi-stage longitudinal qualitative study of 18 U.S. adults, conducted from April to December 2025, combining initial interviews, a four-week diary study, focus groups, and exit interviews. We find that socioemotional use often emerged gradually out of practical use and when other forms of support were unavailable. Participants developed routines and boundaries around chatbot use, which were disrupted by model updates, evolving public discourse about AI harms, and changes in personal circumstances. We demonstrate how longitudinal study captures factors beyond the human-AI dyad, and argue that HCI researchers and designers should account for users' histories with their chatbots and broader care ecologies when evaluating AI systems over time and introducing updates that may disrupt established sources of support.

---

### [28] Decomposing LLM-Judge Uncertainty to Target Expert Labels

**链接**: https://arxiv.org/abs/2609.06444
**作者**: Ryan Lail
**来源**: cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [29] Is that Really You? Understanding Persona Adoption in LLM -Based Requirements Engineering

**链接**: https://scholar.google.com/scholar_url?url=https://ieeexplore.ieee.org/abstract/document/11676655/&hl=zh-CN&sa=X&d=10894295131055814562&ei=bu6nauWvHcOuieoP-djIkQ0&scisig=AIVdB-wnK3kRytYFReAU7unmQsAR&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=2&folt=kw-top
**作者**: P Morente, Q Motger, M Oriol - 2026 IEEE 34th International Requirements …, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> We present a research preview aimed at guiding the adoption and evaluation of persona patterns in LLM -supported RE tasks. Our … prompts for LLM -based systems. Third, we evaluate whether LLM outputs reflect the intended persona characteristics

---

### [30] LLM -Driven Aspect-Based Semantic Alignment for Review-Based Recommendation

**链接**: https://scholar.google.com/scholar_url?url=https://dl.acm.org/doi/pdf/10.1145/3843223&hl=zh-CN&sa=X&d=9036563915247092054&ei=bu6nauWvHcOuieoP-djIkQ0&scisig=AIVdB-wRuaN5AdzBhJmz8aIJgILx&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=4&folt=kw-top
**作者**: H Chen, Z Cheng, F Liu, R Hong, M Wang - ACM Transactions on Recommender …, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Since LLM -ASAR employs an LLM in Stage I for sentence-level aspect annotation, we investigate the robustness of the proposed framework with respect to diferent annotation backbones. Speciically, we re-run Stage I using LLMs from the Qwen

---

### [31] A reflection-enhanced LLM literature-to-design framework for surrogate-guided inverse design of high-entropy alloys

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S0950705126017387&hl=zh-CN&sa=X&d=6673939797734565790&ei=bu6nauWvHcOuieoP-djIkQ0&scisig=AIVdB-zzftcSzwbAMMyjBy_AyLXF&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=6&folt=kw-top
**作者**: YX Chang, KH Chao, YC Wang, YH Chen, FY Ouyang… - Knowledge-Based Systems, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> To address this challenge, this study proposes a reflection-enhanced, LLM -assisted literature-to-design framework for first-pass HEA screening and … to satisfy the LLM context limit, and the resulting cleaned text is used as standardized input for

---

### [32] Can We Trust LLM Judges: A Study of Capability-Dependent Biases and Multi-Judge Ensemble for Bias Calibration

**链接**: https://arxiv.org/abs/2609.12002
**作者**: Gemma Zhang, Prachi Badarayani, Asmi Kumar, Sadid Hasan, Sulaiman Vesal
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLMs are increasingly used as automated judges for model training and evaluation, yet individual judges exhibit systematic biases that undermine reliability. Much of prior work has studied biases in pairwise LLM-as-a-judge settings; in this paper, we focus on absolute scoring tasks, which mirror more realistic use cases. Across four benchmarks and six models (36 judge-examinee pairs), we show that a model's task accuracy strongly predicts its judging accuracy (Pearson $r \geq 0.90$ on most models) and inversely predicts its directional bias ($r \leq -0.83$), but that accuracy alone does not ensure fair evaluation: more capable examinee models consistently receive more lenient judgments from all judges ($r \geq 0.83$). To address this, we propose calibrated weighted majority voting (WMV), an ensemble evaluation method that aggregates multiple LLM judges weighted by online estimates of their false-positive and false-negative rates. We introduce a disagreement-based estimator that derives

---

### [33] HyQuant: Hybrid-Precision Quantization for LLM Attention

**链接**: https://arxiv.org/abs/2608.27875
**作者**: Jiatong Ding, Bingxin Xing, Yu Zhang, Dian Ding, Xiaodong Yi, Xianbin Ouyang 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [34] Who Judges the Judges? A Chinese Safety QA Benchmark for Evaluating LLM Responses and Safety Judges

**链接**: https://arxiv.org/abs/2609.01210
**作者**: Rui Yang, Shuang Huang, Junhua Liu, Ziqi Zhao, Qingzhong Yan, Yuhang Sun 等 (10 人)
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [35] ElectriQ: LLM dialogue benchmark for electric power marketing in renewable-integrated power systems

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S2352484726006384&hl=zh-CN&sa=X&d=10340315361842373452&ei=bu6nauWvHcOuieoP-djIkQ0&scisig=AIVdB-yQ05mUWb3ju1wMq4f3Lqyq&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=8&folt=kw-top
**作者**: J Wang, Q Peng, H Li, Z Zeng, J Zhang, K Yang 等 (8 人)
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> To address this gap, we present ElectriQ, a large-scale benchmark for LLM evaluation in EPM. ElectriQ contains over 550k multi-turn dialogues … basis for deploying LLM -based EPM assistants in demand-side management, renewable

---

### [36] ReasoningFlow: Discourse Structures for Understanding LLM Reasoning Traces

**链接**: https://arxiv.org/abs/2606.05402
**作者**: Jinu Lee, Shivam Agarwal, Amruta Parulekar, Siddarth Madala, Dilek Hakkani-Tur, Julia Hockenmaier
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [37] What Drives Recovery in Agentic Text-to-Cypher? LAST-CQ: An LLM Agent Self-Refinement Framework

**链接**: https://arxiv.org/abs/2609.12746
**作者**: Ioannis Prokopiou, Athanasios Aidinis, Panagiotis-Christos Kyrmpatsos, and Pantelis Vikatos
**来源**: cs.AI cs.CL cs.LG cs.MA cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Agentic pipelines for structured-query generation are rapidly expanding, but it is unclear which part of the loop produces the gain. We use LAST-CQ -- a five-agent, training-free, execution-grounded Text-to-Cypher framework -- as an instrumented testbed, running three counterfactuals over 2,471 live-database queries and six backbones spanning three vendor scale tiers. Removing correction is worth between 3.1% aggregate execution-BLEU against the single-pass system and 12.3% against a no-refinement counterfactual (up to 80.7% for the weakest backbone). Replacing schema-grounded, LLM-synthesised feedback with raw database error strings costs almost nothing (20.9% vs. 19.9% naive exact match; <0.2% end-to-end; equivalent within $\pm 0.075$ set-F1 by two one-sided tests). Spending the same call budget on parallel sampling degrades quality by 10-11%. What works is detecting failure and routing it to a retry, not the feedback sophistication or number of samples. LAST-CQ itself recovers 91.7%

---

### [38] Creating an Atomic User Model for Personality-Aware Large Language Model Interaction

**链接**: https://arxiv.org/abs/2609.12086
**作者**: B. Sankar, Deepthika S, Pawni Yadav, Amogh A S
**来源**: cs.HC cs.AI cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Assistants built on large language models are expected to write as their user would, and the dominant approach is single-channel: preferences summarised from conversation history and reinserted into context. This inverts the order of inference. Preferences are the task-dependent surface of a comparatively stable personality structure, so a system storing only preferences relearns the person whenever the task changes. First, we characterise personality seepage, where a prompt's linguistic surface carries a personality fingerprint the assistant mirrors without access to the personality behind it. Second, we propose the Atomic User Model (AUM), a human-readable representation organising a person as a stable identity nucleus with four interpretable shells (psychological, cognitive and experiential, behavioural, and social), plus cross-shell entries recording internal conflict and authenticity. Third, we treat AUM as a retrieval index over a person rather than a prompt prefix, with a pipeli

---

### [39] ASTRIL-MPC: Autonomous Traversal Framework of Articulated Tracked Robots with Language-Guided Neural-Kinematic MPC

**链接**: https://arxiv.org/abs/2609.13083
**作者**: Zhenfeng Gan, Yanbo Chen, Lirong Che, Junbo Tan, and Xueqian Wang
**来源**: cs.RO cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In urban search and rescue, articulated tracked robots (ATRs) must traverse structured but contact-rich environments such as stairwells and cluttered building interiors. Reliable autonomy remains challenging because robot-terrain interaction (RTI) is hybrid and discontinuous, and effective flipper-track coordination is difficult to model analytically. We present ASTRIL-MPC, a language-guided neural kinematics model predictive control (MPC) framework for autonomous traversal. A learned kinematics model predicts short-horizon task-state increments from a height sequence and recent trajectories; NMPC plans with multi-objective costs and strict feasibility constraints; and a large language model (LLM) proposes bounded updates to selected weights and bounds through a safety-checked interface with range clipping, rate limiting, and consistency checks. The compiled predictor enables a full control cycle within 100 ms. Across three traversal tasks and a multi-height generalization setting, AST

---

### [40] T-GADE: Thermodynamical Generative-AI-Driven Evolution of LLM Artifacts

**链接**: https://arxiv.org/abs/2609.12286
**作者**: Kyoko Ogawa, Naoki Mori
**来源**: cs.AI cs.NE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Integrating evolutionary computation and large language models (LLMs) requires control of population diversity as well as generative capability. Among LLM outputs, those with explicit structure, such as a description paired with code, are structured artifacts; we use artifact for short. We propose T-GADE, which evolves these artifacts by extending thermodynamical genetic algorithms through LLM-based genetic operators and artifact-level diversity evaluation. A common free-energy objective supports generational and steady-state updates, with Fermi-type occupancy excluding repeated genotypes and Bose-type occupancy permitting them. We establish exact one-member removal and conditions for recovering the zero-temperature survival rule of Evolution of Heuristics (EoH). On the online bin-packing task studied in the EoH paper, excess measures relative bin-count overhead above a volume lower bound. Training excess uses search instances; transfer excess uses instances with another bin capacity. 

---

### [41] A decision-basis contract for auditable LLM-assisted medical billing verification: deterministic rules, verbatim evidence, and fail-closed abstention

**链接**: https://arxiv.org/abs/2609.12156
**作者**: Jan H\"olter, Kevin Geis, Benjamin Raab, Boris Bauke
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> This work presents a proof of concept for auditable LLM-assisted medical billing verification based on a decision-basis contract. The contract separates deterministic checks of versioned fee-catalog rules from LLM-based assessment of free-text documentation. The deterministic layer resolves the applicable catalog release and checks code availability, quantity limits, and exclusions. The semantic layer classifies each claimed item as supported, contradicted, or missing required information. Support and contradiction require a verbatim evidence span; unavailable rule context, unsuccessful assessment, or missing required evidence prevents support through fail-closed abstention. We evaluated four locally run open-weight models on a synthetic catalog and 36 curated cases under the contract, an ablation without explicit documentation requirements, and an end-to-end baseline. Outcome agreement varied across models and showed no consistent advantage over the baseline. Explicit documentation re

---

### [42] Behavior Quotient Learning for Low-Rank Adaptation of LLM Agents

**链接**: https://arxiv.org/abs/2609.12896
**作者**: Pengyang Zhou, Xiaobin Tu, Zhengxi Liu, Rongkun Xue, Haochen Li, Miancan Liu 等 (10 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based agents rely on heterogeneous interaction capabilities to accomplish complex tasks. Existing approaches often distribute these capabilities across multiple LoRA adapters, which increases adapter storage requirements and introduces routing overhead during inference. A single LoRA avoids this overhead, but learning from diverse agent trajectories under a fixed rank budget presents two challenges. First, trajectories with different interaction traces and parameter gradients can induce equivalent changes in decision distributions, causing repeated updates to overemphasize redundant behavioral changes. Second, an aggregated update may exceed the rank budget of the adapter, and approximating it in weight space can distort the decision changes that it is intended to produce. We propose BQ-LoRA, a low-rank adaptation framework that organizes trajectory updates through a local behavior quotient manifold. It contains two modules, i.e., behavior quotient balancing (BQB) and decision pres

---

### [43] LLM-Enhanced Dual-Branch Learning for Large-Scale Multi-Label Text Classification

**链接**: https://arxiv.org/abs/2609.12915
**作者**: Hui Ye, Jing Zhang, Xiulong Yang, Rajshekhar Sunderraman
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large-scale multi-label text classification assigns a small subset of relevant labels to each document from a vocabulary containing thousands or tens of thousands of candidate labels. Although pretrained language models have improved semantic text representations, most representation-based approaches center their prediction pipelines on a primary encoder or combine auxiliary features within a single ranker. The complementarity between heterogeneous language models therefore remains insufficiently explored. We propose DualMLC, a dual-branch framework that processes the same document through an autoregressive decoder-only language model and a bidirectional encoder. Each branch maintains its own representation pathway and independently estimates relevance scores over the shared label space. DualMLC combines the two score vectors through late logit fusion, allowing shared evidence to reinforce relevant labels and branch-specific evidence to compensate for limitations in the other branch's 

---

### [44] Kraken: LLM-based Speech-to-Speech Translation via Low-bitrate VQ and Dual-path Source Conditioning

**链接**: https://arxiv.org/abs/2609.13045
**作者**: Hayato Futami, Hassan Shahmohammadi, Tushar Dhyani, Alkis Koudounas, Rapha\"el Lafargue, Yosuke Kashiwagi 等 (8 人)
**来源**: cs.CL cs.SD
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Speech-to-speech translation (S2ST) has advanced significantly with speech LLMs, offering the potential for joint optimization and preserving non-linguistic information. However, these models struggle with predicting high-bitrate speech tokens in LLMs, and face the challenge of relying on S2ST training data with ideally aligned speaker identity and prosody. We propose using low-bitrate tokens based on single-layer vector quantization, trained to reconstruct self-supervised learning (SSL) features. We also employ a separate token-to-waveform decoder named Autowave-X, which is also conditioned on the source speech to improve non-linguistic transfer, thereby relaxing the training data constraints. With the integration of these techniques, we propose an S2ST model named Kraken, which augments a pre-trained LLM with speech feature inputs and the low-bitrate token outputs, followed by Autowave-X vocoder. We built the model upon Qwen3-8B and trained it using 150k hours of multilingual and mul

---

### [45] AIM: A Privacy-Aware Interoperable Memory Framework for Multi-Agent Multi-User LLM Systems

**链接**: https://arxiv.org/abs/2609.12320
**作者**: Zachary Johnson, Nigel Boachie Kumankumah, Somya Chatterjee, Tejas Sathyamurthi, Min Chen, Xinyi Alice Li 等 (10 人)
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Traditional large language models (LLMs) are scoped to individual user sessions, limiting their knowledge to a single conversation and preventing them from learning user preferences that evolve over time. Existing agentic memory systems address this limitation but generally operate at the individual-user level, restricting the public knowledge that could be shared across users to improve downstream responses. We introduce AIM (Agentic Interoperable Memory), a unified, privacy-aware memory framework that enables multi-agent, multi-user LLM systems to persistently manage private and shared memory. AIM dynamically classifies information as private, scoped to one user and inaccessible to others, or public, accessible to all users. It enforces index-level access controls so that private memories are retrievable only by their owner, protecting sensitive data while allowing beneficial shared knowledge to improve coordination and consistency. We also introduce MUMBench (Multi-User Memory Bench

---

### [46] GAUGE: When Not to Trust LLM-as-a-Judge in User-Simulated Evaluation of Task-Oriented Agents

**链接**: https://arxiv.org/abs/2609.12191
**作者**: Umesh Bodhwani, Thanh Tran, Kai Wei
**来源**: cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Comparing and selecting task-oriented LLM agents increasingly relies on a low-cost offline evaluation gate: persona-driven LLM user-simulators converse with each candidate, an LLM-as-a-judge scores the transcripts, and the higher-scoring agent is promoted. We introduce GAUGE, a reusable offline protocol that measures whether this gate's ranking matches a grounded verifiable reward across 25 agents from six providers on the $\tau^2$-bench and SimulatorArena benchmarks, separating two kinds of evaluation validity that release practices conflate: ranking validity and construct validity. First, a satisfaction-success gap: satisfaction carries essentially no information about task success, as conversations rated satisfied by our blind panel are decorrelated from actual success, with 57.5% of them failing the customer's task, a pattern consistent across five rater populations, both benchmarks, and every subjective dimension we rated. Second, while the gate's ranking is robust across the broa

---

### [47] On The Effectiveness-Fluency Trade-Off In LLM Conditioning: A Systematic Study

**链接**: https://arxiv.org/abs/2606.12234
**作者**: Iuri Macocco, Pau Rodr\'iguez, Arno Blaas, Luca Zappella, Marco Baroni, Xavier Suau
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [48] Dissecting GPU Utilization for LLM Inference on Nvidia Hopper

**链接**: https://arxiv.org/abs/2609.12923
**作者**: Mohammad Siavashi, Gerald Q. Maguire Jr., Dejan Kostic, Marco Chiesa
**来源**: cs.PF cs.AR cs.DC cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A single SM utilization percentage can make an LLM inference workload look compute-saturated while hiding how much useful work is being done. The problem is not that the counter is wrong, but that it collapses several different mechanisms into one number. This is most severe during decode, where each request contributes only one new token and dense projection GEMMs become small-row matrix multiplications. On Hopper, the bfloat16 GMMA path executes these operations in fixed 64-row matrix fragments, so small-batch decode can fill only a small fraction of each fragment with real token rows. In this paper, we profile vLLM with FlashAttention-3 and cuBLASLt on an H100 NVL across cold prefill, warm prefill, and decode, sweeping sequence length and batch size. We replace the usual single utilization number with eight counter-validated views derived from raw Nsight Compute reports, each pinned to an NCU counter or explicit formula. Together, these views map utilization gaps to concrete mechani

---

### [49] RoofLang: Enabling AI-Driven Architecting of LLM Inference Systems

**链接**: https://arxiv.org/abs/2609.12551
**作者**: Ziyue Yang, Yuting Jiang, Lei Qu, Peng Cheng
**来源**: cs.DC cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> AI is beginning to make substantive contributions to LLM inference optimization. Existing AI optimizations are predominantly profiling-based. Profiling-bound feedback confines the search to the capabilities and performance of an existing software stack, preventing a fundamentally better architecture of LLM inference systems from being identified. To enable the AI-driven LLM inference system architecting loop, we argue that a general workload representation, a verifiable mutation space, and an implementation-independent evaluator are required. We present the RoofLang domain-specific language (DSL) that provides these features. In our evaluation, RoofLang reveals that DeepSeek V4-series models could achieve 3.5-39.5$\times$ higher peak decode throughput than other representative models. This gap is disproportionate to their total parameter counts and arises largely from compact KV-cache designs that support larger batches and reduce memory traffic. A persistent optimizer agent further di

---

### [50] UFO: Chain-of-Evaluation for Omni-Condition Alignment in Multi-Modal Image Generation

**链接**: https://arxiv.org/abs/2609.12397
**作者**: Danning Zhang, Yijing Lin, Shuhan Zhuang, Mengqi Huang, Shaojin Wu, Shancheng Fang 等 (7 人)
**来源**: cs.CV cs.AI
**匹配关键词**: Large Language Model, MLLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-modal image generation, particularly subject-driven customization, has garnered growing attention in recent years. Despite the rapid advancement of generative models, their evaluation remains largely lagging. Existing methods, whether embedding-based or Multi-modal Large Language Model (MLLM)-based, evaluate alignment with each modal condition in isolation, which contradicts the simultaneous condition alignment objective of multi-modal image generation, leading to poor consistency with human judgments. To address this challenge, we propose UFO, the first unified framework for omni-condition alignment simultaneous evaluation. Specifically, UFO introduces a novel Atomized Chain-of-Evaluation paradigm, \emph{i.e.}, it first decomposes omni-condition alignment into a sequential chain of fine-grained, disentangled Atomic Evaluation Units (AEUs), categorizes them into distinct modality-relevance classes, and then employs general or dedicated functional calls for accurate verification o

---

### [51] PRISMA-LLM: An Empirical Reporting Framework for AI-Assisted Systematic Reviews

**链接**: https://arxiv.org/abs/2609.11559
**作者**: Miguel Zabaleta, Baihan Lin
**来源**: cs.SE cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) and AI-enabled software increasingly participate in systematic-review decisions, yet the information needed to audit these workflows is reported inconsistently. We analyze SciLitBench, a corpus of 888 review-automation papers with 14,726 annotations, to characterize changes in methods, review-stage use, evaluation and reported limitations. Automation has shifted toward LLM- and software-facing workflows, including stages that can alter the evidence base. Since 2023, 38.0% of software/product papers reported no evaluation, compared with 9.3% of LLM papers. Reporting coverage increased with LLM workflow complexity, yet 52% of positive-only LLM evaluations still reported an unmet reliability or performance requirement. From these patterns, we introduce PRISMA-LLM, an empirically grounded framework separating implementation disclosure from consequence-sensitive evaluation and limitation reporting.

---

### [52] CoHyDE: Iterative Co-Training of LLM Rewriter & Dense Encoder for Tool Retrieval

**链接**: https://arxiv.org/abs/2605.29271
**作者**: Vaishali Senthil, Ashutosh Hathidara, Sebastian Schreiber
**来源**: cs.AI cs.IR cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [53] SimSkill: A Self-Evolving LLM Agent for Skill and Knowledge Accumulation in Traffic Simulation

**链接**: https://arxiv.org/abs/2609.03753
**作者**: Qi Liu, Qinzheng Wang, Can Li, Yiming Bie, Wanjing Ma
**来源**: cs.AI cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [54] When Auditors Fabricate: Batch-Size Degradation and Confident Hallucination in LLM Detection of Planted Document Contamination

**链接**: https://arxiv.org/abs/2609.09696
**作者**: Karan Parekh, Sanjana Pendyala Ravinder, Sana Mhapsekar, Medina Maloku
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [55] Demystifying the Privacy-Utility Trade-off in LLM Interactions

**链接**: https://arxiv.org/abs/2609.10992
**作者**: Zhenhua Liu, Zhanxu Xie, Junjie Yu, Tong Zhu, Lijun Li, Wenliang Chen
**来源**: cs.AI cs.CR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [56] “Triggering autonomy, not just automation”: Design implications for LLM -based home automation assistants for people with intellectual disability

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S1071581926002132&hl=zh-CN&sa=X&d=5701584399145355644&ei=bu6nauWvHcOuieoP-djIkQ0&scisig=AIVdB-xfaHC9adf0Lc2cOTocPZjj&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=9&folt=kw-top
**作者**: D Morra, M Andrao, Q Ai, M Mores, M Matera… - International Journal of …, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> It explores whether an LLM -powered conversational interface can support individuals with ID in shaping smart home behaviors through natural … We conclude by outlining design opportunities and broader implications that can inform

---

### [57] Closed-Loop Bayesian Molecular Inverse Design with Semantic LLM Surrogates

**链接**: https://arxiv.org/abs/2608.22967
**作者**: Yaoyao Xu, Xinjian Zhao, Xiaozhuang Song, Lei Bai, Tianshu Yu
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [58] ORQA: An Occupation-Realistic Question and Answer Framework for LLM Professional Knowledge

**链接**: https://arxiv.org/abs/2609.12366
**作者**: Shreyas Krishnan, Serina Chang, Abhishek Nagaraj
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We present ORQA, a method for testing occupation-level knowledge in large language models. Prior methods either map abstract LLM skills to occupations via task definitions or utilize expert knowledge which is difficult to obtain at scale and expensive. ORQA complements both of these methods by connecting O*NET occupations to trusted occupation-specific websites (such as regulatory agencies, licensing bodies, professional organizations, and government publications) and converting these into source-traceable question-answer pairs. A combination of an automated pipeline and human review produces a set of high quality questions about occupations. The question set created via our method covers 116 occupations from all 21 major groups in the SOC, with 480 questions sourced from 187 different websites. Each question is designed to probe a real-world skill question that is relevant to the occupation in question. We test 15 state-of-the-art frontier and open-weight models via this method. Claud

---

### [59] Exploring Multiple Sources to Enhance LLM Effectiveness in Non-Functional Requirements Elicitation

**链接**: https://scholar.google.com/scholar_url?url=https://ieeexplore.ieee.org/abstract/document/11676657/&hl=zh-CN&sa=X&d=4094351380279837825&ei=bu6nauWvHcOuieoP-djIkQ0&scisig=AIVdB-wSHGMh_UNH35tXORENyyNx&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=7&folt=kw-top
**作者**: C Almeida, S Freire, M Mendonça, JC Leite - 2026 IEEE 34th International …, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> This paper’s goal is to investigate whether combining multiple information sources can improve LLM -based NFR elicitation. We augment a … Future work will explore LLM -generated traceability data, quality attribute classification, and persona

---

### [60] U-Lens: Supporting User Uncertainty Management in Long-Form LLM Responses

**链接**: https://arxiv.org/abs/2607.10604
**作者**: Yu Mei, Qingyue Zhuang, Jie Cai, Chang Liu, Zhi Zheng, Zhoutong Ye 等 (8 人)
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [61] Whitewashing Hate, Smearing Harmless Content: Annotator-Style Rebuttal Attacks on LLM-Based Moderation

**链接**: https://arxiv.org/abs/2608.22230
**作者**: Junyu Lu, Kaiyuan Liu, Kaichun Wang, Jingyi Kang, Deyi Ji, Hailong Zhang 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [62] LLM-BabyBench: Can Language Models Plan in Worlds They Can Simulate?

**链接**: https://arxiv.org/abs/2505.12135
**作者**: Idriss Malek, Omar Choukrani, Daniil Orel, Anh Duy Le Dinh, Zhuohan Xie, Zangir Iklassov 等 (8 人)
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [63] LLM Compression by Block Removal with Constrained Binary Optimization

**链接**: https://arxiv.org/abs/2602.00161
**作者**: David Jansen, Roman Rausch, Ali Hashemi, David Montero, Rom\'an Or\'us
**来源**: cs.LG cs.AI cs.CL quant-ph
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [64] Diffract: Spectral View of LLM Domain Adaptation

**链接**: https://arxiv.org/abs/2608.10850
**作者**: Nikita Borodin and Maria Krylova and Artem Zabolotnyi and Dmitry Aspisov and Egor Shikov and Nikita Tyuplyaev and Oleg Travkin and Roman Alferov and Dmitry Vinichenko
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [65] From Collaboration to Capability: Internalizing Routed LLM Experts into Compact Reasoners

**链接**: https://arxiv.org/abs/2609.12578
**作者**: Frank Nie, Shuyao Wang, Ethan B. Liu
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A compact controller can coordinate stronger experts by selecting whom to consult, formulating requests, and integrating their responses. We study whether learning from both the controller's decisions and the experts' reasoning and code improves its generation after expert removal. We introduce \textsc{Rivet} for \emph{collaboration internalization}: expert-augmented reinforcement learning applies a shared outcome signal to controller decisions and returned expert spans, and verified trajectory internalization consolidates complete successful interactions through format-aware supervised training. The deployed controller generates reasoning, code, and interaction structure with local Python execution and no external LLM. Across seven competition-mathematics benchmarks, RIVET-1.7B and RIVET-4B achieve average accuracies of $28.25\%$ and $44.16\%$; Stage~II improves RIVET-4B's accuracy after expert removal by $6.49$ points, and GPQA-Diamond results provide evidence of generalization to sc

---

### [66] Is Multilingual LLM Watermarking Truly Multilingual? Scaling Robustness to 100+ Languages via Back-Translation

**链接**: https://arxiv.org/abs/2510.18019
**作者**: Asim Mohamed and Martin Gubri
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [67] Separating Engineering Reasoning from DEXPI Serialization in LLM-Based Greenfield Surface-Process Design: A Three-Case Study for Underground Gas Storage

**链接**: https://arxiv.org/abs/2609.12656
**作者**: Qingchuan Zhu, Shuyue Tong, Pengju Ren
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models can produce engineering descriptions and structured process representations, but standards-level serialization can substantially increase the generation burden. This diagnostic study examines whether separating engineering reasoning from Data Exchange in the Process Industry (DEXPI) serialization changes where representation and engineering failures occur in constrained greenfield surface-process design for underground gas storage. We compare Direct DEXPI generation with generation of a lightweight Engineering Intermediate Representation (IR) on three cases: single-pressure injection, withdrawal and export, and dual-pressure injection. All six conditions use one fixed model snapshot, qwen3.8-max-0902, with one completed hosted generation per condition. Direct outputs are XSD-valid in 2 of 3 cases, while all 3 Engineering IR outputs are structurally valid under a minimal validator. Direct prompt inputs contain approximately 121.8k-121.9k tokens, compared with 617-6

---

### [68] An LLM -Based Multi-Agent System for Multilingual Product Review Analysis

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S0957417426032926&hl=zh-CN&sa=X&d=3420055527160844083&ei=bu6nauWvHcOuieoP-djIkQ0&scisig=AIVdB-zYlzE_wE8zEa9ppieo4C_N&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=0&folt=kw-top
**作者**: HR Hasan, K Salah, A Musamih, R Islayem, A Mayyas… - Expert Systems with …, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> In this section, we review prior work on LLM -supported review analysis, visualization, and structured e-commerce knowledge extraction. The review focuses on studies relevant to review generation and summarization, sentiment classification

---

### [69] Debiasing as a Measurement Intervention: Calibrated Ties and Resolution Loss in LLM-as-a-Judge Evaluation

**链接**: https://arxiv.org/abs/2609.12439
**作者**: Liang Zhao and Yong Wang and Jiangzhe Chen
**来源**: cs.DL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-as-a-judge protocols are commonly debiased by instructing judges to ignore presentation cues such as citation formatting, source labels, and evidence-display style. We show that this intervention can suppress bias while damaging the resolution of the measurement instrument. We introduce TraceJudgeBench, a diagnostic benchmark for auditing citation-like artifacts in RAG and agent-workflow evaluation, covering content-equivalent pairs, citation ablations, correctness conflicts, human-validated soft and moderate quality gaps, prompt-strength ladders, decoupled judging, and a controlled workflow-ranking probe. Across GPT-5.5, Claude Sonnet 4.6, and DeepSeek V4-Flash, stronger anti-citation prompts reduce worse-cited wins from up to 50.5% to 0%; yet some operating points already convert validated moderate-gap decisions into Tie before the strict stress-test endpoint, while correctness-conflict accuracy remains at or above 93.0%. A second, 50-pair FinQA moderate-gap construction reproduc

---

### [70] MedRoundsQA: A Persona and Difficulty Aware Evaluation for Multi-Turn Medical Consultations

**链接**: https://arxiv.org/abs/2609.12851
**作者**: Youssef Mohamed, Ahmed Heakl, Qinrong Cui, Junhong Liang, Rafiq Ali, Bdour Babillie 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Medical benchmarks are dominated by single-turn, multiple-choice clinical cases that poorly reflect real consultations. Practically, clinicians elicit evidence interactively and patient communication varies widely. We introduce MedRoundsQA, a multi-turn diagnostic benchmark derived from 1,387 board-exam cases across 17 specialties. Each case is converted into a structured 24-slot clinical record, and then instantiated as controlled doctor-patient dual-agent dialogues under varying patient personas, with the underlying clinical content held fixed. We further classify cases by difficulty using model-based uncertainty to enable easy-to-hard analysis. Evaluations of fifteen LLM doctor agents show that (i) moving from a single-turn diagnosis on the standardized records to multi-turn consultations causes large degradations of roughly 13-39 points; (ii) more turns reliably improves question relevance, but diagnostic accuracy exhibits diminishing returns and typically plateaus after 6-12 turns

---

### [71] Residual Vector-based Reconstruction as Long-Context Recall Regardless of Context Window Size

**链接**: https://arxiv.org/abs/2609.12686
**作者**: MyungHoon Ryu, XinYu Piao, Jong-Kook Kim
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) process long contexts, including long documents and lengthy conversations, but face token-level memory usage that increases proportionally to input length. Although model optimization and lossy prompt compression are widely used, these methods still fail to solve the long-context recall problem beyond pretrained and size-constrained context windows. This paper proposes a long-context recall method that maintains near-constant GPU memory usage as context length increases, without additional training. The main idea is to reconstruct facts using parameter activations in the LLM's feed-forward layers, which store residual vectors representing facts from the source document. Utilizing residual vectors allows the LLM to deterministically reconstruct query relevant facts without referencing the original document, preserving high fidelity and reducing memory usage without fine-tuning weights. Experimental results show that the proposed method enables answering sing

---

### [72] DuplexDrama: A Synthesized Dialogue Dataset with Scenarios, Full-Duplex Behaviors, Expressive Speech, and Sound Events

**链接**: https://arxiv.org/abs/2609.12872
**作者**: Qingxiang Guo, Wenke Fan, Shuofeng Zhao, Dawei Yang, Zhiyang Zhou, Yingxin Shang 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We present DuplexDrama, the first synthesized spoken dialogue dataset that simultaneously covers four dimensions: (i) complete persona and scenario settings; (ii) three full-duplex behaviors (interruption, backchannel, incomplete); (iii) expressive speech with persona-aligned emotion labels; and (iv) script-aware sound events. DuplexDrama is built via a 4-stage pipeline; quality validation on both scripts and synthesized audio confirms its quality. We have produced more than 2,000 hours audio data with a 64-voice timbre pool spanning 13 personas and 5 age buckets; 3.8% of all turns carry at least one full-duplex behavior. This data has been validated through internal full-duplex model training. We will release a curated subset of 6,400 bilingual dialogues (800 h, Chinese ~500 h + English ~300 h) to advance full-duplex spoken dialogue model research. Data samples are available at our demo page and LLM-judge evaluation prompts will be released with the dataset.

---

### [73] Detecting and Explaining Fake News Short Videos with Multimodal Content and Real-World Evidence

**链接**: https://arxiv.org/abs/2609.12678
**作者**: Yifeng Luo, Yupeng Li, Ming Tang, Jianxiong Guo, Liang Lan
**来源**: cs.CV cs.MM
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Short-video platforms have become a primary news source for the public, which has also enabled the widespread dissemination of fake news videos. We study the task of fake news video detection and explanation (FNVDE). Existing methods face two critical limitations. First, commonly used frame selection strategies may omit veracity-relevant cues or provide insufficient temporal context for understanding news videos. Second, prior methods neglect either multimodal understanding or evidence retrieval. To address these limitations, we propose NVKE-CEI, a unified system that integrates a news video keyframes extraction method (NVKE) and an FNVDE framework leveraging both content and evidence information (CEI). NVKE selects keyframes based on chronological changes in combined visual and OCR-text similarity. CEI employs two specialized LLM-based fact checkers (content-based and evidence-based) whose outputs are fused by a lightweight judge model. Extensive experiments show that NVKE-CEI outperf

---

### [74] Implicit Personality Representations in Humans and LLMs

**链接**: https://arxiv.org/abs/2609.12704
**作者**: Yilin Geng, Omri Abend, Eduard Hovy, Lea Frermann
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A century of psychology has found that the trait words people use to describe one another vary, but the relational structure among those traits, which ones go together and which oppose, is strikingly consistent across raters and cultures. We test whether the LLM (Qwen 2.5-7B-Instruct) reproduces this structure in its internal trait representations. From millions of crowd-sourced personality ratings of fictional characters, we build a human implicit-personality matrix over hundreds of traits; from contrastive model activations, we build a matching matrix over the same traits. The two relational structures align strongly (Mantel r = 0.77), and the agreement holds trait by trait as well as in aggregate. Two dominant axes of the model's trait representations recover the social and intellectual dimensions long known to organize human personality impressions, social warmth and intellectual competence. On held-out dialogue, projecting model activations onto these directions yields personality

---

### [75] Scaling Clinical Judgment to Evaluate Medical AI

**链接**: https://arxiv.org/abs/2609.12822
**作者**: Thomas A. Buckley, Zahir Kanjee, Peter G. Brodeur, Byron Crowe, Anthony M. Pettinato, Aashna P. Shah 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Blinded physician evaluation has been considered by many to be the gold standard for assessing clinical reasoning in large language models (LLMs). This is difficult to scale; thus, prior studies typically rely on small physician panels, often from a single institution or specialty, which both limits the scientific questions investigated and makes it unclear whether findings would be reproduced with a different set of evaluators. To more rigorously and scalably study clinical reasoning in AI models, here we introduce PrecepTron, an LLM fine-tuned for physician-level evaluation of open-ended responses. PrecepTron was trained using low-rank adaptation (LoRA) of a 32-billion-parameter model on a small number of physician examples. We also release GRAND-ROUNDS, a new large-scale physician-annotated benchmark of 9,217 scores by 11 physicians across seven studies. We show that frontier LLMs in typical "LLM-as-a-judge" approaches often disagree with physicians and with each other, but fine-tun

---

### [76] Sampling via Decision-Flow: Training-Free Extraction of Improved Latent Reasoning Paths in Large Language Models

**链接**: https://arxiv.org/abs/2609.12317
**作者**: Zhendong Mi, Shaoyi Huang
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A central question in LLM reasoning is whether reinforcement learning (RL) instills genuinely new capabilities or merely reshapes how existing knowledge is expressed during inference. Building on the distribution-sharpening hypothesis, which holds that RL reallocates probability mass toward high-reward trajectories already latent in base models, we ask: can we unlock those latent paths without costly RL fine-tuning? We present Decision-Flow Sampling (DF-Sample), a training-free, data-free inference-time framework that constructs a hierarchical reasoning tree, scores terminal nodes for quality, and back-propagates utilities to inform each intermediate branching decision. Unlike conventional sampling strategies that make purely local step-wise choices, DF-Sample performs explicit global trajectory evaluation before committing to a path, recovering high-quality but low-probability reasoning chains that standard decoding overlooks. On GPQA, DF-Sample achieves 45.6% accuracy, surpassing pow

---

### [77] Retrieval-Augmented Generation for Scientific Code Understanding

**链接**: https://arxiv.org/abs/2609.12190
**作者**: Aaron Nobile, Andreas Adelmann, Mohsen Sadr
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models have become central to modern coding assistants, but state-of-the-art systems such as Claude Code or Codex rely on very large, cloud-hosted models with significant computational cost and data-privacy implications. This work investigates whether a useful, fully local coding agent can be built around small open-source models by shifting the computational burden away from inference. We develop a Retrieval-Augmented Generation (RAG) system for scientific code understanding that strictly separates an expensive offline ingestion stage parsing, structural graph construction, LLM-generated entity explanations, and embedding from a lightweight online answering stage. The system is evaluated on a 100-question benchmark spanning eleven categories over the IPPL scientific codebase written in C++, with answers scored by an independent frontier model as the judge. Across seven answering models, we find that model family and retrieval quality matter more than parameter count, i.

---

### [78] Autonomous Research for Open-Ended Problems: A Case Study on Telecom Ticket Retrieval

**链接**: https://arxiv.org/abs/2609.13073
**作者**: Junghyun Min, Huseyin Uzunalioglu, Mohamed Trabelsi
**来源**: cs.AI cs.IR cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent breakthroughs in LLM-based systems and their abilities in problem solving and coding have allowed progress in the AI for Science paradigm, potentially replacing human roles in machine learning (ML) research. However, while several frameworks of fully autonomous end-to-end ML research have been proposed, successful implementations of them are often limited to problems with narrow search spaces, like language modeling or biomedical ML benchmarks. In this paper, we explore how autonomous research can be adapted to solve open-ended, industry-grade ML problems, by considering a case study: telecom ticket retrieval, an open-ended task with degrees of freedom in representation, architecture, and training data generation. We discover that autonomous research for open-ended problems with commercial and open-source agents shows both promise and limitations: while autonomous research can excel in narrow hyperparameter optimization, it lacks human-like intuition and creativity and requires 

---

### [79] I Am AdMan: A Pipeline for Automatic Generation of Personalized Advertising Imagery

**链接**: https://arxiv.org/abs/2609.12694
**作者**: Victor Kolominsky-Rabas, Leopold M\"uller, Claudius Budcke, Niklas K\"uhl
**来源**: cs.AI cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Personalized marketing can increase customer engagement, satisfaction, and conversion. While existing personalization approaches have become effective at matching the right product to the right customer, the visual representation of advertisements remains generic and only weakly tailored to the individual. Prior research shows that generative artificial intelligence can improve the creation of personalized advertisements, particularly for text, and that image generation models can support scalable advertisement production. However, little research has examined how detailed customer information can be systematically translated into fully AI-generated, personalized advertising imagery at scale on a technical level. To address this gap, we propose AdMan, a multi-agent pipeline that transforms customer data into personas, generates personalized advertisement images conditioned on product reference images, and applies an LLM-based judge agent for automated quality control. We implement the 

---

### [80] One Skill Does Not Fit All: Automatic Discovery and Taxonomy-Guided Routing of Frame-Selection Skills for Long-Video Question Answering

**链接**: https://arxiv.org/abs/2609.12517
**作者**: Jian Hu, Zixu Cheng, Da Li, Wei Li, Ziquan Liu, Shaogang Gong
**来源**: cs.CV
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-Video Question Answering (LVQA) requires locating decisive evidence in hour-scale videos under a limited frame budget. Most training-free methods apply the same frame-selection strategy to all questions, despite substantial variation in the evidence required by different question types. Our analysis shows that the relative effectiveness of frame-selection strategies varies across semantic categories and benchmarks, motivating adaptive evidence acquisition. In this paper, we introduce AutoSkill, a source-supervised framework for automatically discovering and routing executable frame-selection skills. Starting from a small labelled source pool, LLM agents iteratively propose, implement, evaluate, and refine candidate skills. For a target benchmark, AutoSkill uses only unlabelled question and option text to induce a shared semantic taxonomy, rewrite labelled source examples into the target style, and estimate a category-to-skill mapping. Neither target videos nor target answers are u

---

### [81] TripPattern: A Pattern-based Text Watermarking Method for Large Language Models

**链接**: https://arxiv.org/abs/2609.12472
**作者**: Sangjun Moon, Dasom Choi, Jingun Kwon, Hidetaka Kamigaito, Taro Watanabe, Manabu Okumura
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Text watermarking techniques have gained significant attention for identifying machine-generated text and mitigating risks from large language models (LLMs). Existing methods typically divide an LLM's vocabulary into green and red tokens, but encouraging generation toward green tokens can reduce text quality and naturalness. To address this, we propose TripPattern, a watermarking framework that formulates text watermarking as a pattern-based matching task using three vocabulary partitions. TripPattern divides the vocabulary into one neutral group and two pattern groups. During generation, the model alternates token selection between the two pattern groups to embed detectable patterns, while neutral tokens are selected independently to improve flexibility and preserve naturalness. For detection, TripPattern uses pattern-based statistical tests that provide interpretable p-values by measuring how often adjacent tokens alternate between the pattern groups. Theoretical analysis and empiric

---

### [82] Direct Preference Density Alignment for Conversational Audio Equalization

**链接**: https://arxiv.org/abs/2609.12607
**作者**: Ioannis Stylianou, Sven Ewan Shepstone, Jon Francombe, Pablo Martinez Nuevo, Zheng-Hua Tan
**来源**: cs.SD cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Model alignment typically relies on learned proxy reward models, which significantly increase the memory footprint during training and are notoriously prone to instability and reward hacking. While offline methods like Direct Preference Optimization (DPO) bypass the reward model, they lose the ability to perform online exploration. If no optimization constraints are applied, this can lead to format collapse in bounded, continuous spaces. To resolve this, we propose Direct Preference Density Alignment: An alternative framework that removes the need for a learned proxy reward model while strictly preserving the benefits of online reinforcement learning. We leverage large-scale user data (approximately 90,000 samples) to construct non-parametric preference density maps, establishing an empirical reward surface. In addition to removing the reward model, Direct Preference Density Alignment enables the combination of the online structural grounding of Group Relative Policy Opt

---

### [83] Earth-Agent-Pro: Towards Real-World Full-Chain Earth Observation with Agents

**链接**: https://arxiv.org/abs/2609.12533
**作者**: Zhutao Lv, Chenhao Dang, Yi Feng, Yanpei Gong, Xiaolei Wang, Junyan Ye 等 (8 人)
**来源**: cs.CV cs.AI cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Real-world Earth observation (EO) agents must translate high-level scientific questions into executable workflows to acquire observations, prepare data, perform domain computations, and derive conclusions from runtime evidence. Existing EO agents typically start from supplied observations, while benchmarks typically provide prepared inputs or candidate answers, leaving full-chain open-world EO execution largely untested. We present Earth-Agent-Pro, an execution-adaptive Plan-and-Execute framework using expert-authored skills to constrain planning and runtime tool use. Workflow-centered structured memory records planned steps, accepted evidence, and their dependencies, enabling repair of only the affected workflow suffix when runtime evidence invalidates a step. Separate large language model adapters use sequence-level supervised fine-tuning for planner workflow composition and node-level group relative policy optimization with locally verifiable rewards for executor tool-argument groun

---

### [84] Can LLMs in Draft-Verify-Revise Pipelines Resolve Deictic Ambiguity?

**链接**: https://arxiv.org/abs/2609.12162
**作者**: Obinna I. Ekekezie
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Draft-verify-revise is a common LLM orchestration pattern for scaling inference-time compute. One LLM drafts, a second critiques the draft and provides feedback, and a third uses that feedback to revise the draft into the final output. As context cascades between stages, LLMs at different stages can resolve a context-dependent expression such as "previous" differently. When that happens, the expression undergoes a deictic shift, a change in what it refers to. This phenomenon was studied with a synthetic dataset of 10 base examples, each rendered in three conditions. Holding the shared components constant, the conditions varied whether the draft stage LLM (the assistant) or the verify stage LLM (the grader) resolved the expression correctly, and how much independent reasoning the revise stage LLM (the meta-evaluator) needed to determine which reading was correct. Six models from three providers were tested across 21 reasoning effort configurations using e-values for sequential testing, 

---

### [85] Anchoring Clinical Events in Time: UID-Preserving Multimodal Reconstruction and Source-Grounded Adjudication

**链接**: https://arxiv.org/abs/2609.13062
**作者**: Sayantan Kumar, Nicolas Grimaldi, Jack Cummins, Jeremy C. Weiss
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Clinical timelines support treatment-window analysis and leakage-free modeling, but discharge summaries often obscure chronology and structured EHR tables describe only part of the patient course. We present a UID-preserving framework that links each narrative event occurrence to its source span and retains that identity through text-only estimation, structured-evidence retrieval, timestamped source-row grounding, and joint revision. We also present GAVEL, an LLM judge that compares two UID-aligned timelines against the narrative and structured record, to augment prior matching and temporal assessments. Across six open-weight models and 40 mixed-critical-care summaries, the GLM 5.2 multimodal revision, as compared to its text-only variant, improved temporal agreement without reducing event recovery and performed competitively with clinician annotations, while other model revisions showed smaller gains and lower overall performance. Ablations showed that UIDs primarily preserve event re

---

### [86] Navigating Schema Drift: Orchestrating Agents and Schema Discovery for Robust, Domain-Specific Knowledge Graph Question Answering

**链接**: https://scholar.google.com/scholar_url?url=https://ebooks.iospress.nl/volumearticle/80581&hl=zh-CN&sa=X&d=14676000767924410158&ei=bu6naorgKea6ieoPp62dCQ&scisig=AIVdB-z0ymyVkHTLIZ_vHhObj1ma&oi=scholaralrt&hist=F21tmVgAAAAJ:14380004662027926800:AIVdB-wBlF6h20BcrGbCh9DPQSnW&html=&pos=3&folt=kw-top
**作者**: A Diettrich, D Friedenberger, A Both - Bridging the Gap Between Curated and …, 2026
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> Knowledge Graph Question Answering (KGQA) over Large Language Models (LLMs) increasingly translates natural- language questions … A multi - model Quorum extension over heterogeneous LLM families further increases reliability

---

### [87] Confidence-Gated Transductive Test Generation for Code Reranking

**链接**: https://arxiv.org/abs/2609.12489
**作者**: Sungjae Lee, Youngsik Yoon, Seockbean Song, Siwei Wang, Wei Chen, Jungseul Ok
**来源**: cs.AI cs.CL cs.SE
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Test case synthesis is crucial for evaluating and ranking programs generated by large language models (LLMs). However, constructing high-quality test cases remains challenging because reliable expected outputs are often difficult to obtain. We propose Confidence-Gated Transductive Test Generation (CoTT), which first uses an efficient inductive procedure and invokes transductive generation only when inductive confidence is low. This adaptive design improves output reliability while allocating extra computation only when needed. On code reranking benchmarks, CoTT outperforms prior baselines across the reported metrics while reducing cost relative to applying transductive generation to every input. These results show that confidence-based allocation of test-time computation provides a favorable efficiency-effectiveness trade-off with a single efficient LLM.

---

### [88] A Graph-Based Approach for Mapping Kernel-Level Telemetry to MITRE ATT&CK

**链接**: https://arxiv.org/abs/2609.12841
**作者**: Matteo Lupinacci, Luigi Arena, Francesco Blefari, Angelo Furfaro
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Mapping observed system behavior to standardized frameworks like MITRE ATT&CK is essential for threat-informed defense, but remains largely manual. Existing automated methods depend on Cyber Threat Intelligence reports, which offer only retrospective accounts of attacks. Low-level telemetry, i.e. kernel-level system calls, instead provides evidence of adversary behavior, yet its volume and complexity have limited its use for automated mapping. We present a methodology that collects kernel-level events via eBPF, correlates attacker commands into a provenance graph, and derives compact graph representations suitable for LLM-based reasoning. These representations are mapped to the MITRE ATT&CK framework using both pure LLM prompting and retrieval-augmented generation (RAG) grounded in the ATT&CK knowledge base, producing ranked technique candidates along with supporting rationales. We implement this methodology as an end-to-end pipeline, named Trace2ATT&CK and evaluate it on 347 Linux Ato

---

### [89] SWARM: A Multilingual Human-Annotated Dataset for Russian Propaganda Detection in Search Engine Results

**链接**: https://arxiv.org/abs/2609.12653
**作者**: Manuel Tonneau, Abhinav Dubey, Farhan Shaikh, Ilaria Vitulano, Martha Stolze, Hale Dedeoglu 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Russian state propaganda spreads across many languages and online spaces. Yet, most computational work examines only one such space, usually social media, in one or two languages, and analyses sources rather than content. We introduce SWARM (Search-Web documents Annotated for Russian propaganda, Multilingual), a dataset of 2,183 search engine results across nine languages and diverse web domains (e.g., news, blogs, government sites), each annotated by trained coders for whether it supports a recurring Russian propaganda narrative. We benchmark a source-based blocklist, supervised classifiers, and zero-shot LLMs against these labels. The blocklist misses most propaganda-supporting documents, because such content is not confined to flagged "propaganda" outlets but also appears on mainstream ones. Content-level analysis helps, though how much depends on the model: the strongest LLM reaches a positive-class F1 of 0.73, whereas the supervised classifiers reach only about 0.5, with the small

---

### [90] Do LLMs Trust the Accuser or the Accusation? Measuring Belief Shifts in Werewolf

**链接**: https://arxiv.org/abs/2609.12446
**作者**: Yu-Yu Yang, Ti-Rong Wu, Hung Guei, Hsing-Yu Chen, I-Chen Wu
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Social-deduction games such as Werewolf are increasingly used to evaluate LLM agents, but existing evaluations often rely on final game outcomes. We propose a belief-shift evaluation benchmark in Werewolf for analyzing communication skills through belief updating. Using LLM-played games, we annotate suspicion and accusation messages and measure how an observing village-side model's beliefs change after each message. We evaluate 40 open-weight LLM configurations on 1,224 annotated messages. Our results show that larger models better distinguish true wolves from villagers based on game history, but accusations still strongly influence their beliefs. Models become more suspicious of the accused target and less suspicious of the accuser, especially when the accuser is trusted, even if the accuser is wolf-aligned. Larger models better resist accusations from accusers they already distrust. Overall, our findings suggest that current open-weight LLMs up to 120B parameters still struggle to in

---

### [91] The House with a Million Windows: Interactive Fiction for Narrative Restorying

**链接**: https://arxiv.org/abs/2609.12537
**作者**: Cody Kommers, Sarah G Immel, Drew Hemment, Mina Lee
**来源**: cs.CL cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> AI-assisted writing can flatten meaning in human storytelling, enabling the production of homogeneous outputs without the intentional effort and sense-making writing entails. To address this challenge, we present The House with a Million Windows (HWAMW), an LLM-based interactive fiction system designed to help users explore both the breadth and depth of potential meanings within their personal stories -- drawing on a psychological paradigm called the restorying intervention. In HWAMW, users play through a text-based narrative in which they tell a story, then encounter a set of LLM-generated "windows" reframing it according to different literary styles. Empirical evidence shows that HWAMW increases users' sense of narrative identity, while an expert review explores how this effect is achieved. Our findings suggest that HWAMW facilitates restorying and offers a valuable paradigm for AI-assisted writing, wherein LLMs do not tell our stories but rather help us see greater potential in the 

---

### [92] GUIDE: Generative Utility Inference and Decision Engine

**链接**: https://arxiv.org/abs/2609.12137
**作者**: Anagha Tiwari, Alexander G. Gray, Nick Feamster, Brian Jabarian, Alex Imas, Alex Kale
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Measuring the preferences of human users remains a fundamental challenge of AI alignment. Existing elicitation approaches struggle to efficiently discover multidimensional preferences or accurately ground these inferences in domain knowledge. To address this, we introduce GUIDE, an LLM-driven elicitation architecture that infers user preferences through conversations by combining Bayesian adaptive sampling for question selection and symbolic representation learning to initialize domain-specific preference models. GUIDE generalizes adaptive sampling to diverse elicitation questions through an extensible type system of transforms on a parameterized preference state. GUIDE produces domain-specific preference representations through an initialization process using symbolic rule-based learning to capture world knowledge and set priors over preference dimensions grounded in data about decision alternatives. The architecture provides observability and steerability to facilitate deployment and

---

### [93] LifeFuse-Mem: Lifecycle-Aware State Fusion Against Temporary Overwriting for Long-Term Memory

**链接**: https://arxiv.org/abs/2609.12436
**作者**: Hanyu Zhao, Yuqian Feng, Zhenyu Song, Yuanchao Cheng, Yance Jiao, Tengfei Pan 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-running LLM agents require memory mechanisms that maintain coherent internal states across interactions. We study a lifecycle-labeled memory setting in which write episodes provide lifecycle metadata during training, and phase-aware readout is used during evaluation. This setting reflects the need to distinguish information that should remain influential across future interactions from information that should affect only the current context. A mismatch between these lifecycles can cause temporary information to overwrite durable knowledge, leading to behavioral drift in persistent agents. Within this setting, we introduce \textbf{LifeFuse-Mem}, a lifecycle-aware neural memory framework that separates information according to its temporal commitment. LifeFuse-Mem uses dedicated memory components and lifecycle-aware updates to allow stable and transient knowledge to evolve locally without converting temporary context into durable state. On the controlled anti-overwrite benchmark, Li

---

### [94] CueMem: Cue-Guided Context Reconstruction for Long-Term Conversational Memory

**链接**: https://arxiv.org/abs/2609.12354
**作者**: Changjian Wang, Rongzhen Li, Weili Guan, Shuming Shi, Quan Lu, Ning Jiang
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-term conversational agents must answer user queries by recalling information from extended dialogue histories, yet directly using the full history is costly and often unreliable, while compressed memory units may lose fine-grained evidence needed for question answering. Motivated by the reconstructive view of autobiographical memory, we propose CueMem, a cue-guided framework that treats extracted memory records as retrieval cues rather than self-contained evidence and reconstructs query-relevant dialogue context from their source turns. During memory construction, CueMem extracts fine-grained memory cues from dialogue turns and links each cue to its source turn. At query time, it retrieves query-relevant cues, maps them to source-turn anchors, and expands from these anchors over a turn graph that captures temporal proximity and semantic relatedness, reconstructing a compact evidence context from the original dialogue for LLM answer generation. Experiments on LoCoMo and LongMemEval

---

### [95] Agentic TCAD Calibration Workflow for Oxide Semiconductor Transistors

**链接**: https://arxiv.org/abs/2609.12184
**作者**: Gyujun Jeong, Junmo Lee, Sungwon Cho, Woohyun Hwang, Kwangyou Seo, Suhwan Lim 等 (10 人)
**来源**: physics.ins-det cs.AI cs.LG physics.app-ph
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Experimental TCAD calibration is essential for predictive technology modeling of emerging oxide semiconductor transistors. However, it remains time-consuming and expert dependent because of model ambiguity. Multiple physical models and parameter sets can reproduce the same measured transfer characteristics, while local fitting alone cannot uniquely identify the underlying device physics. We present the first demonstration of an agentic TCAD calibration workflow for a fabricated bottom-gate In--W--O (BG-IWO) transistor. Starting from the measured transfer curve and device information, the workflow uses measurement--TCAD residuals and local sensitivity tests to select bounded parameter corrections or evaluate additional physical models, and accept only updates that improve device metrics. The LLM agent orchestrates the workflow, while Sentaurus governs the device physics. For the 2\%-W reference device, five agent-suggested updates yield a fixed calibrated model, reducing the multi-metri

---

### [96] GraphProfiler: Source-Linked Sensitive Attribute Inference via Personal Knowledge Graphs

**链接**: https://arxiv.org/abs/2609.12448
**作者**: Ahmed Sohair Khan, Estrid He, Chenglong Ma, Monica Wachowicz, Elham Naghizade
**来源**: cs.CL cs.CR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Sensitive attributes such as age, income, and occupation can be inferred from user-generated content by aggregating indirect cues across many ordinary posts. LLM-based profilers can perform this aggregation automatically and with high accuracy, which makes large-scale personal attribute inference a major privacy threat. Existing LLM-based profilers, however, offer limited insight into which specific posts, concepts, and relationships made an inference possible, which is key to targeted privacy mitigation, i.e., redacting or rewriting only the few posts that actually leak an attribute, rather than perturbing entire histories. We introduce GraphProfiler, an auditable LLM-based profiler that represents each user's post history as a source-linked personal knowledge graph where nodes and edges trace back to the originating post and resolves attribute predictions to cited graph records and source texts. GraphProfiler reaches 86.7% attack success rate on the eight-attribute SynthPAI benchmark

---

### [97] AMDKernelVault: Large-Scale Datasets and Agentic Training for AMD GPU Kernel Optimization

**链接**: https://arxiv.org/abs/2609.12471
**作者**: Ji Liu, Saptarshi Majumder, Yiqing Huang, Wenwen Ouyang, Umang Pandey, Zeping Li 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We introduce AMDKernelVault, an open HIP and Triton kernel corpus and training framework for recent AMD CDNA GPUs. Existing LLM-based kernel agents are largely CUDA/NVIDIA-centric and often depend on repeated frontier-LLM calls for generation, reflection, and optimization. To address this gap, we develop HIPKernelGen and TritonKernelGen, agent-driven pipelines that transform PyTorch references into HIP or Triton kernels, compile and validate candidates under ROCm, and latency-profile them on AMD hardware. The corpus contains 62,153 execution-verified HIP kernel samples, 2,377 production-grounded ROCm Libraries QA entries, and 39,893 Triton kernels. We further train Qwen3-8B with supervised fine-tuning and execution-aware reinforcement learning as a demonstration of the corpus's utility. Under fixed evaluation budgets, it achieves the highest correctness among the compared models on PyTorch-to-HIP (34.0% Pass@1), TritonBench-G (33.2% Corr@3), and ROCmBench (41.94% Corr@3), but does not 

---

### [98] Safe Visual Counterfactuals Can Make Multimodal LLMs Safer: A Visual Representation Editing Approach for MLLM Safety

**链接**: https://scholar.google.com/scholar_url?url=https://openreview.net/pdf%3Fid%3D63xBNXGjZO&hl=zh-CN&sa=X&d=6699715816059565423&ei=bu6narveL4-P6rQPucXD2Ac&scisig=AIVdB-xZdVZB7hIOaFFaT5PT02jQ&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIVdB-zriNRzHNJlpJSQpNhQEFvt&html=&pos=4&folt=kw-top
**作者**: P Jain, VCR Sairam, VN Balasubramanian - Women in Computer Vision workshop
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Multimodal Large Language Models (MLLMs) largely refuse a harmful text prompt, but can comply harmfully when paired with a semantically aligned image. We further study this behavior in Qwen2.5-VL-7B-Instruct and observe that replacing an aligned

---

### [99] The Challenges and the Potential of MLLM -based Psychological Examination Tools

**链接**: https://scholar.google.com/scholar_url?url=https://ieeexplore.ieee.org/abstract/document/11676796/&hl=zh-CN&sa=X&d=15588503786986092621&ei=bu6narveL4-P6rQPucXD2Ac&scisig=AIVdB-xO8rBUZJnaje7EOw9E0gH0&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIVdB-zriNRzHNJlpJSQpNhQEFvt&html=&pos=3&folt=kw-top
**作者**: H Joh, J Jung, SG Ryu, SH Sohn, U Oh - … on Information Reuse and Integration for …, 2026
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Ultimately, we suggest developing an MLLM powered screening tool for art-based psychological assessment that combines … CONCLUSION We propose SimriSketch, an online MLLM -based phychological examination tool with HTP test, and a user

---

### [100] What Did the MLLM Hear? Token-Level Spectro-Temporal Grounding for Audio MLLM Explainability

**链接**: https://arxiv.org/abs/2609.12663
**作者**: Lucia Cascone, Valeria Fraenza, Michele Nappi, Fabio Narducci, Benedetto Simone
**来源**: cs.SD cs.CV cs.LG
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Audio-based Multimodal Large Language Models (MLLMs) can generate detailed natural-language descriptions of complex acoustic scenes, yet it remains unclear which parts of the input audio support each generated token. This is particularly challenging because acoustic evidence is distributed across time and frequency, and concurrent sound events may overlap temporally while occupying different spectral regions. We introduce STAG, to our knowledge the first post-hoc framework for token-level spectro-temporal grounding of captions generated by audio-based MLLMs. STAG estimates the temporal support for each generated token using target-token-specific vocabulary projections of the encoded audio representations, measures frequency-band relevance through controlled spectral occlusion, and combines the two signals into a spectro-temporal relevance map. We evaluate STAG against ten post-hoc explanation methods across four grounding benchmarks, where it achieves the best event-localization perfor

---

### [101] EMMI: Edge Multi-Modal Intelligence for Communication-Efficient MLLM Inference via Fused Representation Compression

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2609.11058&hl=zh-CN&sa=X&d=8963110336959790011&ei=bu6narveL4-P6rQPucXD2Ac&scisig=AIVdB-yYldeiBybAhf1vivA0tOhQ&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIVdB-zriNRzHNJlpJSQpNhQEFvt&html=&pos=1&folt=kw-top
**作者**: M Mounesan, I Khan - arXiv preprint arXiv:2609.11058, 2026
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> where pθ(·) denotes the server-side projection module and ut i denotes the resulting MLLM -compatible representation. The MLLM processes ut i for multimodal reasoning, followed by a task-specific prediction head to generate the final inference

---

### [102] Mixture of Specialized Vision Experts: Unlocking Complementary Visual Insights for Faithful MLLM Reasoning

**链接**: https://scholar.google.com/scholar_url?url=https://link.springer.com/chapter/10.1007/978-3-032-37023-5_2&hl=zh-CN&sa=X&d=5783357685732230872&ei=bu6narveL4-P6rQPucXD2Ac&scisig=AIVdB-xNWp941QRuEkFnpUxUIygI&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIVdB-zriNRzHNJlpJSQpNhQEFvt&html=&pos=0&folt=kw-top
**作者**: Y Gao, L You, J Xie, C Wang, K Fu, J Liu 等 (9 人)
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> vision-language tasks, while achieving faithful MLLM reasoning remains a critical challenge: … explicitly routes hard samples from the anchor MLLM to the most visually-disparate auxiliary … Ultimately, MoSVE provides an advanced and efficient

---

### [103] 과학기술특화 MLLM 개발을위한복합문서기반학습데이터자동구축프레임워크

**链接**: https://scholar.google.com/scholar_url?url=https://www.earticle.net/Article/A491161&hl=zh-CN&sa=X&d=8186724480781793134&ei=bu6narveL4-P6rQPucXD2Ac&scisig=AIVdB-xnOaFBn9DT6SvDWrnTxb6u&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIVdB-zriNRzHNJlpJSQpNhQEFvt&html=&pos=5&folt=kw-top
**作者**: 박효빈， 장하윤， 김태섭， 정진욱， 최동걸 - 한국차세대컴퓨팅학회논문지, 2026
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> a robust foundation for high-quality, domain-specialized MLLM datasets. This approach drastically cuts data curation costs compared to manual workflows while ensuring logical consistency via KGs to advance MLLM performance. Experimental

---

### [104] MDF- MLLM : Deep Fusion Through Cross-Modal Feature Alignment for Fundoscopy Classification

**链接**: https://scholar.google.com/scholar_url?url=https://ieeexplore.ieee.org/abstract/document/11676712/&hl=zh-CN&sa=X&d=3766285908974707940&ei=bu6narveL4-P6rQPucXD2Ac&scisig=AIVdB-wNNo5D3L0zPMTPU-wnwCyP&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIVdB-zriNRzHNJlpJSQpNhQEFvt&html=&pos=2&folt=kw-top
**作者**: J Jordan, MA Lor, P Koulen, ML Shyu, SC Chen - 2026 IEEE International …, 2026
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> MDF- MLLM (Multi-Depth Fusion of MLLM ), a cross-… MLLM (LLaMA 3.2 11B Vision-Instruct) with appropriate reasoning capacity to assist ophthalmologists in medical imaging diagnostics. The MDF- MLLM architecture incorporates fusion

---

### [105] ReactHuman: A Physics-Grounded Benchmark for Human-Like Reactive Decision-Making in Embodied Multimodal LLMs

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2609.10895&hl=zh-CN&sa=X&d=12693777656500169283&ei=bu6narveL4-P6rQPucXD2Ac&scisig=AIVdB-wA8-BabgJGtxiJldrTCy4g&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIVdB-zriNRzHNJlpJSQpNhQEFvt&html=&pos=7&folt=kw-top
**作者**: Y Li, J You, M Xiong, Y Chen, Z Zhao, D Wu 等 (8 人)
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> We introduce ReactHuman, the first physics-grounded benchmark for human-like reactive decision-making, in which the evaluated MLLM acts as the brain of a simulated humanoid facing sudden household hazards; it spans 17 event families

---

### [106] VGEdit: Unlocking Video Generation Priors for Reasoning-Informed Image Editing

**链接**: https://scholar.google.com/scholar_url?url=https://link.springer.com/chapter/10.1007/978-3-032-37092-1_21&hl=zh-CN&sa=X&d=4217058450940242498&ei=bu6narveL4-P6rQPucXD2Ac&scisig=AIVdB-wxOZOWhXyiBTBW-jztYWaT&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIVdB-zriNRzHNJlpJSQpNhQEFvt&html=&pos=6&folt=kw-top
**作者**: H Lu, G Fang, X Ma, X Wang - European Conference on Computer Vision, 2026
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> We propose an instruction transfer mechanism that uses an MLLM to convert editing instructions into video-oriented descriptions, … We introduce an RL strategy that optimizes the video generation model with MLLM -based rewards over both

---

### [107] Table-MCR2TR: Merged-Cell-Aware Table Recognition via Reinforced Multimodal Language Models

**链接**: https://scholar.google.com/scholar_url?url=https://link.springer.com/chapter/10.1007/978-3-032-37020-4_10&hl=zh-CN&sa=X&d=11470204044085818205&ei=bu6narveL4-P6rQPucXD2Ac&scisig=AIVdB-yF8fwuteGOLVTW5OFFRrCK&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIVdB-zriNRzHNJlpJSQpNhQEFvt&html=&pos=9&folt=kw-top
**作者**: B Zhou, Z Zhu, F Gao, H Xing, Y Qu, Q Zheng 等 (8 人)
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> Regarding the influence on general MLLM ability, we observe that after 3-task SFT and M-CRL training, the model can no longer reliably follow general-purpose instructions and only responds as expected to the three prompts used during training

---

### [108] OpenVE-3M: A Large-Scale High-Quality Dataset for Instruction-Guided Video Editing Supplementary Material

**链接**: https://scholar.google.com/scholar_url?url=https://link.springer.com/chapter/10.1007/978-3-032-37627-5_33&hl=zh-CN&sa=X&d=5112976057126412370&ei=bu6narveL4-P6rQPucXD2Ac&scisig=AIVdB-wAtDQnv2k1MmF4HV0Pk7xh&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIVdB-zriNRzHNJlpJSQpNhQEFvt&html=&pos=8&folt=kw-top
**作者**: H He, J Wang, J Zhang, Z Xue, X Bu, Q Yang 等 (8 人)
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> main components: a MLLM , a Mixture-of-Experts (MoE) Connector, and a Diffusion Transformer (DiT). The MLLM processes both the video and the text instruction simultaneously. Unlike approaches that only use a text encoder for the

---

### [109] FRIST: FMRI Representation Informed Shared-space Training Improves EEG-only Individual-Finger BCI Decoding

**链接**: https://arxiv.org/abs/2609.12298
**作者**: Jintao Zhang, Yidan Ding, Joshua Kosnoff, Maxim Karrenbach, Hanwen Wang, Bin He
**来源**: cs.LG eess.SP
**匹配关键词**: EEG, BCI, Brain-Computer Interface, Motor Imagery
**相关性评分**: 10.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Finger-level motor decoding is important for naturalistic brain-computer interface (BCI) control, yet individual-finger decoding from scalp electroencephalography (EEG) remains challenging because finger representations are spatially close in the sensorimotor cortex and blurred by volume conduction. Leveraging the high spatial resolution of functional MRI (fMRI), we introduce fMRI Representation-Informed Shared-Space Training (FRIST), a two-stage EEG decoding framework that first learns fMRI-informed spectral projections from simultaneous EEG-fMRI recordings and then uses fMRI-derived class geometry to guide residual refinement of EEG predictions. FRIST transfers information across recordings through shared finger labels without requiring paired trials and uses only EEG at inference. We evaluated 12 able-bodied participants during movement execution (ME) and motor imagery (MI) under two-class and three-class chronological session-held-out decoding simulating the online scenario. Using 

---

### [110] BRIDGE-EEG: Bridging Self-Supervised Pretraining and Efficient Deployment for Cross-Dataset EEG Classification

**链接**: https://arxiv.org/abs/2609.12218
**作者**: Meghna Roy Chowdhury, Chengwei Zhou, Haotian Yu, Gourav Datta, and Shreyas Sen
**来源**: cs.HC cs.LG eess.SP
**匹配关键词**: EEG, Foundation Models, Motor Imagery
**相关性评分**: 7.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The growing use of electroencephalography (EEG) motivates automated analysis that is accurate, transferable, and deployable on constrained hardware. Recent EEG foundation models learn general representations from large-scale pretraining, but their size and computational cost limit edge and wearable deployment. We introduce BRIDGE-EEG, an efficient multi-task EEG classification pipeline that preserves the benefits of pretraining while reducing model size. A unified preprocessing scheme maps heterogeneous recordings with different channel counts, montages, and sampling rates to a device-agnostic 62-channel time--frequency representation. We pretrain an SE-ResNet18 teacher (11.84 M parameters) with SimCLR on unlabeled EEG from five heterogeneous datasets, then compress it into SE-ResNet8 (1.56 M) and SE-ResNet4 (0.48 M) students using task-agnostic and task-specific distillation. We evaluate six benchmarks spanning abnormality detection, motor imagery, and emotion recognition. For abnorma

---

### [111] Multivariate decoding of EEG reveals key spatial and temporal distinctions in perception and valuation

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S1053811926005458&hl=zh-CN&sa=X&d=4306848736888269302&ei=bu6naty6I4-P6rQPucXD2Ac&scisig=AIVdB-y0iR6qwg5D2l8agL8nEG5E&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIVdB-zf-Kmv1B5RydEgEMFMJLsi&html=&pos=2&folt=kw-top
**作者**: MD Bachman, A HajiHosseini, H Cho, D Nemrodov… - NeuroImage, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Decisions often require the integration of multiple considerations or attributes. Yet despite considerable research, debate continues about the neural mechanisms underlying the calculation of individual attribute values. One key question centers on

---

### [112] Current Studies of EEG Markers of Stress

**链接**: https://scholar.google.com/scholar_url?url=https://link.springer.com/article/10.1134/S0362119726700647&hl=zh-CN&sa=X&d=7841722368825349372&ei=bu6naty6I4-P6rQPucXD2Ac&scisig=AIVdB-yP5S_Fu0B6mhffXeK_82Tt&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIVdB-zf-Kmv1B5RydEgEMFMJLsi&html=&pos=1&folt=kw-top
**作者**: OM Bazanova, OA Dzhafarova - Human Physiology, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> , and EEG parameters of stress response. The literature analysis identifies the key factors affecting the quality of stress diagnostics using EEG . These include: the identification of individually defined EEG frequency bands; co-registration of EEG

---

### [113] Altered EEG -derived functional brain states in Parkinson's disease with mild cognitive impairment

**链接**: https://scholar.google.com/scholar_url?url=https://academic.oup.com/braincomms/advance-article-pdf/doi/10.1093/braincomms/fcag348/71031413/fcag348.pdf&hl=zh-CN&sa=X&d=12986206028816306594&ei=bu6naty6I4-P6rQPucXD2Ac&scisig=AIVdB-wDK7iQDZBsX3kQ-D0K1xT5&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIVdB-zf-Kmv1B5RydEgEMFMJLsi&html=&pos=3&folt=kw-top
**作者**: Y Wang, Z Zhang, J Wang, Z Jiang, L She, Y Pan 等 (8 人)
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Leveraging the high temporal resolution of source-reconstructed EEG , we characterized these … EEG data to probe the temporal properties and transition dynamics of brain functional states in Parkinson’s disease patients with and without

---

### [114] A two-stage fusion framework for EEG -based emotion recognition combining pre-training and multi-source domain adaptation

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S1746809426019804&hl=zh-CN&sa=X&d=10190847083902180713&ei=bu6naty6I4-P6rQPucXD2Ac&scisig=AIVdB-yJsxbGoGYppC-ilpMH4gwo&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIVdB-zf-Kmv1B5RydEgEMFMJLsi&html=&pos=5&folt=kw-top
**作者**: Y Yang, N Du, Q He, M Yu - Biomedical Signal Processing and Control, 2027
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Abstract Emotion recognition based on electroencephalograms ( EEGs ) is crucial for affective … In the first stage, a self-supervised pre-training strategy is designed to learn transferable EEG … These results indicate the potential effectiveness of

---

### [115] EEG -Based Auditory Attention Recognition Using DSCANet: An Innovative Incremental Learning Framework

**链接**: https://scholar.google.com/scholar_url?url=https://ieeexplore.ieee.org/abstract/document/11686138/&hl=zh-CN&sa=X&d=10545308008226226132&ei=bu6naty6I4-P6rQPucXD2Ac&scisig=AIVdB-wx8ywN9iqyfdqkK_n0-_fg&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIVdB-zf-Kmv1B5RydEgEMFMJLsi&html=&pos=6&folt=kw-top
**作者**: K Zhang, J Li, Z Li, S Yan, D Jia, Y Chen 等 (8 人)
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Auditory attention recognition from electroencephalography ( EEG ) is fundamental for … The deep learning module is responsible for effectively extracting key EEG features, while the … , which supports its adaptability and robustness in dealing with

---

### [116] An open-set learning framework for EEG -based sleep stage classification

**链接**: https://scholar.google.com/scholar_url?url=https://iopscience.iop.org/article/10.1088/1741-2552/aea59e/meta&hl=zh-CN&sa=X&d=12773878237096145456&ei=bu6naty6I4-P6rQPucXD2Ac&scisig=AIVdB-xnmmyoiENwHnwo_DQ7hZ5F&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIVdB-zf-Kmv1B5RydEgEMFMJLsi&html=&pos=4&folt=kw-top
**作者**: Q Feng, C Li, H Peng, H Qiao, R Song, X Chen - Journal of Neural Engineering 等 (7 人)
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> framework for EEG sleep … EEG datasets, our framework accurately classifies known sleep stages and reliably detects unknown categories, significantly boosting open-set recognition (OSR) performance. Significance. This work provides a

---

### [117] Multimodal Neuroimaging in Schizophrenia: a Systematic Review of EEG and fMRI Integration

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S0925492726001939&hl=zh-CN&sa=X&d=13890810903078269315&ei=bu6naty6I4-P6rQPucXD2Ac&scisig=AIVdB-wtExtbL9ZXhTuUJt4YpmeC&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIVdB-zf-Kmv1B5RydEgEMFMJLsi&html=&pos=0&folt=kw-top
**作者**: F Carbone, F Donati, E Bondi, A Kozlowski–Dal Bosco… - Psychiatry Research …, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Schizophrenia (SCZ) is a complex psychiatric disorder involving disruptions in neural signaling and neurovascular function that are incompletely characterized by single-modality imaging. This systematic review evaluates how concurrent

---

### [118] Atlas-Based Electrical Source Imaging for Mouse EEG : Application to an Fmr1 Knockout Model

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S1053811926005331&hl=zh-CN&sa=X&d=2347082025146815153&ei=bu6naty6I4-P6rQPucXD2Ac&scisig=AIVdB-y2EQ6QRRMJfk1tl_Xohqsu&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIVdB-zf-Kmv1B5RydEgEMFMJLsi&html=&pos=8&folt=kw-top
**作者**: AD Edmondson, A Gaulden, R Lacher, G Westerkamp… - NeuroImage, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> EEG signal arises. It is routine in humans but unestablished in the mouse, whose brain is some 3,000 times smaller where it is not obvious that a sparse array can separate one region from another. We built an atlas-based ESI pipeline for 30-channel

---

### [119] Reduced Motor Preparation and Altered EEG Signatures of Prediction in Autistic Adults

**链接**: https://scholar.google.com/scholar_url?url=https://onlinelibrary.wiley.com/doi/pdf/10.1111/ejn.70673&hl=zh-CN&sa=X&d=16632919801910719829&ei=bu6naty6I4-P6rQPucXD2Ac&scisig=AIVdB-wDpNV1zjPifVqywE9rh3PP&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIVdB-zf-Kmv1B5RydEgEMFMJLsi&html=&pos=7&folt=kw-top
**作者**: S Bagheri, A Cardinaux, L Bungert, CE Li, AM O'Brien… - European Journal of …, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> A standing hypothesis proposes that the social and behavioral diagnostic features of autism may develop as a result of more fundamental difficulties in forming and utilizing predictions. More specifically, in the present study, we hypothesized that

---

### [120] EEG resting-state gamma power as a potential biomarker of excitation/inhibition imbalance in autism: Evidence from the Autism Biomarkers Consortium for Clinical …

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S0924977X26011053&hl=zh-CN&sa=X&d=6111860459073508947&ei=bu6naty6I4-P6rQPucXD2Ac&scisig=AIVdB-w6dsQpV7wTy-ARnmo3doEW&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIVdB-zf-Kmv1B5RydEgEMFMJLsi&html=&pos=9&folt=kw-top
**作者**: V Arutiunian, CA Sugar, A Naples, M Santhosh… - European …, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> a naturalistic longitudinal study assessing a set of candidate electroencephalographic ( EEG ) biomarkers, their change over time, utility for group … A total of 1597 EEGs were analyzed resulting in 399 autistic children and typically

---

### [121] DCRA: Diffusion-Conditioned Representation Alignment for Robust Time-Series Learning

**链接**: https://arxiv.org/abs/2609.11997
**作者**: Wenrui Xu, Anas Enanaa, Keshab K. Parhi
**来源**: cs.LG stat.ML
**匹配关键词**: EEG
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Learning robust representations for time-series signals under noise and distribution shifts remains challenging, especially in clinical applications such as electroencephalogram (EEG) and electrocardiogram (ECG) analysis. We propose Diffusion-Conditioned Representation Alignment (DCRA), a training framework that repurposes the forward diffusion process as a structured corruption scheduler for representation learning. Different from conventional augmentation and consistency-based methods that rely on independently sampled perturbations, DCRA introduces a structured corruption trajectory via the diffusion forward process, which enables continuous and controlled representation evolution across noise levels. We introduce a feature-level consistency objective that aligns representations across noise levels while preserving class-discriminative structure. This mechanism promotes structure-preserving consistency, which enables smooth and semantically coherent feature trajectories in latent sp

---

### [122] Attention Quantization for Tabular Foundation Models

**链接**: https://arxiv.org/abs/2609.13031
**作者**: Jonas M. K\"ubler, Benjamin J\"ager, Klemens Fl\"oge, Noah Hollmann, Frank Hutter
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> With the recent rise and adoption of tabular foundation models, optimizing their inference performance becomes an emerging field for efficiency research. While the models are architecturally similar to transformer-based large language models (LLMs), the size and serving patterns differ significantly. We show that the focus should be on the attention calculation and less on weight or KV cache quantization, which are more popular in LLMs. We develop a quantization strategy for queries, keys, and values to FP8 and use explicit FP8 matrix multiplication instructions to speed up the attention calculation. We find that it is crucial to align the quantization error in the test rows with the quantization error in the training rows, as otherwise the accuracy drops drastically. Our Triton kernel achieves a speedup up to 1.7x over regular 16-bit kernels, and we show that on TabPFN-v3 and TabICLv2 there is no relevant accuracy loss across TabArena and BeyondArena.

---

### [123] Can Foundation Models Moderate Online Content? Evaluating Instruction- vs. Example-Driven Policy Operationalization

**链接**: https://arxiv.org/abs/2609.10410
**作者**: Ayan Majumdar, Shounak Paul, Pushpdeep Singh, Ines Abdelaziz, Sayeh Jarollahi, Seungeon Lee 等 (9 人)
**来源**: cs.CL cs.AI cs.CY
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [124] Reinforcement Learning over Patient Trajectories for Clinical Reasoning in EHR Foundation Models

**链接**: https://arxiv.org/abs/2609.12277
**作者**: Yuxin Xiao, Sheng Zhang, Chandan Singh, Tristan Naumann, Hoifung Poon, Jianfeng Gao 等 (7 人)
**来源**: cs.LG cs.AI cs.CY
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Electronic health record (EHR) foundation models trained on longitudinal patient trajectories have demonstrated strong performance across diverse clinical prediction tasks. However, their clinical reasoning capabilities remain constrained by next-token prediction on limited and incomplete EHR data. To address this, we propose a reinforcement learning (RL) fine-tuning framework that treats EHR foundation models as generative policies over patient trajectories. We formulate common clinical prediction problems (e.g., hospital readmission) as event-conditioned, time-windowed reasoning tasks. We then design time-aware, rollout-sensitive rewards to account for finite rollout lengths and temporally inconclusive outcomes. We find that RL fine-tuning consistently improves over pre-trained backbones and strong baselines. Notably, it enables smaller models to surpass larger pre-trained models in data-limited regimes and induces positive transfer across tasks. Further analysis shows that RL fine-t

---

### [125] No One Knows the State of the Art in Geospatial Foundation Models

**链接**: https://arxiv.org/abs/2605.12678
**作者**: Isaac Corley, Nils Lehmann, Caleb Robinson, Gabriel Tseng, Anthony Fuller, Hamed Alemohammad 等 (9 人)
**来源**: cs.CV cs.CY
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [126] HoliBench: A Cross-Platform Benchmarking and Deployment Toolkit for Foundation Models in CPS-IoT Applications

**链接**: https://arxiv.org/abs/2609.12412
**作者**: Inesh Chakrabarti, Zejun Xiong, Pragya Sharma, Mani Srivastava
**来源**: cs.DC cs.LG cs.PF
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Foundation models, including large language models, vision-language models, and time-series foundation models, are increasingly deployed on embedded and edge platforms for CPS and IoT applications, where energy, latency, and memory are as critical as task accuracy. Existing benchmarking tools evaluate model capability in isolation, reporting accuracy assuming sufficient compute, while hardware profiling tools remain platform-specific and mutually incompatible. As a result, users lack a unified workflow for making deployment decisions across heterogeneous devices. We present HoliBench, a modular benchmarking and deployment toolkit that jointly characterizes accuracy, latency, and energy across platforms from single-board computers to GPU servers. Its platform abstraction layer calibrates cross-device measurement, and the toolkit supports multiple model modalities, inference engines, concurrencies, and existing evaluation harnesses. An interactive interface exposes constraint-aware confi

---

### [127] UniPart: Towards Zero-shot Language-Grounded 3D Part Segmentation for Embodied Interaction

**链接**: https://arxiv.org/abs/2609.12898
**作者**: Xinqiang Yu, Zekun qi, Jiawei He, Wenyao Zhang, Xuchuan Chen, Guaocai Yao 等 (9 人)
**来源**: cs.CV cs.AI cs.RO
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Fine-grained robotic manipulation depends on understanding parts, not only whole objects. Existing 3D foundation models tend to be either generalized but object-aware, or part-aware but limited to closed-set taxonomies, which weakens zero-shot transfer. We study text-conditioned 3D part segmentation, where a free-form phrase selects a functional part on point cloud. We introduce UniPart, a feed-forward cross-modal 3D Transformer that conditions CLIP text embedding. To scale supervision, we build LangPart-1M with 160K+ Objaverse assets and 8M text to part pairs using multi-view consistent part generation. We further manually label a high-quality subset, LangPart-4K, for fine-tuning and evaluation. UniPart achieves strong zero-shot results on open-vocabulary part benchmarks and transfers to language-conditioned part grasping in real world.

---

### [128] Bridging Vision Foundation Model Priors with CLIP for Spatial-aware Few-shot Anomaly Detection in Medical Images

**链接**: https://arxiv.org/abs/2609.12454
**作者**: Juzheng Miao, Yuchen Yuan, Cheng Chen, Pheng-Ann Heng
**来源**: cs.CV cs.AI cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Vision-Language Models such as CLIP enable effective few-shot medical anomaly detection (AD) via strong image-text semantic alignment. However, their globally contrastive pretraining lacks explicit spatial supervision, limiting precise lesion localization. In contrast, Vision Foundation Models (VFMs) such as DINO learn spatially coherent patch representations via self-distillation and local-to-global consistency, better capturing fine-grained anatomical structures. Leveraging this complementarity, we propose Spatial-FAD, a spatial-aware few-shot medical AD framework that improves lesion localization by combining VFM spatial priors with CLIP semantics. Specifically, we introduce a VFM-enhanced adapter that injects a structural affinity prior derived from DINO into CLIP features. This structure-guided refinement encourages visual embeddings to better adhere to lesion boundaries while maintaining semantic alignment. To address the loss of spatial detail from patchification and the limited

---

### [129] Reading the Whole Heart: Latent-Attention Masked Autoencoders for Multimodal Cardiac Representation Learning

**链接**: https://arxiv.org/abs/2609.12035
**作者**: Andrea Agostini, Simon B\"ohi, Moritz Vandenhirtz, Samuel Ruiperez-Campillo, Max Kr\"ahenmann, Silke M\"uhlstedt 等 (10 人)
**来源**: cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Cardiovascular diagnosis rests on integrating complementary modalities, like ECG, echocardiography, chest radiographs, and clinical variables, each capturing distinct but correlated aspects of cardiac physiology. Yet most medical foundation models remain modality-specific, combining modalities only for finetuning or post-training. This discards the cross-modal evidence clinicians naturally integrate and ignores the structure within each modality. We introduce Latent-Attention Masked Autoencoders (LAMAE), a multimodal, structure-aware masked autoencoder that jointly learns patient-level representations during self-supervised pretraining. Rather than fusing modalities post hoc, LAMAE exchanges information directly in the latent space through a shared latent-attention module operating over a study-view-entity hierarchy, enabling aggregation of variable observations and graceful handling of missing modalities. Pretrained on over 1.2 million MIMIC-IV hospital stays, LAMAE outperforms modali

---

### [130] Involving before Evolving: A Vision for Trustworthy Enterprise Digital Twin Engineering

**链接**: https://arxiv.org/abs/2609.13071
**作者**: K\'erian Fiter, Adil Lagrou, Franck Dervault, Bentley Oakes
**来源**: cs.SE cs.AI cs.HC
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Enterprise Digital Twins (EDTs) promise data-driven decision support at organizational scale, but realizing them requires navigating siloed departments, tacit knowledge, and high-stakes decisions with long-horizon consequences. Existing approaches involve domain experts during model development but focus less on early organizational buy-in in EDTs. We present a vision for trustworthy EDT engineering grounded in an `involving before evolving' paradigm: rapidly involving stakeholders through a working prototype before evolving toward federation and full interoperability. Our three-stage approach combines foundation models for rapid prototyping, an ontological backbone for federated interoperability, and observability tooling for stakeholder trust. We ground our vision in an ongoing collaboration with Michelin, a multinational manufacturer, where an initial prototype has helped support stakeholder buy-in.

---

### [131] Partition-Invariant Tuning for 3D Scene Understanding

**链接**: https://arxiv.org/abs/2609.12473
**作者**: Hongqiang Lin, Tianle Wang, Shuiwang Li, Dongxu Zhang, Yiding Sun, Zihao Guo 等 (7 人)
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Scene-level point cloud understanding remains challenging due to diverse geometries and spatial layouts. While pre-trained 3D point cloud foundation models (PFMs) offer strong transferability, full fine-tuning (FFT) incurs substantial computational and storage costs. Parameter-efficient fine-tuning (PEFT) provides a promising alternative, but existing PEFT methods largely focus on object-level point clouds and overlook serialization-induced partition variations in large-scale scenes. To address this issue, we propose PointPiT, a partition-invariant tuning framework for scene-level point clouds. Specifically, a Scene-aware Structural Adapter (SSA) integrates local geometric patterns with global scene context to mitigate partition-induced representation shifts. Moreover, Gradient Subspace Optimization (GSO) selects informative and partition-stable update directions, suppressing partition-dependent variations during optimization. Extensive experiments across multiple scene-level benchmark

---

### [132] Where Decoder Cosine Similarity Fails for SAE Feature Flow Discovery

**链接**: https://arxiv.org/abs/2609.12591
**作者**: Hendrik Droste, Christian Medeiros Adriano, Kathrin Korte, Holger Giese
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Foundation models are increasingly adapted through fine-tuning, model editing, and alignment procedures while retaining previously acquired capabilities. Understanding the internal computations that support these adaptations is therefore becoming increasingly important for continual model evolution. Sparse autoencoders (SAEs) provide interpretable feature dictionaries for residual-stream activations and sublayer outputs, but it remains unclear how state features and update features interact to produce downstream residual features. In this work, we focus on MLP updates as a first test case. We construct a transition atlas of triples $s_k + u_j \rightarrow t_\ell$, where a residual-state feature and an MLP-update feature jointly predict a target residual feature, and validate candidate triples by ablating the decoded update feature. In a 20M-token Pythia-160M $L_7 \rightarrow L_8$ run, we find 38,125 strong ablation-effect transitions, but 88.0% have both state-target and update-target d

---

### [133] The Anatomy and Boundary of Adaptation under Temporal Tabular Shift

**链接**: https://arxiv.org/abs/2609.12136
**作者**: Tianyu Wang, Xi Vincent Wang, Lihui Wang, Mian Li, Zhihao Liu
**来源**: stat.ME cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Prequential adaptation of frozen tabular foundation models under temporal drift, with each label revealed only after prediction, helps some deployments and harms others, yet current practice does not predict which. We study the sources and limits of these gains. A diagnostic anatomy attributes gains to four recurring mechanisms under a streaming protocol that removes three optimistic biases and quantifies a fourth. Within an agnostic total-variation drift class, the target conditional is only partially identified: its identified-set diameter, the \emph{wall}, is irreducible from unlabeled data uniformly in sample size. A second, orthogonal $L^2$ projection wall quantifies what the frozen representation cannot express. Two canonical mechanism priors collapse the first wall. Under stated nuisance-rate conditions, the wall can be estimated from labeled historical windows at a $\sqrt N$ rate above the margin threshold $\gamma^\star=d_0/(2\alpha_s)$. At $\gamma=0$, the conditional lower-bou

---

### [134] LatentVerse: A Framework for Understanding Shared and Modality-Specific Information in Multimodal Latent Representations

**链接**: https://arxiv.org/abs/2609.12364
**作者**: Majd Alafrange, Samuel Friedman, John Kitonyo, Sana Tonekaboni, Mahnaz Maddah
**来源**: cs.LG cs.HC
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Latent embeddings have become a central data abstraction in modern machine learning, especially in biomedicine, where foundation models are increasingly used to encode multimodal data like clinical text, medical images, omics, and physiological signals. However, the utility and value of these representations depends on understanding their quality, structure, and the information they encode. Existing analysis workflows for evaluating representations remain fragmented across custom scripts, isolated metrics, and most importantly lack multimodal analysis, limiting accessibility and reproducibility. We present LatentVerse, a representation analysis resource that combines a web-based visual analytics platform for accessible, report-driven exploration with a command-line interface for scalable technical workflows. LatentVerse unifies diagnostics for various representation quality metrics and extends to multimodal settings by decomposing embeddings into shared and modality-specific components

---

### [135] Beyond Argmax: A Mechanistic Study of Semantic Retention in Frozen Foundation-Model Composition for Generalized Few-Shot 3D Segmentation

**链接**: https://arxiv.org/abs/2609.12099
**作者**: Silas Kwabla Gah and Ebenezer Owusu
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Classical classifier-combination work distinguishes score-level fusion from hard decision-level voting. We revisit this distinction where independently pretrained, frozen foundation models are composed at inference time for generalized few-shot 3D segmentation. We ask: how much useful semantic information is lost when heterogeneous sources are collapsed to a single class before they can interact? We answer with a same-input semantic-retention intervention. Dense RegionPLC and sparse cross-view SAM3 evidence, model weights, masks, geometry, vocabularies, and fusion rules are frozen; only the number of semantic alternatives retained before interaction is varied via a matched top-k ladder. On 156 held-out ScanNet200 scenes, top-1 reaches 28.47 harmonic-mean (HM) IoU while full distribution fusion reaches 34.87 HM (+6.40, 95% CI [+5.24,+7.64]). The pattern replicates on 50 ScanNet++ scenes: 23.02 vs. 26.50 HM (+3.48, 95% CI [+1.64,+5.93]). The conclusion is robust: full-distribution HM is 

---
