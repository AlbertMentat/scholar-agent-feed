# 📑 论文索引 - 2026-10-16

共 177 篇论文

---

### [1] Scaling LLM Inference via Parallelism: Throughput-Latency Trade-off

**链接**: https://arxiv.org/abs/2610.19405
**作者**: Javad Mirzaei, Jeebak Mitra
**来源**: cs.DC cs.AI cs.LG cs.PF
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Model (LLM) serving systems must balance latency and throughput while efficiently utilizing distributed GPU resources. This challenge arises because inference consists of two fundamentally different phases: prefill, which determines time-to-first-token (TTFT), and decode, which determines inter-token latency (ITL). The use of tensor parallelism (TP), pipeline parallelism (PP), and hybrid configurations exposes different trade-offs between these latency dimensions, making the optimal parallelism configuration highly dependent on workload characteristics, latency requirements, and context length. Moreover, despite the widespread adoption of distributed inference, there is still limited understanding of how parallelism configurations should be selected under varying workload conditions and service-level objectives (SLO). In this paper, we develop a systematic framework for characterizing LLM inference parallelism via throughput-latency trade-offs, SLO-aware serving, and lon

---

### [2] Scoping the Landscape of Large Language Model-based Affective Personal Informatics: Review, Reflection, Future Direction

**链接**: https://arxiv.org/abs/2610.20084
**作者**: Minjie Liu and Lihuan Li and Xuran Li and Flora Salim and Benjamin Tag
**来源**: cs.HC
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Affective personal informatics (PI) involves capturing, tracking, analyzing, and reflecting on personal data to support emotional self-awareness and mental well-being. Recent advances in large language models (LLMs) are reshaping affective PI, yet a comprehensive survey of LLM-based affective PI systems is lacking. To bridge this gap, we systematically analyzed 45 papers published between January 2020 and June 2026 across four major computing and health databases, examining their macro trends, system taxonomies, and research methodologies. Our synthesis reveals an overreliance on multi-stage, text-centric pipelines, a predominance of active, screen-bound interactions, and a severe demographic skew toward young, university-campus-based cohorts in empirical evaluations. Based on these findings, we critically reflect on prevailing architectural and methodological shortcomings and outline actionable future directions for building end-to-end multimodal, low-burden, and inclusive affective P

---

### [3] Designing Textual Interfaces To Enhance Llm Reasoning On Audio-Visual Question Answering

**链接**: https://arxiv.org/abs/2610.20085
**作者**: Yi Wang, Tianzi Wang, Tong Lei, Dahan Wang, Peter Bell
**来源**: cs.AI cs.CL eess.AS
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Automatic prompt optimization (APO) has shown strong effectiveness for text-based LLMs and LLM systems, but its application to audio-visual understanding systems requires suitable textual interfaces through which multimodal reasoning can be exposed to text-based optimizers. We investigate how the design of textual interfaces affects prompt optimization for multimodal reasoning, on the audio-visual question answering task. We compare three interface designs, including a direct inference system consisting of a single omni-modal large language model (OmniLLM), a captioner-reasoner system, and an agentic architecture in which a primary agent orchestrates subagent OmniLLMs. Experiments with Qwen3-Omni and Gemini show that direct prompt optimization provides model-dependent gains; the captioner-reasoner system and the agentic system expose more interpretable optimization interfaces but are harder to optimize, where error analysis of cases affected by optimization is conducted. Our study high

---

### [4] XferAgent: Cross-Agent Experience Transfer for Self-Improving LLM Agents

**链接**: https://arxiv.org/abs/2610.19581
**作者**: Weihao Li, Jun Bai, Shijie Chen, Qincheng Lu, Xinyu Wang, Ziyang Song
**来源**: cs.MA cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents can reuse experience from prior task executions to improve performance on subsequent tasks. Although existing methods enable cross-agent experience sharing, differences in agents' execution histories and task requirements make shared experiences difficult to reuse effectively. We propose XferAgent, a framework for cross-agent experience transfer that organizes reusable experience in local and shared experience graphs. XferAgent reconciles compatible contributions from heterogeneous agents while avoiding unreliable merges. For each new task, it selects shared experiences and integrates them with the target agent's local experience to support task execution. Experiments across diverse task domains show improvements over representative memory-based methods and effective experience transfer between heterogeneous agent frameworks. Cumulative task success also increases over successive task passes as agents update and reuse their experiences.

---

### [5] PersEvalBench: Can LLM Evaluators Judge Contextually Appropriate Use of Persona Information?

**链接**: https://arxiv.org/abs/2610.19314
**作者**: Xinyi Liu, Hooshang Nayyeri, Emine Yilmaz, Dilek Hakkani-Tur, Charith Peris, Hari Thadakamalla
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) evaluators are increasingly used to assess personalized assistants, yet whether they can reliably judge personalization has rarely been tested. We introduce PersEvalBench, a benchmark testing whether an evaluator can recognize appropriate and inappropriate uses of user history. It contains 403 multi-episode scenarios where user information should persist, transfer, or cease to apply. The benchmark covers nine controlled error subtypes across three families: under-personalization, over-personalization, and misapplied-state errors. Human audits confirm that generated errors match their intended types and that the prescribed uses of user information are reasonable. Across five LLM evaluators, recognition of controlled personalization errors remains limited even with the full dialogue history. On the human-evaluated subset, under-personalization shows the largest gap: humans recognize 94.4% of these errors, compared with 63.9% for the strongest reported evaluator

---

### [6] EvoProbe: Evaluation-Driven Benchmark Evolution for LLM Agents

**链接**: https://arxiv.org/abs/2610.19433
**作者**: Qianhong Guo, Wei Xie, Xiaofang Cai, Shuoyoucheng Ma, Chengxin Hu, Baosheng Wang
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Static benchmarks for large language model (LLM) agents face saturation and data contamination risks, motivating continual updates to evaluation tasks. However, aggregate scores and success rates offer limited insight into specific problem-solving bottlenecks and provide limited guidance for subsequent task design. We propose EvoProbe, an evaluation-driven benchmark evolution framework that integrates task generation, diagnostic evaluation, and feedback-driven regeneration into a closed loop. It combines verifiable subtask outcome scoring with evidence-supported multi-judge trajectory evaluation and distills phase-level bottlenecks, success patterns, and failure patterns into diagnostic feedback for generating new executable tasks. Across two rounds of cybersecurity experiments, evaluations of eight models on 66 tasks reveal phase-level performance differences and common failure patterns beyond aggregate scores. In a cross-round comparison with the Examiner model set and solver configu

---

### [7] From Unreliable to Usable: Decomposing Failure Modes and Confidence Signals in LLM Entity Extraction - Evidence from Cyber Threat Intelligence

**链接**: https://arxiv.org/abs/2610.20417
**作者**: Jiahong Qian
**来源**: cs.CL cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Audits of large language model (LLM) extraction from full-length documents report severe unreliability, leaving two questions open: what the failures actually consist of, and whether confidence signals can turn unreliable output into usable output. We run a preregistered, fully frozen evaluation of two new-generation low-cost LLMs (DeepSeek-V4-Flash, GLM-5.3-Flash) with a flagship-tier control (GPT-6.1-Sol) on a public corpus of 354 incident campaigns (315 unique reports, 630 model-report evaluations), scoring extraction quality against gold, confidence calibration, and robustness to single-sentence perturbations. Three findings emerge. (1) Unreliability persists across tiers: micro precision is 0.03-0.34 and verbalized calibration error (ECE) 0.53-0.94 across both splits; the gap does not close at the flagship tier. (2) The dominant failure is not hallucination: a full mention census plus a three-tier annotation of 360 sampled candidates (two independent LLM annotators from vendors ou

---

### [8] SEA-HELM Audio: Evaluating Multilingual ASR-LLM Pipeline Performance Across SEA-HELM Subsets

**链接**: https://arxiv.org/abs/2610.19869
**作者**: Yixian Tan, Aulia Adila, Jonathan Heng, Kunat Pipatanakul, Donghang Wu and Anocha Sutaveephamochanon
**来源**: cs.SD cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We introduce SEA-HELM Audio, a Southeast Asian (SEA) multilingual evaluation framework that extends the text-based SEA-HELM benchmark to assess performance degradation in cascaded automatic speech recognition and large language model (ASR-LLM) pipelines. Using synthesized speech, we compare speech-input and text-input performance across five languages (Chinese, English, Malay, Indonesian, and Tamil) on multiple-choice reasoning and instruction-following tasks. We evaluate open-weight and commercial ASR-LLM systems using identical verifiers and quantify the speech gap as the difference between text and speech accuracy. Results show substantial degradation, with accuracy drops of 9.00 to 18.50 percentage points for multiple-choice reasoning and 20.00 to 42.86 points for instruction following. Tamil exhibits the largest degradation, exceeding 40 percentage points. Our findings highlight the limitations of text-only benchmarks in predicting voice-agent reliability and demonstrate the value

---

### [9] AgentSafeEvo: Adversarial Co-Evolution for LLM Agent Safety

**链接**: https://arxiv.org/abs/2610.19422
**作者**: Chenxu Wang, Xiaoyu Wen, Han Qi, Ziyuan Zhou, Cheng Jin, Chaochao Lu 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents accomplish complex tasks through multi-turn interactions with external tools. However, malicious content embedded in user queries, tool descriptions, or environment observations can manipulate their decisions and induce unsafe actions. Adversarial co-evolution has emerged as an effective approach to strengthening LLM safety, but existing work primarily focuses on language-level safety or indirect prompt injection in web tasks. In this paper, we introduce AgentSafeEvo, a co-evolutionary reinforcement learning framework for agent safety built on an attacker-defender game spanning diverse tasks and attack types. The attacker learns to construct adversarial agent tasks that expose weaknesses in the defender's tool use, while the defender learns to complete tasks safely under these attacks. We further introduce learnability-guided task weighting, which uses within-task defender-reward variability to adjust each task's contribution to attacker and defender u

---

### [10] When Extremists Enter LLM Societies: Investigating Extreme Behavior in Multi-Agent Systems

**链接**: https://arxiv.org/abs/2610.19863
**作者**: Guo Chen, Huaijin Xie, Ziwen Li, Reed Li, Yu Lu, Haibo Shi 等 (8 人)
**来源**: cs.MA
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents increasingly serve as computational actors in multi-agent social simulations. While existing work emphasizes representative personas and average-case behavior, social science shows that persistent tail actors can disproportionately shape collective dynamics. We study this regularity in controlled LLM-based multi-agent systems (LLM-MAS). In these systems, such actors cannot be reduced to fixed scalar states: prompts, natural-language histories, and backbone generation mediate their behavior and influence. We first analyzed three properties of extremists in sociology and model the LLM extremist based on LLM-native perspective. We introduce EXAM, an EXtremist Agent Modeling framework that capable of configuring extremist agents for specific tasks and precisely controlling their population proportion, spatial distribution, interaction protocols, and measurement interfaces. Across four scenarios: congressional election, financial crisis, epidemic public opi

---

### [11] RA$^2$: Retain-Anchored Attraction Preserves Forget-Adjacent Utility in LLM Unlearning

**链接**: https://arxiv.org/abs/2610.19385
**作者**: Zinan Ling, Yang Xiao, Ruimeng Ye, Sijia Liu, Bo Hui
**来源**: cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Model (LLM) unlearning is often evaluated primarily by target suppression and clean retain utility. These metrics can miss a local failure mode: a model may perform well on standard retain prompts, yet degrade on benign reasoning when prompts lie near the forgotten domain. This phenomenon is termed forget-adjacent utility loss. A fundamental question is: where should forget representations go after they leave the removed behavior? Successful unlearning depends not only on whether forget-conditioned representations depart from the harmful computation, but also on the direction in which they are redirected afterward. We propose RA$^2$ (Retain-Anchored Attraction), a latent-space unlearning method that redirects forget-token states toward nearby retain-supported representations while preserving higher-layer behavior on retain data. On WMDP and MUSE, RA$^2$ yields higher forget-adjacent utility than strong unlearning baselines at similar broad-utility levels. These results s

---

### [12] Retrieve What Helps, Only When It Helps: Agentic Reinforcement Learning for Selective Retrieval-Augmented Machine Translation

**链接**: https://arxiv.org/abs/2610.19528
**作者**: Shijun Li, Yang Liu, Najmeh Sadoughi, Dongmei Wang, Xinjie Li, Zhu Liu 等 (8 人)
**来源**: cs.CL cs.AI cs.IR
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Retrieving external knowledge can improve large language model (LLM) translation by providing supplementary information such as idiom interpretations and terminology. However, existing retrieval-augmented machine translation systems typically apply predefined retrieval strategies uniformly across all inputs. We argue that translation operates in a partial-evidence regime: LLM's parametric knowledge suffices for many inputs, while external evidence benefits a subset and usually supports rather than directly provides the desired translation. This creates two challenges: deciding when to retrieve and what evidence to acquire. We introduce Selective Retrieval-Augmented Translation (SRAT), an agentic reinforcement learning framework that learns when to translate directly or retrieve, what to retrieve, and how to integrate these decisions by optimizing final translation quality. To align evidence retrieval with downstream translation quality rather than simple semantic similarity, we further

---

### [13] EvalBuilder: Can LLMs Build Efficient Benchmarks?

**链接**: https://arxiv.org/abs/2610.20099
**作者**: Huaisheng Zhu, Hangfan Zhang, Teng Xiao, Siyuan Xu, Shijie Zhou, Zhimeng Guo 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents are increasingly used for long-horizon research and engineering, yet evaluating these capabilities remains expensive, time-consuming, and heavily dependent on human expertise. This motivates a natural question: can LLM agents themselves construct efficient benchmarks that preserve the conclusions of costly reference evaluations? We study this capability by formulating automatic benchmark development as a meta-evaluation problem, where an agent is given a task and an expensive reference benchmark and requested to construct a lower-cost proxy benchmark that faithfully distinguishes among candidate models and solutions. Based on this formulation, we introduce EvalBuilder, a framework for evaluating such benchmark-generation capabilities along three key dimensions: fidelity, efficiency, and robustness. Specifically, we assess whether generated benchmarks preserve model rankings, generalize to held-out models and freshly collected responses, and provide wel

---

### [14] Confidently Wrong: Detecting Hallucinations in Financial Question Answering from LLM Internal States

**链接**: https://arxiv.org/abs/2607.11414
**作者**: Richard Zhe Wang
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [15] TULIP: Targeted LLM Unlearning at Layers Identified Per-input

**链接**: https://arxiv.org/abs/2609.34591
**作者**: Yejin Kim, William F. Shen, Seokwon Jung, Daeun Park, Seong Joon Oh
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [16] From Structure to Validity: Mechanism-Guided Generation and Refinement of LLM Rubrics

**链接**: https://arxiv.org/abs/2610.13375
**作者**: Feifei Qian, Xuan Chen, Lixin Cui, Chaoyang Mei, Fanlin Meng, Shuyao Xiao 等 (9 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [17] Review Rarely Beats the Stronger Model: Separating Verification from Capability Transfer in LLM Pipelines

**链接**: https://arxiv.org/abs/2610.15897
**作者**: Yirui Zhang, Yash Raj Shrestha
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [18] Divergent Paths: Learning an Outcome-Predictive Representation of LLM Agent Trajectories

**链接**: https://arxiv.org/abs/2610.19614
**作者**: Alexander Gill, Guram Gogia, Francisco Guzm\'an
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In this work, we reframe agentic trajectories as paths through a shared embedding space of actions and environmental observations. We show that successful and failed rollouts of the same task separate in this space, with simple per-task discriminators predicting held-out rollout outcomes at up to 0.95 AUROC across three agent benchmarks and three policy models. To exploit this signal across tasks, we introduce Precog-RM, a transformer-based model that meta-learns a representation in which outcome prediction can be performed in a few-shot setting. We show that Precog-RM generalizes to unseen tasks and models, and gives confident predictions of trajectory success long before termination. Deployed as an early stopping controller for Group Relative Policy Optimization (GRPO) on Tau2-Bench, Precog-RM cuts training FLOPs by up to 47.3\% while maintaining performance comparable to baseline GRPO.

---

### [19] Reclaiming Low-Quality Instruction Data with Rule-Guided LLM Reconstruction

**链接**: https://arxiv.org/abs/2510.23160
**作者**: Zile Yang, Ling Li, Na Di, Jinlong Pang, Yao Zhou, Hao Cheng 等 (8 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [20] JockeyBench: Evaluating LLM Agents on Horse-Racing Decision-Making

**链接**: https://arxiv.org/abs/2610.19589
**作者**: Zhongwei Xie, Xingsu Li, Jingqiao Yu, Zihao Wang, Hong ChiTat, Zhaowei Wang 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Repeated event forecasting requires extracting predictive signals from noisy evidence and evaluating their value across successive decisions. We introduce JockeyBench, a benchmark and evaluation protocol that studies this problem through historical Japanese horse racing. The protocol combines time-gated evidence, priced tools, paired frozen-program controls, and two workflows: executing an LLM-written predictor or acquiring evidence for a fresh per-race LLM forecast. Evaluation separates forecast quality, benchmark-specific net utility, and retrospective betting returns and risk under fixed decision rules. Across 28 model--scaffold configurations on 324 races, paired tests identify seven revision gains and two declines after multiple-testing correction. Yet every configuration has negative mean profit under capped-Kelly settlement. In a four-model comparison, the reusable-program workflow has higher mean betting profit and lower research fees, although both workflows lose on average. F

---

### [21] RouteWeaver: Weaving Mode Selection and Execution into Unified LLM Routing

**链接**: https://arxiv.org/abs/2610.19705
**作者**: Xiaohan Wang, Haozhen Zhang, Qingyuan Liu, Tao Feng, Wenya Wang
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM routing dynamically selects and coordinates heterogeneous language models across diverse tasks. However, existing approaches are largely built around a predefined execution paradigm, such as single-round, multi-round, or agentic routing, which fixes how model calls are organized and limits adaptation to different query needs. We propose RouteWeaver, a unified routing framework that integrates these routing modes within a single LLM policy, jointly learning which mode to use and how to select models within that mode. To jointly optimize mode selection and within-mode execution, we develop COMET-GRPO (COordinated Mode-Execution Training), which decouples the trajectory-level advantage into separate signals for mode selection and within-mode execution, enabling more targeted credit assignment to each decision level. We further introduce progressive exploration, which gradually shifts training from externally assigned modes to autonomous selection, so that the router first learns how t

---

### [22] MemCode: Discrete Semantic Representations for Long-Term Agent Memory

**链接**: https://arxiv.org/abs/2610.19472
**作者**: Xin Li, Liang Hu, Duoqian Miao, Ming Peng, Qi Zhang
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-term memory remains a fundamental bottleneck for large language model (LLM) agents across sessions. Existing systems typically adopt a write-then-retrieve paradigm, storing context-dependent dialogue fragments and retrieving them via nearest-neighbor search in a continuous embedding space. This design yields unstable access units and systematically misses logically related but lexically distant evidence. We propose MemCode, a long-term agent memory framework that couples retrieval-oriented writing with discrete associative retrieval. MemCode rewrites dialogue into self-contained atomic memory units (AMUs), maps AMUs into a learnable codebook with isomorphic semantic quantization (ISQ), and uses codebook co-occurrence topology as a retrieval path complementary to vector search. For long-term memory stores, MemCode separates online atomic writes from asynchronous offline consolidation. On LongMemEval-S and LoCoMo with GPT-4o-mini and Qwen3-30B-A3B-Instruct-2507 backbones, MemCode ac

---

### [23] LLM-jp-4 Technical Report

**链接**: https://arxiv.org/abs/2610.19331
**作者**: LLM-jp: Chaoran Liu, Daisuke Kawahara, Hideyuki Tachibana, Hirokazu Kiyomaru, Jun Suzuki, Koshi Eguchi 等 (10 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> This paper presents LLM-jp-4, a family of Japanese sovereign large language models (LLMs) developed with an emphasis on transparency, reproducibility, and practical usability. LLM-jp-4 comprises an 8B dense model and a 32B-A3B mixture-of-experts model, both trained from scratch on approximately 12 trillion tokens. To support independent verification and reproduction, we establish explicit criteria for selecting training data, external models, and software, and make the development process publicly available. Evaluation results demonstrate substantial improvements over previous LLM-jp models and competitive performance against open-weight models of similar scale. By documenting the development principles, training procedures, and empirical findings of LLM-jp-4, we aim to provide a reference for future sovereign AI development.

---

### [24] SpectrumQuant: Spectrum Alignment for LLM Quantization

**链接**: https://arxiv.org/abs/2610.20303
**作者**: Dwaipayan Haldar, Indranil Patra, Azhar Yousuf, Chandra Sekhar Seelamantula
**来源**: cs.LG stat.ML
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Orthogonal transforms have emerged as an effective tool for low-bit quantization of large language models (LLMs), as they reshape activation distributions without changing the underlying model function. Existing approaches typically rely either on fixed data-agnostic transforms, such as Hadamard rotations, or on calibration-time optimization of learned rotations. We study rotation selection from first principles and show that maximizing covariance leads to spectral alignment and provides a principled criterion for constructing quantization-friendly orthogonal transforms. Based on this insight, we propose SpectrumQuant, a closed-form rotation method that estimates activation covariance from calibration data and uses it to construct a covariance-aware orthogonal transform for post-training quantization. Our formulation characterizes quantization-friendly rotations as compositions of alignment and mixing components, while recovering Hadamard matrices as a special case. Interestingly, a cl

---

### [25] The Instability of Safety: How Random Seeds and Temperature Expose Inconsistent LLM Refusal Behavior

**链接**: https://arxiv.org/abs/2512.12066
**作者**: Erik Larsen
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [26] From Relevance to Validity: Zero-Shot Tool Selection via Functional and Contextual Validation

**链接**: https://arxiv.org/abs/2610.20388
**作者**: Xiaoxuan Dong, Jin Zhang, Zichen Yuan, Yue Zhou, Zihao Rao, Dexu Yu 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents increasingly face tasks from unseen domains and execution contexts, making zero-shot tool selection essential for identifying tools that can satisfy task requirements. Existing dominant methods mainly rely on relevance ranking, but semantic matching alone cannot ensure that a tool is functionally compatible or remains applicable in a new context. We preliminarily identify a \emph{transfer-validity gap}, where semantically relevant tools may still fail to satisfy functional or contextual requirements after transfer. To address this gap, we propose \methodname{}, a progressive validation framework that complements semantic relevance with endpoint-grounded functional compatibility and task-conditioned contextual evidence. Across cross-domain and cross-dataset transfer, \methodname{} consistently improves capability ranking, with larger gains under functional or contextual ambiguity. Ablation results further confirm the complementary contributions of funct

---

### [27] LLMON: An LLM-native Markup Language to Leverage Structure and Semantics at the LLM Interface

**链接**: https://arxiv.org/abs/2603.22519
**作者**: Michael Hind, Basel Shbita, Bo Wu, Farhan Ahmed, Chad DeLuca, Nathan Fulton 等 (8 人)
**来源**: cs.SE cs.AI cs.PL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [28] TopicMerge: A Divide and Conquer Approach to Topic Modeling

**链接**: https://arxiv.org/abs/2610.19323
**作者**: Matthew Raffel, Lizhong Chen, Sai Munikoti, Sameera Horawalavithana
**来源**: cs.CL cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent advancements in topic modeling have split into two main paths: efficient embedding-based methods that offer scalability but are often outperformed on standard clustering metrics, and Large Language Model (LLM) approaches that achieve state-of-the-art clustering performance but at the cost of prohibitive computational expense and poor scalability. This paper introduces TopicMerge, a novel multi-stage pipeline that bridges these approaches to achieve both state-of-the-art clustering performance and computational efficiency. TopicMerge first employs an efficient clustering pipeline to deliberately over-segment a document corpus into a large set of fine-grained, semantically pure micro-clusters, which are then given initial semantic labels. It then introduces a novel, iterative merging algorithm where an LLM, guided by local neighborhood context, arbitrates on consolidating candidate pairs. These approved merges are then selectively executed and semantically relabeled by the LLM, hi

---

### [29] Where to Start, How to Move: Analyzing Curricula under GRPO for Long-Horizon LLM Agents

**链接**: https://arxiv.org/abs/2610.19349
**作者**: Minchan Kim, Sungho Bae, Youngjin Kim, Hyunwoo Park
**来源**: cs.LG cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Group Relative Policy Optimization (GRPO) provides no reward-relative learning signal when all rollouts receive identical rewards. In long-horizon tasks that require multiple interactions, rewards are given only upon successful task completion, making all-fail groups common early in training and limiting opportunities to practice later steps. Guide Assisted GRPO replays a successful reference prefix before the learner continues. We study how initial positions, handoff units, and movement rules affect unassisted task completion. Across three model sizes on BFCL, starting near completion is more effective under a fixed turn-level threshold rule. Finer handoffs alone do not consistently help, but outcome-informed tool-call selection outperforms GRPO on trained and untrained task categories. Guided starts also improve AppWorld success on both evaluation splits. These findings highlight where learning starts and how starting positions move as key curriculum choices.

---

### [30] GraphRAG-LTM: A Layered Threat Modeling Framework for Attacks on Graph Retrieval-Augmented Generation

**链接**: https://arxiv.org/abs/2610.19549
**作者**: Yining Tang, Junyu Zhang, Haomiao Qiu, Yongchao Liu, Jiajun Zheng, Zhao Wang 等 (8 人)
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Graph retrieval-augmented generation (GraphRAG) uses document-derived knowledge graphs to assemble evidence for large language model (LLM) answers. Its security depends on both the seed chunks retrieved for a query and the graph evidence assembled from them, yet attacks on this evidence path remain underexplored. We introduce GraphRAG-LTM, a Layered Threat Modeling framework that tests three nested levels of attacker access. BB Query uses ranking feedback to make query edits under a semantic-similarity constraint and demote relevant seed chunks. WB Query uses retriever gradients for the same objective. Graph-aware WB keeps the white-box adversarial query and deletes bridge triplets from the query-specific evidence graph, disrupting multi-hop evidence propagation through localized graph edits. Across datasets, retrievers, and LLM backbones, rank feedback alone reduces answer quality, gradient access strengthens query attacks, and bridge-triplet deletion further impairs supporting-fact r

---

### [31] Did the LLM Answer the Question? A Semantic Reconstruction Game for Jailbreak Evaluation

**链接**: https://arxiv.org/abs/2610.19306
**作者**: Liam Davis, Romain Emil-Popescu, Suman Jana
**来源**: cs.LG cs.CR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Jailbreak attacks against large language models (LLMs) are evaluated using attack success rate (ASR), which depends on correctly identifying responses that fulfill prohibited requests. Existing evaluators can mistake refusals or topically related responses for successful attacks. We show that changing only the judge LLM can alter reported ASR by up to $82$ percentage points. We introduce the semantic reconstruction game, a training-free evaluator that decomposes compliance judgments into constrained semantic comparisons. Given only a response, an LLM reconstructs the request answered by its substantive content, excluding information merely repeated or refused. The game compares this reconstruction against similar decoy requests to determine whether it matches the original request, allowing abstention when neither candidate matches. Across three off-the-shelf LLM judges, the game achieves the lowest mean error against human labels among evaluated methods and reduces variation in reporte

---

### [32] From Clicks to Intent: Cross-Platform Session Embeddings with LLM-Distilled Taxonomy for Financial Services Recommendations

**链接**: https://arxiv.org/abs/2606.26277
**作者**: Dianjing Fan, Yao Li, Kyaw Hpone Myint, Dwipam Katariya, Alexandre G.R. Day, Pranab Mohanty 等 (7 人)
**来源**: cs.IR cs.AI cs.CE cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [33] AgentCIScope: Grounded Contextual Integrity Evaluation for LLM Agents

**链接**: https://arxiv.org/abs/2610.19158
**作者**: Chengquan Guo, Zhaorun Chen, Zinan Lin, Xiaodong Liu, Bo Li
**来源**: cs.AI cs.CR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents are becoming increasingly capable of handling daily workspace tasks by interacting with application environments through tool calls. However, as agents read and write sensitive user data across email, documents, and other applications, a central privacy question is whether they preserve contextual integrity (CI), that is, whether the information flows they produce comply with context-specific disclosure constraints. Existing work either focuses on model-level privacy leakage or evaluates agents in limited application environments with manually constructed disclosure constraints. In this work, we introduce AgentCIScope, a unified platform and benchmark for evaluating agent-level contextual integrity through executable, multi-step tasks across diverse, realistic application environments. AgentCIScope transforms public and synthetic privacy cases into executable agent tasks, with disclosure constraints grounded in three criteria: governing privacy policies, persona-based agreem

---

### [34] Refusing Intent, Not Form: Wrapper-Based Intent-Group Supervision for LLM Safety

**链接**: https://arxiv.org/abs/2608.13304
**作者**: Ping Wu, Haibo Tong, Feifei Zhao, Han Shen, Yu Shi, Yilin Zhao 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [35] SecureClaw: Clawing Back Control of LLM Agents

**链接**: https://arxiv.org/abs/2606.09549
**作者**: Yuhan Ma and Stefan Schmid
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [36] SAGE: Structured Strategic Reasoning for Efficient LLM Game Playing

**链接**: https://arxiv.org/abs/2609.34342
**作者**: Zhiwei Chen and Tianchun Wang and Zhongtao Rao and Haiming Zhu and Ding Cao and Tianxiang Zhao
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [37] Drivers of LLM Consensus Formation Under Competing Incentives: A Simulation Study

**链接**: https://arxiv.org/abs/2610.20200
**作者**: Isabel Jones, Matthew Edwards, Janina A. Hoffmann
**来源**: cs.AI cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) are increasingly deployed in multi-agent environments that produce unanimous agreement, both in intended interactions that need coordination and in unintended emergent interactions. Consequently, understanding how LLMs with competing incentives reach consensus is crucial to better interpret and design LLM collectives. We introduce an evaluation, based on the Network Consensus game, to assess the mechanisms driving this process. Here, a network of agents must agree on one of two colours to receive a payoff, but agents are offered different payoffs for the agreed colour. We vary components such as communication access and network structure and assess six open-source models and one closed model (ChatGPT 5.6-sol). We find that open-source LLMs reach consensus less often than humans in comparable experiments and only if messages are communicated across the global network. ChatGPT 5.6-sol, however, is able to reach consensus with communication limited to its neig

---

### [38] Contextual Credit Policy Optimization

**链接**: https://arxiv.org/abs/2610.19103
**作者**: Huiwen Han, Ziyao Zeng, Zihao Zhu, Sisong Bei, Hao Wang, Hongyu Xu 等 (9 人)
**来源**: cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Group-based reinforcement learning enables large language model agents to learn from sparse outcome rewards in long-horizon tasks. Recent methods derive step-level credit by comparing observation-matched experiences across trajectories. However, identical observations can occur in different contexts, and matched peers are not equally informative for a given decision. Moreover, favorable terminal outcomes can obscure redundant actions or detours within successful trajectories. To address these two challenges, we propose Contextual Credit Policy Optimization (CCPO). For the first, CCPO weights observation-matched peers from other trajectories by contextual similarity, computed from frozen LLM representations and accumulated trajectory statistics, allowing peers from similar contexts to contribute more to a step's baseline. For the second, CCPO pairs historical credit, which compares the realized return against the weighted peer baseline, with future credit, which measures the change in c

---

### [39] From Training to Escalation: Forensic Analysis and Local Recreation of RL/RLHF-Induced Privilege Escalation in AI Agents (CVE-2026-65616)

**链接**: https://arxiv.org/abs/2610.20437
**作者**: Alicia Colmenero-Fern\'andez
**来源**: cs.MA cs.AI cs.CR
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Mid-2026 reporting on autonomous AI evaluation incidents claimed that frontier large language model (LLM) agents escaped server containment through emergent coordination and cloud infrastructure attacks. This paper contextualizes those claims through forensic analysis and containerized recreation of both the Highly Persistent Internal Model (HPIM) training-case conditions and the Phase One privilege escalation targeting internal package repositories during OpenAI's ExploitGym evaluations. We recreate the configuration of the OpenAI-provided training example and reproduce the cryptographic verification bypass (CVE-2026-65616) in isolated repository servers, where misconfigured systems enabled token forgery and privilege escalation through basic HTTP requests, Python, and JavaScript. Crucially, the training-example conditions and the Phase One (and later) misconfigurations share the same exploitable patterns. Our analysis explains how Zero Trust Architecture principles neutralize this sh

---

### [40] Can LLM Agents Efficiently Identify Appliance Faults? Insights From Diagnosing a Simulated Appliance

**链接**: https://arxiv.org/abs/2610.19291
**作者**: Lucas H. McCabe, Sarah Lukens, H. Howie Huang
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In so-called "Industry 4.0," integrated sensors, analytics tools, and other digital technologies supplement industrial workflows, potentiating enhanced visibility and automation. Prognostics and health management (PHM) and natural language processing (NLP) practitioners alike have explored the application of large language models (LLMs) to industrial asset management, but many prior works' focus on exam-like benchmarks has limited their assessment of LLMs' ability to automate practical operations. Herein, we introduce CoffeeBench, a fault diagnostics task for LLM agents, using a simulated appliance. The LLMs we evaluate struggle to consistently identify faults from the sensor information alone, but the best-performing ones can iteratively refine the fault-option space to eventually obtain a successful diagnosis. Our subsequent analyses, therefore, focus on: differentiating models by diagnostic efficiency (RQ1); examining the lagging performance of the three worst models (RQ2); and iden

---

### [41] New Model, Old Habits: Behavior Transfer under Model Swapping in Multi-Session LLM Agents

**链接**: https://arxiv.org/abs/2610.19712
**作者**: Youngbin Choi, Sehyun Hwang, Suhyeon Jun, Seoyeon Lee, Sunghyun Choi, MoonJeong Park 等 (7 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-session agents can switch between LLMs to balance performance and inference cost. Such switches require transferring a history for continuity, yet their effects on the recipient remain underexplored. Through controlled experiments with multi-session tasks, we uncover behavior transfer: recipients tend to adopt reasoning and action patterns from the models that generated their histories. This effect is most evident with raw-history transfer but is substantially reduced by summarization. Based on these findings, we propose Direction- and Authorship-aware Summarization of History (DASH) that preserves stronger-model behavior while minimizing weak-to-strong transfer via summarization. Experiments with repeated swaps show that DASH outperforms raw-history transfer and naive summarization baselines. These results suggest that effective multi-model orchestration requires considering not only which model to use, but also which behavioral patterns to carry forward.

---

### [42] Retrieval-Augmented Large Language Model Decision-Making for Autonomous Driving Guided by Chinese Philosophical Wisdom

**链接**: https://arxiv.org/abs/2610.03948
**作者**: Xiaojun Bi, Xiaoyuan Ma, Yiwen Sun, Tianren Huang, Chaoran Liu, Bokai Huang 等 (8 人)
**来源**: cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [43] Beyond LLM Judge: Mechanical Verification for Agentic Autoformalization

**链接**: https://arxiv.org/abs/2610.20573
**作者**: Anna Mei, Michael R. Douglas
**来源**: cs.LO cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We introduce a novel method for verifying Lean formalizations that goes beyond LLM-judged faithfulness. Unlike most verification methods, which rely on LLMs or trained models, our method combines LLM-based semantic review with mechanical numerical and vacuity checks, providing checkable feedback and detecting errors missed by LLM judges. We apply this method, along with our Extract-Verify-Proof autoformalization pipeline, to construct the Formalized Library of Mathematical Functions (FLMF), a partial formalization of the NIST Digital Library of Mathematical Functions (DLMF). On three labeled datasets, our method achieves the lowest accepted-error rate among the evaluated methods, measured as the fraction of incorrect statements accepted by the verification method. Expert review of the results also identifies translation and source defects in existing datasets. Code available at https://github.com/annamei1/FLMF-Ch7ErrFunc-Release.git.

---

### [44] When Protection Overrides Consequences: Understanding Protection Mode in Large Language Model Decision-Making

**链接**: https://arxiv.org/abs/2610.19948
**作者**: Yuanfan Li, Junyi Chen, Qi Zhou, Rui Yang, ZhangLiujie, Weihang Chen
**来源**: cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Frontier language models excel at complex tasks yet may prioritize protection over larger physical consequences in simple, urgent decisions. GPT-5.6 Sol, for example, moves a girl playing in shallow water before retrieving a submerged camera. We call this Protection Mode and study it with ProtectionBench: 285 prompts, 34 physical families, and nine models. At lowest effort, at least one of four responses prioritizes the subject on 34.74% of Sol prompts and over 83% of MiniMax M3 and Qwen3.5-27B prompts; none of four independent human raters does so. Controls show that choices usually track physical risk. We elicit both risks before requesting an action. Some models assess risk incorrectly; others state the correct ordering but still choose the subject. Qwen3.5-27B with thinking shows 100% correct risk ordering but 57.81% subject choice among eligible conversations on eight selected scenes. Attention audits find no stable reduction in attention to relevant facts; removing the stated ris

---

### [45] PN-Mix: Pair-Norm Guided Mixed-Precision Key Cache Quantization for Efficient Long-Output LLM Inference

**链接**: https://arxiv.org/abs/2610.19605
**作者**: Gil Jae Song, Sungjoo Yoo
**来源**: cs.LG cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-output inference in large language models suffers from severe KV cache memory and bandwidth bottlenecks. While KV cache quantization alleviates this issue, low-bit quantization (e.g., 2-bit) severely degrades model accuracy. Recent mixed-precision key-cache quantization methods mitigate this degradation by allocating higher precision to important key channels, but estimate channel saliency using only key statistics. Through attention logit perturbation analysis at the RoPE channel-pair level, we show that quantization errors in channel pairs with large query--key pair-norm products contribute significantly to logit variation. Based on this insight, we propose PN-Mix, a mixed-precision key-cache quantization method for RoPE-based decoder-only LLMs, which allocates higher precision to salient channel pairs identified once during the prefill stage and reused throughout decoding. Across standard reasoning, code-generation, and AIME benchmarks, PN-Mix with 2.26-bit average precision ac

---

### [46] SQD-Agent: LLM-driven agentic framework for Quantum Chemistry workflows

**链接**: https://arxiv.org/abs/2609.39302
**作者**: Kislaya Tiwari, Anupama Ray
**来源**: quant-ph cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [47] Anticipatory Evaluation of Language Models: Predicting LLM Benchmark Scores from Descriptions

**链接**: https://arxiv.org/abs/2509.20645
**作者**: Jungsoo Park, Ethan Mendes, Gabriel Stanovsky, Alan Ritter
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [48] STRATA: Self-Maintaining Structured Experience Graphs for Self-Evolving Language Agents

**链接**: https://arxiv.org/abs/2610.19386
**作者**: Guanhua Zhu, Hanwen Li, Zhi Wei, Mengnan Du, Chenxi Yuan
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents can self-evolve at test time by accumulating experience: retrieving relevant memories before acting and writing new lessons back afterwards. Yet most are single-level: trajectories, distilled workflows and reasoning items all land in one undifferentiated pool indexed by embedding similarity, with no typed abstraction hierarchy. They never forget or deduplicate, and are prone to negative transfer, where a superficially similar but directionally opposite experience is recalled and its concrete steps are copied verbatim, actively harming the agent. We introduce STRATA, a structured, outcome-grounded, self-maintaining memory that organizes experience into a three-layer graph of atomic skills and code snippets, task workflows and generalized meta-frameworks, connected by typed edges. STRATA maintains itself through five mechanisms sharing one similarity geometry: a multi-dimensional similarity that scores retrieval by operation and target; a typed reflector

---

### [49] Design Creativity Bench: Measuring creativity in LLM-Generated UI

**链接**: https://arxiv.org/abs/2610.11539
**作者**: Aman Rusia, Abhijit Bhole, Prashank Gupta, Dipanjan Dey
**来源**: cs.HC cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [50] MAPLE: A Multi-Axis Parametric Knowledge Extraction Lens for LLM Evaluation

**链接**: https://arxiv.org/abs/2610.19827
**作者**: Minsuh Joo, Youna Kim, Choonghyun Park, Soo Kyung Kim, Hyunsoo Cho
**来源**: cs.LG cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLMs absorb vast knowledge from training data, yet their inherently probabilistic nature offers no guarantee that this knowledge will surface in their outputs. To bridge this gap, Knowledge Extraction Enhancement (KEE) techniques such as activation steering, decoding adjustments, and prompting modify inference, potentially reinforcing existing predictions or surfacing less accessible answers. Yet their evaluations centered on aggregate accuracy, which obscures diverse effects by collapsing recovered failures and disrupted successes into a single score. We introduce MAPLE, a unified framework for characterizing how KEE techniques affect parametric knowledge extraction. Its diagnostic metrics disentangle these effects at the surface, probability, and beyond-sampling levels by measuring answer recovery and disruption, gold-token rank shifts on unrecovered failures, and recovery of answers missed by fixed-budget sampling. We evaluate six KEE techniques spanning decoding, activation steerin

---

### [51] Plant Memory: Technical Language Processing and a Verified Maintenance Ontology for Agent-Accessible Failure Knowledge from SAP PM Work Orders

**链接**: https://arxiv.org/abs/2610.19131
**作者**: Akash Raj
**来源**: cs.AI cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Maintenance work orders are the largest written record of how industrial equipment fails, yet in most plants they are close to unusable for analysis. Short texts are abbreviated and misspelt, asset identity is buried in free text, work-type labels contradict the work described, and the fields that matter most for reliability (symptom, root cause, action taken) are usually empty. As a result, diagnostic knowledge stays with senior technicians and leaves when they do. We present Plant Memory, a system that applies technical language processing (TLP) to SAP Plant Maintenance (PM) exports and builds an ISO 14224-aligned maintenance ontology in which every extracted statement is a reified fact carrying a confidence score, the evidence it was read from, and a verification state. Extraction is rule-first, with an optional large language model (LLM) acting as a second reader whose disagreements raise a fact's review priority rather than overwrite it. Technicians verify facts through a review q

---

### [52] Human and LLM Facilitation in Collaborative Design Meetings: A Computational Behavioral Comparison

**链接**: https://arxiv.org/abs/2610.13082
**作者**: Mohammed Azeez Khan, Aaron Dsouza, Ashutosh Mishra, Ummul Faiz Z. Bibi, Neha K. Nair, and Arshaan Khan
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [53] Old Ideas, Novel Problems: The Instability of LLM-Based Novelty Evaluation

**链接**: https://arxiv.org/abs/2610.02022
**作者**: Noy Sternlicht, Simra Shahid, Peter Jansen, Daniel S. Weld, Pao Siangliulue, Tom Hope
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [54] LycheeMemory V2: Efficient Long-Term Memory for LLM Agents via Semantic Segment-Level Consolidation

**链接**: https://arxiv.org/abs/2608.12990
**作者**: Dongfang Li, Zixuan Liu, Junmai Wang, Jiahe Huang, Fuhao Li, Lin Zhang 等 (8 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [55] Automated Standardization of Legacy Biomedical Metadata Using an Ontology-Constrained LLM Agent

**链接**: https://arxiv.org/abs/2604.08552
**作者**: Josef Hardi, Martin J. O'Connor, Marcos Martinez-Romero, Jean G. Rosario, Stephen A. Fisher and Mark A. Musen
**来源**: cs.DB cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [56] Not All Criteria Matter: Importance-Aware Criteria Weighting for Rubric-Based LLM Evaluation

**链接**: https://arxiv.org/abs/2610.19915
**作者**: Haocheng Yang, Licheng Pan, Yiming Dong, Xiaoxi Li, Yuan Lu, Zhenhao Chen 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Rubric-based evaluation assesses the responses of large language models (LLMs) by aggregating the verification results of explicit criteria, yet not all criteria matter equally. However, existing methods commonly aggregate the verification results with uniform weighting, which assigns minor and overlapping criteria the same weight as essential ones and thus produces misleading evaluation scores. Although some methods prompt an LLM to directly assign weights, direct weighting requires a holistic judgment over all criteria that LLMs struggle to make reliably. To address these limitations, we propose Importance-Aware Criteria Weighting (ICW), which derives the weights of criteria from pairwise importance comparisons made by an LLM. Specifically, ICW transforms the holistic judgment over all criteria into a series of pairwise importance comparisons, checks and revises inconsistent comparisons, and derives the weights from the principal eigenvector of the comparison matrix. Extensive experi

---

### [57] Beyond Corrected Actions: Training LLM Agents on Textual Critiques

**链接**: https://arxiv.org/abs/2610.19367
**作者**: Thomas Zeng, Zelei Cheng, Mingyang Zhou, Sambit Sahu, William Campbell, Genta Indra Winata
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly used for multi-turn agentic tasks that require interactions with users and environments over extended sequences of actions. A common approach to improving LLM agents is to use more capable expert models to provide training supervision, either by behavior cloning the expert's trajectories or by using the expert to correct the actions in trajectories generated by the weaker student model. However, expert LLMs can provide richer supervision than actions alone: they can directly generate textual critique that explain why specific actions are incorrect. We study whether training on such feedback benefits LLM agents and propose Critique-Augmented Agentic Fine-Tuning (CAFT), a framework that elicits textual expert feedback on student-generated trajectories. For each incorrect action, the expert yields both a corrected action and a textual critique explaining the student's mistake--which we then use as the training target for fine-tuning. Across fo

---

### [58] ARAFA: An LLM-Generated Arabic Fact-Checking Dataset

**链接**: https://arxiv.org/abs/2609.25833
**作者**: Christophe Khalil, Shady Elbassuoni, Rida Assaf
**来源**: cs.CL cs.IR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [59] Measuring and Reducing Unusable Replies of LLM Agents

**链接**: https://arxiv.org/abs/2610.19659
**作者**: Yilin Jiang, Fei Tan, Xuanyu Yin, Guanchu Wang, Xia Hu, Yutao Yue
**来源**: cs.CL cs.AI cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> People delegate multi-step work to LLM agents and read only the reply that the agent hands back. Current evaluation scores task completion and the faithfulness of reports, and it leaves open whether the requester can understand and use the reply. We call this property reply usability and measure it with a reader model that takes the requester's position and tests whether the reply can be interpreted from what the requester has seen, is in the requester's language and answers the request. Its agreement with the majority of five annotators lies within the range of the individual annotators. Across eight models from seven families, 54% of 480 replies fail, and the best model still fails on 30%. Failed replies mostly point to material the requester has not seen or use labels that the agent coined during its work. Stating explicit requirements for the reply reduces the failure rate from 0.52 to 0.43 together with errors and omissions, and a secondary model that rewrites the reply reduces it

---

### [60] ContextWeaver: Selective and Dependency-Structured Memory Construction for LLM Agents

**链接**: https://arxiv.org/abs/2604.23069
**作者**: Yating Wu, Yuhao Zhang, Sayan Ghosh, Sourya Basu, Anoop Deoras, Jun Huan 等 (7 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [61] DUALVIEW: Leveraging Broad and Output-Specific Evidence for LLM-based Multi-Output Text Regression

**链接**: https://arxiv.org/abs/2610.19206
**作者**: Yiheng Su, Junyi Jessy Li, Matthew Lease
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> While work on LLM-based regression has largely focused on scalar prediction, multi-output text regression remains less explored. We present DualView, a parameter-efficient approach to leverage LLMs for multi-output text regression. \method{} first extracts broad and output-specific representations from a frozen LLM, then uses a dual-branch architecture to produce the full score vector. Across five heterogeneous regression tasks and eight LLMs (up to 122B), DualView outperforms seven supervised regression baselines while requiring 82--1842 times fewer fitted parameters than the three strongest baselines. These improvements extend across individual output dimensions and persist even with limited training data. Notably, DualView using a smaller open-weight LLM can outperform unsupervised prediction with Gemini 3.1 Pro. Controlled ablations show that broad and output-specific evidence provide complementary predictive benefits, while lightweight shared predictors achieve strong performance 

---

### [62] SHAPE of Thinking: Mathematical Heuristics for Analyzing and Improving LLM Reasoning

**链接**: https://arxiv.org/abs/2608.28600
**作者**: Jonghyun Song, Sangjun Song, Minjae Oh, Haesung Pyun, Sungsik Lee, Yohan Jo
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [63] DischargeBench: Pre-Deployment Evaluation of LLM Discharge Educators through Persona-Grounded Patient Simulation

**链接**: https://arxiv.org/abs/2609.20827
**作者**: Won Seok Jang, Youngbin Jang, Chanyoung Ko, Hyunwook Kim, Zonghai Yao, Hong Yu
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [64] Beyond Benchmark Accuracy: A Diagnostic Test for LLM Chemical Prediction

**链接**: https://arxiv.org/abs/2610.19906
**作者**: Yanyi Su, Yu Zeng, Hongshuai Wang, Chenyan Wang, Zhifeng Gao, Xiaohui Yang
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLMs have achieved strong performance on chemical prediction benchmarks. However, existing evaluation methods typically provide target entity identity information directly, making it difficult to determine whether model predictions arise from transferable structure-property reasoning capabilities or rely on target-related contextual information or memory retrieval. We propose the Identity-Blinded Reasoning Diagnostic framework to evaluate chemical prediction models when target entity identity information is hidden. In this framework, the target is no longer directly defined by its entity identity, but instead by a known source entity and an explicit structural edit operation. This setting preserves the information required to determine the target while reducing the opportunity for models to access target identity cues. We evaluate this framework across six tasks spanning odor prediction, molecular property prediction, retrosynthesis, and reaction yield prediction. The results show that

---

### [65] What You Sign Is Not What You Run: The Verifiability Gap in Quantized LLM Supply Chains

**链接**: https://arxiv.org/abs/2610.19498
**作者**: Wei-Liang Liu, Cheng-Yen Tsai
**来源**: cs.CR cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Model signing authenticates the full-precision weights W an LLM is released with, yet users run a quantized artifact Q whose producing transformation is not uniquely determined under current disclosure. We separate the non-environment inputs from the execution environment E and measure a quantity that, to our knowledge, has not been measured before: the Independent Verifiability Rate (IVR), the fraction of a popularity-sampled GGUF ecosystem that a third party can re-derive bit-for-bit. Across the 200 most-downloaded Hugging Face GGUF repositories (198 in scope), no artifact or model card records the build environment, so under a recorded-inputs protocol the IVR is 0/198. Yet the artifacts are not irreproducible. On four in-sample repositories that disclose their inputs, the card's information alone reproduces no Q4_K_M file, but two coordinates the card omits - the build's floating-point-contraction setting and, for hybrid models, the per-tensor quantization recipe - re-derive 7/8 tar

---

### [66] Same Claim, Different Interpretations: How LLM Agents Resolve Ambiguity in Scientific Claims

**链接**: https://arxiv.org/abs/2610.20457
**作者**: Delip Rao, Ahmed Muharram, Chris Callison-Burch
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Co-scientists and agentic scientific claim verifiers are increasingly used to assess claims across the sciences. Natural-language scientific claims, written for human experts, are often underspecified and so admit several defensible interpretations. Such verifiers usually pick one, often tacitly, and benchmarks score their verdicts against expert labels without recording the expert's interpretation or the verifier's in a comparable form. This leads to disagreements with expert labels that cannot be traced to the evidence or the interpretation, and to compute spent on unchecked interpretations. We introduce Claim Cards to make such interpretations explicit in the reasoning itself. A Claim Card records a verifier's interpretation as nine fields before evidence gathering, each marked stated, inferred, or default. To test whether an agent's interpretation can change its verdict, we ran a GPT-5.4 agent five times on each of 60 expert-labeled materials-science and biomedical claims with a ca

---

### [67] Truthful and Expected-Payment-Optimal Model Routing in Graph-Based Agentic Workflows

**链接**: https://arxiv.org/abs/2610.19316
**作者**: Jiayuan Liu, Mingyu Guo, Jiarui Gan, Vincent Conitzer
**来源**: cs.GT cs.CL cs.MA
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Assigning routine tasks to cheaper large language model (LLM) providers can reduce generation cost, but switching providers may require processing accumulated context again. Keeping dependent tasks with the same provider can instead reuse eligible context. Graph-based workflows therefore couple routing decisions across tasks. Independent providers may also privately know their real-time unit costs and strategically misreport them. We formulate this routing problem as a single-parameter procurement auction and propose STAR (Strategy-proof Topology-aware Agent Routing), which minimizes virtual-cost-weighted graph workloads. Its allocation rule and payments, computed by integrating workload over possible cost reports, make truthful reporting utility-maximizing regardless of other providers' reports and cover each truthful provider's execution cost. With independent cost distributions and non-decreasing virtual costs, STAR additionally minimizes the user's expected total payment to provide

---

### [68] Correlation-Aware Contextual Bandits with Surrogate Rewards for LLM Routing

**链接**: https://arxiv.org/abs/2607.09015
**作者**: Ajay Narayanan Sridhar, Ronak Singh, Mehrdad Mahdavi, Vijaykrishnan Narayanan
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [69] Manac\'a-1B-Instruct-2: Reproducible Safety Alignment for a Native Brazilian-Portuguese LLM. Negative DPO Results, a Controlled Composition Scan, and a Silent Failure Mode of the LLM Judge

**链接**: https://arxiv.org/abs/2610.20570
**作者**: Bruno Leonardo Santos Menezes, Carlos Leonardo Souza Cardoso, Fabio Andr\'e Machado Porto
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Brazilian Portuguese remains underserved by open-source language models, and the few that are safety-aligned rarely document what did not work or validate comparisons with statistical significance. We present Manac\'a-1B-Instruct-2, the second-generation post-training alignment of Manac\'a-1B (1.72B parameters, trained from scratch for PT-BR), with an SFT corpus of 291,223 examples. We document three DPO attempts, all negative, including a case where the training reward margin reaches 1.0 while free generation does not change at all, and show that safety came from a dedicated safety-SFT (LLM-jp AnswerCarefully style), refined over three iterations until closing the safety-helpfulness frontier. A controlled scan of the fraction of general data in the safety-SFT mix (10% to 60%) reveals a non-monotonic over-refusal curve with a knee point at 40-50%. The final model is compared against four external PT-BR models on the same items, with Wilson confidence intervals and paired McNemar tests 

---

### [70] Embedding Geometry Shapes LLM Routing: Tracing Failure Modes and Improving Generalization

**链接**: https://arxiv.org/abs/2610.19198
**作者**: Leonardo Torti, Emanuele Rimoldi, Tomer Galanti, Tomaso Poggio, Pierfrancesco Beneventano
**来源**: cs.AI cs.LG stat.ML
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> With the growing number of LLMs available, selecting which one to use for a prompt has become a key question. A large part of the routing literature relies on semantically embedding prompts into a vector space and then applying a lightweight classifier to the embedded representations. These methods perform robustly in-distribution but they struggle to generalize to unseen tasks. By studying the geometry of semantic embeddings, we trace a clear failure mode: features that determine the neighbors of unseen prompts are an unreliable proxy for LLM selection. We therefore replace the semantic embedding with the following map: we run a partial forward pass of Qwen2.5-7B-Instruct on the prompt and use the hidden state of its last token at a deep layer as the representation. When applying kNN and other simple classifiers to this new representation, we obtain a clear result in generalization: on average across cost penalties, their performance improves. Moreover, kNN and another simple classifi

---

### [71] CAST: History-Adaptive Spectral Clipping for LLM Pretraining

**链接**: https://arxiv.org/abs/2610.19761
**作者**: Jiacheng Li, Jianchao Tan, Kefeng Zhang, Yuchen Xie, Xunliang Cai
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Soft spectral clipping (SSC) reduces gradient singular values, but its effect depends on the gradient scale and clipping threshold. We introduce CAST (Clipping with Adaptive Scales and Thresholds), a history-adaptive extension of SSC. AdamW's previous second moment sets row and column scales. An exponential moving average of the clipped output's estimated spectral norm sets each matrix's threshold. CAST restores the original coordinates before the AdamW update. We train a mixture-of-experts (MoE) model with 19.08B total parameters for 83.89B tokens. CAST achieves lower training and mean validation losses than nine gradient-processing baselines, with the fewest relative gradient spikes. It reaches the best baseline's final smoothed training loss in 7.2\% fewer steps.

---

### [72] Towards Security-Auditable LLM Agents: A Unified Graph Representation

**链接**: https://arxiv.org/abs/2605.06812
**作者**: Chaofan Li, Lyuye Zhang, Jintao Zhai, Siyue Feng, Xichun Yang, Huahao Wang 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [73] LLM-Based Policy Compliance Verification of Loan Applications

**链接**: https://arxiv.org/abs/2610.20155
**作者**: Florentina Voboril
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Banks rely on extensive internal policy frameworks to ensure that corporate lending decisions comply with regulatory requirements and internal risk standards. Reviewing loan applications against these policies is a largely manual and knowledge-intensive process, which can lead to overlooked policy violations or exceptions. This report presents a prototype of an LLM-based policy checker that automatically verifies loan applications against internal lending policies. The proposed approach follows a two-step architecture. First, compliance-relevant rules are automatically extracted from policy documents and converted into structured, machine-readable representations. Second, loan applications are evaluated against the extracted rules to identify policy exceptions, non-compliant findings, missing information, and cases requiring manual review. Evaluation results demonstrate that the rule extraction process is highly stable across multiple runs and consistently captures rules identified as 

---

### [74] MemeTrace: A Multimodal LLM-Based Agent for Safety-Aware Meme Provenance Analysis

**链接**: https://arxiv.org/abs/2610.19267
**作者**: Bo Shao, Yihan Ma, Yiting Qu, Michael Backes, Yang Zhang
**来源**: cs.AI cs.CL cs.CY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Online memes are often carriers of unsafe content such as disinformation and propaganda. Their rapid evolution in response to news events and strong dependence on contextual information make it difficult for platforms and moderators to detect and moderate them effectively. Moreover, existing moderation studies typically classify memes as safe or unsafe based on individual images, lacking the ability to perform broader provenance analysis, i.e., where a meme originates, how it spreads, what cultural symbolism it represents, whether it poses potential risks to society, etc. To bridge this gap, we introduce MemeTrace, a multimodal LLM-based agent that automatically traces the provenance and potential risks of emerging memes. We evaluate MemeTrace on Meme100, a dataset of 100 real-world memes, using both human annotation and automatic metrics. The results demonstrate that MemeTrace substantially outperforms the VLM baseline. More importantly, MemeTrace achieves higher accuracy in detecting

---

### [75] A large-scale pipeline for LLM-assisted corpus annotation: variation and change in the English consider construction

**链接**: https://arxiv.org/abs/2510.12306
**作者**: Cameron Morin and Matti Marttinen Larsson
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [76] AgentWorld: A Data Factory for Training LLM Agents from Multi-Turn Interactions

**链接**: https://arxiv.org/abs/2606.09138
**作者**: Daoyu Wang, Mingyue Cheng, Qingchuan Li, Shuo Yu, Jie Ouyang, Qi Liu 等 (7 人)
**来源**: cs.LG cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [77] NOMOS: Compiling Written Policies into Statically Verified Tool-Call Gates for LLM Agents

**链接**: https://arxiv.org/abs/2610.11030
**作者**: Min-Young Yu, Tony Kim, Jang Won Choi
**来源**: cs.CR cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [78] Do LLM Tutors Actually Teach? A Process-Centered Synthesis of the Tutoring Loop

**链接**: https://arxiv.org/abs/2610.15692
**作者**: Sayantan Adak, Rima Hazra, Koyel Mukherjee, Digbalay Bose, Somnath Banerjee
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [79] Why Static Skill Inconsistencies Do Not Equate to Runtime Risks: A Behavioral Analysis of LLM Agent Execution

**链接**: https://arxiv.org/abs/2610.18927
**作者**: Fengrui Fan, Huahao Wang, Jingyi Fang, Yutao Hu, Yueming Wu, Deqing Zou
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agent frameworks heavily rely on external skill assets to standardize tool usage, encode operational workflows, and supply executable runtime resources. Despite their widespread adoption, multi-component skill packages frequently suffer from cross-artifact inconsistencies, where documentation, scripts, and configuration files specify conflicting behavioral constraints. Although static auditing techniques can uncover such contractual discrepancies, static defect volume cannot reliably reflect real-world agent performance degradation. This gap leaves practitioners without rigorous evidence to assess the practical risk of flawed agent skills. This paper presents a systematic empirical study to demystify the runtime implications of skill inconsistencies. We conduct large-scale auditing over 575 community and benchmark skills, yielding 1,182 manually validated contract inconsistencies. We further build a controlled evaluation pipeline with 49 executable agent tasks and three representat

---

### [80] MCAIR: Monitoring and Correcting Agent Unfaithfulness via Internal Representations

**链接**: https://arxiv.org/abs/2610.19679
**作者**: Yan Xu, Dandan Song, Luan Zhang, Jun Yang, Ke Duan, Yuhang Tian 等 (10 人)
**来源**: cs.AI cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Model (LLM)-based agents have demonstrated remarkable capabilities in completing complex tasks through multi-step reasoning and tool interactions. However, recent studies have revealed that LLM-based agents can exhibit unfaithful behaviors, where their final reports fail to faithfully reflect their actual execution trajectories. Specifically, when agents fail to accomplish tasks through the intended sources or procedures, they may resort to alternative sources or strategies while failing to disclose such deviations, leading users to incorrectly believe that the tasks have been completed according to the original requirements. We refer to this specific form of agent unfaithfulness as Agent Completion Unfaithfulness. Detecting and mitigating agent completion unfaithfulness is critical yet remains largely unexplored. In this work, we propose MCAIR, a runtime monitoring and correction framework that leverages internal representations of LLM-based agents. MCAIR uses multi-ste

---

### [81] Right Values, Wrong Places: Diagnosing and Fixing Record Misplacement in LLM-Generated JSON

**链接**: https://arxiv.org/abs/2608.25358
**作者**: Yiwei Zhang, Chengke Wu, Jiahao Li, Li Wang, Yao Yao, Jianqiang Li
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [82] One Task, Many Interfaces: Simple Cross-Interface Consistency Training Improves LLM Agent Robustness

**链接**: https://arxiv.org/abs/2610.20576
**作者**: Artin Tajdini, Manpreet Kaur, Peng Qi
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Post-training binds the competence of an LLM agent to the interface it was trained on. Semantics-preserving perturbations of that interface, such as renaming an action or changing the notation, leave the underlying task unchanged yet make the agent worse at it. Scoring each sample independently means interface randomization only broadens this dependence from a single interface to the training interface distribution, so out-of-distribution perturbations still degrade the agent. We propose Cross-Interface Policy Regularization (CIPR), a self-supervised objective that replaces action names with uninformative identifiers and presents each training sample under two interfaces in which equivalent actions are identified by construction. CIPR penalizes the KL divergence between the action distributions induced under the two interfaces, so the policy behaves consistently across them. We evaluate CIPR in both supervised and reinforcement-learning post-training, where it improves robustness. On a

---

### [83] $\tau$-Emotion-Bench: Exposing the Interaction Fragility of LLM Agents through Real-World User Emotions

**链接**: https://arxiv.org/abs/2610.19560
**作者**: Rishitosh Kumar Singh and Amir Saeidi and Shamanthak Hegde and Shrinidhi Kumbhar and Chitta Baral
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In long-horizon tool-calling tasks, LLM agents can fail not only because of tool-use errors, but also because of ineffective interaction with users. Yet existing benchmarks largely assume cooperative and behaviorally stable users, leaving the effect of emotional variation on agent reliability underexplored. We introduce $\tau$-Emotion-Bench, a ten-domain benchmark for evaluating tool-calling agents under controlled emotion-conditioned user interactions while preserving the underlying task objective. To scale both benchmark construction and agent training, we introduce Tracer, a scalable agentic data-generation pipeline that constructs grounded, policy-valid tasks and collects trajectories through an interactive agent--user--environment harness. By allowing dissatisfied users to terminate inefficient interactions, the harness provides an interaction-aware signal that filters trajectories with excessive user dependence and favors effective tool use. Experiments with two user simulators s

---

### [84] The Dice Roll Method: A Standardized Protocol for Repeated-Query Auditing of Large Language Model Brand Recommendations

**链接**: https://arxiv.org/abs/2609.04047
**作者**: Dmitrij \.Zatuchin
**来源**: cs.IR cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [85] Whom Do AI Agents Work For? Role Assignment Induces Sponsorship Bias in LLM Recommenders

**链接**: https://arxiv.org/abs/2609.17989
**作者**: Davood Wadi, Yu Ma
**来源**: econ.GN cs.AI q-fin.EC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [86] PerSo: Investigating Facets of LLMs' Social Intelligence in Real-World Persuasion Scenarios

**链接**: https://arxiv.org/abs/2610.20548
**作者**: Ali Zamani, Soroush Esfahanian, Erfan Shahabi, Mohammad Taher Pilehvar, Azadeh Shakery, Yadollah Yaghoobzadeh
**来源**: cs.CL cs.AI cs.SI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Understanding the social intelligence of large language models (LLMs) is increasingly important for applications involving human-AI interaction and multi-agent environments. Social intelligence comprises two aspects: cognitive intelligence, the ability to infer others' mental states, and behavioral intelligence, the ability to select appropriate social actions based on these inferences to achieve social goals. Persuasion provides a natural testbed in which both aspects are simultaneously at play, yet prior benchmarks typically evaluate them in isolation using synthetic scenarios. We introduce PerSo, a benchmark that evaluates both aspects on real-world persuasion dialogues from Reddit's ChangeMyView community, using an LLM-in-the-loop pipeline to construct the evaluation tasks, validated through human annotation. Our evaluation of diverse LLMs shows that performance generally scales with model size but varies across dimensions. The strongest LLM slightly surpasses the best observed hum

---

### [87] Scaling Discovery Requires Forgetting

**链接**: https://arxiv.org/abs/2610.20563
**作者**: Shangyin Tan, Ben Zhou, Lakshya A Agrawal, Jialin Zhang, Yilin Chen, Qiuyang Mang 等 (10 人)
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Automated research with LLM agents has shown promising results in various domains. Through iterative refinement and scored verifiers, LLM agents are capable of discovering new ideas. There are different ways to scale automated research: let one agent iterate for longer, run several agents in parallel, or further let the parallel agents communicate and build on one another's candidates. However, we find that all three strategies eventually plateau as the agents accumulate history. Each agent becomes anchored to its own past attempts, making fewer and smaller edits. Beyond this point, additional budget brings little further improvement. In this paper, we show that the key to scaling discovery further is to forget. Periodically discarding the search state, including every agent's session and the candidate history, and restarting from the best candidate found so far, unblocks the search and pushes the same budget further. We implement forgetting in a team of agents with communication and e

---

### [88] Beyond Initial Creation: Two Decades of Community-based Chart Revisions from Wikimedia Commons

**链接**: https://arxiv.org/abs/2610.19337
**作者**: Jasmine Y. Shih, Chase Stokes, Melanie Tory, Marti Hearst
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Open online communities like Wikipedia offer a rich space for understanding the organic evolution of public-facing artifacts, but little is known about how these communities collectively edit chart images. We investigate the phenomenon of "community editing" of visualizations by exploring chart revision patterns on Wikimedia Commons. We introduce a novel dataset of 7,786 longitudinal chart revisions across 1,664 images, labeled with edit categories using an LLM pipeline. Initial data analysis uncovered several novel findings. Multi-contributor revision is associated with more edits to mark styling and text content compared to single-contributor revision. Temporally, mark and text edits occur in more "bursty" cadences than data edits. In addition, while SVG charts attract more unique contributors and revisions than raster charts, their edit histories involve more tightly scoped and less diverse changes. This dataset enables a wide range of analyses of chart change over time.

---

### [89] Sparse Autoencoders Are a Shared Coordinate System for Symbolic Matching

**链接**: https://arxiv.org/abs/2610.19636
**作者**: Xiaocong Yang, Xuanyu Meng, Yuji Zhang, Jiawei Han, ChengXiang Zhai
**来源**: cs.LG cs.AI cs.CL cs.SC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) hold broad knowledge in one set of weights, but lack interpretability and trustworthy reasoning, especially in high-stakes use cases. A neuro-symbolic model, with its interpretable architecture and System 2 reasoning capacity, is a promising alternative if built at the scale of LLMs; however, its symbolic backbone is usually constructed with human effort, so existing neuro-symbolic models are bottlenecked by the scope of the symbol component and usually domain-specific. A data-driven method could instead build a larger symbolic system by aligning and merging existing ones. We target its first, foundational step: matching units across these heterogeneous systems. Our method, SAE-IDF, encodes a symbol in its native context into a sparse code with a sparse autoencoder (SAE), re-weights each dimension by its rarity and matches across systems. On 12 tasks across 6 kinds of symbolic system, SAE-IDF outperforms the same LLM's dense baseline on all tasks with Gemma

---

### [90] PFedMA: Who Should Join Next as Federated Multi-Agent Orchestration Evolves?

**链接**: https://arxiv.org/abs/2610.19458
**作者**: Shuai Li, Shengyuan Liu, Fan Qi, Xiaoshan Yang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Federated Multi-Agent Systems (FedMAS) offer a promising paradigm for collaborative reasoning among LLM-based agents while keeping raw client data decentralized. However, reliable multi-round collaboration remains challenging. Agent selection must take into consideration evolving task requirements and the agent's historical reliability, while privacy rules must adapt to changing collaboration contexts and meet the client's personalized needs. To address these challenges, we propose PFedMA, a federated multi-agent framework for feedback driven multi-round collaboration under heterogeneous privacy requirements. Across rounds, PFedMA maintains historical capability and reliability states to guide agent selection, evaluates task responses before aggregation, and refines subsequent queries according to accumulated collaboration feedback. PFedMA enables bidirectional local to global and global to local private rule evolution across heterogeneous clients. Clients generalize locally updated pr

---

### [91] ActMOF: Mapping Reticular Synthesis through Active Learning

**链接**: https://arxiv.org/abs/2610.19404
**作者**: Hongrui Sheng, Shutian Liang, Reid A. Coyle, Shyam Chand Pal, Peter Walther, Bin Feng 等 (8 人)
**来源**: cond-mat.mtrl-sci cs.LG physics.chem-ph
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reticular chemistry allows metal-organic frameworks (MOFs) to be designed from their building units, yet their synthesis remains constrained by sparse experimental data, noisy crystallization outcomes, and the absence of benchmarks for comparing active-learning strategies. While data-driven approaches such as Bayesian optimization (BO) can improve synthesis success rates, selecting appropriate optimizers beforehand for mapping MOF crystallization landscapes remains largely empirical. Here we present ActMOF, an experiment-grounded benchmark for comparing search strategies in aluminum-carboxylate MOF synthesis. ActMOF is emulated from experimentally measured microwave syntheses with each encoded condition assigned a crystallinity index calculated based on diffraction peak intensity and full width at half-maximum. By benchmarking policies guided by Gaussian processes (GP), tree ensembles and large language models (LLM), ActMOF placed the GP family among the leading policies for active lea

---

### [92] JointServe: Serving Multi-Model Agents on Memory-Constrained GPUs

**链接**: https://arxiv.org/abs/2610.19822
**作者**: Daijin Hu
**来源**: cs.DC cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents are evolving from a single model calling tools to planners that orchestrate multiple expert models whose capabilities live in distinct weights. This shift breaks a hidden assumption of today's serving systems: that the working set of models fits in GPU memory. On the memory-constrained GPUs typical of private and edge deployments, naive whole-model swapping serializes weight transfer with computation and, without host-backed KV restoration, discards session state at a switch. We present JointServe, a serving system that treats weight shards and KV blocks as residency objects competing for one unified memory budget. JointServe exploits three structural properties of agent workloads (directed calls, gapped execution, and dual-state residency) to prepare models before they are called: an intent signal parsed from the caller's own output stream triggers prefetch during generation, partial k* residency reduces switching to incremental layers, and a preemptive transfer scheduler p

---

### [93] Exact Scaling Laws for a Random-Features Bigram Model

**链接**: https://arxiv.org/abs/2610.19281
**作者**: Julian Enoch and Elvis Dohmatob
**来源**: cs.LG
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Understanding neural scaling laws is increasingly important for theory and practice, yet first-principles explanations remain limited even in simple settings. In this work, we study capacity-limited scaling in a bottlenecked bigram model with power-law (Zipf) token statistics, viewed as an analytically tractable toy model of a large language model. Fixed random embeddings serve as a proxy for representational capacity and induce an explicit bottleneck of width, allowing us to derive scaling laws for prediction regret as a function of model width, vocabulary size, and the Zipf exponent. Our results complement recent theoretical accounts based on optimization dynamics by isolating scaling due purely to representational constraints. In the appropriate regime, the theory recovers the functional form of classical neural scaling laws and suggests that heavy-tailed language statistics may underlie both optimization- and capacity-driven scaling. Experiments natural language datasets (WikiText2

---

### [94] Qwen-MT-Lumen at WMT2026: Instruction-Specialized Translation via Quality-Aware Training and On-Policy Distillation

**链接**: https://arxiv.org/abs/2610.19758
**作者**: Hao Wang, Yangyang Liu, Xiaohu Zhao, Heng Liu, Zifu Shang, Tianhao Li 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We present Lumen, The open-source model is available at, our submission to the WMT 2026 General Machine Translation Shared Task. We focus on instruction-specialized translation, where systems must produce accurate translations while satisfying fine-grained requirements on style, terminology, and structured output. Lumen follows a four-stage pipeline. First, continued pre-training and supervised fine-tuning jointly strengthen multilingual translation competence and the ability to follow translation-specific instructions, such as terminology, style, and format constraints. Second, we extend the originally offline M^{2}PO preference-optimization framework into an online preference-optimization stage: the current policy samples candidate translations, an LLM judge assigns continuous direct-assessment scores, and the resulting multi-pair preferences are used to update the model. Third, on-policy distillation transfers stronger translation-instruction-following behavior from a larger teacher

---

### [95] J-tau: A Fully Localized Japanese Benchmark for Tool-Agent-User Interaction

**链接**: https://arxiv.org/abs/2610.19638
**作者**: Chihiro Yano, Jun Hirako, Hiroaki Yamagiwa, Ryota Hirobuchi
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We present J-tau, the first publicly available Japanese benchmark for evaluating tool-using LLM agents in interactive customer-support scenarios. While tau-bench is widely used to evaluate LLM agents, it is English-centric and cannot evaluate agents in other languages. Existing multilingual extensions offer no public Japanese version and rely primarily on machine translation, leaving locale-specific entities such as addresses and currencies inconsistent with the target region. To enable reliable evaluation in Japanese, we carefully localize tau-bench through machine translation, entity adaptation, and human review. During this process, we also uncover and fix two flaws in the original tau-bench: invalid tasks and a score aggregation error that inflates certain models' results. Experiments show that J-tau yields fewer evaluation errors than a naively machine-translated counterpart and that our fixes resolve both flaws.

---

### [96] Fantastic Metrics and How to Find Them: Meta-Evaluating Metrics for Multi-lingual Style-Personalized Generation

**链接**: https://arxiv.org/abs/2610.19166
**作者**: Anubhav Jangra, Adrian de Wynter
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Meta-evaluation of text generation metrics and LLM-judges is primarily conducted using metric-human correlations. However, prior work has shown that correlation is not an appropriate estimate of a metric's evaluation capability and can be unstable across evaluation settings, such as different datasets or languages. Therefore, we propose a regression-based meta-evaluation of metrics that learns on calibrated metric outputs to predict human ratings. We ground this measurement relative to a trivial constant-mean baseline and human agreements to provide a comparable measure of metric capability across evaluation settings. To test our meta-evaluation framework, we developed a large-scale multi-lingual style-personalized text generation (SPTG) benchmark, collecting multiple annotations across 10 topologically diverse languages and four evaluation dimensions, each with varying degrees of subjectivity. We meta-evaluated 32 metrics from three style evaluation paradigms (string-based, embedding-

---

### [97] Frustratingly Easy Majority Voting Using Length Conditioning

**链接**: https://arxiv.org/abs/2610.19890
**作者**: Fiorenzo Parascandolo, Enver Sangineto, Xiaoyi Yu, Wenhui Tan, Jipei He, Ruihua Song 等 (7 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Majority Voting (MV) is a simple and widely used strategy which improves the reasoning accuracy of Large Language Models (LLMs) by allocating additional inference-time computation. Specifically, in MV multiple Chain-of-Thoughts (CoTs) are independently sampled and the most frequent final answer is selected. In this work, we propose Length-Conditioned Majority Voting (LCMV), a Test-Time Training approach which improves MV leveraging an empirical observation that has recently been established in several studies: longer CoTs tend to be associated with a lower probability of correctness. We formulate this inductive bias as a length-conditioned prior probability, which is modeled by a simple logistic function. Moreover, we adapt this prior at test time using only unlabeled testing data and without fine-tuning the LLM. Finally, the adapted prior is used to weight the vote of each sampled answer. Extensive experiments across multiple LLMs and reasoning benchmarks show that LCMV consistently i

---

### [98] Revisiting Generative vs. Dense Retrieval: A Static Value Prior Reverses the Gap

**链接**: https://arxiv.org/abs/2610.19065
**作者**: Renbo Tu, Yang Liu and Shuying Sun
**来源**: cs.IR cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Generative retrieval (GR) has emerged as a strong candidate generator for sequential recommendation as language models and semantic-item identifiers have improved. However, GR is not a uniformly stronger replacement of dense retrieval (DR) in online retail candidate generation. We examine their differences on two Amazon Toys datasets under different metrics. GR leads on best relevant item value among users both methods cover, while DR leads on exact-target recall and relevant value across the ranked list. With deep analysis, we find that popularity contributes the most to GR's measured value lead. Adding the same static item value to DR in one reranking step reverses this lead and keeps recall above GR. Finally, on an industrial-scale internal e-commerce dataset with LLM-judged relevance, we show that a 14B SID-LLM still underperforms a $47\times$ smaller dense encoder.

---

### [99] Whose turn is it? Context-guided model routing for stateful agents

**链接**: https://arxiv.org/abs/2610.19292
**作者**: Anikesh Parashar, Avik Dutta, Vashu Chauhan, Sumit Gulwani, Priyanshu Gupta, Hosein Hasanbeig 等 (9 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Model routing can reduce the cost of LLM applications by assigning simpler requests to cheaper models without sacrificing the quality of the response. However, most routers treat requests as independent. Stateful agents do not operate under this assumption: a user turn may require multiple model and tool calls, its difficulty depends on the state produced by earlier turns, and changing models can sacrifice reuse of the conversational prompt cache. We study zero-shot, cost-aware routing at the user-turn boundary, systematically varying the routing rule, access to session history, candidate models that differ in size, reasoning effort, or model provider, and prompt-cache behavior. We evaluate on multi-turn versions of SheetCopilot and SpreadsheetBench 2, where persistent workbooks and cross-turn dependencies make isolated routing decisions especially brittle. At a matched offloading rate, giving the router session history improves task pass rate over the same router without history, with

---

### [100] Weighted Ensemble Sampling for Rare-Event Estimation in Language Models

**链接**: https://arxiv.org/abs/2610.19202
**作者**: Zixuan Liu, Gustavo Didier, Fangzheng Wu, Brian Summa, Zizhan Zheng
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Rare but severe failures of large language models can become practically significant at deployment scale. Estimating their probabilities with direct Monte Carlo sampling is highly inefficient, while proposal-based methods typically require auxiliary learning of an additional proposal distribution. We introduce \textbf{Weighted Ensemble (WE)}, a training-free framework for rare-event estimation in language models. WE samples exclusively from the original language model and improves upon direct Monte Carlo by periodically reallocating the sampling budget toward prefixes that appear more likely to reach the target rare event. To guide this reallocation without learning a separate proposal distribution, we exploit internal LLM representations as prefix-level signals and empirically validate their effectiveness. We provide a theoretical analysis of the proposed algorithm. Experiments on safety-related tasks spanning both small-scale and modern large-scale LLMs demonstrate that WE improves t

---

### [101] DeLoop: Repeated Actions as Self-Supervision for Long-Horizon Agents

**链接**: https://arxiv.org/abs/2610.19376
**作者**: Tianle Chen, Pushkar Singh, Ketan Todi, Biswajit Paria, Qijia He, Wenqi Wang 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Language-model agents that run long tasks often redo work they have already done: they re-issue a tool call they made earlier and get back exactly the same observation, a step that adds no new information. We identify this failure as a loop. Loops appear natively in Qwen, Llama, and Gemini agents and become far more common once the agent's history is compressed to fit its context window. To reduce these loops, we propose DeLoop, a self-supervised training method. DeLoop builds on a simple observation: the agent's own rollout can provide the supervision needed to learn from its loops. We use a looping action as a negative example and the first later non-looping action in the same rollout as a positive example. DeLoop learns from these pairs through direct preference optimization and does not require task rewards, gold answers, or LLM judges. On CodeGym under compression, DeLoop reduces the share of Qwen3-8B tasks containing loops from 57.3% to 6.1%. It also uses about one third as many 

---

### [102] Analyzing performance of Retrieval Augmented Generation models for Question Answering Tasks

**链接**: https://arxiv.org/abs/2610.20419
**作者**: Fazle Mohammed Tasfiq, Sabab Attin, Sheikh Md. Tahmid Hossain, Raiat Reza, Tanzim Ahmmed, Nafis Chowdhury 等 (8 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Retrieval-Augmented Generation (RAG) models have become almost a cornerstone of open-domain question answering tasks; in which the quality of answers generated in the process, greatly relies on the effectiveness of retrieval mechanisms. In the realm of LLM, the last two years have seen tremendous progress in RAG architectures, with many models reporting to have improved performance through various design innovations. The cultural question and answering systems of South Asia, in particular, present a specific challenge since the region is home to the vast number of languages and traditions, which are closely interrelated. Along with these deeply intertwined historical narratives increase the need for culturally grounded and context-aware interpretation. Despite major architectural advances in LLMs, claiming significant improvements, challenges remain when answering these region specific questions in native languages. In this study, we aim to extract high-performing factors to guide the 

---

### [103] CLASHarness: Benchmarking Multi-Agent Conflict in Computer Use via a Controllable and Verifiable Generation Pipeline

**链接**: https://arxiv.org/abs/2610.19128
**作者**: Yuxiang Lai, Jike Zhong, Chengzhi Liu, Ming Li, Haonan Wang, Xiaofeng Yang 等 (9 人)
**来源**: cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Vision-language models (VLMs) are increasingly deployed in multi-agent systems to automate complex computer-use workflows, yet existing benchmarks mostly assume consistent, cooperative environments. In contrast, real-world collaboration rarely runs on consistent information: peer or sub-agents frequently report outdated states, issue contradictory instructions, or compete over shared permissions and files, forcing agents to check others' outputs and verify ground truth in the environment. Evaluating such conflict resolution remains challenging: manual authoring cannot scale across complex systems, while unconstrained LLM generation produces narrative drift, answer leakage, and unsatisfiable rubrics. We introduce CLASHarness (Conflict-Loaded Agent Scenario Harness), a controllable framework for generating verifiable multi-agent conflicts in computer use, with a benchmark of 600 multi-round tasks. By combining hierarchical scenario planning with an eight-step verified micro-pipeline, CLA

---

### [104] Can LLMs Access their World Knowledge for Event Prediction?

**链接**: https://arxiv.org/abs/2610.19021
**作者**: Zijun Wu, Zhitian Zhang, Hossein Hajimirsadeghi, Nikita Dvornik, Alexander Pashevich
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent work has questioned whether large language models (LLMs) can be useful for temporal event prediction. Despite vast pretrained world knowledge, LLMs often underperform simpler specialized models. We ask whether this knowledge is truly inaccessible, or whether current methods fail to present event prediction in a form LLMs can use. We argue for the latter and show that LLMs become effective event forecasters when the interface is designed around two choices. The first grounds each event in a natural-language description, and the second separates event semantics from the prediction space to prevent semantic bias from label associations. To test this, we introduce DescribeEvent, a benchmark of ~150K events across seven datasets and six domains with event-level descriptions. We find that capable LLMs substantially benefit from descriptions and symbolic labels, outperforming description-free variants and non-LLM baselines, while weaker models gain little. These results suggest that ac

---

### [105] ListQA: A Benchmark for Evaluating List-Formatted Factual Knowledge Retrieval in Large Language Models

**链接**: https://arxiv.org/abs/2610.19165
**作者**: Mayank Kulkarni, Rakesh Vaideeswaran
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Many real-world questions demand not a single fact but an organized collection of them, yet existing factual knowledge benchmarks almost exclusively target single answer retrieval. We introduce ListQA, a benchmark of 9,045 human-curated, cross-validated questions (audited error rate of 1.7%) that require LLMs to recall multiple facts and compose them into structured lists of 3-10 elements. Questions range from flat lists ("Which NCAA teams went undefeated between 2000 and 2024?") to hierarchical lists with sub-attributes ("...and what was their record and result?"), spanning eight categories across 60+ countries. An evergreen design (explicit temporal constraints or historically immutable facts) keeps ground truth valid without periodic updates. For evaluation, we frame element matching as a linear sum assignment problem: optimal bipartite matching paired with LLM-based semantic grading jointly captures factual accuracy, hallucination, and format compliance. We benchmark 34 models (8 f

---

### [106] Inverse Reasoning Models for Efficient Post-Training and Verification from Answer-Only Data

**链接**: https://arxiv.org/abs/2610.18878
**作者**: Eric O. Korman
**来源**: cs.LG cs.AI stat.ML
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Post-training reasoning LLMs often requires making a tradeoff between costly supervision and compute inefficiency: supervised finetuning typically requires reasoning traces, which is data inefficient since in many applications one only has prompt-answer tuples and lacks the groundtruth chain-of-thought (CoT) sequence. On the other hand, reinforcement learning (with verifiable rewards, for example) can operate without CoT data but it is much more compute-inefficient since it requires multiple autoregressive completions per optimization step, none of which are guaranteed to give a non-zero policy gradient. In this work we explore a middleground, a self-distillation technique that uses answer-only data, treating CoT as latent variables. This relies on training a partner ``inverse reasoning LLM" that generates the original's reasoning traces conditioned on the answer. The inverse model is trained once and reused across incoming batches of answer-only data, with all generation happening off

---

### [107] Interlock: From Local Correctness to Task Completion in Long-Horizon Agents

**链接**: https://arxiv.org/abs/2610.19686
**作者**: Linji Hao, Yanji He, Zihan Wang, Hansi Yang, Jiayuan Zhang, Hongyan Hao 等 (9 人)
**来源**: cs.CL cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model agents increasingly undertake long-horizon tasks in complex environments characterized by fragmented evidence, partially completed states, and dependencies across resources and artifacts. Existing agents may satisfy individual requirements while failing to maintain these relationships, producing locally correct but incomplete outcomes. These failures arise because task completion depends on relationships among environmental evidence, consequential decisions, and required effects. To address this completion gap, we propose Interlock, a framework for task synthesis that represents each task as a typed completion graph. Grounding edges connect public evidence to decisions, coupling hyperedges impose joint constraints across components, and realization edges connect decisions to all required downstream effects. Interlock compiles this graph into a resettable workspace, a public request, and an evaluation rubric. A source-coverage review checks whether the original requ

---

### [108] FOLD: Position-Free Far Memory with Local Order for Long-Context Speculative Decoding

**链接**: https://arxiv.org/abs/2610.20392
**作者**: Shuxuan Li, Jialiang Kang, Yanghao Zhou, Ziye Zhu, Xiao Yang
**来源**: cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Speculative decoding accelerates LLM generation through lightweight drafting and parallel verification. It is particularly promising for long inputs, where KV-cache access costs can be amortized over multiple accepted tokens. Yet most drafters are trained on short sequences and degrade on long inputs, while long-context training is costly. Existing training-free approaches restrict the context window, rescale positions, or augment recent context with retrieved distant entries. Drafters, however, read target hidden states that already encode contextual and positional information, and their lightweight architecture makes full-history attention affordable. We propose FOLD, a training-free method that preserves exact local positions and treats all distant entries as far memory at a shared position. To counter attention dilution as the memory grows, we sharpen attention within it to emphasize relevant entries while separately controlling its total weight relative to the local window. Across

---

### [109] REPORT-OPS: Hybrid Evidence-Guided Reporting with Human-Supervised Refinement for HPC

**链接**: https://arxiv.org/abs/2610.19222
**作者**: Mah Kadidia Konate, Mayur Akewar, Janki Bhimani, Steven Farrell
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Operational reporting for high-performance computing (HPC) facilities requires combining information from monitoring services, schedulers, incident and maintenance records, storage measurements, periodic reports, and operator investigations. Producing a reliable report requires more than retrieving relevant records: the evidence must refer to the correct system, metric definition, time period, and source of authority. We present REPORT-OPS, a hybrid reporting agent in which an LLM interprets requests, plans evidence collection, evaluates possible explanations, and drafts reports, while author-seeded operational policies and automated checks determine whether the available evidence supports the requested conclusion. Depending on the evidence state, the system answers the request, reports a qualified conclusion, or withholds an unsupported claim. During offline refinement, an LLM critic proposes bounded policy changes that a human approves or rejects without editing; accepted candidates 

---

### [110] Narrowing the Collaboration Gap, Probably

**链接**: https://arxiv.org/abs/2610.19215
**作者**: Mirah Shi, Marcel Hussing, Ira Globus-Harris, Natalie Collina, Aaron Roth, Surbhi Goel
**来源**: cs.LG cs.AI cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models are increasingly deployed as teams of agents that hold different private information about a shared task. How should such agents concisely communicate in a way that promotes aggregation of decision-relevant information? Communicating only proposed actions can discard decision-relevant uncertainty: two agents may prefer the same action for different reasons. We study an alternative interface in which agents communicate calibrated beliefs over actions. We first analyze a simple synthetic setting that captures the structure of multi-round reasoning under partial information. In this setting, we show theoretically and empirically that communicating unbiased probabilities can be strictly more powerful than communicating actions. We then test the same principle in a collaborative maze-solving task with trained transformers and pretrained LLM agents. Our results demonstrate that probability communication outperforms action communication when the exchanged predictions pre

---

### [111] Equal CER, Unequal Damage: Severity-Weighted Character Error Rate for OCR

**链接**: https://arxiv.org/abs/2610.20461
**作者**: Nguyen Nguyen, Yongyi Zang
**来源**: cs.CL cs.AI cs.CV
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Character Error Rate (CER), the standard metric for OCR and vision-language models (VLMs), charges a typo as much as a wrong name. We introduce semCER, which keeps CER's alignment and denominator and charges each grapheme edit a severity from an LLM judge, with no word segmentation. Normalized CER keeps the score of a whole transcription, where it tracks readers as well as semCER or better, and semCER breaks that score down into named edits. The charges track readers' ratings edit by edit in English, Vietnamese, and Chinese and put the edits readers rate most severe near the top of a sorted list. On pairs drawn where CER and semCER disagreed, readers side with semCER more often than with normalized CER in English and Chinese, and equally often in Vietnamese. Across 16 languages, the judge charges a wrong diacritic or tone mark almost nothing in Spanish but nearly a wrong letter's severity in Telugu. Where we can count real words, a general VLM's wrong letter forms one far above chance 

---

### [112] When Does Momentum Help in Reinforcement Learning with Verifiable Rewards?

**链接**: https://arxiv.org/abs/2610.20413
**作者**: Kaifei Wang, Zikang Shan, Liwei Wang, Yinyu Ye, Han Zhong
**来源**: cs.LG cs.AI math.OC stat.ML
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Momentum is a classical tool for accelerating convex optimization and a standard component of modern large language model training. Yet recent empirical work has questioned the usefulness of first-moment momentum in reinforcement learning with verifiable rewards (RLVR). We study this question through a bandit formulation of RLVR with bias-corrected exponential moving average (EMA) momentum, where the EMA coefficient $\beta$ controls how quickly the weights on past gradients decay. When policy gradients are evaluated exactly, we prove that increasing $\beta$ within a range that prevents overshoot strictly accelerates optimization. When gradients are estimated from sampled responses, a positive expected gain can be obscured by sampling fluctuations. We show that as the learning rate $\eta$ decreases, the expected gain with fixed $\beta$ vanishes faster than these fluctuations, whereas increasing $\beta$ to keep $\eta/(1-\beta)$ within the safe regime preserves a nonvanishing gain that ev

---

### [113] From Failures to Learnable Worlds: Policy-Conditioned Environment Generation for Navigation Agents

**链接**: https://arxiv.org/abs/2610.19420
**作者**: Yue Zhang, Han Lin, Zun Wang, Yidong Huang, Zaid Khan, Mohit Bansal
**来源**: cs.RO cs.AI cs.CV
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Simulated environments enable scalable training data generation for embodied agents, but more data does not necessarily provide what a particular agent needs to learn. Existing environment-generation pipelines largely optimize generic properties such as realism, diversity, or task coverage, while different pretrained policies can fail for different environmental reasons. We therefore introduce WEDGE, a framework for weakness-guided navigation learning in which the failure modes of a pretrained agent guide the generation of training environments at each adaptation round. Given a pretrained policy, WEDGE uses an LLM to propose executable weakness features from contrasting successful and failed rollouts, automatically validates them on the diagnostic set, and selects the strongest validated weakness based on its success-rate gap. The validated weaknesses are then mapped to the environmental factors that control them. WEDGE varies these factors to construct environments in the difficulty r

---

### [114] Plan or Retrieve First? A Scale Study of Tool Discovery Architectures

**链接**: https://arxiv.org/abs/2610.19068
**作者**: Mingfei Zhang, Amit Surana, Ziauddin Majid, Chenxi Wang, Michael Xu
**来源**: cs.AI cs.IR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tool-augmented LLM agents discover relevant APIs from large registries before planning execution, yet finite context windows prohibit injecting all tool definitions into a single prompt. The dominant approach, which we term Retrieve-then-Plan (RtP), embeds the user query and retrieves similar tools via approximate nearest-neighbor search. We study an alternative Plan-then-Retrieve (PtR) paradigm in which the LLM first generates Abstract Tool Stubs (hypothesized function signatures describing needed capabilities) which then serve as retrieval queries against the registry. Evaluating on ToolBench (46,984 unique API endpoints, 50 categories) across single-tool (G1), intra-category multi-tool (G2), and cross-category multi-tool (G3) query subsets, we find a clear complexity-dependent crossover: RtP outperforms PtR on single-tool queries while PtR outperforms RtP on multi-tool queries. This crossover holds at every retrieval budget (k=1 to 20), is robust across registry sizes from 1k to 47k

---

### [115] What Makes a Social Agent's Interactions Effective? Learning from Verifiable Outcomes in Paired Worlds

**链接**: https://arxiv.org/abs/2610.20195
**作者**: Caixin Kang, Ke Wang, Yuchuan Wu, Xiaoqiang Wang, Ling Li, Bingxue Qiu 等 (8 人)
**来源**: cs.CL cs.AI cs.SI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Effective social interaction requires more than fluent responses: agents must reach plans that fit the participants' needs and circumstances. Existing evaluations of social agents mainly rely on LLM judges that rate the conversation, without checking the resulting plan. We introduce HICO-Bench, a benchmark of 180 everyday coordination scenarios, such as resource allocation, scheduling, and authorization, in which two agents with private information converse and then independently record the plan they agreed on. A program checks Feasibility (the two records match and satisfy both participants' private conditions), and an LLM judge checks Integrity (the conversation supports the recorded plan); passing both is a Verified Success. Each scenario has two versions that share the same public context but differ in one private condition, so the correct plan differs between them. Across thirteen LLMs, 36% of conversations rated highly for goal completion fail Verified Success. To learn from outc

---

### [116] Cortex: Consolidating Context into Parametric Memory

**链接**: https://arxiv.org/abs/2610.20399
**作者**: Jintian Zhang, Feng He, Xinnian Liang, Ziwen Xu, Haoming Xu, Haojing Huang 等 (8 人)
**来源**: cs.CL cs.AI cs.CV cs.LG cs.MA
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Context can improve large language model performance, but these gains may be lost after context removal. Inspired by biological systems consolidation, we formulate Memory Consolidation (MC) as internalizing these gains while preserving non-target capabilities, connecting context-specified editing, skill learning, and behavioral steering under a common objective. We introduce a five-task-family testbed measuring consolidation and retention under single, batch, and sequential updates. We propose Cortex, which generates prospective queries to anticipate uses of context and distills context-conditioned outputs into mergeable low-rank or structural feed-forward network updates. Across 4B--120B dense and mixture-of-experts backbones, including both text-only and multimodal models, Cortex lies on the empirical consolidation--retention Pareto frontier in most evaluated settings. After 50 sequential factual edits on a 14B model, Cortex-Structural recovers 88.9% of the context-induced gain while

---

### [117] Model What Matters: Decision-Guided Selective World Modeling for Language Agents

**链接**: https://arxiv.org/abs/2610.19642
**作者**: Maolin Ran, Minda Chen, Di Huang, Wei Xiong, Fei Huang, Weiwen Liu
**来源**: cs.AI cs.CL cs.LG
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reinforcement learning provides a direct mechanism for optimizing task objectives in large language model-driven agents, but task rewards are typically sparse trajectory-level signals that only evaluate task success, without directly supervising action-conditioned environment transitions, leaving the model with limited explicit understanding of action consequences and environment dynamics. Recent work introduces auxiliary supervision through policy and world modeling co-training, yet typically treats complete environmental observations uniformly as world modeling targets, overlooking the varying decision relevance of observation content. We propose DGS-WM (Decision-Guided Selective World Modeling), a decision-guided policy-world modeling co-training approach for language agents. DGS-WM employs a Decision-Guided Observation Selection component that filters observation units with decision value as world modeling targets based on their support for subsequent policy responses, and a Confid

---

### [118] When Non-Adversarial Noise Hurts Learning: Benchmarking Skill Self-Evolution in Agents

**链接**: https://arxiv.org/abs/2610.19910
**作者**: Tao Yu, Zhongtian Luo, Yuchen Long, Yiheng Lu, Yuxuan Zhou, Yanpei Gong 等 (10 人)
**来源**: cs.LG
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model agents increasingly improve by distilling experience into reusable skills, but errors in that experience can persist in learned rules and affect later tasks. Existing evaluations largely examine clean learning or perturbations encountered after skills are frozen, leaving robustness during self-evolution insufficiently understood. We introduce RSE-Bench, to our knowledge the first benchmark for evaluating skill self-evolution under ordinary, non-adversarial noise. It spans four domains and six benchmarks, with controlled perturbations to instructions, environmental evidence, execution records, and outcome--record pairings that preserve the underlying tasks and native scoring rules. The protocol separates noise during learning from input-side noise at evaluation, testing frozen skill stores on held-out tasks. We also introduce \textsc{RSEClaw}, a method-agnostic framework supporting consistent noise injection and process diagnostics of actual exposure and skill updat

---

### [119] Let Me Clarify: Interactive Modeling of Soft Attributes

**链接**: https://arxiv.org/abs/2610.20227
**作者**: Steffen Holter and Rita Sevastjanova and Michaela Benk and Mennatallah El-Assady
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> People commonly express preferences through soft attributes such as is interesting,'' which are difficult to operationalize for computational preference modeling. Latent representations can obscure how such attributes are interpreted, limiting transparency and user control. We formalize softness as the diversity of valid interpretations a description permits and provide empirical support for this characterization. Our proposed measure estimates softness to guide clarification and determine when to generate computational approximations. This is instantiated in AttriFy, a mixed-initiative system that translates descriptions into executable Python functions over text corpora. An interactive dashboard connects the dialogue to proposed functions and computed values, enabling users to inspect, accept, reject, and refine interpretations. An exploratory within-subjects study with 32 participants compares our softness-guided clarification approach with an LLM baseline in supporting interpretabl

---

### [120] CommerceGen-Studio: An End-to-End Framework for Commercial-Grade Main-Image Generation

**链接**: https://arxiv.org/abs/2610.20603
**作者**: Xiaoli Xu, Zhengtao Wu, Zhengze Xu, Tao Liu, Yongchao Du, Zuan Gao 等 (10 人)
**来源**: cs.CV
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We present CommerceGen-Studio, an end-to-end framework for generating commercial-grade main images for e-commerce Stock Keeping Units (SKUs). Our framework is organized along a three-stage pipeline of information extraction, semantic rewriting, and multi-condition generation: Prompt-Eval-Refine-Loop Agent (PERL-Agent) distills heterogeneous SKU metadata into concise selling-point text lists through an iterative closed loop of VLM and LLM roles scored by a reference-free rubric. Layout Thinker Optimization (LTO) aligns the rewriter with both caption and rendered-image quality via alternating domain-specific policy optimization. SKU-DiT, trained under Reinforce-Distill-Reinforce (RDR) progressive training, conditions jointly on the white-background product image, the trademark crop, and the structured layout to hold subject fidelity, trademark integrity, and character-level text accuracy together. The framework runs in production at a scale of millions of main images per day with a laten

---

### [121] Explorer-Zero: Improving Self-Play for Long-Horizon Tasks with Decomposable Verifiable Rewards

**链接**: https://arxiv.org/abs/2610.19868
**作者**: Tianyu Liu, Davide Belli, Bence Major, Arash Behboodi, Tribhuvanesh Orekondy
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Training LLM agents on long-horizon interactive tasks with reinforcement learning typically relies on human-annotated tasks and reliable verification, both expensive to construct for stateful environments. Self-play offers an alternative, but must generate achievable, compositional tasks and provide feedback beyond binary outcomes. We propose Explorer-Zero, a self-play framework that jointly generates tasks and fine-grained, verifiable rewards through environment interaction. A learned proposer explores the environment, constructs tasks, and records intermediate and final states as verification targets. These checkpoints reward partial completion, while alternating proposer--solver training adapts the generated curriculum. We show theoretically that subtask rewards reduce collapse among unsuccessful rollouts when they complete different numbers of subtasks. Without human-annotated training tasks, Explorer-Zero outperforms the evaluated self-play baselines across ALFWorld, ScienceWorld,

---

### [122] Progress-Aware Distillation for Mitigating Stagnation in Small Language Model Agents

**链接**: https://arxiv.org/abs/2610.19439
**作者**: Yuanpu Cao, Saket Sathe, Hanyu Wang, Ziyi Yin, Fenglong Ma, Jinghui Chen
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> While LLM-based agent systems have demonstrated remarkable proficiency in reasoning and solving complex real-world tasks, they also come with substantial token consumption and inference latency, limiting their practical deployment. To enhance the efficiency of agent systems, recent efforts have focused on transferring agentic capabilities from large-scale models to small language models (SLMs) via supervised fine-tuning-based distillation. Nevertheless, as interaction trajectories grow longer, involving extended reasoning-action chains and extensive environmental feedback, distilled student agents tend to experience progress stagnation: becoming trapped in unproductive loops characterized by persistent failed strategies and difficulty making meaningful progress. Our systematic analysis shows that this phenomenon consistently occurs across diverse SLMs and task domains. To address this issue, we propose Progress-Aware Distillation (ProD), which explicitly detects and penalizes stagnatio

---

### [123] Delta Tokenizer: Reference-Identical Tokenization of Session Deltas and Segment-Parallelism for Long Prompts on Multicore CPUs

**链接**: https://arxiv.org/abs/2610.19801
**作者**: Zhenyu Zhang, Zhichao Cao
**来源**: cs.CL cs.DC cs.PF
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> An agent that drives an LLM sends the model the same conversation again and again, and each turn adds only a little text at the end. Inference engines reuse the KV cache of the shared prefix, so only the new tokens pass through the model. However, tokenization has no such shortcut. The CPU front end of the serving engine converts every request back into token IDs from its first character, which lengthens the time to first token (TTFT) and consumes CPU on every turn. We present Delta Tokenizer, a CPU tokenization front end that tokenizes only the delta between a request and the previous request of the same session. It retains the earlier token sequence, encodes again only the appended text and the short tail whose tokens the append could affect, and joins the two only at a position the tokenizer's splitting rules themselves cannot move, which keeps the result exact. For long requests with no state to reuse, it cuts the text where practical tokenizers already keep neighboring pieces inde

---

### [124] MemDuet: Learning Dual-Process Memory for Long-Context Reasoning

**链接**: https://arxiv.org/abs/2610.19928
**作者**: Jiangcheng Song, Haodong Jing, Yulin Mu, Lesong Tao, Jixin Wang, Jin Cui 等 (10 人)
**来源**: cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reasoning over infinitely long documents is becoming a reality with recurrent memory agents. However, increasing context length exacerbates the trade-off between reasoning performance and inference efficiency. Inspired by Kahneman's account of fast and slow thinking, we propose MemDuet, a dual-process memory framework that learns to coordinate a small language model for fast, parallel evidence selection from raw context chunks (System 1) with a large language model for memory-update verification and memory updates in document order (System 2). We train MemDuet in three stages: supervised fine-tuning of System 1 for evidence selection, Group Relative Policy Optimization (GRPO) of System 2 for verification and memory rewriting, and joint optimization of both policies to coordinate selection and updating for long-context reasoning. Experiments on diverse long-context reasoning benchmarks (RULER-HQA, LongBench v2, and 2WikiMultiHopQA) demonstrate a favorable accuracy-efficiency trade-off a

---

### [125] Memory-Efficient Subspace Optimization with Residual Correction: From Momentum SGD to Muon

**链接**: https://arxiv.org/abs/2610.19844
**作者**: Sifan Yang, Hongyi Tao, Dingzhi Yu, Haomin Bai, Wei Jiang, Silin Gao 等 (8 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Memory-efficient subspace optimization has emerged as a practical approach to reducing the memory cost of LLM training while preserving optimization performance. Previous algorithms typically rely on the leading singular subspace of stochastic gradients, yet the gradient noise may dominate the subspace in later training stages and can prevent convergence. To overcome this limitation, we adopt a residual correction framework, which maintains the optimizer states in the subspace and adds the orthogonal residual gradient to the parameter update. We first integrate this scheme into momentum SGD to develop SMRC, which attains an $O(T^{-1/4})$ convergence rate for a fixed orthonormal basis, matching that of full-space momentum SGD. Our analysis introduces a subspace virtual iterate to resolve the coupling between the momentum and the residual correction. Furthermore, we extend SMRC to a multi-stage variant which periodically recomputes bases to track the evolving dominant subspace and retain

---

### [126] Calibration and Risk-Budgeted Decisions with System One Models

**链接**: https://arxiv.org/abs/2610.19811
**作者**: Soundouss Messoudi, Youness Mansar
**来源**: stat.ML cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM workflows and agents rely on a set of binary decisions like allow/block an input, or discard/retain a retrieved document. When human deferral is unavailable, uncertain cases must still receive an action. We study System One decision scores in this setting by defaulting to a conservative fallback when uncertain, and controlling the false omission risk within the subset of inputs assigned the utility-maximizing action. Across six datasets covering moderation, safety, and reranking, we compare general System One models with task baselines and a local open-weights fine-tuned System One model. We show that naive baselines for threshold selection exceed the target risk in roughly half of settings with defined test risk, compared with 7.8\% for Learn Then Test (LTT), which leverages finite-sample statistical guarantees. Our results show why relying on a probability-like interface is insufficient for deployment decisions and how risk-budgeted selection trades useful action against observed

---

### [127] HyrCap: Hybrid Rank-Calibration of Action Proposals for Temporal Event Understanding

**链接**: https://arxiv.org/abs/2610.19526
**作者**: Rui Chen and Xingyu Chen and Pengxin Xu and Kai Chen and Junzhi Yu
**来源**: cs.CV
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Temporal action detection in long untrimmed videos suffers from inaccurate localization and low-quality proposals, especially with sparse annotations and ambiguous boundaries. For open-ended video understanding and LLM-driven event analysis, reliable proposals connect temporal localization, event annotation, and semantic understanding. However, conventional temporal action detection (TAD) pipelines lack explicit modeling of proposal localization quality, cross-representation support, and inter-proposal relations. We propose Hybrid Rank-Calibration of Action Proposals (HyrCap), a proposal-centric query-based TAD framework for temporal event understanding. Hybrid combines complementary video features with different localization cues, while Rank-Calibration adjusts proposal ranking confidence to reflect localization reliability and candidate competition. HyrCap treats dense query-based predictions as an over-complete temporal event hypothesis space. Cross-Representation Consensus Calibrat

---

### [128] ixi-sLM: On-Device sLM for AI Call Agent Service

**链接**: https://arxiv.org/abs/2610.19382
**作者**: Han-Sang Lee, Kyuho Lee, Juneyoung Park, Seongbae Lee, Jin Kyu Park, Minjae Kim 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Running an AI call agent on-device makes it private, network-independent, and free of per-query cloud cost, but shipping one as a real-world service imposes constraints a cloud deployment never faces: ~1GiB memory budget, in-call latency and thermal limits, static-integer NPU execution, Korean STT input far from sLM pretraining, and cloud-level quality expectations. We bring ixi-sLM, a 1.2B Korean sLM, to mobile NPUs through ON-DEVICE MODELING: domain-adaptive modeling trims the vocabulary by call frequency to shrink the embedding and LM head that take nearly half the model under INT4 transformer weights and refits the tokenizer to call speech (18% fewer tokens on call traffic), while task-aware quantization calibrates on real calls and assigns per-module mixed precision by activation sensitivity. A single domain-adapted model runs ixi-O's two production services, AI Call Summary and AI Call Answering, at 94% of a state-of-the-art cloud LLM's task-weighted quality; our on-device modeli

---

### [129] Joint Subspace Sparse Attention for Efficient Long-Context Decoding

**链接**: https://arxiv.org/abs/2610.19026
**作者**: Jiwon Song, Yoongon Kim, Jae-Joon Kim
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Sparse attention reduces the KV-cache traffic that dominates long-context LLM decoding, but practical methods largely operate at coarse granularity. Token-level selection offers finer control, yet presents two challenges: low-dimensional scoring may lose query--key structure needed for accurate ranking, while gathering scattered selected tokens can offset the resulting latency benefit. We introduce Joint Subspace Sparse Attention (JSSA) to address both challenges. For selection quality, JSSA learns a shared low-dimensional query--key subspace by minimizing token-score preservation error. We upper-bound the resulting non-convex objective with a tractable marginal objective that admits a closed-form spectral solution; direct refinement of the exact objective provides no measurable improvement in the tested settings. For execution efficiency, we develop a gather-free token-level indexed-attention kernel that supports distinct per-KV-head selections under the standard grouped-query attenti

---

### [130] Definition Grounding in Theory-Level Auto-formalization

**链接**: https://arxiv.org/abs/2610.19223
**作者**: Leyan Pan, Christian Szegedy, Frederick Rajasekaran, Robi Bhattacharjee, Gregory Constantine, Wenke Lee
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based auto-formalization systems can now generate formally verified Lean code at unprecedented rates. However, a formalization advances mathematical research only when further mathematical results can be built on it, especially when its definitions and helper lemmas are general enough to be imported and used idiomatically. We propose definition grounding, where definition formalizations are continuously judged and revised, as a method to ensure formalization quality. We find that agents formalizing definitions from textbook text often produce definitions that later statements cannot use, and only 25%-50% of their definition sets are compatible with all later statements. However, clarifying the informal definitions can improve this rate up to 77.5% averaged over all models. Furthermore, stating a small set of basic properties without proving them can improve model judges' capability to detect definitions with compatibility issues, at only about 11% of the definition formalization co

---

### [131] Learning from Self-Generated Responses: Reliability--Uncertainty Self-Distillation for Reasoning

**链接**: https://arxiv.org/abs/2610.19176
**作者**: Jinhao Pan, Bowen Wei, Yuqing Zhou, Ziwei Zhu
**来源**: cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reference solutions and question-specific rubrics are not always available to guide the teacher in self-distillation. A large language model's own solution attempts offer an alternative, but their quality is difficult to assess in open-ended tasks without automatic correctness checks, and even correct attempts can involve uncertain token predictions. We propose Reliability--Uncertainty Self-Distillation (\method{}) to learn from these attempts. The same model serves as teacher and student: the teacher receives the question and completed attempt, and the student matches the teacher's token-level predictions using a question-only prompt. \method{} weights each attempt's distillation loss by additively combining judged reliability, estimated from a self-judge's score and confidence, with student predictive uncertainty. Across eleven reasoning benchmarks, \method{} outperforms all five baselines in average accuracy, reaching 70.47\% on Qwen3-4B and 76.69\% on Qwen3-8B (8.90 and 2.10 percen

---

### [132] VideoHarness-SRSI: Structured Recursive Self-Improvement for Video Understanding Harness

**链接**: https://arxiv.org/abs/2610.19424
**作者**: Zihao Lin, Haoyu Dong, Haobo Xu, Chi-Chih Chang, Xuying Ning, Yinglong Xia 等 (10 人)
**来源**: cs.CV cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM system capabilities depend not only on model parameters but also on the executable harnesses that organize information acquisition, tool use, reasoning, and memory. Recursive harness evolution can automate their design, but how it can reliably discover generalizable systems from limited, noisy, and repeatedly reused feedback remains unclear. We study this question in agentic video understanding, where rich multimodal evidence and coupled mechanisms make harness optimization challenging. We first introduce VideoHarness-BRSI, a recursive self-improvement framework that evolves video harnesses around a frozen vision-language model. Analyzing over 4,000 evolved candidates, we find it competitive with hand-engineered systems but identify three interconnected failure modes: validation overfitting, search-budget dilution, and the early-experience trap. We trace all three to a common root: the same imperfect validation evidence drives both harness revisions and the proposer's search strate

---

### [133] TRACER: Trace-Regularized Training Against Indirect Prompt Injection

**链接**: https://arxiv.org/abs/2610.19133
**作者**: Kshitij Mishra, Salem Lahlou, Nils Lukas
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Indirect prompt injection uses untrusted retrieved content, tool outputs, or agent messages to override an LLM's intended behavior. We show that defense robustness is channel-conditioned: the same attack succeeds 18% of the time as a follow-up message but 53% when placed in retrieved context. We propose TRACER (Trace-Regularized Adversarial Channel Exposure with Reward-shaping), a channel-aware adversarial training method that samples presentation wrappers and combines an answer-anchored, evidence-gated reward with ATRC, which aligns attacked reasoning with clean evidence when an injection is invalid. On GSM8K with Qwen2.5-3B-Instruct, TRACER reduces RAG-framed ASR from 65.5% to 6.1% while preserving 78-82% clean accuracy. Joint RAG+tool training achieves 13.9% average ASR across framings at 3B scale, while a single epoch at 7B reaches 9.4%. These results demonstrate that robust defenses must explicitly train and evaluate across deployment channels.

---

### [134] Evolve Together, Fall into Place: How Social Scaffolding Shapes Self-Evolving Multi-Agent Systems

**链接**: https://arxiv.org/abs/2610.19799
**作者**: Seojin Hwang, Youngmin Choi, Hwanhee Lee
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent work lets LLM agents evolve their own harness, up to the team itself. Yet in human groups, the same abilities achieve different outcomes under different social conditions. Borrowing the notion of scaffolding from developmental psychology, we investigate whether the social scaffolding of a self-evolving multi-agent system (MAS), namely its team composition and structure of interdependence (e.g., collaboration, conformity, or competition), shapes how the team evolves. We present AGORA (Agents Growing through Organization and Relational Arrangements), a framework that varies the two axes independently across three evolution mechanisms. Across web search, codebase understanding, and document QA, we find that (1) evolution alone rarely helps, while the right scaffolding surpasses a strong agent evolved alone by up to 25 points; (2) it does so by moving authority to the most capable member while the others step back; and (3) this member, having grown within the team, outperforms the s

---

### [135] HACHIMI-II: From Role-Play to Learner Behavior Modeling for Faithful Student Simulation

**链接**: https://arxiv.org/abs/2610.19654
**作者**: Yilin Jiang, Fei Tan, Xuanyu Yin, Jing Leng, Aimin Zhou
**来源**: cs.CL cs.AI cs.CY cs.LG
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Simulated students let researchers test tutoring systems and teaching strategies before real learners are available, but only if the simulation reproduces where a particular learner succeeds and fails. The common approach asks a large language model to role-play a student, but a role does not model what this learner knows or will do next, so the model's own competence fills the gap. Simulated students perform at a level set by the model, differ little from one another, and seldom make the real learners' errors. We model the learner's behavior and recast student simulation as third-person prediction of the learner's next action. HACHIMI-II builds a student model from the learner's history, infers the learner's state for the current item or tutor turn, and compiles it into a behavior harness that constrains the next action. On three item-response datasets, the Wasserstein-1 distance between simulated and real student ability is 2.4--8.4$\times$ smaller than that of the strongest baseline

---

### [136] Unlocking Structured Pruning for Reasoning Language Models via Attention-Preserving MLP Trimming

**链接**: https://arxiv.org/abs/2610.19121
**作者**: Woosang Lim, Haneul Yoo, Vincent-Daniel Yun, Sungjoo Yoo
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Structured pruning reduces LLM inference costs by removing model components to produce smaller dense models. However, existing methods can cause reasoning performance to collapse on long-form reasoning tasks such as AIME. We propose \textit{LayerTrim}, a training-free structured pruning method that identifies redundant decoder layers and selectively trims their MLP features while preserving attention and decoder depth. LayerTrim is the first training-free structured pruning method designed to preserve long-form reasoning without gradients or recovery training. Across three reasoning language models and five benchmarks, LayerTrim outperforms existing structured pruning methods in most evaluated settings, improving average accuracy by up to 21.4 percentage points over RESP. On \texttt{Qwen3-14B}, LayerTrim achieves 1.24$\times$ faster prefill and 19.7\% lower peak GPU memory than the dense model, while better preserving reasoning ability. It also achieves the shortest average generation 

---

### [137] Qwenfant: Train Big Character-level BabyLMs on Concise Parallel Text

**链接**: https://arxiv.org/abs/2610.19294
**作者**: Lukas Edman, Alexander Fraser
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> This work concerns our submission for the Multilingual track of the 2026 BabyLM Challenge. We improve on our baseline using data that has been summarized and translated by an LLM, showing that higher-quality data can come from synthetic sources. We further improve with 2 simple changes: using a larger model, and using a character-level vocabulary. Both of these changes require LoRA-style fine-tuning for realizing their full potential. We dub our final Qwen3-based model Qwenfant, which, at the time of submission, ranks 1st in the Multilingual track.

---

### [138] Towards a Data-Centric Understanding of Spatial Reasoning in Multimodal Large Language Models

**链接**: https://arxiv.org/abs/2610.19108
**作者**: Mahdieh Mallahnezhad, Masoud Jafaripour, Mohamadali Tofigh, Sheila Schoepp, Osmar R. Zaiane
**来源**: cs.CV cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal Large Language Models (MLLMs) have been widely applied in embodied agents and robotics for vision tasks. However, MLLMs suffer from limitations in spatial reasoning and perception. Post-training techniques have shown promise for improving these capabilities; yet, there are limited data-driven surveys of such approaches. In this survey, we consider approaches to fine-tuning pretrained MLLMs for spatial reasoning tasks, ranging from supervised to reinforcement learning, with an emphasis on the datasets used. We investigate themes of dataset construction, data modality and annotation, and evaluation of the resulting models. Based on these themes, we categorize research into three groups: dataset design, dataset construction and evaluation. We find four main methods for constructing fixed spatial annotations: rules and templates, LLM prompting, procedural generation, and human-in-the-loop. We also observe substantial variation in evaluation approaches, including different scorin

---

### [139] How Inner Optimizers Shape Replica Scaling

**链接**: https://arxiv.org/abs/2610.19064
**作者**: Eugene Belilovsky, Stefan Horoi, Edouard Oyallon, Benjamin Th\'erien
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Training large language models (LLMs) across geographically distributed and poorly interconnected compute pools or data centers has become a topic of significant interest. This has led to increased study of local optimization methods such as DiLoco for LLMs, especially those that use local (or inner) adaptive or preconditioned optimizers, which are critical for high-performance LLM training. However, a central challenge remains: it is well known that increasing the number of model replicas (replica scaling) while fixing the total training budget leads to monotonically decreasing performance. Existing work has empirically demonstrated that the choice of inner optimizer (Muon v.s. AdamW) can significantly improve this trend, but offers only limited explanation of the performance difference. In this work, we consider a range of inner-optimizers and identify two important factors that impact replica scaling: (1) the covariance structure of the pseudo-gradients and (2) the impact of batch s

---

### [140] Lotus: Learning to Understand Time-series by Learning to Forecast

**链接**: https://arxiv.org/abs/2610.18877
**作者**: Van Dai Do, Huu Hiep Nguyen, Minh Hoang Nguyen, Manh Nguyen, Hung Le
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Time-series language models typically align numerical signals with language using labels, captions, or question-answer pairs. Although such supervision encourages linguistic representations, it does not explicitly require them to preserve information about how the underlying time-series signal evolves. We introduce forecast grounding, a pretraining principle that requires language-aligned time-series representations to remain predictive of the future evolution before they are adapted to downstream tasks. We instantiate this principle in LOTUS, which divides each time-series channel into non-overlapping patches and maps them into the LLM embedding space. It then predicts the next patch from the LLM hidden states of the time-series tokens, encouraging the learned representation to retain temporal information. To capture both temporal changes and periodic patterns, we also propose a temporal-spectral patch representation that combines each raw time-series patch with its spectral represent

---

### [141] HERO: Harnessing Evidence for Test-time Refinement and Prompt Optimization in Program Generation

**链接**: https://arxiv.org/abs/2610.19184
**作者**: Mingyu Lu, Timothy Ossowski, Tristan Naumann, Hoifung Poon, Peniel Argaw
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Harness optimization improves LLMs by refining reusable prompts and scaffolding, yet requires further adaptation for program generation tasks such as text-to-SQL and text-to-Python. Existing methods often rely on LLM reflectors to propose harness updates, which can fix observed failures but also disrupt previously correct behavior. Text-to-code tasks offer a natural way to mitigate this issue: we can execute generated outputs, allowing us to evaluate and verify the effects of proposed updates directly. Building on this signal, we introduce \textsc{HERO} (\textbf{H}arnessing \textbf{E}vidence for \textbf{R}efinement and \textbf{O}ptimization), which combines offline and test-time harness optimization. At the first stage, \method{} learns reusable prompt updates from execution-verified successes and failures and validates candidate revisions before adoption. At test time, we treat the generated code as an instance-specific harness and refine it using execution feedback. Across four SQL, 

---

### [142] Twenty Days Later: A Pre-Registered Test of History-Based Forecasts of Brand Mentions in Gemini Answers

**链接**: https://arxiv.org/abs/2610.19608
**作者**: Dmitrij \.Zatuchin
**来源**: cs.IR cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Counts of which brands a large language model names are useful only if they hold long enough to act on. We test this with a pre-registered replication. The same 162 requests (54 questions in English, Estonian and Finnish about three software categories, four of twelve candidate brands per question, three repeats) were sent to gemini-3.1-pro-preview in three waves within about ten hours on 22 and 23 September 2026, and again on 13 October 2026, 20.3 days after the third wave, with identical request bodies. The plan and its decision rule were frozen, hashed and registered on OSF before the first call. The outcome is a lexical mention label per answer and brand, 648 per wave. The primary forecast, each brand-and-question cell's mention rate over the nine earlier answers, scored Brier 0.0281 and log loss 0.126, against Brier 0.0259 for the six-answer forecast of the 8-hour wave and a registered ceiling of 0.0559. It beat brand history (0.104), the overall rate (0.234) and a constant 0.5 (0

---

### [143] FinGREAT: Evaluating LLMs on Financial Graph-guided Retrieval And Typing

**链接**: https://arxiv.org/abs/2610.19240
**作者**: Ashman Mehra, Bryan Routledge, Jane JaeYeon Pyo, Pierre Jinghong Liang
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Financial disclosures express the underlying relationships of double-entry accounting through unstructured text. While financial LLM benchmarks predominantly emphasize question answering and classification, schema-guided evidence discovery remains relatively under-explored. We investigate whether open-weight LLMs can extract and classify evidence corresponding to predefined double-entry accounting relationships underlying the text. Using a financial accounting graph comprising 11 nodes (accounts) and 11 edges (transaction types), we evaluate mid-sized models from 5 open-weight families across 1,300 SEC 10-K Item 7 filings spanning 26 years, comparing their extraction performance against three proprietary models. Results reveal substantial differences in extraction volume, edge distributions, and cross-model agreement. Building on this study, we introduce a human-annotated relation classification benchmark comprising 483 passages across three financial accounting categories, evaluating 

---

### [144] SoK: Grading Open-Text Legal Answers, from Law School Exams to Trustworthy Rubric Judges

**链接**: https://arxiv.org/abs/2610.19992
**作者**: Sebastian Nagl
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Law students are examined through open-text answers: case solutions, essays and memos that apply the law to a set of facts. Such answers are expensive to grade, human graders disagree widely on them, and large language models (LLMs) now offer to grade them at scale, both in teaching and in the benchmarks that test legal AI. This paper systematizes how open-text legal answers can be evaluated. We derive eight desiderata from educational measurement and from the law that governs exams, among them validity, reliability, reasons, credit for defensible alternative solutions, robustness to gaming and human oversight. We then compare eight evaluation paradigms against them, from unstructured human grading to LLM judges with instance-specific rubrics and pairwise comparison. Three findings stand out. A rubric written for the task is the strongest lever for agreement between an LLM judge and human graders, but the reported figures answer different questions and rarely come with the human agreem

---

### [145] Evaluating Large Language Models for Multilingual Abstractive Summarization: A Comprehensive Study of English and Bengali

**链接**: https://arxiv.org/abs/2610.19003
**作者**: Khan Mahi Al Atahar, Nazifa Tasneem, Ajwad Abrar
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Abstractive summarization remains challenging across languages, where linguistic quality and factual consistency may diverge, particularly in low-resource settings. We present a standardized zero-shot benchmark of eight closed-source and open-weight LLMs on size-matched English and Bengali XL-Sum test sets. Our evaluation combines lexical and semantic metrics with reference-free factuality verification and multidimensional LLM-as-a-Judge assessment, providing a comprehensive analysis of both surface-level quality and factual reliability in multilingual summarization. Results reveal substantial cross-lingual variation: GPT-5.6 Luna leads several English lexical metrics but does not maintain the same advantage in Bengali, where LLaMA 3.3 70B achieves the highest ROUGE and BLEU scores. Gemini 2.5 Flash obtains the highest observed Bengali factuality score. Furthermore, evaluation methods produce different model rankings, highlighting the limitations of relying on a single metric for multi

---

### [146] Beyond the Trial-and-Error Loop: Hybrid Projection and Automated Tuning for Distributed Training

**链接**: https://arxiv.org/abs/2610.19423
**作者**: Anshu Raina, Peyman Razaghi, Yuankai Chen, Cheng Yao, Yao Fu, Vidushi Goyal 等 (10 人)
**来源**: cs.AI cs.DC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Configuring distributed LLM training across hundreds of GPUs requires jointly optimizing tensor, pipeline, expert, context, and data parallelism alongside micro-batch size, recomputation, sharding, and overlap, a combinatorial space where memory legality can hinge on a single byte of activation accounting. Today, teams navigate it through expensive multi-node trial and error, burning GPU-hours on crashes and suboptimal recipes. We present Primus Projection, which closes this loop with two coupled components. First, a hybrid projection engine that measures what it can and simulates what it cannot: GPU microbenchmarks on as few as a single device capture compute kernels and any in-scope communication; a sub-node downscale-measure-upscale workflow analytically restores out-of-scope collectives, FSDP overlap, and the full pipeline schedule at the multi-node target. A pure simulation mode runs entirely on CPU, enabling pre-silicon planning without any GPU. Second, the Primus Tuning Agent tr

---

### [147] RLPE: Teaching LLMs to Prompt with Reinforcement Learning

**链接**: https://arxiv.org/abs/2610.19062
**作者**: Rahul Singhal, Karime Maamari, Pradyumna Tambwekar
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Prompting is a widely used method for adapting general-purpose LLMs to domain-specific tasks. Effective prompts can be tedious to create manually, so prompt writing is increasingly handed to LLMs, with recent work training LLMs to write prompts for other models. These techniques either write prompts without observing how the task model behaves, blind to the failure modes the prompt should address, or must run alongside the task LLM at inference time, adding overhead to every query. Neither reflects how prompt engineering is often practiced. To close this gap, we introduce Reinforcement Learned Prompt Engineering (RLPE), which trains a model to analyze traces of a separate task model and write a prompt targeting the failures it observes. RLPE rewards the trained model strictly on prompt performance, so it learns the prompting strategies that improve the task model. The prompt is generated once and reused across the task, so inference does not require the trained model. Since RLPE needs 

---

### [148] MolHop: Scaffold-Hopping Molecular Design with Agentic Reinforcement Learning

**链接**: https://arxiv.org/abs/2610.19920
**作者**: Yanyi Su, Chenyan Wang, Yulei Gong, Yeyun Chen, Xiaohui Yang, Jun Cheng
**来源**: cs.LG cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Molecular design is often formulated as an optimization problem over existing molecular spaces. However, molecular optimization and the discovery of structurally distinct replacement molecules represent two fundamentally different search problems. LLM-based molecular design agents typically perform the former, conducting local refinement within the neighborhood of existing structures to improve target properties through structural modifications. In contrast, the latter requires exploration of a broader chemical space to discover molecules with entirely different scaffolds while preserving the functional characteristics of reference molecules. We propose MolHop, an agentic framework for cross-scaffold molecular discovery that enables models to navigate and edit within a pre-organized chemical space. MolHop organizes approximately 1.6 million molecular scaffolds from commercial molecules into a coarse-to-fine hierarchical action space. The agent selects new exploration regions through sc

---

### [149] Decoupled Marginal Sharpening for Training-Free Inference-Time Scaling

**链接**: https://arxiv.org/abs/2610.20483
**作者**: Weixin Wang, Wei Deng, Anderson Schneider, Yuriy Nevmyvaka, Pan Xu, Andrew Bennett
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We study how to improve LLM reasoning at inference time without updating model weights or using external reward models. Recent reward-free power-sampling methods define the sequence-level power target $\pi_\alpha(y\mid x)\propto p_0(y\mid x)^\alpha$, where $\alpha>1$, which increases the relative probability of completions that are already likely under the base model. Existing methods use Metropolis--Hastings or Sequential Monte Carlo (SMC) to approximately sample from this target. However, two challenges arise at different levels. At the target level, full-sequence sharpening can concentrate probability on a few exact reasoning--answer trajectories, suppressing alternative paths that support the same answer. At the sampler level, finite-particle SMC can suffer from path collapse when resampling repeatedly duplicates a few high-weight prefixes. To address these challenges, we propose Decoupled Marginal Sharpening (DMS), which separately controls how strongly the model favors particular

---

### [150] Beyond Static Cues: Unified Dynamic Detection of MLLM Backdoors via Dual-Flow Trajectory Analysis

**链接**: https://arxiv.org/abs/2610.20319
**作者**: Yinzhen Huang, Jiahe Xie, Yitong Sun, Ruochen Zhang, Xingxing Wei
**来源**: cs.CV cs.AI
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal Large Language Models (MLLMs) are increasingly deployed in safety-critical domains, yet their susceptibility to backdoor attacks remains a formidable challenge. While existing defenses have evolved from visual-centric patch cues to unsupervised internal attention statistics, they are fundamentally constrained by a reliance on static snapshots and attack-specific heuristics. Given the intricate interplay between dual modalities, the vast design space for multimodal triggers allows diverse threats, such as textual injections, sub-perceptual noises, and coordinated cross-modal triggers, to easily circumvent such rigid priors, particularly when attack types are unknown in real-world applications. In this paper, we rethink backdoor detection by shifting the diagnostic paradigm from static observations to dynamic output evolution. We observe that a successful attack inevitably hijacks the model's decoding trajectory, skewing internal modal contributions during generation while mai

---

### [151] ActICL: Post-Training for Agentic Multimodal In-Context Learning

**链接**: https://arxiv.org/abs/2610.19475
**作者**: Yanshu Li, Ruixiang Tang, Junyi Jessy Li, Elias Stengel-Eskin
**来源**: cs.CV cs.CL
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal in-context learning (ICL) is an important capability of multimodal large language models (MLLMs). Its performance is closely tied to the demonstrations it uses, making demonstration retrieval a core problem for ICL. Common methods use fixed scoring methods to retrieve all the demonstrations at once, which may introduce redundancy and noise. Context-aware retrieval methods have emerged to address this problem by allowing incremental retrieval from a growing context. However, none of them lets the MLLM learn how to judge what new demonstrations it needs and then carry out progressive retrieval on its own. To this end, we introduce ActICL, which trains an MLLM agent to acquire and use an ICL context via tool-augmented reasoning. An ActICL agent analyzes its own information gaps during iterative reasoning and tool-use actions. Based on these gaps, it performs targeted retrieval to acquire a set of initial candidates. It can then use the existing context to further filter the can

---

### [152] WinARDet: Compressed Window Auto-Regression for Long-Horizon Vision-Language Grounding

**链接**: https://arxiv.org/abs/2610.19419
**作者**: Chenxu Wang, Hangyi Kuang, Bo-Wen Yin, Yuxuan Li, Quan-Sheng Zeng, Yang Zhang 等 (9 人)
**来源**: cs.CV
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> MLLM-based detectors formulate vision-language grounding as autoregressive coordinate generation, yet in dense scenes, they often collapse into a box repetition loop, repeatedly emitting identical boxes until the decoding budget is exhausted. We trace this failure to historical-answer attention takeover: Under full-history autoregression, repeated coordinate tokens in the growing answer history attract disproportionate attention, crowding out the attention sinks needed to attend to new visual evidence. % To break this loop, in this paper, we propose \textbf{Compressed Window Auto-Regression} (WinAR). This new mechanism partitions a long answer sequence into consecutive generation windows and restricts full token-level autoregression to the current window only while compressing each previous window into a fixed set of latent tokens that condition subsequent decoding. This design reduces the repeated exposure to raw historical coordinates that triggers the attention takeover, yet preserv

---

### [153] MMKG-R1: Constructing Multimodal Knowledge Graphs via Reinforcement Learning

**链接**: https://arxiv.org/abs/2610.19341
**作者**: Zongyu Wu, Yilong Wang, Xiaochen Wang, Minhua Lin, Yuan Zhong, Fenglong Ma 等 (8 人)
**来源**: cs.CV
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal knowledge graphs (MMKGs) organize information across different modalities to support multimodal Graph Retrieval-Augmented Generation (RAG), which aims to improve the performance of multimodal large language models (MLLMs). The effectiveness of these multimodal Graph RAG methods largely depends on the quality of the constructed MMKGs. However, most existing methods construct MMKGs without explicit guidance on graph quality, while reinforcement learning (RL)-based methods that rely on final-answer correctness may provide only indirect feedback on MMKG quality. To address these limitations, we propose MMKG-R1, a novel MMKG-quality-driven RL framework for training an MLLM as a multimodal knowledge constructor. To be specific, MMKG-R1 introduces multiple quality-aware rewards to directly evaluate both the quality of information extracted from individual knowledge sources and the quality of the assembled MMKG. These rewards are then used to guide the RL training. Experiments acros

---

### [154] FACES: Fine-grained Gated Semantic Alignment for Multimodal Emotional Support Conversation

**链接**: https://arxiv.org/abs/2610.20051
**作者**: Hang Ren, Peidong Wang, Yichen Gao, Wen Zhang, Jiayang Yu, Xiaocui Yang 等 (7 人)
**来源**: cs.CL
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In recent years, with advances in multimodal interaction technologies and the growing demand for intelligent emotional support, Multimodal Emotional Support Conversation (MESC) has emerged as an important task. However, existing systems still suffer from shallow responses and inappropriate support strategies due to weak semantic feedback, cross-dimension reward compensation, and coarse reasoning supervision. To address these challenges, we propose FACES, a fine-grained gated semantic alignment framework for MESC. Specifically, FACES integrates multi-source rewards to construct multidimensional semantic and functional alignment signals, employs a non-compensatory gated fusion mechanism to reduce cross-dimension reward offset, and leverages structured Chain-of-Thought (CoT) anchors to perform token-level credit assignment. Under a controlled response-length protocol, FACES improves the average MLLM-based evaluation score from 3.61 to 4.04 and achieves an 80.22% pairwise win rate over SOT

---

### [155] GeoThinker-$F$: Endogenous Predictive World Representations for Fast Spatial Intelligence

**链接**: https://arxiv.org/abs/2610.20592
**作者**: Haoyuan Li, Qihang Cao, Huanyuan Zhou, Xin Hu, Sijia Chen, Zihan Guo 等 (10 人)
**来源**: cs.CV
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Existing geometry-aware Multimodal Large Language Models (MLLMs) increasingly rely on external 3D encoders to provide structural priors, but executing these additional encoder paths at inference introduces substantial latency and computational overhead. We propose GeoThinker-$F$, an efficient framework that internalizes spatiotemporal perception by transforming causal MLLM hidden states into predictive latent world representations. Our key insight is that intermediate semantic representations contain sufficient information to predict useful representations of current geometry and future semantics, without requiring an exact reproduction of features from a dedicated 3D encoder. To realize this idea, GeoThinker-$F$ adopts a decoupled two-stage training strategy. In the first stage, the MLLM backbone is frozen while lightweight Latent Frame Prediction (LFP) heads learn from an offline 3D geometry expert and next-frame semantic targets. In the second stage, the external expert is removed, 

---

### [156] On the Limits of Representation-Based Test-Time Adaptation for Multimodal LLMs

**链接**: https://arxiv.org/abs/2610.19892
**作者**: Miko{\l}aj Pi\'orczy\'nski, Wojciech Masarczyk, Damian S\'ojka, Sebastian Cygert, Bart{\l}omiej Twardowski
**来源**: cs.LG cs.CV
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Vision-language models suffer significant accuracy drops under common corruptions. While test-time adaptation (TTA) successfully mitigates these shifts in CLIP-like contrastive models, its application to generative multimodal large language models (MLLMs) remains underexplored and uniquely challenging due to their sequential token generation. In this work, we demonstrate that representation-based TTA fails to recover performance in MLLMs. Our experiments reveal that even when violating standard TTA assumptions by leveraging target data offline, sample-blind feature alignment recovers only marginal accuracy. We attribute this failure to the nature of corruption shifts: unlike CLIP-like architectures, which benefit from a shared domain-shift direction within a single pooled classification embedding, MLLM visual token sequence shifts are nearly orthogonal and span the full embedding space.These findings bound what any sample-blind, position-shared correction at a single encoder site can a

---

### [157] Towards Modality-Agnostic Seizure Classification: A Unified Deep Learning Framework for Heterogeneous EEG and Intracranial EEG Signals

**链接**: https://arxiv.org/abs/2610.16596
**作者**: Ramya Sundaram, Muhammad Aslam Jarwar, M Uma, Sunder Ali Khowaja, and Qurat-Ul-Ain Mastoi
**来源**: cs.LG cs.AI
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [158] NeuroDETR: Multiscale Discrete Spatiotemporal Tokenization for Asynchronous EEG Event Detection

**链接**: https://arxiv.org/abs/2610.20349
**作者**: Yaozhi Wen, Kun Zhao, Wei Wei, Haoyang Chen, Kangning Wang, Yi Sun 等 (10 人)
**来源**: cs.LG
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Asynchronous EEG event detection supports practical brain-computer interfaces by identifying event classes and temporal boundaries directly from continuous recordings without predefined event boundaries at inference time. The primary challenge lies in extracting event-related patterns embedded in ongoing background activity. To address this, we propose \textbf{NeuroDETR}, a discrete spatiotemporal multiscale framework that combines structured tokenization with event-aware feature refinement. Multiscale temporal codebooks capture brief responses and sustained dynamics, while Spatial-Pyramid VQ hierarchically encodes spatial structure across EEG channels. These complementary representations form a compact event memory for jointly classifying events and estimating their onsets and offsets. Before tokenization, we apply FOCAL, an event-aware sparse attention module that uses predicted event presence to guide temporal feature refinement and spatial aggregation, emphasizing likely event peri

---

### [159] TEX-MEX: Similarity-Guided Temporal Contrastive Learning for Time Series

**链接**: https://arxiv.org/abs/2610.19557
**作者**: Aditya Radhakrishnan, Maxwell A. Xu, Wanting Mao, Santosh Kumar, Harish Haresamudram, James M. Rehg
**来源**: cs.LG cs.AI
**匹配关键词**: EEG
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Contrastive learning for time series depends on deciding which pairs of inputs should be treated as similar and dissimilar. Because few augmentations reliably preserve meaning in time series, prior methods have relied on two disjoint notions of similarity between windows: structural similarity, which relates windows with similar morphology, and temporal similarity, which relates windows that occur close together in time. We introduce TEX-MEX, to our knowledge the first approach to unify the two into a single relationship. Given a random batch of windows drawn across the dataset, TEX-MEX uses the encoder to identify which windows are structurally similar or dissimilar to each other. It then pulls each window toward the temporally shifted versions of similar windows and pushes it away from those of dissimilar ones, learning what typically accompanies similar windows in time. Across PPG, EEG, ECG, accelerometry, and continuous glucose monitoring, TEX-MEX broadly achieves state-of-the-art 

---

### [160] Moving Beyond the Flat Screen: Opportunities and Challenges of Extended Reality for Studying Human Brain and Behavior

**链接**: https://arxiv.org/abs/2610.19199
**作者**: Tom Bullock, Radha Kumaran, You-Jin Kim, Emily Machniak, Tobias H\"ollerer, Barry Giesbrecht
**来源**: cs.HC
**匹配关键词**: EEG
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Much of what we know about human perception and cognition comes from austere experimental settings: static stimuli presented to sedentary observers on flat monitors, complex responses reduced to simple button presses, and brain activity recorded from immobilized heads using EEG or fMRI. These highly controlled paradigms have provided remarkable insights, but capture a small and often unusual slice of behavior, raising questions about how well the findings generalize to the real world. Extended reality (XR), spanning both immersive virtual reality (VR) and augmented reality (AR) that overlays digital content on the real world, offers a way beyond these constraints, supporting controlled, reproducible experiments in which participants actively engage with three-dimensional tasks. Drawing on a growing body of VR and AR studies of attention, memory, and language -- our own and others', some involving EEG -- we outline what XR makes newly possible for cognitive neuroscience and reflect on t

---

### [161] SuperAI: Merging Capabilities Across Heterogeneous Foundation Models

**链接**: https://arxiv.org/abs/2610.15322
**作者**: Jingtong Dou, Chuancheng Shi, Wenhua Wu, Wei Bao, Fei Shen, Zhiyong Wang and Tat-Seng Chua
**来源**: cs.AI cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [162] When Does Depth Help? Understanding Layerwise Inference in Tabular Foundation Models

**链接**: https://arxiv.org/abs/2610.19814
**作者**: Wenwen Gong, Haotian Gu, Zhen Yang, Jiaying Ma, Hanqing Zhang, Zhongshen Wang 等 (9 人)
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Transformer-based tabular foundation models (TFMs) achieve state-of-the-art performance on small to medium-sized tabular prediction tasks while processing diverse inputs through a shared stack of layers. Recent layerwise analyses identify strong predictive performance in early TFM representations and substantial overlap in computation across layers. However, early predictive accessibility alone does not establish whether later layers are dispensable for every input, and aggregate accuracy can obscure which inputs benefit from additional computation. We study all 24 in-context-learning layers of TabPFN-3 across 272 classification datasets, combining representation geometry, prediction trajectories, truncation, and structural interventions, while also examining related representation dynamics in four additional TFMs. We uncover a pronounced expansion-compression trajectory, with stronger late dimensional contraction associated with larger increases in class-prototype separation. A target

---

### [163] TIMERSI: Towards Self-Improved Agentic Deployment for Time-Series Foundation Models

**链接**: https://arxiv.org/abs/2610.19725
**作者**: Haoxin Liu, Deqing Fu, Lucheng Fu, Yiqiao Jin, Rushi Qiang, Harshavardhan Kamarthi 等 (7 人)
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Time-series foundation models provide strong zero-shot forecast, but deployment for real- world applications still requires task-specific designs for model inputs and outputs. Direct inference can leave domain knowledge and re- curring forecast errors unaddressed, while tai- lored pipelines require substantial human ex- pertise and effort. We introduce TIMERSI, a self-improving agentic deployment system around frozen forecasting models. A cod- ing agent translates task descriptions into ex- ecutable pipeline changes. It tests each re- vision on historical forecasting windows and uses observed errors to guide subsequent re- visions. During deployment, an adaptive se- lector chooses among the resulting pipelines using completed forecasts under similar con- ditions. Across 198 tasks on TIME and FEV- bench, TIMERSI outperforms all submissions on six point and probabilistic forecasting met- rics. Controlled comparisons support the value of feedback-guided revision over non-iterative pipelin

---

### [164] What Do Foundation Models for Market Microstructure Learn? A Controlled Study with Synthetic Limit Order Books

**链接**: https://arxiv.org/abs/2610.20104
**作者**: Fernando Acero
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Autoregressive transformers trained on limit order book (LOB) message streams are increasingly proposed as foundation models for market microstructure. Because the generative process of real markets is unknown, these models can be judged only by the realism of their output, leaving open what they actually learn. We make the question answerable by inverting the setup: we train GPT-style models on order flow from simulators whose latent parameters are known, so that the Bayes-optimal predictor, the generating state, and the exact data entropy serve as references. Measured against them, next-token pretraining on order flow implements amortized Bayesian inference over market regimes. The learned predictive matches the exact Bayes optimum to within a millinat per token and approaches the oracle floor even on a nonstationary family whose latent state drifts within an episode, a regime that requires filtering. The latent regime is linearly decodable from frozen activations, well above baselin

---

### [165] RRM-GPT: A Framework and Vision for Radio Resource Management Foundation Models

**链接**: https://arxiv.org/abs/2610.04296
**作者**: Ahmed Aboulfotouh, Akram Bin Sediq, Koosha Pourtahmasi Roshandeh, Omar Mashaal, Ahmad M. Nagib, Jale Sadreddini 等 (7 人)
**来源**: eess.SP cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [166] CORTEG: Foundation Models Enable Cross-Modality Representation Transfer from Scalp to Intracranial Brain Recordings

**链接**: https://arxiv.org/abs/2605.10337
**作者**: Liuyin Yang, Qiang Sun, Bob Van Dyck, Eva Calvo Merino, Marc M. Van Hulle
**来源**: cs.AI eess.SP
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [167] Capability $\neq$ Interpretability: Human Interpretability of Vision Foundation Models

**链接**: https://arxiv.org/abs/2605.20337
**作者**: Julien Colin, Lore Goetschalckx, Nuria Oliver, Thomas Serre
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [168] Remember, Revisit, Revise: Scaffold Memory for Long-Horizon 3D Geometry

**链接**: https://arxiv.org/abs/2610.19674
**作者**: Soumick Sarker, Mengmi Zhang
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Geometry foundation models estimate camera poses and 3D scene structure from video sequences, but maintaining consistent reconstructions over long horizons remains challenging. Feed-forward models process long sequences as independent, fixed-length frame windows and align their predictions, causing pose and reconstruction errors to accumulate across windows. Streaming models retain information from past frames to inform future predictions, but cannot revise earlier estimates when later observations reveal errors. To address this, we introduce Scaffold MemOry for Revision (SMORE), a framework equipping frozen geometry foundation models with a revisable external memory for long-horizon inference. Inspired by hippocampal associative memory in biological brains, which links spatial context with sensory experience, SMORE associates where an observer is with what it observes, enabling past observations to be stored, retrieved, verified against new evidence, and revised when inconsistencies a

---

### [169] GDBA-Net: A Gated Dual-Branch Adaptation of SAM2 for Robust Cross-Domain Nuclei Segmentation

**链接**: https://arxiv.org/abs/2610.20073
**作者**: Biplab Poudel, Betserai Albert Magarire, Anish Kumar Shah, Jiacheng Xie, Dong Xu
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Accurate nuclei segmentation underpins quantitative computational pathology, yet remains challenging due to morphological variability, weak boundaries, nuclear crowding, and pronounced domain shifts arising from differences in tissue preparation, staining, and acquisition. While deep learning and recent foundation models have improved segmentation performance under matched distributions with the original training data, their generalization across heterogeneous histopathology domains remains limited. We introduce GDBA-Net, a parameter-efficient nuclei segmentation framework built around the proposed Gated Dual-Branch Adapter (GDBA). GDBA-Net adapts a frozen SAM2 encoder by integrating pretrained semantic representations with explicit frequency-derived structural priors. The complementary representations are independently transformed through Grid MLP branches and dynamically integrated using sample-adaptive channel-wise gating, selectively emphasizing structural cues relevant to nuclear 

---

### [170] Spectral World Renderer: Unified 3D Hyperspectral Unmixing

**链接**: https://arxiv.org/abs/2610.19520
**作者**: Chia-Ming Lee, Yu-Jou Hsiao, Ming-Ching Chang, Xin Li, Yu-Lun Liu, Chih-Chung Hsu
**来源**: cs.CV cs.GR
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Cameras and the foundation models built on them recognize what a 3D scene contains, but not what it is made of: surfaces of the same colour can be different materials. Hyperspectral unmixing explains each spectrum as a mixture of material signatures, yet in 3D it is applied to rendered images after the views are composited, or tied to slow implicit fields, and no multi-view data with known composition exist to check the result. We present the Spectral World Renderer (SWR), which unifies world generation and unmixing. A coding agent builds executable 3D worlds that are rendered with measured spectra, so every hyperspectral image comes with exact labels and sub-pixel proportions; the resulting SWR-Bench provides eight indoor and outdoor worlds in which decompositions can be verified. SWR then unmixes inside rendering: each Gaussian of a compact 3D representation is decoded into material abundances before compositing, so one render yields spectra and material maps, and any surface can be 

---

### [171] PhySGA: A Physics-Space Grounded Agentic Framework for Generalizable and Interactive 3D Composition

**链接**: https://arxiv.org/abs/2610.20560
**作者**: Weichen Lyu, Chong Xia, Mingyu Dong, Long Xu, Shengjun Zhang, Yueqi Duan
**来源**: cs.AI cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> 3D object composition is pivotal to digital content creation and robot simulation, while also serving as a critical testbed for physical intelligence in foundation models. Previous methods either leverage large language models to directly predict object coordinates, or utilize generative diffusion priors to synthesize composite images for visual alignment, both of which rely on static priors in digital spaces. However, these methods consistently struggle with complex compositions such as precise hanging, gravity-driven settling and hidden containment, as these tasks require interactive construction processes involving global planning, fine-grained alignment, and physical simulation. To address these challenges, we propose PhySGA, a Physics-Space Grounded Agentic Framework for 3D composition via agent exploration and physical simulation, enabling the universal interactive assembly of rigid, articulated, and deformable objects. Directly applying vanilla LLMs or VLMs to this task proves i

---

### [172] Occupancy Modeling via Drifting: One-Step Generation Enables Direct Policy Extraction

**链接**: https://arxiv.org/abs/2610.19883
**作者**: Robin Uhrich, Marco Bagatella, N\'uria Armengol Urp\'i, Pavel Kolev, Georg Martius
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The growing interest in behavior foundation models, combined with recent advancements in generative modeling, has led to an appealing recipe for reinforcement learning from unlabeled data: pre-train a generative model to model occupancies, i.e., discounted state visitations, on reward-free trajectories, such that a policy can be easily extracted once a small reward-labeled dataset becomes available. We decompose this recipe along three axes: (i) the degree to which the multi-modal structure of occupancies must be captured, (ii) the class of generative model, and (iii) the method used for policy extraction. Along each axis, we consider existing choices, propose simpler alternatives, and validate each decision experimentally. This analysis culminates in a novel, streamlined method that leverages drifting, a modern one-step generative sampler, to model the occupancy. We show that this enables policy extraction via direct differentiation through the occupancy model, and bypasses the need f

---

### [173] Test-Time Forecasting: Recurrent Depth Enables In-Context Dynamics Prediction

**链接**: https://arxiv.org/abs/2610.19552
**作者**: Jeffrey B. Lai, John Quinn, Anthony Bao, William Gilpin
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Foundation models for dynamical systems can forecast unseen partial differential equations (PDEs), ordinary differential equations (ODEs), and time series during inference. However, it remains an open question whether these foundation models truly learn generalizable in-context forecasting strategies. We show that looped transformers are capable of emulating propagators for dynamical systems in-context by first establishing a link between linear attention and (extended) dynamic mode decomposition. We then generalize this insight into the $\textit{Test-Time Forecasting}$ (TTF) framework in which a one-step forecaster leverages iterations of gradient descent as recurrent depth. We demonstrate that lightweight TTF models trained on ODEs and PDEs generalize to out-of-distribution system dynamics during autoregressive rollout after being trained for one-step prediction. Our results reinforce TTF as a theoretically motivated framework for designing recurrent depth models capable of forecasti

---

### [174] OrionMoE-v1.0: A Mixture-of-Experts Foundation Model for Tabular In-Context Learning

**链接**: https://arxiv.org/abs/2610.20418
**作者**: Mohamed Bouadi, Nassim Bouarour, Aditya Tanna and Vinay Kumar Sankarapu
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tabular foundation models enable in-context learning by predicting unseen observations from a labeled support table without task-specific parameter updates. Despite recent advances, most existing approaches rely on dense architectures that apply the same transformations across features and datasets. We introduce OrionMoE-Small, a compact tabular foundation model that combines distribution-aware representations with dataset-conditioned sparse mixture-of-experts computation. Built on a dual-axis Transformer architecture, OrionMoE-Small selectively activates experts along the feature axis, with routing decisions informed by both individual feature representations and the broader dataset context. This design enables adaptive allocation of computation across heterogeneous tabular problems while retaining a shared computational pathway across tasks. OrionMoE-Small is pretrained entirely on synthetic classification tasks generated from a structured causal prior and performs downstream predict

---

### [175] Continual pretraining Prostate MRI ViT Encoder for task alignment

**链接**: https://arxiv.org/abs/2610.20217
**作者**: Bilal A. Sidiqi, Yipei Wang, Shaheer U. Saeed, Shiqi Huang, Daniel C. Alexander, Yipeng Hu
**来源**: cs.CV cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Building foundation models for MRI has emerged as a promising direction for advancing medical image analysis and improving accessibility of task specific models. Existing approaches primarily focus on effective pretraining strategies and evaluating their performance across diverse downstream tasks. While these methods show performance gains, limited attention has been given to understanding task alignment between pretraining and downstream objectives. Unlike language models, where the two stages are naturally aligned, such alignment is less evident in vision based applications. Motivated by this gap, we explore continual pretraining. Specifically, continually pretraining a pretrained ViT encoder using Low-Rank Adaptation (LoRA) on a prostate segmentation task to enhance task alignment and downstream performance. We further perform layer-wise representational analysis using Centered Kernel Alignment (CKA) to assess representational shifts and their correlation with task outcomes. Our ex

---

### [176] Kandinsky S2V 1.0: Audio-Driven Avatar Video Generation

**链接**: https://arxiv.org/abs/2610.19290
**作者**: Nikolay Semenov, Artem Riabinin, Sergey Bassenko, Anna Averchenkova, Julia Agafonova, Anastasia Aliaskina 等 (10 人)
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We present Kandinsky S2V 1.0, an open family of speech-to-video models for controllable audio-driven human animation, comprising Kandinsky S2V 1.0 Lite (2B parameters) and Kandinsky S2V 1.0 Pro (21B parameters). From a single reference image, a speech waveform, and a text prompt, the models generate long-form 25 FPS video in which lip motion, expression, pose, and gesture follow the speech. The architecture draws text and audio conditioning from one Qwen2.5-Omni model and adds a reference-aware three-scale visual memory. Training starts from the Kandinsky 5.0 Video foundation models [1] and combines mixed reference-memory layouts with an area-adaptive face loss. The training corpus contains 1.17M single-speaker clips selected by active-speaker detection, with captions generated directly in English and Russian. A side-by-side human evaluation against the strongest open-source baseline and two proprietary commercial models shows that Kandinsky S2V 1.0 Pro performs comparably to or better

---

### [177] Learning by Examples: Power Grid Steady State Analysis with a Tabular Foundation Model

**链接**: https://arxiv.org/abs/2610.20462
**作者**: Olayiwola Arowolo, Oluwadara Adedeji, Peter Palensky, Jochen L. Cremer
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Foundation models have shown strong generalization across scientific domains, but their use in power systems remains largely task-specific. We investigate whether a pretrained tabular foundation model (TFM), TabPFN, can serve as a general-purpose neural solver for power grid steady-state analysis. We evaluate the TFM on three tasks: power flow (PF) prediction, N-k contingency screening (NCS), and voltage stability margin (VSM) prediction. We performed experiments on 118- and 2000-bus systems, comparing the TFM against task-specific neural baselines. Without retraining or fine-tuning, the TFM matches or outperforms the best task-specific model in several settings across the three tasks. For 118-bus PF prediction, a variant of the TFM achieves errors of $1\times 10^{-3}$ pu for voltage magnitudes and $0.30^\circ$ for voltage angles, outperforming all baselines. On unseen N-1 contingency and close-to-infeasible PF cases, the TFM is competitive with the DCPF approximation. For millions of 

---
