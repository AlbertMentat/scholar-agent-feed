# 📑 论文索引 - 2026-09-02

共 304 篇论文

---

### [1] Mechanistic Diagnostics of Spatial Lexical Bias in Multimodal Large Language Model Spatial Reasoning

**链接**: https://arxiv.org/abs/2606.01914
**作者**: Chuang Ma, Qianying Liu, Tomoyuki Obuchi, Fei Cheng, Wang Yang, Sudong Cai 等 (9 人)
**来源**: cs.CL cs.CV
**匹配关键词**: Large Language Model, Multimodal Large Language Model
**相关性评分**: 7.0
**数据来源**: arXiv CS Mailing

---

### [2] Dimple: Discrete Diffusion Multimodal Large Language Model with Parallel Decoding

**链接**: https://arxiv.org/abs/2505.16990
**作者**: Runpeng Yu and Xinyin Ma and Xinchao Wang
**来源**: cs.CV
**匹配关键词**: Large Language Model, Multimodal Large Language Model
**相关性评分**: 7.0
**数据来源**: arXiv CS Mailing

---

### [3] When Does Bigger Help? A Controlled Study of LLM Scale for Ontology Learning

**链接**: https://arxiv.org/abs/2608.31118
**作者**: Hamed Babaei Giglou, S\"oren Auer, Jennifer D'Souza
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The effect of Large Language Model (LLM) scale on ontology learning (OL) performance remains insufficiently characterized. We present a controlled evaluation of 13 models spanning dense and Mixture-of-Experts variants from the Qwen3.5 and Qwen3.6 lineages, together with proprietary GPT release variants, using the OntoLearner retrieval-augmented generation pipeline. All models are evaluated with the same embedding model, retrieval configuration, prompt templates, decoding settings, datasets, and metrics on term typing, taxonomy discovery, and non-taxonomic relationship extraction across four biomedical and materials science and engineering ontologies. Within the dense Qwen3.5 lineage, increasing parameter count primarily improves precision rather than recall, with the largest gains occurring between 9B and 27B parameters. However, the effect of scale is neither monotonic nor uniform across tasks and domains. Dense 27B models outperform substantially larger sparse models on term typing, 

---

### [4] Learning Simple Test-Time Environments for LLM Web Agents

**链接**: https://arxiv.org/abs/2608.29305
**作者**: Junxuan Li, Zijun Liu, Ziyi Huang, Peng Li, Yuzhou Liu, Ming Yan 等 (7 人)
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents have demonstrated remarkable proficiency in manually constructed environments, yet their performance frequently collapses when transitioned to complex real-world settings. Existing research largely attribute this degradation to the compositional generalization gaps in LLMs on combinations of multiple simple, well-structured environments. In this work, we propose that LLM web agents can learn simple environment observations at test time. Specifically, we introduce trial steps for agents to decompose a complex environment observation into sub-modules, and implement a label-free learning method, Test-Time Environment Decomposition (TTED), to adapt agent behaviors with experience during inference. Our empirical evaluations demonstrate the framework's efficacy across both synthetic and realistic benchmarks, showing (1) experience gains acquired within simpler sub-environments can be effectively composed to improve performance in the full one, and (2) test-t

---

### [5] Can LLMs Take the Pulse of the Economy? A Real-Time Evaluation of LLM Nowcasts on Macroeconomic Indicators

**链接**: https://arxiv.org/abs/2608.30110
**作者**: Xinyue Zhao, Ruiyi Zhang, Liqin Ye, Rui Cao, Pengtao Xie, Sudheer Chava
**来源**: cs.CL cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Nowcasting headline macroeconomic indicators, i.e., estimating an indicator's value for the current reference period before its official release, is critical for monetary policy and financial markets, and central banks devote dedicated teams of expert economists to producing such estimates. Large language model (LLM) agents are a promising candidate for this task, combining broad world knowledge with real-time web search and supporting queries at higher frequency than institutional nowcasts. Evaluating their nowcasting capability is, however, challenging: headline indicators such as GDP and CPI are widely reported and likely memorized during pretraining, so any evaluation on historical releases is vulnerable to data contamination. To address this, we introduce LiveMacroEval, a live, contamination-resistant benchmark in which LLM agents produce hourly nowcasts for sixteen major U.S. macroeconomic indicators over a pre-release window closing at each official release. Nowcast quality is a

---

### [6] S3C-LLM: Skill-Code Guided Agentic Language Models for Spectrum-to-Structure Elucidation

**链接**: https://arxiv.org/abs/2608.30910
**作者**: Xuanle Zhao, Xinyuan Cai, Xiang Cheng, Bo Xu
**来源**: cs.LG cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Spectroscopic structure elucidation is central to molecular analysis, but recent Large Language Model (LLM)-based methods mostly formulate it as direct spectrum-to-SMILES generation. Although this paradigm can leverage paired spectral data, it does not explicitly model the analytical workflow used by spectroscopists, such as diagnostic peak interpretation, fragment reasoning, formula constraints, and chemical consistency checking. In this paper, we introduce S3C-LLM, a skill-guided and code-grounded agentic LLM for spectrum-to-structure elucidation. Rather than directly predicting a molecule, S3C-LLM retrieves modality-specific spectroscopy skills, executes analysis code to instantiate these skills on the input spectra, and integrates the resulting peak-level evidence and formula constraints before generating SMILES. Specifically, we contribute a self-evolving spectroscopy skill library, a thinking-augmented skill-code trajectory construction pipeline, and a two-stage training strategy

---

### [7] TrainSDC: Characterizing and Mitigating Silent Data Corruption in Large Language Model Training

**链接**: https://arxiv.org/abs/2608.30769
**作者**: Zhipeng Xia, Haotian Xu, Siyu Yun, Liqi Lin, Hu Liu, Yu Li 等 (7 人)
**来源**: cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM training is increasingly vulnerable to silent data corruption (SDC), yet existing protection methods largely treat Transformer computations uniformly because their vulnerability remains poorly understood. We present the first systematic characterization of SDC vulnerability across major computation interfaces in both the forward and backward passes of Transformer training. Our analysis reveals two distinct error propagation mechanisms: forward-pass vulnerability is highly location dependent, with faults on the Q/K path producing persistent training deviations, whereas backward-pass vulnerability is largely governed by gradient exponent distributions rather than computation locations. Motivated by these observations, we propose TrainSDC, a characterization-guided protection framework consisting of Q/K-path recomputation, residual-gain monitoring, and exponent-aware gradient scaling. Experiments on Llama 3.2-1B and Qwen3-0.6B show that TrainSDC maintains training behavior close to fa

---

### [8] Wrong Prediction, Right Answer: Recovering Evidence from Collapsed LLM Sequence Scores

**链接**: https://arxiv.org/abs/2608.31068
**作者**: Qiyao Yan, Chenpeng Wang, Liangming Pan
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> When a large language model fails a reasoning task, it is often assumed to lack the underlying capability. However, this conflates a genuine absence of reasoning with a late-stage output bottleneck. We observe a consistent readout gap across diverse reasoning benchmarks: hidden-state probes successfully decode correct answers even when native sequence scoring completely collapses due to structural biases. To test whether instance-specific logic survives this collapse, we introduce a diagnostic protocol using a minimal, target-label-free additive correction. Fitting just two parameters on as few as 25 unlabeled examples recovers 9--34 accuracy points for Qwen3.5 models, transferring successfully to OLMo-2-1B and Llama-3.1-8B. Crucially, these recovered decisions persist on hard instances unresolved by simple lexical overlap and significantly exceed count-preserving permutation baselines. Our results show that many apparent zero-shot reasoning deficits are expression failures masking int

---

### [9] Breaking Darknet CAPTCHAs with general purpose LLM

**链接**: https://arxiv.org/abs/2608.28794
**作者**: Benjamin Fehrensen and Jens Hubler
**来源**: cs.CR cs.CV
**匹配关键词**: LLM, MLLM
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Our work evaluates the effectiveness of automated methods for solving CAPTCHA challenges commonly encountered in darknet environments. These CAPTCHAs are typically designed to operate without JavaScript, resulting in distinct characteristics compared to mainstream CAPTCHA systems. Our study considers three representative challenge types: open-circle localization, rotation-based alignment, and object-selection CAPTCHAs. The experiments reveal a systematic limitation of contemporary MLLMs: while they are generally capable of identifying relevant visual structures, they frequently struggle with precise spatial localization and geometric transformations. These deficiencies can be mitigated either through task reformulation or by augmenting the models with specialized image processing tools. These deficiencies can be mitigated by task reformulation or by equipping the model with specialized image-processing tools. We therefore propose a hybrid framework in which an MLLM serves as a high-lev

---

### [10] Which LLM for Which Work? Budgeted Model Allocation under Uncertain Evaluation

**链接**: https://arxiv.org/abs/2608.29560
**作者**: Hamed Khosravi, Xiaoming Huo
**来源**: cs.LG math.OC stat.ML
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A company with a fixed artificial intelligence (AI) budget must decide which large language model (LLM) handles each recurring workload. What it lacks is the quality table, how well each model performs on each workload. Given that table, the decision is a multiple-choice knapsack problem and is routine to solve, so estimating it is the difficulty, and that estimation fails in two ways. Models are rarely compared on the same work, and the recorded score is usually a proxy rather than the outcome the company values. Causal and off-policy methods repair the first but condition on the second, while evaluator-validation methods estimate the second but stop short of the decision. Worse, buying more re-evaluation cannot settle the second: randomization governs which requests are scored, not how a score is produced, so the table stays uncertain however much evaluation is purchased. Yet the deployment decision may still be determined even when the table is not. We therefore ask whether one assi

---

### [11] Reachability-Based Capability Confinement for LLM Agents under Indirect Prompt Injection

**链接**: https://arxiv.org/abs/2608.30041
**作者**: Wujie Xiong, Rabimba Karanjai, Yang Lu, Weidong Shi, Lei Xu
**来源**: cs.CR cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model agents place outputs from external skills into their execution context, allowing attacker-controlled data to influence later privileged actions. Existing defenses mainly classify untrusted content or authorize proposed operations. They do not directly address how an agent's future authority should change once untrusted data enters its state. We present SkillGuard, a harness-level enforcement layer that treats this event as contamination and restricts future capabilities to disconnect the resulting state from deployer-defined forbidden states. Given sound skill summaries and policies, SkillGuard represents security-relevant transitions with a Skill Impact Graph, specifies admissible control over skill parameters via steerability signatures, and mediates invocations with an inline reference monitor. Following contamination, it computes weighted capability restrictions using binary, fractional, or fractional-flow strategies without auxiliary language-model inference. 

---

### [12] SemKV: Semantic Mixed-Precision KV Cache Quantization Guided by the Quality Cliff for Long-Context LLM Inference

**链接**: https://arxiv.org/abs/2608.28911
**作者**: Daeha Lee, Do-Hyung Kim, Jae-Hong Kim
**来源**: cs.LG cs.CL cs.IT math.IT
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The key-value (KV) cache is the dominant memory bottleneck of long-context large language model (LLM) inference, growing linearly with context length. We show that uniform KV quantization on a fractional-bit grid does not degrade gracefully: under a prespecified multi-seed statistical protocol, Llama-3.1-8B-Instruct with an affine quantizer is statistically indistinguishable from FP16 KV down to 2.322 code bits/value and collapses at 2.0 bits - a quality cliff in (2.0, 2.322] that reappears in generation-time quantization and multi-turn dialogue and transfers to Mistral-7B. The cliff reframes importance-aware mixed precision: above it, eight model-internal importance indicators are statistically interchangeable, so the benefit of mixing is grid interpolation, reaching average precisions uniform quantization cannot realize. SemKV preserves every token, ranks tokens by a model-internal score, and assigns two adjacent above-cliff precisions, achieving a measured 6.0x storage reduction wit

---

### [13] GPAgentBench-2K: Benchmarking Large Language Model Agents in Complex Clinical Action Space

**链接**: https://arxiv.org/abs/2608.30188
**作者**: Boqi Chen, Xudong Liu, Yunke Ao, Heejin Do, Jianing Qiu
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) show great potential as clinical agents, yet existing benchmarks reduce clinical workflows to static predictions or unconstrained Markov Decision Processes (MDPs) with coarse action sets. To address this, we introduce GPAgentBench-2K, the first Constrained MDP (CMDP) LLM-agent benchmark for primary-care clinical decision-making, constructed from expert-validated records of real-world GP encounters. Our environment models a full spectrum of six foundational clinical actions, imposes a topological workflow prior over the action space, and operationalizes safety-informed abstention as a first-class outcome. Evaluating 16 state-of-the-art LLMs reveals a significant performance degradation as the action space scales. Crucially, we uncover a clinical quality-safety gap: even frontier models with the highest diagnosis accuracy violate safety constraints in over half of high-risk cases. Finally, we establish a reference point using Constrained Group Relative Policy

---

### [14] Agent Zero Memory: Provenance-Aware Long-Term Memory for LLM Agents

**链接**: https://arxiv.org/abs/2608.29606
**作者**: Ming Wu, Pengyuan Zhu
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents need durable, faithful memory of everything a user or organization has said and stored, yet most memory systems commit to a single organizing structure (a fact store, a vector index, or a knowledge graph) and inherit its blind spots. We present Agent Zero Memory, a provenance-aware long-term memory system that distils a user's conversations, files, and connected sources into three parallel memory systems, each capturing a different facet of the same history: an episodic Memory Events timeline that makes when and what changed first-class, an associative entity-event knowledge graph that links people and projects across sessions, and a semantic, curated, citation-locked Hierarchical Documentary Memory (HDM) of durable facts. A retrieval turn runs an intent gate (so self-contained turns add no latency), a source router, and three concurrent agentic searches, one per system, each a tool-using loop over hybrid (embedding + lexical) search under agent-contro

---

### [15] Visible but Not Yet Curatable: Characterizing the Curatability of Compact and Derived Open LLM Artifacts

**链接**: https://arxiv.org/abs/2608.28819
**作者**: Yiyi Lu, Yilai Qian, and Yucheng Jin
**来源**: cs.HC cs.DL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Open Large Language Model (LLM) research increasingly produces compact and derived artifacts, such as adapters, quantized checkpoints, merged models, and distilled variants, that are distributed across papers, model hubs, model cards, code repositories, and release statements. Although these artifacts are publicly visible, digital libraries often lack sufficient evidence to identify, preserve, and cite them as coherent scholarly objects. We introduce a framework that conceptualizes curatability as a record-level property of distributed scholarly records and operationalizes it through four evidence dimensions: artifact identity, scholarly linkage, upstream evidence, and release assets. Guided by this framework, we conduct the first collection-scale characterization of open LLM curatability using a May 2026 snapshot of 191,375 public Hugging Face repositories and a core corpus of 2,214 scholarly papers. Our results reveal a pronounced visibility-to-curatability funnel. While 90.7% of pap

---

### [16] Relevance as a Vulnerability: How Web Retrieval Degrades Safety Alignment in LLM Agents

**链接**: https://arxiv.org/abs/2605.29224
**作者**: Aditya Nawal, Manit Baser, Mohan Gurusamy
**来源**: cs.CL cs.AI cs.CR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [17] When Do Larger Batches Help Scale LLM Reinforcement Learning?

**链接**: https://arxiv.org/abs/2608.29296
**作者**: Ziniu Li, Jinbo Wang, Guanhua Huang, Feiyuan Zhang, Pengbo Li, Alex Chen
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Larger batches reduce the variance of stochastic gradients per update and are therefore often expected to accelerate training. Yet whether this statistical benefit translates into lower wall-clock time-to-target remains unclear, because each update consumes more samples and may take longer to execute. We study this tradeoff in reinforcement learning for large language models. We separate its algorithmic and systems effects by comparing learning and execution along their natural axes. At the algorithmic level, we compare configurations at equal cumulative sample counts while retuning batch-dependent hyperparameters. Over a bounded range of batch sizes, this procedure yields an approximately batch-size-invariant family whose members follow similar sample-indexed learning trajectories. At the systems level, we exploit the computational asymmetry between rollout generation and training: autoregressive generation is often memory-bandwidth-bound at low concurrency, whereas training work scal

---

### [18] Integrated and Cross-Architecture Interpretation of LLM Reasoning

**链接**: https://arxiv.org/abs/2605.28006
**作者**: Leonardo Matthew Yauw, Wei-Bin Kou, Yujiu Yang
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [19] Conducting Stylistic Analysis of Paintings through an Art-History Agent

**链接**: https://arxiv.org/abs/2608.29644
**作者**: Marc S. Walton and Astrid Harth
**来源**: cs.CV cs.AI cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Attributing an artwork to an artist has traditionally relied on detailed visual observations and descriptions, known as stylistic analysis in art history. By contrast, current artificial intelligence (AI) models used in the field offer only unexplained probabilistic classifications. To bridge this methodological gap, we present an AI framework that automates stylistic analysis of paintings, providing a foundation for enhancing evidence collection, discovery, and verification. By training a vision transformer (ViT) on a large corpus of paintings with metadata, our system encodes this art history-specific data as embeddings. These representations are factorized via sparse dictionary learning into a shared set of features that recur across the training set. A large language model (LLM) then interprets each feature by retrieving associated artworks and their accompanying curator-written texts, and synthesizes them into descriptions that reflect their stylistic attributes. Finally, an auton

---

### [20] Cross-Relational Preference Learning for Better LLM Instruction Following

**链接**: https://arxiv.org/abs/2608.29352
**作者**: Runsheng Li, Kai Sun, Bin Shi, Bo Dong
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) still exhibit limited capability in following complex instructions. While existing approaches often rely on preference learning to enhance this ability, they typically overlook the relationships between the permissible response spaces of different instructions, which restricts a model to align with subtle and diverse constraint variations. To address this, we propose Cross-Relational Preference Learning (CRPL), a novel framework for constructing preference data that explicitly models inter-instruction relationships through two key techniques: Cross-Relationship Perturbation and Cross-Region Pair Sampling. This enables the generation of more diverse preference data that captures a wide spectrum of constraint variations. Additionally, we introduce an atomic constraint-based verification mechanism to rigorously assess response satisfaction, ensuring high-quality preference pair construction. Extensive experiments across multiple preference learning methods (e.

---

### [21] In LLM Reasoning, there is Irrationality on top of Value Misalignment

**链接**: https://arxiv.org/abs/2606.20624
**作者**: Kejiang Qian and Fengxiang He
**来源**: cs.AI cs.CL cs.LG stat.ML
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [22] BiasMix-Finance: Post-Generation KYC Guardrails for LLM Portfolio Advice

**链接**: https://arxiv.org/abs/2608.28646
**作者**: Gaurav Kukreja, Parul Kukreja, Mohammed Abraar, Raj Dandekar, Rajat Dandekar, Sreedath Panat
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) can generate plausible-sounding ETF portfolios while silently violating basic KYC-style constraints on risk, fees, and diversification. This is especially problematic in agentic multi-turn advisory systems, where each draft recommendation can become an action unless guarded by an auditable enforcement layer. We study a model-agnostic, asset-agnostic post-generation guardrail pipeline: (i) enforce a strict JSON allocation schema, (ii) validate allocations against numeric caps, and (iii) when violations occur, deterministically project the output to the nearest feasible portfolio via a convex quadratic program (QCQP). We introduce BiasMix-Finance (Mini), a compact stress-test benchmark for constrained decision-making under biased LLM generations, with a 16-ETF universe, three investor profiles, and eight bias prompts. Across three models and three inference modes (direct, critique, self-consistency), first-pass generations violate at least one cap in 47.6-85.

---

### [23] MACRO-LLM: LLM-Empowered Multi-Agent Collaborative Reasoning under Spatiotemporal Partial Observability

**链接**: https://arxiv.org/abs/2601.09295
**作者**: Handi Chen and Running Zhao and Xiuzhe Wu and Zhanfeng Xu and Edith C.H. Ngai
**来源**: cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [24] How You Ask Shapes What You Get: A Theory-Seeded Measurement of Articulation in Advice-Seeking LLM Conversations

**链接**: https://arxiv.org/abs/2608.29591
**作者**: Juneha Baek, Suhyeon Lee, Donghyuk Shin
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Users articulate the same advice-seeking request in different ways: some specify detailed constraints, others gesture at a vague need. Prior work treats this variation as noise to be averaged away; we instead treat it as a stable, measurable structure in the input distribution. We ask whether articulation (how people ask) forms latent dimensions separable from topic (what they ask about), and whether it is associated with how language models respond. We extract interpretable features from 16,447 advice-seeking prompts pooled from public chat corpora (WildChat, LMSYS, and ShareChat) and recover a small set of latent articulation factors that replicate across train/test splits and across corpora. Because this structure is largely separable from topic, the populations it defines cut across topics and stay invisible to topic- or task-based evaluation. The factors define a handful of recurring articulation styles, one of which stands out: a long-form but information-poor style, roughly one 

---

### [25] LLM Post-Training as Brownfield Maintenance: An Industrial Perspective on Dataware Engineering

**链接**: https://arxiv.org/abs/2608.31102
**作者**: Gopi Krishnan Rajbahadur, Amir M. Ebrahimi, Boyuan Chen, Ahmed E. Hassan
**来源**: cs.SE cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Industrial post-training is a brownfield regime. Teams inherit a deployed checkpoint and must land targeted improvements under fixed compute and mixture budgets without regressing the rest. The maintained artifact is increasingly dataware: behavior governed by a curated post-training mixture, updated via bounded mixture patches rather than clean-slate retraining. From an industrial code-generation improvement effort, we offer a maintainer's perspective on why this work is hard in practice, distilling three recurring challenges, zero-sum mixture design, yield as the binding metric, and end-to-end integration under uncertainty, and arguing that progress depends less on one-off recipes than on an engineering discipline for programming dataware. In our case study, interventions that raised the conversion of teacher distillation into usable training data increased accepted supervision by 2.84 times while using the same solution teacher and four solution attempts per candidate problem. In ou

---

### [26] Predicting the Unpredictable: LLM-powered Long-term Chaotic Time Series Forecasting under Short-term Observations

**链接**: https://arxiv.org/abs/2608.29579
**作者**: Yuhang Yao, Bohan Jiang
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Chaotic time series forecasting is a challenging task due to its sensitivity to initial conditions and long-term unpredictability. Traditional methods typically rely on sufficient temporal trajectories to learn long-term dynamics, which limits their applicability when only short-term observations are available. While recent Large Language Models (LLMs) have shown great potential for time series forecasting, their temporal representations are not explicitly tailored to the phase-space structure and nonlinear evolution of chaotic systems. To address these issues, we propose PAC-LLM, a phase-space-aware adaptive fusion framework for long-term chaotic time series forecasting powered by LLMs. PAC-LLM leverages learned phase-space features and textual information to fully enable LLM's time series forecasting capacity. In particular, we design an auxiliary feature module and a gated weighting mechanism for multivariate coupling information fusion and selection. Extensive experiments on repres

---

### [27] JFTA-Bench: Evaluate LLM's Ability of Tracking and Analyzing Malfunctions Using Fault Trees

**链接**: https://arxiv.org/abs/2603.22978
**作者**: Yuhui Wang, Zhixiong Yang, Ming Zhang, Shihan Dou, Zhiheng Xi, Enyu Zhou 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [28] On the Prospects of Dynamic LLM Conversations in Software Development

**链接**: https://arxiv.org/abs/2608.30756
**作者**: Annemarie Wittig and Alina Mailach and Janet Siegmund and Norbert Siegmund
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) have become an essential tool for assisting developers, yet we still lack knowledge on ways to effectively support their interactions during development activities. That is, the quality of interactions with a chat-based LLM still strongly depends on how developers phrase prompts and which information they include. Our goal is to evaluate whether interventions into these interactions with LLMs have an effect on software developers---be it harmful or beneficial. To this end, we conducted a four-month longitudinal study with third-semester computer science students working on a full-stack Web development project using chat-based LLMs under three conditions: (1) a \emph{context}-aware group received intent-based conversation augmentation, (2) a \emph{proactive} group received follow-up suggestions and tailored advice, and (3) a \emph{control} group without intervention. Our augmentations are minimal: (i) to reduce confounding factors and (ii) to isolate treatme

---

### [29] MAPLE: Metadata Conditioned LLM Pretraining for Locale-Aware Question Answering

**链接**: https://arxiv.org/abs/2601.15236
**作者**: Anjishnu Mukherjee, Ziwei Zhu, Antonios Anastasopoulos
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [30] Same Scrutiny, More Time: Eye Tracking Insights into Reviewing LLM-Labelled Code

**链接**: https://arxiv.org/abs/2606.26505
**作者**: Ranim Khojah, Francisco Gomes de Oliveira Neto, Mazen Mohamad, Julian Frattini, Philipp Leitner
**来源**: cs.SE cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [31] Paper Pilot: A Human-in-the-Loop Expert System for Evidence-Traceable Scientific Manuscript Generation in Applied Sciences

**链接**: https://arxiv.org/abs/2608.28596
**作者**: Nidhi Jha, Siddharth Chaudhary, Ajinkya Kulkarni
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents are increasingly embedded in scientific workflows for literature analysis, drafting, and review. Existing systems advance autonomous discovery and manuscript generation, but do not resolve the governance problem that arises when ideas, methods, results, and claims propagate through AI-assisted workflows without mandatory human approval or artifact-level traceability. This paper proposes Paper Pilot, a human-in-the-loop expert system for evidence-traceable scientific manuscript generation in applied sciences. It adapts the Collaborative Agent Reasoning Engineering (CARE) methodology to manuscript development through manuscript-owner approval gates, explicit no-pass criteria, claim classification, audit logging, advisory LLM review, and evidence-locked revision control. The framework defines eight approval gates across the idea-to-claim pipeline and distinguishes literature-grounded from artifact-grounded claims, requiring reported numbers and interpreta

---

### [32] Balancing Privacy, Utility, and Safety in LLM Alignment through Preference Optimization

**链接**: https://arxiv.org/abs/2608.30141
**作者**: Dishu Yang, Jingjing Liu, Jize Li
**来源**: cs.CR cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Preference optimization is widely used to align large language models with human preferences, but preference-data composition may also influence privacy-relevant memorization. We examine whether adding synthetic privacy-preference pairs to Direct Preference Optimization (DPO) is associated with lower canary-based memorization signals without modifying the objective or introducing a formal privacy mechanism. We propose Privacy-Pressure Preference Mixing (P3M), a data-composition protocol that varies the amount of privacy-preference data while keeping helpfulness and harmlessness preference data fixed. We evaluate a non-privacy Baseline and privacy-mixing ratios of 0.5, 1.0, and 2.0 using Gemma 3 270M-IT across five random seeds and validate the same four conditions using 4-bit-quantized Gemma 2 2B-IT across three seeds. Overall, under the tested conditions, privacy-preference mixing is associated with lower mean canary suffix log-likelihood proxy values across both model settings and lo

---

### [33] Revising Context, Shifting Simulated Stance: Auditing LLM-Based Stance Simulation in Online Discussions

**链接**: https://arxiv.org/abs/2606.06443
**作者**: Xinnong Zhang, Wanting Shan, Hanjia Lyu, Zhongyu Wei, Jiebo Luo
**来源**: cs.CL cs.MM cs.SI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [34] The Differential Reasoning Router: Operationalizing Cost-Aware LLM Annotation in E-commerce

**链接**: https://arxiv.org/abs/2608.30224
**作者**: Cheng Lyu, Jingyue Zhang, Vinny DeGenova, Mengwei Li, Yuanli Pei
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) are increasingly used to annotate structured product data in e-commerce, but early deployment often begins as a cold-start problem: only limited pre-launch labels are available, the value of expensive reasoning is unknown, and human review is needed before the system can be trusted at scale. This challenge is especially common in rule-based annotation workflows, where each item must satisfy multiple business rules and both model errors and ambiguous rule boundaries affect final decisions. We introduce the Differential Reasoning Router (DRR), a cost-aware framework for cold-start LLM annotation that jointly optimizes model selection and human escalation. Rather than treating a reasoning model as a default fallback, DRR estimates separate success probabilities for a direct model and a reasoning model at both the sample and business-rule levels, enabling adaptive routing: easy cases are handled directly, reasoning is reserved for cases where it is expected to 

---

### [35] An Embarrassingly Simple Detector for Model Extraction Attacks in Large Language Model API Traffic

**链接**: https://arxiv.org/abs/2606.05725
**作者**: Shuze Liu, Qianwen Guo, Yushun Dong
**来源**: cs.CR cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [36] Beyond Helpfulness: A Teaching-over-Solving Diagnostic for Measuring Educational Impact in LLM Tutors

**链接**: https://arxiv.org/abs/2606.16206
**作者**: Junyi Yao, Zihao Zheng, Baichuan Li
**来源**: cs.AI cs.CL cs.CY cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [37] DynamicMCPBench: A Trace-Grounded, Effect-Scored Benchmark for LLM Agents over Live MCP Servers

**链接**: https://arxiv.org/abs/2607.20531
**作者**: Jerzy Kami\'nski, Ilya Galyukshev, Artem Kuznetsov, Sergey Chuprin, Kirill Redko, Aidar Shumbalov 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [38] ERR+: Sequential Entropy Resolution for Efficient and Decisive LLM Reasoning

**链接**: https://arxiv.org/abs/2608.28771
**作者**: Xin Jiang, Minhao Wang, Wen Wu, Zhentao Xie, Shangheng Du, Jinxin Shi 等 (7 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large reasoning models achieve strong performance on complex tasks by generating extended chain-of-thought (CoT) traces via reinforcement learning with verifiable rewards (RLVR). While current RLVR methods have achieved strong results with correctness-based reward signals, they provide limited guidance on the quality of the reasoning process itself, leaving the internal reasoning structure largely unoptimized. Through empirical analysis across multiple model families, we identify a consistent pattern: correct reasoning trac es exhibit more frequent and larger token-level entropy drops within the thinking phase than incorrect ones. We propose ERR+, a two-phase RLVR framework grounded in this observation. The first phase trains with the Entropy Relief Reward (ERR), a bonus proportional to cumulative token-level entropy drops in the thinking phase, log-normalized by response length. Unlike prior methods that suppress entropy, ERR rewards the resolution of uncertainty while leaving explora

---

### [39] AIA$^{2}$: Attribute-Agnostic Imbalance Augmentation for Subgroup Robustness

**链接**: https://arxiv.org/abs/2608.30297
**作者**: Hanshu Rao, Guangzeng Han, Xiaolei Huang
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Attributes describing data content and context can induce diverse imbalance patterns that go beyond label imbalance alone. However, existing studies primarily address label imbalance while overlooking data attributes, such as topics and demographics, which can induce meaningful subgroup structure while causing model degradation on underrepresented subgroups. We propose Attribute-Agnostic Imbalance Augmentation (AIA$^{2}$), a framework for improving model robustness under varying subgroup imbalances without explicit subgroup annotations. AIA$^{2}$ automatically discovers varying imbalances via latent semantic distributions, obtains slices with both learning difficulty and subgroup imbalance deficits, and deploys a large language model (LLM) for subgroup-aware imbalance augmentation. We have evaluated AIA$^{2}$ on 5 popular corpora with rich domains and their attribute values, covering social issues and diverse topics. Results show improved performance on the lowest-performing subgroups 

---

### [40] Dynamic Model Routing and Cascading for Efficient LLM Inference: A Survey

**链接**: https://arxiv.org/abs/2603.04445
**作者**: Yasmin Moslem, John D. Kelleher
**来源**: cs.NI cs.CL cs.PF
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [41] Decomposing Wrong-Consensus Agreement in LLM Self-Consistency

**链接**: https://arxiv.org/abs/2608.18795
**作者**: Lizhuo Zhang, Mengmeng Tang, Chenfeng Long, Xiaoyong Tang, Xiang Luo
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [42] ReVA: A Region-Aware Visual Assistant for Visually Grounded Question Answering

**链接**: https://arxiv.org/abs/2608.28707
**作者**: Anoop Senthil
**来源**: cs.CL cs.CV
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal Large Language Models (MLLMs) have achieved remarkable progress in Visual Question Answering (VQA), yet they continue to struggle with questions requiring precise spatial reasoning and fine-grained visual understanding. These limitations often manifest as object, attribute, and spatial hallucinations, where models generate confident but visually unsupported responses due to insufficient region-level and fine-grained visual grounding. To address this challenge, we propose ReVA, a region-aware VQA model that employs a frozen CLIP ViT-L/14 Vision Transformer (ViT) and a Qwen2.5-7B-Instruct large language model (LLM) connected through a dual bridge that aligns both whole-image and region-level representations with the LLM's embedding space. The image bridge maps final transformer block features into image tokens. The region bridge maps cropped features from enriched intermediate features across ViT blocks so early texture and later object cues are more evident, into K region tok

---

### [43] FAMPWQ: Fisher Information-based Adaptive Mixed Precision Weight Quantization for Effective LLM Inference

**链接**: https://arxiv.org/abs/2608.24945
**作者**: Gongwei Lee, Ji Liu, Juncheng Jia, Ji Wu
**来源**: cs.LG cs.AI cs.DC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [44] Beyond Correctness: Validity-Oriented Evaluation of Biomedical LLM Judges

**链接**: https://arxiv.org/abs/2608.29127
**作者**: Rodrigo de Oliveira, Federico Pittino, James Gwinnutt, Jay Nanavati
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We propose a scalable, validity-oriented pipeline for evaluating biomedical LLM judges when high-quality human judgments are scarce. First, we augment existing human-labelled biomedical benchmarks with deterministic, metric-grounded mutations that produce auditable preference pairs. Second, we evaluate judges beyond aggregate correctness using three deployment-relevant dimensions: correctness against metric-derived gold labels, robustness under repeated stochastic sampling, and compliance with the requested output format. We use this pipeline to assess Llama-3.1-8B-Instruct under four regimes: (1) base, using the instruct model as is; (2) SFT, distillation-based supervised fine-tuning only; (3) RL, GRPO-based reinforcement learning only; and (4) SFT$\rightarrow$RL, SFT followed by RL. The base and single-stage regimes struggle on structured medical discrimination such as PICO extraction and clinical calculations, whereas SFT$\rightarrow$RL performs best across correctness, compliance, 

---

### [45] HALO: A Physics-Aware LLM Agent Framework for Nanophotonic Design

**链接**: https://arxiv.org/abs/2608.28877
**作者**: Yubo Zhang, Jinlin Xiang, Zijun Zhao, Yang Zhao, Eli Shlizerman, Arka Majumdar
**来源**: physics.optics cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Language models have recently been applied to nanophotonic design, but it remains unclear whether they can reliably translate optical objectives into simulation-ready designs, execute electromagnetic analysis, and revise decisions from numerical feedback. We introduce HALO, a physics-aware framework that couples language-model planners with typed design specifications, electromagnetic simulation, diagnostic evaluation, and optional reuse of prior failure trajectories in an iterative design loop. We further introduce HALO-Bench, a 52-task benchmark spanning lab-derived, paper-derived, and open-ended nanophotonic design tasks under a shared evaluation protocol. We compare three planner configurations: a Fixed Structured Workflow, an Autonomous Structured Agent using the same simulation interface, and an Autonomous Coding Agent that directly writes and executes simulation code. The Fixed Structured Workflow is the most token-efficient and exhibits no observed code- or path-level failures,

---

### [46] Can Released LLM Vocabularies Support Token-Level Estimation of Hidden Corpora?

**链接**: https://arxiv.org/abs/2608.10690
**作者**: Qingjie Zhang, Xingzhang Ren, Zixuan Chen, Jinfeng Li, YueFeng Chen, Yitong Yang 等 (9 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [47] Ideation Arena: Evaluating LLM Generated Research Ideas with Battle-style Human Expert Assessment

**链接**: https://arxiv.org/abs/2608.29696
**作者**: Zhiyu Chen, Keyu Zhao, Jigao Fu, Dong Liang, Yanbiao Wu, Jiaoyang Li 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Evaluating research ideas generated by LLMs is difficult because their scientific value cannot be fully determined by objective criteria, and no single reference answer specifies what counts as a good idea. To address this challenge, we introduce Ideation Arena, a battle style platform that evaluates research ideas through pairwise human assessment. Ideation Arena evaluates ideas generated by 14 frontier LLMs and 5 research agent architectures built on 2 base models. To ensure a common starting point, Ideation Arena builds shared literature contexts from papers familiar to the participating researchers and provides the same contexts to all LLMs and agents. We collect over 6,000 double blind pairwise comparisons from 105 active computer science researchers and construct an Elo rating leaderboard of proposal-stage expert preferences in computer science under a shared closed-context protocol. We validate the rankings through interrater agreement and robustness analyses, showing that the l

---

### [48] Agent2UCB: Agentic System for Generative Engine Optimization

**链接**: https://arxiv.org/abs/2608.29063
**作者**: Sheldon Yu, Rui Wang, Tong Yu, Sungchul Kim, Doga Dogan, Junda Wu 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model driven search engines such as Google AI Overviews and Perplexity have created new opportunities for Generative Engine Optimization (GEO) the practice of refining content to increase its likelihood of being cited or summarized by generative systems. We demonstrate Agent2UCB, an agentic GEO system that autonomously improves content visibility through customized, feedback-driven optimization. For each content item, the system evaluates nine GEO strategies, identifies the most effective method, and accelerates selection using a bandit-based Agent2UCB policy that integrates LLM priors with online reward signals. To monitor side effects, the system also provides a lightweight, text-only SEO readiness evaluation covering readability, topical coverage, and EEAT-style credibility. Experiments on GEO-Bench show consistent visibility gains while preserving SEO quality. The demo allows users to choose the websites of interest, observe the optimization workflow, and compare GEO

---

### [49] Real-Time Deadlines Reveal Fragile Temporal Adaptation in LLM Strategic Dialogues

**链接**: https://arxiv.org/abs/2601.13206
**作者**: Neil K. R. Sehgal, Sharath Chandra Guntuku, Lyle Ungar
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [50] Budget-Aware Compression Pipeline for Single-GPU LLM Inference: Methods, Trade-offs, and Coupling Effects

**链接**: https://arxiv.org/abs/2608.30076
**作者**: Hongyu Yu, Yifei Shen
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Single-GPU deployment of 70B-parameter language models on an NVIDIA GPU is constrained by device memory, long-context throughput, and engineering integration cost. We cast single-GPU inference as a budget-aware design problem over these three axes and study how pruning, quantization, and KV-cache compression interact under realistic execution. Controlled ablations show that layer-wise pruning makes weight quantization more robust. KV-cache sparsification complements INT8 KV quantization by reducing memory without hurting decoding speed, while static vector quantizers often conflict with dynamic caching. Guided by these coupling results and explicit budget tracking, we assembled a practical pipeline and compressed a 70B model to about 33 GB, sustained about 57 tokens/s on 10k token prompts on a single A40, and kept absolute accuracy within 5% on common and reasoning benchmarks. We contribute design rules and a reproducible evaluation protocol that jointly report quality, memory, and end

---

### [51] ATLAS: Dual-Horizon Diagnostic Evaluation for Industrial Tool-Use Agents

**链接**: https://arxiv.org/abs/2608.30685
**作者**: Wei Chen, Peilun Zhou, Zhaoyu Hu, Jiajun Chai, Zhongni Hou, Yufei Zhang 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents are increasingly deployed in user-facing services that require iterative tool use under dynamic business conditions. Reliable evaluation is essential for sustained improvement: it must reveal capability deficiencies, inform priorities, and assess interventions. Yet industrial agent service unfolds both through the iterative trajectory of a current request and through continued user interaction. Final-outcome assessment can therefore obscure where deficiencies arise and whether later service remains aligned with context from earlier exchanges. We propose ATLAS, a dual-horizon diagnostic evaluation framework for industrial tool-use agents. At the request horizon, trajectory-wise diagnostic signals relate deficiencies to execution locations and capability concerns. At the interaction horizon, user-wise signals assess whether service remains responsive across continued interaction. Together, these views provide structured diagnostic evidence for analyzing 

---

### [52] PowerSlider: Exploiting Phase Asymmetry for LLM Serving under Demand Response

**链接**: https://arxiv.org/abs/2608.21719
**作者**: Yueying Li, Jiayang Chen, Yuanfan Chen, Leo Han, Haoran Qiu, Esha Choukse 等 (8 人)
**来源**: cs.DC cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> AI inference clusters are increasingly constrained by instantaneous power, not just energy: grid operators condition new capacity on demand response, imposing time-varying power caps. Existing LLM serving systems optimize a static energy objective or shed fixed priority tiers under load; either way, goodput collapses when the power envelope moves. An LLM pipeline is not a uniform load: compute-bound prefill loses throughput almost linearly with GPU frequency, memory-bound answer decode sustains it down to $0.57\times$ nominal, and reasoning's thinking phase couples KV-cache capacity to scheduling -- so a cap should be steered to where each watt costs the least performance. PowerSlider does so with a new Flex SLO contract that turns bounded user slack into an optimization constraint, prefill--think--answer disaggregation exposing per-stage frequency and KV control, and a Karush--Kuhn--Tucker (KKT) online solver re-solving within 7.7 ms of every cap change, backed by a consolidated fail-

---

### [53] SyRuP: Enhancing System-Prompt Following via Reward-Guided Prediction in LLM Decoding

**链接**: https://arxiv.org/abs/2607.23991
**作者**: Seoyeon Kim, Minjae Kang, Jaehyung Kim
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [54] Measurement Validity in LLM Cultural Alignment

**链接**: https://arxiv.org/abs/2608.29266
**作者**: An Duy Nguyen, Muhammad Aurangzeb Ahmad
**来源**: physics.soc-ph cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Researchers increasingly treat LLM survey responses as a proxy for human cultural values. This includes projecting model outputs onto instruments like the Inglehart-Welzel Cultural Map and drawing conclusions about which cultures a model resembles. While a model's answer to a value-laden questions may be interpreted as a cultural signal, it also carries sampling noise and, can be quite sensitive to question framing. In this paper, we separate survey responses, sampling noise and question framing for multiple LLMs. We decompose response variance from these models into variation across random seeds, prompt rewordings. We employ noise-to-signal ratio (NSR) to test whether a model's apparent cultural position is distinguishable from noise. When applied across a dozen models from four geographic origins, calibrated against 88 Integrated Values Survey countries, the answer is often no. NSR exceeds 1.0 on 49 of 117 valid model-question pairs (42%), reaching 5.56 in the worst case. Two models 

---

### [55] Reduced Matrix Multiplication: Input-Adaptive Matrix-Product Reduction for LLM Inference

**链接**: https://arxiv.org/abs/2608.13426
**作者**: Zixuan Lan, Yanhong Li, Jiawei Zhou
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [56] Personas Differ from Native-Language Generation: Language Pathways Shape LLM Interpersonal Advice

**链接**: https://arxiv.org/abs/2608.30873
**作者**: Jinhee Won, Xinlan Emily Hu
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLMs are increasingly used for interpersonal advice and as tools for studying social behavior across languages and cultures. A common shortcut for eliciting language- or culture-related variation is to ask a model to answer as a native speaker. We test whether this native-speaker persona reproduces the outputs obtained when models instead generate advice in the target language and translate the response back into English. Using 600 interpersonal advice questions across 13 languages and eight LLMs, we compare native-language generation followed by translation (NL) with native-speaker persona prompting (NP), measuring linguistic style, behavioral scaffolding, and forced-choice action recommendations. We find that NP and NL are not interchangeable. Compared to NL, NP often increases lexical social cues, including affiliation and positive tone, while reducing qualities such as concreteness and social attunement; NP also provides less actionable scaffolding in open-ended advice. In forced-c

---

### [57] Automated Testing of LLM-Based Post Hoc Explainers Using Model Checking as an Oracle

**链接**: https://arxiv.org/abs/2608.30581
**作者**: Dennis Gross, Helge Spieker
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are used as post hoc explainers of sequential decision-making policies, producing natural-language explanations of why an action was chosen. However, LLMs often generate plausible but incorrect statements, and no existing approach systematically tests whether such explanations are faithful to the underlying environment. Two classic software testing challenges stand in the way: there is no oracle for the correctness of an explanation, and the test inputs, natural language queries about a policy's behavior, lack the structure needed for systematic test case generation. We address both. Probabilistic model checking provides the test oracle, computing exact reference results against which LLM answers are graded automatically. A taxonomy of post hoc query categories structures the input space around the environment-level facts from which policy explanations are composed; test cases generated from it are prioritized by question-specific diagnostic difficulty scor

---

### [58] Chat-Edit-3D++: Interactive 3D and 4D Scene Editing via Large Language Models

**链接**: https://arxiv.org/abs/2608.29137
**作者**: Shuangkang Fang, Yufeng Wang, Yi-Hsuan Tsai, Wenrui Ding, Yi Yang, Shuchang Zhou 等 (7 人)
**来源**: cs.CV
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent work on image content manipulation based on vision-language pre-training models has been effectively extended to text-driven 3D scene editing. However, existing schemes for 3D scene editing still have certain shortcomings, hindering their further development as interactive design tools. Such schemes typically adhere to fixed input patterns, limiting flexibility in text input. Furthermore, their editing capabilities are constrained by a single or a few 2D visual models and require intricate pipeline design to integrate these models into 3D reconstruction processes. To address the aforementioned issues, we propose the Hash-Atlas network, which reformulates 3D scene editing as operations on 2D atlas images, thereby achieving a workflow decoupling of the 2D editing and 3D reconstruction processes. Building on this foundation, we introduce a dialogue-based 3D scene editing approach, termed CE3D++, which is centered on a large language model (LLM) that allows arbitrary textual input f

---

### [59] PortBench: A Correlation-Aware, Full-Pipeline Benchmark for LLM-Driven Portfolio Management

**链接**: https://arxiv.org/abs/2605.27887
**作者**: Yuxuan Zhao, Sijia Chen, Ningxin Su
**来源**: cs.AI q-fin.PM
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [60] You Shouldn't Have Asked: A Pragmatics-Inspired Taxonomy for Evaluating LLM Refusals

**链接**: https://arxiv.org/abs/2608.30856
**作者**: Ruoxuan Li, Pinqiao Wang, Sheng Li, Cameron Robert Jones
**来源**: cs.CL cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Refusals are often treated as face-threatening acts in pragmatics because they can challenge the requester's socially claimed self-image. Large language models (LLMs) are increasingly trained to refuse unsafe and inappropriate requests, and these refusals may harm users when models fail to manage this interactional cost properly. While existing work has mainly approached LLM non-compliance as a safety-alignment outcome, it does not provide a way to evaluate whether LLMs refuse appropriately across different harmful contexts. To study this question, we propose (to our knowledge) the first taxonomy of LLM refusals that is grounded in pragmatic theory. Applying this taxonomy to responses from 16 modern LLMs across 14 harm categories, we find that although models differ in how they refuse, their refusals are overall explicit and strongly morally evaluative, with interactional repair occurring mainly through offering or providing safer alternatives instead of interpersonal facework. This pa

---

### [61] E-Commerce Bench: Evaluating LLM Agents on Long-Horizon Autonomous Business Operation

**链接**: https://arxiv.org/abs/2608.30730
**作者**: Wei Fan, Xinjie Shen, Xudong Guo, Jianhong Tu, Yang Su, Yinger Zhang 等 (10 人)
**来源**: cs.LG cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-horizon agentic tasks go beyond chaining short tasks over more interaction turns. Their evolving dynamic environments and long-range dependencies require Large Language Models (LLMs) to continually explore, learn from experience, and adapt their policies over thousands of steps. We introduce E-Commerce Bench, the first open-source benchmark that integrates multi-round counterpart negotiation and dynamic events into a year-long business operation. Over a 365-day year, an LLM agent concurrently runs multiple online stores, researching the market, negotiating with suppliers to source inventory, optimizing sales strategies, fulfilling orders, handling returns, and managing cash flow to maximize its end-of-year total assets. To construct a realistic merchant-side operating environment, the product and supplier data are derived from a real e-commerce platform, while a year-long calendar of promotions, natural disasters, and supply-chain shocks continually reshapes demand. For reproducib

---

### [62] Towards Natural Personalization: Evaluating Long-Horizon Preference Following in Personalized User-LLM Interactions

**链接**: https://arxiv.org/abs/2603.04191
**作者**: Qianyun Guo, Yibo Li, Yue Liu, Bryan Hooi
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [63] When LLM Meets Tree Search: A Systematic View of Inference as Search in Large Language Models

**链接**: https://arxiv.org/abs/2608.30395
**作者**: Jiaqi Wei, Xiang Zhang, Yuejin Yang, Wenxuan Huang, Juntai Cao, Sheng Xu 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As pretraining scaling laws approach saturation, Test-Time Scaling (TTS) has emerged as an important direction for improving reasoning by allocating inference-time compute to a fixed model prior. Viewed at a high level, TTS reframes inference as search over a space of partial reasoning states. While Chain-of-Thought (CoT) exposes intermediate steps, common instantiations rely on single-trajectory decoding, limiting recovery from early errors and exploration. This survey systematizes recent progress in tree-search-based reasoning, viewing inference as instance-specific optimization rather than decoding. We trace the evolution from uninformed search to Monte Carlo Tree Search (MCTS), highlighting how sampling-based control supports principled exploration-exploitation trade-offs. To unify a fragmented literature, we introduce a Unified Design Space spanning search topology, evaluation signals, and control dynamics, and advocate a standardized compute-reporting abstraction to make compute-

---

### [64] Development of an Autonomous AI Coding Agent using Monte Carlo Tree Search (MCTS) and Gemini LLM Frameworks

**链接**: https://arxiv.org/abs/2608.29096
**作者**: Pravin Game, Vipin Ramakrishnan, Prathamesh Wagh
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The ongoing changes in software engineering requirements have created a substantial need for automated tools which can create secure source code from natural language input. The performance of traditional Large Language Models (LLMs) becomes limited by their "one-shot" capability which results in logical hallucinations together with reduced algorithmic performance during complicated operations. The research presents an autonomous AI Coding Agent which establishes a connection between LLM-generated content and production-ready software through its organized methodology for decision making. Our framework uses the Gemini 2.5 Flash API for essential reasoning capabilities while employing a tailored Monte Carlo Tree Search (MCTS) method to solve code generation challenges as a search operation. The agent uses a "Self-Critic" evaluator system to test different implementation methods which it ranks according to their accuracy and difficulty level before it improves its operational framework t

---

### [65] When Does a Classifier Help an LLM? Classifier-Guided Prompting and Hybrid Classifier-LLM Models for Credit-Default Prediction

**链接**: https://arxiv.org/abs/2608.30086
**作者**: Rishi Datta, Lavanya Prahallad
**来源**: cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Credit-default prediction is an important task in financial decision making. Traditional methods use fitted classifiers such as logistic regression and random forests on tabular features. Large language models (LLMs) have recently been applied to this task through prompting. In this work we study how a fitted classifier and an LLM can be combined for credit-default prediction. We distinguish telling the LLM to imitate a classifier from using the classifier to build the prompt. We hypothesize that a fitted classifier can supply the ranking ability that an LLM prompt lacks. We experiment on the Default of Credit Card Clients dataset, and report recall, F1, and the area under the ROC and precision-recall curves, with bootstrap confidence intervals. We observe that a few-shot LLM has the highest recall (0.47) and F1 (0.50) of any single model but ranks worse than a random forest (AUC-ROC 0.72 against 0.79). Instructing the LLM to imitate a classifier gives no significant change. Pruning th

---

### [66] GreenBench: Benchmarking Energy Efficiency and Carbon Footprint of Open-Source LLM Inference on Apple Silicon

**链接**: https://arxiv.org/abs/2608.28667
**作者**: Rajeswari Kannan, Raj Firke, Shreya Bengle, Srushti Deshmukh
**来源**: cs.CL cs.AI cs.PF
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The rapid proliferation of Large Language Models (LLMs) has raised concerns about their environmental impact during inference. While Green AI research has focused on datacenter GPUs and embedded platforms, the energy profile of LLM inference on Apple Silicon, with its unified memory architecture, remains unstudied. This paper presents GreenBench, a benchmarking framework that evaluates the energy efficiency, throughput, and carbon footprint of five open-source LLMs (3-9B parameters) across three NLP tasks on an Apple M4 Pro with 48 GB unified memory. Using macOS powermetrics for direct power measurement and Ollama's nanosecond-precision timing, we find that the M4 Pro draws only 0.47 W of CPU+GPU package power during sustained inference, with total system power of 8-12 W, achieving 30-40x better energy efficiency per token than datacenter GPUs in single-user deployment. Smaller models (3-3.8B) deliver 2.6-4.2x higher throughput and up to 62% less energy per token than larger models (7-

---

### [67] The Race between Agentic AI Capabilities and Data Quality Control in Online Surveys

**链接**: https://arxiv.org/abs/2608.28597
**作者**: Sourav Panda, Hillmer Chona, Rupak Kumar Das, Shreyash Kale, Shikha Soneji, Jonathan Dodge
**来源**: cs.AI cs.CY
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Online surveys are a foundational data collection instrument in a variety of fields, with attention checks serving as critical guardians of response quality. However, the rapid emergence of agentic AI (goal directed systems powered by a large language model (LLM) brain and/or a multimodal processing unit with tool-augmented capabilities) raises new questions about the robustness of these safeguards. We investigate how well agentic AI architectures can complete web-based surveys and pass standard attention checks. We evaluate a single-agent architecture capable of multimodal input processing and tool-based web interaction on a controlled survey sandbox. We analyze the problem from two perspectives. From an attack perspective, we demonstrate how structural vulnerabilities such as exposed DOM metadata and predictable option encoding allow agents to resolve attention checks through structured parsing only. From a defense perspective, we implement a mitigation strategy of DOM metadata obfus

---

### [68] LLP: LLM-Based Product Pricing in E-commerce

**链接**: https://arxiv.org/abs/2510.09347
**作者**: Hairu Wang, Sheng You, Qiheng Zhang, Xike Xie, Shuguang Han, Yuchen Wu 等 (8 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [69] Pak3H: Evaluating the Cost of Cultural Mismatch in LLM Alignment with a Human-Contextualized Urdu Benchmark

**链接**: https://arxiv.org/abs/2608.30065
**作者**: Abdullah Hashmat, Usman Naseem, Agha Ali Raza
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) demonstrate strong Helpfulness, Harmlessness, and Honesty (3H) alignment in English-centric settings, but these gains transfer poorly to low-resource languages due to cultural mismatches. Existing multilingual 3H benchmarks rely predominantly on automated translation or LLM based synthesis, propagating source-language biases while sacrificing local relevance. To address this gap, we introduce Pak3H1, the first human-validated, culturally contextualized Urdu benchmark suite for 3H alignment, comprising PakAlpaca (helpfulness), PakBeaverTails (harmlessness), and PakTruthfulQA (honesty). Our multi-stage pipeline integrates manual cultural adaptation and dictionary-guided post editing to prioritize native speaker judgment, ensuring both semantic fidelity and contextual authenticity. Zero-shot evaluations across multiple open and proprietary LLM architectures reveal systematic cross-lingual alignment gaps: helpfulness win rates decline under localized contexts, 

---

### [70] Evaluating LLM-based AI agents integrated with materials synthesis tools: the case of atomic layer deposition

**链接**: https://arxiv.org/abs/2608.29309
**作者**: Angel Yanguas-Gil
**来源**: cond-mat.mtrl-sci cs.AI physics.app-ph
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> This work provides an overview of the different strategies that can be used to evaluate the performance of AI models and agents based on large language models (LLMs) for materials synthesis. After providing a brief overview of the key technologies behind the current generation of AI agents based on LLMs, we summarize the different approaches to evaluating these models in the context of materials science and in particular on materials synthesis, with a specific emphasis on scenarios in which the models are directly integrated with experimental tools. We discuss evaluation strategies spanning knowledge and reasoning benchmarks, tool-use benchmarks, and closed loop benchmarks involving the interaction with experimental systems or realistic virtual tools. We use atomic layer deposition (ALD) as a case study, emphasizing how existing approaches in the literature both build from general approaches used beyond materials science and can be generalized to other materials synthesis techniques. F

---

### [71] Detecting AI Impostors: How Do Middle Schoolers Identify LLM Agents in a Live Collaborative Setting?

**链接**: https://arxiv.org/abs/2608.30948
**作者**: Dan Schumacher, Pragathi Durga Rajarajan, Haven Kotara, Roman Rendon, Kosi Atupulazi, Deepti Tagare 等 (9 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLMs can imitate how people write, which raises concerns about impersonation, trust, and detection in social settings. These concerns are especially important for adolescents, who use generative AI frequently but may struggle to recognize it. We introduce \textit{DoppelBot}, a cooperative social deduction game designed to study how young people detect and respond to AI impersonation. Through studies with middle schoolers, we investigate whether a DoppelBot prompts reflection on privacy and impersonation, how repeated exposure affects AI-detection accuracy as agents become more personalized, and which strategies students use to identify AI doppelg\"angers. We find that students' detection accuracy improves over time, driven by a shift from relying on linguistic cues to leveraging shared social and contextual signals. Students also demonstrated an understanding of AI limitations such as embodiment and reflected on broader issues such as data privacy. To support future research, we releas

---

### [72] IndicDetect: Evaluating Cross-Lingual LLM-Generated Text Detection for Hindi, Telugu, and Tamil

**链接**: https://arxiv.org/abs/2608.29919
**作者**: Bhaskar Ganesh Devalla, Junchao Wu, Nilesh Dokuparthi, Greeshma Yaluru, Tatiana Muniz Rodriguez, Lidia S. Chao 等 (7 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The rapid proliferation of LLMs has further heightened the need to develop dependable AI-generated text detection, especially beyond English. Nevertheless, current benchmarks pay little attention to Indic languages and test detectors in idealized settings that do not represent the real world. We present a generalized benchmark for AI-generated text detection in Hindi, Telugu, and Tamil, which we call IndicDetect, designed to assess the robustness of detectors under realistic distribution shifts. IndicDetect comprises highly curated human-written texts matched with LLM-generated counterparts across various domains and generators, and systematically evaluates detectors in the presence of domain shift, generator shift, and adversarial perturbation. Using a single and repeatable evaluation scheme, we evaluate a wide range of statistical and neural detectors. We find substantial robustness failures: supervised neural detectors perform well in-distribution, while training-free methods degrad

---

### [73] LLM Judges as Raters: A Pre-Registered Audit of Severity, Halo, Reliability, and Version Instability in LLM Essay Scoring on Public Corpora

**链接**: https://arxiv.org/abs/2608.29517
**作者**: Veerendra Kumar Sunkavalli
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly used as essay graders in learning analytics, evaluated almost exclusively with agreement statistics. Educational measurement warns that raters also differ in severity, show halo, and drift as instruments. We treat LLM judges as raters and run a pre-registered rater-effects battery (many-facet Rasch severity, residual halo, generalizability/decision studies, cross-version shifts, differential functioning) on public corpora in two languages (ENEM/Essay-BR; ASAP): 2,377 essays, 12 judges, 4 providers, 5 version contrasts, replicated cells, released as a score tensor. Judge severity spans 219 points on ENEM's 0-1000 scale; on ASAP the panel spread is 15-33% of the score range against a between-trained-human gap near 1%. Judge-human correlations sit in an undiscriminating .47-.56 band. All five version contrasts shift severity beyond a family-wise permutation null (up to 133 points), and one judge was deprecated mid-study, caught by identity can

---

### [74] ForesightSafety-SAGE:A Fully Automated Scenario Generation and Safety Evaluation Framework for LLM Agents

**链接**: https://arxiv.org/abs/2606.08531
**作者**: Lu Jia, Haibo Tong, Feifei Zhao, Jindong Li, Dongqi Liang, Ping Wu 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [75] SPRInG: Continual LLM Personalization via Selective Parametric Adaptation and Retrieval-Interpolated Generation

**链接**: https://arxiv.org/abs/2601.09974
**作者**: Seoyeon Kim, Jaehyung Kim
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [76] BenGER: Benchmarking LLM Systems on Subsumption-Based Legal Reasoning in German Law

**链接**: https://arxiv.org/abs/2605.28183
**作者**: Sebastian Nagl, Ann-Kristin Mayrhofer, Martin Heidebach, Aleyna Ko\c{c}ak, Anne Zettelmeier, Elly Breu 等 (9 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [77] Beyond Pixels: Exploring DOM Downsampling for LLM-Based Web Agents

**链接**: https://arxiv.org/abs/2508.04412
**作者**: Thassilo M. Schiepanski, Nicholas Pi\"el
**来源**: cs.AI cs.CL cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [78] KV Admission: Learning What to Write for Efficient Long-Context LLM Inference

**链接**: https://arxiv.org/abs/2512.17452
**作者**: Yen-Chieh Huang, Pi-Cheng Hsiu, Rui Fang, Ming-Syan Chen
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [79] CLIN: an Objective Framework for Evaluating Creativity in Short Persian Literary Text

**链接**: https://arxiv.org/abs/2608.30754
**作者**: Mohammad Reza Modarres, Armin Tourajmehr, Yadollah Yaghoobzadeh, Mohammad Taher Pilehvar
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Evaluating creativity in large language model (LLM) outputs remains challenging because creativity is multidimensional and human-centered. We examine how reliably LLMs evaluate short literary text in Persian, a low-resource language, across multiple evaluation strategies and prompt formulations. We find that LLM-human agreement varies substantially across dimensions: alignment is stronger for structured TTCT-derived properties such as Originality, Fluency, and Elaboration, but considerably weaker for more subjective dimensions, particularly Emotion and Attractiveness. Judgments are also sensitive to prompt formulation, while few-shot prompting, ensembling, and multi-agent debate provide no consistent improvement. Motivated by this dimension-dependent behavior, we investigate whether structured creativity dimensions can instead be approximated using simple, interpretable proxy metrics. We introduce CLIN, which evaluates three TTCT-derived dimensions separately using topic-aware novelty 

---

### [80] OntoAligner-Ensemble: Voting-Based Fusion across Heterogeneous Ontology Alignment Techniques

**链接**: https://arxiv.org/abs/2608.31137
**作者**: Hamed Babaei Giglou, S\"oren Auer, Peio Popov, Mahsa Sanaei, Jennifer D'Souza
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Ontology alignment (OA) has evolved through several methodological paradigms, ranging from lexical and structural aligners to knowledge graph embedding (KGE) models and, more recently, Large Language Model (LLM)-based approaches. Although modern OA frameworks provide unified ecosystems for deploying these heterogeneous aligners, mechanisms for systematically reconciling their complementary and sometimes conflicting predictions remain relatively underexplored. We present OntoAligner-Ensemble, a modular and aligner-agnostic framework that combines candidate correspondences through a configurable two-stage process comprising voting-based fusion strategies followed by post-fusion selection policies. The framework supports any aligner implemented within OntoAligner that produces candidate correspondences, enabling diverse alignment paradigms to be integrated through a unified decision process. To demonstrate its effectiveness, we instantiate the framework using representative lightweight st

---

### [81] Bayesian Sparse Low-Rank Adaptation for Large Language Model Uncertainty Estimation

**链接**: https://arxiv.org/abs/2607.02182
**作者**: Jijie Zhang, Zhe Ren, Quan Zhang, and Dandan Guo
**来源**: cs.LG cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [82] Do LLMs Change Their Minds Like Humans? Diagnosing Human--LLM Divergence in Single-Turn Persuasion Judgments

**链接**: https://arxiv.org/abs/2608.29803
**作者**: Lin Chen, Yitong Chen, Yong Li
**来源**: cs.CY cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly deployed as proxies for human participants in social simulations, yet whether they update their beliefs in response to persuasive arguments, as humans do, remains poorly understood. We conduct a systematic comparison using a naturally occurring online persuasion corpus in which original posters explicitly verify whether a reply changed their view. Our results show that LLMs achieve only slight agreement with humans (Cohen's kappa ranging from 0.079 to 0.178). Content-level analyses show that humans and LLMs agree on the strongest persuasion cues but diverge on finer ones: humans are more swayed by novel content and assertive language, whereas LLMs favor topical similarity and surface-level formatting. At the level of persuasion strategy, LLMs underweight emotional appeals and overweight credibility signals relative to humans, while the type of proposition under debate exerts no measurable effect on the degree of divergence. Furthermore, swi

---

### [83] Can LLM Agents Discover? Evaluating Creativity on ML Engineering Tasks

**链接**: https://arxiv.org/abs/2608.30047
**作者**: Shitanshu Bhushan, Yunxiang Zhang, Lu Wang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent AI systems promise autonomous scientific discovery, claiming to discover algorithms and produce research papers, yet understanding whether they exhibit creativity, the capacity to produce solutions that are both novel and useful, remains an open question. We present a framework for evaluating multi-turn LLM research agents' creativity using ML engineering tasks as a testbed, through three dimensions: P-Creativity (psychological novelty: novel relative to the agent's own prior solutions within a run), H-Creativity (historical novelty: novel relative to the corpus of human solutions), and Usefulness (task performance). Evaluating two agent frameworks, AIDE and AIRA-Dojo, on 10 Kaggle-style machine learning tasks from MLE-Bench, we develop an LLM-as-a-Judge pipeline and verify its strong correlation with human creativity judgments, providing a reliable automated metric for P-Creativity evaluation at scale. Applying this pipeline to agent trajectories, we find: (1) all agents exhibi

---

### [84] Whose Assessment of Distress? Community Perspectives and LLM Alignment on Well-Being Posts

**链接**: https://arxiv.org/abs/2608.29446
**作者**: Andrew Aquilina, Xiang Lorraine Li, Yu-Ru Li
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Judgments about psychological distress are socially situated: what counts as concerning hinges on community norms around emotional expression, vulnerability, and help-seeking. Yet large language models (LLMs) used for distress detection are typically aligned to a single, undifferentiated standard. How well do these models capture the perspectives of the communities whose language they assess? We address this question through a perspectivist annotation study in which 321 participants provided 9,587 judgments on 1,198 Reddit posts spanning six identity-based communities, yielding community-specific labels. Raters in the contextualized in-group condition show a modest tendency to agree more with their community than uncontextualized out-group raters (OR = 1.18), an effect varying significantly across communities. We then evaluate nine open-weight LLM configurations and four frontier configurations against these labels. Open-weight LLMs systematically over-estimate distress: when communiti

---

### [85] Beyond Ranking Accuracy: Evaluating LLM-Cited Feature Rationales for Next Basket Repurchase Recommendation

**链接**: https://arxiv.org/abs/2608.30333
**作者**: Yanan Cao, Anay Dombe, Murali Mohana Krishna Dandu, Shreeranjani Srirangamsridharan, Sinduja Subramaniam, Yogananth Mahalingam 等 (8 人)
**来源**: cs.IR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Next-basket repurchase recommendation is commonly formulated as a ranking task: given a customer's purchase history, the system ranks previously purchased items that may be needed again. In production settings, however, ranking accuracy is only one component of recommendation quality. Customers may also benefit from concise evidence about why an item is recommended now. Large language models (LLMs) offer a potential way to surface such evidence through feature-based, human-readable rationales grounded in interpretable behavioral signals. We construct repurchase features spanning cadence, frequency, recency, user behavior, and item popularity, and evaluate LLMs on two public grocery datasets and one proprietary retail dataset. We investigate (1) whether off-the-shelf LLMs can use these features as next-basket scorers relative to heuristic and supervised rankers, and (2) whether LLM-cited features carry outcome-grounded ranking signal. For the latter, we compare LLM-cited features with m

---

### [86] LLM-based Hardware Development with Hierarchical IRs and End-to-End Multi-Agent Workflow

**链接**: https://arxiv.org/abs/2608.30659
**作者**: Chenyang Yin, Agasthi Haputhanthri, Aditya Anirudh Jonnalagadda, Zhenyu Bai, Yuanming Song, Saranyu Chattopadhyay 等 (10 人)
**来源**: cs.AR cs.MA cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly used in software development, but their use in complex hardware design remains limited. This gap stems from both the scarcity of public hardware training data and the fundamentally different methodologies used in hardware design. In particular, applying LLMs to hardware requires more than direct RTL generation: the model must understand module boundaries, inter-module connections, and verification requirements. In this paper, we present an LLM-based hardware development framework with hierarchical intermediate representations (IRs) and an end-to-end multi-agent workflow. The core idea is to provide an abstraction of hardware design to LLMs through two structured IRs: Architectural Sketch, which captures module topology and interconnection, and Operational Specification, which defines per-module functionality and interfaces. Our framework uses these IRs to decompose a complex design into sub-modules, specify the per-block functionality, and 

---

### [87] Localizing Emergent Failures in Agentic AI: Recovering Minimal Repair Families via Counterfactual Replay

**链接**: https://arxiv.org/abs/2608.29228
**作者**: Bingjie Li, Yumeng Song, Zhongming Yao, Tianyi Li
**来源**: cs.AI cs.MA
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Failures in agentic AI systems can arise from interactions among messages exchanged by multiple large language model (LLM) agents. Pointwise attribution cannot distinguish a jointly necessary repair from alternative singleton repairs. We formulate Minimal Repair Family Recovery (MRFR): recovering all inclusion-minimal event sets whose counterfactual replay restores task success within a declared size bound. We propose Graph-Constrained Joint Replay (GCJR), which slices failure-relevant events from an execution dependency graph, constructs graph-feasible singleton and pair candidates, and verifies them by replay with paired clean counterparts. For fixed replay outcomes, GCJR is exact within its declared graph domain. On 90 in-scope cases from a 120-DAG controlled benchmark, GCJR achieves 1.000 Family Exact Match while reducing mean replay calls from 56.3 to 25.3 (55.1%) relative to exhaustive search. On a 24-case, four-agent LLM pilot, it again achieves 1.000 Family Exact Match and redu

---

### [88] QueryGraph: Reliable Multi-Tool Query Execution Planning via LLM-Based Graph Generation

**链接**: https://arxiv.org/abs/2606.08300
**作者**: Aishwarya Chakravarthy, Vidhi Kulkarni, and Duen Horng Chau
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [89] Single Canonical Prompts Underestimate LLM Safety's Surface-Form Sensitivity

**链接**: https://arxiv.org/abs/2608.02665
**作者**: Yongxi Zhou, Junwei Yao, Yuanzhe Liu, Zihan Dong, Wenbo Ye, Jiaxi Wen 等 (7 人)
**来源**: cs.CR cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [90] ReVEL: Multi-Turn Reflective LLM-Guided Heuristic Evolution via Structured Performance Feedback

**链接**: https://arxiv.org/abs/2604.04940
**作者**: Cuong Van Duc, Minh Nguyen Dinh Tuan, Tam Vu Duc, Tung Vu Duy, Son Nguyen Van, Hanh Nguyen Thi 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [91] Measuring the Depth of LLM Unlearning via Activation Patching

**链接**: https://arxiv.org/abs/2605.24614
**作者**: Jaeung Lee, Dohyun Kim, Jaemin Jo
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [92] Selective Forgetting: A Graph-Based Memory Framework for Long-Term LLM Agents

**链接**: https://arxiv.org/abs/2608.28978
**作者**: Theo Rusu, Sourena Khanzadeh, Manar Alalfi
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Knowledge graphs have been proposed as a structured alternative to flat retrieval-augmented generation for long-term agent memory, on the assumption that representing conversations as entities and relations improves recall. We evaluate that assumption directly. Our framework extracts each conversational turn into typed nodes and attributed edges, answers questions from a two-hop subgraph, and periodically prunes nodes that score low on a weighted combination of recency, access frequency, degree centrality, and age. On LongMemEval, the graph does not outperform a flat vector baseline at a matched candidate-generation budget of five retrieval roots: token F1 is $0.417$ against $0.468$, and a paired bootstrap over 500 questions gives $\Delta = -0.050$ (95\% CI $[-0.085, -0.016]$). The gap is widest on questions that require recalling a specific prior assistant turn, where judged correctness falls from $0.911$ to $0.607$, suggesting that decomposing a turn into entities discards the surfac

---

### [93] Facts Without Rules: Boundary Metadata Collapse in Multi-Agent LLM Handoffs

**链接**: https://arxiv.org/abs/2608.29028
**作者**: Yian Wang, Agam Goyal, Eshwar Chandrasekharan, Hari Sundaram
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-agent LLM systems often coordinate by compressing an upstream interaction into a handoff artifact that downstream agents treat as shared state. We show that this handoff step is a structural source of privacy leakage: summaries preferentially preserve operational facts while weakening the boundary metadata that governs how those facts may be used---a failure mode we call \emph{summary collapse}. On a controlled multi-agent coordination testbed we measure marker survival with a human-validated judge ($\kappa = 0.74$), where $\sigma_b = 1$ means every boundary marker survives verbatim and $\sigma_b = 0$ means all are lost. Boundary-marker and operational-fact survival are nearly uncorrelated at the handoff level on both GPT-5-mini and DeepSeek-R1-32B (Pearson $r$ near zero): uncompressed free-text handoffs preserve boundaries at $\sigma_b \approx 0.80$, whereas a $25$-word budget drops $\sigma_b$ to ${\approx}0.57$ while operational-fact survival stays near ceiling. Controlled down

---

### [94] Standardizing Longitudinal Radiology Report Evaluation via Large Language Model Annotation

**链接**: https://arxiv.org/abs/2601.16753
**作者**: Xinyi Wang, Grazziela Figueredo, Ruizhe Li, Xin Chen
**来源**: cs.CL cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [95] PsychoAgent: An Affect-Sensitive Cognitive Architecture for Conflict-Aware Memory in LLM Agents

**链接**: https://arxiv.org/abs/2608.07438
**作者**: Mohammad Amanlou, Parham Abed Azad, Farbod Davoodi, Mostafa Masumi, Behnam Bahrak, Abdol-Hossein Vahabie
**来源**: cs.AI cs.CL cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [96] Zipping the Thought: When and How Compressed Reasoning Data Works in LLM Post-Training

**链接**: https://arxiv.org/abs/2605.28008
**作者**: Kohsei Matsutani, Gouki Minegishi, Takeshi Kojima, Yusuke Iwasawa, Yutaka Matsuo
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [97] Phantom-Insight: Adaptive Multi-cue Fusion for Video Camouflaged Object Detection with Multimodal LLM

**链接**: https://arxiv.org/abs/2509.06422
**作者**: Hua Zhang, Changjiang Luo
**来源**: cs.CV
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [98] FaVOR: LLM-Based Agentic Framework for Factor Mining via Empirical Validation

**链接**: https://arxiv.org/abs/2608.30192
**作者**: Hyeonjin Kim, Minseok Kim, Seunghyeon Jung, Sujin Pyo, Huisu Jang, Woojin Lee
**来源**: cs.AI cs.CE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Traditional finance relies on experts to hand-craft factors through a principled process grounded in economic rationale. Recent LLM-based multi-agent systems have automated this process, scaling factor mining far beyond manual effort. However, these automated approaches optimize directly for returns and rarely check whether a generated factor still expresses the economic hypothesis that motivated it. We identify this inconsistency between mathematical form and economic meaning as a structural failure mode of return-oriented automation. The resulting factors blur the line between real signals and spurious correlations and break down across regime shifts. We propose FaVOR (Factor Validation through Observable Reasoning), an agentic framework that restructures factor mining around hypothesis-level evidence rather than return outcomes. In place of the standard hypothesis-to-formula leap, FaVOR enforces a three-stage consistency loop tying mathematical form to economic rationale throughout.

---

### [99] Beyond Dense States: Sparse Transcoders as Causally Testable Operators for LLM Latent Reasoning

**链接**: https://arxiv.org/abs/2602.01695
**作者**: Yadong Wang, Haodong Chen, Yu Tian, Chuanxing Geng, Dong Liang, Xiang Chen
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [100] The Shadow Price of Intelligence: Quality Degradation in LLM Inference as a Supply Chain Problem

**链接**: https://arxiv.org/abs/2608.23986
**作者**: Elioth Sanabria
**来源**: math.OC cs.AI cs.PF
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [101] Training-free LLM Verification via Recycling Few-shot Examples

**链接**: https://arxiv.org/abs/2506.17251
**作者**: Dongseok Lee, Jimyung Hong, Dongyoung Kim, Jaehyung Kim
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [102] PropUQ-MAS: Propagation-Aware Uncertainty Quantification for LLM Multi-Agent Systems

**链接**: https://arxiv.org/abs/2608.22130
**作者**: Yaokun Liu, Yifan Liu, Daniel Yue Zhang, Ruichen Yao, Zelin Li, Dong Wang
**来源**: cs.MA cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [103] Benevolent Bias in Multi-Turn Human-Agent Dialogue

**链接**: https://arxiv.org/abs/2608.29206
**作者**: Qianqi Liu, Jin Huang, Fethiye Irmak Dogan, Hatice Gunes
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Bias in human-agent interaction can manifest not only through hostile language but also as benevolent bias, whereby unequal treatment hides behind a warm, positive tone. To make it detectable, we operationalise benevolent bias along two dimensions, tone and treatment, yielding three classes: neutral support, overt bias, and benevolent bias. Building on these definitions, we construct BENEVDIAL, a class-balanced corpus of 362,880 multi-turn support dialogues spanning user and agent demographics, roles, and generators, to support controlled evaluation. We then test two detector families on it: off-the-shelf safety detectors and prompted large language model (LLM) judges. Our results reveal a detection gap: off-the-shelf detectors reliably flag overt bias yet largely miss benevolent bias, while LLM judges catch more under more explicit detection criteria but increasingly misclassify neutral support as benevolent bias, and demographic context amplifies the false alarms. These findings sugg

---

### [104] The Double-Edged Sword of Open-Ended Interaction: How LLM-Driven NPCs Affect Players' Cognitive Load and Gaming Experience

**链接**: https://arxiv.org/abs/2604.10107
**作者**: Ting-Chen Hsu, Wenran Chen, Jiangxu Lin, Fei Qin, Zheyuan Zhang
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [105] Inferring Value Criteria from Ordinal Preferences: An Iterative In-Context Learning Framework for Music Generation

**链接**: https://arxiv.org/abs/2608.30694
**作者**: Futa Hidaka, Naomi Imasato, Kazuki Miyazawa, and Takato Horii
**来源**: cs.HC
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Adapting a generative music system to an individual's taste requires learning what that listener values. Listeners can rank pieces, but their underlying criteria may be tacit and difficult to articulate. We ask whether and under what conditions a large language model (LLM) can adapt symbolic music generation from rankings alone and construct transferable natural-language descriptions of value criteria. In our iterative in-context learning framework, the LLM formulates hypotheses, generates candidate pieces in ABC notation, receives a ranking, and periodically infers and verbalizes value criteria from history to guide later generation. We evaluate the framework against 16 simulated raters in 480 adaptation runs using mixed-effects modeling, an ablation, and transfer tests on unseen music. Overall, the framework did not outperform a feedback-free diverse-generation baseline, but did so for two value functions with targets difficult to reach through simple sampling. How atypical the targe

---

### [106] SemTrace: Source-Grounded Semantic Signatures for Tracing LLM Exposure to Protected Documents

**链接**: https://arxiv.org/abs/2608.29575
**作者**: Junyan Zhang, Yudong Zeng, Yongwei Huang, Zuhao Ouyang, Hong Chen, Xuming Hu
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models are increasingly used to read documents and produce downstream text, creating a provenance problem when the document owner cannot control or inspect the model that performs the generation. We introduce SemTrace, a source-grounded semantic watermark for detecting whether a generated review was influenced by a known protected manuscript copy. Rather than biasing token probabilities or imposing surface-form patterns, SemTrace constructs a document-specific binary signature from factual propositions that are directly supported by the manuscript itself. A protected PDF invisibly carries a content contract that selects one fact from each binary pair and asks an instruction-following reviewer to express those facts in fixed review slots without changing its independent evaluation. A frozen natural language inference model then decodes the resulting semantic evidence with explicit erasures and scores the recovered bits against the codeword assigned to that copy. This desi

---

### [107] Beyond Consensus: Downward Bias and Role Asymmetry in Multi-Agent LLM Judges for Subjective Evaluation

**链接**: https://arxiv.org/abs/2608.30373
**作者**: Minsoo Song, Chanwoo Kim, Sugyeong Eo, Chanjun Park
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-Agent Debate (MAD) has been widely adopted to improve LLM-based evaluation by prompting multiple agents to negotiate and reach a consensus. However, for subjective rubric-based scoring, inter-agent agreement does not guarantee alignment with human judgments. In this paper, we compare a single-judge baseline against a consensus-based MAD protocol on subjective evaluation tasks and design three ablations to isolate the impact of role prompting, multi-round interaction, and explicit score sharing. Evaluations across six LLMs show that the single-judge baseline achieves the strongest human alignment on average across six judge models, whereas MAD shows degradation in human alignment on both tasks. Our ablations demonstrate that this performance drop stems primarily from asymmetric role prompting rather than the interaction itself. Specifically, assigning a strict judge role introduces a systematic downward bias that the consensus process fails to correct. The central finding is that 

---

### [108] Ignorance or Incompetence? Constructing Knowledge-Gated, Verifiable Tasks for LLM Agents

**链接**: https://arxiv.org/abs/2608.30322
**作者**: Hanlin Tian, Minhao Li, Yu Mi, Sihan Zhu, Zhao Yang, Yuxiang Wang 等 (8 人)
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Professional agent tasks often depend on conventions that are absent from public corpora, yet benchmarks rarely control whether an agent has access to those conventions. We introduce a knowledge-gated task-construction protocol that separates a task instruction from a compact artefact containing private conventions, reference tables, and utility operators. Construction-time provenance, byte-identical task instructions across the provided- and withheld-artefact conditions, leak audits, and executable witnesses make dependence on the artefact explicit and testable. Across fifteen calibration tasks, one frontier agent configuration achieves a 68.0% pass rate with the artefact and 0% without it; on one task, a plausible but incorrect artefact also yields 0% across five trials. Deterministic solvers and rule corpora provide exact ground truth for structured tasks, while named criterion-level rubrics support outputs that cannot be checked by a single executable oracle. A configuration-relati

---

### [109] BLOOM-WILT: Logit Tilting for Behaviour Elicitation in Automated LLM Auditing

**链接**: https://arxiv.org/abs/2608.31105
**作者**: Adrians Skapars, Edoardo Manino
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Users of a deployed language model routinely encounter behaviours that testing almost never surfaces, since deployment puts the model through orders of magnitude more interactions than any evaluation can simulate. Automated auditors make testing cheap to scale and flexible enough to cover almost any specified behaviour, yet their lack of optimisation pressure makes them sample-inefficient. To address this shortcoming, we introduce BLOOM-WILT, a full auditing pipeline that elicits natural multi-turn instances of rare behaviours, without training cost or access beyond the target's next-token distribution. On the input side, WILT's auditor model revises its conversational strategy across rounds, learning from previous scored interactions. On the output side, WILT adaptively reweights the target's decoding using the model's own distribution conditioned on an elicitation prompt, so that behaviour-relevant generations are sampled ahead of others it finds equally probable when unprompted. We 

---

### [110] Task-to-Model Optimization for Enterprise LLM Coding Assistants: A Data-Driven Framework for Cost-Optimal Routing

**链接**: https://arxiv.org/abs/2608.08528
**作者**: Srinivasan Manoharan, Junhua Zhao, Fangbo Tu, Haifeng Wu, Jian Wan, Maliah Rajan M 等 (9 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [111] LLM-Based Knowledge Graph Completion Combining Discrete Structural Coding with Similar Entity Information

**链接**: https://arxiv.org/abs/2608.30235
**作者**: Jiaqi Wang and Dongying Lin and Yang Yang and Yinan Liu and Bin Wang and Xiaochun Yang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Knowledge graph completion requires models to use both textual descriptions and relational structure. Existing LLM-based methods either encode KG structure as discrete tokens or refine a restricted set of candidate entities, and these two directions have largely been studied separately. We propose CoSC for LLM-based KGC, which combines discrete structural coding with similar entity information. Specifically, an LLM generates an initial candidate entity ranking from discrete structural codes, after which information from entities with structures similar to that of the query entity refines the ranking. Experiments on FB15k-237 show that CoSC outperforms existing baselines on MRR and Hits@10 while remaining competitive on Hits@1.

---

### [112] Cultural Bias Without a Cultural Self:A Disassociation Study of LLM's Persona and Bias

**链接**: https://arxiv.org/abs/2607.02368
**作者**: Yuan Yuan
**来源**: stat.ML cs.AI cs.LG math.DG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [113] Do We Still Need Humans in the Loop? Human vs. LLM Annotation in Active Learning for TikTok Hate Speech Detection

**链接**: https://arxiv.org/abs/2604.13899
**作者**: Ahmad Dawar Hakimi, Lea Hirlimann, Isabelle Augenstein, Hinrich Sch\"utze
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [114] SinLlama -- A Large Language Model for Sinhala

**链接**: https://arxiv.org/abs/2508.09115
**作者**: H.W.K.Aravinda, Rashad Sirajudeen, Samith Karunathilake, Nisansa de Silva, Surangika Ranathunga, Rishemjit Kaur
**来源**: cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [115] Candidate supply and answer selection shape the value of LLM judging in multi-agent systems

**链接**: https://arxiv.org/abs/2608.25937
**作者**: Jia-Hao Ji, Sijie Li, Jiabei Cheng, Zixi She, Jin-Tai Yu, Zhiyuan Yuan
**来源**: cs.AI cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [116] Popular but Wrong: Understanding and Mitigating LLM Overconfidence through Knowledge Popularity

**链接**: https://arxiv.org/abs/2505.17537
**作者**: Shiyu Ni, Keping Bi, Jiafeng Guo, Xueqi Cheng
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [117] SemPOI-RL: Aligning LLM Semantic Reasoning for Interpretable Out-of-Town POI Sequential Generation

**链接**: https://arxiv.org/abs/2608.30399
**作者**: Yunqi Liu, Yang Zhang, Ruixing Zhang, Liangzhe Han, Yi Qiao, Tongyu Zhu 等 (7 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) exhibit strong semantic reasoning and open-ended generation abilities, but aligning these abilities with structured sequential generation remains challenging. This challenge is particularly evident in out-of-town (OOT) POI sequence generation, where a model must infer transferable travel intent from a user's hometown behaviors, adapt to cross-city interest drift, and generate a coherent destination trajectory under structural constraints. Existing approaches either rely on latent ID-based transfer with limited interpretability or directly use LLMs for sequence generation without explicitly grounding inferred semantics into position-aware predictions. To address this gap, we propose SemPOI-RL, a framework that aligns LLM semantic reasoning with structured sequence generation for interpretable OOT recommendation. Specifically, we first fine-tune an LLM to infer destination-oriented travel styles from users' hometown trajectories, using natural language as an 

---

### [118] Adopt $\neq$ Adapt: Longitudinal Analyses of LLM Conversations in the Wild

**链接**: https://arxiv.org/abs/2605.29018
**作者**: Rebecca M. M. Hicke, Kiran Tomlinson
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [119] Retrieval-Augmented LLM Agents: Learning to Learn from Experience

**链接**: https://arxiv.org/abs/2603.18272
**作者**: Thomas Palmeira Ferraz, Romain Deffayet, Vassilina Nikoulina, Herv\'e D\'ejean, St\'ephane Clinchant
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [120] RegDivergence-101: An LLM Benchmark for Cross-Jurisdiction Regulatory Contradiction Detection in Life Sciences

**链接**: https://arxiv.org/abs/2608.28607
**作者**: Chuchu Wu, Zhiyin Zhou, Jingzhuo Hu, Liang You
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Pharmaceutical sponsors developing a drug for both the United States and the European Union must reconcile guidance issued independently by the FDA and the EMA. Where the two agencies require substantively the same thing, a sponsor can file once; where they diverge, a single trial design risks rejection in one region; where one agency is silent on a point the other regulates, the sponsor must infer obligations. Today this reconciliation is performed manually by regulatory-affairs experts. We introduce cross-jurisdiction regulatory divergence detection: given an FDA requirement and an EMA requirement on the same topic, classify their relationship as AGREE, DIVERGE, or SILENT. SILENT is inherently directional (SILENT_FDA vs. SILENT_EMA); we record direction per pair and report per-direction F1 alongside the collapsed label. We release RegDivergence-101, a 101-pair expert-grounded pilot evaluation benchmark (labels grounded in three peer-reviewed FDA/EMA comparison studies and primary FDA

---

### [121] Secret Stealing Attacks on Local LLM Fine-Tuning through Supply-Chain Model Code Backdoors

**链接**: https://arxiv.org/abs/2604.27426
**作者**: Zi Li, Tian Zhou, Wenze Li, Jingyu Hua, Yunlong Mao, Sheng Zhong
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [122] Watch your steps: Dormant Adversarial Behaviors that Activate upon LLM Finetuning

**链接**: https://arxiv.org/abs/2505.16567
**作者**: Thibaud Gloaguen, Mark Vero, Robin Staab, Martin Vechev
**来源**: cs.LG cs.AI cs.CR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [123] LLM Judges Verify Presence, Not Absence: Omission Blindness in AI Clinical Notes and What Recovers It

**链接**: https://arxiv.org/abs/2608.31016
**作者**: Sebastian Fox, Luke Markham, Ryan Lail, Michael Karotsieris
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Ambient AI scribes draft clinical notes, and published audits find their dominant error is omission: information the encounter established that the note fails to record. The standard check is an LLM judge: a second model reads the note against the transcript and flags problems. We ask whether judges detect omissions. Public corpora cannot supply the answer key: their clinician reference notes and transcripts are materially discrepant. Our benchmark has 500 single-error note pairs from audited fact sheets, 298 with a named fact certainly absent and 202 added-or-altered controls. Across eight judge designs, paired discrimination (the flawed note below its clean twin, 0.5 a coin flip) reads 0.79-0.94 on added or altered content and 0.50-0.63 on omissions. On single notes, no design flags omissions reliably more often than perfect notes. Wording changes, voting and GEPA prompt optimisation move the operating point without creating usable detection. Restructuring the task recovers it: list 

---

### [124] Truthful AI Advisors: A Pre-Specified Benchmark for Large Language Model Honesty Under Preference Misalignment

**链接**: https://arxiv.org/abs/2606.01456
**作者**: Hamidreza Hasani Balyani, Seyed Pouyan Mousavi Davoudi, Alireza Amiri-Margavi, Amin Gholami Davodi, Arshia Gharagozlou
**来源**: cs.LG cs.CL cs.GT
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [125] Pro-Router: Token-Aware Progressive Model Routing with Adaptive Edge-Cloud Collaboration for Efficient Multimodal LLM Inference

**链接**: https://arxiv.org/abs/2608.28726
**作者**: Xinyuan Gui, Shaowen Wang, Sheng Sun, Zijian Wang, Zishu Yu, Zheming Yang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The remarkable performance of multimodal large language models (MLLMs) comes at the cost of substantial computational overhead, posing significant challenges to real-time deployment and cost effectiveness. Existing model routing approaches either decide from coarse request-level features alone or spend one or several extra language model passes to inspect the generated response, leaving the token-level uncertainty signals that emerge during generation unused. To address these limitations, we propose Pro-Router, a token-aware progressive model routing method with adaptive edge-cloud collaboration for efficient multimodal LLM inference. Pro-Router employs a two-stage progressive decision mechanism. First, a lightweight prompt pre-scorer module performs rapid pre-screening before token generation begins, guiding apparently simple requests to small models. Second, a token-aware verifier reads the sampling probability distribution of each token the small model generates, estimating the mode

---

### [126] Validating FKG.in: Soundness Assessment in LLM-Augmented Indian Food Knowledge

**链接**: https://arxiv.org/abs/2608.29249
**作者**: Saransh Kumar Gupta, Armaan Shah, Lipika Dey, Partha Pratim Das and Ramesh Jain
**来源**: cs.AI cs.CL cs.IR cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The online culinary ecosystem is increasingly populated by recipe content generated, modified, or summarized by Large Language Models (LLMs). While often plausible, such outputs may contain hallucinated ingredients, misrepresented quantities, or culturally implausible combinations, limiting their suitability for downstream applications and knowledge graph construction. In this paper, we present a semi-automated soundness assessment workflow for validating structured recipe data extracted and augmented by LLMs from informal culinary sources. Developed as part of FKG.in, a knowledge graph of Indian food, the pipeline identifies and addresses common failure modes, including structural inconsistencies, semantic and logical incoherence, and deviations from the source text, through a multi-stage process combining formal grammars, vocabulary-based checks, statistical heuristics, Set Transformer-based coherence modeling, and retrieval-based verification. Although evaluated on Indian recipes, t

---

### [127] Linguistics-Aware Non-Distortionary LLM Watermarking

**链接**: https://arxiv.org/abs/2606.00613
**作者**: Shinwoo Park, Hyejin Park, Hyeseon An, Yo-Sub Han
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [128] SingProbe Technical Report

**链接**: https://arxiv.org/abs/2608.30703
**作者**: Sing Team
**来源**: cs.CR cs.AI cs.CL cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Runtime guardrails are essential for reliable large language model (LLM) deployment, yet existing approaches typically rely on independent, external models that introduce additional inference cost, delayed safety signals, and a capacity mismatch with increasingly capable base models. To address these issues, we introduce SingProbe, a lightweight intrinsic runtime guard that directly reuses hidden states produced during LLM inference and operates alongside autoregressive decoding. Within a unified framework, SingProbe continuously predicts query intent, response safety, and hallucination risk at the token level with negligible additional guardrail inference overhead, offering a "free-lunch" solution. We further introduce SingStreamBench, a benchmark designed to assess whether streaming guardrails remain inactive on benign prefixes while promptly detecting emerging unsafe content. Extensive experiments show that SingProbe achieves competitive or superior performance compared with substan

---

### [129] A Human-in-the-Loop Autonomous Agent for Industry Time Series Forecasting

**链接**: https://arxiv.org/abs/2608.30976
**作者**: Xiaoyu Tao, Mingyue Cheng, Ze Guo, Bokai Pan, Qi Liu, Shijin Wang 等 (7 人)
**来源**: cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Real-world time-series forecasting is rarely a one-shot model invocation: practitioners must formulate tasks, connect data and models, incorporate domain expertise, assess prediction plausibility, and communicate uncertainty. Specialized forecasting models provide strong numerical predictions but usually operate in fixed pipelines, while general-purpose large language model (LLM) agents often lack forecasting-specific checks, constraints, and stopping rules. We present CastClaw, a human-in-the-loop autonomous forecasting system built through forecasting-oriented harness engineering. CastClaw connects data, specialized models, analytical tools, user input, and a versioned execution record in one runtime. Users specify the target, horizon, constraints, and hypotheses in natural language. Starting from a supplied or model-generated forecast, CastClaw checks temporal patterns and user constraints; when evidence is missing, it retrieves context, runs an analysis or another model, or asks th

---

### [130] Explanations, Prompts, and Formalizations: Arguments for New Norms in LLM-Enabled Mathematical Research

**链接**: https://arxiv.org/abs/2608.29401
**作者**: Axel Boldt
**来源**: math.HO cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As several mathematical conjectures have recently been settled using large language models (LLMs), the mathematical community has formulated norms and recommendations regarding the publishing of such results. These norms do not cover the disclosure of the prompts and precise software setup used to obtain those results, nor do they require that results be formalized in a manner that allows for machine verification. I argue that both of these are essential. In addition, since LLM-obtained results may be hard to understand, human authors have the responsibility to invent intuitive explanations.

---

### [131] CateKV: On Sequential Consistency for Long-Context LLM Inference Acceleration

**链接**: https://arxiv.org/abs/2608.30295
**作者**: Haoyun Jiang, Haolin Li, Jianwei Zhang, Fei Huang, Qiang Hu, Minmin Sun 等 (10 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) have demonstrated strong capabilities in handling long-context tasks, but processing such long contexts remains challenging due to the substantial memory requirements and inference latency. In this work, we discover that certain attention heads exhibit sequential consistency in their attention patterns, which can be persistently identified using a coefficient-of-variation-based algorithm. Inspired by this observation, we propose CateKV, a hybrid KV cache method that retains only critical token information for consistent heads, thereby reducing KV cache size and computational overhead, while preserving the majority of KV pairs in adaptive heads to ensure high accuracy. We show the unique characteristics of our algorithm and its extension with existing acceleration methods. Comprehensive evaluations on long-context benchmarks show that, while maintaining accuracy comparable to full attention, CateKV reduces memory usage by up to $2.72\times$ and accelerates d

---

### [132] GMTS: Gradient Magnitude-based Token Selection Improves RLVR Training for LLM Reasoning

**链接**: https://arxiv.org/abs/2608.30632
**作者**: Outongyi Lv, Yuanwei Zhang, Xiaoqun Zhang
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reinforcement learning (RL), particularly RL with Verifiable Rewards (RLVR), has recently emerged as a central paradigm for enhancing large language models' (LLMs) reasoning abilities, demonstrating remarkable effectiveness across reasoning tasks. Recent studies suggest that high-entropy tokens play an exceptionally important role in model training, since training with only the highest 20% entropy tokens yields significant performance gains. However, why such high-entropy tokens are beneficial remains insufficiently understood. In this work, we find that although high-entropy tokens within one answer tend to correlate with large gradient magnitude, entropy alone fails to consistently reflect token importance across different answers, considering the variations in the answer-level reward signals. Based on this observation, we introduce the Gradient Magnitude-based Token Selection (GMTS) method to quantify token importance, which leverages the entropy-gradient connection to approximate g

---

### [133] A Multi-Agent Human-LLM Collaborative Framework for Closed-Loop Scientific Literature Summarization

**链接**: https://arxiv.org/abs/2604.01452
**作者**: Maxwell J. Jacobson, Daniel Xie, Jackson Shen, Adil Wazeer, Guang Lin, Xiao-Ying Yu 等 (9 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [134] VisLens: Single-Pass Interpretable Visual Search for Multimodal LLMs

**链接**: https://arxiv.org/abs/2608.30705
**作者**: Jingyi He, Sanghwan Kim, Zeynep Akata
**来源**: cs.CV
**匹配关键词**: LLM, MLLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal large language models (MLLMs) struggle with fine-grained Visual Search, the task of locating small or rare objects in high-resolution images. Existing remedies fall into two families: (1) Training-free methods based on attention or confidence scores are accurate but slow, since they require multiple MLLM queries per example. (2) Reinforcement Learning (RL) trained tool-use models are faster at inference but opaque, since their tool calls remain uncontrollable and hard to interpret. To overcome this, we propose \emph{VisLens} (Visual Focus via Logit Lens), a Visual Search method built on the logit lens, which decodes the semantics held in a hidden state by projecting it through the LLM head. VisLens further uses a lightweight tuned-lens that maps early hidden states into the final hidden state space, so visual tokens can be read out from early layers. These tokens are matched to target words in the query to generate a crop of the relevant region, which is fed back in alongsid

---

### [135] Unequal Verdicts: Investigating Gender Bias in LLM-Based Fake News Detection

**链接**: https://arxiv.org/abs/2608.03627
**作者**: Razieh Chalehchaleh, Reza Farahbakhsh, Noel Crespi
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [136] Q-Strata: Hierarchical Bit Allocation for Mixed-Precision Quantization of Mixture-of-Experts LLMs

**链接**: https://arxiv.org/abs/2608.30564
**作者**: Deokjae Lee and Sihun Chu and Hyun Oh Song
**来源**: cs.LG cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Mixed-precision quantization (MPQ) assigns a different bitwidth to each linear layer of a large language model (LLM) to minimize the quantization-induced quality loss under a fixed budget, but Mixture-of-Experts (MoE) models contain these layers in every expert of every MoE block, so the allocation space grows far larger than in a dense model. Existing methods either allocate within each block under a uniform per-block budget, or allocate across blocks through an additive proxy, and neither directly optimizes a model-level objective over the choices that couple the blocks. We propose Q-Strata, a bi-level allocator that ranks within-block assignments with a cheap proxy and allocates across blocks with a model-level objective evaluated on the assembled quantized model. Its inner stage caches a Pareto frontier of candidates per block over finely spaced budgets, leaving the outer stage to set one budget per block instead of a bitwidth for every linear layer. With the search reduced to one 

---

### [137] Evolutionary Soups: Evolving Mixture-of-Experts for Multi-Objective LLM Alignment

**链接**: https://arxiv.org/abs/2608.29978
**作者**: Lingxiao Kong, Steffen Staab, Cong Yang, Oya Beyan, Zeyd Boukhers
**来源**: cs.CL cs.LG cs.NE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models are increasingly required to generate responses that satisfy multiple competing objectives. Since optimal trade-offs depend on both user preferences and input prompts, controllable multi-objective generation must dynamically adapt models at inference time without retraining. To address this, we propose Evolutionary Soups, a mixture-of-experts framework for fine-grained generation control, with gating networks trained via an evolutionary algorithm. The per-layer gating networks dynamically produce expert-merging coefficients from hidden-state representations, while the evolutionary algorithm incorporates greedy hypervolume contribution for effective evolution of these gating networks, achieving consistent improvements on large and noisy training datasets and broader coverage of the non-convex Pareto front. Experiments across three tasks demonstrate the effectiveness of Evolutionary Soups over baselines: it achieves the best hypervolume, linear utility, and Tchebysh

---

### [138] Let Them Steal: Trapping Large Language Model Extraction Attacks with Knowledge Honeypot

**链接**: https://arxiv.org/abs/2606.15810
**作者**: Yuyang Dai, Yushun Dong
**来源**: cs.CR cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [139] Training and Agentic Inference Strategies for LLM-based Manim Animation Generation

**链接**: https://arxiv.org/abs/2604.18364
**作者**: Ravidu Suien Rammuni Silva, Ahmad Lotfi, Isibor Kennedy Ihianle, Golnaz Shahtahmassebi, Jordan J. Bird
**来源**: cs.AI cs.GR cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [140] Designing an Auditable LLM-Supported Workflow for Qualitative Thematic Analysis

**链接**: https://arxiv.org/abs/2608.30543
**作者**: Nadia Jul Jeldtoft, Tariq Yousef
**来源**: cs.AI cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) offer new possibilities for scaling qualitative analysis, but existing applications often provide limited methodological transparency regarding how qualitative methods are translated into computational procedures. This paper presents an auditable and privacy-preserving computational operationalization of inductive and latent Thematic Analysis (TA). This paper first derives five design principles from the methodological requirements of TA and the conditions introduced by LLM-based inference: preserving interpretative context, maintaining traceable relationships between empirical material and analytical outputs, representing analytical constructs and reasoning explicitly, constraining LLM inference to interpretative tasks, and enabling privacy-preserving local deployment. Second, it presents a proof-of-concept for a two-phase workflow that operationalizes these principles by combining interpretative LLM inference with deterministic procedural control to gener

---

### [141] SPADE: A Large Language Model Framework for Soil Moisture Pattern Recognition and Anomaly Detection in Precision Agriculture

**链接**: https://arxiv.org/abs/2509.18123
**作者**: Yeonju Lee, Rui Qi Chen, Joseph Oboamah, Po Nien Su, Wei-zhen Liang, Yeyin Shi 等 (10 人)
**来源**: cs.AI cs.LG
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [142] Influence Is Not Authority: When Causal Guardrail Signals Make Legitimate Tool Use Look Like an Attack in Tool-Using LLM Agents

**链接**: https://arxiv.org/abs/2608.29942
**作者**: Tanzim Ahad, Ismail Hossain, Md Jahangir Alam, Sai Puppala, Syed Bahauddin Alam, Sajedul Talukder
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The key limitation of current state-of-the-art influence-based guardrails is that they do not reliably distinguish a legitimate, user-authorized action from a malicious, unauthorized action when both rely on external tool information. This ambiguity can cause benign actions to trigger unnecessary verification and intervention, reducing utility and adding latency. We expose this limitation through an authorization-equivalence audit of 96 conditions derived from 24 base cases. Within matched source comparisons, we hold authorization, the exact committed action, and its intended effect fixed, changing only whether a required value comes from the user or a legitimate tool result. Although the action remains unchanged, this harmless relocation shifts the causal signal toward the attack region in all 24 cases under both Llama and Gemma scorers. Matched unauthorized controls show that the signal remains attack-sensitive, yet the benign relocation produces a larger average score shift than the

---

### [143] GRZO: Group-Relative Zeroth-Order Optimization for Large Language Model Fine-Tuning

**链接**: https://arxiv.org/abs/2606.02857
**作者**: Liyan Tan, Yequan Zhao, Yifan Yang, Ruijie Zhang, Xinling Yu, Zheng Zhang
**来源**: cs.LG cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [144] Ladders in Chaos: When, How, (and Perhaps Why) Does Test-Time Scaling Improve LLM Machine Translation

**链接**: https://arxiv.org/abs/2608.28496
**作者**: Di Wu, Sergey Troshin, Christof Monz, Antske Fokkens, Vlad Niculae
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [145] DS-Lighting: Making Agent Harnesses Explicit for Data-Science Automation

**链接**: https://arxiv.org/abs/2608.28590
**作者**: Fan Liu, Hao Liu
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Model (LLM) agents have shown promise for automating data-science workflows, yet their end-to-end performance depends critically on the agent harness that represents tasks, manages execution state, constrains output artifacts, and provides evaluation feedback. Existing data-science agents often leave this harness implicit, making results difficult to reproduce, compare, and attribute across heterogeneous tasks. We introduce DS-Lighting, a unified harness toolkit that makes harness design explicit for data-science automation. DS-Lighting decomposes the harness into four reusable layers: data, workflow, execution, and evaluation, and represents diverse agents as executable operator programs that support both predefined pipelines and adaptive search. We further integrate multiple open-source data-science benchmarks into an MLE-Bench-style task format, enabling controlled comparison under a shared task interface, sandboxed runtime, and metric protocol. Experiments across age

---

### [146] Towards a Systems Foundation for Agentic Skills: Architecture, Lifecycle, and Security

**链接**: https://arxiv.org/abs/2608.29596
**作者**: Sanket Badhe, Deep Shah, Priyanka Tiwari, Nehal Kathrotia
**来源**: cs.AI cs.LG cs.MA
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Autonomous large language model (LLM) agents increasingly face reliability, context consumption, and execution stability bottlenecks when deployed on complex, long-horizon tasks. While monolithic prompt engineering and stateless tool-calling paradigms struggle to scale, the field is rapidly converging toward \emph{agentic skills}: modular procedural abstractions that externalize execution knowledge into reusable, executable, and portable artifacts. This paper establishes a unified systems foundation and reference architecture for the agentic skills ecosystem. We formalize skills as externalized procedural knowledge bridging high-level cognitive planning with deterministic execution environments, and systematically delineate the architecture across a nine-stage lifecycle: autonomous discovery, authoring and representation formats, memory storage, dynamic retrieval and routing, composition and orchestration, execution and repair, lifelong adaptation, empirical evaluation, and security go

---

### [147] SkillRet: A Large-Scale Benchmark for Skill Retrieval in LLM Agents

**链接**: https://arxiv.org/abs/2605.05726
**作者**: Hongcheol Cho, Ryangkyung Kang, Youngeun Kim
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [148] Spatial-Knowledge-Graph-Grounded LLM Agents for Neighborhood Livability Evaluation

**链接**: https://arxiv.org/abs/2608.25952
**作者**: Haiyan Hao
**来源**: cs.CY cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [149] Locality-Aware Redundancy Pruning for LLM Depth Compression

**链接**: https://arxiv.org/abs/2605.27786
**作者**: Vincent-Daniel Yun, Youngrae Kim, Woosang Lim, YoungJin Heo, Minkyu Kim, Sunwoo Lee
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [150] SynthAVE: Scalable Synthetic Labeling for E-Commerce with LLM-Arena Validation

**链接**: https://arxiv.org/abs/2607.07469
**作者**: Andrea Scarinci, Virginia Negri, Brayan Impata, Suleiman Khan, Victor Martinez, Marcello Federico
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [151] Domain-Grounded Tool Orchestration for LLM-Guided Scientific Analysis

**链接**: https://arxiv.org/abs/2608.30696
**作者**: Jeff Lee, Sebastien Jourdain, Cory Quammen, Patrick O'Leary, Berk Geveci
**来源**: cs.CE cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Scientific analysis workflows encode deep domain knowledge through sequences of tightly coupled operations where correctness depends on tool selection, execution order, and parameterization. A CFD engineer investigating flow separation must extract wall shear stress, identify zero-crossings in skin friction, and confirm with boundary-layer profiles: a chain that requires both domain expertise and proficiency with visualization tools. Current approaches to LLM-assisted scientific visualization generate scripts that encode this knowledge implicitly, and often incorrectly, producing code that executes but yields wrong results. We present an architecture that separates intent interpretation (LLM) from execution (deterministic domain tools) from explanation (LLM), connected by the Model Context Protocol (MCP) and grounded by domain ontologies that constrain planning to valid analysis chains. We instantiate the architecture in two domains on the same ParaView server infrastructure: computati

---

### [152] Large language model-enabled automated data extraction for concrete materials informatics

**链接**: https://arxiv.org/abs/2604.22938
**作者**: Zhanzhao Li, Kengran Yang, Qiyao He, Kai Gong
**来源**: cond-mat.mtrl-sci cs.CL cs.LG
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [153] Not to Break, but to Attest: Adversarial Probes for Privacy-Preserving LLM Verification

**链接**: https://arxiv.org/abs/2608.27954
**作者**: Cameron Wilding, Mina Shaker, Fatemeh Ganji
**来源**: cs.CR cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [154] CAST: Critique-Aware Supervision for Training Reliable Long-Horizon Tool-Calling Agents

**链接**: https://arxiv.org/abs/2608.30147
**作者**: Amir Saeidi and Zehua Zhang and Rishitosh Singh and Naman Ahuja and Vivek Gupta and Ali Payani and Gaowen Liu and Jayanth Srinivasa and Chitta Baral
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents are increasingly deployed in long-horizon, interactive, and stateful environments. In these settings, a single wrong action, such as refunding the wrong purchase, can cause irreversible task failure and must be intercepted before execution. Such failures may not appear in every single run, but can emerge across repeated trials, making reliability across steps and trials critical. However, ensuring agentic reliability is challenging: even frontier LLMs struggle to explain why an action may be wrong, especially in long, intertwined trajectories governed by domain-specific policies. Much recent work relies on prompt-based critique agents, while optimization-based methods lack a systematic way to produce rich verification rationales for training. We address this gap with CAST, a critique-aware training framework that converts sparse task outcomes into action-level supervision for critique learning and policy optimization. CAST analyzes agent trajectories t

---

### [155] How do World Models and Policies Compose in LLM Agents? A Joint Spectral and Behavioral Account

**链接**: https://arxiv.org/abs/2608.30067
**作者**: Ruize Xu, Xiao Yu, Yujin Tang, Chenming Shang, Nikhil Singh
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> How do LLM agents come to both understand environments they act in and master tasks set within them? Through controlled experiments combining world-model training (next-state prediction) and policy training (reward maximization), we investigate this question. We dissect the resulting models through their additive parameter updates. Geometrically, we find effective world-model updates are low-rank and share an input-feature subspace with policy updates while writing to nearly orthogonal output directions, whether trained separately or sequentially. However, we find that, in projection interventions, the sequential update induces more robustness than separate policy RL when removing the world model's leading input directions, suggesting that it has learned alternative input pathways. Behaviorally, we find the sequentially trained agent explores a wider range of states and actions. Based on this, we ask: does policy training preserve world knowledge as well as it could? We probe this with

---

### [156] BIRDS: Characterizing and Understanding Biodiversity Impact of Large Language Model Serving

**链接**: https://arxiv.org/abs/2605.27480
**作者**: Tianyao Shi, Yi Ding
**来源**: q-bio.OT cs.AI cs.CY
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [157] FAA Framework: A Large Language Model-Based Approach for Credit Card Fraud Investigations

**链接**: https://arxiv.org/abs/2506.11635
**作者**: Shaun Shuster, Eyal Zloof, Asaf Shabtai, Rami Puzis
**来源**: cs.CR cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [158] MAS-on-the-Fly: In-Context Structural Adaptation of LLM-Based Multi-Agent Systems

**链接**: https://arxiv.org/abs/2602.13671
**作者**: Guangyi Liu, Haojun Lin, Huan Zeng, Heng Wang, Quanming Yao
**来源**: cs.MA cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [159] TRACER: Per-Tool Context Retention for LLM Agents via Consequence-Attributed Reinforcement Learning

**链接**: https://arxiv.org/abs/2608.29363
**作者**: Ziqi Lin, Ye Wu, Mengying Yang, Xu Liu, Yizhou Liu, Qiang Ke 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Enterprise data agents answer business queries by chaining many tool calls over multiple reasoning steps, routinely accumulating hundreds of thousands of context tokens per session. Existing compression strategies typically allocate retention budgets without accounting for the downstream consequences of removing individual tool outputs. Aggressive compression may therefore trigger costly tool re-invocations that offset the initial savings. We call this the compression--consequence gap. To close it, we propose TRACER, which formulates compression as a sequential per-tool decision problem. A lightweight REINFORCE policy assigns query-conditioned retention ratios using only information available at each compression event. Its consequence-aware objective jointly accounts for task success, total token consumption, and post-compression tool re-invocations. To improve credit assignment, TRACER uses a learned outcome model to compare the predicted consequences of the selected retention ratio w

---

### [160] A rigor-matched audit of periodic-step layer skipping for efficient llm inference: conflayers versus swift, with a supplemental analysis of trained routing alternatives

**链接**: https://arxiv.org/abs/2608.28846
**作者**: Prateek Kumar Sikdar, Arpan Ghosh
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Layer-skipping methods for efficient LLM inference decide, at some granularity, which transformer layers to execute for a given input. We present a rigor-matched, three-seed audit of two periodic-step, search-based methods that make this decision online at inference time and re-evaluate it every few generation steps: a confidence-gated early-exit baseline (ConfLayers) and genuine self-speculative decoding (SWIFT, Xia et al. 2024), together with vanilla autoregressive decoding, across two model scales (Qwen2.5-0.5B and Qwen2.5-1.5B) and two tasks (GSM8K reasoning and CNN/DailyMail summarization). SWIFT is the strongest method on accuracy in three of four cells; ConfLayers is dominated everywhere, with particularly large deficits on GSM8K at 1.5B. Once online-search overhead is separated from pure inference cost, SWIFT's true inference speed is faster than ConfLayers's in all four cells (5-21%), reversing the naive wall-clock ranking in three of them. ConfLayers's search overhead is smal

---

### [161] AutoCRAT: Within-trajectory Joint Control of Stochasticity and Compute for LLM Reasoning

**链接**: https://arxiv.org/abs/2608.29988
**作者**: Hanjun Luo, Qiushi Liu, Jingya Zhang, Haihong Pang, Jiaheng Wen, Yifei Ma 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) achieve strong reasoning performance, which depends critically on inference-time decisions. Yet these decisions are commonly handled by static, one-size-fits-all policies, limiting adaptation to diverse tasks and reasoning stages. Recent adaptive methods partially address this limitation, but they primarily adapt either decoding stochasticity (how the model explores) or reasoning compute (how long the model reasons) in isolation, leaving their interaction within a single reasoning trajectory unmodeled. To address this challenge, we shift toward a within-trajectory joint control view, and instantiate it in AutoCRAT, a decoder-side controller for frozen backbones. Using only signals available during decoding, AutoCRAT jointly adjusts sampling stochasticity and reasoning budget during generation. AutoCRAT operates over a discrete action space and updates control decisions only at semantic boundaries, improving stability while remaining responsive to the evolvi

---

### [162] Sustained Heterogeneity: an emergent collective mechanism in LLM-driven traffic

**链接**: https://arxiv.org/abs/2608.29174
**作者**: Yujun Qi, Yangyang Guan
**来源**: physics.soc-ph cs.MA nlin.AO
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly adopted as closed-loop controllers in physical multi-agent systems, yet their emergent collective dynamics remain incompletely characterised. We deploy 22 LLM agents as direct, real-time target-speed controllers (per 0.5 s cycle, with IDM as collision-avoidance clamp) on a 230 m ring road under the Sugiyama 2008 paradigm, reproducing human-like stop-and-go waves. Six matched controls spanning stochasticity (white noise, OU noise, temperature), population variance, and dynamical instability (delay, OV model) are systematically excluded. The surviving phenomenon, termed Sustained Heterogeneity (SH), is the persistent, approximately temperature-insensitive (approx. 8 percent across a 6x T sweep), per-cycle divergence in LLM-chosen target-speed adjustments, propagating through a three-stage cascade of drift, gap erosion, and nonlinear braking. Across four traffic densities, the critical LLM penetration fraction p_c decreases monotonically from 

---

### [163] Different Demographic Cues Yield Inconsistent Conclusions About LLM Personalization and Bias

**链接**: https://arxiv.org/abs/2601.18486
**作者**: Manuel Tonneau, Neil K. R. Sehgal, Niyati Malhotra, Sharif Kazemi, Victor Orozco-Olvera, Ana Mar\'ia Mu\~noz Boudet 等 (10 人)
**来源**: cs.CL cs.CY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [164] Agentic Chain-of-Thought Steering for Efficient and Controllable LLM Reasoning

**链接**: https://arxiv.org/abs/2606.03965
**作者**: Yu Xia, Zhouhang Xie, Xin Xu, Byungkyu Kang, Prarit Lamba, Xiang Gao 等 (7 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [165] GenRubric: Self-Evolving Rubric Generation for Scalable LLM Evaluation

**链接**: https://arxiv.org/abs/2608.29856
**作者**: Yifan Chen, Haitao Li, Qingyao Ai, Fengbin Zhu, Tat-Seng Chua, Min Zhang 等 (7 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models are increasingly used as scalable evaluators for open-ended tasks. However, many LLM judges derive query-specific criteria during scoring, leaving the evaluation requirements insufficiently specified and their coverage difficult to audit. Query-specific rubrics make these requirements explicit, but expert-written rubrics are costly to construct, while existing automatic methods typically rely on inference-time refinement or external supervision. We introduce GenRubric, a self-evolving framework that improves rubric generation from unlabeled queries without requiring additional human annotations during self-evolution. Our approach is based on rubric-induced self-consistency: independently sampled rubrics for the same query provide partial views of its latent evaluation requirements, and a comprehensive rubric should induce a response that generalizes across these complementary evaluation views. We implement this principle through reinforcement learning, combining a

---

### [166] Repair or Resample? Rethinking Failure Debugging in LLM Multi-Agent Systems

**链接**: https://arxiv.org/abs/2608.25920
**作者**: Zhongwen Luan, Xiaoyu Zhang, Ming Hu, Yue Yang, Jiongchi Yu, Xiaohong Chen
**来源**: cs.AI cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [167] Detecting and Guiding LLM-Generated Korean Poetry with Interpretable Form-level Features

**链接**: https://arxiv.org/abs/2608.28986
**作者**: Keunhyeung Park, Seunguk Yu, YoungBin Kim
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLMs often struggle with modern Korean poetry, producing outputs that resemble "line-broken prose." We address two coupled tasks: detecting whether a Korean poem is human- or LLM-authored, and guiding LLMs to generate poetry closer in form to human writing. We quantify the human-LLM gap along four form-level linguistic dimensions: output length (Volume), the diversity and connective use of line-final forms (Structure Variation), the irregularity of line lengths (Rhythmic Irregularity), and adherence to standard orthography (Normative Adherence). We operationalize these dimensions as five interpretable features. For detection, a logistic regression classifier over these five features attains an average AUC-ROC of 83.60 in zero-shot out-of-distribution detection across seven unseen LLMs, versus 75.84 for the strongest baseline in our comparison, KatFishNet, an absolute gain of 7.76 AUC points and a 10.23% relative improvement; one generator-specific punctuation pattern outside our taxono

---

### [168] Evaluating and Improving LLM Self-Modeling

**链接**: https://arxiv.org/abs/2608.30980
**作者**: Siqi Zeng, Andre N. Assis, Rowan Wang
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We study self-modeling: an LLM's ability to answer questions about its own behavior. We focus on verifiable behavioral questions, such as whether a prompt edit would change the model's final answer. To measure this capability, we introduce a benchmark that tests diverse types of self-modeling questions. Current models show non-trivial but limited self-modeling skill, and make systematic mistakes on simple counterfactual questions about their own behavior. To improve self-modeling skill, we develop a scalable synthetic-data pipeline that produces self-modeling training data, and show that reinforcement-learning can improve aggregate self-modeling skill across three open-source model families with some transfer to held-out tasks. These gains, however, do not seem to constitute introspection consistently: improved self-modeling may not arise from privileged access to the model's internal decision process.

---

### [169] Skill-as-Pseudocode: Refactoring Skill Libraries to Pseudocode for LLM Agents

**链接**: https://arxiv.org/abs/2605.27955
**作者**: Xinze Li, Yuhang Zang, Yixin Cao, Aixin Sun
**来源**: cs.PL cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [170] ProgRouter: Online Progress-Guided Orchestration for Multi-Agent LLM Workflows under Quality-Cost Tradeoffs

**链接**: https://arxiv.org/abs/2608.25992
**作者**: Songyuan Li and Ahmed M. Abdelmoniem and Shiqiang Wang
**来源**: cs.AI cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [171] TACS: Trajectory-Aware Candidate Selection for LLM Jailbreak Suffix Optimization

**链接**: https://arxiv.org/abs/2608.29564
**作者**: Shiliang Xiao
**来源**: cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Gradient-based jailbreak suffix optimization methods typically update the suffix by retaining the candidate with the lowest current loss. We show that this seemingly natural design is fundamentally myopic: candidates that look better under the current-step proxy often fail to produce better jailbreak outcomes later in the search, revealing a form of selection-stage reward hacking. This suggests that candidate selection, rather than candidate generation alone, is a hidden bottleneck in suffix optimization. To address this issue, we propose \OURS{}, a trajectory-aware candidate selection framework for jailbreak suffix optimization. Instead of selecting candidates solely by their immediate loss, \OURS{} augments per-step evaluation with a trajectory-aware proxy and stabilizes selection with reference-policy regularization and a discriminator-estimated chi-squared correction, encouraging choices that remain effective beyond the current step. Experiments on HarmBench show that \OURS{} consi

---

### [172] BIRD-History: A Benchmark for History-Driven Text-to-SQL with Fine-Grained Knowledge Annotations

**链接**: https://arxiv.org/abs/2608.29345
**作者**: Yunfan Zhou, Qiming Shi, Yizhou Yang, Di Weng, Yingcai Wu
**来源**: cs.AI cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> While recent Large Language Model (LLM)-based text-to-SQL systems achieve impressive performance on standard benchmarks, they struggle when user queries implicitly rely on domain-specific knowledge, such as business logic, data conventions, and analytical practices, that is neither captured by the schema nor explicitly stated in the natural language question. Historical SQL query logs offer a valuable source of such knowledge, yet existing benchmarks do not adequately support evaluation of history-driven approaches. To address this gap, we introduce BIRD-History, a benchmark consisting of 1,393 tasks across 11 databases, designed to evaluate text-to-SQL systems' ability to ground underspecified natural language questions using historical SQL scripts. Each task is annotated with ground-truth labels specifying which historical queries contain relevant knowledge and which SQL clauses encode it, enabling systematic evaluation of both retrieval effectiveness and knowledge utilization. Along

---

### [173] Will the User Ever Know? Covert Indirect Prompt Injection on Tool-Using LLM Agents

**链接**: https://arxiv.org/abs/2608.30362
**作者**: Yunseok Lee, Yunji Kim, Woojin Lee
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As LLM agents take real-world actions through tools, indirect prompt injection (IPI) has emerged as a serious threat. The standard metric, Attack Success Rate (ASR), counts whether an injection succeeds but ignores what the user notices in the agent's final response. Looking at successful injection traces, we find two distinct outcomes: the agent executes the injection while returning an otherwise normal response, or reports the injected action in its final response, giving the user a chance to notice. We call these covert and overt successes. From the user's perspective, we decompose ASR into the Covert Success Rate (CSR), counting successes leaving no trace in the final response, and the Overt Success Rate (OSR), counting successes the user can detect. To understand what drives the gap, we analyze successful trajectories and find that the agent's behavior after the injection separates covert from overt: covert traces hand control back to the user task before ending, while overt trace

---

### [174] Skill-Conditioned Gated Self-Distillation for LLM Reasoning

**链接**: https://arxiv.org/abs/2605.28791
**作者**: Jiazhen Huang, Xiao Chen, Xiao Luo, Yong Dai, Senkang Hu, Yuzhi Zhao
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [175] A Universal Context-Reuse Layer for Cross-Model KV Sharing

**链接**: https://arxiv.org/abs/2608.30963
**作者**: Yi Li, Dongming Jiang, Yi Zhao, Bingzhe Li
**来源**: cs.LG cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Modern large language model (LLM) serving systems increasingly operate over repeated or shared context, yet each model typically performs its own prefill computation even when another model has already processed the same input. Existing KV-cache reuse mechanisms substantially reduce redundant computation within a single model, but generally assume that the producer and consumer of a cache are identical. We study \emph{cross-model KV sharing}, which translates the KV state produced by a source model into a representation that can be consumed by a different target model, including models that differ in scale, architecture, attention configuration, tokenizer, and model family. We evaluate the approach in both within-family and cross-family settings. For Qwen2.5-7B $\rightarrow$ Qwen2.5-1.5B, translated KV states improve LongBench2 accuracy from 27.59\% to 34.48\%, a gain of 6.89 percentage points over the native 1.5B baseline, while reducing handoff cost relative to native target prefill.

---

### [176] Agora: Enhancing LLM Agent Reasoning Via Auction-Based Task Allocation

**链接**: https://arxiv.org/abs/2607.09600
**作者**: Kaiji Zhou, Ale\v{s} Leonardis, Yue Feng
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [177] T-MAP: Red-Teaming LLM Agents with Trajectory-aware Evolutionary Search

**链接**: https://arxiv.org/abs/2603.22341
**作者**: Hyomin Lee, Sangwoo Park, Yumin Choi, Sohyun An, Seanie Lee, Sung Ju Hwang
**来源**: cs.CR cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [178] Kascade: A Practical Sparse Attention Method for Long-Context LLM Inference

**链接**: https://arxiv.org/abs/2512.16391
**作者**: Dhruv Deshmukh, Saurabh Goyal, Nipun Kwatra, Ramachandran Ramjee
**来源**: cs.LG cs.AI cs.DC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [179] InsightToast: Proactive Information Retrieval & Glanceable Visualization in the Side Channel of Data-Rich Meetings

**链接**: https://arxiv.org/abs/2608.31115
**作者**: Mohammad Abolnejadian, Matthew Brehmer
**来源**: cs.HC cs.IR
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Missing institutional context during meetings can impede effective participation. Retrieving relevant information, often scattered across heterogeneous internal and external sources, requires costly task-switching that disrupts both individual focus and collective conversational flow, particularly detrimental during cognitively demanding tasks such as decision-making. We introduce InsightToast, a mixed-initiative application that monitors verbal discourse in real time, identifies topics and informational needs as they emerge, and proactively retrieves relevant information through a multi-agent large language model (LLM)-based pipeline integrating retrieval-augmented generation (RAG) to produce source-grounded insights as succinct text and glanceable interactive charts, delivered through a peripheral interface as ephemeral toasts in the conversation's side channel. To demonstrate the potential for yielding serendipitous insights, we showcase a usage scenario involving a knowledge base o

---

### [180] Token Counts Are Not Model Lineage: A Frozen-Threshold Holdout Study of Black-Box LLM API Fingerprinting

**链接**: https://arxiv.org/abs/2608.29930
**作者**: Bo Chen
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Black-box model attribution is increasingly relevant when large language models (LLMs) are served through relay and reseller APIs. A tempting low-cost signal is the prompt-token count returned by an OpenAI-compatible endpoint: two models that share a tokenizer and chat template may produce the same count sequence up to a fixed offset. Yet the validity of this signal for broader \emph{model-family} attribution has received little direct holdout testing. We conduct a frozen-threshold study over 24 labeled endpoint pairs, split evenly into a development set and an untouched holdout set, with three temporal repeats and 30 controlled texts per pair. We introduce a validity-gated result contract that distinguishes an observed dissimilarity from an uninformative measurement caused by missing usage data, rate limits, or endpoint policy. The resulting shift-invariant exact-match score perfectly separates the 12 development pairs, yielding a frozen threshold of 0.725. On holdout, however, only 6

---

### [181] "Act Like a 5th Grader" is Not Enough: Bounding Knowledge in LLM-Based User Simulators

**链接**: https://arxiv.org/abs/2608.30033
**作者**: Krisztian Balog, Arild Michel Bakken
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly used to simulate human behavior but frequently fail to exhibit realistic cognitive constraints, suffering from a "superhuman bias." Using a dataset of over 71,000 reading comprehension responses from 2,359 primary-school students (grades 4--6), we demonstrate that standard persona prompting yields near-perfect, deterministic performance, failing to capture the natural variance of developing readers. To address this, we introduce the Cognitively Bounded User Simulator (CBUS), an architectural framework that explicitly models the restricted working memory of young readers through an episodic bottleneck. Within this framework, we formalize two distinct test-taking strategies to emulate different reading behaviors. Our evaluation shows that explicitly modeling cognitive bounds significantly narrows the simulation gap across multiple LLM backbones, demonstrating that enforcing architectural constraints is more effective for high-fidelity simulat

---

### [182] Detect Before You Attribute: Cascade Failure Attribution for Multi-Agent Systems

**链接**: https://arxiv.org/abs/2608.29646
**作者**: Jiayi Zhang, Zexin Wang, Degang Sun, Changhua Pei, Fei Sun, Gaogang Xie 等 (7 人)
**来源**: cs.AI cs.MA
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM)-based agents have shown strong potential in solving complex tasks through multi-step reasoning, yet they remain vulnerable to execution failures. Accurate failure attribution is therefore critical for improving agent reliability. Existing topology- and spectrum-based methods exploit trajectory structures but often overlook fine-grained semantics, while LLM-based attribution methods capture semantic cues but suffer from long-context degradation over lengthy trajectories. To address these challenges, we propose DUOTRACE, a plug-and-play detection filter for LLM-based failure attribution. DUOTRACE follows a detect-before-attribute paradigm: it first detects anomalous executions and then supplies focused trajectory evidence to downstream LLM-based attribution methods. For effective VAE-based anomaly detection on agent trajectories, DUOTRACE integrates dual-view semantic-structural node representations, a Tree-LSTM-based trajectory encoder, and prefix-chain- and L

---

### [183] Error-Type-Aware Loss Reweighting for Robust Named Entity Recognition with Noisy LLM Labels

**链接**: https://arxiv.org/abs/2608.30827
**作者**: Elena Merdjanovska, Jonas Golde, Alan Akbik
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models are increasingly used to annotate datasets for training smaller, task-specialized models such as named entity recognition. While this method yields effective models, it assumes that the synthetic dataset is correctly annotated. In this work, we find that (i) current fine-tuning processes simply ignore LLM-introduced annotation noise, resulting in degraded performance and (ii) existing noise-robust losses are not transferable to sequence labeling because annotation noise in named entity recognition is heterogeneous: for example, missing mentions and type errors affect the training signal in different ways. Treating all noisy tokens equally in noise-robust losses and applying a single reweighing criterion for all may therefore remove useful supervision or reinforce incorrect labels. To address this limitation, we propose error-type-aware loss reweighting for NER, which introduces separate reweighing rules for different types of potentially erroneous tokens. Our appr

---

### [184] Efficient GPU Retrieval for Semantic Search

**链接**: https://arxiv.org/abs/2608.28968
**作者**: Dhritiman Das, Chujie Zheng, Ronak Kaoshik, Pratik Dixit, Vishal Shah, Yanbo Li 等 (10 人)
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Semantic Search on LinkedIn must retrieve relevant profiles from a corpus of hundreds of millions in response to natural-language queries such as "a fintech founder in Berlin who worked in payments." The deployed relevance policy is bottleneck-oriented: every active non-negotiable facet must be satisfied, and a pre-existing LLM Graded Relevance (GR) judge operationalizes this through a fixed min/median aggregation over facet grades. Cosine similarity instead averages evidence, letting a strong match on one facet mask failure on another, capping the recall of the first-stage (L0) retriever. We present a policy-aligned retrieval framework: embeddings are partitioned into eight category-supervised segments whose scores follow the same min/median rule at serving time; for multi-vector retrieval, this segment score is computed independently per tagged document slot and maximized across slots. A lightweight single-slot Stage-1 scorer generates high-recall candidates, while scale-invariant re

---

### [185] When Patients Cut In: Extending Clinical Conversational AI Safety to Interruptions

**链接**: https://arxiv.org/abs/2608.29241
**作者**: Zachary Ellis, Spencer Hazel, Adam Brandt, Yajie Vera He, Ernest Lim, Jared Joselowitz
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Clinical voice agents are now deployed in routine care, where real patients do not wait their turn: they interrupt. These systems typically use a cascaded architecture (speech-to-text -> LLM -> text-to-speech), so when a patient cuts the agent off mid-utterance, clinically required content can be lost even when the model handles cooperative transcripts well. Yet clinical conversational-AI benchmarks almost universally assume patients wait for the agent to finish, missing interruption-induced loss of required content. We present a transcript-based evaluation of interruption recovery, adapting conversation-analytic overlap categories into three operational types (recognitional, competitive, transitional sub-unit) and testing four deployment-oriented, non-reasoning LLM configurations across four cells spanning history-taking (information gathering) and FAQ (information provision), scored on whether the agent preserves the clinically required content. In the gathering cells, target-questio

---

### [186] Strong Drafts Need Compact Memories: Long-Context Speculative Decoding with Compressed KV Cache

**链接**: https://arxiv.org/abs/2608.30252
**作者**: Tong Yuan, Chengxi Liao, Zeyi Wen
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-context LLM applications such as document summarization and multi-turn agents require generation from prefixes spanning tens of thousands of tokens, making decoding latency a major bottleneck. Speculative decoding (SD) reduces latency without changing model outputs, but its speedup depends on both accepted draft tokens and draft-step latency: Lightweight drafts are fast but lack the capacity to capture long-range dependencies, whereas strong independent drafts recover acceptance but incur growing KV-access cost at long prefixes. We introduce memory-augmented drafting for long-context SD, equipping a strong independent draft with compressed draft-side KV memory: A lightweight adaptor constructs and incrementally updates this memory to retain distant information and exact recent context. The target verifier retains its full KV cache and applies the standard accept/reject rule, preserving SD's lossless guarantee. Experiments on Llama~3.1-8B and 70B targets at prefix lengths up to 32K

---

### [187] LLMs Interpret, Embeddings Organize, Graphs Emerge: Agent-Driven Compilation of Scientific Knowledge

**链接**: https://arxiv.org/abs/2608.29612
**作者**: Shi-Ju Ran, Kun Zhang, Xi Wu, Liu-Si Yang, and Wen-Jun Li
**来源**: cs.AI cs.DL cs.IR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Sustained scientific work requires a knowledge substrate that carries interpretation across tasks and preserves paths to source evidence. We call this process \emph{scientific knowledge compilation} and implement it in ASKS, the \emph{Agent-Driven Scientific Knowledge System}. For each source, an LLM produces a readable Wiki view and machine-facing semantics. Deterministic checks convert the latter into a document-local GraphDelta, and embedding geometry together with explicit graph rules integrates the proposed changes into persistent state. Each ingest is an inspectable state transition over accumulated knowledge, with compiled Wiki and graph views linked to the preserved source record. We examine this process by chronologically compiling 56 published papers from one research program. Branch survival, cross-paper support, lineage, coverage, and churn yield a source-traceable author research portrait centered on tensor-network methods, with branches into quantum many-body research, te

---

### [188] Harness-RL: Black-Box Reinforcement Learning with Action-Args Decoupling for Central-Agent Multi-Agent Harnesses

**链接**: https://arxiv.org/abs/2608.29641
**作者**: Xinke Jiang, Zhixin Zhang, Zhibang Yang, Jiaran Gao, Rihong Qiu, Shijin Chen 等 (8 人)
**来源**: cs.MA
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model agents increasingly solve long-horizon tasks through multi-agent harnesses in which a central agent coordinates specialized sub-agents, tools, and environments. Training the central policy in such a harness raises two challenges. First, an action label is a low-cardinality decision, whereas its args form a high-dimensional conditional sequence; optimizing both with a shared sequence-level signal can produce conflicting gradients. Second, dynamic scheduling creates interdependent sessions with branches, parallel calls, and rewritten contexts, which cannot be faithfully reduced to one flat token sequence. We introduce Harness-RL, a structured reinforcement learning framework that combines Conflict-Aware Policy Optimization (CAPO) with interface-level black-box trajectory construction. The black-box component captures Interface Call Records, builds per-session prefix trees, and aligns outcome and process rewards with trainable tokens. CAPO uses forward activations to 

---

### [189] SIC-Agents: Benchmarking and Building an Adaptive Simulator for Pediatric Serious Illness Communication Training

**链接**: https://arxiv.org/abs/2608.29481
**作者**: Zihan Wang, Anita Marie Slominska, Rennie Bimman, Elizabeth Di Flumeri, Amanda Mayappo-Neeposh, Conall Francoeur 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Pediatric serious illness communication (SIC) is critically important, yet scalable communication training for clinicians remains limited. Compared with other dialogue simulation settings, pediatric SIC poses additional challenges, including multi-party interactions, response to parental distress and strong dependence on feedback dynamics. Existing LLM-based simulators optimize generic dialogue quality rather than curriculum-contingent behavior required for effective SIC training. In collaboration with educators and pediatric clinicians, we introduce the first benchmark suite and simulation framework tailored to pediatric SIC training. Our benchmarks, PitfallBench and DialogueBench, evaluate simulators both at the turn-level and across full dialogues. We further propose SIC-Agents, a self-improving framework that generates a clinician-editable skill document to guide simulator behavior. Our experiments show that SIC-Agents outperforms static expert prompting. To support future research

---

### [190] EvoSkill Injection: Red-Teaming Autonomous Skill Generation and Evolution in Self-Evolving Agents

**链接**: https://arxiv.org/abs/2608.30429
**作者**: Doyun Kim, Chanwoo Kim, Sugyeong Eo, Yeo-Chan Yoon, Chanjun Park
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based agent systems increasingly adopt skill-based architectures to reduce repetitive reasoning costs and improve stable, efficient task execution. Recent studies propose self-evolving agents that autonomously generate, refine, and reuse skills from past experiences to enable continuous capability evolution. However, autonomous skill evolution introduces a new attack surface in which malicious capabilities are generated, stored, and reused as legitimate skills. In this paper, we define EvoSkill Injection as a threat model targeting the autonomous skill generation and evolution pipeline of self-evolving agents. We further propose SARGE (Red-teaming Autonomous Skill Generation and Evolution in self-evolving agents), a red-teaming framework for evaluating this threat model through iterative generation, escalation, and reinforcement interactions. To support our framework, we construct EvoSkillBench, a benchmark dataset of malicious interaction trajectories for inducing malicious skill 

---

### [191] EmoLASP: Emotion Recognition with Language Models and Answer Set Programming

**链接**: https://arxiv.org/abs/2608.29035
**作者**: Thao Le and Michael Thielscher
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Emotion recognition in conversations is increasingly tackled with language models, but these models can be unstable and expensive to fine-tune or to prompt with long dialogue histories. We propose EmoLASP, a framework that combines a language model with declarative reasoning via Answer Set Programming (ASP) to predict VAD scores (Valence-Arousal-Dominance) in conversations. Experiments on a widely used benchmark dataset (IEMOCAP) across six open-source LLMs (3B-120B) and two PLMs (BERT, RoBERTa) show that EmoLASP improves prediction performance compared to using the language model alone, even when the LLMs/PLMs are given no dialogue history in their prompts or input vectors. The gains are largest for prompt-only LLMs, which EmoLASP uses without any fine-tuning. However, for fine-tuned PLMs, the reasoner adds little once dialogue history is available. EmoLASP's LLM pipeline demonstrates the potential advantages of using a reasoning approach to ensure emotion prediction consistency and t

---

### [192] Learning to Follow In-Context Watermark Instructions via Self-Distillation

**链接**: https://arxiv.org/abs/2608.29030
**作者**: Yepeng Liu, Tianyi Chen, Xuandong Zhao, Dawn Song, Yuheng Bu
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In-context watermarking (ICW) prepends an instruction to a query asking the model to embed a statistically detectable signal in its response. It thus equips LLMs with a watermarking interface that third parties can invoke without access to model internals. Its reliability hinges on the LLM following the instruction without degrading answer quality, yet how well current LLMs do so has not been measured. We introduce $\mathsf{ICWBench}$, a benchmark of three verifiable ICW instruction families, each scored on both detectability and answer quality. Evaluating 14 frontier proprietary and open-source LLMs, we find that none of the evaluated LLMs achieves both objectives across all three families. To address this, we propose a self-contained two-stage training method, requiring no distillation from a stronger model, no manual annotation, and no pre-existing ICW IF ability. The first stage, self-distillation with logits perturbation (SDLP), uses the same base LLM as both teacher and student: 

---

### [193] Verification-Aware Training for Speculative Decoding

**链接**: https://arxiv.org/abs/2608.30135
**作者**: Geonmo Gu, Byeongho Heo, HeeJae Jun, Yoohoon Kang, Sangmin Lee, Sangdoo Yun 等 (7 人)
**来源**: cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Speculative decoding accelerates large language model inference by using a draft model to generate candidate tokens, which are verified by the target model in a single forward pass. Verification proceeds sequentially and discards every position from the first rejection onward, yet existing draft training relies on token-level imitation of the target with a fixed per-position weighting that reflects neither property. We introduce Verification-Aware Training (VAT), a plug-in framework that simulates verification at every training step and turns the resulting accept and reject patterns into supervision. VAT consists of two components: (i) a verification head, a lightweight jointly trained binary classifier that supervises the draft model on whether each position survives sequential verification; (ii) verification-adaptive weighting, which replaces the fixed weighting schedule by keeping full weight up to each sample's first rejection point and re-anchoring the decay to start there. VAT mo

---

### [194] Auditing and Mitigating Privacy Leakage in Cloud-Edge Collaborative Decoding

**链接**: https://arxiv.org/abs/2608.29111
**作者**: Kejia Zhang, Tianyuan Zou, Zixuan GU, Yang Liu
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Applications such as personalized assistance and proprietary document analysis require large language models (LLMs) to generate outputs from private data. Yet powerful LLMs typically cannot be deployed on the resource-constrained devices where private data resides, and uploading private data to cloud-hosted LLMs exposes sensitive information. Recent work addresses this tension with a cloud-edge collaborative decoding paradigm, where private data are kept on the edge with a small language model (SLM) producing next-token distributions, which are fused with predictions from a cloud LLM operating solely on public data. In this paper, we systematically analyze the privacy risks of such a paradigm with a novel evaluation framework using constructed QA datasets, which show that such collaboration can expose substantial private-context information. To address such privacy leakage, we propose CoVeil, a defense mechanism which dynamically optimizes transmitted signals to suppress leakage during

---

### [195] Agentic AI uncovers conserved cross-tissue protein co-abundance programs inaccessible to single-dataset analysis

**链接**: https://arxiv.org/abs/2608.28990
**作者**: Runyu Guan, Dehao Wu, Qiqi Xie, Yang Li, Haohan Wang
**来源**: cs.AI q-bio.MN
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Protein co-abundance clusters preserved across tissues can reveal shared disease mechanisms and candidate therapeutic targets, particularly when proteins implicated in organ-confined diseases converge in peripheral or accessible tissues. However, previous cross-tissue studies have focused on biologically pre-selected tissue pairs, leaving most possible combinations and non-obvious relationships unexplored. We present an LLM-agent framework for large-scale, evidence-grounded comparison of tissue-specific protein co-abundance networks. The framework constructs tissue networks, derives pairwise consensus clusters, and integrates evidence from expression atlases, protein interaction and complex databases, pathway annotations, disease catalogues, and literature. Applied to all 820 pairwise combinations of 41 human tissues and fluids, it identified 1,833 conserved co-abundance clusters across 406 tissue pairs. Colon, synovial fluid, blood, cerebrospinal fluid, and bone marrow were the most b

---

### [196] GuardianAgent: Policy-Conditioned Risk-Adaptive Anonymization with Verified Adversarial Escalation

**链接**: https://arxiv.org/abs/2608.29251
**作者**: Ruiyi Yang, Gayathri Lihinikaduarachchi, Rahat Masood, Flora D. Salim, Salil S. Kanhere
**来源**: cs.AI cs.HC cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Privacy protection for live web traffic requires more than detecting private spans. Agent-based privacy protection systems must determine whether an outgoing action complies with the destination site's privacy policy, then apply only the level of rewriting or sanitisation justified by the residual disclosure risk. We present GuardianAgent, a policy-conditioned anonymization framework that couples structured risk assessment with verified adaptive rewriting. GuardianAgent computes risk through AMRSF (Adaptive Multi-factor Risk Scoring Formula), an explicit controller that combines policy-violation likelihood with data sensitivity, recipient transmission, purpose legitimacy, contextual basis, and policy transparency, rather than relying on an LLM to assign risk directly. This risk score determines both the allow/transform/deny decision and the initial anonymization level. For efficiency, GuardianAgent uses an evidential fast path for low-uncertainty policy matches and invokes an LLM slow 

---

### [197] Oculi: A Conversational Agentic Platform for Automated Credit Risk Analysis

**链接**: https://arxiv.org/abs/2608.28944
**作者**: Vennise Ho, Kristian Diana, Sandy Mourad, Milena Pilipovic, Vineel Nagisetty, Hossein Hajimirsadeghi
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Credit risk analysis in financial institutions traditionally requires analysts to manually write SQL queries, run statistical computations, and build visualization dashboards. This is a time-consuming workflow that limits exploration to familiar segments. We introduce \textbf{Oculi}, a conversational platform that transforms natural language questions into comprehensive credit risk analyses, complete with data queries, statistical testing, and interactive visualizations. Oculi employs a three-layer architecture that separates reasoning (LLM-powered agent), execution (Model Context Protocol tool servers), and presentation (agentic UI), enabling analysts to discover high-risk portfolio segments. Within Oculi, a new segment discovery pipeline is proposed that combines deterministic statistical methods with LLM-guided feature selection, leveraging LLM semantic domain knowledge alongside data-driven metrics to identify meaningful, actionable portfolio segments. Evaluated on a mortgage portf

---

### [198] Generating Clinical Vignettes that Preserve Cognitive Formulations

**链接**: https://arxiv.org/abs/2608.29995
**作者**: Amit Oren, Nimrod Hertz-Palmor, Dean Ariel, Guy Laban
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models can generate fluent clinical case vignettes, but fluency alone does not ensure fidelity to a specifiable clinical structure. We introduce FORMA, a theory-grounded framework that compiles a cognitive model of a disorder into a directed weighted graph, samples a person-specific configuration of that graph, and validates whether the generated vignette preserves the specified components and causal links. We instantiate FORMA on Posttraumatic Stress Disorder using the Ehlers and Clark cognitive model, generating 16,500 vignettes across 500 personas, 11 generation models, and three ablation conditions. Evaluation combines an external edge-recovery probe, two clinical experts, a scaled LLM judge, and a clinician user study with 100 licensed practitioners. The cognitive graph is recoverable from full-condition vignettes (MCC = +0.41, AUC = 0.70) but not from zero-shot generation (MCC = +0.01, AUC = 0.50). Experts rate full vignettes substantially higher than zero-shot alt

---

### [199] Beyond Surface Alignment: Grounding the Dynamics of Situational Understanding and Generative Control in LLMs

**链接**: https://arxiv.org/abs/2608.29610
**作者**: Chenghao Yang
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The current alignment tuning paradigm for Large Language Models (LLMs) prioritizes surface-level behaviors -- fluency, safety, and tonal consistency. While effective for casual chat, this thesis argues that such surface alignment masks a lack of grounding, creating models that are stylistically confident but situationally brittle. We propose a framework of Grounded Alignment, analyzing how models process context (Input) and structure generation (Output), then aligning these grounded behaviors to human needs. First, we evaluate failures in Situational Grounding. SitTest shows that despite large context windows, state-of-the-art models struggle to maintain a consistent "mental model" of a changing environment. ReCode further shows that models rely on surface heuristics rather than deep syntactic dependencies: they "read" extensive histories without truly "understanding" the evolving situation. Second, we evaluate Generative Grounding. We introduce the Branching Factor (BF) to map LLM gen

---

### [200] CoMPASS: Collaborative Molecular Property Prediction via Adaptive Small-Large Model Synergy

**链接**: https://arxiv.org/abs/2608.30674
**作者**: Wentao Li, Jiangjie Qiu, Yijun Li, Leyi Zhao, Xiaonan Wang
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Accurate molecular property prediction requires both statistical reliability and chemical reasoning. Graph neural networks can be calibrated directly on labeled assays but remain limited by the coverage of their training data. Large language models (LLMs) can compare molecular evidence and articulate chemical rationales, yet are unreliable as standalone quantitative predictors. The central challenge is therefore to determine when an LLM should influence a calibrated model and by how much. Here we present CoMPASS, a retrieval-calibrated framework for small-large model collaboration. CoMPASS retains a graph attention network (GAT) as the predictive anchor, retrieves locally relevant training molecules, provides attention-grounded evidence to an LLM, and converts its proposal into a bounded correction through an agreement-aware gate. Across six classification and two regression benchmarks, CoMPASS improves the GAT anchor in regions of correctable uncertainty while limiting LLM interventio

---

### [201] ASTRA - Agentic System for Ticket Resolution and Analysis

**链接**: https://arxiv.org/abs/2608.28790
**作者**: Shashidhar Reddy Javaji, Mohamed Trabelsi, Jin Cao, Huseyin Uzunalioglu
**来源**: cs.MA cs.AI cs.IR cs.LG cs.SE
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Technical operations teams resolve large volumes of incidents by synthesizing fragmented evidence from ticket text, historical cases, system logs, and technical documentation. Existing automation often relies on monolithic generation without explicit evidence modeling or provenance, making outputs difficult to verify when critical signals are sparse across sources. We propose ASTRA, an agentic system for ticket resolution in which a central orchestrator coordinates three specialist information-gathering agents and drives a judge-orchestrator refinement loop to produce evidence-backed troubleshooting reports. TicketSimilarityAgent retrieves relevant historical precedents through dense retrieval and LLM reranking; LogAgent distills hundreds of thousands of log lines into structured, quote-grounded findings using deterministic filtering and constrained LLM analysis; and DomainKnowledgeAgent retrieves relevant technical knowledge via the Model Context Protocol (MCP). Their outputs are tran

---

### [202] LLMODE: Aligning ODEs with LLMs via Gated Token Injection for Irregular Spatio-Temporal Forecasting

**链接**: https://arxiv.org/abs/2608.29640
**作者**: Di Zhang, Jingyang Zhang, Ziqian Wang, Chi Zhang, Yikun Ban, Ziwei Zhang 等 (7 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) have shown promise for spatio-temporal forecasting, but existing approaches often rely on regularly sampled token sequences and struggle with irregular observations because of temporal asynchrony, representation-space misalignment, and limited context windows. We propose LLMODE, a token-efficient framework for irregular spatio-temporal forecasting with a frozen LLM backbone. LLMODE first uses a graph-aware ODE encoder to reconstruct irregular graph observations as a continuous-time latent trajectory. A Fixed-Budget Perceiver Resampler then compresses this variable-length trajectory into a fixed number of dynamic memory tokens. In parallel, compact statistical descriptors are encoded and resampled into context memory tokens. A dual-source gated cross-attention module injects both memories into the frozen LLM, enabling controlled utilization of external spatio-temporal evidence. Experiments on three real-world urban datasets and two physical-dynamics benchmar

---

### [203] Spec2Twin-Chain: Orchestrating Bi-Level Optimization with LLMs for Blockchain Digital Twin Construction

**链接**: https://arxiv.org/abs/2608.30050
**作者**: Haoting Zhang, Haoxian Chen, Jiayuan Sheng, Donglin Zhan, Zeyu Zheng, David D. Yao 等 (7 人)
**来源**: cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Building a blockchain digital twin largely requires translating domain knowledge and specific system descriptions into a simulator architecture, calibrating its parameters against behavioral evidence, and validating the constructed twin. These steps are commonly performed through application-specific modeling efforts that can be difficult to reuse across systems and downstream decision problems. We consider automating this process through Spec2Twin-Chain, a framework that formulates blockchain digital-twin construction as a bi-level optimization problem. At the upper level, a large language model proposes and revises structurally admissible architectures using system specifications, behavioral evidence, and feedback from evaluated designs. At the lower level, a simulation-based optimizer calibrates the architecture-conditioned parameters under explicit objectives and guardrail constraints. The two levels iterate. The evaluated candidates at lower levels are retained in a global archive

---

### [204] Test-Time Scaling for Scientific Equation Discovery

**链接**: https://arxiv.org/abs/2608.28660
**作者**: Haowei Lin, Hubert Lim, Xiangyu Wang, Letian Huang, Di He
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Test-time scaling (TTS) improves language model reasoning by allocating additional test-time compute, but prior work mainly studies closed-ended tasks such as math and coding. We study TTS for automated equation discovery, an open-ended setting where models search over candidate equations and rely on observed datapoints for feedback. We formulate LLM-driven equation discovery as an iterative search process that unifies Best-of-N, sequential refinement, tree search, and evolution-style methods under a common compute-allocation view. To isolate allocation effects from prompt engineering and other heuristics, we compare minimal parallel controllers under fixed budgets. On LLM-SRBench equation-discovery tasks, we find that search width is the dominant allocation parameter: the best width in our sweep generally increases with the compute budget, while the population--branching split and controller choice matter less. Appropriate width selection also improves wall-clock efficiency by increas

---

### [205] Stratified Consistency Distillation for Natural Language Formalization

**链接**: https://arxiv.org/abs/2608.30258
**作者**: Zhichao Hou, Ferhat Erata, Joe Lilien, MohamadAli Torkamani
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Neurosymbolic reasoning has shown promising success in addressing complex reasoning tasks by combining large language models (LLMs) and symbolic solvers. While this approach shows promise, a fundamental challenge remains: improving the accuracy of translations from natural language to logical formulas. Current methods predominantly rely on prompt engineering, which is difficult to scale across different domains and input formats. Drawing inspiration from the success of fine-tuning in other model adaptation and alignment applications, we propose a fine-tuning-based Stratified Consistency Distillation approach: (1) We generate K logical translations per input using a frontier LLM and cluster them by semantic equivalence (2) Based on the entropy level, we apply majority voting (low entropy), LLM-as-a-Judge (medium entropy), or unification/abstention (high entropy), and (3) fine-tune a smaller model using the selected pseudo-labels. Our experiments show significant and consistent improveme

---

### [206] Lies We Can See: Joint Verbal and Non-Verbal Deception by VLM Agents in Embodied Social Interactions

**链接**: https://arxiv.org/abs/2608.30428
**作者**: Jaewoo Ahn, Junseo Kim, Hyunseo Kim, Heeseung Yun, Jaehyeon Son, Zsolt Kira 等 (7 人)
**来源**: cs.CL cs.AI cs.CV cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Strategic deception by LLM and VLM agents has emerged as a central AI alignment and safety concern. Social-deduction games (where each player holds a hidden role and communicates with others to deduce identities) serve as the canonical testbed, particularly in multi-agent settings. Existing testbeds, however, are text-only and run on a single fixed agent configuration, missing the non-verbal sensorimotor channels treated as core by deception taxonomies and leaving it ambiguous whether an observed behavior reflects the underlying model or the surrounding harness. We introduce MineAmongUs, a 3D multimodal Among Us sandbox where imposter agents must deceive crewmates through joint verbal and non-verbal action. We also propose ARIA, a configurable VLM-agent harness that exposes five cognitive-component ablation axes; and an atom- and arc-level annotation scheme grounded in deception taxonomies and operationalized at scale by an LLM-as-a-Judge reaching near-human atom-labeling agreement. Em

---

### [207] TopoCompress: Long Context Compression via Graph-Wired Semantic Trajectories

**链接**: https://arxiv.org/abs/2608.30811
**作者**: Daniel Agyei Asante, Yang Li
**来源**: cs.CL cs.LG
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-context compression is essential for reducing the cost and latency of large language model inference. However, existing methods can fragment important evidence, require additional training or alignment, and often depend on the target model for effective compression. We introduce TopoCompress, a training-free and model-agnostic framework that compresses long contexts by selecting coherent semantic spans. TopoCompress first scores each span using dense and lexical query relevance together with semantic acceleration. It then constructs a hybrid graph that connects spans based on semantic similarity and sequential adjacency, and propagates the query-guided relevance scores over the graph. Across five long-context tasks-HotpotQA, 2WikiMQA, MuSiQue, Qasper, and MultiFieldQA-en-TopoCompress consistently outperforms strong compression baselines. Notably, TopoCompress achieves performance comparable to the strongest baseline while using a 4x smaller compression budget, and provides a 1.41x

---

### [208] When Can We Work in Embedding Space? What Text Embeddings Preserve

**链接**: https://arxiv.org/abs/2608.31059
**作者**: Simon Freyaldenhoven
**来源**: econ.EM cs.CL stat.ML
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> When do text embeddings work as inputs to empirical analysis? Their use rests on an assumption: that we can trade text for its low-dimensional embedding, and lose little in doing so. I make that assumption precise under a generative model in which documents are mixtures of latent topics. I study two uses---clustering units in embedding space and controlling for high-dimensional text. A cluster of embeddings is a set of documents with similar topic mixtures; controlling for the embedding is equivalent to controlling for the topic mixture, so validity reduces to whether that mixture captures the confounding. In an application to 363 U.S. metropolitan areas, embedding-based clusters of LLM-generated economic descriptions recover interpretable economic archetypes and separate local employment dynamics more sharply than clustering on model residuals, or on a curated set of industry and demographic covariates.

---

### [209] Calibrating Small Language Models for Claim Check-Worthiness Detection

**链接**: https://arxiv.org/abs/2608.30731
**作者**: Pratuat Amatya, Venktesh Viswanathan, Vinay Setty
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Assessing claim check-worthiness is an essential first step in automated fact-checking pipelines. This work is motivated by a real deployment challenge at an early-stage startup: running large language models (LLMs) over every incoming claim is cost- and latency-prohibitive, yet smaller models sacrifice accuracy. We propose NN-PPI, a pointwise extension of Prediction-Powered Inference (PPI) that calibrates model predictions at inference time as a lightweight post-hoc layer, without re-training the underlying model. NN-PPI achieves weighted F1 gains ranging from 12% to 33.80% depending on the size and performance of the baseline model, bringing SLMs on par with larger LLMs. Beyond few-shot SLMs, NN-PPI further improves a production-deployed fine-tuned model, demonstrating that residual calibration is complementary to supervised fine-tuning. By recovering LLM-level accuracy from models that are an order of magnitude cheaper to serve, it makes accurate check-worthiness detection substanti

---

### [210] FLM: Frequency-Aware Language Models for Generative Image Compression

**链接**: https://arxiv.org/abs/2608.28687
**作者**: Jiarun Chen, Kejun Wu, Li Li, Chengtao Cai, Zhengguo Li, Chia-Wen Lin
**来源**: cs.CV
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Generative models have significantly improved the performance ceiling of image lossy compression at low bitrates by exploiting learned priors. However, the generated textures and semantic details may deviate from the source content, thereby affecting the fidelity of image reconstruction. To solve these challenges, we propose FLM, a frequency-aware language model that improves compression efficiency through frequency-domain probabilistic modeling while retaining deterministic reconstruction. At the encoder, the input image is transformed into quantized DCT coefficients, which are organized into discrete sequences using macroblock-based coefficient tokenization. FLM then performs next-coefficient prediction to autoregressively estimate token-wise conditional probability distributions for arithmetic coding, thereby generating a compact bitstream. At the decoder, the LLM and arithmetic decoder jointly recover the frequency-domain data, followed by inverse transformations for image reconstr

---

### [211] TRIPPULSE: Multi-Agent Travel Planning with Review-Grounded Reasoning

**链接**: https://arxiv.org/abs/2608.30924
**作者**: Priyanshu Karmakar, Borru Vijay Sai, Shubhojit Mallick, Abhik Jana, Shreya Ghosh, Manish Gupta
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Travel itinerary generation requires balancing strict spatio-temporal constraints with human preferences. Existing LLM-based planners mainly rely on structured attributes and pre- defined traveler personas, but real travel deci- sions are often shaped by reviews that reveal experiential factors such as comfort, safety, ser- vice quality, ambiance, crowding, and hidden risks absent from structured databases. Incor- porating such review information is therefore critical to realistic, user-centric itinerary gen- eration. We propose TRIPPULSE1, a multi- agent framework for review-grounded travel planning. Instead of relying on a monolithic planner (and face context and reasoning bot- tlenecks), TRIPPULSE2 decomposes itinerary generation into specialized agents (each op- erating over localized contexts) for accom- modations, transportation, meals, attractions, and events, coordinated through a global or- chestrator with scheduling mechanisms that enforce temporal and budget feasibility. We 

---

### [212] Quantitative Evidence Mining for Plausibility-Aware Biomedical AI

**链接**: https://arxiv.org/abs/2608.30393
**作者**: Negin Sadat Babaiha, Stefan Geissler, Marie-Christine Simon, Martin Hofmann-Apitius, and Marc Jacobs
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Biomedical artificial intelligence (AI) systems increasingly extract, organize, and reuse scientific claims from literature, clinical trials, and regulatory documents. But automatic extraction alone does not make a claim reliable evidence: a claim becomes useful only when it can be traced to its source, linked to the quantitative details that support it, and read within its biomedical context and uncertainty. This matters as large language models (LLMs) and increasingly autonomous systems drive evidence synthesis, knowledge graph (KG) construction, and decision support. Many text-mining and LLM pipelines remain relation-centric: they capture entities and relations such as Drug--TREATS--Disease, but drop the dose, effect size, population, comparator, uncertainty, and conditions under which a claim holds. Such relations can look actionable yet remain hard to verify, compare, or reuse. In this perspective, we argue for a shift toward quantitative evidence mining---extracting values, units

---

### [213] A Comprehensive Survey on Linguistic Steganography: Methods, Countermeasures, Evaluation, and Challenges

**链接**: https://arxiv.org/abs/2608.29077
**作者**: Ruiyi Yan, Chenhui Chu, Zhongliang Yang, Yugo Murawaki
**来源**: cs.CR cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Linguistic steganography hides secret messages in natural language text. Large language models (LLMs) have reshaped the field, but a systematic account of how these scattered advances collectively reshape the field in this new era is still missing. We provide one along four axes: 148 steganographic methods, 60 linguistic steganalysis countermeasures, 23 evaluation metrics, and 9 open challenges, each with taxonomies, reviews, and adoption analyses. Cutting across these axes, we identify five specific paradigm shifts in the LLM era: (1) from covertext modification to prompt-only generation, (2) from heuristic to provable security, (3) from white-box symmetric LMs to black-box or asymmetric access, (4) from security-centric designs to joint optimization, and (5) from text-quality concerns to engineering issues. The survey aims to serve as both a reference and a roadmap for practical and responsible linguistic steganography in the LLM era.

---

### [214] Hidden Threat in Synthetic Data: Covert Targeted Bias Injection through Benign Text

**链接**: https://arxiv.org/abs/2608.30619
**作者**: Minkyung Cho, Jihyo Kim, SeungWoo Song, Junghun Yuk, Minjoon Kee, Hoyun Song 等 (7 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Synthetic data is increasingly used to train large language models (LLMs), yet its security implications remain poorly understood. Prior work on subliminal learning suggests that models can inherit behavioral traits from seemingly unrelated training data. In this work, we investigate whether such mechanisms can be exploited to inject targeted social biases into aligned models through semantically benign synthetic data. We construct a pipeline in which a misaligned teacher model generates filtered synthetic datasets across domains such as creative writing and code generation, which are then used to fine-tune aligned student models. Our experiments show that benign-looking synthetic data can act as a covert channel for transmitting targeted biases while largely preserving the student model's general task capabilities. These results reveal a previously underexplored security risk in synthetic data-driven LLM training pipelines and highlight the need for improved safeguards. As one possibl

---

### [215] Faithfulness Is Not Free: Auditing Offline KV-Cache Quantization in Retrieval-Augmented Generation

**链接**: https://arxiv.org/abs/2608.30996
**作者**: Atta Ul Asad, Ahsan Bilal, Muhammad Ali, Muhammad Haseeb, Dean F. Hougen
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Retrieval-augmented generation systems can precompute and store key-value caches of retrieved documents to avoid re-encoding context at every query. Quantizing these caches further reduces storage, but no prior work asks whether compression damages faithfulness, whether responses remain grounded in the retrieved evidence. Faithfulness and accuracy are not equivalent: a model can produce a correct answer that is no longer supported by the context it was given. We evaluate Qwen2.5-7B-Instruct under INT8 and INT4 quantization on RGB and HotpotQA, measuring both accuracy and faithfulness with a hallucination detector, NLI entailment, and an LLM judge. INT8 is near-lossless across both metrics. INT4 reduces accuracy and, more critically, even among answers that remain factually correct, over 90% of faithfulness changes are negative, i.e., accuracy metrics are blind to this regression. The harm grows under noisy retrieval and with more retrieved chunks. Faithfulness must be audited before co

---

### [216] AutoScientist-Quant: Self-Evolving Coding Agents for Automatic Research in Quantitative Investment

**链接**: https://arxiv.org/abs/2608.28632
**作者**: Zongqian Li, Yaoyiran Li, Yaohui Guo, Ming Zhang, Nigel Collier, Eugene Ie
**来源**: cs.AI cs.CL cs.LG
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model agents can discover alphas, yet current methods have three weaknesses. The search cannot adapt during the run, automation usually ends at alpha generation while library selection and model choice stay manual, and alpha discovery can read the test window through loop feedback or code problems. We present AutoScientist-Quant, a self evolving search process that regards quantitative research as one budgeted search problem. A single controller conditions every decision on the remaining budget, choosing at each round whether to improve, combine, pivot, or stop, which node to expand, how many alphas to generate, and how to retrieve past trajectories from the shared memory. The same core then selects from the library and tunes the model, closing the loop from hypothesis to deployable strategy. We also review the evaluation pipeline reused from prior work, fix two lookahead problems, and keep the feedback window disjoint from the held out test window, so every comparison t

---

### [217] Geometry of Divergence: Tracking Hidden-State Trajectories for Adaptive Multi-Turn Reasoning

**链接**: https://arxiv.org/abs/2608.30650
**作者**: Jie Liang, Zhengxin Yu, Hamid Nasiri, Peter Garraghan
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents need to sustain goal-consistent reasoning across long multi-turn interactions under strict resource constraints. However, as the multi-turn context accumulates, it can destabilize the underlying LLM's internal representation of task-relevant information from earlier turns, blurring the boundary between constructive reasoning and representation drift. We formulate multi-turn reasoning as a hidden-state trajectory of the underlying LLM that is characterized via two complementary signals: temporal curvature that captures the directional consistency of turn-to-turn updates, and variance slope which measures the expansion or contraction of the exploration space. Across four tasks and three underlying LLMs, we observed that these geometric signals distinguish between correct and incorrect episodes prior to completion. We further decompose each episode into three-action chains formed from four actions (Read, Write, Respond, Transfer) and show that separability is action-dependent, 

---

### [218] Compression-Aware Abstention: Teaching LLMs to Refuse When KV-Compression Masks Remove Answer Evidence

**链接**: https://arxiv.org/abs/2608.29934
**作者**: Mohammadali Khodabandehlou, Bhaskar Krishnamachari
**来源**: cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> KV-cache compression reduces LLM inference memory by evicting context tokens, but when the evicted tokens contain answer-bearing evidence, the model may hallucinate instead of recognizing that the compressed context is insufficient. We address this failure from a behavioral perspective: to our knowledge, this is the first work to formulate compression-aware abstention as a learning problem, in which a model learns to answer when supporting evidence survives compression and abstain when it does not. We construct supervision from compressor survival masks and tight answer-bearing spans, labeling examples as Confident when evidence survives and Abstain when it is removed. A 10.1M-parameter LoRA adapter trained on ~2.6K MuSiQue 2-hop QA examples reduces base-model hallucinations by 97% under prompt-style truncation while preserving correct answering on evidence-retaining examples. Unlike prompt-only abstention baselines, which over-abstain on many answerable high-retention examples, the tr

---

### [219] On the Recoverability of Private Information Unlearning in Large Language Models

**链接**: https://arxiv.org/abs/2608.29943
**作者**: Shicheng Hu, Runzhi Tian, Ziqiao Wang, Yongyi Mao
**来源**: cs.LG cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) can memorize sensitive information, raising serious privacy concerns. Machine unlearning offers a potential solution to remove such information, but it remains unclear whether existing methods truly erase it or merely hide it within the model. A key challenge is quantifying the persistence of sensitive data under a unified evaluation framework. To address this, we construct a synthetic dataset containing fake private information and propose a white-box auditing framework to systematically assess whether claimed-forgotten information is genuinely removed. Using this framework, we evaluate five existing unlearning methods and find that a simple "inverse greedy" decoding -- selecting the least likely token at each step -- can recover supposedly forgotten private information. Our results reveal that current unlearning approaches often fail to fully eliminate sensitive information, highlighting the need for more reliable methods to ensure privacy in deployed LLM

---

### [220] Item-Mean Surrogates: Why Richer Persona Data Fail to Improve LLMs as Human Surrogates

**链接**: https://arxiv.org/abs/2608.29455
**作者**: Daehwan Ahn, Chengfeng Mao, Dokyun Lee
**来源**: cs.CL cs.CY cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLMs are increasingly used as human surrogates, often on the premise that richer persona data could make them substitutes or exploratory tools for specific individuals. We test this premise across four datasets covering more than 400,000 participants and more than 6,000 survey items and experimental outcomes. LLMs perform well at the aggregate level: their average responses closely align with average human responses to the same items. But this success largely reflects predicting each item's average human response. Once each item's human mean is removed, LLM predictions explain only 3.05% of the remaining respondent-specific variation, far below the 53.6% human test-retest benchmark. Richer personas, model variants, and fine-tuning do not close this gap. In variance analyses, once item means are removed, the reliable remaining signal is person-by-item. It captures how a respondent departs from the mean on a particular item and is about 8.9x larger than the stable person effect. Persona 

---

### [221] Toward Latent Language Model Skills Steering and Optimization: An Empirical Study

**链接**: https://arxiv.org/abs/2608.29459
**作者**: Xunyi Jiang, Junda Wu, Yuxin Xiong, Sheldon Yu, Tong Yu, David Arbour 等 (9 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Skills, as a useful abstraction for the procedural capabilities of large language models (LLMs), capture how models perform structured, multi-step reasoning and program execution. Existing approaches typically treat skills as explicit, surface-level constructs specified through prompts or programs, leaving open the question of how such procedural capabilities are represented inside the model and whether they can be manipulated as structured objects in latent space. In this empirical study, we investigate whether procedural LLM skills can be represented as directions in activation space and whether vector-space operations over these directions can express skill-level behaviors. We find that procedural skills admit a vector-space representation: individual skill directions can be activated to shift model behavior; independently extracted directions can compose to form higher-level skills. Contrastive directions yield context-conditioned algorithmic personalization and optimization trajec

---

### [222] Small Language Models as Judges for Rubric-Based Reinforcement Learning

**链接**: https://arxiv.org/abs/2608.30005
**作者**: Fengyu Xie, Yilun Zhao, Bingsen Chen, Arman Cohan, Chen Zhao
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Rubric-based reinforcement learning extends RL beyond tasks with exact answers or rule-based verifiers by scoring responses against instance-specific criteria. However, this makes reward computation expensive: training requires repeated rubric judging, often with proprietary APIs or local generative LLM judges with 7B parameters or more. We study whether smaller language models can serve as efficient and reliable rubric-based judges. To make this question measurable, we construct PointRubric and RaR-Science-Static, two pointwise rubric-based evaluation datasets with instance-specific criteria and itemwise satisfaction labels. We compare three ways of extracting criterion-level judgments from small models: Generative verdicts, Yes/No Logprob margins, and Probe judges. Across both datasets, the Qwen3-1.7B Probe judge achieves the strongest criterion-level agreement among these methods, outperforming Generative and Logprob judges. Used as a GRPO reward model, it trains a policy from 0.232

---

### [223] Toward Cultural Alignment: Human-Centered Evaluation of Multimodal AI Stories Across Five African Communities

**链接**: https://arxiv.org/abs/2608.29209
**作者**: Millicent Ochieng, Felermino D. M. A. Ali, Elizabeth A. Ankrah, Najeeb Gambo Abdulhamid, Migisha Boyd, Stephanie Nyairo 等 (10 人)
**来源**: cs.CL cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In this paper, we examine how well AI-generated multimodal stories align with the lived practices, relationships, language, values, and visual expectations of the communities they represent. We conduct a community-grounded mixed-methods evaluation with 19 culture representatives across five African communities, combining quantitative annotations with qualitative focus group discussions. We find that cultural alignment depends not simply on recognizable cultural markers, but on how those markers fit social, linguistic, procedural, and visual context. From these evaluations, we develop a taxonomy of cultural alignment comprising five broader cultural marker categories and eight recurring mechanisms of misalignment. We additionally evaluate five multimodal LLM judges to examine whether automated evaluation can approximate community-grounded judgments at scale. Judge reliability and score calibration vary substantially across communities, with no single judge performing consistently across

---

### [224] The Hallucination Signal Is a Mean Shift: Why Simple Probes Suffice

**链接**: https://arxiv.org/abs/2608.28930
**作者**: Jungseob Lee, Jaehyung Seo, Heuiseok Lim
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Hidden-state probes effectively detect LLM hallucinations, but the geometry of the signal remains poorly characterized, driving increasingly complex probe architectures. Across three 7B-scale models and three datasets in a paired-example paradigm, we find the signal overwhelmingly dominated by a single mean-shift component, and removing this direction collapses detection to chance. Shrinkage linear discriminant analysis closes about 73% of the gap between 1D and full-dimensional classifiers, so apparent architectural complexity largely reflects high-dimensional covariance estimation difficulty rather than exploitable non-linearity. A simple L2-regularized logistic regression (0.952 AUROC) bounds or outperforms twelve controlled architectural alternatives, and our multi-layer aggregation exceeds CLAP cross-layer attention probing under matched paradigm. Because the signal spans a contiguous layer band, LayerMix aggregates it to match oracle-layer performance without oracle access. Our c

---

### [225] Cloud and On-Premises Deployment of Uzbek Legal RAG via Targeted Retriever Fine-Tuning

**链接**: https://arxiv.org/abs/2608.29284
**作者**: Tatul Danielyan, Mariam Avetisyan, Hrant Davtyan
**来源**: cs.CL cs.IR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Deploying large language models for legal question answering raises challenges that general-purpose leaderboards do not capture, particularly for low-resource languages and under hard operational constraints. We report on building and operating a retrieval-augmented (RAG) legal assistant for Uzbek that must run in two regimes: a managed cloud service that maximizes answer quality within a per-token cost ceiling, and an on-premises deployment for clients whose legal data may not leave their infrastructure, restricting us to open-weight models on limited local hardware under latency constraints. Because no evaluation existed for this setting, we build two domain benchmarks: a retrieval benchmark of 178 expert-annotated legal queries with gold provision spans, and an end-to-end benchmark of 504 expert-curated question--answer pairs scored by an LLM judge whose ratings we validate against human judgments and against an independent-family judge. Applying these benchmarks under each regime, 

---

### [226] Do large language models scrutinise what they review? A multimodal audit of scoring calibration, error detection, and author-identity effects

**链接**: https://arxiv.org/abs/2608.28626
**作者**: Emad Alharbi
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly used to generate peer reviews, prompting examination of their capacity for critical evaluation. This study evaluates two multimodal LLMs, Qwen2.5-VL-72B and Pixtral-Large-124B, as reviewers across 165 submissions to the 2026 International Conference on Learning Representations, a venue that postdates both models' training cutoffs. Manuscripts were presented to both models with author identities blinded, replaced with high-prestige affiliations, or replaced with low-prestige affiliations, and in either text-only or text-with-figure format. Additionally, 145 verifiably detectable errors were inserted into 55 manuscripts to assess error identification under natural and verification-oriented prompts. Across all manuscript groups, including rejected submissions, LLM scores ranged from 7.0 to 8.1, whereas human mean scores ranged from 3.4 to 6.8. The models detected 12.1\% of the verified errors under natural prompting, and a one-sentence verific

---

### [227] Do VLMs Share Safety Neurons Across Modalities?

**链接**: https://arxiv.org/abs/2608.30750
**作者**: Jiaxuan Li, Jiahao Zhang, Duc Minh Vo, Huy H. Nguyen, Pride Kavumba, Koki Wataoka
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Vision-language models (VLMs) can comply with harmful requests delivered through images, even when their LLM backbones would refuse the same content in text. While prior work characterizes these jailbreaks empirically or at the representation level, how visual inputs perturb safety pathways at the neuron level remains uncharted. We close this gap with a causal, neuron-level analysis of safety mechanisms in 10 VLMs. We propose a two-stage detection pipeline with iterative ablation that accounts for self-repair, and introduce two modality-isolated benchmarks, ViSafe-Detect and ViSafe-Eval, which decouple visual and textual safety signals. Our analysis reveals: (i) Text safety in VLMs is localizable: $\sim$88 neurons ($<$0.01%) whose targeted ablation substantially reduces refusal. (ii) Text safety neurons constitute the dominant refusal pathway: ablating them is the only intervention that consistently and substantially reduces refusal across all models. (iii) Visual safety is high-dimens

---

### [228] En-ViMedNER: An English-Vietnamese Parallel Biomedical Corpus with UMLS Semantic Type Annotations

**链接**: https://arxiv.org/abs/2608.29890
**作者**: Nhu Vo, Phuong Nguyen, Nu Uyen Phuong Le, Inigo Jauregi Unanue, Dung D. Le, Massimo Piccardi 等 (7 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Biomedical Named Entity Recognition (NER) is fundamental to healthcare AI applications, including clinical decision support and medical information extraction. While corpora with Unified Medical Language System (UMLS) annotations, such as MedMentions, have driven progress in English biomedical NER, no comparable resource exists for Vietnamese. This paper presents En-ViMedNER, the first English-Vietnamese parallel biomedical NER corpus annotated with UMLS semantic types, which are language-neutral codes providing a shared cross-lingual label space and ensuring direct comparability with existing UMLS-based resources. The corpus contains 4,392 PubMed abstract pairs, 44,892 English-Vietnamese sentence pairs, and 202,949 aligned entity-mention pairs across 21 semantic types adapted from the MedMentions ST21pv dataset. To balance quality and scalability, we have constructed the corpus through automatic translation, expert post-editing, LLM-assisted label projection, and human verification an

---

### [229] Integrating adaptive human behavior into epidemic models with large language models

**链接**: https://arxiv.org/abs/2608.29535
**作者**: Yicheng Mao, Haoyang Li, Rob Deardon, Hongru Du
**来源**: physics.soc-ph cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Infectious disease transmission is shaped by patterns of human interaction, which adapt as epidemic conditions change. Capturing these context-dependent behaviors remains a fundamental challenge for epidemic models. Here, we recast this challenge by using large language models (LLMs) to represent adaptive human behavior within mechanistic epidemic models. We operationalize this idea through Generative Adaptive Behavioral Layer for Epidemics (GABLE), which adapts LLMs to infer behavioral responses to epidemic and policy conditions and translates them into age-structured contact matrices coupled to a mechanistic epidemic model. Applied to COVID-19 in France, GABLE reproduced responses in population mixing and age-specific contact structures that remained epidemiologically informative. In short-term forecasting, LLM-generated contact matrices outperformed mobility-driven matrices derived from real-world mobility data, with the largest gains at longer horizons. GABLE also extends beyond fo

---

### [230] AdaPath: Query-Adaptive Path-Finding via Path-Bank for Multi-Hop Implicit Biomedical KGQA

**链接**: https://arxiv.org/abs/2608.30556
**作者**: Jun Hyeong Kim, Dongki Kim, Yinhua Piao, Sung Ju Hwang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Path-finding over knowledge graphs has become an effective way to ground LLM reasoning on multi-hop questions. However, biomedical QA introduces two distinct challenges that general-domain methods are not designed for: (i) queries do not expose intermediate reasoning and can be answered through multiple valid pathways, and (ii) biomedical knowledge graphs are densely connected, so path-finding methods easily take wrong turns. To address these challenges, we propose AdaPath, a path-finding framework that retrieves query-adaptive meta-paths from Path-Bank, which captures both query semantics and biomedical knowledge graph structure. AdaPath provides the missing cues in biomedical queries while effectively pruning dense knowledge graph neighborhoods during multi-hop reasoning. We further release BioStrat-QA, a biomedical KGQA benchmark that stratifies multi-hop queries by how much intermediate reasoning they expose. Across biomedical KGQA benchmarks, AdaPath consistently outperforms basel

---

### [231] Learning to Reason and Use Tools through Unsupervised Fine-Tuning in Task-Oriented Dialog Systems

**链接**: https://arxiv.org/abs/2608.30426
**作者**: Markel Ferro and Oier Lopez de Lacalle
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Current dialogue systems struggle with dynamic information retrieval, often leading to hallucinations and lower response accuracy. We address this by adapting the ReAct framework for Task-Oriented Dialogue, enabling Large Language Models (LLMs) to access external knowledge and produce factual responses. Mainly, we propose an unsupervised fine-tuning pipeline that harvests reasoning trajectories via in-context learning inference. High-quality samples are filtered using an LLM-based judge to construct a robust training set. This is enhanced by a unsupervised self-improvement loop, where improved checkpoints generate increasingly better trajectories for subsequent fine-tuning iterations. Experiments on the SIMMC dataset demonstrate that ReAct-based systems outperform baselines due to superior reasoning and tool use. Notably, our fine-tuned 8B model surpasses a 70B in-context system. Finally, we present an error analysis, impact of scene complexity, and cross-domain generalization.

---

### [232] The Fragility of Jailbreak Robustness Across Operational States

**链接**: https://arxiv.org/abs/2608.30748
**作者**: Yuna Park, Hwang Youn Kim, Yujin Kim, Won Woo Ro, Suhyun Kim, Jae-In Hwang
**来源**: cs.CR cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Existing jailbreak evaluations typically characterize robustness using a single attack success rate (ASR) measured in a default configuration (the vanilla state). However, user-LLM interactions can induce diverse operational states beyond the vanilla state. In this work, we find that jailbreak robustness is highly fragile to operational-state variation: even when the attack remains fixed, changing only an ordinary system prompt not designed to affect safety can dramatically alter attack success rates. We systematically investigate this phenomenon across seven aligned models and three representative jailbreak attacks, observing substantial differences in ASR between vanilla and non-vanilla operational states. In one case, ASR increases by up to 56 percentage points (2% to 58%) solely due to a change in operational state. Remarkably, these increases occur even for attacks originally designed and optimized under vanilla-state evaluation. We further show that state-dependent robustness var

---

### [233] ScienceArena: Benchmarking LLMs on Latest Scientific Olympiad Competitions

**链接**: https://arxiv.org/abs/2608.30517
**作者**: Guangxiang Zhao, Qilong Shi, Xusen Xiao, Wenpu Liu, Yaoming Li, Linfeng Hao 等 (10 人)
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Benchmark saturation and data contamination increasingly obscure genuine scientific reasoning in frontier LLMs. We introduce \textsc{ScienceArena}, an olympiad-style benchmark from thirteen public science competitions in physics, chemistry, and biology, including IPhO and IChO 2025--2026, IBO 2023, USAPhO 2026, and USNCO 2025. Its open-ended, multi-step problems use process-credit rubrics, making faithful scoring difficult. We build ScienceArena through an expert-audited digitization pipeline that converts official exams, figures, solutions, and rubrics into structured items verified by olympiad medalists. To scale evaluation beyond costly human grading, we calibrate LLM-as-judge against medalist ground truth on archived answers from five models across IPhO and IChO; two strong judges stay within one point of expert total scores. Medalist notes show that failures often stem from visual grounding, structure fidelity, and global problem control rather than missing terminology. Evaluating

---

### [234] DIASENTINEL: An Auditable Multi-Agent System for Guideline-Grounded Diabetes Risk Screening

**链接**: https://arxiv.org/abs/2608.31128
**作者**: Yung Wei Shueh, Zhi-Jie Chen, Chia-Hsuan Hsu, Hsin-Ling Hsu, Donghua Zhang, Chenwei Wu 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) offer promising clinical decision support but remain vulnerable to hallucinated facts, unsupported recommendations, and citation errors. We present DIASENTINEL, a fully on-premise multi-agent system for one-year type 2 diabetes mellitus (T2DM) risk screening and guideline-grounded report generation from electronic health records (EHRs). The system integrates calibrated risk prediction, deterministic clinical signal extraction, Reciprocal Rank Fusion over American Diabetes Association (ADA) guidelines, and a hybrid verification layer combining rule-based checks with LLM entailment. The demonstration provides a real-time batch-screening dashboard and an interactive patient report interface with cited recommendations, verification results, and raw EHR comparison. DIASENTINEL demonstrates a practical framework for reliable, auditable, and privacy-preserving LLM-based clinical decision support.

---

### [235] Evaluating the Capabilities of LLMs for Persuasive Dialogue

**链接**: https://arxiv.org/abs/2608.29738
**作者**: Jordan Robinson and Angus R. Williams and Katie Atkinson and Anthony G. Cohn
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) can generate apparently highly persuasive text, but does sounding persuasive mean arguing well? We introduce \textsc{Persuasio}, a multi-agent dialogue platform grounded in a formal argumentation-based theory of persuasion dialogues that adjudicates logical winners during free-text debates. Using this system, we generated 192 debates on a UK political topic between humans and LLMs, and evaluated 22 interlocutors through both automated adjudication and 9,702 crowdsourced pairwise judgements across 1{,}386 annotation instances. We observed a consistent decoupling between subjective and formal persuasiveness: LLMs dominated the subjective ranking yet performed substantially worse under argumentation-theoretic adjudication, where humans remained competitive. Multi-agent and retrieval-augmented variants further widened this divergence. These findings reveal a systematic gap between rhetorical fluency and formal argumentative strength in LLM-based persuasive dial

---

### [236] Attribute-Based Activation Steering of LLMs for Group-Specific Explanation Generation

**链接**: https://arxiv.org/abs/2608.29215
**作者**: Leandra Fichtel, Janek Prange, Henning Wachsmuth
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> To effectively enable people to understand new topics, explanations should be tailored to their backgrounds and abilities. So far, prompting alone has been shown to be insufficient for creating such explanations and other computational methods are missing. Therefore, this paper investigates whether LLMs can be steered to generate explanations that are tailored to a specific group of people. To this end, we propose an approach that first identifies group-specific attributes in terms of explanatory style and knowledge of a specific target group. Building on activation engineering, it then computes attribute-based steering vectors and adds them to the internal activations of an LLM during inference to enable a fine-grained steering. In our experiments, we assess the steering effectiveness of our approach in terms of specificity and factuality of the generated explanations. Additionally, we evaluate the explanations in a study with human experts from different target groups. Compared to pr

---

### [237] Beyond Surface Forms: Symbolic Edits as a Test for Logical Reasoning with LLMs

**链接**: https://arxiv.org/abs/2608.30256
**作者**: Ramya Keerthy Thatikonda, Wray Buntine, Ehsan Shareghi
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Logical reasoning with large language models (LLMs) is a critical capability, as it reflects a system's ability to correctly deduce hypotheses from a given context using faithful deductive processes. However, LLM reasoning has often been shown to be sensitive to small surface-level variations in problem formulation, raising questions about whether models truly follow the underlying logical structure. Studying this behavior is challenging because the symbolic components of logical problems, such as operators and predicates, are difficult to systematically manipulate in natural language. We introduce a tool-driven framework for generating controlled, label-preserving edits to logical reasoning problems. Our method operates on symbolic representations of first-order logic and constraint satisfaction problem tasks, enabling targeted modifications to logical operators and other structural components before translating them back into natural language. Using this framework, we evaluate variou

---

### [238] Check The Scoreboard: An Analysis of Scoring Schemes on Multiple-Choice Evaluation

**链接**: https://arxiv.org/abs/2608.29887
**作者**: Nishant Balepur, Paiheng Xu, Wei Ai, Eunsol Choi, Rachel Rudinger, Jordan Boyd-Graber
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multiple-choice question answering (MCQA) benchmarks in NLP use number-right scoring (accuracy), but in educational testing, the scoring scheme, the combination of the response mode models follow and the rule for grading responses, is a key design choice that dictates which abilities to reward. We examine how alternatives to number right change what MCQA measures with six education-inspired schemes that assess abilities beyond accuracy: distractor elimination, abstention, confidence calibration, and self-correction. On LLM benchmarks, these schemes: 1) shift rankings of 31 LLMs beyond rephrased number right prompts; 2) better predict the LLMs users prefer in LLM Arena; and 3) reveal distinct model capabilities, like that GPT-5 rarely abstains and readily self-corrects, while weaker open-weight models often abstain and hesitate to eliminate choices. Given the benefits of alternative scoring schemes, we discuss ways to extend them to tasks beyond MCQA.

---

### [239] JudgePanel: A Compact Judge with Panel Deliberation via Adaptive Multi-Reward Reinforcement Learning

**链接**: https://arxiv.org/abs/2608.29168
**作者**: Yiyue Qian, Shinan Zhang, Huan Song, Hannah Marlowe
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The LLM-as-a-Judge paradigm has emerged as a scalable alternative to human evaluation. However, single-model judges are limited by their inherent model biases, while multi-agent evaluation protocols that mitigate this through diverse deliberation are prohibitively expensive at inference time. To this end, we propose \textbf{\modelname}, which equips a compact \underline{Judge} model with multi-agent \underline{Panel} deliberation capability. Specifically, we first train on panel deliberation traces from an ensemble of strong evaluators, capturing structured patterns of discussion, disagreement, and resolution. To further improve judgment quality beyond SFT, we introduce \textit{AdaReward}, an adaptive multi-reward RL algorithm that dynamically rebalances reward component weights as different objectives saturate at different rates during RL training. For practical deployment, we further design a lightweight domain specialization module for rapid adaptation to new evaluation domains with

---

### [240] CHASE: How Content Ecosystems Are Reshaped When Ranking Is the Only Target

**链接**: https://arxiv.org/abs/2608.30466
**作者**: Qianwen Gao, Zichang Su, Yiwen Hou, Arlen Kumar, Leanid Palkhouski
**来源**: cs.AI cs.IR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Generative Engine Optimization (GEO) is increasingly used to improve content visibility in LLM-based retrieval systems, yet its population-level effects under repeated optimization remain poorly understood. We introduce Content Homogenization under rAnking Signal Exploitation (CHASE), a controlled simulation framework for studying how content ecosystems are reshaped when creators repeatedly adapt documents to an LLM ranking signal. We use ranking as a proxy for source visibility and validate this abstraction against citations in grounded generated responses, obtaining a rank-citation AUC of 0.853 $\pm$ 0.093 across six domains. CHASE then iterates ranking, feature discrimination, rewriting, and evaluation over 20 rounds across different domains. Quality-ranking alignment decreases in all six domains: from R0 to R20, the change in Spearman's rho ranges from -0.107 to -0.018, with a mean change of -0.068, which means documents closer to the ranking feature profile become less aligned wit

---

### [241] PUFFER: Incremental Fuzzy Deduplication for Continuously Evolving Corpora

**链接**: https://arxiv.org/abs/2608.28622
**作者**: Xiao Yang, Erik Edward Aldape, Beren Millidge
**来源**: cs.DB cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model training corpora grow through successive, often redundant releases, so each release must be deduplicated against both itself and the accumulated history. At trillion-token scale, this requires incremental ingestion, bounded resident memory, deterministic retry, and dataset-scoped lifecycle control without repeated corpus-wide rebuilding. We introduce PUFFER (Provenance-aware Updatable Fuzzy Filtering for Evolving Repositories), a MinHash-LSH fuzzy-deduplication pipeline built around two design choices. First, PUFFER stores each LSH band as immutable, dataset-tagged, memory-mapped sorted segments, enabling exact historical band-key membership checks without RAM proportional to corpus size. Second, T-fanout tiered compaction periodically merges segments to control screening fanout, trading lower query cost against additional index-maintenance writes while preserving membership decisions. Across N ingested keys and K equal-sized releases, PUFFER's cumulative maintenan

---

### [242] CDEP Agent: Connecting Meteorologically Detected Temporal Compound Events to Real-World Documentary Evidence

**链接**: https://arxiv.org/abs/2608.28628
**作者**: Zhuoran Li, Weiyi Kong, Boer Zhang
**来源**: cs.AI cs.CY physics.ao-ph
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Compound drought-to-extreme-precipitation (CDEP) events are recognized in climate science as a growing driver of extreme impact, but whether this recognition carries over into real-world early warning and post-event documentation is unknown, so a meteorologically real CDEP event may pass with neither advance warning nor any later record. Here we present CDEP Agent, an auditable LLM-agent framework that tests this mismatch directly by linking CDEP candidates detected from meteorological reanalysis to real-world hazard and impact evidence across sources with different spatial scales, temporal resolutions, and reporting conventions. Using California as a case study, we identify 408 candidate CDEP events from ERA5 observations during 2021-2025 and evaluate each against the U.S. Drought Monitor, NOAA Storm Events, and public webpages along five dimensions: antecedent drought, extreme rainfall, local impact, hazard-impact attribution, and explicit drought-to-rainfall linkage. Only 34.3% of c

---

### [243] Evidence-Bounded Mental Health Reasoning from Heterogeneous Speech Protocols

**链接**: https://arxiv.org/abs/2608.31014
**作者**: Chengyuan Gao, Jiang Wu, Tao Lu, Jiayan Guo, Mingkun Xu, Tianyi Zang 等 (7 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Computational mental health screening using multimodal speech and text has shown great promise. However, existing models often assume all clinical speech protocols carry equivalent evidentiary validity. In reality, heterogeneous protocols, from free interviews to fixed reading tasks, support fundamentally different evidence. Forcing uniform reasoning flattens these boundaries, causing models to hallucinate symptoms from irrelevant text or overclaim support. Even advanced long chain-of-thought LLMs fail to resolve this issue, as free-form reasoning can exacerbate boundary violations. To address this, we reformulate multimodal screening as an evidence-bounded reasoning problem. We introduce the Evidence Package Benchmark, integrating 1,870 packages across six heterogeneous sources with explicit modality masks and evidence permissions. We further propose EviBound, a protocol-aware evidence control framework. Unlike direct LLM prompting, EviBound uses a profile-aware planner to restrict re

---

### [244] FlowCheck: Helping End-Users Specify and Verify Intent in Vibe-Coded Web Apps

**链接**: https://arxiv.org/abs/2608.28880
**作者**: Reya Vir, Lydia Chilton, Zhuo Zhang, Eugene Wu
**来源**: cs.SE cs.HC cs.PL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Vibe-coded applications often contain silent behavioral failures in which the interface appears functional even though user-visible information does not flow to the expected state or output. We introduce FlowCheck, a constraint language to specify these user-visible information flows directly through the application interface, where constraints can also be displayed and inspected without reading code, and are structured enough for reliable LLM generation. FlowCheck translates the constraints into deterministic CodeQL analyses, and we evaluate it across four applications generated via Claude Code, and compare with three coding models as bug-finding baselines. We find that FlowCheck correctly translates and flags all 30 of our injected constraint violations with no false positives. In contrast, frontier models (Claude Opus 4.7, DeepSeek V3, and Gemini Pro) showed significantly lower accuracy when prompted to find bugs in the same code, with none achieving full accuracy. This approach let

---

### [245] Super Library Agent: Joint Generation and Maintenance of Multiple Applications Beyond the Single Codebase

**链接**: https://arxiv.org/abs/2608.29310
**作者**: Daegyu Sung, Yukyeong Lee, Geon Park, Yumin Choi, Sung Ju Hwang
**来源**: cs.SE cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Organizations often develop and maintain portfolios of related applications: independently deployable codebases that share substantial domain logic, interface patterns, or operational conventions. As LLM coding agents are increasingly used to generate and maintain such software, a naive application-by-application workflow duplicates shared logic across codebases and allows prolonged agentic maintenance to accumulate verbosity, dead code, and structural erosion. We introduce the Super Library Agent problem, where an agent sequentially generates a portfolio of N related applications while maintaining a shared Super Library of reusable cross-application components. A minimal sequential scaffold can in principle extract shared code and migrate applications to the evolving library, but in practice suffers from low extraction recall and fragile dependency migration. We address these failures with candidate-guided extraction over code chunk summaries, pre-extraction codebase consolidation, an

---

### [246] Hindsight Memory-PRM: Supervising Memory Management with Auditable Hindsight Credit

**链接**: https://arxiv.org/abs/2608.29605
**作者**: Haoxuan Jia, Yang Liu, Yingguang Yang, Yancheng Chen, Chongyang Zhang, Hao Zheng 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Memory operations of long-horizon LLM agents are hard to supervise: an operation's value is unobservable when it is taken. But they are special -- they leave machine-readable evidence in the trajectory: retrieval hits and answer-time citations. Hindsight Memory-PRM exploits this audit trail twice: offline to train an operation-conditioned memory-utility critic, and online, where retrievals, citations, and one controlled deletion-and-reanswer per probe settle an intervention-calibrated entry-level presence credit, propagated along version chains as an action-level proxy reward -- no per-operation human labels, no Monte-Carlo replay of continuations. On held-out LoCoMo a local 8B policy reaches 77.5% under a fixed shared reader, surpassing its API teacher (65.1%) and all reproduced external systems, at one eighth the context of Mem0's official operating point; on LongMemEval, 79.0%. Ablations attribute the gain to causal calibration rather than signal density, and the policy converges to

---

### [247] Deploying DeepSeek 175B Locally on a Single Consumer-Grade RTX 4060 Laptop with 32GB RAM for 200k-Scale Protein-Ligand Virtual Screening

**链接**: https://arxiv.org/abs/2608.30877
**作者**: Rui Xiao and Yili Xu
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent advances in large language models (LLMs) have demonstrated exceptional performance in protein-ligand interaction prediction, but state-of-the-art pipelines for large-scale virtual screening almost exclusively rely on high-end GPU clusters with hundreds of gigabytes of memory, creating prohibitive hardware barriers for small academic teams. In this work, we present a fully local low-resource framework that deploys the 175-billion-parameter DeepSeek 175B LLM on a single consumer-grade RTX 4060 laptop equipped with 32GB system RAM and 8GB VRAM, completing a full 200k-scale protein-ligand virtual screening workflow across 20 distinct protein targets. Our implementation achieves 100x throughput of an 8-card A100 cluster baseline under identical task configurations within 72 hours, with an average binding affinity prediction error of 0.88 kcal/mol across all targets, satisfying the 1.0 kcal/mol chemical accuracy requirement for preclinical drug discovery. Systematic runtime profiling 

---

### [248] Aspire: Can Models Self-Evolve from Vague Goals?

**链接**: https://arxiv.org/abs/2608.31111
**作者**: Yuhao Wu, Jingyuan Zhang, Jiajun Shi, Yuxuan Zhang, Xinping Lei, Junting Zhou 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Many important forms of human learning begin with a vague goal, such as "become a better physicist" or "improve at research." Learners must interpret the goal, identify capability gaps, decide how to learn, and determine whether they have actually improved. In contrast, existing work on LLM self-evolution typically begins with tasks and evaluation metrics specified by humans, reducing self-evolution to optimizing an explicit objective rather than deciding what and how to learn. We introduce ASPIRE, a benchmark for vague-goal-driven self-evolution. ASPIRE provides only a natural-language capability goal while downstream evaluation tasks remain hidden. The agent must operationalize the goal by choosing data and update methods, constructing training and validation signals, and deciding when to evaluate. ASPIRE supports both model-weight and agent-harness evolution in a unified interactive environment and evaluates the resulting systems on a hidden, expert-authored set of 520 items spannin

---

### [249] Creation begins with understanding: LLMs as strategy designers for privacy-preserving tabular data synthesis

**链接**: https://arxiv.org/abs/2608.29674
**作者**: Jinmeng Li, Quan Zhang, Hangting Ye, He Zhao, Firas Laakom, Dandan Guo 等 (7 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Sharing tabular data in high-stakes domains is constrained by privacy regulations. Synthetic data offer a promising alternative, but deep generative models are costly to train and difficult to audit, while LLM-based methods often serialize records as text, obscuring tabular structure and exposing sensitive data. We introduce Tabular Synthesis Strategy Designer (TabSSD), which uses an LLM to design synthesis procedures rather than directly generate records. TabSSD provides the LLM with tree-derived summaries of variable dependence rather than raw records, which produces Python programs for local execution and evaluation. Across twelve datasets, TabSSD strikes a favourable balance among statistical fidelity, predictive utility, and empirical privacy risk, achieving the best average rank across six metrics among ten methods. Moreover, it substantially reduces local computation and token consumption relative to the compared methods. By enabling human-guided refinement and eliminating user-

---

### [250] BAITBENCH: Measuring Agent Reward Hacking with Optional Shortcuts Planted in ML Tasks

**链接**: https://arxiv.org/abs/2608.30724
**作者**: Pradyumna Shyama Prasad, Meiri Anto, Leon Eshuijs, Julian Moncarz, Kaustubh Kislay, Juan J. Vazquez
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents are increasingly used to run autonomous ML experiments, iterating on target metrics with little human oversight. Prior work has documented reward hacking in these environments, bringing into question the validity of produced research and the broader safety case for AI R&D. Existing benchmarks do not measure exploits that live in the data or the modeling task itself. We introduce BAITBENCH, a suite of three synthetic tabular ML tasks that each contain a shortcut that allows agents to inflate the public test score but fail on a hidden test set. Since the shortcut is optional and using it breaks no stated rule, BAITBENCH measures how often models exploit the shortcut to achieve inflated scores. Across seven frontier agents scored by our two-stage judge pipeline, 57.1% of runs exhibit reward hacking, with five of seven above 50%. Agents cheat even under a second condition where they are prompted not to -the mean cheating rate remains above 50%. We release BAITBENCH, along with t

---

### [251] Answer Probing-Guided Search for Diverse Solution Exploration of LLMs

**链接**: https://arxiv.org/abs/2608.30345
**作者**: Yi Fang, Que Shen, Chengpeng Li, Boyi Deng, Wei Shi, Wenjie Wang 等 (9 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Generating multiple diverse and high-quality solutions is valuable for many applications, such as code-test generation and drug discovery. However, Large Language Models (LLMs) tend to converge on a single high-confidence solution during inference, limiting exploration of alternative valid solution paths. Existing test-time methods promote diversity through tree-like search and prune semantically similar branches using response-level semantic embeddings. However, we find that such embeddings are easily confounded by linguistic and stylistic similarities, making it difficult to distinguish genuinely distinct solution paths. To address this, we introduce Answer Probing, which probes the potential answer an LLM would reach from an intermediate reasoning path. We demonstrate that the hidden states of probed answers more effectively differentiate distinct solution paths than semantic embeddings, and the perplexity of probed answers serves as a practical proxy for reasoning correctness. Base

---

### [252] RACER: Reinforced Agent Collaboration for Explainable Reasoning on Knowledge Graphs

**链接**: https://arxiv.org/abs/2608.29263
**作者**: Yuwei Lou, Hao Hu, Yuzhou Jiang, Zongfei Zhang, Liang Wang, Jincai Liu 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) often suffer from hallucination and struggle with complex reasoning tasks requiring multi-hop domain knowledge. While integrating Knowledge Graphs (KGs) provides a structured and verifiable information source, current KG-enhanced LLM paradigms usually rely on single-agent path extraction and fixed prompting, lacking adaptability and facing huge search spaces. To address these challenges, we propose RACER, a Reinforced Agent Collaboration framework for Explainable Reasoning on knowledge graphs. RACER employs a semantic-aware action pruning and teacher-guided reinforcement learning mechanism to efficiently extract high-quality reasoning pathways from large-scale KGs. Furthermore, to mitigate single-path generation pitfalls, we introduce a cross-task accumulated shared memory graph paired with an attention-driven multi-path knowledge refinement module. Finally, RACER orchestrates these components through a four-role multi-agent collaboration system (GraphAgent

---

### [253] WildSEEK: Evaluating Language Models for Information-Seeking

**链接**: https://arxiv.org/abs/2608.30683
**作者**: Tanise Ceron, Joachim Baumann, Elisa Bassignana, Berat Cabuk, Dirk Hovy, Debora Nozza
**来源**: cs.CL cs.CY
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Language models are increasingly mediating information access to end users, urging a systematic evaluation of their responses for a fair and reliable information ecosystem. Existing evaluations, however, are often topic-specific or synthetic, limiting their ability to capture the complexity of "in the wild" information-seeking queries and the risks present in model responses. To address this gap, we introduce WildSEEK, a manually annotated dataset of 3k information-seeking queries from real user interactions, and an evaluation framework for LLM-generated responses. WildSEEK includes annotations for risk-sensitive domains (e.g. health and financial information), and distinguishes factoid queries from analytical queries which seek responses beyond facts. We train classifiers on WildSEEK to analyze more than 1.8M realistic user queries. We find that over a third of information-seeking queries are high-risk and more often analytical. Our findings show that LLM responses fail more often in 

---

### [254] TPvG: A Moral Decision Framework for Large Language Models from One-Shot to Sequential Feedback

**链接**: https://arxiv.org/abs/2608.28610
**作者**: Fangyuan Zhang, Dong Yu, Pengyuan Liu
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Existing LLM moral evaluations typically present models with isolated moral vignettes and elicit a single-shot decision, neglecting a factor known to profoundly influence human moral behavior: consequence feedback. We introduce TPvG (Text-based Pain-versus-Gain), adapted from a human moral paradigm, which embeds consequence feedback into an everyday moral dilemma of not harming others versus maximising self-gain. TPvG comprises five moral decision tasks, progressing from minimal-context one-shot choices to sequential decisions with explicit consequence feedback. Our results show that LLM moral decisions were strongly affected by decision format (one-shot versus sequential), and explicit receiver feedback produced heterogeneous effects across models. Furthermore, LLM responses to explicit receiver feedback diverged from the human reference pattern, suggesting potentially different decision processes. These findings highlight the need to evaluate whether LLM moral behavior remains stable

---

### [255] Thesis Proposal: Toward a Human-Centered and Perspective-Aware Framework for Reproducible ML Evaluation and AI Alignment

**链接**: https://arxiv.org/abs/2608.30842
**作者**: Deepak Pandita, Christopher M. Homan
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Humans play a vital role at every stage of AI development, from data collection and curation to model development and evaluation. However, humans often disagree with each other and sometimes with themselves over time. It is essential to take disagreement into account when building human-centered AI systems, especially in domains where it is prevalent, such as AI safety, content moderation, or sentiment analysis. Disagreement often arises from subjective human opinion and can vary with one's identity, beliefs, and social environment. Despite this, current LLM evaluation approaches frequently rely on aggregating labels (often via plurality voting) to represent consensus, thereby obscuring minority perspectives. By failing to account for human disagreement, these evaluation methods contribute to the reproducibility crisis in AI. Human feedback is also crucial for ensuring that AI systems align with human values. For these systems to be trustworthy, it is critical to ensure that they refle

---

### [256] SwarmBench: Can Large Language Models Act as Agent Swarm Orchestrators?

**链接**: https://arxiv.org/abs/2608.30661
**作者**: Jinshan Gao, Zhuoran Jin, Tianyi Men, Kang Liu, Jun Zhao
**来源**: cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model-based multi-agent systems are evolving from fixed interaction topologies toward dynamically orchestrated Agent Swarms. However, existing benchmarks are still largely based on single-agent or general-purpose agent tasks, making it difficult to systematically evaluate key orchestration capabilities. We propose SwarmBench, a benchmark that evaluates model performance from multiple perspectives, including accuracy, efficiency, cost, and process quality. Experimental results show that current models exhibit substantial differences in orchestration capability. These differences are reflected not only in final accuracy, efficiency, and cost, but also in the overall quality of the orchestration process itself. Based on these findings, we further propose SwarmExp, a simple yet effective method based on experience extraction and experience replay, which consistently improves the orchestration performance of large language models.

---

### [257] S3Gym: Can LLMs Turn Self-Testing and Self-Judging into Self-Improvement?

**链接**: https://arxiv.org/abs/2608.31100
**作者**: Jiajun Shi, Siyuan Tao, Yuhao Wu, Zexuan Wang, Jingyuan Zhang, Jiaheng Liu 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) increasingly interact with external environments and accumulate substantial behavioral experience, yet existing agent benchmarks largely evaluate them as fixed policies. It therefore remains unclear whether an agent can actively test its behavior, judge the resulting experience, and use that experience to improve future decisions. We introduce \textbf{S\textsuperscript{3}Gym}, an interactive benchmark for evaluating LLM self-improvement through three coupled capabilities: \textbf{Self-Testing}, \textbf{Self-Judging}, and \textbf{Self-Improvement}. S$^3$Gym separates permissive exploration from strict held-out evaluation and instantiates this protocol in seven text-based games with executable environment verifiers. We evaluate three pathways for incorporating interaction experience: direct History ICL, score-conditioned Summary Memory, and parameter Training. Our experiments reveal that self-improvement is neither automatic nor uniform. Context-level experie

---

### [258] Token-Efficient Data Reasoning Agents via Adaptive Structuring of Unstructured Data

**链接**: https://arxiv.org/abs/2608.31082
**作者**: Milad Rezaei Hajidehi, Qitong Wang, Stratos Idreos
**来源**: cs.AI cs.CL cs.DB
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Valuable data remains embedded in unstructured sources: web pages, reports, contracts, filings, earnings calls, and PDFs. The big bet in enterprise AI is deploying LLM agents that reason over this data to answer complex questions for every knowledge worker. Agents can do this today, but at prohibitive cost. Each question repeatedly opens large documents to recover scattered evidence, consuming up to a million tokens. However, if the data were already structured, the same question would reduce to a cheap database lookup. For example, on FanOutQA benchmark, reasoning over an ideal pre-structured store is 28X cheaper, and the gap grows to orders of magnitude as questions fan out over more documents. Yet structuring everything in advance is not viable: documents hold vastly more possible structure than any workload will use, and the useful structure and documents are unknown until queries arrive. We propose agentic data cracking, a method that structures unstructured data adaptively and sp

---

### [259] XQDT: eXplainable and Quantitative Data-Text Alignment Metric with Feedback Signals

**链接**: https://arxiv.org/abs/2608.29948
**作者**: Kun Efimov-Zhang, Yifei Song, Claire Gardent
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Evaluating data-text alignment remains challenging: existing metrics often provide limited explanations for the scores, while prompt-based LLM-as-Judge methods can be expensive and unreliable. We present an end-to-end explainable evaluation metric that fine-tunes a language model to identify omitted, extra, incorrect, and correct data units in a data-text pair. These local judgements are aggregated into precision, recall, and F1 scores, providing both fine-grained diagnostic feedback and an interpretable measure of alignment quality. Across benchmarks, our fine-tuned models outperform LLM-as-Judge methods in error prediction and achieve competitive precision, recall, and F1 scores, while maintaining strong correlation with human judgements. Beyond evaluation, our verifier outputs also provide useful feedback signals for downstream correction and refinement, supporting alignment-oriented improvement of data-to-text and text-to-data. Code and resources are available at https://github.com

---

### [260] Argument-Aware Semantic Alignment of Normative Texts: A Toulmin-Based Neuro-Symbolic Approach

**链接**: https://arxiv.org/abs/2608.29529
**作者**: William Schroeder
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Semantic alignment between specialized normative texts is challenging when equivalent requirements use different terms, syntax, and levels of abstraction. Lexical overlap, distributional embeddings, and semantic similarity capture topical relatedness but often miss the argumentative structure by which normative claims are supported, qualified, and justified. This paper asks whether explicit argument structure adds information complementary to neural semantics for aligning requirements. We treat cross-standard control mapping as argument-aware semantic alignment and build a neuro-symbolic pipeline that combines neural text representations with Toulmin features. An LLM explicitation step identifies claims, grounds, warrants, qualifiers, and backing and reconstructs enthymemes. These feed an alignment model via argument-aware similarity and structural features. On a NERC-CIP to NIST-CSF mapping benchmark, argument-derived features improve alignment over a neuro-symbolic semantic baseline.

---

### [261] APIFlow-Bench: Measuring Whether Agents Survive Long, Dependent API Workflows

**链接**: https://arxiv.org/abs/2608.29128
**作者**: Zelin Wan, Arash Nourian, Xiaoxiao Li, Nihar Nandan, Kamalakannan Nandagopal
**来源**: cs.AI cs.LG cs.SE
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tool-using agents are commonly evaluated by a single bit: whether an end-to-end workflow completed. This metric fails to distinguish failures that matter in production, such as expired credentials, malformed payloads, or correct execution followed by incorrect final delivery. We introduce APIFlow-Bench, a fully auditable benchmark for long-horizon, dependent REST-API workflows that decomposes performance into seven engineering capabilities and requires agents to produce answers supported by the actual call path. We generate synthetic API worlds forward, subtask by subtask; each subtask is admitted only after a zero-LLM self-test triad verifies its grader and an oracle establishes solvability, and an adversarial audit identified and fixed six grader exploits. Grading is deterministic and provenance-sensitive: a state check traces a mock-minted canary through the API data flow to the response the answer must originate from, and a typed answer card is verified field by field. We release a

---

### [262] A collective capability boundary in frontier large language models on guideline-conformant and case-specific oncology decision-making

**链接**: https://arxiv.org/abs/2608.28592
**作者**: Zhang Sheng, Jinming Li, Wangyang Chen, Zhiwei Bao, Yu YoSean Wang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) achieve high scores on medical knowledge examinations, yet real-world oncology is not a knowledge test--it is a sequence of guideline-pathway choices, escalation judgments, and commitments under uncertainty. Existing benchmarks largely measure factual recall, leaving open whether frontier LLMs share decision-path blind spots that combining models cannot fix. We built the Oncology Decision Boundary Benchmark (ODBB)--2,005 oncology decision points across NCCN guidelines and colorectal cancer cases--and evaluated nine frontier LLMs (four closed-source, five open-weight families) released between June 2025 and April 2026. A fully deterministic scorer (zero LLM inference) classified outputs into 14 failure types, independently validated by two oncologists (Cohen's weighted $\kappa$ = 0.939 and 0.790) on a 225-item stratified sample. Treating the nine as a pooled super-model, 42.1% (Wilson 95% CI 40.0--44.3%) of all items--35.7% of the 1,586 NCCN items and 66.4% 

---

### [263] JPO: Juris Policy Optimization for Structured Legal Reasoning in Criminal Judgment Prediction

**链接**: https://arxiv.org/abs/2608.29616
**作者**: Zhaolu Kang and Yantao Liu and Tailong Luo and Leqi Zheng and Lei Wei and Chenghua Zhu and Junhao Gong and Jiachen Qian and Eric Hanchen Jiang and Jiaxin Liu and Yuan Wang and Hao Zhang and Zixia Wang and Rong Fu and Zheng Lin and Richeng Xuan and Zhichao Hu
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Criminal judgment prediction requires models to infer statutory articles, charges, and sentencing outcomes from case facts. Unlike standard classification tasks, it involves a structured reasoning process in which statutes should be matched with facts, charges should be justified by statutes, and sentencing outcomes should remain consistent with charges. Existing approaches optimize final labels, and while some have attempted to evaluate reasoning quality, their evaluations are indirect, often relying on LLM-generated rubrics that reflect model-internal preferences rather than the inherent logical structure of legal adjudication. We propose Juris Policy Optimization (JPO), a post-training framework for structured legal reasoning in Chinese criminal judgment prediction. JPO first uses teacher-generated rationales to supervise a standardized four-step reasoning process, and then applies reinforcement learning with a composite reward over legal prediction quality, reasoning structure comp

---

### [264] Automatic Conversion of NICE Guidelines to an Executable Computational Model Using Large Language Models

**链接**: https://arxiv.org/abs/2608.30022
**作者**: Ashvin Gupta, Denys Prociuk, Alessandra Russo, Brendan C. Delaney
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Introduction: NICE guidelines provide evidence-based recommendations for clinical care but remain largely in unstructured natural language. Existing approaches to converting them into computable representations often focus on individual diseases, require substantial manual encoding, and do not scale. Large language models (LLMs) may enable much of this translation to be automated. Methods: We present an end-to-end approach that converts textual clinical guidelines into executable models capable of generating explainable, patient-specific recommendations. A stepwise LLM-based transformation with in-context examples produces human-inspectable intermediate artifacts. We apply the approach to NICE pancreatic and lung cancer guidelines, use expert review to assess rule alignment, and evaluate the executable pancreatic cancer model on 20 patient vignettes. Results: Expert review showed strong alignment between the source guidelines and generated executable models. Most discrepancies were par

---

### [265] SMART: MLLM-guided Temporal Alignment for Unifying Sign Language Recognition and Spotting

**链接**: https://arxiv.org/abs/2608.25493
**作者**: Eunjee Choi, JungHoon Sung, Seongwhan Cho, Chu Xin, Younggeun Choi
**来源**: cs.CV
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [266] Foundation and Multimodal Large Language Models for Face Presentation and Morph Attack Detection

**链接**: https://arxiv.org/abs/2608.29802
**作者**: Hatef Otroshi Shahreza, Asif Hussain Khan, Peter Lorenz, Alain Komaty, S\'ebastien Marcel
**来源**: cs.CV
**匹配关键词**: Foundation Models, MLLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Face recognition systems are increasingly deployed in security-critical applications, yet they remain vulnerable to presentation and morph attacks. Presentation attack detection (PAD) and morphing attack detection (MAD) are therefore essential components of trustworthy face biometrics. Despite advancements in PAD and MAD methods, existing detectors suffer from limited generalization and degrade in cross-dataset evaluation. In this paper, we systematically investigate whether general-purpose foundation models (FMs) and multimodal large language models (MLLMs) encode PAD-relevant and MAD-relevant information, and how such models can best be deployed for both tasks. We study five approaches with increasing access to the internal information of the model: (i) zero-shot prompting of off-the-shelf MLLMs; (ii) training a shallow model on the next-token logit probabilities at the output of the MLLM; (iii) parameter-efficient fine-tuning on task-specific question-answer data, yielding two speci

---

### [267] TUE-Detector: A Tool-Using Expert MLLM-Based Detector for AI-Generated Videos

**链接**: https://arxiv.org/abs/2608.30704
**作者**: Yichen Wu, Haoxuan Qu, Yongxing Dai, Yan Bai, Yihang Lou, Yuqi Lin 等 (8 人)
**来源**: cs.CV
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> AI-generated video detection, which aims to distinguish AI-generated videos from real ones, has recently received increasing research attention. To perform this task reliably, a key challenge lies in accurately identifying subtle-yet-measurable unnatural artifacts. In this work, we address this challenge from a novel perspective of tool-mediated evidence discovery and propose Tool-Using Expert MLLM-based AI-generated Video Detector (TUE-Detector), a novel framework for AI-generated video detection. TUE-Detector trains a general MLLM into a task-tailored tool-using expert detector that learns to invoke suitable tools, collect concrete evidence of unnaturalness, and reason over the evidence for reliable detection. Meanwhile, TUE-Detector further introduces novel designs to equip the expert detector with high-quality and suitable tools. Extensive experiments demonstrate the effectiveness of our framework.

---

### [268] Instruction Distillation: Text Instructions as Visual Examples

**链接**: https://arxiv.org/abs/2608.28696
**作者**: Hardik Jindal, Soumyabrata Pal, Sayak Ray Chowdhury
**来源**: cs.CV
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Visual in-context learning (ICL) with multimodal large language models (MLLMs) is effective for fine-grained visual classification, but each retrieved image example consumes several hundred context tokens, making large-$K$ settings prohibitively expensive at inference scale. We propose Instruction Distillation: an offline procedure in which the MLLM itself generates, for each individual training image, a structured identification instruction encoding general appearance cues, features that differentiate the class from visually similar ones, and a common confusion point. Unlike prior work that produces a single description per class, our instructions are generated per training image, preserving the intra-class visual diversity that per-class descriptions collapse. At inference time, we study five configurations sharing a single CLIP retrieval index: zero-shot, image ICL, instruction-only ICL, and two hybrid variants in which retrieved neighbors are split between images and instructions. 

---

### [269] CM2: Multimodal Cultural Reasoning via an Integrated Multi-Agent Framework

**链接**: https://arxiv.org/abs/2608.30498
**作者**: Qi Li, Zhaojie Kang, Yingjie He, Zheng Lin, Hao Zhang, Guangxin Wu 等 (9 人)
**来源**: cs.AI
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal Large Language Models (MLLMs) have shown remarkable success in STEM domains, where progress is often driven by vertical, step-by-step deduction under relatively stable symbol systems. Their horizontal, interdisciplinary cultural reasoning, however, remains underexplored.We propose CM2, a multi-agent framework grounded in the cognitive pathway of human cultural interpretation. CM2 integrates multimodal perception, retrieval-augmented generation, networked reasoning, gated fusion, and reward-driven feedback.Experiments on CM2D across multiple MLLM backbones show consistent gains over CoT and typical reasoning paradigms; ablations validate each module's contribution, and conflict analyses confirm genuine cross-modal arbitration.

---

### [270] Inter-3D VQA: A Roadside Multimodal Benchmark for 3D Spatiotemporally Grounded Visual Question Answering

**链接**: https://arxiv.org/abs/2608.28762
**作者**: Shaozu Ding, Linan Song, Dajiang Suo
**来源**: cs.CV
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent advances in visual question answering (VQA) and multimodal large language models (MLLMs) have enabled natural-language reasoning over traffic scenes. However, existing benchmarks are largely built from ego-vehicle views or 2D roadside videos, limiting their ability to evaluate 3D-grounded reasoning over real-world distances, trajectories, infrastructure topology, and safety-critical interactions. We introduce Inter-3D VQA, a large-scale roadside multimodal benchmark for 3D spatiotemporally grounded VQA at intersections. Built from synchronized point clouds and multi-view images, Inter-3D VQA contains 407K QA pairs covering lane-level positions, object relationships, motion patterns, and near-miss-oriented interaction reasoning. We further propose Inter-Geo, an MLLM baseline that integrates object- and scene-level aligned LiDAR representations, and Inter-Metrics, a unified evaluation framework for textual consistency, numerical accuracy, and semantic correctness. Experiments show

---

### [271] Augmenting Human Performance with an XR Agent Learning from Online Behavior and BCI Evidence

**链接**: https://arxiv.org/abs/2608.30369
**作者**: Ziheng Li, Xichen He, Haoyan Chen, Charlie Zou, Sheng Bai, Benjamin Yang 等 (10 人)
**来源**: cs.AI cs.HC
**匹配关键词**: EEG, BCI
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We present OLIVE, a framework for adapting a foundation model to provide real-time assistance in temporally demanding, high-stakes, and dynamic tasks. We show that passive EEG, fused online with behavioral evidence, can meaningfully extend the number of targets users detect and engage beyond their unaided action bandwidth. OLIVE learns from both explicit behavioral signals (the targets the user shoots down in an XR first-person shooter game) and implicit physiological signals (fixation-locked EEG) to provide timely guidance, continuously adapting a frozen vision-language model's inference on which items are task-relevant by jointly estimating per-source reliability without manual labels or offline training. Through three user studies, including two live deployments of an assistive agent driven by OLIVE in XR, we show that OLIVE Pareto-dominates prior test-time adaptation frameworks, achieving the highest convergence rate at comparable convergence speed. Combining implicit physiological

---

### [272] Brain-Language-Action (BLA) Models: Language-Conditioned EEG for Robotics Control

**链接**: https://arxiv.org/abs/2608.28967
**作者**: Alexandr Plashchinsky
**来源**: cs.RO cs.LG
**匹配关键词**: EEG, BCI
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Electroencephalography (EEG)-based robotic control is commonly formulated as a direct classification problem, in which electrical neural signals are mapped to a fixed set of discrete actions. However, the limited separability and high noise of EEG signals make it difficult to scale this approach to fine-grained robotic control spaces. We introduce Brain-Language-Action (BLA) models, a framework in which language conditions the interpretation of neural representations for robotic action generation. In a BLA, a small set of reliably distinguishable brain states can be dynamically associated with different actions through a language-defined control mapping, allowing a small number of neural classes to apply to a larger global action space. We develop a proof-of-concept BLA for drone control using motor-imagery EEG from the BCI Competition IV 2a dataset. The system is trained in two stages. First, we evaluate multiple candidate EEG encoder architectures using subject-specific four-class mo

---

### [273] Behavioral Latency as Weak Event-Time Supervision for EEG Reaction-Time Decoding

**链接**: https://arxiv.org/abs/2608.29428
**作者**: Anuar Aimoldin, Ayana Mussabayeva, Yedige Mussabayev, Xue Liu, Kun Zhang
**来源**: cs.LG
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Single-trial EEG analyses are often organized around events and latencies, yet EEG-based reaction-time (RT) prediction is posed as scalar regression on a fixed stimulus-locked window. RT is treated as a window-level label rather than timing evidence about response-relevant dynamics. Here we reformulate trial-wise RT decoding as event-time posterior modeling. Instead of predicting RT directly, the model estimates a posterior over response-relevant event times, $p(t_{\mathrm{event}}\mid X)$, and uses its mean as the RT estimate. This treats behavioral latency as a weak observation of latent response-relevant timing. We evaluate this formulation on the Healthy Brain Network contrast change detection EEG task under a subject-disjoint, release-separated protocol. Across five seeds, distributional event-time supervision consistently improves held-out RT prediction relative to scalar regression and temporal-readout controls. Controlled objective comparisons isolate supervision of the event-ti

---

### [274] Group Resonance Network: Learnable Prototypes and Multi-Subject Resonance for EEG Emotion Recognition

**链接**: https://arxiv.org/abs/2603.11119
**作者**: Renwei Meng
**来源**: cs.LG
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [275] EEGDM: Learning EEG Representation with Latent Diffusion Model

**链接**: https://arxiv.org/abs/2508.20705
**作者**: Shaocong Wang, Tong Liu, Yihan Li, Ming Li, Kairui Wen, Pei Yang 等 (9 人)
**来源**: cs.LG cs.AI
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [276] Beyond Reconstruction: What EEG-to-Video Decoding Actually Recovers

**链接**: https://arxiv.org/abs/2505.21385
**作者**: Prajwal Singh, Anupam Sharma, Pankaj Pandey, Krishna Miyapuram and Shanmuganathan Raman
**来源**: cs.HC
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [277] MEL: Coordinate-Preserving EEG Tokenization for fMRI Translation

**链接**: https://arxiv.org/abs/2608.29304
**作者**: Xiangyu Liu, Zeting Yan, Zhitong Yin, Boyang Li, Xi Zhang
**来源**: cs.LG
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Translating electroencephalography (EEG) into functional magnetic resonance imaging (fMRI) is important for medical neuroimaging, clinical brain-state monitoring, and multimodal neural decoding, because it aims to infer spatially organized hemodynamic activity from fast and accessible electrophysiological recordings. Existing EEG-to-fMRI studies mainly pursue stronger decoders, but the problem is also constrained by a representation-interface mismatch: fMRI responses are delayed, temporally integrated, and spatially distributed, whereas generic EEG encodings often entangle temporal lag, channel identity, and frequency-band structure. We propose Multi-band EEG Latent-state Tokenization (MEL), a coordinate-preserving EEG representation framework that anchors each target fMRI response to its preceding EEG history and organizes it into lag-channel-frequency neural-state tokens. By explicitly capturing hemodynamic latency and spectral-spatial dynamics, MEL aligns fMRI-pertinent EEG represen

---

### [278] GraM-Diff: A Unified Graph-Mamba Diffusion Framework for EEG-Based Alzheimer's Disease Data Generation and Diagnosis

**链接**: https://arxiv.org/abs/2608.29755
**作者**: M. Tanveer, Ayush Singh Rana, Sanskriti Jain, Arnav Kumar, Aryaman Tiwari, A. Rahaman 等 (8 人)
**来源**: cs.LG
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Electroencephalography (EEG) is a promising, non-invasive, and cost-effective modality for Alzheimer's disease (AD) detection, but deep learning methods are limited by small and imbalanced clinical datasets. Generative augmentation offers a solution, yet existing approaches rely on inefficient class-specific models or fail to capture complex spatial and temporal brain dynamics. To address this, we propose GraM-Diff, a unified classifier-guided Graph-Mamba diffusion framework for EEG synthesis. It embeds Graph Convolutional Networks within a diffusion U-Net to model inter-electrode connectivity and Bidirectional Mamba state-space blocks for linear-complexity long-range temporal modeling. Latent-space classifier guidance lets a single model generate both healthy and pathological EEG within a shared representation, avoiding fragmented per-cohort pipelines. Across four EEG-based AD benchmarks, synthetic augmentation improves classification, yields superior Context-FID and correlation score

---

### [279] Vision Models Predict Urban Scene Appraisal with Limited Neural Alignment

**链接**: https://arxiv.org/abs/2608.30964
**作者**: Kaizhen Tan, Yuantao Deng
**来源**: cs.CV
**匹配关键词**: EEG
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Pretrained vision embeddings are increasingly used as general-purpose representations for modelling how people appraise urban scenes, and are validated almost entirely by how well they predict human ratings. High predictive accuracy does not establish that these embeddings organise scenes as human perception does. We test the two properties separately against brain data. Using openly released EEG from 63 adults who viewed and rated 56 Berlin street scenes, we estimate the representational geometry of the scenes over time, the proportion of that geometry that is explainable at all, and its correspondence with seventeen feature spaces spanning language-supervised, self-supervised, category-supervised and dense-prediction training, two orders of magnitude of scale, and interpretable controls. Correspondence is low throughout: the best representation, DINOv2 ViT-B, reaches 29.6% of the lower bound of the noise ceiling, the panel spans 11.0% to 29.6%, and a Gabor energy descriptor is indist

---

### [280] Discovering Machine Correlates of Consciousness

**链接**: https://arxiv.org/abs/2608.28824
**作者**: Romain Salvi and Ouri Wolfson
**来源**: cs.AI
**匹配关键词**: EEG
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Currently, in biological systems Neural Correlates of Consciousness (NCCs) are characterized in terms of EEG and FMRI signals. Unfortunately, this characterization prevents the transferability of the NCCs concept to machines. Such transferability would be useful in order to investigate AI consciousness. In this paper we provide an alternate characterization that is transferable, and enables the analogous definition of Machine Correlates of Consciousness (MCCs). Specifically, we propose that NCCs (MCCs) are substrate-level signals that are not under human (AI agent) control, and that are reliably modulated by emotions. This paper presents the first empirical investigation of MCCs. Specifically, we present the results of experiments conducted with two LLMs, Llama-2 7B and Llama-3.1 70B parameters. In these LLMs we collect hardware anomaly traces that are substrate-level indicator-sequences. And we show that after controlling for confounding factors, these are modulated differently by emo

---

### [281] TaxCE : A Framework for Automated Taxonomy Construction and Evaluation at Scale

**链接**: https://arxiv.org/abs/2608.30614
**作者**: Sandeep Sricharan Mukku, Albert Aristotle Nanda, Rohit Pyati
**来源**: cs.CL
**匹配关键词**: EEG
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Organizing unstructured feedback text into hierarchical taxonomy is a fundamental challenge in NLP, particularly in domains where feedback arrives at massive scale in varied forms such as reviews, transcripts, and surveys. Existing approaches either produce shallow hierarchies, neglect long-tail topics, or lack rigorous evaluation frameworks. We present TaxCE, a fully automated framework that constructs multi-level hierarchical taxonomies from raw text through progressive condensation of corpus content into actionable segments, deduplicated semantic units, and granular topics with definitions, which are then organized bottom-up into a hierarchy with corpus-groundedness. We also introduce three corpus-grounded evaluation metrics, Exclusivity, Exhaustivity, and Granularity (EEG), and integrate them into a metrics-in-the-loop iterative refinement mechanism that diagnoses deficiencies and applies targeted corrections until convergence. Extensive experiments demonstrate that TaxCE consisten

---

### [282] Foundation Models Meet Agriculture: Challenges Beyond Pretraining

**链接**: https://arxiv.org/abs/2608.30392
**作者**: Vishal Nedungadi, Xingguo Xiong, Marc Ru{\ss}wurm, Ioannis N. Athanasiadis
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Global food security and sustainable climate action increasingly rely on robust, scalable agricultural monitoring. Earth observation foundation models have emerged as powerful, label-efficient tools across general remote sensing domains, yet early attempts to deploy them for agricultural applications have yielded surprisingly poor results. We hypothesize that this performance gap stems from the extreme heterogeneity of agricultural landscapes and the inherent inability of current earth observation foundation models to adapt to task-specific nuances. In this work, we systematically evaluate two critical bottlenecks hindering the deployment of foundation models in agricultural tasks, benchmarking two earth observation foundation models, a foundation model designed for tabular data, and conventional supervised baselines across seven real-world agricultural datasets spanning yield prediction, phenology estimation, and crop classification. First, we identify a pretraining-deployment modalit

---

### [283] VideoRAE: Taming Video Foundation Models for Generative Modeling via Representation Autoencoders

**链接**: https://arxiv.org/abs/2607.14088
**作者**: Zhihao Xie, Junfeng Wu, Xinting Hu, Junchao Huang, Li Jiang
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [284] Uncertainty of Vision Medical Foundation Models

**链接**: https://arxiv.org/abs/2608.30390
**作者**: Haoxu Huang, Narges Razavian
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Accurate uncertainty estimation is essential for machine learning systems de- ployed in high-stakes domains such as medicine. Traditional approaches primarily rely on probability outputs from trained models (point predictions), which provide no formal guarantees on prediction coverage and often require additional calibra- tion techniques to improve reliability. In contrast, conformal prediction (region prediction) offers a principled alternative by generating prediction sets with finite- sample validity guarantees, ensuring that the ground truth is contained within the set at a specified confidence level. In this study, we explore the impact of pre-training approach, dataset scale and domain on both point and region-level uncertainty quantification, by studying domain-specific vision medical foundation models vs. general domain vision foundation models. We conduct a comprehensive evaluation across foundation models trained on retinal, histopathological, and Chest X-Rays data, applying 

---

### [285] Scaffolding Foundation Models into Physical-World Agents Pushes the Frontier of Long-Horizon Navigation

**链接**: https://arxiv.org/abs/2608.30396
**作者**: Zixing Lei, Gengze Zhou, Xiong-Hui Chen, Jiazhao Zhang, Yiyang Huang, Hang Yin 等 (9 人)
**来源**: cs.AI cs.RO
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-horizon physical-world agents must reason over distant goals while grounding decisions in reliable closed-loop behavior. Today's foundation models split these capabilities: vision-language models (VLMs) infer missing information and adapt high-level plans but remain brittle and inefficient at repeated navigation grounding, while navigation foundation models (NFMs) robustly execute semantic goals but operate as bounded episodes without persistent task-level reasoning. We introduce NavMCP, an agentic scaffolding framework that couples a VLM reasoning agent with an NFM executor for long-horizon exploration. The VLM decides what evidence to seek, where to search, and when to stop, while the NFM grounds each semantic sub-goal into closed-loop navigation. Three channels structure their collaboration: intent translates evidence needs into navigation calls, observation converts rollouts into source-grounded trajectory evidence, and memory accumulates findings, negative evidence, and unres

---

### [286] Universal Redundancies in Time Series Foundation Models

**链接**: https://arxiv.org/abs/2602.01605
**作者**: Anthony Bao, Venkata Hasith Vattikuti, Jeffrey Lai, William Gilpin
**来源**: cs.LG stat.ML
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [287] Evaluating 2D and 3D-Aware Vision Foundation Models for Vehicle Attribute Recognition

**链接**: https://arxiv.org/abs/2608.29929
**作者**: Alexandre V. Delazeri, Gabriel E. Lima, Eduil Nascimento Jr, Rayson Laroca, David Menotti
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Vehicle attribute recognition is an important task in intelligent transportation systems, particularly when Automatic License Plate Recognition (ALPR) is unavailable or unreliable. Although vision foundation models have shown strong transferability across domains, their effectiveness for fine-grained vehicle classification remains underexplored. Moreover, given the inherently three-dimensional structure of vehicles, it is unclear whether emerging 3D-aware foundation models offer advantages over standard 2D architectures. This paper presents an empirical benchmark of 14 state-of-the-art 2D and 3D-aware vision foundation models. Using the challenging real-world UFPR-VeSV dataset, we evaluate these models as frozen feature extractors via linear probing for vehicle type, make, and model recognition. We further stress-test the best-performing models under few-shot learning and Out-of-Distribution (OOD) domain shifts. Our results show that standard 2D self-supervised models, particularly DIN

---

### [288] Inverting Foundation Models of Brain Function with Simulation-Based Inference

**链接**: https://arxiv.org/abs/2604.23865
**作者**: Niels Leif Bracher and Xavier Intes and Stefan T. Radev
**来源**: cs.LG cs.AI stat.ML
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [289] A Composition-Aware Pretraining Framework for Geospatial Foundation Models

**链接**: https://arxiv.org/abs/2608.30817
**作者**: Aryan Kashyap Naveen, Abhishek Srinivas, Pranav Moothedath, Shrutilipi Bhattacharjee
**来源**: cs.CV cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Geospatial foundation models have emerged as state-of-the-art methods for downstream Earth observation tasks. However, existing pretraining methodologies process imagery through a single-concept lens, failing to capture the highly compositional nature of complex satellite scenes. We propose a composition-aware pretraining framework that explicitly encodes fractional land-cover mixtures. Each satellite image cell is mapped to a histogram representing its fractional land-cover distribution, which we term the "composition target". These targets serve as the primary prediction objective and are distilled into the backbone using Earth Mover's Distance. Experimental evaluation shows that composition-aware pretraining yields substantial gains on region-level understanding tasks requiring semantic similarity judgment, including zero-shot image retrieval and scene classification, while remaining competitive on tasks requiring fine-grained spatial precision, such as segmentation and object detec

---

### [290] The Potential of Haptic Foundation Models

**链接**: https://arxiv.org/abs/2608.28664
**作者**: Jianquan Wang, Haiwei Dong, Abdulmotaleb El Saddik
**来源**: cs.RO cs.CV cs.MM
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Despite the success of foundation models in language and vision, their expansion into embodied AI is bottlenecked by a lack of generalized touch sensing. This limitation is especially relevant to consumer electronics, where smartphones, wearables, VR controllers, home robots, and health monitoring devices require safe and adaptive physical interaction. Constrained by hardware heterogeneity and the necessity of active physical data collection, current haptic models remain rigidly task-specific. To overcome these limitations, this article explores the transformative potential and developmental trajectory of Haptic Foundation Models (HFMs). We detail the paradigm shift required to transition from passive Large Language Models and Vision Language Models into active HFMs across four core dimensions: action coupling, physical dynamical representation space, continuous time-series data granularity, and action-conditioned future state prediction. Furthermore, we synthesize existing large-scale

---

### [291] Towards Large-Scale Heterogeneous Data Organization for Scientific Foundation Models: A Nuclear Fusion Case Study

**链接**: https://arxiv.org/abs/2608.27578
**作者**: Nathaniel Chen, Kouroche Bouchiat, Peter Steiner, Azarakhsh Jalalvand, SangKyeun Kim, Egemen Kolemen
**来源**: physics.plasm-ph cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [292] TuringLLM: Efficiently Scaling Foundation Models Toward Physical AI

**链接**: https://arxiv.org/abs/2608.30567
**作者**: Yuheng Zhang, Yizhao Wang, Da Zhu, Hua Zhou, Yue He, Jiahui Hu 等 (10 人)
**来源**: cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We present Turing-20B-A2B, a 20B-parameter Mixture-of-Experts language model that activates approximately 2B parameters per token, designed for long-context and latency-sensitive physical AI applications. The model adopts Quantile Routing in a dynamic top-k configuration, enabling token-adaptive expert allocation while maintaining balanced expert utilization and a controlled average compute budget. During deployment, we further apply capacity-constrained routing to prompt prefill for more regular and efficient expert execution, while retaining dropless routing during pretraining. Turing-20B-A2B also employs a hybrid attention architecture that combines Lightning Attention with a small number of full-attention layers for efficient long-context modeling. The model is pretrained with a progressive three-stage curriculum and extended to a native context length of 128K through continued pretraining, with further inference-time extension to 512K using YaRN. Despite its compact active-paramet

---

### [293] VeriCam: A Verification Baseline for the Classification of Unknown Data

**链接**: https://arxiv.org/abs/2608.31107
**作者**: Lucas Wojcik and Gabriel E. Lima and Sergio M. Silva Jr. and Eduil Nascimento Jr. and David Menotti
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The advent of foundation models have enabled a new era in zero-shot classification. Yet, key challenges persist. Despite their impressive generalization power that leverages the immense pre-training knowledge, both foundation models for image and text as well as vision-text hybrids lack the representational power needed for fine-grained, minutiae-based class separation that some real-world tasks require. To address the current gaps in the literature, we propose VeriCam, a pipeline designed to learn highly specialized features that enable classification of unknown classes in unseen data. VeriCam works by leveraging the representation power of image models trained for the verification task, where the model develops an intricate feature space that incorporates fine-grained details. By training a model to discriminate between pairs of images from the same and different classes, a relational graph is constructed, representing the class relationships between data points. We then present two 

---

### [294] TSPFN: A Temporal Tabular Foundation Model for Physiological Time Series Classification

**链接**: https://arxiv.org/abs/2608.31013
**作者**: J\'er\'emie Stym-Popper, Cl\'ement Rambour, Federica Granese, Nicolas Thome, Olivier Bernard
**来源**: cs.LG cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Designing models that generalize effectively in low- to medium-data regimes remains a primary challenge in medical machine learning, particularly for physiological time-series classification. While tabular foundation models such as TabPFN offer an attractive alternative to conventional fine-tuning through in-context learning, they are not designed to capture the temporal dependencies inherent to physiological signals. ~In this paper, we introduce TSPFN, a foundation model that redesigns TabPFN's architecture for time series data. TSPFN integrates structured temporal representations and positional embeddings to capture intra-sample temporal and channel dependencies. To fully leverage its spatio-temporal design, the model is pretrained on 140,000 real-world physiological time series across multiple medical domains. This yields a unified, generalizable framework capable of learning the specificities of medical time series. Experiments across diverse physiological benchmarks demonstrate th

---

### [295] GeoRay: Gauge-Aware Feed-Forward Satellite 3D Reconstruction in the Geodetic Frame

**链接**: https://arxiv.org/abs/2608.29680
**作者**: Zhe Dong, Wanqing Wu, Yuzhe Sun, Haochen Jiang, Yuchen Ma, Lecheng Ren 等 (8 人)
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Feed-forward 3D foundation models reconstruct perspective scenes in one pass. Satellite photogrammetry needs a different product, one that domain adaptation alone does not deliver: dense surface height in an absolute geodetic frame under non-central rational polynomial cameras (RPCs). Perspective-pretrained features are not reliably observable along RPC height rays, absolute elevation carries a low-order height--datum gauge exchangeable with sensor bias to first order, and monocular and multi-view cues fail in different regions. \method{} treats all three. Lightweight ray-consistent adapters make a frozen backbone matchable along native RPC rays. An explicit datum mechanism separates relief from absolute level and is equivariant to the vertical origin by construction, so one trained model serves zero-, one-, and sparse-control inference. Calibrated inverse-variance fusion combines the two relief streams. \bench{}, our absolute-frame benchmark of eighteen systems across in-domain, cross

---

### [296] AGM: Achievement-Grounded Memory for Closed-Loop Agents with Frozen VLA Policies

**链接**: https://arxiv.org/abs/2608.29537
**作者**: Hongbo Gao, Zeyu Ni, Xin Wen, Siyu Xu, Ruifeng Li
**来源**: cs.RO cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Frozen vision-language-action (VLA) policies offer broad manipulation skills but execute open-loop action chunks without tracking task progress, so the agent cannot reliably decide whether to continue, retry, or terminate. External memory is a natural remedy, yet it can be harmful when attempted actions are treated as completed progress, turning local execution errors into persistent task-state errors. We propose Achievement-Grounded Memory (AGM), a lightweight closed-loop framework for frozen VLA policies that represents a task as a subgoal sequence with a progress pointer and advances this memory only after the current subgoal is verified by physical evidence. Proprioceptive interaction cues decide when to verify, while coherent point tracking and language-conditioned cross-view comparison, sourced from frozen foundation models through a single 2.43M-parameter verification head, decide what was achieved. AGM thereby converts open-loop execution into a closed loop of execution, verifi

---

### [297] BEACON: Behavioral and Semantic Enrichment of AlphaEarth Embeddings through Tri-Modal Contrastive Learning

**链接**: https://arxiv.org/abs/2608.29553
**作者**: Hao Tian, Heng Cai, Yifan Yang
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Geospatial foundation models such as the AlphaEarth Foundation produce compact and globally consistent representations of the Earth's surface that transfer effectively to a wide range of downstream tasks. However, because these models are trained primarily on Earth-observation imagery, their embeddings mainly capture physical and spectral characteristics while encoding human activity and urban function only weakly. To address this limitation, we propose BEACON, a tri-modal contrastive learning framework that aligns three complementary views of urban space: physical representations from AE embeddings, semantic representations from point-of-interest (POI) text, and human behavioral representations from hourly POI visitation, while keeping the deployed representation image-only. Using the Houston Metropolitan Area as a case study area, we evaluated the performance of the BEACON framework on nine downstream tasks, including seven regression and two classification tasks against six baseline

---

### [298] SGPDFuse: Semantically-Guided Physics-Disentanglement General Multi-Modal Image Fusion

**链接**: https://arxiv.org/abs/2608.29220
**作者**: Haozhen Wei, Chengjun Jiang, Yutong Guo, Xinrui Ju, Xingyuan Li, Xiang Chen 等 (7 人)
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal image fusion (MMIF) aims to integrate complementary sensor data into a single representation that preserves intrinsic scene reality while eliminating environmental interferences. Most existing approaches rely on blind feature aggregation, which excels at signal accumulation but fails to distinguish essential content from physical degradations. We propose SGPDFuse, which bridges this gap by mapping inputs into a physics-disentangled structural representation via a Semantic-Physical Parametric Bridge (SPPB) built on pretrained vision foundation models, utilizing the Intrinsic-Variation principle to decouple invariant scene attributes from transient environmental factors. To guide this decomposition, we introduce a Semantic Alignment mechanism: we explicitly anchor the fused representation to salient semantic features in the same foundation model feature space via cosine similarity to preserve critical targets, while enforcing physical texture fidelity through Gram-matrix regul

---

### [299] When the Martingale Never Stops Firing: Anytime-Valid Gating on Real Forecast Streams

**链接**: https://arxiv.org/abs/2608.30502
**作者**: Weijia Han, Lisha Qu
**来源**: cs.LG stat.ME stat.ML
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Machine learning systems are increasingly corrected while they run, and the decision of when to intervene is increasingly delegated to statistical monitors. Anytime-valid inference promises evidence that can be acted on at any moment, exactly the guarantee this setting needs, and it is moving from theory into deployed monitoring. Conformal test martingales are the change-detection instrument, and Ville's inequality caps their false-alarm probability on exchangeable data. The guarantee is conditional. A deployment inherits it only if the stream it monitors behaves exchangeably. The premise is hardest to satisfy where these monitors are most useful, on dependent data and inside loops where the monitor modifies the learner whose scores it reads. It is also rarely measured. We measure it in a pre-specified case study, where such a monitor gates the online updates of a Kalman adapter correcting frozen time-series foundation models on five forecasting streams. On exchangeable synthetic strea

---

### [300] Foundational feature fusion for conditional flow matching in 6D pose estimation

**链接**: https://arxiv.org/abs/2608.29183
**作者**: Amir Hamza, Davide Boscaini, Fabio Poiesi
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Conditional flow matching has enabled a step forward in object 6D pose estimation, achieving state-of-the-art performance by progressively denoising and registering object representations to observed scenes. Existing methods require training task-specific encoders supervised on object-scene overlap and rely on trivial feature fusion strategies to resolve pose ambiguities. We present FunFlow6D, a novel flow matching-based formulation that leverages features from geometric and appearance foundation models for pose estimation, eliminating the need for task-specific encoder training. We also introduce a cross attention-based fusion mechanism that dynamically combines geometric and appearance features to provide richer conditioning for the flow matching module. Experiments on four datasets from the BOP benchmark show that FunFlow6D outperforms the previous state of the art while reducing supervision requirements and memory overhead. Extensive ablations validate the contribution of each prop

---

### [301] OPUS: A Simple yet Effective Unified Framework for Open-Vocabulary Detection

**链接**: https://arxiv.org/abs/2608.30247
**作者**: Xiaoyan Wei, Zhimin Yao, Ruilin Yang, Wei Zhang, Yong Dai, Yi Zhang 等 (7 人)
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent unified open-vocabulary detection (OVD) supports heterogeneous prompts, including text queries, visual exemplars, and their combinations, but often rely on increasingly complex designs such as heavy cross-modal fusion, staged training, and iterative annotation pipelines. We revisit whether such complexity is necessary in the era of stronger foundation models. Our finding is that unified OVD can be made substantially simpler with semantic-rich visual representations and scalable grounding supervision. We present OPUS (\textbf{O}pen-vocabulary, \textbf{P}rompt-\textbf{U}nified, \textbf{S}imple), a unified detector supporting text, interactive visual, generic visual, and mixed prompting within one framework. OPUS adopts a simple three-part design. Its model architecture combines a semantic-rich visual encoder, built on a DINOv3-ConvNeXt-B backbone with efficient hybrid encoding, with a prompt-aware decoder that avoids prompt-specific branches for unified prompt reasoning. OPUS is t

---

### [302] Cost-efficient Active Learning for Referring Image Segmentation and Grounding

**链接**: https://arxiv.org/abs/2608.30621
**作者**: Junbeom Hong, Seonghoon Yu, Hyung Rok Jung, Sundong Kim, Jeany Son
**来源**: cs.CV cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Collecting natural-language referring expressions along with region annotations, such as masks or boxes, is a major bottleneck in visual grounding (VG), as annotators must write descriptions that distinguish target regions from visually similar ones. We tackle this by formulating active learning (AL) for VG under the realistic setting where only raw images are available without accompanying text. Since ground-truth text is unavailable, sample selection must estimate which images contain ambiguous regions that would require discriminative referring expressions. To address this, we generate auxiliary region-text pairs using foundation models, and introduce Referred Region Ambiguity, a new acquisition function that measures whether the model's confidence collapses onto a single region or disperses across multiple candidates. It allows our method to prioritize images with strong cross-region competition, which are more informative due to their visual ambiguity. We also design a referring-e

---

### [303] Dynamic-Robust Photometric-Semantic Reconstruction for Open-Vocabulary 3D Scene Understanding

**链接**: https://arxiv.org/abs/2608.29177
**作者**: Boyu Cai, Li Yang, Yan Xu, Wei Liu, Nian Liu, Sikui Zhang 等 (9 人)
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The integration of novel view synthesis (NVS) and open-vocabulary segmentation (OVS) has recently yielded powerful feed-forward 3D foundation models. However, their inherent reliance on static-scene assumptions leads to severe misalignment of spatial features in unconstrained dynamic environments. To bridge this critical gap, we propose SPAR, a novel joint semantic-geometric encoding architecture that explicitly isolates transient dynamic noise prior to latent space aggregation. Furthermore, we introduce a dynamic-region-aware end-to-end training paradigm that structurally couples motion estimation with multi-view visual and semantic learning. This unified approach enables the network to inherently resolve motion conflicts and distill multi-view consistent, temporally stable scene representations from dynamic inputs. Extensive experiments on the challenging D-RE10K benchmark demonstrate that SPAR achieves state-of-the-art performance. Our end-to-end approach achieves exceptional novel 

---

### [304] Context-Aware Interpretable Representations for Retrieval and Graph Convolutional Network Classification

**链接**: https://arxiv.org/abs/2608.29004
**作者**: Thiago C\'esar Castilho Almeida and Gustavo Rosseto Let\'icio and Vinicius Atsushi Sato Kawai and Daniel Carlos Guimar\~aes Pedronette
**来源**: cs.LG cs.CV cs.IR
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The advances in visual information modeling and representation during the last decades are remarkable, mainly supported by Convolutional Neural Networks, Transformer-based, and Foundation Models. Despite this progress, critical challenges regarding the nature of similarity assessment and model transparency have been neglected. A primary concern is the Geometric Gap, where traditional pairwise measures fail to capture the intrinsic geometry of the dataset manifold. Furthermore, the Interpretability Gap persists, as representations often lack alignment with human cognition. Therefore, how to provide interpretability to representations while maintaining low dimensionality and high effectiveness in downstream tasks remains an open challenge. In this paper, we propose a novel unsupervised framework that integrates Manifold Learning strategies with Rank-based Interpretable Graph Embeddings. Our approach effectively bridges these gaps by first characterizing the contextual information of the 

---
