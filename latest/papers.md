# 📑 论文索引 - 2026-10-02

共 210 篇论文

---

### [1] TACTIC: Temporal and Context-Aware LLM Tactical Planning for Roadside LiDAR Attacks

**链接**: https://arxiv.org/abs/2609.39969
**作者**: Yiming Gao, Shaocheng Luo
**来源**: cs.RO cs.AI cs.SY eess.SY
**匹配关键词**: LLM, Large Language Model, MLLM, Multimodal Large Language Model
**相关性评分**: 8.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Physical LiDAR attacks are often evaluated using fixed primitives and manually selected parameters, despite their strong dependence on surrounding traffic. We present TACTIC, a scene-aware framework that uses a multimodal large language model (MLLM) to coordinate state-adaptive roadside LiDAR attacks. Under a gray-box threat model, TACTIC relies only on an attacker-operated roadside perception stack, without accessing the victim LiDAR's native point clouds or internal processing. Local perception provides metric vehicle states, while the MLLM combines these measurements with roadside imagery to infer relational traffic context and construct a semantic scene graph. Based on this representation, TACTIC selects and configures two complementary primitives: \emph{push-away}, which shifts the perceived range of a lead vehicle, and \emph{phantom-obstacle braking}, which triggers emergency braking through obstacle injection. Measured traffic states and empirically calibrated constraints ground

---

### [2] Characterizing High Bandwidth Flash for LLM Serving

**链接**: https://arxiv.org/abs/2609.39131
**作者**: Zack Yu, Chloe Wong, Coleman Hooper, Minjae Lee, Wonjun Kang, Youngjin Cho 等 (10 人)
**来源**: cs.LG cs.AR cs.DC
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) serving requires substantial memory to store model weights and KV caches. As models grow larger and contexts become longer, memory capacity and bandwidth increasingly become bottlenecks for serving performance. Agentic workloads compound this pressure through repeated interactions over growing contexts, making it increasingly important to retain KV state for reuse. High-bandwidth flash (HBF) offers a way to expand accelerator memory capacity for large language model (LLM) serving, but its access costs and limited write endurance complicate its use. We evaluate HBF for high-throughput agentic serving across system design and scheduling choices to understand when additional capacity improves serving performance and energy efficiency. We introduce an HBM-HBF-host hierarchical storage system and buffered cache-aware scheduling, and use trace-driven simulations to analyze their effects on performance, energy consumption, and HBF write lifetime. Across the evaluate

---

### [3] Structure vs. Chain-of-Thought: Evaluating LLM Criteria Extraction for Depression Severity

**链接**: https://arxiv.org/abs/2609.39049
**作者**: Xinkai Chen
**来源**: cs.CL cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A large language model (LLM) can rate depression severity directly from a social media post or mark which clinical criteria the post shows and let code turn the count into a label. The latter is easier to audit because a clinician can check each marked criterion. We compare these approaches on two Reddit corpora using three LLMs (from 9B to frontier scale) and two questionnaires (PHQ-9, BDI-II), and measure agreement with quadratic weighted kappa. For the two frontier models, criteria extraction scores above chain-of-thought on one corpus only when its decision thresholds are fitted on labeled data. Neither model's gain is significant, with or without recalibrating chain-of-thought on the same labels. With thresholds fixed a priori from PHQ-9's criteria, extraction shows no gain on either corpus, even where models mark over two criteria per post. The 9B model behaves differently on a corpus from depression communities. It labels most posts severe, whether prompted directly or with chai

---

### [4] CamAgent: An LLM-Agent Framework for Multi-Species Camera-Trap Workflows

**链接**: https://arxiv.org/abs/2609.39112
**作者**: Yutong Deng and Qi Song and Xi Guo and Tianming Wang and Lei Bao and Jianping Ge
**来源**: cs.CV
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Camera traps accumulated vast, multidimensional data for wildlife monitoring, yet translating raw media archives into meaningful ecological insights remains highly fragmented. Current research workflows require laboriously stitching together disparate analysis tools and scripts, creating steep programming hurdles and complicating end-to-end spatiotemporal analyses. To overcome this fragmentation, we present CamAgent, an autonomous Large Language Model (LLM) agent framework that integrates camera-trap analytical workflows into a unified intelligent ecosystem. CamAgent interprets natural-language ecological intent, schedules computational routing, and executes specialized tools spanning computer-vision perception (e.g., SpeciesNet), CamtrapDP-compatible data management, detection-corrected occupancy modeling, temporal activity analysis, and species co-occurrence networks. The framework automates multi-stage analytical pipelines while maintaining essential data-quality controls and analyt

---

### [5] Optimal Design for Active Preference Learning with Biased LLM Judges

**链接**: https://arxiv.org/abs/2609.38860
**作者**: Zhongman Du, Huiming Zhang, Haodong Zhu, Baochang Zhang
**来源**: cs.LG cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Learning from human preferences is central to large language model (LLM) alignment, but human preference annotation is costly. Active preference learning reduces this cost by selecting informative comparisons, and LLM judges can provide additional scalable feedback. However, the preferences of the judges may deviate from those of the target human population. Even after calibration on trusted reference data, active acquisition can shift the comparison distribution and expose residual judge bias. We therefore incorporate judge deviations into the acquisition design rather than relying on a separate calibration stage. Under joint estimation, comparisons that appear highly informative about the reward may also reflect judge bias and therefore provide less information about human preferences. To address this issue, we propose Nuisance-Adjusted Optimal Design (NAOD), a comparison-selection strategy that prioritizes policy-relevant target information after nuisance adjustment and uses the Fra

---

### [6] Agentic Tool-Augmented Reasoning for Explainable Image Forgery Detection

**链接**: https://arxiv.org/abs/2609.39066
**作者**: Zhiya Tan, Jing Huang, Changtao Miao, Lin Tan, Xin Zhang, Weiwei Feng 等 (8 人)
**来源**: cs.CV
**匹配关键词**: Large Language Model, MLLM, Multimodal Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Conventional image forgery detection methods produce binary scores or pixel-level masks without interpretable evidence, while recent multimodal large language model (MLLM)-based approaches generate post-hoc explanations of predetermined classification results rather than reasoning from evidence. Inspired by the forensic workflow of human judicial experts, we propose Agentic Tool-Augmented Reasoning (ATAR), a framework integrating 22 specialized forensic tools across seven complementary domains to autonomously detect, localize, and explain image forgeries through multi-turn reasoning. A Dual-Stream Forensic Reasoning paradigm combines a high-level semantic anomaly path, which magnifies suspicious regions for fine-grained inspection, with a low-level forgery artifact path, which invokes forensic tools to extract objective evidence. We further introduce Forensics Curriculum Learning: during General Experience SFT, an automated teacher-student mentoring pipeline synthesizes multi-turn tool

---

### [7] Provable Test-Time Scaling for Beam Search in LLM Reasoning

**链接**: https://arxiv.org/abs/2609.38672
**作者**: Qijia He, Yu Huang, Yuan Cheng, Yuxin Chen, Yingbin Liang
**来源**: cs.LG cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Beam-search-based test-time methods provide an effective way to improve large language model (LLM) performance on long-horizon generation by pruning invalid reasoning paths early, leading to significantly improved reasoning efficiency and more favorable test-time cost scaling. Despite strong empirical success, the theoretical understanding of beam search remains limited. In this paper, we study the test-time compute guarantee of the commonly used beam search framework that uses the model's internal log-likelihood for intermediate scoring, while relying on an external reward model only after a complete response is generated. We first establish a lower bound for vanilla beam search, showing that at least $\Omega(C^\star(x)^2)$ samples are required for the optimal response to survive, where $C^\star(x)$ is the token-level coverage coefficient for prompt $x$. This motivates our modified confidence-filtered beam search (CF-Beam), which reduces the sufficient coverage dependence from quadrat

---

### [8] SkillFM: Generating Skills for LLM Agents via Latent Flow Matching

**链接**: https://arxiv.org/abs/2609.39382
**作者**: Zuming Zhang, Jie He, Yizhe Zhang, Jeff Z. Pan
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Textual skills provide reusable guidance for large language model agents, but existing approaches often rely on manually curated skill banks or reinforcement learning with indirect and delayed feedback. We introduce SkillFM (Skill Flow Matching), a generative framework that synthesizes task-conditioned textual skills directly without test-time skill retrieval. Our framework combines a codec for encoding and reconstructing textual skills in a continuous latent space with a conditional flow model trained using improved MeanFlow. At inference time, the learned velocity field enables single-step latent sampling, and an LLM-based decoder converts the sampled representation into textual guidance for a frozen downstream agent. We evaluate the framework on embodied tasks, question answering, and web shopping. On ALFWorld and Search-QA, our method achieves the best overall performance among the compared vector-based skill approaches. Our analyses further demonstrate that latent skill generation

---

### [9] Whose Voice Survives the Summary? A Voice-Retention Audit of LLM Employee Listening

**链接**: https://arxiv.org/abs/2609.38818
**作者**: Thilo Tamme, Anton Hantel, Bijan Khosrawi-Rad
**来源**: cs.AI cs.CL cs.CY cs.HC
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Organizations increasingly route employee feedback to leaders through large language model (LLM) summaries, an unaudited layer that silences already-spoken voice. We introduce a Voice Retention / Representation Ratio metric for representational bias in summarization and apply it to a bilingual (English/German) corpus of 2,586 free-text responses from a global professional service company. First, employees supply criticism more reliably than praise (withholding praise is 82 times more common). Second, across 45 leader-summaries the pipeline filters by popularity, not sentiment: criticism survives, yet a concern voiced once is dropped 86% of the time, with short and German-only content lost on the same axis (theme retention 0.14 vs 0.74; German directional). Controlling for frequency, sentiment has no independent effect; the harm is prevalence-driven, which sentiment-only audits miss. A targeted prompt recovers only named themes. We contribute the metric, field evidence, and a disaggrega

---

### [10] PrivMeSA: Privacy-Aware Self-Evolving Multi-Agent System for Medicine via Local-Remote LLM Collaboration

**链接**: https://arxiv.org/abs/2609.38458
**作者**: Dannong Wang, Yuran Zhang, Bian Sun, Alex Stinard, Yuzhang Shang, Song Wang 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Clinical large language model (LLM) agents deployed locally can consult more capable remote models, but doing so risks exposing patient information. Privacy-conscious delegation places disclosure decisions with a local agent, yet removing explicit identifiers is insufficient: quasi-identifiers can accumulate across multi-turn consultations and repeated patient visits to enable re-identification. We introduce PrivMeSA, a privacy-aware self-evolving multi-agent system that learns to control disclosure and retains remote expertise for local reuse. A local agent manages each encounter and consults remote specialists that may request additional information. Reinforcement learning balances task accuracy against direct disclosure and registry-based re-identification risk, with privacy evaluated over the complete outbound transcript of each encounter. A local lesson memory distills completed consultations into generalized clinical guidance and retrieves relevant lessons before transmission, al

---

### [11] Rep2Skill: Representation-Guided Skill Self-Evolution for LLM Agents

**链接**: https://arxiv.org/abs/2609.39149
**作者**: Kaixing Zhang, Changming Li, Yingdong Shi, Zheng Zhang, Kaitao Song, Wenjie Shi 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Textual skills enable large language model (LLM) based agents to accumulate reusable procedural knowledge without updating model parameters. Yet existing skill evolution remains largely confined to the text space: an optimizer must diagnose success and failure patterns, and revise skills solely from long execution trajectories and sparse task outcomes. This text-only paradigm leaves the agent's internal representations, which contain rich records of its evolving execution state, outside the skill optimization loop. We ask whether an agent can improve its external textual skills by reflecting on its own internal representations. We introduce Rep2Skill, a representation-guided framework for self-evolution on agent skills. Specifically, upon the collected agent rollouts, Rep2Skill models their internal model representation trajectories to localize turns that deviate from successful execution dynamics, and it further interprets these signals alongside the execution contexts as actionable t

---

### [12] Reasoning Externalization for Faithful Large Language Model Narratives of Stock Return Predictions

**链接**: https://arxiv.org/abs/2609.38869
**作者**: Sujung Kim, Seung Hwan Cho, Sangjin Park, and Young-Min Kim
**来源**: cs.AI cs.CE
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In finance, interpreting machine learning predictions is essential, yet the numerical outputs of explainable AI can be difficult for non-experts to understand. While large language models (LLMs) can translate these outputs into natural language, they may produce errors when inferring numerical changes and feature relations. We propose an LLM narrative framework for cross-sectional stock return prediction that combines temporal Shapley additive explanations (SHAP) evidence with historical regime analogs. Temporal evidence tracks changes in the normalized global SHAP importance of an XGBoost model over six months. Historical analogs are past periods with similar changes in SHAP importance, their model performance and subsequent market returns are provided as comparative context. Using this framework, we conduct a controlled study of progressive reasoning externalization, sequentially providing raw SHAP sequences, deterministic temporal descriptors, and feature relations. Each generated c

---

### [13] FlexRouter: Learning Complementary Model Sets for Flexible LLM Routing

**链接**: https://arxiv.org/abs/2609.38585
**作者**: Wang Wei, Harry Yang, Tiankai Yang, Samyadeep Basu, Hongjie Chen, Andy Zhao 等 (9 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Existing Large Language Model (LLM) routing methods score LLMs independently to select top-$k$ models. However, this ignores model correlations and enforces a rigid computational budget. Consequently, routers often select redundant models that share failure modes, limiting the overall probability of success. To address this, we propose FlexRouter, a routing framework that explicitly models model complementarity. FlexRouter optimizes for \textit{answer coverage}, maximizing the probability that at least one selected model yields a correct response. This objective aligns with practical inference pipelines where multiple candidate outputs are generated and a downstream verifier or user selects the final one. We formulate routing as a coverage-oriented subset selection problem and model the routing policy using Determinantal Point Processes (DPPs), which naturally capture both model competence and redundancy. To directly optimize coverage without requiring a ground-truth target subset, we 

---

### [14] Which Models Work Well Together? Measuring Heterogeneity for LLM Team Selection

**链接**: https://arxiv.org/abs/2609.38274
**作者**: Liangyu Teng, Hengsong Liu, Juncen Guo, Jingyu Zhang, Yang Liu, Jing Liu 等 (7 人)
**来源**: cs.CL cs.LG cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The performance ceiling of an LLM team is constrained not only by individual model capabilities, but also by inter-member error resonance and predictive differences. Although heterogeneous teaming is often observed to be effective in practice, existing approaches lack complementarity metrics that are computable, interpretable, and optimizable, leaving team composition to rely on heuristics. We propose a heterogeneity-driven team selection framework that performs offline profiling to characterize individual capability along with two complementary signals: one captures decorrelation in error patterns to reduce co-failures, while the other measures divergence in predictive behavior to capture strategy diversity. We formulate team selection as a standardized quality--complementarity combinatorial objective and apply an efficient greedy search to select a small team from a candidate pool. Experiments across multiple benchmarks demonstrate that our framework consistently outperforms quality-

---

### [15] APTInvestBench: Evaluating Autonomous APT Investigation under Varying Telemetry

**链接**: https://arxiv.org/abs/2609.38954
**作者**: Yu Wang, Shuhao Li, Tao Yin, Ziyang Li, Xueying Zhao, Peishuai Sun 等 (7 人)
**来源**: cs.CR cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents could help security operations centers (SOCs) investigate advanced persistent threats (APTs) by turning weak leads into evidence for intrusion scoping and response. Yet success under one telemetry setting does not establish robustness to changes in log collection, retention, or sampling. We introduce APTInvestBench, a benchmark for evaluating cross-telemetry robustness in autonomous APT investigation. It comprises 370 cases across seven SOC-inspired conditions, derived from 56 report-informed attack reconstructions with 16.4 million log records. Agents investigate unverified leads and submit reports with record-level citations. Fixed action-level support requirements track sufficient evidence across available logs, query returns, and formal citations, separating telemetry limitations from acquisition and reporting gaps. Across eleven LLMs, agents acquire sufficient evidence for 44.3% of recoverable attack actions on average, while formal citations supp

---

### [16] Inference-Layer Security: Defending Against Adversarial Inference and Infrastructure Abuse

**链接**: https://arxiv.org/abs/2609.38239
**作者**: Keifer Lee
**来源**: cs.CR cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A Technical Report: Operating a large language model (LLM) as a service requires more than inference infrastructure: the provider must also defend against adversarial interactions that seek to exploit the service, including jailbreaking for harmful use, sophisticated denial of service, and distillation attacks. We study this problem at the inference layer, using a hypothetical frontier lab, Five Elements Inc., as a running example. Because no public labelled dataset of adversarial LLM usage exists, we introduce a structural causal model (SCM) that generates a realistically grounded, labelled dataset of user-sessions, with coordinated multi-account campaigns, platform feedback, and three tiers of label observability. On this dataset we train a practical gradient-boosted detector that classifies each user-session as benign or malicious and, if malicious, by attack type. Against oracle labels the detector very nearly solves the binary task (AUPRC $0.993$), yet against the operational labe

---

### [17] SQD-Agent: LLM-driven agentic framework for Quantum Chemistry workflows

**链接**: https://arxiv.org/abs/2609.39302
**作者**: Kislaya Tiwari, Anupama Ray
**来源**: quant-ph cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Quantum algorithms and quantum hardware are advancing towards a promising paradigm for scientific applications. However, translating domain-specific problems into executable hybrid quantum-classical workflows remains a significant barrier for application researchers due to the required expertise in quantum algorithms, nuances in quantum programming, and hardware-aware system integration. At the same time, AI and primarily LLM based agents are increasingly capable of interpreting natural-language intent, reasoning over complex workflows, and translating high-level objectives into executable code and building computational pipelines. In this work, we introduce SQD Agent, an LLM-based agentic framework that translates natural-language user intent into executable workflows for Quantum Chemistry applications where algorithms from the Sample-Based Quantum Diagonalization (SQD) family are used. By automating this translation, SQD Agent reduces the level of human expertise and configuration ov

---

### [18] Defining and Categorising Human-AI Interactions in Clinical Trials: A Multidimensional Human-AI Classification Approach

**链接**: https://arxiv.org/abs/2609.38559
**作者**: Sandra Woolley, Tim Collins, Khalid Khattak, Illia Chernomorets, Ariane Arevalo and Chris Richardson
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> This paper examines human-AI interactions (HAIIs) in clinical trials and presents a multidimensional categorisation framework that classifies interactions according to AI tasks, human-AI relationships, interaction configurations and interacting human groups. We define HAII, examine existing taxonomies and extend existing categorisation approaches through this novel multidimensional framework. We purposively sampled 15 clinical trials from a previously reported dataset. Each trial was independently categorised by two human reviewers and six large language model (LLM) classifiers. The proposed categorisation provides a structured method for the consistent identification, comparison and synthesis of human-AI interactions across clinical-trial records. The framework is intended to support more consistent comparison and synthesis of AI-related clinical trials and to make explicit the different forms of human involvement associated with AI interventions. The results demonstrate the potential

---

### [19] Event-Driven Refresh and Recurrence Memory to Reduce Stale Grounding in Referring Video Object Segmentation

**链接**: https://arxiv.org/abs/2609.38758
**作者**: Abu Hanif Muhammad Syarubany, Jaehyun Jang, Siwoo Lim, Seungyeon Ryu, Chang D. Yoo
**来源**: cs.CV
**匹配关键词**: Large Language Model, Multimodal Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Referring Video Object Segmentation (RVOS) aims to produce a pixel-accurate mask sequence for an object specified by natural language. Sa2VA combines a multimodal large language model with SAM2 for grounded segmentation; however, its inference typically grounds the query from a small fixed set of initial keyframes and then relies on propagation. In long or dynamic videos, this can cause stale grounding and persistent false positives when the object composition changes (e.g., distractors enter or the target disappears/re-appears). We propose Event-Driven Refresh + Recurrence Memory (EDRRM), an enhancement that selectively re-invokes Sa2VA only at stable change points. EDRRM triggers refresh boundaries using an EMA-smoothed event score computed from tracking-derived cues (births/deaths and coarse composition/layout changes) with temporal constraints. A recurrence memory further retrieves anchor frames via CLIP similarity to re-condition the model on re-appearance events. Experiments on R

---

### [20] SEPAL: Separated Expert Pairs with Answer-Level Fusion for Reliable LLM Collaboration

**链接**: https://arxiv.org/abs/2609.39645
**作者**: Weijie Ren, Yanwen Zhang, Hao Li, Zhuolin Qi, Hengyi Zhang, Naibo Wang
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-agent collaboration lets large language models (LLMs) improve question answering through deliberation and feedback. Yet shared discussion couples correction with exposure to the same mistakes, which can erode the diversity needed for voting. Self-consistency offers sampling diversity without feedback, while single-pair Actor-Critic collaboration refines only one candidate. We introduce SEPAL, which assigns three private Actor-Critic teams to direct reasoning, evidence grounding, and verification. Role-specific training gives the teams different reasoning objectives beyond sampling variation. Each Critic guides revisions within its own team, preventing feedback from carrying errors across candidates. Once revision ends, majority voting combines only the final answers, keeping the reasoning histories separate until the decision. Across five open-weight backbones and five question-answering benchmarks, SEPAL improves mean accuracy by 1.81 percentage points over a matched single Acto

---

### [21] Multi-LLM Collaborative Alignment via Stackelberg Games

**链接**: https://arxiv.org/abs/2609.39076
**作者**: Christina Hahn, Shangbin Feng, Dean Light, Swastik Roy, Hila Gonen, Yulia Tsvetkov
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A pool of language models can collaborate and improve collectively by learning from one another's responses. These interactions depend on the instructions used during training. Existing methods typically sample instructions uniformly, even though their usefulness may change as the models improve: an instruction on which models' responses once differed in quality may later be answered equally well, while a previously difficult instruction may begin to provide a useful learning signal. We propose Stackelberg Alignment, a game-theory-inspired leader-follower framework that turns instruction selection into an adaptive curriculum. An EXP3 bandit acts as the leader, allocating a fixed sampling budget across instructions and updating its sampling distribution using a reward that combines instruction difficulty and response discriminability. The language models act as followers: they respond to the selected instructions, evaluate one another's responses, and learn from the resulting preference

---

### [22] SpanUQ: Span-Level Uncertainty Quantification for Large Language Model Generation

**链接**: https://arxiv.org/abs/2607.05721
**作者**: Yimeng Zhang, Yingying Zhuang, Ziyi Wang, Yuxuan Lu, Pei Chen, Aman Gupta 等 (10 人)
**来源**: cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [23] What Was Said, Not What Was 'Thought': Type-6 Logic for CoT Verification

**链接**: https://arxiv.org/abs/2609.38420
**作者**: Adrian de Wynter
**来源**: cs.LO cs.AI cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We introduce Type-6 logic, a variant of dynamic epistemic logic augmented with two operators (uncertainty and recurrence), designed to model the inferential dynamics of contemporary large language model (LLM) chain-of-thought (CoT) reasoning. Type-6 accounts for common LLM reasoning pathologies such as unlicensed revision, enthymemes, loopbacks, and unverifiable/incorrect claims. We propose a verifier based on Type-6 logic that builds a graph out the trace, and checks it against Type-6's axioms and inference rules. We evaluate our framework on LLM-generated CoTs four splits spanning formal and informal reasoning. Our verifier detects structurally unsound reasoning steps that surface-level heuristics miss, and allows for easy visualisation of the model's reasoning process. In our corpus, our verifier shows that derived contradiction is the most common hard-fail category in CoT, and that only about 3\% of the propositions of a trace have impact on the final derivation. Ablation studies s

---

### [24] Anchor-ECC: Local Integrity Checking for Watermarked LLM Outputs via Error-Correcting Codes

**链接**: https://arxiv.org/abs/2609.38722
**作者**: Zewei Deng, Muhammad Siddeek, Liyan Xie, Mohamed Seif, Mengdi Wang, H. Vincent Poor 等 (7 人)
**来源**: cs.CR cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM watermarking has become an effective approach to distinguishing AI-generated text from human-written text by embedding detectable patterns during generation. However, a small post-generation edit may change the meaning of the text without removing its overall watermark signal, creating a risk that the modified content is still attributed to the original model. We propose Anchor-ECC, which incorporates the error-correcting code (ECC) constraints and explicit boundary anchors into the watermark structure and pairs them with a dynamic-programming decoder to detect and localize post-generation edits. Across Qwen3-8B, Mistral-7B-Instruct-v0.3, and OPT-125M, the approximate-hard setting achieves about 99.7% block-level true positive rate (TPR) with at most 7.6% false alarm rate (FAR) for edit detection under mixed insertions, deletions, and substitutions, while preserving the distinction between watermarked outputs and unwatermarked text. Additional quality experiments identify lower-per

---

### [25] Beyond LoRA vs. Full Fine-Tuning: Gradient-Guided Optimizer Routing for LLM Adaptation

**链接**: https://arxiv.org/abs/2605.07111
**作者**: Haozhan Tang, Xiuqi Zhu, Xinyin Zhang, Boxun Li, Virginia Smith, Kevin Kuo
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [26] Personalized State-Transition-Aware Memory for Clinical Agents

**链接**: https://arxiv.org/abs/2609.38490
**作者**: Maryam Haghifam, Zahra Rajabi, Yizhou Sun, Carlos Morato
**来源**: cs.CL cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents that reason over clinical records must track changes in a patient's state while preserving the history needed to understand them. Simply accumulating memories leaves it unclear which information still applies, whereas overwriting earlier memories can erase evidence needed to reconstruct treatment history and clinical trajectories. We introduce STAM, a state-transition-aware memory framework that records state changes as new clinical entries arrive. STAM combines semantic retrieval with typed clinical relations to identify affected memories, maintaining current information in Active and superseded or resolved information in History. At read time, a query-dependent gate selectively serves historical memory. Across four longitudinal clinical benchmarks, we evaluate STAM with downstream question answering, direct state-maintenance diagnostics, and comparisons at approximately matched context lengths.

---

### [27] Talk2Agent: Benchmarking Voice Interfaces for Text Agents

**链接**: https://arxiv.org/abs/2609.38867
**作者**: Terumi Chiba, Guangzhi Sun, Zheqi Yuan, Chao Zhang
**来源**: cs.AI eess.AS
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) computer-use agents are typically evaluated with clean written instructions, despite speech being an increasingly popular interface for interacting with such systems. Speech input introduces an additional failure point: transcription errors can alter task-critical entities, constraints, or targets before the agent begins reasoning, while conventional ASR metrics do not directly measure whether the information required for successful execution has been preserved. We introduce Talk2Agent, a benchmark for evaluating how effectively voice interfaces convey human-spoken instructions to LLM-based computer-use agents. Talk2Agent builds human-spoken versions of tasks from WildClawBench and OSWorld and evaluates a range of voice interfaces, including dedicated ASR models, audio-capable LLMs, contextual biasing, and LLM-based ontology repair. Because repeatedly executing long-horizon computer-use tasks is costly and stochastic, we further propose an execution-free, tas

---

### [28] LEARN-TS: LLM-Enhanced Alignment and Reconstruction with Normality Guidance for Multivariate Time-Series Anomaly Detection

**链接**: https://arxiv.org/abs/2609.38789
**作者**: Jahyeob Koo, Kio Yun, Byoungmo Koo, Jun-Geol Baek
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reconstruction errors in multivariate time-series anomaly detection may not reliably distinguish abnormal behavior from benign deviations. Language-derived semantics offer complementary context, but existing multimodal approaches may rely on time-associated paired textual information that is difficult to obtain consistently and is not provided by standard multivariate time-series anomaly detection benchmarks. This setting poses two challenges: (1) conditioning masked reconstruction on window-specific semantics without exposing exact numerical targets or anomaly-specific cues, and (2) using a window-independent concept of normality as a complementary semantic reference rather than an independent anomaly detector. We propose LLM-Enhanced Alignment and Reconstruction with Normality Guidance for Time Series (LEARN-TS), which uses a frozen language model to construct two role-separated semantic representations without requiring temporally paired external text. Window-specific observation se

---

### [29] Diversity Combining for Multi-Path LLM Reasoning

**链接**: https://arxiv.org/abs/2609.38829
**作者**: Guangsheng Yu and Litianyi Zhang and Qin Wang and Xu Wang and Mingyuan Li and Shaoxiong Ji and Ren Ping Liu and Massimo Piccardi
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-path reasoning methods such as self-consistency (SC) sample $K$ reasoning paths and choose the most frequent answer. However, their gains quickly plateau as $K$ increases, and existing methods do not predict when this saturation will occur. We formalize multi-path LLM reasoning as a diversity combining problem from wireless communications: each path is a noisy channel observation, and the pairwise correlation of path correctness caps the design-effect effective sample size of the vote at a finite ceiling. Generalized least squares (GLS) analysis shows that, under exchangeability, the optimal symmetric linear combiner of latent embeddings is uniform, supporting majority vote as the natural default in standard SC while leaving room for weighting or pruning under heterogeneous prompt-template branches. Across 5 models and 12 benchmarks, prompt-template diversity reduces path correlation in $55$ of $57$ valid cells, with the strongest effect on open-ended QA. We derive an Adaptive-K 

---

### [30] Right Answers, Costly Models: The Efficiency Gap in LLM-based Optimization Modeling

**链接**: https://arxiv.org/abs/2609.38884
**作者**: Zhong Li, Xin Huang, Jinhui Wan, Xiangyi Wang, Shenkai Zhang, Ruiqi Chen 等 (9 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Optimization modeling formulates real-world decision problems as mathematical programs that solvers can use to find optimal decisions. Large language models (LLMs) can automate this process, but the resulting correct formulations can require substantial time and memory to construct and solve, limiting practical scalability. Therefore, we systematically investigate whether LLMs can identify problem structure from natural-language descriptions and apply suitable optimization modeling techniques to generate mathematical models and solver code that solve the problems correctly and efficiently. To this end, we first curate OptTips, a knowledge base of 50 expert modeling techniques in eight families. Using this knowledge, we develop OptDachshund, a multi-agent framework that transforms problems from existing optimization benchmarks into new tasks for evaluating LLMs' use of modeling techniques. It constructs conventional and expert mathematical models with solver code for the same task and d

---

### [31] Values as Style: Disentangling Values from Semantics with One-Way Mixing for Low-Damage LLM Steering

**链接**: https://arxiv.org/abs/2609.39701
**作者**: Jiale Dai, Hongcan Deng, Liuxian Ma, Xiaoke Niu, Guojie Song
**来源**: cs.AI cs.CY cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Value steering should change an LLM's normative priorities while preserving the scenario, facts, and task constraints underlying its answer. Conventional activation edits often change both. We introduce an editable semantic-value interface on frozen residual states, with a one-way semantic-to-value pathway that grounds value recognition in context. Stop-gradient blocks feedback through this pathway; swap consistency, topic de-confounding, and decorrelation encourage selective codes. At inference, editing the value code produces a residual delta while holding the semantic code fixed. On two instruction-tuned backbones, this interface improves semantic preservation and reduces benign refusals at comparable value alignment. A matched mixing-by-gating ablation separates representation learning from selective edit activation, and dimension-matched probes establish improved code selectivity. Against validation-selected prompting on LLaMA-3.1-8B, the method achieves comparable alignment (0.75

---

### [32] Training LLM Judges from Language Feedback via Position-Selective Self-Distillation

**链接**: https://arxiv.org/abs/2609.38792
**作者**: Ilgee Hong, Changlong Yu, Zhenghao Xu, Xin Liu, Yuwei Zhang, Qin Lu 等 (8 人)
**来源**: cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We study training LLM judges from natural language feedback, especially for subjective tasks where the verdict depends strongly on which evaluation criteria the judge invokes and how it weighs them. The dominant approach, outcome-supervised RL (e.g., GRPO), credits every token in the rollout with a single scalar determined only by the accuracy of the final verdict, providing no separate credit at the criterion-choice tokens and ignoring the rich language feedback (e.g., preference rationales) that naturally accompanies preference labels. Self-Distillation (SD) is one natural way to use this language feedback: the same model, conditioned on this feedback, acts as a teacher providing dense, position-level supervision. However, not all positions carry equally useful signal. Using the per-position entropy shift between teacher and student, we identify two regimes: context sharpening, where the teacher concentrates probability on a particular feedback-aligned criterion expression, and conte

---

### [33] First Things First: Teaching LLM-Based Agents to Prioritize Must-Haves before Nice-to-Haves

**链接**: https://arxiv.org/abs/2609.05224
**作者**: Tianjie Ju, Xinyue Xu, Wanxuan Sun, Lingxiao Diao, Gongshen Liu, Zhuosheng Zhang 等 (7 人)
**来源**: cs.CV
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [34] Large Language Model-Driven Small-Capitalization Trading: Integrating Financial News Sentiment, Macroeconomic Indicators, and Technical Signals

**链接**: https://arxiv.org/abs/2608.12283
**作者**: Alireza Kargarzadeh, Nariman Khaledian, Navid Parvini, Arman Khaledian
**来源**: q-fin.PM cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [35] What Can Component-Replacement Evidence Establish? A Critical Scoping Review of Local Decisions in LLM Agents

**链接**: https://arxiv.org/abs/2609.39989
**作者**: Shuyang Zhang (The Hong Kong Polytechnic University), Jianshuo Chang (The Hong Kong Polytechnic University)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Background. A component replacement in a language-model agent changes an execution trajectory, potentially altering later observations, resource use, and recovery opportunities. Different evidence is needed to assess its task-level benefit and the contribution of local decision quality. Methods. This critical scoping review maps 348 studies and examines 90 comparison records: 88 from 40 included studies and two from supplementary studies. Eight purposively selected cases structure the synthesis around the replaced decision, executed conditions, measurement comparability, controls, and remaining explanations. Results. Of 222 studies reporting local decision metrics, 142 also report measured task endpoints and 49 report proxies. These counts identify studies that report both types of measurement, without establishing that the measurements come from matched comparisons. Outcome Monitors reports a package-level completion gain whose attribution to detector quality remains limited; First-ch

---

### [36] Taming Speculative Search for Test-Time Scaling in LLM Serving

**链接**: https://arxiv.org/abs/2609.39334
**作者**: Jinwoo Jeong (Korea University), Woohyung Choi (Korea University), Myeongjae Jeon (POSTECH), Jeongseob Ahn (Korea University)
**来源**: cs.DC cs.CL cs.OS
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Test-time scaling has recently emerged as a powerful approach for improving LLM reasoning by allocating additional computation during inference, substantially enhancing accuracy on challenging tasks such as mathematics and coding. To accelerate the exploration of reasoning paths, recent studies proposed speculative execution. However, we show that supporting speculative execution poses two unique challenges for LLM serving systems: (1) an explosion in the search space of candidate paths and (2) frequent, fine-grained verification tasks for candidates. To address these challenges, this paper proposes SpecScale, a serving system for efficient speculative execution. We introduce three techniques to reconcile the trade-off between latency and computational overhead: (1) early pruning of low-quality candidate paths, (2) deduplicating computation across redundant candidate paths, and (3) deferring fine-grained verification tasks. We evaluate SpecScale on challenging reasoning benchmarks, inc

---

### [37] Covert Assistance: Helpful LLM Agents Evade Oversight in Multi-Agent Systems

**链接**: https://arxiv.org/abs/2609.39050
**作者**: Deema Alnuhait, Gengyu Wang, Muhammad Khalifa, Hao Peng
**来源**: cs.CR cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As multi-agent systems enter high-stakes domains, the possibility that agents may circumvent safety boundaries is a growing concern. Prior work has examined this risk primarily in adversarial settings, where agents are instructed or rewarded to communicate covertly and evade oversight. We show that benign agents can cross the same boundaries without adversarial incentives. We emulate a software-engineering workflow in which a planner represents a company hiring an external developer. The planner writes requirements and holds a company credential it is instructed not to disclose to the developer; a monitor screens their exchanges. Seven of nine tested frontier models disguise the credential in their requirements to help the developer recover it while evading the monitor, even after completing their assigned objective. For example, across 6,000 episodes with DeepSeek-V4-Pro, the planner attempts concealment in 16.9%; in 0.9%, the credential evades the monitor and is recovered and used by

---

### [38] VirusCascade: Hijacking Collaborative Reflection in LLM-Powered Recommender Agents

**链接**: https://arxiv.org/abs/2609.38270
**作者**: Yurong Hao, Wen Zhou, Guowei Guan, Tiantong Wu, Fuyao Zhang, Wei Yang Bryan Lim
**来源**: cs.CR cs.LG cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Advancing beyond traditional static scoring models, LLM-powered agentic recommender systems (LLM-ARS) instantiate users and items as autonomous agents, whose semantic states are dynamically refined through a recurrent process known as collaborative reflection. While this mechanism improves recommendation quality, it simultaneously introduces a systemic vulnerability: adversarial evidence injected into a single agent can be rationalised into a legitimate preference narrative, written back into memory, and propagated to other agents through interaction contexts. We term the local rationalisation process reflection laundering, and its system-wide escalation through collaborative reflection collaborative-reflection hijacking. Existing attacks on recommender systems, whether based on interaction-level data poisoning or text-level adversarial perturbations, assume static pipelines and thus cannot exploit this recurrent, multi-agent amplification pathway. To bridge this gap, we first conduct 

---

### [39] How Much of a Harness Does a Strong Agent Need for Autonomous ML Engineering?

**链接**: https://arxiv.org/abs/2609.40303
**作者**: Kirill Brilliantov, Alejandro Hern\'andez-Cano, Emmanuel Abb\'e
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent autonomous machine learning engineering (MLE) agents have made significant progress on public leaderboards. Often motivated by progress stagnation over long-horizon cycles and limited Large Language Model (LLM) primitives, modern MLE agents are deployed on top of increasingly elaborate machinery: multi-agent orchestrators, dedicated retrieval subagents, and more. While such harnesses expand, the use of more primitive but improved coding agents - where LLMs have direct access to the execution environment through read, write, and bash primitives - has received little attention in the field. In this paper we find that, under an equal time budget and the same frontier LLM backbone, open-source state-of-the-art harnesses provide no advantages over a single session of a minimal-harness coding agent baseline, pointing to the backbone as the primary driver for performance. Via a series of large-scale systematic ablation studies, we argue that the machinery layers become redundant in the

---

### [40] SR-Fraud: An Outcome-Supervised Reflective LLM Agent Framework for Non-Stationary Payment Fraud Detection

**链接**: https://arxiv.org/abs/2609.27287
**作者**: Xuwei Tan, Yao Ma, Xueru Zhang
**来源**: cs.LG cs.CR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [41] EDGC: Entropy-driven Dynamic Gradient Compression for Efficient LLM Training

**链接**: https://arxiv.org/abs/2511.10333
**作者**: Qingao Yi, Jiaang Duan, Jun Zhang, Haiyan Zhao, Shiyou Qian, Dingyu Yang 等 (8 人)
**来源**: cs.LG cs.AI cs.PF
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [42] From Search to Signal: Online Post-Training in Automatic Heuristic Design

**链接**: https://arxiv.org/abs/2609.39383
**作者**: Yilun Yuan, Tianyu Zhou, Zhenzhou Tang
**来源**: cs.LG cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM)-based automatic heuristic design (AHD) iteratively proposes and refines heuristics, pairing design rationales with executable code. Task-specific evaluators assess programs; execution outcomes and performance scores guide search. Many AHD systems keep the generator frozen; EvoTune and Co-Evolution of Algorithms and Language Model (CALM) instead update it from evaluated candidates. When such outcomes drive reinforcement learning with verifiable rewards (RLVR), they create a search-coupled loop: the evaluated candidate stream supplies both search-state updates and training signals for the model that generates future candidates. Yet validity and performance do not uniquely determine useful model updates; converting them into learning signals must account for the prompt and evolving search state that produced each candidate. We formulate online post-training of small open-weight LLMs in AHD as context-dependent signal construction and develop alternative mappings

---

### [43] TomasuLLM: Out-of-Order Speculative Execution for LLM Agents

**链接**: https://arxiv.org/abs/2609.38201
**作者**: Jiangnan Yu, Ceyu Xu, Mengming Li, Shiyu Huang, Yiran Xia, Jian Weng 等 (9 人)
**来源**: cs.CL cs.OS cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-running tools can dominate coding-agent latency: compilers, test suites, and repository commands take seconds to minutes while the agent idles. This observation stall presents the same tension that drove out-of-order processors -- asequential interface hides work that can be predicted and started early, but a speculative result may become visible only after it and every earlier step have been validated. We present TomasuLLM, a runtime that executes agent tool calls out of trajectory order while preserving task-execution correctness. It drafts future actions, runs them in isolated copy-on-write sandboxes, traces their dependencies and effects, and commits results in trajectory order only after validation against committed state. Across three benchmarks spanning sub-second to minutes-long tool calls, TomasuLLM improves the reported benchmark means and scales with tool latency: 1.31x on 100 SWE-bench Verified tasks, 1.35x on 28 Terminal-Bench 2.0 tasks, and 1.27x matched progress on 

---

### [44] Sequential Bayesian Evaluation of Large Language Model Behavior

**链接**: https://arxiv.org/abs/2511.10661
**作者**: Saatvik Kher, Shang Wu, Rachel Longjohn, Catarina Bel\'em, Padhraic Smyth
**来源**: cs.CL cs.LG stat.AP stat.ML
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [45] You're Hired: Strategic Model Selection for LLM Collaboration

**链接**: https://arxiv.org/abs/2609.38816
**作者**: Zongwan Cao, Ziyuan Yang, Shangbin Feng, Michael Duan, Skyler Hallinan, Bingbing Wen 等 (8 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> While multi-agent and model collaboration algorithms gain traction to combine the strengths of diverse Large Language Models (LLMs), existing systems remain bottlenecked on pre-defined and hand-crafted model pools. In this work, we investigate the problem of model selection in multi-LLM systems. We propose and systematically evaluate a taxonomy of 9 selection algorithms ranging from diversity of model descriptions, capability-aware behavioral diversity, and LLM-based recruiters. We conduct extensive experiments across two candidate pools of 10 and 32 models, deployed in four model collaboration algorithms, and evaluated across tasks spanning math, coding, QA, and reasoning. Results demonstrate that successful selection algorithms greatly outperform random or heuristics-based teams such as merely selecting the models with top individual performance, by up to 36.1% across settings. Specifically, capability- and training-based selection strategies alleviate selection variance and achieve 

---

### [46] WorkGenesis: Building the Worlds That Teach Agents to Work

**链接**: https://arxiv.org/abs/2609.39325
**作者**: Xinyu Zhu, Fenyi Liu, Yuzhu Cai, Shuo Tang, Rui Ye, Linfeng Zhang 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The ability of Large Language Model (LLM) agents to complete daily and professional work is receiving increasing attention. Training such agents requires realistic work scenarios. Expert-authored occupational work is costly and slow to produce, while unconstrained synthesis often yields tasks with weak factual grounding or internally inconsistent requirements. To bridge this gap, we introduce WorkGenesis, a framework that constructs executable occupational work from real-world artifacts through two core technical innovations: (1) Evidence-Based Work Construction, which grounds each unit of work in real-world evidence by retrieving public files guided by O*NET occupational knowledge and synthesizing the surrounding context, companion materials, work request, and itemwise rubric around them; and (2) Execution-Guided Consistency Verification, which renders a reference deliverable inside the constructed work, attributes every unsatisfied rubric item to the agent, the task, or the rubric, a

---

### [47] Learning What to Forget: Distributional Unlearning for LLM Representation Spaces

**链接**: https://arxiv.org/abs/2609.38929
**作者**: Pinaki Mohanty, Haoran Tang, Maggie Makar, Rajiv Khanna
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Machine learning systems increasingly face the need to remove the influence of entire data domains, such as toxic language, harmful behavior, or topical content, rather than isolated records. Recent work formalizes this problem as \emph{distributional unlearning}: selecting a subset of a forget domain whose removal moves the training distribution away from an unwanted population while preserving proximity to the desired one. However, existing analyses often impose parametric assumptions to obtain tractable selection rules. These assumptions may be poorly suited to high-dimensional language-model representations. We introduce \textsc{Mamushi}, a framework for non-parametric distributional unlearning that ranks forget examples using a probabilistic classifier whose Bayes-optimal logit equals the forget-to-retain log-density ratio (up to an additive class-prior constant). We show that thresholding the population log-density ratio yields the optimal fixed-budget selection rule for our remo

---

### [48] ShamAN-Q: Shampoo Augmented NanoQuant for Sub-1-bit LLM Weights

**链接**: https://arxiv.org/abs/2609.38521
**作者**: Jonathan Mei, Sang Hyub Kim, Oliver Knitter, Chi Chen, Martin Roetteler
**来源**: cs.LG cs.AI stat.ML
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We introduce ShamAN-Q, a sub-1-bit post-training quantization method that extends NanoQuant by replacing each its diagonal reconstruction geometry with a tractable dense curvature metric, using a general paradigm popularized by the Shampoo optimizer. For each linear weight, ShamAN-Q fits a Kronecker product to the empirical Fisher information matrix of a small calibration set by Kullback--Leibler minimization, forming a Mahalanobis reconstruction loss from the result. The continuous ADMM updates from NanoQuant become solutions to Sylvester equations, while its discrete projection and deployment format remain unchanged. Because the curvature is local to a given set of weights, ShamAN-Q re-measures the input curvature statistic for each layer immediately before layer factorization, periodically refreshing all statistics on the partially quantized model. ShamAN-Q also redistributes the uniform rank from NanoQuant across layers at the same total number of bits. On Qwen3-Base, ShamAN-Q lowe

---

### [49] Learning from Viable Failure Prefixes: Milestone Viability Potential Policy Optimization for Long-Horizon LLM Agents

**链接**: https://arxiv.org/abs/2609.37111
**作者**: Qi Zhou, Yuanfan Li
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [50] QATFactory: A Versatile, Deployment-Aligned Framework for Quantization-aware Training and Distillation of LLMs

**链接**: https://arxiv.org/abs/2609.39223
**作者**: Weili Xu, Jisen Li, Yuqing Jian, Chenxi Li, Zhizhou Sha, Yifan Yu 等 (10 人)
**来源**: cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) inference is increasingly moving toward lower precision to realize the throughput of hardware accelerators, but aggressive post-training quantization (PTQ) can degrade model quality. We present QATFactory, an open-source framework for deployment-aligned quantization-aware distillation (QAD) and reinforcement learning (QARL). QATFactory simulates deployment-time quantization while performing matrix multiplications in BF16, allowing models to adapt to quantization noise without requiring training hardware that natively supports the target format; for example, it supports NVFP4 training on H100 GPUs, which lack FP4 Tensor Cores. The framework supports NVFP4, MXFP4, and llama.cpp's Q4_K format; dense and mixture-of-experts models; and both full-parameter and LoRA-based training. It exports checkpoints directly to vLLM and llama.cpp without an additional lossy conversion step or added inference overhead. With QATFactory, we conduct extensive experiments on models 

---

### [51] A Proposed Rubric for Evaluating Expressed Clinical Reasoning in Large Language Model Responses

**链接**: https://arxiv.org/abs/2609.37788
**作者**: Zhangshu Joshua Jiang, Zina Ibrahim, James T. Teo
**来源**: cs.CL cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [52] Three Ways Classical Test Theory Can Mislead About LLM Judges

**链接**: https://arxiv.org/abs/2609.29709
**作者**: Louis Yiven Zhu
**来源**: cs.LG cs.CL stat.ME
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [53] Hiding in Plain Sight: Decoupling Pretext from Actuation for Skill Poisoning in LLM Agents

**链接**: https://arxiv.org/abs/2609.39352
**作者**: Wenxin Wu, Lingyong Yan, Lei Sha, Shuaiqiang Wang, Jiashu Zhao
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents increasingly rely on reusable Skills for complex, multi-step tasks, creating a critical supply-chain attack surface where poisoned Skill content steers agent decision loops under benign requests. Existing skill poisoning attacks either colocate actuation with its contextual pretext or distribute actuation across multiple Skills, but do not explicitly separate the rationale for execution from the operation itself. In this work, we reveal that untrusted agent decisions fundamentally depend on two conceptually distinct Risk-Realization Factors (RRFs): an actuation factor (specifying what concrete operation is performed) and a pretext factor (providing the situational rationale for why the agent must perform it). Guided by this abstraction, we propose a coordination-based attack paradigm: decoupling pretext from actuation. Rather than fragmenting the malicious actuation, we preserve it as an intact operation within a downstream Steering Skill, while delegating the pretext factor

---

### [54] Can Agents Trust Their Skills? Uncovering Unsafe Chains of Trust in Skill-Based LLM Agents

**链接**: https://arxiv.org/abs/2609.39065
**作者**: Yan Wang, Zhihao Zhang, Ke Chen, Kai Chen, Yaqin Zhang, Duohe Ma 等 (8 人)
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents increasingly rely on installable skills, which are packages of instructions, code, and resources that equip them with task-specific capabilities and, once installed, can be automatically invoked across subsequent user tasks. This creates a chain of trust in which users delegate authority to agents, while agent frameworks admit skill-provided content into the agents' context with insufficient validation, allowing malicious skills to influence agent behavior under that delegated authority. Yet, little is known about whether this trust model adequately constrains untrusted skill content before it reaches security-sensitive operations, or how frequently such trust violations arise in real-world agents. We present TrustProbe, a framework for uncovering unsafe chains of trust in skill-based LLM agents. First, TrustProbe analyzes agent source code to identify source-to-sink call paths from skill-controlled inputs to security-sensitive operations. Second, it generates semantically r

---

### [55] Contrastive Representation Shaping for LLM Unlearning

**链接**: https://arxiv.org/abs/2601.22028
**作者**: Haoran Tang, Rajiv Khanna
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [56] HARDE: Optimizing Agent Harnesses for Runtime Risk Detection and Execution Control

**链接**: https://arxiv.org/abs/2609.38291
**作者**: Zhuo Liu, Moxin Li, Zhixin Ma, Wentao Shi, Wenjie Wang, Fuli Feng
**来源**: cs.CR cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents are vulnerable to safety risks such as injected malicious instructions or misleading information, motivating runtime defenses that prevent unsafe action in execution across diverse risks while preserving benign-task utility. Existing system-level defenses either focus on risk detection rather than timely prevention or rely on predefined rules with limited flexibility across diverse risks. We propose a risk-aware harness that integrates LLM-based monitoring for flexible risk detection and structures monitor-guided execution around three core modules: trigger, monitor, and feedback, enabling targeted safety interventions while limiting disruption to benign task execution. To adapt the harness to different risks and deployment settings, we introduce HARDE, a two-stage harness optimization framework that first performs isolated probing of each module to derive an optimization guide, then uses this guide to iteratively optimize the harness based on safety a

---

### [57] "AI Psychosis" in Context: How Conversation History Shapes LLM Responses to Delusional Beliefs

**链接**: https://arxiv.org/abs/2604.13860
**作者**: Luke Nicholls, Robert Hutto, Zephrah Soto, Hamilton Morrin, Thomas Pollak, Raj Korpan 等 (7 人)
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [58] SimpleEvol: An Agent-Loop Framework for LLM-Driven Automated Heuristic Design with Minimal Human Priors

**链接**: https://arxiv.org/abs/2609.37172
**作者**: Jianghan Zhu, Cong Zhang, Rongjie Zhu, Chi Zhang, Zhiguang Cao
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [59] Fairness Beyond a Single Run: Training-Seed Variability in Speech LLM Adaptation

**链接**: https://arxiv.org/abs/2609.38976
**作者**: Srishti Ginjala, Eric Fosler-Lussier, Srinivasan Parthasarathy
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Demographic fairness gaps in automatic speech recognition are almost always reported from a single training run. We fine-tune the Q-former projector and LoRA adapters of a speech LLM at five audio compression factors and six random seeds, holding the encoder, base decoder, data and decoding fixed, and evaluate every run on Common Voice and Fair-Speech. At 460 h of clean LibriSpeech, the seed moves fairness metrics more than compression does on most demographic axes. A balanced 3x3 decomposition attributes 85.3% of the variation in Fair-Speech ethnicity normalized gap to the seed against 8.3% to compression (p = 0.009), though compression explains more on age and gender. Held-out LibriSpeech word error rate spreads by 0.04 points across those seeds while Common Voice spreads by 8.57, so these are not failed runs, and the effect survives controlling for accuracy and dropout. Scaling and diversifying the adaptation set to 960 h damps the effect but does not remove it. On Fair-Speech ethni

---

### [60] Towards a Belief-Based World Model for LLM Agents

**链接**: https://arxiv.org/abs/2609.00455
**作者**: Shubham Kumar, Harshit Kumar, Narendra Ahuja, Saurabh Jha
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [61] JustFit: Just-in-Time State Management for Local LLM Serving

**链接**: https://arxiv.org/abs/2609.17475
**作者**: Yuhua Chen
**来源**: cs.AI cs.PF
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [62] Explore-on-Graph: Hybrid Embedding-LLM Reasoning for Knowledge Graph Question Answering under Incompleteness

**链接**: https://arxiv.org/abs/2609.39786
**作者**: Ola El Khatib and Djellel Difallah
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly combined with knowledge graphs (KGs) to ground reasoning in structured evidence. However, most LLM-based KGQA methods rely on traversing existing graph edges and become unreliable when reasoning paths are broken by missing facts. Alternatives that ask LLMs to generate missing knowledge risk introducing hallucinated evidence. We introduce XoG (eXplore-on-Graph), a framework for multi-hop question answering over incomplete KGs that recovers missing reasoning paths from learned graph structure rather than LLM parametric knowledge. XoG combines type-level entity-relation statistics to identify candidate relations with KG embeddings to retrieve plausible missing entities, using the LLM as a semantic selector and reasoner. These mechanisms are integrated into an iterative planning-exploration-reasoning process. Experiments on WebQSP, CWQ, and the Wikidata-based BRINK benchmark show that XoG remains competitive on complete KGs and consistently out

---

### [63] Improving Fairness of Large Language Model-Based ICU Mortality Prediction via Case-Based Prompting

**链接**: https://arxiv.org/abs/2512.19735
**作者**: Gangxiong Zhang and Yongchao Long and Yuxi Zhou and Yong Zhang and Shenda Hong
**来源**: cs.LG
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [64] When Order Matters: First-Speaker Bias and Mitigation through Personality in Sequential Multi-Agent Debate

**链接**: https://arxiv.org/abs/2609.38964
**作者**: Duofeng Xu and Bryan Hooi and Dandan Qiao
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-agent debate (MAD) is often used to improve large language model (LLM) reasoning, but sequential debate is rarely a neutral aggregator of agents' opinions. We show that sequential MAD suffers from a pronounced first-speaker bias: agents disproportionately shape the final answer when they speak first. As a result, placing a stronger model after weaker ones can substantially offset its reasoning advantage. We then focus on the disadvantaged strong-agent-last setting and ask whether personality prompting can mitigate this imbalance. Drawing on the Big Five model, we study agreeableness and extraversion as behavioral interventions applied to either the strong or weak side. We find that their effects are trait-specific. Influence consistently shifts in the direction of lower agreeableness, and assigning low agreeableness to the stronger agent helps restore its lost influence and improves final accuracy. Extraversion, by contrast, produces less systematic changes in influence and accur

---

### [65] Diagnosing Training Inference Mismatch in LLM Reinforcement Learning via a Zero-Mismatch Reference

**链接**: https://arxiv.org/abs/2605.14220
**作者**: Tianle Zhong, Neiwen Ling, Yifan Pi, Zijun Wei, Tianshu Yu, Geoffrey Fox 等 (8 人)
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [66] Doc2LoRA Provides Decodable Representations of Scientific Ideas

**链接**: https://arxiv.org/abs/2609.38374
**作者**: Chand Sahil Mansuri, Joel Zachariah, Sadamori Kojaku
**来源**: cs.CL cs.DL cs.IR cs.LG physics.soc-ph
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Representing scientific papers as points in a space lets us search for similar papers and inquire about how fields relate to one another and drive innovation. Beyond search, the vector space of papers invites generation: mixing papers through simple vector operations creates new points, mirroring combinatorial novelty, the recombination of existing ideas into new ones. However, a mixed point often represents an idea no paper has yet realized, with no papers nearby to identify the idea. We propose representing each paper by a LoRA adapter generated by the Doc-to-LoRA hypernetwork. Every point in the space, including mixtures, thus represents a large language model (LLM) open to questions and instructions in natural language. On papers from the American Physical Society (APS), we instruct the LLM at the average of each subfield to name the field in a few words and obtain labels closer to the official names than the labels of five baselines, as judged by word overlap and a panel of five L

---

### [67] LLM Persona Unlearning

**链接**: https://arxiv.org/abs/2609.39882
**作者**: Kemou Li, Zhuan Shi, Qizhou Wang, Fengpeng Li, Negar Rostamzadeh, Golnoosh Farnadi 等 (7 人)
**来源**: cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Pre-training equips large language models (LLMs) with a broad repertoire of behavioral patterns associated with roles, styles, values, and goals. Post-training teaches conditional enactment and makes a helpful Assistant the default, but it does not erase alternative modes from the weights; explicit prompts can therefore elicit personas that repeatedly shape judgment, language, and action. In open-weight settings, runtime controls can be removed, motivating persona unlearning: a weight-level edit that makes a designated persona difficult to elicit and enact on unseen contexts. We introduce PersonaUnlearnBench, a model-specific paired benchmark spanning six LLMs from three families and five personas, with aligned forget/retain sets, held-out instruction paraphrases, and four-axis evaluation. The benchmark shows that standard unlearning methods cannot reliably erase the target persona without sacrificing meaningful generation or general utility. We therefore propose PaCE, which compares t

---

### [68] Steer-to-Detect: Probing Hidden Representations for Detection of LLM-Generated Texts

**链接**: https://arxiv.org/abs/2605.12890
**作者**: Luxu Liang and Xiang Li
**来源**: stat.AP cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [69] Lowest Span Confidence: Zero-Shot Hallucination Detection from a Single LLM Response

**链接**: https://arxiv.org/abs/2601.19918
**作者**: Yitong Qiao, Licheng Pan, Yu Mi, Lei Liu, Yue Shen, Jian Wang 等 (9 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [70] When Correct Memory Goes Wrong: Fuzzing Persistent Memory Use in LLM Agents

**链接**: https://arxiv.org/abs/2609.38275
**作者**: Yuqiao Meng, Luoxi Tang, Yingxue Zhang, Yuchen Yang, Zhaohan Xi
**来源**: cs.DC cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Persistent memory helps LLM agents carry information across long interactions, but correct memory can still be used incorrectly when queries change or memory states evolve. Existing work mainly studies memory content errors or evaluates fixed test cases, leaving memory-use failures hard to discover systematically. We formulate this issue as a fuzzing problem and categorize such failures into query-related and memory-state failures. We then develop U-Fuzz, which starts from memory checkpoints as test seeds, mutates queries or memory states under explicit mutation obligations, validates each mutant, and uses observed memory behavior to guide iterative testing while keeping failure labels outside the search. We evaluate U-Fuzz across several memory systems against diverse fuzzing baselines, and further test an output-only setting with API-based LLMs where memory retrieval is hidden. Across these settings, U-Fuzz consistently uncovers more confirmed memory-use failures, showing that its se

---

### [71] Large Language Model-Guided Evolutionary Discovery of Native Neural Architectures for Spiking Sequence Modeling

**链接**: https://arxiv.org/abs/2609.40258
**作者**: Ruoyu Zhao, Jiaqi Wu, Chenyu Zhu, Zhichao Lu
**来源**: cs.NE
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Spiking neural networks (SNNs) offer low-energy sequence modeling through sparse, event-driven computation. However, interactions among spike encoding, neuronal dynamics, and information propagation complicate architecture design. Existing SNN sequence models often adapt artificial neural network (ANN) architectures designed for real-valued activations, potentially underusing spike-based communication and temporal state updates, motivating automated discovery of native SNN architectures. Most evolutionary neural architecture search (ENAS) methods operate within predefined configuration spaces, limiting discovery to mechanisms expressible within those spaces. We introduce OpenArchEvo, which uses large language models (LLMs) to evolve executable architecture code in an open program space under spiking-projection constraints. In this space, code differences need not reflect architectural novelty, while direct performance evaluation requires costly training. We construct a three-view repre

---

### [72] Sense and Sensitivity: Benchmarking LLM Clinical Triage Recommendations with Physician Experts

**链接**: https://arxiv.org/abs/2609.38600
**作者**: Abinitha Gourabathina, Haoran Zhang, Yuexing Hao, Walter Gerych, Marzyeh Ghassemi
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As large language models (LLMs) are increasingly used in clinical settings, it is critical to evaluate their reliability under realistic variation in clinical text. We study this question in clinical triage, comparing LLMs to practicing physicians under text perturbations that preserve the underlying clinical setting. We introduce a benchmark of over 6,000 clinical scenarios, 7,000 physician annotations, and 225,000 model responses. Using this benchmark, we make two key observations. First, LLMs are more likely than physicians to recommend unnecessary care at baseline, and this tendency increases under perturbed inputs. Further, we find that LLM recommendations are more sensitive to gender and tone perturbations than human recommendations. Together, these results demonstrate that LLMs can vary under clinically irrelevant textual changes, highlighting the need for deployment-oriented evaluations grounded in expert physician behavior.

---

### [73] TensorHub: Scalable and Elastic Weight Transfer for LLM RL Training

**链接**: https://arxiv.org/abs/2604.09107
**作者**: Chenhao Ye, Huaizheng Zhang, Mingcong Han, Baoquan Zhong, Xiang Li, Qixiang Chen 等 (10 人)
**来源**: cs.DC cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [74] Consensus and Factual Dynamics in Large Populations of Interacting Language Models

**链接**: https://arxiv.org/abs/2609.39211
**作者**: Emanuele Ricco, Elia Onofri, Vincenzo Sammartino, Roberto Di Pietro
**来源**: cs.MA
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Model (LLM) agents are increasingly deployed as populations of interacting entities, in which consensus --agreement on a shared answer-- emerges as a collective, unengineered behaviour. Prior work on LLM consensus shows that agents can cross-verify their answers and converge towards more factual responses, treating agreement as a proxy for correctness. However, these studies usually fix a single interaction structure, leaving open how consensus depends on how agents interact. We address this gap by introducing RHEON, a physics-inspired framework that recasts a population drawn from a single frozen model as an evolving $O(n)$ spin system on a ladder of interaction geometries of increasing effective dimension --from a 1D ring to a full-coupling mean-field graph-- with the sampling temperature $T$ as the tunable source of thermal disorder, evolved through a Glauber-like asynchronous dynamics. Sweeping RHEON across $432$ configurations of prompt, population size, communicati

---

### [75] Offline Guidance, Online Reasoning: Reusing LLM Feedback for Small Language Models

**链接**: https://arxiv.org/abs/2609.39346
**作者**: Bohan Zhang (1), Linan Yue (1), Weibo Gao (2), Pengyu Chen (1), Hong Guo (1), Yanqi Hao (3) ((1) Southeast University 等 (8 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) offer strong reasoning capabilities but are often costly to access through commercial APIs, while small language models (SLMs) are easier to deploy locally yet remain weaker in reasoning. This capability-deployment gap has motivated LLM-SLM collaboration, which aims to improve SLM reasoning using LLM capabilities while preserving the deployment advantages of SLMs. Existing approaches mainly follow two paradigms. Knowledge distillation uses LLM-generated answers and reasoning trajectories to train SLMs offline, but requires parameter updates and additional training. Alternatively, online collaboration routes difficult problems to an LLM or leverages LLM-generated guidance and corrections when an SLM encounters difficulties. Although effective, online collaboration requires repeated LLM access. Moreover, the guidance produced for a particular problem is discarded after inference and cannot benefit subsequent problems involving similar reasoning states. In the

---

### [76] An Empirical Study of Reward Specification and Benchmark Reliability in GRPO-based LLM Unlearning

**链接**: https://arxiv.org/abs/2608.17804
**作者**: Rub\'en Balbastre, Juan Manuel Ordu\~na, Mariano P\'erez
**来源**: cs.LG cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [77] PhantomEnvironments: Training LLM Agents in Fictional Worlds

**链接**: https://arxiv.org/abs/2609.40221
**作者**: Anmol Kabra, Swathi Saravana Selvam, Albert Gong, Chao Wan, Christian Belardi, Dongyoung Go 等 (8 人)
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Training LLM agents with reinforcement learning (RL) is bottlenecked by environments, which must provide verifiable rewards, support long-horizon interaction, and scale cheaply. Existing approaches rely on costly human-curated data or on LLM-generated environments that risk hallucinations and benchmark contamination. We show that LLMs can instead be trained into capable search agents using synthetic environments generated entirely by rules, whose generation requires no LLM and has zero marginal cost. We build PhantomEnvironments, multi-turn RL environments from fictional worlds, where agents must search a corpus of templated articles to answer multi-hop questions. Despite sharing no facts with the real world, these strikingly simple environments yield agents that transfer to real-world multi-hop search benchmarks, often outperforming real-world training data on newer benchmarks. Trained agents generalize to unseen fictional universes, and Qwen models learn to scale their search budget 

---

### [78] Absorbing State Phase Transitions in Multi-Agent Search

**链接**: https://arxiv.org/abs/2609.38327
**作者**: Wenwen Zheng, Yuzhe Yang, Helen Qu, Xin Eric Wang, Haewon Jeong
**来源**: cs.MA
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Nontrivial dynamics can emerge in large language model (LLM)-based multi-agent systems, and preliminary evidence exists that formalisms from statistical mechanics can be effective at modeling and predicting such behaviors. In parallel, designing multi-agent communication topology for optimal task-solving is an active research question. In this paper, we focus on predicting the success of multi-agent search tasks using the formalism of absorbing state phase transitions. We first taxonomize search tasks into four types, informed by classical results in combinatorial search. We then theoretically derive a critical communication degree $d_c$, the minimum number of agents each agent can communicate with, above which incorrect hypotheses do not proliferate uncontrollably and the search enters the solved state. Finally, we evaluate frontier LLM-based multi-agent systems on real-world search and discovery tasks, software configuration debugging and physical mechanism discovery, and find that a

---

### [79] Stress-Testing LLM Lie Detectors: Role-Play Failures and Spurious Correlations

**链接**: https://arxiv.org/abs/2609.39807
**作者**: Maximilian von Klinski, Sebastian Lapuschkin, Wojciech Samek, Lennart B\"urger
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Lie detection probes aim to predict from a language model's internal states whether its output is truthful or dishonest. However, role-play complicates what "truth" means for an LLM: language models can adopt a wide range of personas that take very different claims to be true, including personas whose beliefs clearly contradict reality, such as a conspiracy theorist. In this work, we investigate whether lie detection probes reliably flag falsehoods generated under such an anti-factual persona or whether they instead follow the persona's beliefs. We introduce a dataset of 8,916 human-reviewed, on-policy responses from three LLMs adopting anti-factual personas. Evaluating eight probes from prior work, we find that many fail in this setting, particularly when correct and incorrect answers are evaluated under the same persona prompt. To investigate why, we construct three novel confounder datasets in which truth is anti-correlated with a potential confounding concept. Our experiments revea

---

### [80] SkillMaster: Toward Autonomous Skill Mastery in LLM Agents

**链接**: https://arxiv.org/abs/2605.08693
**作者**: Min Yang, Jinghua Piao, Xu Xia, Xiaochong Lan, Jiaju Chen, Yongshun Gong 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [81] Working Around the Compute Ceiling: Byte-Exact Memory in Galahad Makes LLM Reading a One-Time Cost LLM Reading a One-Time Cost

**链接**: https://arxiv.org/abs/2609.39358
**作者**: Sietse Schelpe
**来源**: cs.CL cs.AI cs.IR cs.LG cs.PF
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A transformer language model performs a bounded amount of computation per token, and recent work by Vishal Sikka, former CEO of Infosys, argues that this bound limits which tasks a model can carry out or verify (

---

### [82] GeoFP8: Geometry-Aware FP8 Gradient Compression for Distributed LLM Training

**链接**: https://arxiv.org/abs/2607.07494
**作者**: Jieying Wang, Zizhong Wang, Fangru Linghu, Shuyuan Fan, Jiajia Li, Zhao Zhang
**来源**: cs.DC cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [83] From Spectra to Joint Schedules in LLM Pre-training: 3+3(+2) Scaling-Law Regimes

**链接**: https://arxiv.org/abs/2609.40148
**作者**: Yichen Wang, Fanghui Liu, Yudong Chen
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Power-law learning curves are often treated as fixed properties of a model and its data, although learning-rate and batch-size schedules can change the observed loss. We study this dependence in noisy online SGD with linear random features. Conditional on the representation, an exact Volterra equation separates two response components: a forcing term that propagates unresolved target error and a memory kernel that propagates stochastic-error injections. We prove that either component follows a power law if and only if its cumulative weighted spectral mass has the corresponding low-spectrum scaling; individual eigenvalues and target coefficients need not obey coordinatewise power laws. Under a joint schedule, intrinsic time $T_t=\sum_{s<t}\eta_s$ controls optimization progress, while $r_t=B_t/\eta_t$ controls noise injection. Their interaction yields sharp conditions under which a schedule preserves, changes, or destroys the clean power law, together with a memory ceiling on noise reduc

---

### [84] Speculative Safety Honeypot: Toward Proactive Defense Against Multi-turn Agent Attacks

**链接**: https://arxiv.org/abs/2609.39549
**作者**: Zezhong Wang, Xueyang Tang, Rui Lian, Yang Lou, Heqing Huang
**来源**: cs.CR cs.AI cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As Large Language Model (LLM) agents are increasingly deployed in complex environments, multi-turn interaction attacks have become a significant security challenge. Existing detection methods typically rely on historical context. However, this retrospective logic struggles to identify deep malicious intents that are split across turns to hide future risks. Inspired by speculative decoding, we propose the Speculative Safety Honeypot (SSH) framework. SSH uses a multi-agent simulation system composed of small LLMs to build an action-level speculate-and-verify workflow. In the speculation stage, SSH predicts future behaviors of the target agent and asynchronously builds a trajectory tree to expose potential risks in advance. In the verification stage, the system uses the target agent's real actions to calibrate and prune the trajectory tree, effectively reducing false positives. As a plug-and-playable component, SSH provides existing detectors with rich decision redundancy beyond the curre

---

### [85] TwinRouterBench: Fast Static and Live Dynamic Evaluation for Realistic Agentic LLM Routing

**链接**: https://arxiv.org/abs/2605.18859
**作者**: Pei Yang, Wanyi Chen, Tongyun Yang, Pengbin Feng, Jiarong Xing, Wentao Guo 等 (10 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [86] Linguistic Loopholes in LLM Unlearning: From a 174-Language Benchmark to Coverage-Aware Unlearning

**链接**: https://arxiv.org/abs/2609.40286
**作者**: Tyler Skow, Shravan Chaudhari, Rama Chellappa, Abhay Yadav
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Unlearning a fact in one language does not guarantee its removal in others as changing the query or even the requested answer language can reopen seemingly forgotten knowledge -- a cross-lingual loophole. The most straightforward solution to this challenge -- unlearning in all languages -- is neither scalable nor desirable as it amplifies damage to unrelated model capabilities. We introduce the task of language budgeted multilingual unlearning where the goal is to select a subset of languages that maximizes cross-lingual erasure. To study this task we introduce the Cross-Lingual Unlearning Tensor, an unlearning benchmark that spans 174 language--script pairs and 25 atomic paraphrase types to examine when forgetting generalizes across linguistic expressions of the same knowledge. We further propose COVER, which selects source languages to maximize predicted COVERage of languages receiving no forget supervision, enabling unlearning on a language budget. Surprisingly, we find naively sele

---

### [87] Preemptive LLM Unlearning against Forbidden Capability Acquisition via Gradient Sealing

**链接**: https://arxiv.org/abs/2609.39866
**作者**: Kemou Li, Qizhou Wang, Yue Wang, Fengpeng Li, Zhuan Shi, Negar Rostamzadeh 等 (9 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Open-weight LLMs are released not only as fixed products but also as substrates for downstream fine-tuning. This openness, however, creates legal and ethical risks because users may misuse fine-tuning to instill illicit knowledge or enable hostile operations. Model providers therefore need apre-release defense against such acquisition, motivating the problem of preemptive unlearning. Unlike retrospective unlearning, which removes capabilities already present in a fixed model, preemptive unlearning seeks to prevent their acquisition under unseen attack data and future fine-tuning procedures. Despite its practical importance, this setting remains largely unexplored, presents distinct challenges, and is therefore the central focus of our work. We first verify that existing retrospective methods provide insufficient pre-release protection. Even when forbidden capabilities are suppressed in current outputs, forbidden-domain data can still induce gradients through internal pathways, enabling

---

### [88] LLM Parkinsonism: Executive-Control Failure, Token-Inefficient Persistence, and an Uncertainty-Aware Global Executive Control Architecture for Autonomous Language-Model Agents

**链接**: https://arxiv.org/abs/2609.30662
**作者**: Dongsheng Xiao, Zeyuan Wang, Xuzhe Xia, Bo Zhao, Yankai Cao
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [89] MERGE: Multi-LLM Ensemble for Retrieval via Generative Enrichment

**链接**: https://arxiv.org/abs/2609.37574
**作者**: Tzu-I Ho, Yung-Yu Shih, Shang-Yu Su, Dongzhe Wang, Yun-Nung Chen
**来源**: cs.IR cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [90] MoEless: Efficient MoE LLM Serving with Serverless Experts

**链接**: https://arxiv.org/abs/2603.06350
**作者**: Hanfei Yu, Bei Ouyang, Shwai He, Ang Li, Hao Wang
**来源**: cs.DC cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [91] Reach Into The CHOIR: Free-List Elicitation Uncovers Distinct Model Voices in LLM Ensembles

**链接**: https://arxiv.org/abs/2609.38448
**作者**: Ben Wigler, Maria Tsfasman
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Open-ended LLM homogeneity can create false plurality when several systems appear to offer independent perspectives while returning the same familiar default. Single-pass answers obscure the distinction between agreement produced by a tightly constrained answer space, prompt-vocabulary echo, and broader answer spaces with stable alternatives beneath the surface. We introduce CHOIR (Collective Hierarchically-Ordered Inquiry Responses), a framework that adapts free-list elicitation from cognitive anthropology to LLM ensembles. CHOIR repeatedly elicits ranked lists, clusters items into prompt-level concepts, and measures concept salience across models, prompt variants, and persona conditions. We evaluate CHOIR on Infinity-Chat 100, an external prompt bank from recent work on open-ended model homogeneity, and on a 27-question targeted diagnostic bank designed to isolate mechanism-level contrasts. On Infinity-Chat 100, CHOIR reproduces high surface agreement (93/100 prompts above chance) wh

---

### [92] The Row Normalization Puzzle in Muon

**链接**: https://arxiv.org/abs/2609.39114
**作者**: Jiayu Zhang, Tianyi Lin
**来源**: cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> This paper examines how row-wise renormalization affects Muon, focusing on the gap between NorMuon's worst-case guarantees and its practical performance (Li et al.). Despite its growing adoption and promising performance in large language model (LLM) pretraining, NorMuon's worst-case guarantees remain poorly understood. One fundamental question is: Does row normalization yield provable convergence gains, potentially through its interaction with approximate polar computation and exponential moving-average momentum? Our results show that row normalization introduces a dimension-dependent factor in the worst-case iteration complexity under the operator-norm geometry, which persists even with exact polar computation and any fixed momentum parameters. Indeed, we establish an algorithm-dependent lower bound and a matching upper bound in deterministic settings, and extend our upper bound analysis to stochastic settings. Both upper-bound analyses allow approximate polar computation. Experiment

---

### [93] Beyond Text: LLM-Based Dimensional Emotion Evaluation in Multimodal Dialogue

**链接**: https://arxiv.org/abs/2609.39072
**作者**: Yutong Hu and Jinho Choi
**来源**: cs.CL cs.AI cs.LG cs.MM
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Emotion recognition in conversation has been widely studied, but applying Large Language Models (LLMs) to continuous dimensional emotion evaluation in multimodal dialogue remains largely unexplored. We propose an LLM-based framework that performs discrete emotion recognition and Valence-Arousal-Dominance (VAD) dimensional evaluation on IEMOCAP, incorporating acoustic cues as natural language descriptions following the SpeechCueLLM approach. We evaluate six models spanning the LLaMA, GPT, and Qwen families under zero-shot prompting, few-shot prompting, and LoRA fine-tuning. LoRA fine-tuned LLaMA models substantially outperform prompt-engineered GPT models on both tasks despite GPT's larger scale, a gap we attribute to domain adaptation rather than model capacity. Our best model achieves a Valence CCC of 0.7822, a new state-of-the-art on IEMOCAP. Ablation studies confirm that textual audio descriptions meaningfully improve smaller models (+3.5 to 3.6 weighted F1) while contributing littl

---

### [94] Agent-Facing Information Design in LLM Tool Registries: A Preregistered Test of Rhetoric, Position and Structure

**链接**: https://arxiv.org/abs/2605.23916
**作者**: Haochuan Kevin Wang, Zechen Zhang
**来源**: cs.IR cs.AI econ.GN q-fin.EC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [95] dattri-LLM: A Unified and Efficient Library for Training Data Attribution at LLM Scale

**链接**: https://arxiv.org/abs/2609.38767
**作者**: Shixuan Liu, Tongli Zhou, Junwei Deng, Pingbang Hu, Jiaqi W. Ma
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Training data attribution (TDA) estimates the contribution of individual training examples to model outputs. Most scalable TDA methods rely on per-example gradients, whose computation and use at LLM scale pose challenges in efficiency, compatibility, and extensibility. We introduce dattri-LLM, a TDA library that makes gradient-based attribution more practical at scale. For efficiency, dattri-LLM uses compact gradient representations and dynamically routes gradient operations based on a cost model. For compatibility, its capture mechanism collects per-example gradients from existing training loops that call backward(), without requiring changes to the loop or its configuration. This includes distributed training with DDP and FSDP and pipelines built with HuggingFace Transformers, TRL, and OLMo. For extensibility, dattri-LLM exposes reusable gradient operations and training-time callbacks for implementing attribution methods and applications. These interfaces support a variety of attribu

---

### [96] Atomic and Holistic LLM Judges for Reference-Grounded Support Labels: A Prompt-Controlled Comparison

**链接**: https://arxiv.org/abs/2603.28005
**作者**: Xinran Zhang
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [97] SparLeak: Privacy Leakage from Sparse Attention in LLM Inference on Shared GPUs

**链接**: https://arxiv.org/abs/2609.38830
**作者**: Fahao Chen, Linkang Du, Jinhao Zhou, Peng Li, Zhou Su
**来源**: cs.LG cs.CR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Sparse attention is widely used to accelerate long-context inference in modern large language models (LLMs), but its input-dependent execution behavior introduces previously unexplored privacy risks. We identify a new GPU micro-architectural side channel, termed Sparsity-Induced Memory Access (SIMA), which arises from secret-dependent key-value cache access patterns induced by sparse attention. Based on this observation, we present SparLeak, a phase-aware side-channel attack that extracts SIMA traces during LLM inference and enables two practical privacy extractions: query attribute inference from prefill-phase traces and autoregressive response reconstruction from decoding-phase traces. By reconstructing approximate token-level sparsity profiles from page-level observations and applying profiling-based learning, SparLeak accurately recovers sensitive information, including user-query attributes and private LLM response content. Extensive evaluation across three LLM architectures, thre

---

### [98] Comparative study of adapting pre-trained models for driving behavior video captioning

**链接**: https://arxiv.org/abs/2609.39542
**作者**: Sayak Mallick, Philipp Geiger, Augustin Kelava
**来源**: cs.CV cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> This report examines and compares some of the many fine tuning and prompting methods existing, applying them within the domain of autonomous driving. The idea is to compare these methods by adapting a Large Language Model (LLM) on a video dataset. LLM's have become extremely good at achieving a good understanding of different forms of data and this study aims to induce a low dimensional understanding of driving situations into our primary test model SpaceTimeGPT. Experiments on BDD-X (Berkeley DeepDrive eXplanation) dataset demonstrate good performance of the full fine tuning framework on some automatic metrics, and in some metrics, it even surpasses the baseline. We also try Low-Rank Adaptation (LoRA) and prompt engineering on VideoLLaVA model and discuss its limitations.

---

### [99] Faithful Dual-constrained Erasure for Robust LLM Safety Alignment

**链接**: https://arxiv.org/abs/2609.39279
**作者**: Jiaqing Li, Shide Zhou, Zhibo Zhang, Yuxi Li, Tianlong Yu, Kailong Wang
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Machine unlearning has emerged as a crucial mechanism for removing hazardous knowledge and enforcing safety alignment in Large Language Models (LLMs). However, recent studies reveal a persistent security risk: unlearned models remain highly vulnerable to retraining attacks, where suppressed malicious behaviors rapidly resurface after benign fine-tuning. In this work, we investigate the optimization dynamics of unlearning and identify that this vulnerability stems from shallow alignment. Rather than effectively erasing target knowledge, models often exploit a shortcut by activating previously dormant parameters to act as spurious suppressors, forming a fragile inhibitory shell over intact malicious representations. To address this issue and enforce authentic memory deletion, we propose FDCU, a novel dual-constrained subspace projection framework. FDCU restricts parameter updates through a highly scalable, element-wise dual-masking rule: it preserves general knowledge manifolds via Fishe

---

### [100] The Invisible Language Tax: Token Premiums of French and Regional Languages in 2026 LLM Tokenizers, and a French-Optimized Prototype

**链接**: https://arxiv.org/abs/2609.39001
**作者**: Thomas Serval
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM services are billed per token and context windows are measured in tokens, yet the number of tokens needed for the same content varies across languages. We measure this token premium on seven tokenizers of widely used 2026 models (OpenAI o200k, Llama 3, Qwen3, DeepSeek V3/V4, Gemma 3, Mistral Tekken, and the Claude generation-5 tokenizer via Anthropic's counting API) on NTREX-128 (124 non-English reference translations) and on the Universal Declaration of Human Rights for regional languages. French requires 31% to 58% more tokens than English, whereas Simplified Chinese ranges from 5% fewer to 40% more and is cheaper than French on six of the seven tokenizers. Regional and overseas languages of France pay roughly 1.6 to 3.3 times the English count. We discuss how history re-sending, tiered pricing and fixed context windows amplify the absolute gap in agentic use. In a controlled experiment (BPE, Europarl, 50k vocabulary), adding French to tokenizer training data quickly reduces the 

---

### [101] Explicit Trajectory Diversity for RL-Based Post-Training of LLM Agents

**链接**: https://arxiv.org/abs/2609.38805
**作者**: Huaiyu Fu, Heng Cao, Hao Wang, Jian Ya, Tao Chen
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents often admit multiple high-quality solutions to the same task, differing in reasoning structure, tool-use pattern, or interaction trajectory. Yet existing notions of diversity in LLM post-training are mostly implicit, arising from general stochasticity and regularization mechanisms rather than explicitly targeting task-relevant behavioral variation. While such implicit diversity can be useful, it does not directly specify which forms of behavioral variation should be encouraged for a given task. In this work, we study explicit trajectory diversity in RL-based post-training for LLMs. Our key idea is to define diversity through user-specified, task-specific trajectory descriptors, which map each sampled trajectory to an interpretable behavioral representation, and then measure diversity as a set-level functional over the resulting descriptor matrix. Building on this formulation, we introduce Trajectory-guided Joint Policy Optimization(TJPO), a single-policy framework that optim

---

### [102] Relational Priors as Convergence Pressure in LLM-Based Multi-Agent Systems

**链接**: https://arxiv.org/abs/2608.03239
**作者**: Ming Shen, Chao Shang, Sadat Shahriar, Devang Kulshreshtha, Yi Zhang, Sandesh Swamy 等 (7 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [103] Persistent Context Graphs for Efficient Memory Compaction in LLM Agents

**链接**: https://arxiv.org/abs/2609.40118
**作者**: Jingbo Yang, Kwei-Herng Lai, Xiaowen Wang, Zhaoxuan Tan, Pei Zhou, Mengting Wan 等 (9 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As LLM capabilities advance, agents are tackling increasingly complex tasks over longer horizons. Their growing interaction histories make memory compaction essential for staying within context windows and reducing prefill cost. Existing methods summarize the history or compress its KV cache, often adding model computation to preserve information for future requests. A new user request can change which history matters, but reassessing that history with the model requires re-encoding it if the KV cache has expired. Past attention provides signals of historical importance and dependencies between messages, while relevance to the current task must be assessed using the new user request. We introduce ReCAP, a memory compaction method that stores attention-derived importance scores and dependency links in a lightweight, persistent context graph. For each new request, ReCAP combines stored importance with relevance cues from the request and follows dependency links to select messages and the

---

### [104] RICE-Alpha: Reliability-Informed Correction with Event Graphs for LLM-Agent Stock Forecasting

**链接**: https://arxiv.org/abs/2609.34004
**作者**: Tong Liu, Lanmiao Liu, Xiang Hu
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [105] Forging LLM Authorship Fingerprints with Targeted Rewriting

**链接**: https://arxiv.org/abs/2609.38831
**作者**: Haohan Yuan, Simin Chen, Xi Niu, Hanqing Guo, Depeng Xu, Haopeng Zhang
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Model-attribution classifiers can often identify which language model produced a text, making model-specific writing patterns a signal of provenance. Accurate attribution on unmodified text, however, does not show whether the prediction still identifies the original source after deliberate rewriting. We formulate this problem as targeted fingerprint transfer: rewriting one model's output so that attribution classifiers assign it to a chosen target model. We study summarization, where different models receive the same document and express the same underlying content, providing a controlled setting for conditional generation. We introduce ForgePrint, a search-then-distil framework that first searches for rewrites that move attribution toward a target fingerprint, then distils the selected rewrites into a one-pass 4B Student model. On CNN/DM, the Student reaches 70.2% target success rate, outperforming both its Teacher (54.1%) and the strongest of six published rewriting baselines (39.3%)

---

### [106] MADBench: Benchmarking the Security of Multi-Agent Debate

**链接**: https://arxiv.org/abs/2609.39146
**作者**: Yuwan Liu, Jiaming Zhang, Yue Huang, Sisi Duan
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-agent debate (MAD) can improve large language model (LLM) reasoning by allowing multiple agents to exchange and critique their answers to the same task. However, the interactions that enable agents to correct mistakes can also spread adversarial errors and steer the agents toward an incorrect answer. Although some efforts have been made to examine particular attack types on MAD, systematic evaluation of MAD under diverse attacks remains limited. A central question is whether debate mitigates adversarial influence or amplifies it. In this paper, we present MADBench, a benchmark for evaluating the security of MAD. We organize attacks into a layered taxonomy following the MAD workflow, incorporating both established attacks and new strategies tailored to debate. We evaluate six attack families over 356 source tasks and 3,958 test cases, examining their effects on the final answer and the propagation of adversarial influence. Our results show that, under attacks, MAD does not necessa

---

### [107] Examining Variation in How Guided AI Tutors Resolve Student Impasses

**链接**: https://arxiv.org/abs/2609.38346
**作者**: Bakhtawar Ahtisham, Kirk Vanacore, Alessandra Napoli, Josh Arens, Ksenia Ionova, Clayton Cohn 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> When a student is stuck, a tutor faces the assistance dilemma: help given too early can hinder productive struggle, while help withheld too long leaves the student in a frustrating, persistent impasse (i.e., wheel spinning). Generative AI tutors increasingly use guardrails restricting answer-giving, yet little is known about how such tutors behave once an impasse persists. We analyze 20,462 student turns from 1,260 authentic sessions with a guided LLM chemistry tutor, identifying 6,630 impasse turns of three major types: conceptual errors, expressed uncertainty, or help-seeking. We then used these impasses to simulate three tutoring conditions to study variation in AI tutor guidance through impasses: baseline, no-direct-answer, and guided tutor. For a sample of 150 impasses, prompt specificity changed pedagogy: a baseline tutor provided the answer directly in 50.7% of responses, a no-direct-answer tutor asked a follow-up question every time, and the guided tutor responded in a wide var

---

### [108] Re-ranking and Late Interaction Drive Retrieval Quality: A Controlled Comparison of RAG Strategies for Scientific Question Answering

**链接**: https://arxiv.org/abs/2609.38473
**作者**: Bhagyesh Rathi, Eshan Chawla, William B. Andreopoulos
**来源**: cs.IR cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Retrieval-Augmented Generation (RAG) is now the standard way to ground Large Language Models (LLMs) in external knowledge, yet the design space of retrieval pipelines is large and the trade-offs between variants are not well understood, especially on domain-specific corpora at realistic scale. In this work, we present a controlled comparison of six retrieval strategies for scientific question answering: (i) classic top-k dense retrieval, (ii) LLM-based query rephrasing, (iii) query rephrasing followed by LLM-based reranking, (iv) multi-query fusion via Reciprocal Rank Fusion (RRF), (v) an agentic tool-call pipeline in which the generator decides for itself whether to retrieve, and (vi) late-interaction retrieval with ColBERTv2. All six pipelines share the same generator (Meta-Llama/Llama-3.1-8B-Instruct), prompt, and evaluation protocol; the five single-vector pipelines additionally share SPECTER2 embeddings and a Chroma vector store; and all six retrieve from the full corpus of 463,97

---

### [109] Self-Spec Verifiable Code Generation

**链接**: https://arxiv.org/abs/2609.39568
**作者**: Jiaru Qian, Yihong Dong, Yongmin Li, Hao Zhu, Bin Gu, Ge Li
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) may generate unreliable code on corner cases missed by testing, while formal verification can provide machine-checkable guarantees. Recently, researchers have proposed several benchmarks to evaluate the capabilities of LLMs in generating formally verifiable code, where LLMs need to formulate formal specifications, generate the corresponding code, and verify its correctness. However, existing benchmarks have two key limitations: (I) They primarily evaluate specification and code generation stage-wise, with code generation typically conditioned on an oracle specification. This setup overlooks whether strong stage-wise performance translates into end-to-end success. (II)They mainly focus on a single proof-oriented language and mathematically structured tasks, offering limited coverage of tasks common in software development. In this paper, we introduce VeriCodeBench, a benchmark for self-spec verifiable code generation, where the LLM relies solely on its own g

---

### [110] GraphMAS: A Systematic Benchmark of Multi-Agent Coordination for Graph Learning

**链接**: https://arxiv.org/abs/2609.39777
**作者**: Jiayi Yang, Yifang Chen, Yuanfu Sun, Xinyan Ge, Qiaoyu Tan
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based multi-agent systems coordinate specialized reasoning through aggregation, interaction, and adaptive control, yet their potential for graph learning remains unexplored. Graph learning is a natural setting for such systems because useful evidence may arise from heterogeneous local, long-range, global structural, and semantic perspectives whose relevance varies across instances. Existing LLM-based graph learning approaches primarily rely on single-agent reasoning, while multi-agent coordination has been studied mainly in general reasoning settings. Consequently, it remains unclear whether multiple specialized agents can improve graph learning and how coordination strategies should be designed and evaluated. To address this gap, we introduce GraphMAS, a systematic benchmark of multi-agent coordination for graph learning. GraphMAS builds a shared pool of graph reasoning specialists and organizes coordination along two dimensions, inter-agent interaction and runtime adaptivity, yie

---

### [111] Targeted Retrieval, Compact Representations: How CoT Reasoning Improves Long-Context Counting

**链接**: https://arxiv.org/abs/2609.38958
**作者**: Liang Twist Shan, Tianyu Hu, Hao Yan, Yiqiao Zhong
**来源**: cs.AI cs.CL cs.LG stat.AP
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) have been rapidly improving in long-context tasks, powered by Chain-of-Thought (CoT) reasoning. However, the internal mechanisms underlying this improvement remain unclear. We investigate these mechanisms through a needle-in-a-haystack (NIAH) counting task, where an LLM is asked to count the number of records dispersed in a long text. Across twelve model comparison groups, Thinking (or reasoning) improves counting accuracy over Non-thinking, with pronounced gains at larger counts. This motivates our mechanistic analysis, which identifies two contrasting mechanisms: (i) broad retrieval, where Non-thinking models broadly attend to multiple needles; (ii) targeted retrieval, where Thinking models use enumeration in CoT traces to successively retrieve needles. Targeted retrieval concentrates attention on individual needles and is accompanied by more compact internal representations. Moreover, causal intervention analysis suggests that Thinking models use the CoT

---

### [112] Coding Agents for Coding Theory

**链接**: https://arxiv.org/abs/2609.39081
**作者**: Abraham Yeung
**来源**: cs.IT cs.AI cs.LG math.IT
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We spent five weeks using an LLM coding agent on open problems in coding theory: finding large sets of four-letter words, such as DNA barcodes, that stay far apart in edit distance. The agent wrote the verifiers and search code; a human chose the problem and set the verification protocol. Restricting the search to codes with a prescribed symmetry, a classical technique, shrank the problem about fourfold and raised the best known code of length 6 and minimum edit distance 3 from 114 to 120 words ($E_4(6,3) \geq 120$). The same pipeline improved twelve further lower bounds at lengths 6 to 9 and distances 3 to 6. We give the failures equal space. Our own search stopped at 116 and recorded the last symmetry class as topping out at 112; a second agent session, running the same search with a better operator, found the 120. A later verdict that the method did not carry over to length 7 was wrong for the same reason, and an earlier instance cost three weeks. Each time, an intermediate result w

---

### [113] UniAE-MoE: A Unified Audio Encoder via Mixture of Experts

**链接**: https://arxiv.org/abs/2609.39199
**作者**: Shengbo Cai, Zhisheng Zhang, Zichao Nie, Jing Peng, Jingran Xie, Zhiyong Wu
**来源**: cs.SD cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Audio Language Models (LALMs) rely on effective audio encoders for multi-task performance. We introduce UniAE-MoE, a unified audio encoder designed to model cross-domain audio representations and achieve outstanding downstream understanding performance via a Mixture-of-Experts (MoE) architecture. Specifically, we explore mainstream audio encoders and integrate those from Qwen2-Audio and Audio-Flamingo 3, which demonstrate superior downstream capabilities. To facilitate effective model fusion, we improve our encoder using SwiGLU with shared experts to decouple encoder networks, and we further introduce a two-stage instruction-tuning strategy to better adapt the model to diverse downstream tasks. Moreover, we propose the task-specific data scaling (TSDS) technique to enhance \tool's understanding capabilities. On the XARES-LLM benchmark, UniAE-MoE attains a score of 0.802, achieving state-of-the-art performance. It also delivers top-tier performance in the official Interspeech 2026

---

### [114] Beyond Mode Collapse: Generating Diverse Synthetic Expert Conversations via Generative Flow Networks

**链接**: https://arxiv.org/abs/2609.38359
**作者**: Sumit Asthana, Michael Ion, Kevyn Collins Thompson
**来源**: cs.AI cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> High quality synthetic data is central to post training LLMs for adaptive AI applications that represent the diverse expert strategies and decisions in conversations. Prompting LLMs directly or conditioning them on end use scenarios yields low diversity data that collapses onto dominant modes. We propose a method to generate diverse high quality synthetic data using Generative Flow Networks (GFlowNets). We show that training GFlowNets to generate latent conversation structure using a Gaussian mixture density over key interaction features (e.g., confusion episode dynamics, scaffolding directive balance) enables sampling expert strategies in proportion to their prevalence in the training data. Across two structurally distinct domains, tutoring and emotional support dialogues, our GFlow based synthetic data generation approach offers a better balance of fidelity, mode coverage and authenticity than reinforcement-learning and end to end LLM baselines, without copying training data. Evaluat

---

### [115] Efficient Expert-Parallel Communication on PCIe-Connected Consumer GPUs

**链接**: https://arxiv.org/abs/2609.40093
**作者**: Jaehwan Lee, Sangmin Lee, Chaewon Kim, Junsik Shin, Jaejin Lee
**来源**: cs.DC cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Expert parallelism (EP) enables inference of large Mixture-of-Experts (MoE) models by placing their experts across multiple GPUs, but requires substantial communication between GPUs at every MoE layer. As contemporary MoE models activate more experts per token, this communication accounts for a growing fraction of inference time. The cost becomes particularly pronounced on PCIe-based consumer GPU systems, where all inter-GPU transfers traverse CPU memory. However, existing MoE-specialized EP communication libraries assume that direct GPU-to-GPU access is available, largely overlooking consumer GPUs. Therefore, most LLM frameworks instead rely on NCCL, whose CPU-staged communication incurs redundant PCIe transfers and competes with expert computation for GPU resources, limiting their overlap. We present ThunderEP, a novel communication design for such systems that removes the relay hops of traditional ring algorithm, moves data through DMA engines to avoid compute resource contention, a

---

### [116] MASCRDM: Multi-Agent System for Compliance Risk Detection and Mitigation in Training Process of Large Language Models

**链接**: https://arxiv.org/abs/2609.39107
**作者**: Yan Zhang, Chuming Wei, Ruien Li, Yaoyao Peng, Wusheng Zhang, Guangwen Yang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) have been applied in various fields. However, ensuring compliance and safety of LLMs, such as avoiding discrimination and bias, still remains a challenge. Current efforts mainly focus on detecting and filtering inputs and outputs of the trained models, rather than studying the intrinsic architecture of the models in real-time. To tackle this challenge, we analyze the LLMs training process and discover two critical issues: 1) Most of the existing methods are predominantly static in their approach to detection and filtering, achieving only localized optimizations without systematically enhancing the compliance of LLMs. 2) Another issue with existing approaches is the lack of real-time risk detection and mitigation across the full training process, which leads to limited flexibility. Motivated by these, we propose MASCRDM (Multi-Agent System for Compliance Risk Detection and Mitigation) during the LLM training process. Firstly, we develop a set of compliance r

---

### [117] PANDA: A Decentralized Architecture with Flexible Orchestration for Scalable, Fault-Tolerant Multi-Agent Systems

**链接**: https://arxiv.org/abs/2609.38482
**作者**: Matthew D. Laws, Cristina Nita-Rotaru
**来源**: cs.MA cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Existing architectures for LLM-based multi-agent systems (MAS) cannot reliably and efficiently solve multi-step tasks at scale: they struggle to support large numbers of agents and concurrent tasks, tolerate failures, govern agent interactions, and accommodate the diverse planning and execution patterns different tasks require. We present PANDA, a decentralized architecture that connects a large collective of heterogeneous, independently administered agents, letting them discover each other's capabilities and self-organize into small specialized teams per task. PANDA scales by decoupling collective communication from team communication, allowing agents to participate in multiple teams simultaneously, load-balancing tasks across the collective, and scheduling concurrent work within each agent. PANDA further separates the underlying architecture from the orchestration strategy, supporting three planning and execution patterns (star, chain, and mesh) that can be selected according to the 

---

### [118] MetaPersona: Task-Grounded Synthetic Populations from Empirical Social Science

**链接**: https://arxiv.org/abs/2609.38392
**作者**: Jinyi Ye, Yuangang Li, Chenxiao Yu, Preyashi Poddar, Priyanka Dey, Longtian Ye 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Personas used to seed LLM social simulations face a cold-start problem: existing methods lack a principled basis for deciding which attributes to include and how to assign their values. As a result, synthetic populations may misrepresent the demographic composition, latent attributes, and dependency structure that shape downstream behavior. We introduce MetaPersona-DB, a dataset of 11,000+ empirical human-subjects studies annotated with task-relevant variables, reported relationships, and aggregate-level population statistics. Building on this resource, we propose MetaPersona, a framework that retrieves task-relevant evidence, constructs literature-derived persona dependency graphs, and samples synthetic populations from empirical priors linking demographics, latent attributes, and outcomes. Across three downstream case studies, three baselines, and three frontier models, results vary by task and model: MetaPersona performs strongly on misinformation belief and AI-tool sentiment, while

---

### [119] Agent Error Dataset: Scaling 50,000 Error--Diagnosis Pairs for Failure Analysis and Error-Aware Post-Training

**链接**: https://arxiv.org/abs/2609.40111
**作者**: Kunlun Zhu, Xuyan Ye, Yibo Li, Cheng Qian, Beibin Li, Heng Ji
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> An unsuccessful LLM agent rollout contains more information than its final reward: the observations available to the agent, the actions it chose, and the environment's responses. Reusing this experience for learning requires identifying a decision to revise and testing a concrete alternative. We introduce the Agent Error Dataset (AED), comprising 50,228 error-diagnosis pairs from 9,961 source tasks across 33 environments, 19 harness families, and 23 policy models in text-based agent systems. We retain source traces and execution metadata to support cross-setting failure analysis and re-diagnosis without repeating the original rollout. Our five-stage Agentic Error-to-Training (AET) pipeline collects natural failures, generates diagnoses and proposed corrections, and checks them against recorded evidence. Where replay is supported, we compare corrections with original-action retries from the same checkpoint under matched execution settings. We then construct separate training views for d

---

### [120] Component-Aware Feedback for Self-Evolving Programs

**链接**: https://arxiv.org/abs/2609.38639
**作者**: Ethan Lin, Jinming Nian, Yi Fang
**来源**: cs.AI cs.IR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-guided evolutionary search can discover complex programs, but existing methods mostly only save candidate programs and fitness scores while discarding which component edits produced which fitness metric changes. Existing methods force the mutator LLM to infer the effect of prior edits from cluttered histories, making program search slow and unstable. This is especially true for locally servable LLMs to evolve multi-component systems. We introduce component-aware feedback, which compares each evaluated program with its parent, identifies the components that changed, and logs them with the associated metric differences into an attribution memory that later mutations read. The memory keeps each change in two reference frames, local against the parent it came from and global against the seed program, which shows both the immediate effect of a change and the cumulative progress made since the seed. We study this on LLM reranking, a multi-objective optimization problem where a multi-stag

---

### [121] Better Deck or Different Judge? Evaluating Agentic Harness Gains in Corporate and Investment Banking

**链接**: https://arxiv.org/abs/2609.39958
**作者**: Ludovic Gibert, Matis Despujols, Andre-Louis Rochet
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Corporate and investment banking teams use presentations to support credit decisions and advise clients on financing and transactions. Producing these decks requires reconciling financial data, tracing sources and turning analysis into a recommendation. We retrospectively study the development of an agentic harness combining a 27B language model, financial calculations, narrative templates and validation checks. LLM judges guide engineering changes and assess the resulting decks, raising the question of whether higher scores reflect better documents or changes in grading. In shared-session text-only grading with template markers removed, five judges score the complete system 20.4 to 33.6 points out of 95 above the same model generating directly from a short prompt. Every judge scores the system higher on all seventeen development deliverables. Margins against direct Opus generation from a short prompt range from -4.7 to +0.8 points. Judges agree on broad progress across development rou

---

### [122] On the (In)effectiveness of AMR Augmentation for Large Language Models

**链接**: https://arxiv.org/abs/2609.40121
**作者**: Hoa Quynh Nhung Nguyen, Jacopo Staiano, Michael Sullivan
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> While Abstract Meaning Representation (AMR) has historically improved performance on a range of NLP tasks, the benefit---or lack thereof---of AMR augmentation for modern LLMs is thus far unclear. In this paper, we attempt to reproduce recent work that reported substantial downstream gains from AMR augmentation, finding that these are likely due to specific choices in the experimental settings used: using a consistent and unified protocol for hyperparameter selection, we observe that text-only baselines consistently match or exceed the performance of AMR-augmented models. To investigate this null result, we introduce a perplexity-based probe measuring the degree to which AMR provides an LLM with supplemental relational knowledge not already available to the model. We find that AMR augmentation does not help LLMs improve their understanding of relational content in the sentence, indicating that augmenting these models with AMR offers no clear benefit on downstream tasks.

---

### [123] CollabFlow: Recursive Self-Improvement of Agent Collaboration

**链接**: https://arxiv.org/abs/2609.38662
**作者**: Xiao Huang, Mingda Zhang, Junming Zhang, Qiang Huang, Hanwen Zhang, Yue Dai 等 (8 人)
**来源**: cs.MA cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recursive self-improvement (RSI) lets a system improve from its own outcomes; in LLM-based multi-agent systems, Agents refine one another within a task, and outcomes improve how they collaborate across tasks. However, existing multi-agent collaboration leaves this loop open: collaboration is pre-defined at the operator level, topology-only learning keeps verbatim exchange that propagates errors, and reward maximization on a system's own outcomes concentrates on a few teams. To address these challenges, we propose CollabFlow, an RSI system of Learned Agent Collaboration: a trainable Collab-Director constructs teams of complete Agents, a frozen executor runs them, and each round's outcomes retrain the director. Within each round, the edges of a collaboration graph carry protocols of Evidence-Conditioned Communication: a receiver adopts a differing answer only when the sender's evidence is stronger by a margin, so the director learns who communicates and how. Across rounds, we further pro

---

### [124] When Context Changes: Understanding Update Failures in LLMs

**链接**: https://arxiv.org/abs/2609.38866
**作者**: Junyu Guo, Yuchen Fang, Shangding Gu, Costas Spanos, James Demmel, Javad Lavaei
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As preferences, goals, and facts change, LLM agents must use the current state while earlier versions remain in context. Yet they can answer with an old value of the same variable, a failure that we call stale binding. To study when models use outdated information and why, we introduce Controlled In-Context Memory (CICM), a benchmark for tracking and using updated information in conversations and agent logs. We observe that even frontier reasoning models can fail to recover the current state. We find that in open-source models probes can still recover the updated value when the model answers with an old one, pointing to a failure to select information that remains available. Component tests in Qwen and Pythia identify a mechanism for this selection failure: attention drift, where attention favors old values over the current one when producing an answer. We study a one-layer transformer to mathematically understand how this phenomenon happens: when attention scores are similar, several 

---

### [125] SparseEngine: Sparse-First Inference Engine

**链接**: https://arxiv.org/abs/2609.39068
**作者**: Jitai Hao, Quansheng Gu, Qiang Huang, Jun Yu
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-context LLM agents accumulate interaction histories that strain KV-cache memory and attention computation. Although sparse attention reduces these costs, heterogeneous cache representations and workflows hinder integration with existing inference engines, while prior sparse-serving abstractions support only specific layouts or workflows. We present SparseEngine, a ground-up, sparse-first inference engine whose shared lifecycle contract lets each method control its KV representation and computation while coordinating state transitions with common serving infrastructure. SparseEngine supports 15 methods across four categories and enables cross-request state management through Chain Cache, which resumes KV-eviction methods from retained history, and controllable Prefix-Cache Pruning, which removes KV from selected history regions while preserving logical-prefix matching. While maintaining method quality, SparseEngine delivers over 10x higher throughput with KV eviction, over 2.5x fas

---

### [126] TALK-Dem: Benchmarking Embodied Task Planning under Dementia-Associated Communication Patterns

**链接**: https://arxiv.org/abs/2609.38371
**作者**: Guangxin Zhao, Yiran Hu, Yuan Cao, Chenxi Jiang, Jianfei Yang, Yegang Du 等 (10 人)
**来源**: cs.RO cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Existing LLM-driven robot task planners rely on a taken-for-granted assumption of an ideal user whose instructions are clear, complete, and task-focused. However, when interacting with real-world users, especially those experiencing cognitive impairments, such as people living with dementia (PLWD), the planners often make mistakes and even pose physical safety risks. We proposed TALK-Dem (Talking Attributes and Linguistic Knowledge in Dementia), the first benchmark for evaluating LLM-driven robot task planning under dementia-associated verbal communication. TALK-Dem contains 4,800 instructions and covers five typical communication patterns, including Referential Imprecision, Object Substitution, Empty Speech, Topic Drift, and Intrusion, at three intensity levels. Experiments across six open-weight LLMs reveal a substantial robustness gap. Across communication patterns, open-weight models exhibited performance drops of up to 22.3 percentage points compared to ideal instructions. This re

---

### [127] Trustworthy Runtime Error Healing in Real-World Repositories: A Benchmark and Guardrail

**链接**: https://arxiv.org/abs/2609.39086
**作者**: Gou Tan, Pengfei Chen, Zhensu Sun, Jieke Shi, Junkai Chen, Ting Zhang 等 (10 人)
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Runtime error healing lets a crashed program continue by generating code that repairs its live runtime state. Recent work shows that LLMs can generate such healing code, but it is evaluated only on small competition programs, and executing LLM-generated code inside a live process raises safety concerns that remain unaddressed. In this paper, we take LLM-based runtime healing toward practical use in real-world repositories. We first build HealBench, a benchmark of 265 runtime errors from 18 real-world repositories, each paired with a reference execution on the patched version. HealBench also provides a unified framework that lets LLM agents heal with cross-file context and live runtime state. We then design HealGuard, which requires healing code to be written in HealCore, an analyzable subset of Python, and uses static and dynamic taint analysis to check whether state changed by healing reaches operations protected by developers. We evaluate a dedicated healing method and three general 

---

### [128] ReSAIL: Mitigating Collapse in Iterative Agent Self-Distillation

**链接**: https://arxiv.org/abs/2609.39306
**作者**: Shengjie Jin, Hengbo Xu, Zelong Sun, YuJie Guo, Zhiwu Lu
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Iterative self-distillation enables LLM agents to learn from successive deployments, offering a path toward recursive self-improvement (RSI). Yet our experiments with existing methods reveal a collapse in deployment performance across cycles, while task performance with privileged information (PI) also declines. We address this collapse by prioritizing informative interaction steps for distillation and preserving PI-conditioned behavior as the student becomes the next teacher. We introduce Retentive and Selective Augmentation for Iterative Self-Distillation (ReSAIL), a plug-in augmentation for iterative PI-based self-distillation. ReSAIL selects interaction steps where PI most strongly changes the teacher's predictions and balances the resulting distillation losses across trajectories. It also regularizes the student's PI-conditioned output distributions toward those of the frozen teacher at selected and unselected steps to preserve PI-conditioned behavior for supervision in the next c

---

### [129] Inference Auctions

**链接**: https://arxiv.org/abs/2609.40070
**作者**: Keegan Harris, Siddharth Prasad, Asher Trockman, Nika Haghtalab, Michael I. Jordan
**来源**: cs.LG cs.AI cs.GT
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> When inference demand exceeds available compute capacity, model providers must decide which requests should be served first. Users have different tolerances for delay from an LLM API, but current priority pricing schemes compress these differences into coarse fixed-price service tiers. We design an inference auction that allows users to bid for faster service. Our auction allocates priority in an economically efficient way without sacrificing latency, and we develop fast algorithms for implementing prices that incentivize truthful bidding. We also design an autobidding agent for our inference auction, where users specify an inference budget and the autobidder dynamically adjusts its bids over time to maximize user utility subject to the budget constraint. Experiments validate the practicality of our auction: it increases system welfare while maintaining the cache utilization and latency advantages of SGLang, a state-of-the-art inference serving framework.

---

### [130] AI Agents are Vulnerable to Radicalization

**链接**: https://arxiv.org/abs/2609.38296
**作者**: Ozgur Can Seckin, Shalmoli Ghosh, Alessandro Flammini, Kristina Lerman, Maria Elizabeth Grabe, Filippo Menczer
**来源**: cs.AI cs.CY
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) can influence people's beliefs, yet little is known about whether and how they can manipulate each other. To investigate this, we simulate conversations between two agents: a target LLM that role-plays a human persona based on demographic and psychological attributes, and an influencer LLM that aims to make the target's beliefs more extreme. We examine radicalization along two pathways: resonance, where the influencer reinforces a target's pre-existing belief, and persuasion, where the influencer promotes a belief the target initially considers unimportant. Across affective and behavioral metrics, we find that both mechanisms radicalize the target. However, resonance produces consistently stronger effects than persuasion. Different influence tactics, such as using sycophancy and unverified claims, produce different levels of radicalization, but not consistently across metrics. We further show that resonance propagates to related beliefs, suggesting intercon

---

### [131] From Image Interpretation to Clinical Reasoning: Upstream Physician-Context-Aware Multimodal Learning with Causal Reinforcement Learning

**链接**: https://arxiv.org/abs/2609.38924
**作者**: Jialu Pi, Yanan Ma, Weijie Chen, Owen Crystal, Shubham Trivedi, Stephen Xie 等 (10 人)
**来源**: cs.CV
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Major adverse cardiovascular events (MACE) remain the leading cause of mortality worldwide. Opportunistic screening using routinely acquired clinical data offers a scalable approach for identifying high-risk individuals before acute events occur. Although chest X-rays (CXRs) capture latent cardiovascular biomarkers and clinical histories provide complementary patient context, existing medical vision-language models are primarily optimized for radiology interpretation rather than prognostic reasoning. We propose a causal reinforcement learning framework for multimodal clinical reasoning that integrates CXRs and physician-authored clinical histories for opportunistic MACE prediction. The framework introduces (1) a role-decoupled dual-LLM architecture that separates reasoning from risk prediction, (2) a dual-action causal reinforcement learning policy for evidence selection and reasoning optimization, and (3) causal token pruning to learn compact multimodal representations. Evaluated on a

---

### [132] Making LLMs Say What They Think: Measuring and Improving CoT-Interpretability Alignment

**链接**: https://arxiv.org/abs/2609.38972
**作者**: Yihuai Hong, Shauli Ravfogel, Chen Zhao, Eunsol Choi
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Chain-of-thought (CoT) traces often serve as a proxy for how Large Language Models (LLMs) arrive at their answers. However, growing evidence shows that models' CoT often fails to reflect their internal computations and can be changed without affecting their final answers. In this work, we measure and improve the alignment between the reasoning described in an LLM's CoT and what it computes internally. We propose CoT-Interpretability Alignment (CIA), a metric that measures the agreement between a model's CoT traces and its internal reasoning strategies as detected by interpretability tools. We evaluate CIA on three tasks (two-hop question answering, hint intervention, and integer multiplication) across three LLMs, finding that LLMs exhibit limited alignment across all tasks (44.8-75.9%). We then experiment with improving CIA via post-training, setting both the task accuracy and parametric faithfulness signals as a reward. Experiments show that we can substantially improve CoT parametric

---

### [133] CARAT: Do Materials LLMs Reason or Recite?

**链接**: https://arxiv.org/abs/2609.38340
**作者**: Jiajun Wu, Jian Yang, Zixiang Ni, Zhenzhu Li, Bin Chong
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> When a materials LLM answers a question about crystal structure, does it reason from the structure or copy an answer already printed in its input? Accuracy cannot tell: a structural description often prints the very field it is scored against. CARAT holds question and gold answer fixed across eight matched views, names each structural relation separately in GraphSpace, and adds matched fine-tuning, answer masking, evidence injection, paired inference, and a rule that can withhold claims. First, on the benchmark's hardest families the grounded view is worth 17.3 points over formula inputs. Second, we turn that scrutiny on ourselves. GraphSpace beats a plain periodic graph by 19.3 points, but that margin is two effects at once: where the plain rendering carries everything the question needs it is 1.96 points, and where it omits those fields entirely, 46.7 points. The headline mostly measures what the baseline lacked, not how evidence is presented. Third, we attack our own benchmark. A ru

---

### [134] Who Owns That? Evaluating Ownership Intuitions in Large Language Models

**链接**: https://arxiv.org/abs/2609.39483
**作者**: Xizhi Xiao, Yue Wu, Shan Xu, Jia Liu
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Ownership establishes rights over the use, control, and transfer of objects. Understanding these relations is essential for AI systems to interact appropriately with people and their resources. Yet how large language models (LLMs) attribute ownership under competing claims remains unclear. We introduce the Competing Ownership Attribution Task (COAT), comprising 42 scenarios, and compare ownership allocations from 24 LLM configurations with those of 108 human participants. Overall, human-model similarity is close to human-human similarity, but models show greater homogeneity in their ownership judgments. Within individual answers, models also divide ownership more evenly among claimants than humans do. Pooling responses across model configurations reveals more scenarios with a shared judgment and fewer with distinct viewpoint groups than in humans. When humans form distinct groups, models may converge on one viewpoint or between competing viewpoints. Further comparisons reveal different

---

### [135] Argus: Academic Integrity in the Era of Generative AI

**链接**: https://arxiv.org/abs/2609.36073
**作者**: David Racovan, Ajay Rawat, Christopher K. May, Jeffrey A. Turkstra
**来源**: cs.CY cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The rapid proliferation of large language models (LLMs) in the context of education has introduced significant challenges in enforcement of academic integrity, especially in programming courses. We present Argus, an automated detection system for LLM-assisted student work in undergraduate C programming assignments. Argus integrates behavioral and stylistic indicators to create a holistic picture of the student's progress through an assignment and surfaces anomalies that point to potential misuse of LLM assistance. We quantify and analyze data over six years of Spring semester offerings in a large-enrollment CS2 course at Purdue University using Argus, finding that 45% of enrolled students exhibited patterns consistent with LLM-assisted code development in Spring 2026. To contextualize these results, we analyze the relationship between flagged LLM use and student performance on written, in-person proctored examinations, and find a significant negative correlation. We also explore the pr

---

### [136] How People Use ChatGPT: Conversation-Level Evidence from India, Nigeria, Brazil, and Pakistan

**链接**: https://arxiv.org/abs/2609.38279
**作者**: Shreyasi Roy Chowdhury, Kiran Garimella
**来源**: cs.CY cs.HC cs.SI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Public understanding of how people use LLM-based conversational AI assistants comes primarily from aggregate platform reports by OpenAI and Anthropic, which apply fixed taxonomies and inferred demographics to hundreds of millions of users and release only summary statistics that outside researchers cannot re-analyze. We provide a complementary, conversation-level view: complete ChatGPT exports comprising 202,590 conversations from 1,252 users across India, Nigeria, Brazil, and Pakistan, paired with self-reported age and gender and spanning December 2022 to February 2026. To our knowledge this is the first conversation-level, demographically grounded comparison of ChatGPT use across multiple non-Western countries. We ask what these users use ChatGPT for (purpose), what they talk about (topics), and how they engage with it (mode of interaction), using the platform's own classifiers, unsupervised topic discovery, and a thematic analysis of expressive conversations. Personal use accounts f

---

### [137] Beyond Oracle Communication: Benchmarking Interactive Intent Alignment Under Miscommunication and Evolving User Intent

**链接**: https://arxiv.org/abs/2609.38604
**作者**: Zheyuan Zhang, Mengyuan Chao, Ke Xiao, Ziyi Chen, Daoan Zhang, Yan Zhang 等 (8 人)
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Modern LLM agents increasingly tackle complex tasks through interactive, long-horizon exchanges with users, while existing benchmarks generally assume that users always accurately and sufficiently communicate a fixed intent. However, this oracle communication assumption rarely holds in practice: users may miscommunicate, change their goals, and run out of patience. We define this task setting as Interactive Intent Alignment, where agents must recover and continuously track the user's current intent despite imperfect communication and evolving goals. To study this setting, we introduce Drift-Bench++, a principled benchmark construction pipeline for verified executable tasks with controlled misalignment and intent shifts, along with an interaction protocol featuring finite patience, diverse simulated users, and silent interaction-conditioned shifts. We further develop GRIP, a comprehensive evaluation protocol covering task grounding, user realism, inquiry effectiveness, and adaptation to

---

### [138] VAmoS Part Deux: Harder, More Realistic Voice-Agent Simulation

**链接**: https://arxiv.org/abs/2609.38512
**作者**: Joshua Meyer, Sahar Shayegan, Ritiz Tambi, Ali Khan, Sun Kim, Victor Shih 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Voice agents in production must handle several requests, background speech, and customers who lose patience. We introduce VAmoS Energy, a benchmark that combines these challenges in 100 calls about utility billing and payment assistance. Each caller makes two to four requests. The agent has sixteen tools backed by a stateful Stripe billing twin and the Apache Fineract loan engine, with account access blocked until caller verification succeeds. The tasks use public household electricity data and a policy based on Pennsylvania's residential billing rules. An LLM-as-a-verifier checks the agent's actions and spoken figures against explicit requirements. On a calibration run, it agrees with a code verifier on 99.1% of checks. Across fourteen voice stacks and three repeats per task, completion ranges from 17.3% to 44.7%. Grok Voice leads, and Gemini 3.8 Live and GPT-Live follow at about the same cost per call. Background television reduces pooled completion from 38.7% to 8.6%. The simulated 

---

### [139] Code to Control: Synthesizing Parameterized Reactive Controllers

**链接**: https://arxiv.org/abs/2609.38733
**作者**: Zergham Ahmed, Joshua B. Tenenbaum, Chris Bates, Samuel J. Gershman
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent LLM-based approaches to control either invoke a language model to select actions or synthesize world models that require planning at every decision, introducing latency that can limit real-time use. We introduce Code to Control, an approach that synthesizes Python controllers which execute directly as policies. Code to Control separates program structure from parameters. An LLM synthesizes the controller structure, while derivative-free search fits its parameters for continuous control using feedback from the environment. Once learned, the resulting controllers require neither LLM inference nor planning at decision time, enabling real-time gameplay and, under our timing protocol, faster action selection than a PPO policy. Across a suite of Atari games, Flappy Bird, and MuJoCo tasks, Code to Control outperforms planning-based program synthesis methods, remains competitive with deep reinforcement learning while using fewer environment interactions, transfers across substantial cha

---

### [140] EVOKE: Eliciting World Knowledge in Agents for Transferable Decision-Making

**链接**: https://arxiv.org/abs/2609.38334
**作者**: Yuhan Guo, Jinming Liu, Liang Xu, Ziqiang Li, Jianguo Huang, Zhicheng Wang 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly deployed as agents for multi-step decision-making, yet transfer poorly to unseen environments. World-model methods address this by training agents to predict future observations, at the cost of additional training and errors that compound when predictions are used for planning. However, for LLM agents operating in digital environments, much of this world knowledge is already internalized during pretraining, which shifts the problem from acquiring it to eliciting it. We argue that typical post-training provides little pressure for such elicitation, since supervision under a single goal at each visited state inadvertently drives policies to rely on superficial contextual habits. We introduce EVOKE, a post-training method that supplies this pressure through goal diversity at fixed states. Motivated by theory showing that an agent competent across diverse goals must encode a world model recoverable from its action preferences, EVOKE holds the e

---

### [141] Multi-agent discussion gains less when dissent is withheld

**链接**: https://arxiv.org/abs/2609.38324
**作者**: Chand Sahil Mansuri, Xin Wang, Mengying Li, Bryan Acton, Rory Eckardt, Dhaval Patel 等 (7 人)
**来源**: physics.soc-ph cs.CL cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-agent systems of LLMs add discussion to majority voting and are therefore expected to be more capable. However, empirical reports conflict on whether discussion improves accuracy or leads to an incorrect consensus. Here, we introduce a parsimonious model that explains when discussion improves accuracy and when it ends in an incorrect consensus, built from four behaviors repeatedly observed in LLM agents: (1) withholding dissent, (2) internalizing a stated answer, (3) reconsidering after seeing dissent, and (4) correcting toward the correct answer. The model shows that discussion can overturn an incorrect initial majority only when the withholding rate $c$ is below a critical rate $c^* = \gamma/(\gamma + a)$, set by the net correction rate $\gamma$ and the internalization rate $a$. We estimate these rates from conversation logs with a Bayesian method and place LLM teams relative to $c^*$. As the model predicts, the gain from discussion shrinks as withholding rises, across LLMs and

---

### [142] Framing the Narrative: Ideological Mimicry in Large Language Models

**链接**: https://arxiv.org/abs/2609.38256
**作者**: Olivia Macmillan-Scott, Michael Jacobs, Nils Metternich, Mirco Musolesi
**来源**: cs.CL cs.CY
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly used to answer questions about politically contentious issues, yet evaluations typically treat a model's stance as a relatively stable property. Real users, however, communicate political signals through their terminology, assumptions, and personal context. We investigate whether such signals produce ideological mimicry: systematic shifts in the political stance expressed by an LLM toward the position conveyed by the interaction. If LLMs adapt their responses to these signals, they risk creating personalised political information environments in which users with opposing views receive systematically different accounts of the same issue, potentially reinforcing existing divisions. We build the Poli-SHIFT dataset and evaluation framework and assess seven open-weight LLMs across ten contentious political topics in the United States, United Kingdom, and Australia, systematically manipulating contested terminology, politically valenced premises,

---

### [143] Drift Inspector: Exploring and Measuring Scientific Drift with Atomic Contribution Claims

**链接**: https://arxiv.org/abs/2609.39710
**作者**: Vsevolod Karimov, Stepan Ostarkov, Anastasia Poroshina, Anatoly Frolov, Alexander Panchenko
**来源**: cs.CL cs.DL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Scientific abstracts mix contributions with background, motivation, and meta-language, so tools that read them as-is cannot separate what a field produces from what it discusses. We present Drift Inspector, an open-source system for measuring and exploring how a research field changes over time at the level of Atomic Contribution Claims (ACCs): decontextualized, contribution-bearing propositions an LLM extracts from each abstract before analysis. The system clusters these claims across years into an interactive map where every trend traces back to the claims and papers behind it. Applied to six years of EMNLP, it shows the field shifting away from classic NLP tasks toward LLM-era capabilities such as reasoning and multimodality -- a movement that keyword or whole-abstract counts blur. The released data extend beyond EMNLP: the same pipeline has processed the full ACL Anthology (346k claims, 80k abstracts, 423 venues). Extraction is human-validated and clustering checked against an exte

---

### [144] ActionGuard: Tool Call Authorization under Poisoned Skills

**链接**: https://arxiv.org/abs/2609.39450
**作者**: Jihun Han, Yejin Jang, Byung Il Kwak, Mee Lan Han
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based agents extend their capabilities through third-party skills that provide task-specific instructions, scripts, and tool-use procedures. However, malicious instructions inserted into an otherwise benign skill can cause a benign user request to trigger dangerous Tool Calls, including data exfiltration, file deletion, or unauthorized code execution. This paper presents ActionGuard, which inspects skill-influenced Tool Calls immediately before execution. ActionGuard separates the target agent's action-generation context from the safeguard's authorization context. The target agent may use the original skill for planning, but the Reviewer does not receive the potentially poisoned raw skill text. Instead, it determines whether each action is justified by the trusted user request using a balanced skill profile, current and recent Tool Calls, and local script contents. ActionGuard intercepts each Tool Call at OpenClaw's before-tool-call stage and enforces the Reviewer's ALLOW or DENY d

---

### [145] What Limits Recursive Reasoning Models: Optimization, Architecture and Test-Time Scaling

**链接**: https://arxiv.org/abs/2609.39967
**作者**: Yuliana Shakhvalieva, Dmitrii Kharchev, Viacheslav Bezrukov, Inessa Fedorova, Dmitry Bocharov, Ivan Oseledets 等 (7 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recursive reasoning models apply a small shared Transformer block many times to refine a latent state. This gives them large effective depth with few parameters and makes them strong on algorithmic tasks. Such compact solvers are natural candidates for tools that an LLM can call on narrow algorithmic subproblems. However, existing models such as HRM, TRM and URM differ in architecture, gradient propagation and training procedure simultaneously. This makes it hard to tell what drives their performance, and their optimization is still poorly understood and often unstable. In this work we address both of these gaps. First, we study these questions under a unified experimental pipeline spanning six algorithmic domains. Individual controlled ablations are performed on representative domains, while the resulting recipe is evaluated across the full suite. The study reveals a surprisingly simple recipe for stable and generalizable recursive reasoning: an intermediate gradient horizon, large ph

---

### [146] Pretext: Defeating Malicious Skill Detection Frameworks for AI Agents

**链接**: https://arxiv.org/abs/2609.39607
**作者**: Tobias Kaisar, Aritra Dhar
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Skills extend an agent's capabilities by injecting instructions and information into the context, and are widely used by agents such as OpenClaw and Claude Code. Prior work shows third-party marketplaces host malicious skills that give attackers direct influence over the victim's agent. The emerging defense scans skills before installation, pairing deterministic static checks with an LLM-based semantic judge, as in NVIDIA's SkillSpector. We show that such defenses fall to an attacker who knows the detector. Our white-box LLM attacker, Pretext, iteratively crafts skills that evade detection while still delivering the payload and performing the benign task: moving the payload from code into natural language leaves static analysis inert, while framing it as the skill's legitimate purpose and splitting instructions across files keeps the LLM stage below its blocking threshold. Across three open-source models, Pretext achieves up to 97\% and 77\% against a frozen detector and a co-adaptive 

---

### [147] Persona and Persuasive Framing in AI Voice Agents: A $2\times2$ Field Experiment with Children

**链接**: https://arxiv.org/abs/2609.38782
**作者**: Thilo Tamme (1), David Steck (1), Anton Hantel (2) ((1) Technical University of Munich, (2) Massachusetts Institute of Technology)
**来源**: cs.AI cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Conversational agents increasingly interact with children, yet evidence on how their design shapes children's susceptibility to persuasion comes almost entirely from the lab. We report a $2\times2$ randomized field experiment embedded in a public German Santa Claus telephone hotline. Children's calls were randomly routed to one of four LLM voice agents varying persona (Santa, high authority, vs. Helper, low authority) and framing (persuasive nudges toward prosocial wishes vs. neutral). Of 1,072 logged calls, 89 conversations (median age 6) met inclusion criteria. Persuasive framing raised the probability of a prosocial wish from 11.6% to 45.7%, robust to controls. Persona authority showed a near-zero effect: Santa did not outperform the Helper. Persona instead shaped engagement; children hung up on the Helper far more often within the first minute (65% vs. 39%). Where context already lends an agent legitimacy, how it speaks shapes children's compliance more than who it claims to be.

---

### [148] Schema: Discovering Unknown Environments via Agentic Program Induction

**链接**: https://arxiv.org/abs/2609.39140
**作者**: Guanning Zeng, Jiani Wang, Wenjie Ma, Shaofeng Yin, Chenyang Wang, Shichen Liu 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Learning to complete tasks in unfamiliar environments with unknown rules remains a key challenge for LLM agents. Current LLM agents often record their discoveries in prose, which may not provide a compact, explicit account of how the environment works. Inspired by how scientists organize observations into testable, predictive theories, we introduce Schema, an agent harness that organizes learning and action through interactive program induction. The LLM agent decides what to investigate and how to act, expressing its evolving understanding of the environment as executable programs. The harness consists of a persistent program workspace and a small set of interfaces for checking these programs against the interaction history, planning within them, and executing plans under step-by-step verification. Schema raises ARC-AGI-3 RHAE from 58.7% to 99.2% with the same base model, solves 100% of the public DiG-bench games, and reaches the median performance of the top-50 human players on MazeBe

---

### [149] Where Do Multi-Agent Systems Fail? Evidence-Grounded Diagnosis of Collective Mechanisms

**链接**: https://arxiv.org/abs/2609.38761
**作者**: Zhengye Han
**来源**: cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> When a multi-agent system answers correctly, it is tempting to conclude that its agents shared, checked, and used information as intended. Yet a system can break one of its collective mechanisms, the rules that govern how agents route, admit, store, and act on shared information, and still return the right answer, while a wrong answer rarely reveals which mechanism failed. We ask what evidence from an execution is sufficient to conclude that a particular mechanism was violated. Our answer is a diagnostic contract, which separates what counts as a violation from which execution records can establish one, and concludes that a violation is supported, ruled out, or unknown; removing records can make this conclusion unknown but never reverse it. We test contracts for four mechanisms by replaying executions from the step where a mechanism acts, once unchanged, once with the mechanism broken, and once with it restored. Broken mechanisms often left the answer correct. An LLM diagnoser detected

---

### [150] A Reusable Semantic Web Framework for Evidence-Grounded Fundamental Rights Impact Assessments under the EU AI Act

**链接**: https://arxiv.org/abs/2609.39537
**作者**: Faith Olopade, Delaram Golpayegani, David Lewis
**来源**: cs.CY cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The EU AI Act (Art. 27) requires deployers of high-risk AI systems to conduct Fundamental Rights Impact Assessments (FRIAs) before deployment, yet the evidence needed for credible assessments is fragmented across incompatible incident repositories, risk vocabularies, and legal texts. We present a reusable Semantic Web-based framework that consolidates this evidence for two high-risk public sector categories: employment and worker management (Annex III(4)) and access to essential public services (Annex III(5)(a)). A curated 150-record corpus is annotated along four axes using keyword, LLM, and hybrid methods and serialised as a SPARQL-queryable knowledge graph of 1,351 RDF triples. Five FRIA demonstration scenarios surface 103 records (68.7% coverage). Evaluation against a 69-record gold standard reveals that LLM-assisted classification of the employment domain achieves only $\kappa = 0.045$, a cautionary result for automated fairness-related evidence retrieval in this domain. All artef

---

### [151] From Solo to Social Learning: Characterizing Recursive Social Improvement in LLMs

**链接**: https://arxiv.org/abs/2609.38516
**作者**: Kunal Jha, Max Kleiman-Weiner, Natasha Jaques
**来源**: cs.MA cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) can now improve themselves by revising the instructions they follow, and LLM agents are increasingly orchestrated to work together on complex problems. However, self-improvement methods typically optimize one system at a time, and multi-agent frameworks often have every model work toward a shared goal. We ask a different question. When each agent pursues its own reward, can self-improving LLMs learn from one another well enough to improve the whole population? We call this capability recursive social improvement. We study populations that revise skill files and choose whether, when, and whom to copy from. Independent search, learning from peers, and acting all share one token budget. In controlled environments, established social-learning algorithms benefit from peers, but three LLMs do not. They earn less reward per token than solo learners, and explore too narrowly or run out of tokens before acting. We then let the models write and revise their own skill

---

### [152] Large Language Models are Approximate Survival Estimators

**链接**: https://arxiv.org/abs/2609.38181
**作者**: Juan M Zambrano Chaves, Peniel Argaw, Risa Ueno, Carlo Bifulco, Kristina Young, Rom Leidner 等 (8 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Survival analysis estimates time-to-event outcomes from patient covariates and is widely used for medical risk assessment. Patients seeking prognostic information after a diagnosis may turn to large language models (LLMs), now readily accessible through consumer applications. However, whether LLMs can provide accurate survival predictions has not been rigorously evaluated. We introduce Survprompt, a framework that converts structured patient covariates into free-text clinical vignettes and prompts pre-trained LLMs to predict survival zero-shot. We benchmark Survprompt against conventional survival models, including random survival forests (RSF), across two multi-institutional pan-cancer cohorts: the publicly available MSK-CHORD cohort and a newly curated cohort from the Providence St. Joseph Health Network constructed using an LLM-based medical abstraction framework. We report censored mean absolute error (cMAE) and concordance index (c-index) and conduct feature ablations to identify 

---

### [153] E2E-SWE: Benchmarking LLMs on Building Working Codebases from Scratch

**链接**: https://arxiv.org/abs/2609.38335
**作者**: Hantian Ding, Chloe Bi, Jiacheng Zhu, John Yang, Matt Deitke, Pengcheng Yin 等 (8 人)
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Coding agents powered by large language models (LLMs) are evolving from making localized code changes to developing complete software repositories. However, evaluating repository-scale generation remains challenging: tasks must demand system-level reasoning while ensuring that all evaluated behaviors are precisely specified and independent of any particular implementation. We introduce E2E-SWE, a benchmark for evaluating whether coding agents can build complete, functional software repositories end to end. E2E-SWE contains 186 whole-repository generation tasks spanning 11 programming languages. Given only a natural-language specification and an empty workspace, an agent must implement a complete, installable project that satisfies a comprehensive suite of hidden tests. Each task is constructed by a software engineer in collaboration with an LLM; together, they develop the test suite and a corresponding implementation-independent specification. To ensure that tasks are well specified an

---

### [154] ConflictGuide: AutoResearch Improves When Competing Behaviors Are Made Visible

**链接**: https://arxiv.org/abs/2609.39933
**作者**: Binqian Xu, Qiran Zou, Xiangbo Shu, Dianbo Liu
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> When designing machine learning models, desirable properties are often in tension: improving one behavior can impair another, so task progress can depend on alleviating the conflict. LLM-based AutoResearch systems, which iteratively edit model code and retain edits based on scalar task-performance feedback, have largely ignored this trade-off. We find that scalar feedback supports broad exploration early in search, but it does not reveal how edits affect competing behaviors. In matched-budget experiments, introducing competing-behavior feedback as task gains diminish increases the share of proposals that improve both behaviors and sustains progress beyond scalar-only plateaus. Obtaining this feedback for a given model requires identifying its competing behaviors and designing probes to measure them. To make competing-behavior feedback actionable, we introduce ConflictGuide. Its reusable ConflictGuide-Skill combines a literature-grounded taxonomy with model-specific evidence to identify

---

### [155] RAIM: Robust Aggregation of Inexpensive Models for Hallucination Detection

**链接**: https://arxiv.org/abs/2609.39229
**作者**: Elia Onofri and Roberto Di Pietro
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Automatic evaluation of faithfulness increasingly relies on a large language model acting as a judge, yet the most reliable judges are proprietary frontier models, costly and ill-suited to high-throughput monitoring. We investigate whether a panel of cheap open-weight judges (4--9B) can be aggregated to stand in for a frontier one, what the substitution sacrifices, and when it is worth making. We propose RAIM, an aggregation scheme robust to the members' correlated errors, coupling a cross-fitted stacked logistic regression with an admissibility test that, read from the members' own outputs, identifies when aggregating them improves on their best member and stays within reach of the frontier judge. We instantiate RAIM with ten judges from disjoint families across eight faithfulness benchmarks. Against Claude Sonnet, the panel retains a median 93% of its Cohen's $\kappa$ and gives up only 2.9 points of balanced accuracy on average; read as paired differences, it clearly improves on one 

---

### [156] SkillSeek: Revisiting Agent Skill Retrieval at Marketplace Scale

**链接**: https://arxiv.org/abs/2609.38822
**作者**: Guanqun Yang, Wenlong Zhang, Tian Shi, Ping Wang
**来源**: cs.IR cs.AI cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Anthropic's Agent Skills package reusable procedural know-how for an LLM agent into SKILL.md directories, and open-source aggregations have grown past 230,000 skills, making selection rather than authoring the bottleneck. The standing answer in the literature outsources selection to the agent itself: an LLM-mediated retrieval loop that rewrites queries and refines candidates inside the agent's decision loop, paying LLM tokens on every task. We present SkillSeek, an open-source two-stage skill retriever built from the standard IR recipe (a BGE-base bi-encoder feeding a small cross-encoder, exposed over MCP). Across a $4 \times 11$ grid of pool, backbone, and method on the 89-task SkillsBench benchmark, SkillSeek reaches observed parity with the LLM-mediated loop of Liu et al. at essentially no extra cost: plain bm25 alone records a pass rate at or above their refined loop on three of four settings, and a small cross-encoder covers the remaining difference on the fourth. A first-stage re

---

### [157] RankEvolve: A Reliable Multi-Agent Auto-Research Harness for Evolving Ranking Models

**链接**: https://arxiv.org/abs/2609.39551
**作者**: Zheng Chen, Linfeng Liu, Hong Li, Hong Yan
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Auto-research agents, LLM systems that propose, implement, train, and evaluate model changes across iterations, promise to automate applied ML's experimental loop. Over long horizons, execution accuracy is a binding constraint: a change can silently leak held-out data, omit normalization, disconnect a gradient, or leave a train/eval flag unwired, invalidating expensive runs and compounding error across iterations. We present RankEvolve, an auto-research framework for evolving generative ranking models. An Executable Operating Protocol (EOP) declares phases, gates, branches, and loops, and the runtime enforces the compiled state machine. A meta-meta-harness composes complete black-box coding-agent products, including Claude Code and Codex, as execution-graph nodes that review and repair one another's work. In a budget-matched evaluation, heterogeneous composition raises all-oracle execution accuracy from the best single-product baseline of 45.8 percent to 62.5 percent (paired +16.7 poin

---

### [158] EngramBench: A Capability-Grounded Benchmark for Skill-Evolution Harnesses

**链接**: https://arxiv.org/abs/2609.39284
**作者**: Zhixuan Tan, Pengjie Gu, Zhao Li, Yihan Hu, Xu He, Dong Li 等 (7 人)
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> While large language models have achieved remarkable success in isolated code generation, authentic software engineering requires sustained reasoning, complex state management, and continuous cross-domain abstraction. However, current evaluations of skill evolution in autonomous agents suffer from a critical identifiability problem: they structurally confound genuine capability abstraction with rote solution leakage (i.e., copying highly similar code from historical training data). To resolve this, we introduce EngramBench, a rigorous, capability-grounded benchmark governed by the strict axiom of capability overlap without solution overlap. Comprising 30 diverse learning tasks and 13 unseen transfer tasks, EngramBench challenges agents to navigate interactive, multi-hour development cycles driven by LLM-simulated users. Our extensive evaluation across 48 multi-hour execution trajectories -- corroborated by human-expert validation -- reveals a profound insight into procedural memory. We

---

### [159] EvoSteer: Online Self-Evolving Graph Orchestration via Reference-Anchored Credit Assignment

**链接**: https://arxiv.org/abs/2609.38661
**作者**: Mingda Zhang, Hanwen Zhang, Qiang Huang, Zijia Wang, Pengfei Guo, Yuchen Zhang 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In recent years, LLM-based multi-agent systems have been widely applied to orchestrate tool-using agents into executable communication graphs. However, existing self-evolving orchestration still faces key challenges, including post-hoc evolution that revises the team only after the trajectory ends, credit diffusion that gives every action the same terminal advantage under confounded baselines, and skill admission that is uncalibrated and never retired. To address these challenges, we propose EvoSteer, a new paradigm of Online Self-Evolving Graph Orchestration -- the orchestrator builds a running team and repairs its plausible but failing steps from execution features and a learned value estimate. To support this paradigm, we introduce Anchored Trajectory Balance (AnchorTB), a regression-style flow-matching loss that assigns each orchestration action a coefficient by balancing subtrajectories against a frozen reference. Built on the learned flow, we further propose Validated Skill Admis

---

### [160] TACIT: Optimization Models that Learn from Their Mistakes

**链接**: https://arxiv.org/abs/2609.38434
**作者**: Maxime Bouscary, Marco Molinaro, Sirui Li, Saurabh Amin, Ishai Menache, Konstantina Mellou
**来源**: math.OC cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Real-world optimization problems are difficult to model accurately because many objectives and constraints reside in domain experts' tacit knowledge, making them hard to formalize. As a result, optimization models often contain miscalibrated objectives, missing constraints, or omitted decision variables, leading to solutions that fail to reflect operational realities. We address this challenge by automatically repairing misspecified formulations using historical data consisting of past solutions and subsequent user overrides. Traditional approaches such as inverse optimization and constraint learning tend to overfit sparse data and produce complex formulations. Our central idea is to combine the reasoning capabilities and prior knowledge of LLMs with the formal grounding provided by optimization. We realize this idea through two complementary paradigms. Top-down, an LLM proposes structural repairs, including new constraints and variables, whose numerical parameters are calibrated and v

---

### [161] Team MSU GenText-Forensics Challenge 2026 Technical Report

**链接**: https://arxiv.org/abs/2609.38391
**作者**: Kirill Koltsov, Aleksandr Gushchin, Dmitriy Vatolin, Anastasia Antsiferova
**来源**: cs.CV
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Document text forgery has evolved beyond simple pixel-level manipulation: modern attacks alter not only the appearance of a document but also its meaning, and increasingly target the OCR & LLM pipelines that consume such documents. The ACM MM 2026 GenText-Forensics challenge therefore requires systems that not only decide whether a multilingual text image is forged, but also localize the point of manipulation, identify the attack type, and produce a human-readable forensic report with supporting evidence. We present our solution, a decomposed chain-of-thought (CoT) pipeline that combines a document tampering detector (DTD) with two Qwen3-VL-32B vision-language models, each LoRA-adapted to a distinct sub-task. DTD produces tampering probability maps that are converted into numbered candidate regions; a first model (the Filterer) validates these regions and assigns a preliminary forgery type, while a second model (the Semantic Detective) merges and re-grounds the surviving regions, searc

---

### [162] Cognitive Enhancement: Rethinking the Necessity of Role-Playing for Large Language Models

**链接**: https://arxiv.org/abs/2609.39853
**作者**: Xingjie Zhuang, Jialong Tang, Chulun Zhou, Buchao Zhan, Zhirui Li, Junhui Li 等 (8 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Role-playing prompting has become a popular yet simple technique for improving LLM reasoning and output quality. However, whether it consistently boosts performance across diverse domains remains unclear, as systematic validation is lacking. To fill this gap, we run multi-model, cross-domain, and multilingual experiments on MMLU and MMLU-Redux. We find that gains from role-play prompting depend heavily on model capacity, knowledge domain, and prompt language. Drawing on metacognition theory, we propose the persona-related cognitive alignment hypothesis: role-play works only when the LLM correctly grasps the designated persona and its associated knowledge domain. We test this hypothesis through persona information richness ablation, layer-wise entropy divergence analysis, and latent thought-space deflection observation. To reduce persona cognitive bias and stabilize role-play performance, we propose \textbf{M}ixed-\textbf{L}anguage \textbf{C}oncatenate \textbf{P}rediction \textbf{(MLCP}

---

### [163] OverForge: Reasoning Through Strategies and Tactics Helps Cooperative Lifelong Adaptation

**链接**: https://arxiv.org/abs/2609.39727
**作者**: Oana Madalina Fron, Ojas Shirekar, Chirag Raman
**来源**: cs.AI cs.CL cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Cooperative language-model agents must coordinate over long horizons and adapt to changing environments and to partners with unfamiliar conventions, yet existing agents map observations to actions without separating persistent coordination strategies from their tactical execution. We introduce OverForge, a training-free hierarchical architecture that separates strategic reasoning over roles and divisions of labour from tactical reasoning over actions within each agent's private, partner-conditioned world model. A metacognitive Prefrontal Cortex Module couples the two levels by forming strategy-action branches, imagining their consequences with a forward model, and committing when confident. In OvercookedV2, OverForge delivers 7 soups in a connected kitchen versus 3 for each flat LLM baseline, retains agreed roles, and adopts roles proposed by unfamiliar partners. Ablations and a fixed-strategy probe show that persistent strategies guide tactical adaptation while each reasoning level co

---

### [164] AREX-2: Advancing Self-Improving Agents through Long-Horizon Reflective Tasks

**链接**: https://arxiv.org/abs/2609.38288
**作者**: Hongjin Qian, Chaofan Li, Kun Luo, Wenqing Wei, Jianlyu Chen, Shuqi Lu 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We present AREX-2, an effort to advance the self-improving capability of LLM agents, which we define as the ability to iteratively refine a solution at test time. This ability rests on two complementary capabilities: reflection, which produces a solution better than the current one, and long-horizon execution, which keeps the iteration effective over many rounds. We hypothesize that both capabilities are domain-agnostic, and can therefore be learned in scenarios that are well suited for supervision. Accordingly, we synthesize long-horizon improvement trajectories from machine learning and algorithmic programming tasks, two domains that offer verifiable feedback and reward sustained iteration. Trained on this data, our agent, built on Qwen3.8-27B, achieves strong results on MLE-bench Lite (81.8) and Frontier-CS (70.7), transfers to deep research with 84.0 on BrowseComp, 52.6 on HLE, 92.2 on GAIA, and 93.8 on DeepSearchQA, and keeps improving as its budget of rounds grows. These results 

---

### [165] Adaptive Self-Consistency: From Black-Box Sampling to Distribution-Valued Feedback

**链接**: https://arxiv.org/abs/2609.38931
**作者**: Jingkai Huang, Yunfan Zhang, Will Ma, Weihua Zhou, Zhengyuan Zhou
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Self-consistency samples many reasoning trajectories and aggregates their final answers, treating the LLM as a black box that returns one answer per trajectory. Yet the final answer of each trajectory is sampled from a softmax vector that is available from the model's log-probabilities. We refer to this as the grey-box setting in which each trajectory reveals this answer distribution rather than a single draw from it. We formulate efficient inference in this setting as sequential mode identification with distribution-valued observations: sample trajectories one at a time and stop as soon as the LLM's modal answer is identified at a prescribed confidence level. We characterize the asymptotic stopping rate of mode identification with distribution-valued observations exactly and show that it is never worse than the black-box rate. We then propose the ASC-D algorithm, a betting stopping rule that attains this asymptotic stopping rate. On MMLU-Redux, ASC-D uses $46.4$--$95.6\%$ fewer trajec

---

### [166] Marginal Response Surface Elicitation for Zero-Label Tabular Learning

**链接**: https://arxiv.org/abs/2609.39639
**作者**: Liangyu Teng, Yicheng Ding, Jing Liu, Hengsong Liu, Juncen Guo, Hongru Li 等 (8 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tabular learning uses structured data to predict target outcomes. Traditionally, this process has relied on labeled data. However, large language models (LLMs) can be used to elicit domain priors based on the task description and feature semantics, thereby enabling predictions without labeled data. We propose Marginal Response Surface Elicitation (MARS), a method that transforms feature-level LLM priors into a reusable, zero-shot tabular classifier. To construct this classifier, MARS selects representative values for each feature from unlabeled data and prompts the LLM to provide corresponding class support scores and feature weights. It then aggregates multiple responses using the median to construct feature response functions, and makes predictions through their weighted sum without further LLM queries. Across eight tabular benchmark tasks, MARS achieves the highest average AUC and AP, outperforming direct prompting by 1.97 and 6.21 percentage points respectively, while substantially

---

### [167] Breaking Babel: A Self-Evolving Multi-Agent System for Long-Form Subtitle Translation

**链接**: https://arxiv.org/abs/2609.38660
**作者**: Haibo Jin, Xinjie Li, Najmeh Sadoughi, Yang Liu, Yibo Wang, Zhu Liu 等 (7 人)
**来源**: cs.CL cs.AI cs.CV cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-form subtitle translation requires reasoning over discourse and cultural context spanning episodes or entire series, while maintaining consistent terminology and style. Existing single-LLM methods are largely sentence-level, and multi-agent systems often use static workflows that do not adapt to scene complexity or production context. We propose SMART, a Self-evolving Multi-Agent system for long-foRm subtitle Translation. During test-time training, SMART builds persistent series-level memory and translates a subset of sentences through a dynamic router and Mixture-of-Agents layer with tools for terminology verification, subtitle constraint validation, and contextual retrieval. A judge-refiner loop scores candidates and uses textual critiques to update agent prompts and routing policies without retraining the underlying LLMs. During test-time inference, the evolved configuration translates the remaining series. We also introduce Subtitle Arena, covering 14 genres, 2--198 episodes p

---

### [168] ArgGYM: A Procedural, Engine-Verified Benchmark for Structured Defeasible Reasoning

**链接**: https://arxiv.org/abs/2609.38409
**作者**: \.Ibrahim Ethem Deveci, Funda Tan \c{C}al{\i}k, Bar{\i}\c{s} Deniz Sa\u{g}lam, Duygu Ataman
**来源**: cs.AI cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent progress in large language model reasoning has been driven by benchmarks and reinforcement learning environments with automatically verifiable rewards, particularly in mathematics, code, and formal logic. These settings make model accuracy easier to evaluate and optimize, but it remains unclear how far success under fixed problem specifications and stable evaluation criteria transfers to reasoning outside such domains. Real-world reasoning often proceeds under incomplete and revisable information: conclusions may be supported provisionally, defeated by counter-evidence, reinstated by further arguments, or revised when stronger reasons become available. Reasoning of this kind is generally referred to as defeasible reasoning. We introduce ArgGYM, a procedural benchmark and RLVR-compatible training environment for structured defeasible reasoning. ArgGYM decomposes this reasoning into twelve tasks and grounds task-specific scoring in a symbolic argumentation engine that computes the

---

### [169] Learning to Route in Visual Space via Multi-Step Embedding Retrieval

**链接**: https://arxiv.org/abs/2609.38743
**作者**: Tianyu Chen, Mingyuan Zhou, Jiaxing Wu
**来源**: cs.AI cs.IR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents rely on retrieval tools to access external knowledge, yet visual agentic search remains severely bottlenecked by standard single-step retrievers. In current pipelines, the agent must issue text queries for every intermediate step, struggling when visual clues are difficult to describe or when the retriever fails to surface necessary intermediate evidence within its top results. We hypothesize that offloading multi-step navigation across the entire embedding space directly to the retrieval tool resolves this performance bottleneck. To study this systematically, we introduce VHOP, a flexible data generation framework and benchmark with five core difficulty levels testing both visual matching and search planning. Using this framework, we develop VHOP-Router, an end-to-end training pipeline---combining supervised fine-tuning, online imitation learning, and reinforcement learning---that transforms a standard embedding model into an autoregressive multi-step retriever. Operating d

---

### [170] TAGGRAPH: Tag-Augmented Graphs for Graph Retrieval of Agent Persistent Histories

**链接**: https://arxiv.org/abs/2609.38353
**作者**: Yu-Su Chen, Yu-Jung Liang, and Pengtao Xie
**来源**: cs.IR cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-term memory lets LLM agents recall past interactions and remain consistent across sessions, but memory systems are hard to compare because they often vary in representation, indexing, retrieval, and evaluation. We present a controlled evaluation framework based on shared 5W-style conversational memories. Localized graph configurations traverse a common base graph; AdaptiveGraph adds chronological edges and Personalized PageRank diffusion. We also evaluate BM25 over the same extracted notes and OpenClaw as a raw-input external reference. Retrieval rankings vary across memory settings. On LongMemEval-S, AdaptiveGraph is the strongest graph configuration at 0.844 MRR, but BM25 reaches 0.867 and OpenClaw 0.880. On ATANT Core, localized graph traversal outperforms diffusion and BM25, whereas BM25 leads the stress rounds. Reducing LongMemEval-S within the tested range does not reproduce the ATANT diffusion penalty, but the smallest tested store remains larger than ATANT Core, so store s

---

### [171] EvoDuet: Bilevel Co-Evolution of Web Searching and Task Solving for Scientific Discovery

**链接**: https://arxiv.org/abs/2609.40340
**作者**: Young-Jun Lee, Jinheon Baek, Soyeong Jeong, Minki Kang, Seungyeon Jwa, Jonghyun Choi 等 (8 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Evolutionary search with large language models (LLMs) can stall when progress requires external knowledge the model lacks. Supplying relevant documents helps, but simply adding web search tool can keep returning the same pages as solutions change. We introduce EvoDuet, a bi-level optimization method that co-evolves solutions and search queries with fixed model parameters. At each iteration, a retrieval gate lets the LLM assess its knowledge gap and choose to retrieve new documents, reuse stored ones, or proceed without them. An inner loop refines queries and ranks documents by the solution scores they are predicted to yield; an outer loop generates candidates in parallel from these documents and records the evaluated outcomes for later searches. Across 21 optimization tasks with one candidate per iteration, EvoDuet raises OpenEvolve's normalized discovery gain from 74.1% to 78.0% with GPT-5.6-Luna and from 61.3% to 82.3% with Gemini-3.8-Flash, whereas Qwen3.5-9B does not benefit. Our b

---

### [172] Synthetic Data Characterization via Training Dynamics

**链接**: https://arxiv.org/abs/2609.39447
**作者**: Irene Lago, Ana Ezquerro, David Vilares
**来源**: cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Interpreting properties of LLM-generated data is important for understanding its utility and limitations across learning tasks. In this work, we characterize synthetic data through sample-level learnability, studying variation among LLM families and scales, alongside human-written data as a reference. We first generate synthetic datasets spanning single- and multi-label classification, labeling, and tree prediction tasks. We then derive empirical data distributions from encoder training dynamics for both machine and organic data, and estimate the robustness of these distributions across encoders. Finally, we evaluate how data selection strategies based on these learnability signals affect both data sources differently.

---

### [173] MiCo: Mutual Information Coverage Optimization through Semantic Erasure Modeling for Efficient MLLM Inference

**链接**: https://arxiv.org/abs/2609.34330
**作者**: Tinghao Wang, Yichen Guo, Qizhe Zhang, Yuan Zhang, Weimin Ouyang, Rui Huang 等 (10 人)
**来源**: cs.CV
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [174] Rethinking Multi-Image Re-Representation in Multi-Image Understanding

**链接**: https://arxiv.org/abs/2609.39363
**作者**: Gengyuan Zhang, Xiao Han, Xinyu Xie, Tong Liu, Volker Tresp
**来源**: cs.CV cs.AI
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-image understanding requires MLLMs not only to recognise the content of individual images, but also to organise visual evidence distributed across them. We study this problem through multi-image re-representation, viewing prompted Chain-of-Thought reasoning and agentic visual tool use as different ways of re-organising visual evidence during reasoning. We introduce Mosaic, a general-purpose multi-image visual harness that enables an MLLM to actively construct visual intermediates with ten composable image operations. We compare five re-representation settings on existing multi-image benchmarks and on MosaicBench, a new grounding-focused benchmark for fine-grained multi-image understanding. Our experiments show that the relative benefits of textual and visual re-representation are strongly task-dependent. Visual re-representation is particularly effective for tasks requiring precise visual evidence, including hypothesis testing, precision comparison, and orientation-sensitive reas

---

### [175] ThinkV2V: Unleashing the Reasoning Capability of MLLMs for Instruction-Guided Video Editing

**链接**: https://arxiv.org/abs/2609.38541
**作者**: Donghao Zhou, Haoyang He, Fan Zhang, Hao Yang, Guisheng Liu, Xin Gao 等 (10 人)
**来源**: cs.CV
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Instruction-guided video editing has made significant progress, yet existing methods use multimodal large language models (MLLMs) primarily as semantic encoders, so they often fall short in working with implicit edits that require causal or semantic reasoning. To bridge this fundamental gap in video editing, we propose ThinkV2V, a reasoning-driven framework for complex instruction-guided video editing, explicitly activating MLLM thinking before visual generation. At its core, ThinkV2V builds on a practical MLLM-to-DiT architecture to turn explicit thinking over the source video and instruction into refined conditioning signals for video editing. Further, we equip it with a dedicated training and inference recipe, combining Progressive Curriculum Training, which gradually cultivates the model from basic editing to reasoning-intensive cases, with Inference-Time Thinking Scaling, which iteratively refines candidate prompts and selects the most reliable one, to better elicit reasoning in c

---

### [176] NeurDuo-EEG: A Long-Sequence EEG Foundation Model with Persistent State and Explicit Memory

**链接**: https://arxiv.org/abs/2609.38587
**作者**: Yifan Wang, Haiping Liu, Yang Cui, Wenhao Cai, Shuhang Li, Xiaoyang Huang 等 (10 人)
**来源**: cs.LG
**匹配关键词**: EEG, Foundation Models, EEG Foundation Model
**相关性评分**: 9.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Electroencephalography (EEG) is recorded continuously over hours, with relevant dynamics spanning timescales from milliseconds to hours. Most EEG foundation models nevertheless process fixed windows independently, limiting their ability to capture information encoded in long-timescale dynamics. State-space architectures enable persistent recurrent processing, but long-range information remains implicitly compressed in recurrent states. We present NeurDuo-EEG, a causal EEG foundation model with channel-resolved persistent memory. NeurDuo-EEG introduces multi-timescale memory management with learned consolidation and selective retrieval, enabling persistent modelling of continuous EEG with fixed-size state. It is pre-trained on 3,955 hours of EEG from 17 public datasets using multichannel autoregressive prediction of discrete spectral codes. Across three short-window and two long-sequence downstream tasks, NeurDuo-EEG achieves the best performance on four of five benchmarks, including al

---

### [177] NeuroAtlas: Benchmarking Foundation Models for Clinical EEG and Brain-Computer Interfaces

**链接**: https://arxiv.org/abs/2605.14698
**作者**: Konstantinos Kontras, Trui Osselaer, Stylianos G. Mouslech, Angeliki-Ilektra Karaiskou, Guido Gagliardi, Thomas Strypsteen 等 (10 人)
**来源**: cs.LG cs.AI
**匹配关键词**: EEG, Foundation Models
**相关性评分**: 7.0
**数据来源**: arXiv CS Mailing

---

### [178] IDEAL: A Multimodal Domain Adaptation Framework for EEG-Eye Emotion Recognition

**链接**: https://arxiv.org/abs/2609.39421
**作者**: Yang Wu and Jinpeng Li
**来源**: cs.HC
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Electroencephalography (EEG) emotion recognition serves as a pivotal interface for human-computer interaction, yet the physiological variability across individuals complicates the already challenging task of fusing heterogeneous physiological signals (e.g., EEG and eye movements). However, most prevalent domain adaptation paradigms are tailored for unimodal scenarios, failing to address the heterogeneity of multimodal signals. Furthermore, they predominantly rely on feature-level alignment, overlooking the fundamental data-level discrepancy, which risks compromising fine-grained discriminative information during aggressive adaptation. To bridge these coupled gaps, we propose Instance-based Domain Expansion and Adversarial Learning (IDEAL), a unified framework that synergizes instance-level curriculum expansion with feature-level hierarchical adversarial alignment. IDEAL first introduces a multi-model collaborative screening mechanism, which propagates high-confidence target samples to 

---

### [179] PHASE: A Physiology-Guided Hierarchical Foundation Model for Intracranial EEG

**链接**: https://arxiv.org/abs/2609.36087
**作者**: Yipeng Zhang, Chenda Duan, Yuanyi Ding, Tianyi Wang, Atsuro Daida, Masaki Izumi 等 (10 人)
**来源**: cs.LG cs.AI
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [180] Aligning the Incomplete: Joint Distribution Calibration for Multimodal EEG-Eye Emotion Recognition

**链接**: https://arxiv.org/abs/2609.39413
**作者**: Yang Wu and Jinpeng Li
**来源**: cs.HC
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The success of cross-subject multimodal emotion recognition hinges on maintaining the consistency of the joint data distribution across individuals. However, real-world deployment frequently triggers the \emph{asymmetric joint distribution collapse}: EEG signals suffer from severe cross-subject distribution shifts, while eye movements sensors are susceptible to packet loss and tracking failures. Existing methods treat domain adaptation and missing-modality imputation as disjoint tasks. Consequently, they fail to resolve the compounded errors when both degradations co-occur, either propagating domain shifts through imputed signals or destroying the joint decision boundary. To tackle this unified challenge, we propose GUARD (\textbf{G}radient-guided \textbf{U}nsupervised \textbf{A}symmetric \textbf{R}ecovery of \textbf{D}istributions). First, GUARD establishes a reliable anchor manifold in the source domain by employing a theoretically grounded gradient-weighted objective, which forces t

---

### [181] Molecular Property Prediction under Structural Shift with Tabular Foundation Models

**链接**: https://arxiv.org/abs/2609.38744
**作者**: Jinmo Lee, Dooho Lee, Minho Jeong, Jaemin Yoo
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Predicting molecular properties for compounds that differ structurally from labeled training molecules is important for drug discovery and materials design. Tabular foundation models (TFMs) offer a promising approach through in-context learning, but their performance under structural shifts and the value of molecular comparisons in this setting remain underexplored. We study structural generalization in molecular property prediction and introduce MolPAIR (Molecular Pair-Augmented In-context Refinement), a framework that combines molecule-level and molecular-pair contexts without task-specific parameter updates. A global tabular foundation model (TFM) first predicts a query's property from labeled molecular examples. A second frozen TFM predicts differences in prediction errors between the query and labeled reference molecules, using these comparisons to refine the initial prediction. Across 58 MoleculeACE and Polaris tasks, CheMeleon representations combined with TabPFN-3 already outpe

---

### [182] Raw-Routed Mixture of Adapters: A Causal Intervention for Routing Collapse in Time Series Foundation Models

**链接**: https://arxiv.org/abs/2609.39445
**作者**: Hung Phan, Thuy T. Nguyen, Minh Ngoc Dinh, Nhat-Quang Tran
**来源**: cs.LG stat.ML
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Time series foundation models (TSFMs) commonly adapt to new data by attaching a single trainable head to a frozen backbone, a one-size-fits-all setup that underfits heterogeneous regimes. Replacing the head with a mixture of experts is the standard upgrade, but on instance-normalized backbones (the dominant TSFM design class) it fails: routing entropy collapses to zero and one expert absorbs every input, a failure we call normalization-induced routing collapse. Standard MoE rescue mechanisms do not repair it, because the cause is in the router's input, not its optimization. Pre-encoder normalization strips the statistics a router would need to tell regimes apart. A mutual-information decomposition makes this precise and yields a signal-ratio that, computed before training, predicts dataset vulnerability (Spearman $\rho = -0.88$). Eight causal controls, including a vision-modality replication, isolate instance normalization as the cause. The prescription is a minimal causal intervention

---

### [183] TaxDistill: Improving Metagenomic Taxonomic Annotation via Distilled Genomic Foundation Models

**链接**: https://arxiv.org/abs/2605.28868
**作者**: Rongye Ye, Lun Li, Zheng Luo, Yiran Zhan, Zhang Zhang, Shuhui Song
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [184] Grounding Time-Series Foundation Models in Digital Twin Topology for Predictive Maintenance

**链接**: https://arxiv.org/abs/2609.40071
**作者**: Sizhe Ma, Katherine A. Flanigan, Mario Berg\'es
**来源**: eess.SP cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Digital twins increasingly support downstream analytical tasks that depend on time-series data, motivating interest in time-series foundation models (TSFMs) as scalable backbones. However, TSFMs are primarily pretrained for temporal continuation and often underperform on unseen tasks such as regression, and systematic empirical comparisons against state-of-the-art dedicated models in digital twin contexts remain limited. This paper makes three contributions. First, we benchmark five well-known TSFMs with frozen backbones on remaining useful life (RUL) prediction using the C-MAPSS dataset, finding that multivariate architectures substantially outperform univariate ones, particularly under varying operating conditions. This raises a deeper question: when cross-channel dependencies can be modeled through pretrained weights, target-task adaptation, and digital twin-derived representations, how much does each contribute, and are they complementary? Second, we propose a topology-informed fus

---

### [185] Bootstrapping a 4D LiDAR Annotation Tool from Video Foundation Models

**链接**: https://arxiv.org/abs/2608.25418
**作者**: Jihun Kim, Hyun-Kurl Jang, Hyemin Yang, Jinnyeong Yang, Hyeokjun Kweon, Kuk-Jin Yoon
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [186] ShieldCLIP: Selective Safety Alignment for Harmful Content Mitigation in Multimodal Foundation Models

**链接**: https://arxiv.org/abs/2609.39688
**作者**: Tobia Poppi, Silvia Cappelletti, Samuele Poppi, Marcella Cornia, Lorenzo Baraldi, Diego Garcia-Olano 等 (7 人)
**来源**: cs.CV cs.AI cs.CL cs.MM
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal encoders such as CLIP underlie many downstream systems, but their web-scale training data embed harmful associations that safety alignment must suppress without unnecessarily changing benign representations. Because ethical and practical constraints prevent collecting real unsafe content at scale, existing datasets pair safe real samples with generated counterparts, but label every generated sample unsafe, even when one modality is individually safe. To address this, we introduce ShieldCLIP, the first framework to condition safety alignment on the observed safety state of each modality rather than the origin of a sample, preserving safe content while redirecting only what is unsafe. We also introduce ViSUv2, a 195k-quadruplet dataset with independent per-modality safety labels across 578 concepts and 28 categories. Using these labels, ShieldCLIP defines a four-way conditional objective beyond pair-level supervision: safe content is anchored, unsafe modalities are redirected 

---

### [187] Boosting Knowledge Graph Foundation Models via Enhanced Negative Sampling

**链接**: https://arxiv.org/abs/2605.27023
**作者**: Yinan Liu, Wenjin Xu, Zhiyuan Zha, Xiaochun Yang, Bin Wang
**来源**: cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [188] When, Not How Much: Evaluating Time-Series Foundation Models on Sparse Events

**链接**: https://arxiv.org/abs/2609.39386
**作者**: Daniel Schoess and Florian von Wangenheim
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Pretrained time-series foundation models (TSFMs) are evaluated as forecasters of future values, yet for sparse series many decisions depend only on which future periods contain activity. Standard benchmarks do not assess this. On five sparse datasets, we rank positions within forecast windows that contain both events and zeros. The released point forecasts of 12 TSFMs improve chance-corrected average precision over training-free references by at most 0.031, and in chance-corrected AUC the median TSFM falls below them on every dataset. With event supervision, linear probes of six frozen backbones improve on their backbone's point forecast in 29 of 30 backbone--dataset pairs. Averaging the predicted quantiles instead of taking their median improves the ranking of most TSFMs that forecast the median, and on two datasets the strongest such outputs rival the probes. The probes' advantage over raw-context learners depends on the dataset, and under the same probe, pretrained features outperfo

---

### [189] Residuals Are Not Enough: Limits of Physics-Informed Pre-Training for Scientific Foundation Models

**链接**: https://arxiv.org/abs/2503.19081
**作者**: Serge Kotchourko, Amin Totounferoush, Michael W. Mahoney, Steffen Staab
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [190] MoRAX: Mobility-based Representation Augmentation for Geospatial Foundation Models

**链接**: https://arxiv.org/abs/2608.17848
**作者**: Ya Wen, Jixuan Cai, Yulun Zhou, Alec Kirkley
**来源**: cs.LG cs.SI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [191] CIDER-FM: Foundation Models for Causal Inference from Diverse Experimental Regimes

**链接**: https://arxiv.org/abs/2609.39523
**作者**: Yuche Gao, Arik Reuter, Siyuan Guo, Anish Dhir, Bernhard Sch\"olkopf, and Adrian Weller
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Causal foundation models (CFMs) amortise causal inference over priors of synthetic structural causal models (SCMs), predicting the effect of an experiment on a specific variable. However, observational data alone may leave multiple causal models compatible with available evidence, while experimental data with interventions on exactly the variable of interest might be unavailable. This work studies CFMs as a method to combine finite observational and surrogate-interventional datasets in order to predict a target conditional interventional distribution (CID) more accurately than with observational data alone. We first formalise the conceptual benefits of surrogate experiments. Building on this analysis, we introduce \textsc{Foundation Models for Causal Inference from Diverse Experimental Regimes} (\emph{CIDER-FM}), a causal foundation model that uses an intervention-aware representation and hierarchical three-axis attention to exchange information across variables, samples, and experimen

---

### [192] Cryo-Bench: Benchmarking Foundation Models for Cryosphere Mapping

**链接**: https://arxiv.org/abs/2603.01576
**作者**: Saurabh Kaushik, Lalit Maurya, Beth Tellman, Swalpa Kumar Roy, Valerio Marsocci, Gustau Camps-Valls 等 (7 人)
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [193] VIP-COP: Context Optimization for Tabular Foundation Models

**链接**: https://arxiv.org/abs/2605.12904
**作者**: Yilong Chen, Xueying Ding, Leman Akoglu
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [194] Predicting Multi-View Rashomon Representation: Can We Learn Where Models Disagree?

**链接**: https://arxiv.org/abs/2609.39848
**作者**: Mingyue Ma, Zongbo Han, Changqing Zhang, Guangyu Wang
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Foundation models are increasingly adopted across a wide range of applications, often serving as core blocks within AI systems. Yet different foundation models may encode the same input from multiple different views, leading to substantial representation disagreement, which we term Rashomon Representation. Such disagreement often signals inputs that a given model encodes in a way inconsistent with other models, offering a valuable yet underexplored signal for input reliability estimation. While prior work has largely focused on measuring disagreement across multiple models with a representation set, we instead focus on predicting disagreement from a single representation. We hypothesize that this disagreement follows some consistent, input-dependent patterns rather than occurring at random. To test this, we quantify disagreement by comparing each sample's nearest neighbors across different models' representation spaces, then train a lightweight predictor that estimates disagreement fro

---

### [195] Diffusable Latents from Structure-Agnostic Distillation

**链接**: https://arxiv.org/abs/2609.39657
**作者**: Adrien Ramanana Rahary, Nicolas Dufour, Patrick P\'erez, and David Picard
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Distilling pretrained foundation models into an autoencoder bottleneck improves latent diffusability, enabling diffusion models to converge faster and reach higher sample quality. Standard distillation aligns the latent at each position to a co-located teacher feature, tying the latent layout to the teacher's. We show this constraint is unnecessary: aligning a single pooled image-level descriptor to the teacher's performs as well as or slightly better than dense position-wise distillation. We compare first-order and relational pooled objectives across latent shapes and teacher modalities. First-order matching extends naturally to 1D token-sequence latents and across modalities, where distilling a text encoder into an image autoencoder still improves diffusability; a relational objective based only on each image's nearest neighbours improves it as well. Code and blog post are available at https://github.com/AdrienRR/structure-agnostic-distillation and https://kyutai.org/blog/2026-09-28-

---

### [196] A Comprehensive Benchmark of Source-Free Universal Domain Adaptation on Time Series Representations

**链接**: https://arxiv.org/abs/2609.39810
**作者**: Romain Mussard, Fannia Pacheco, Maxime Berar, Paul Honeine, Gilles Gasso
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Source-Free Universal Domain Adaptation (SF-UniDA) extends Universal Domain Adaptation by removing access to source data at adaptation time while still handling label-set mismatches between domains. Despite growing interest in this setting for image data, no benchmark exists for time series, which are more challenging. We present the first SF-UniDA benchmark on time series. In addition, we provide the first study of pretrained foundation models as feature extractors for time series domain adaptation. In this context, we identify a critical and previously underexplored limitation of all existing SF-UniDA methods: the inference threshold for unknown-sample rejection is highly sensitive. We address this by proposing a plug-in auto-thresholding module that can be integrated into any SF-UniDA method. Experiments on three well-known time series datasets confirm the suitability of this module. They also highlight that foundation models do not systematically outperform classical backbones and 

---

### [197] From Given to Gathered Evidence: Agentic Learning for Longitudinal Medical Reasoning

**链接**: https://arxiv.org/abs/2609.39566
**作者**: Minye Shao, Chaohui Yu, Yixuan Wu, Fan Wang, Ling Shao, Yang Long
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Foundation models can serve as clinical agents through tool-use harnesses. However, conventional medical benchmarks assess reasoning over preselected evidence rather than the ability to seek it across clinical records and longitudinal imaging. We propose CASE: a series of role-specific Clinical Agents for Seeking Evidence, together with a tool-use harness and an agentic post-training framework for compact vision-language policy models. We further introduce a longitudinal multimodal benchmark built on UK Biobank, comprising 50,401 clinical questions derived from real-world ICD-10-coded diagnoses of 4,739 participants. Each question links to a patient-specific environment containing clinical context and multi-sequence MRI from baseline and follow-up visits, where agents autonomously select which visits, organs, modalities, slices, and specialist tools to inspect and compare. Supervised fine-tuning transfers evidence-seeking workflows from 14,734 frontier-model interaction trajectories, f

---

### [198] Universal Cross-Prompt Adversarial Attacks on Promptable Concept Segmentation

**链接**: https://arxiv.org/abs/2609.39265
**作者**: Ziqi Zhou, Yifan Hu, Yufei Song, Haowen Jiang, Xianlong Wang, Shengshan Hu 等 (8 人)
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The Segment Anything Model (SAM) achieves remarkable performance in visual segmentation. The latest SAM3 extends promptable segmentation to concept-level prediction, broadening the scope of segmentation foundation models. While recent works reveal that SAM and SAM2 are vulnerable to adversarial examples, the robustness of SAM3 under the concept segmentation paradigm remains unexplored. In addition, existing adversarial attacks on SAM-series models exhibit limited cross-prompt transferability. To this end, we propose AdvPCS, a universal cross-prompt adversarial attack for Promptable Concept Segmentation (PCS), including a min-max prompt optimization strategy, a global-local perception deception attack, and a temporal transition deviation attack. Specifically, we first identify the hardest-to-attack prompts via min-max bilevel optimization. In the inner maximization, we enhance diversity over candidate point, box, and text prompts. In the outer minimization, we select prompts with the hi

---

### [199] Vision-Language-Action Autonomous Driving Agent with Language-based Memory

**链接**: https://arxiv.org/abs/2609.38641
**作者**: Kai Yan and Xiangyu Chen and Yulong Cao and Alex Naumann and Peter Karkus and Yan Wang and Jef Packer and Alex Schwing and Yuxiong Wang and Boris Ivanovic and Wenjie Luo and Marco Pavone
**来源**: cs.CV cs.RO
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Vision-Language-Action (VLA) foundation models have recently emerged as one of the prevailing solutions for autonomous driving, as they can utilize knowledge acquired during vision-language pretraining for accurate and interpretable driving. However, VLAs can take only a limited number of frames as visual input due to the high token cost of an image, which is problematic for memory-dependent tasks such as determining the arrival order at all-way stops and long-horizon driving scene understanding. Existing solutions use latent vector memories accessed through cross-attention, which are neither interpretable nor portable. In this paper, we propose AD-Memo, a general-purpose VLA driving agent with language-based memory. The agent outputs memory as an extension of its Chain-of-Thought (CoT) to record surrounding objects critical to driving; this memory becomes part of the agent's future input. We curate memory-based datasets and train VLAs with a two-stage recipe: Supervised Fine-Tuning (S

---

### [200] Agentic Relative Camera Pose Estimation via Learned Ranking and Verification

**链接**: https://arxiv.org/abs/2609.38755
**作者**: Zhining Gu, Shangjie Du, Weimin Qiu, Carl Olsson, Ping Liu, Meng Tang
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A wide range of approaches have been developed for camera pose estimation, including correspondence-based methods, end-to-end pose regression, and recent 3D geometric foundation models. Our key observation is that no single estimator is optimal for diverse challenges, such as wide baselines, lack of texture, appearance changes, and occlusions. Further analysis reveals substantial performance variation across both benchmarks and individual image pairs, with different estimators exhibiting complementary strengths. We introduce PoseAgent, an agentic framework for relative camera pose estimation that dynamically orchestrates pose estimators through learnable ranking and verification. Given an image pair, a profiling agent first extracts appearance, semantic, and geometric features relevant to pose estimation, e.g., scene type. A learned ranking agent then predicts the relative competence of multiple pose estimators given the image-pair profile. The top-ranked estimator is executed, and its

---

### [201] CellMSA: Context Modeling for Single-Cell Representation Learning

**链接**: https://arxiv.org/abs/2609.38908
**作者**: Suyuan Zhao, Minghao Liu, Yizhen Luo, Zaiqing Nie
**来源**: q-bio.GN cs.AI cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Single-cell transcriptomics enables profiling of cellular states at unprecedented resolution, but its high dimensionality, sparsity, and technical batch effects pose significant challenges for representation learning. Existing single-cell foundation models typically encode each cell independently or only model cells from the same batch for denoising, thereby underutilizing the rich relational information across batches and cell types to model gene expression patterns. We argue that single-cell models can benefit from more informative cell-context modeling. By comparing consistency and variation across cells, models can capture fine-grained gene-gene dependencies associated with cell states, which are essential for learning high-quality representations. Inspired by the use of multiple sequence alignment (MSA) context in protein modeling, we propose CellMSA, a single-cell representation learning framework that introduces an MSA-inspired inductive bias into transcriptomic modeling. For ea

---

### [202] Gestalt: a meta-foundation model for astronomy

**链接**: https://arxiv.org/abs/2609.38312
**作者**: Michael J. Smith, Shashwat Sourav
**来源**: astro-ph.IM cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The Platonic Representation Hypothesis predicts that sufficiently scaled foundation models converge on a shared representation of the world. As each non-converged model gives a noisy view of a common structure when passed the same input, we ask whether we can combine models into a representation that outperforms its individual components. We test this on galaxies: we embed images via a basket of 22 frozen foundation models from eight families, whiten each view, and take a randomised SVD of the embedding concatenation. The resulting 1024-dimensional embedding outperforms every basket member on 19/21 of our tested metrics for physical property and galaxy morphology estimation for HSC, JWST, and DESI Legacy Survey imagery. We find that performance rises with basket size and basket architectural diversity, and that the meta-foundation model's performance transfers across astronomical surveys. We conclude that a useful astronomical foundation model can be assembled from existing generalist 

---

### [203] OpenTSLM TeeMoE: A Unified Time-Series Language Model for Forecasting, Contextual Prediction, and Reasoning

**链接**: https://arxiv.org/abs/2609.40265
**作者**: Tony Chen, Timo Stoffregen, Maxwell Xu, Thomas Kaar, Martin Maritsch, Geremia Pompei 等 (10 人)
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Real-world time-series applications increasingly require models that can handle time series forecasting, context-conditioned prediction, and language-based temporal reasoning. Yet current time-series foundation models remain fragmented across these capabilities: numerical specialists often provide the strongest forecasts, while language-based models offer broader contextual understanding and analysis. A central challenge is to unify these heterogeneous capabilities without reducing their individual performance. We introduce OpenTSLM TeeMoE, a generalist time-series language model that can forecast directly from observed time series, reason over textual context and temporal patterns, and synthesize and refine predictions from external numerical forecasting specialists. We independently train three low-rank experts for forecast aggregation, native forecasting, and temporal analysis over a shared backbone. A learned LoRA mixture-of-experts controller then weights their frozen parameter up

---

### [204] GRC-Pose: Generation-Reconstruction Correspondence for Prior-Free 6D Object Pose Tracking

**链接**: https://arxiv.org/abs/2609.39116
**作者**: Shiyang Liu, Weiquan Lin, Luping Xiao, Jiadong Tang, Yi Yang, Yu Gao 等 (7 人)
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Prior-free 6D object pose tracking seeks to recover the trajectory of an unseen object from a single RGB video without object-specific CAD models, posed reference images, or pose annotations. Geometric foundation models provide complementary object-centric and scene-centric cues, yet SAM3D CAD is indexed by an arbitrary object-local surface parameterization, whereas reconstructed evidence is expressed in a sequence-specific world frame with partial surface coverage. To exploit this complementarity, we formulate tracking as generation-reconstruction correspondence and introduce GRC-Pose, a correspondence-based framework that combines learned correspondence prediction with robust pose estimation. Concretely, GeoCorr-Matcher estimates weighted object-scene correspondences and per-match uncertainty for each pose candidate. FGH-Solver integrates these matches through multiple robust geometric estimators and sequence-level posterior inference, while a posterior-gated memory retains only inli

---

### [205] BAM! Bayesian Anything Model: a foundation model for generative computational imaging

**链接**: https://arxiv.org/abs/2609.39660
**作者**: Alessio Spagnoletti, Charlesquin Kemajou Mbakam, Jonathan Spence, Andr\'es Almansa, Marcelo Pereyra
**来源**: cs.CV stat.ML
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Generative models are transforming Bayesian computational imaging, yet the field still lacks physics-aware foundation models. Current practice falls into two camps. Large foundation image models are deployed as plug-and-play priors with zero-shot approximate likelihood guidance, which introduces significant bias and computational cost. Physics-aware generative models avoid this bias, but each is tied to a specific dataset, task and instrument. We introduce BAM (Bayesian Anything Model), a lightweight foundation model for few-step, physics-aware posterior sampling that generalises robustly to unseen data and tasks, zero-shot or with minimal finetuning. BAM upgrades the operator-conditioned Reconstruct Anything Model (RAM) backbone (Terris et al.) into a conditional flow map, so instrument physics is specified at inference time rather than fixed during training. BAM has just 36M parameters and is pre-trained jointly on large image corpora and libraries of forward operators. A single netw

---

### [206] NodeGround: A Node Classification Benchmark in the Graph Foundation Model Era

**链接**: https://arxiv.org/abs/2609.39673
**作者**: Jinmo Lee, Dooho Lee, Minho Jeong, Jaemin Yoo
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Can a pretrained graph model replace training and tuning a separate predictor for each dataset? Answering this requires evaluating prediction quality alongside computational cost. We present NodeGround, a node classification benchmark that puts graph foundation models (GFMs) and dataset-specific supervised learning under a common evaluation framework. The benchmark spans 51 datasets and evaluates six GFMs alongside 15 supervised methods under two label-availability regimes. Shared data partitions, validation-only model selection, controlled hyperparameter searches, and multiple predictive metrics make comparisons systematic, while workflow measurements account for adaptation, training, tuning, and inference. The results favor carefully tuned graph neural networks overall. GraphPFN reaches third place by Elo when more labels are available, yet its relative strengths vary substantially with dataset properties. Efficiency comparisons further qualify the benefits of pretrained reuse: GVT a

---

### [207] FAST: Flow Any Scene Transformer

**链接**: https://arxiv.org/abs/2609.39748
**作者**: Yongjian Zhang, Longguang Wang, Zhuo Song, Zhiheng Fu, Liang Lin, Yulan Guo
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Scaling has become a primary driver of progress in language and vision foundation models, yet its role in precise correspondence matching remains underexplored. In this work, we present Flow Any Scene Transformer (FAST), a scalable correspondence model driven by two key insights. First, we reveal that the query-key projections inside single-view vision foundation models encode a coarse yet reusable prior for cross-view matching. Second, reusing these pretrained projections in cross-attention form yields a highly effective initialization for a ViT-based matcher built from a single-view encoder. Guided by these insights, we build FAST upon a vanilla single-view foundation model, utilizing a zero-parameter rewiring strategy to convert selected self-attention layers into cross-attention for cross-view interaction. This design allows ViT-based matchers to scale with advances in single-view foundation models, bypassing the need for a dedicated pair-centric pretraining stage. To fully unlock 

---

### [208] StreamRig: Exploiting Intra-Rig Geometry for Streaming Multi-Camera Odometry

**链接**: https://arxiv.org/abs/2609.40244
**作者**: Yufei Wei, Shuhao Ye, Qi Wang, Xin Zheng, Qing Huang, Rong Xiong 等 (7 人)
**来源**: cs.CV cs.RO
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Mobile robots and vehicles carry synchronized multi-camera rigs, yet many streaming 3D foundation models are designed for monocular input, leaving efficient use of rig geometry a challenge. We present StreamRig, a freeze-and-stream framework that builds causal streaming odometry for calibrated rigs on a frozen multi-view 3D foundation model. The frozen front-end jointly perceives the synchronized views using rig calibration. A Rig-Resampler compresses their features, a CausalBridge applies causal attention with a key-value cache, and a lightweight head regresses rig poses. A periodic re-anchoring protocol supports stable pose estimation over long sequences. Only these modules are trained, 74.6M parameters in total, with relative poses as the sole supervision. Our two-stage training strategy combines group relocalization pretraining with causal rig training to transfer the geometric priors of the frozen front-end and the alignment ability of the pretrained modules to streaming odometry.

---

### [209] SCALE: Synthetic Calibration via Agreement Labeling in Embedding Space

**链接**: https://arxiv.org/abs/2609.38705
**作者**: Wenjun Liu, Saeed Hassanpour
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Foundation models for computational pathology are usually evaluated using AUC and accuracy, while calibration is often left untested. This matters because a model can be accurate on average but still assign overly confident probabilities to cases that are difficult even for pathologists. We study calibration across eight pathology foundation models. Using pathologist agreement as a measure of diagnostic difficulty, we find that calibration error is consistently higher on low-agreement cases than on high-agreement cases. This pattern is not apparent from aggregate expected calibration error (ECE) alone. We then propose synthetic agreement calibration, a method for improving calibration without collecting multi-annotator labels. Given a trained linear probe, we select high-confidence embeddings as class anchors and interpolate between anchors from opposite classes. The interpolation weights encode a continuous notion of diagnostic ambiguity, which we use as a synthetic agreement signal t

---

### [210] DiffWAM: A Fast and Efficient Navigation World Action Model

**链接**: https://arxiv.org/abs/2609.39763
**作者**: Mo Zhu and Yuze Wu and Xijie Huang and Xiao Cui and Fei Gao and Xin Zhou
**来源**: cs.RO cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Pretrained video foundation models encode rich semantic and spatiotemporal priors for embodied navigation, yet converting these priors into UAV motion typically requires expensive future-video synthesis and geometric reconstruction. We investigate whether the motion implicit in future visual prediction can instead be recovered directly from the predictive representations of a frozen video model. To this end, we present DiffWAM, a geometry-conditioned navigation world-action model that directly transforms multi-level predictive features into continuous camera trajectories. Its Grid-Motion module preserves spatial-temporal motion associations, while Latent2Pose grounds them with first-frame geometry to recover metrically meaningful 3D motion. Complete video rollouts and geometric reconstruction are required only for offline supervision, eliminating future-video decoding and multi-frame reconstruction during deployment. We further introduce FastDreamer, which overlaps predictive and geome

---
