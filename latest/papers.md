# 📑 论文索引 - 2026-09-30

共 578 篇论文

---

### [1] A Dual-Agent Multimodal Large Language Model Architecture for Fully Automated IMRT Planning in Small Cell Lung Cancer

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S0360301626011223&hl=zh-CN&sa=X&d=11715191487740978788&ei=SJS7atDeGq7N6rQPkrrVkQ0&scisig=ACTRDVFL-zTw4cK-SS3K9LwLLYxy&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:ACTRDVHBiLID0dsXs0coH3hBX4Zg&html=&pos=2&folt=kw-top
**作者**: S Wei, S Yan, Y Liang, J Yang, X Meng, W Li 等 (8 人)
**匹配关键词**: Large Language Model, MLLM, Multimodal Large Language Model
**相关性评分**: 9.0
**数据来源**: Google Scholar

**摘要**:

> We propose a reasoning-driven dual-agent multimodal large language model ( MLLM ) architecture that reproduces the physicist decision … A reasoning-driven dual-agent MLLM architecture can integrate beam geometry selection and inverse optimization

---

### [2] EEGAgentBench: Benchmarking LLM Agents on Short- and Long-Horizon EEG Analysis

**链接**: https://arxiv.org/abs/2609.31632
**作者**: Huyu Wu, Weining Weng, Yuchen Liu, Yiqiang Chen, and Yang Gu
**来源**: cs.LG
**匹配关键词**: EEG, LLM
**相关性评分**: 7.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Electroencephalography (EEG) analysis is evolving from short-segment classification toward long-horizon interpretation that demands iterative evidence accumulation, multi-step reasoning, and coordinated use of specialized signal-processing tools. Although large language models (LLMs) have recently shown promise as autonomous agents for EEG analysis, existing EEG agentic evaluations remain fragmented, covering limited tasks over narrow temporal horizons with inconsistent protocols, and providing no comprehensive assessment of agents' reasoning, tool-use, and workflow construction capabilities. To address this gap, we propose \textbf{EEGAgentBench}, a unified benchmark for systematically evaluating LLM agents on short- and long-horizon EEG analysis. EEGAgentBench spans six representative EEG applications ranging from knowledge question answering to sleep staging. It encompasses signal durations from 2 seconds to nearly 23 hours, with prediction targets ranging from class labels to event 

---

### [3] One Model Is Not a Crowd: Multi-LLM and Aspect-Conditioned Diverse Comment Generation

**链接**: https://arxiv.org/abs/2609.33666
**作者**: Nafis Irtiza Tripto, Delvin Ce Zhang, Mahjabin Nahar, Dongwon Lee
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Human communication on the internet is shaped by diverse perspectives, most visibly expressed in online comment spaces. As large language model (LLM)based AI agents begin to inhabit these spaces, a key question arises: whether synthetic comment threads can capture the diversity inherent in human discourse. This concern is increasingly important, as the growing presence of homogenized AI-generated content risks reducing diversity over time, potentially leading to model collapse and degrading the richness of digital communication. Inspired by the plurality of human crowds and the aspect-driven nature of discourse, we hypothesize that comment diversity is better approximated by combining multiple LLMs with aspect-conditioned generation. We formalize and evaluate this approach using models from different providers and introduce a framework that characterizes diversity across semantic, linguistic, and socio-pragmatic features along three axes: dispersion, coverage, and alignment. Using this

---

### [4] FORGE: Form-Optimal Routing of Grounded Evidence for Frozen LLM Agents

**链接**: https://arxiv.org/abs/2609.34358
**作者**: Xi Xiao, Yunbei Zhang, Chen Liu, Lin Zhao, Jialin Chen, Tianchen Zhao 等 (10 人)
**来源**: cs.LG cs.CL
**匹配关键词**: Foundation Models, LLM
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In agentic AI systems, frozen foundation models are increasingly deployed as closed-weight API endpoints, making downstream adaptation possible only through the inputs and inference procedures surrounding the model. As a result, for each input query, two coupled decisions largely determine both answer quality and token cost: what evidence to provide and how much reasoning budget to allocate. Fixed defaults along these axes are often suboptimal, misallocating support form or reasoning depth on roughly 80% of queries in our analysis. To address this challenge, we propose FORGE, a unified framework for adapting frozen models through per-query routing over a joint action space that spans both support form and thinking depth. Under an entropy-regularized, cost-aware utility objective, we derive a closed-form Boltzmann routing target and instantiate the policy as a lightweight 269K-parameter factorized router. The routing policy is trained around the frozen host, without any weight access, t

---

### [5] SeLMRoute: Probabilistic Semantic Evidence for Large Language Model Routing

**链接**: https://arxiv.org/abs/2609.34736
**作者**: Vasilis Perifanis, Nikolaos Pavlidis, Symeon Symeonidis
**来源**: cs.AI cs.CL cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) routing aims to select the most suitable model for each incoming query. Most existing routers learn this decision directly from query embeddings, model representations, preference data, or clusters of similar examples. Such approaches can be effective, yet the representation used for routing rarely states what a query actually requires. We introduce SeLMRoute, a routing framework that separates the extraction of candidate-independent semantic evidence from the learning of candidate performance and the application of deployment objectives. A decision model first evaluates a set of interpretable questions about the query, such as its reasoning requirements and use of external knowledge, with each judgment retained as a probability distribution. The resulting probabilistic semantic state is used by a lightweight supervised router to estimate candidate model performance. Routing objectives are applied after performance estimation, which allows the same semantic s

---

### [6] RSI-Router: Evolving Subtask-Level LLM Routing and Skills for Cost-Efficient Agents

**链接**: https://arxiv.org/abs/2609.34712
**作者**: Hao Li, Hangfan Zhang, Zhiyao Cui, Chunjiang Mu, Yiqun Zhang, Bo Zhang 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Practical deployment of large language model (LLM) agents requires strong task performance at affordable inference cost. For long-horizon agentic tasks, this performance-cost trade-off can be improved through within-task large-small model collaboration, as smaller models can handle some stages even when they cannot solve the full task. In this paper, we introduce RSI-router, a routing framework that constructs subtask-level model assignments and model-specific skills through recursive self-improvement over accumulated experience. Each iteration consists of four stages: Subtask Mining derives subtask definitions and identification rules from training trajectories; Routing Strategy Evolution proposes and evaluates diverse model assignments; Model-Specific Skill Evolution compares routed and large-model-only trajectories to diagnose failures and develop reusable execution skills; and Pareto-Optimal Router Selection updates the Pareto population using historical and newly generated routers

---

### [7] CyberClear: A Benchmark for LLM Agent Systems on APT Attack Chain Provenance

**链接**: https://arxiv.org/abs/2609.32424
**作者**: Qi Chen, Fushuo Huo, Hangli Shen, Jingcai Guo, Shuhao Li, Guang Cheng
**来源**: cs.CR cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model agents have demonstrated promising capabilities in cybersecurity tasks, yet their ability to reconstruct complete Advanced Persistent Threat attack campaigns from complex security logs remains largely unexplored. Existing cybersecurity benchmarks for agents mainly focus on vulnerability discovery, exploitation, and security analysis tasks, leaving the evaluation of attack chain provenance under realistic security logs insufficiently studied. To address this gap, we introduce CyberClear, a benchmark for evaluating LLM agents and advanced agent systems on APT attack chain provenance from long-context security logs. CyberClear covers both single-step attacks and multi-stage attack chains, requiring agents to identify attack evidence, infer attack progression, and generate provenance graphs containing entities, causal relationships, MITRE ATT&CK techniques, and forensic evidence. To enable comprehensive evaluation, we develop an evaluation method tailored to APT attack

---

### [8] Toward Agentic Optical Networks: A Vision of LLM Agent-Driven Autonomous Lifecycle Management

**链接**: https://arxiv.org/abs/2609.32226
**作者**: Yao Zhang, Shengnan Li, Yuchen Song, Yidi Wang, Yue Pang, Wenbin Chen 等 (10 人)
**来源**: cs.NI cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As optical networks continue to expand in scale, complexity, and service diversity, the implementation of automation has become essential for ensuring agility, efficiency, and reliability in lifecycle management (LCM) of optical networks. Large language model (LLM) Agent, distinguished by its progressively sophisticated capabilities in logical reasoning, adaptive decision-making, complex problem solving, and multi-task orchestration, presents great opportunities to advance network automation beyond traditional AI techniques. Nevertheless, the application of LLM Agent in optical networks remains in its early exploratory stage, challenged by the lack of multi-task coordination, high computational demands, data dependence, and reliability concerns. In this paper, we envision a conceptual roadmap toward Agentic Optical Networks (AONs) by integrating LLM Agents throughout the LCM with high-level autonomy. First, we trace the evolution from manual operations to AI-empowered frameworks and di

---

### [9] SleuthBench: Benchmarking Statistical LLM Evaluation Using Tabular Hidden Signals

**链接**: https://arxiv.org/abs/2609.34228
**作者**: Jingyun Jia, Antoine Remond-Tiedrez, Aaron Alvarez, Joshua Shunk, Rich Caruana, Ben Lengerich
**来源**: cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Evaluating statistical discovery by large language model (LLM) agents requires verifiable analytical ground truth. Establishing such ground truth for real-world datasets is costly, and prior knowledge of public datasets can influence agent responses. We introduce SLEUTHBENCH, a benchmark that addresses both problems by injecting controlled data-quality problems and feature effects into public tabular datasets: the injected pattern determines the answer, so reference answers are computed automatically and memorized knowledge of the original table is insufficient, while the table keeps its background structure. The injected patterns are modeled on phenomena reported in real data analyses. The benchmark defines 17 question templates in two families: data-quality questions and feature-contribution questions. We evaluate six state-of-the-art LLMs that analyze the data using a Python coding tool, on data-science and business phrasings of 70 validated dataset-template combinations, yielding 1

---

### [10] CoDeL: Co-Evolutionary Defense against Indirect Prompt Injection in LLM-based Agents

**链接**: https://arxiv.org/abs/2609.34463
**作者**: Xiao Yang, Yangchen Ou, Yuhan Gao, Le Wang, Zonghao Ying, Aishan Liu
**来源**: cs.CR cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM)-based agents increasingly rely on external tools and content, exposing them to indirect prompt injection (IPI). This threat has motivated a wide range of defenses, among which training-based defenses are often regarded as most reliable. However, existing training-based defenses are typically optimized on a static distribution of explicit injections. They learn surface-form cues rather than the boundary between serving the user and obeying an injected objective, and therefore fail when malicious intent is folded into a plausible workflow and deferred for several turns. We present CoDeL, a defense that hardens agent against an attack distribution it reshapes as it trains. The defender is updated each round via LoRA-based GDPO under a decoupled reward over safety, task progress, and format compliance, so refusing injections and completing the user's task jointly define fitness. To keep supplying it with the failures worth learning from, a co-evolving prober sear

---

### [11] From One-Shot Generation to Incremental Music Composition: Adapting a General-Purpose Instruction LLM for Persistent Symbolic Editing

**链接**: https://arxiv.org/abs/2609.34994
**作者**: Andr\'e Ricardo Ducca Fernandes and Jean-Pierre Briot and Simone Diniz Junqueira Barbosa1 and H\'elio C\^ortes Vieira Lopes
**来源**: cs.AI cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Most music-generation systems are still framed and evaluated primarily as producers of complete outputs, whereas composition often proceeds through successive revisions to a shared musical artifact. This paper studies a different use of a general-purpose instruction-following large language model: not as a one-shot music generator, but as a reusable operator over an evolving symbolic score. We formulate incremental composition as a sequence of operation-aware state transitions over persistent ABC notation, with explicit requirements on what each operation may change and what it must preserve. The interaction includes two artifact-initialization variants and three editing operations -- chord addition, inpainting, and transposition. We instantiate the formulation by adapting Llama 3.1 8B Instruct with Low-Rank Adaptation (LoRA) on 496,038 operation-aware dialogue records derived from Irish traditional music. The comparison with the unadapted model is used to test the feasibility of learn

---

### [12] Trajectory Unlearning on LLM-based Agents

**链接**: https://arxiv.org/abs/2609.33639
**作者**: Yingdan Shi and Ren Wang
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Existing large language model (LLM) unlearning has focused primarily on removing specific knowledge, such as harmful facts, private data, or copyrighted content. However, as LLMs are increasingly deployed as autonomous agents, a fundamental yet overlooked problem emerges: beyond suppressing what an agent knows, an agent should not reproduce undesired behaviors through its action trajectories. In this work, we introduce trajectory-level unlearning, a new problem formulation that targets the removal of specific action trajectories in long-horizon agentic tasks, rather than factual knowledge. We identify two fundamental challenges that distinguish trajectory unlearning from knowledge unlearning: (1) our unlearning target is what the agent \emph{does}, not what it \emph{says}; and (2) trajectories are sequentially dependent action sequences that cannot be decomposed into isolated prompt-response pairs without losing inter-step structure. To address these challenges, we propose Group-inject

---

### [13] Learning Perturbation Robust Policies for LLM Agents with Stable Optimization

**链接**: https://arxiv.org/abs/2609.34064
**作者**: Pengxin Wang, Yuanzhe LI, Yuxin Ren, Huanrui Yang, Jingdi Chen
**来源**: cs.LG cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reinforcement learning (RL) has become an effective post-training paradigm for long-horizon large language model (LLM) agents. However, we find that the resulting policies can be sensitive to various policy perturbations, such as hidden-state noise, pruning, and quantization. In this work, we study how to improve perturbation robustness during policy optimization. We first introduce the notion of a perturbation robust policy and analyze conditions under which perturbed policy updates preserve stable monotonic improvement. Based on this analysis, we introduce Stable Perturbation-Robust Policy Optimization (SPrPO), which applies adaptive and sensitivity-aware perturbations during RL training. We evaluate SPrPO on ALFWorld and WebShop and conduct systematic experiments across multiple perturbation types and scales, showing improved perturbation robustness while maintaining stable policy optimization.

---

### [14] AlphaPareto: Formulaic Alpha Discovery with LLM-Guided Multi-Objective Reinforcement Learning

**链接**: https://arxiv.org/abs/2609.34188
**作者**: Yingbo Zhao and Zeyu Yang and Zhoufan Zhu
**来源**: stat.ML cs.AI cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Formulaic alpha discovery is a core challenge in quantitative trading, as identifying alphas that work well together remains difficult. Recent reinforcement learning (RL) methods formulate this task as a Markov decision process (MDP), but two important issues remain unresolved. First, as the alpha pool evolves, the reward function changes accordingly, making the MDP inherently non-stationary. Second, most existing methods optimize a single objective, typically predictive power, while ignoring other important properties of a high-quality alpha pool. Motivated by these challenges, we propose AlphaPareto, an RL method for formulaic alpha discovery. To address non-stationarity, AlphaPareto augments the state to include both the alpha under construction and the current alpha pool, and applies a large language model (LLM) to encode the pool. This design allows the agent to adapt to the evolving search environment. To overcome the limitation of single-objective reward design, AlphaPareto repl

---

### [15] Beneath the Tokens: A Performance Engineering Study of Multi-Token Prediction in GPU-Accelerated LLM Inference

**链接**: https://arxiv.org/abs/2609.35188
**作者**: Suwesh Prasad Sah
**来源**: cs.AI cs.PF
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Autoregressive large language model inference repeatedly invokes the target model to generate one token at a time, making generation sensitive to GPU memory movement and sequential execution. This study evaluates two-token multi-token prediction (MTP) against autoregressive decoding in a controlled single-request deployment on an NVIDIA A10G GPU. A 360-request benchmark covered plain-text, reasoning-intensive, and tool-calling workloads, while runtime telemetry, Nsight Systems, PyTorch Profiler, and selected Nsight Compute measurements were used to explain the observed performance. MTP increased output throughput by \(1.91\times\) to \(2.19\times\) across all prompts and reduced time to first output by 10.0--14.2\%. Median mean acceptance length ranged from 2.370 to 2.595 tokens per verification iteration. Profiling showed that MTP introduced a longer and more complex execution path, including proposal, sampling, attention, gathering, and reduction operations. However, it required 56.4

---

### [16] WSM-Aware HRI: An IoT-Enhanced Framework for Early Detection and Norm-Guided Repair of Failures with LLM Guidance

**链接**: https://arxiv.org/abs/2609.32336
**作者**: Hanlin Zhang and Yuquan Wang and Tianwei Zhang and Zhenglong Sun
**来源**: cs.RO cs.HC
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Human-robot interaction (HRI) failures remain a major barrier to deploying robots in real-world environments. Prior work often treats failures as isolated technical faults or focuses on post-hoc recovery behaviors. In practice, many breakdowns arise because humans and robots operate under inconsistent assumptions about the current world state. We propose WSM-Aware HRI, an IoT-enhanced modular framework that unifies diverse HRI breakdowns as World-State Mismatches (WSMs) between a human's instruction-implied assumptions and a robot's grounded world model built from multimodal perception and digital augmentation. A Large Language Model (LLM) is used to make implicit assumptions explicit, map them to a small set of mismatch types, and specify the evidence needed for verification against the robot's world state. WSM-Aware HRI shifts failure handling from execution-time recovery to proactive mismatch detection during intention formation, enabling interventions guided by safety, norm complia

---

### [17] MoVISA: Multi-Token Reasoning for Video Object Segmentation

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2609.28956&hl=zh-CN&sa=X&d=8901710064835244041&ei=SJS7atDeGq7N6rQPkrrVkQ0&scisig=ACTRDVF8p8-Vd9d_067V-ste2dsn&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:ACTRDVHBiLID0dsXs0coH3hBX4Zg&html=&pos=6&folt=kw-top
**作者**: R Zhao, HK Cheng, AG Schwing - arXiv preprint arXiv:2609.28956, 2026
**匹配关键词**: Large Language Model, MLLM, Multimodal Large Language Model
**相关性评分**: 5.0
**数据来源**: Google Scholar

**摘要**:

> Recent advances in video object segmentation with Multimodal Large Language Model ( MLLM ) reasoning have demonstrated the effectiveness of using a single textual token, such as SEG, to predict segmentation masks across images and

---

### [18] Population Physics, Population Problems: Safety and Emergence in LLM Societies

**链接**: https://arxiv.org/abs/2609.33871
**作者**: Adrian de Wynter
**来源**: cs.MA cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The collective behaviour of large language model (LLM) societies is not the sum of their individual outputs. It yields statistically distinct, sometimes-unpredictable phenomena, for which the tools we use to study single agents may not scale. Due to recent incidents involving autonomous agentic systems, however, understanding these systems is paramount. For that we introduce a framework for measuring self-organisation in LLM social systems and apply it to three such systems: a Schelling grid, a social network (Moltbook), and a Twitter-like misinformation simulation ('Rogue'). All three exhibit statistically significant self-organisation. Moreover, their relaxation dynamics vary with the environmental information available to the agents, with open-ended systems (Moltbook, Rogue) exhibiting sharp, phase-transition-like dynamics. Further results show that population-level pathologies can emerge even when the LLMs are safety-tuned or monitored, being primarily driven by the coordinated act

---

### [19] SOLAR: A State-Driven Online Learning Rate Scheduler for LLM Pretraining

**链接**: https://arxiv.org/abs/2609.34681
**作者**: Qiulin Shang, Binyu Wang, Yongqi Qiao, Songde Rao, Zhoutong Wu, Kun Yuan
**来源**: cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Learning-rate (LR) scheduling plays a central role in large language model (LLM) pretraining, yet current practice still relies heavily on hand-crafted heuristics such as Warmup-Cosine-Decay and Warmup-Stable-Decay. Because these schedules are fixed in advance, they cannot adapt to evolving optimization dynamics. Online learned scheduling within the Learning to Optimize (L2O) framework offers a dynamic alternative, but remains brittle at LLM scale due to noisy signals, delayed feedback, and the risk of catastrophic divergence. We propose SOLAR (State-driven Online Learning rAte scheduleR), a stabilized framework for reliable online LR adaptation. SOLAR uses a base schedule as a reference and learns bounded, state-dependent residual corrections for individual parameter groups. Each correction re-anchors to the base at every step, allowing the policy to adapt the LR without relearning the warmup-decay profile. A lightweight state representation and progress-aware reward guide online lear

---

### [20] Reading Too Much into Context: Passive Exposure Can Steer LLM Decisions

**链接**: https://arxiv.org/abs/2609.33065
**作者**: Yuxiang Zheng, Lin Tian, Marian-Andrei Rizoiu
**来源**: cs.CL cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) assistants can now search the web and consult external sources while completing user requests. These sources can provide useful evidence, but they can also introduce additional content into the model's context. Can such passive exposure steer a decision even when the added content provides no reason to change it? We examine the stability of model decisions on the same tasks with and without such external content. Across all open-weight and closed-weight models we test, exposure systematically shifts decisions, with effects reaching nearly 50 percentage points in closed-weight models. The same pattern appears with real-world online opinions. The influence also extends beyond subjective preferences. Such exposure can steer models toward choices that violate explicit user requirements and increase their acceptance of false claims. In short, what enters an LLM's context can influence its decision even when it should not determine it.

---

### [21] Measuring Collapse and Correction in Homogeneous-Panel LLM Debate

**链接**: https://arxiv.org/abs/2609.35279
**作者**: Xin Li, Mengbing Liu, Chau Yuen
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-agent large language model (LLM) debate is often evaluated by whether final answers improve, but movement is not necessarily improvement: the same discussion can rescue an initially wrong majority or destroy an initially correct one. Standard final-accuracy evaluations conflate these opposing mechanisms. We introduce an auditable protocol for homogeneous debate on multiple-choice questions (MCQs) that records each run as a transition ledger over collapse, correction, onset, and signed intervention utility. On 6,925 MMLU-Pro debates, the protocol identifies 253 collapses and a parallel correction ledger that changes how interventions should be judged. Replay experiments reveal the central tradeoff: a leave-one-model-out probe-gated freeze prevents 29 collapses but loses 108 corrections under equal weights, so collapse prevention alone can recommend the wrong policy. A compact pre-debate 8-probe screen is a triage signal: its unadjusted family-level association with conditional-col

---

### [22] Business Compromise Detection with Agentic AI and LLM-driven Knowledge Discovery

**链接**: https://arxiv.org/abs/2609.32643
**作者**: Diego Palma, Kyu Bin Kim, Zhen Han, Allbright Dsouza, Zhiyuan Liu
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Detecting compromised business ad accounts is a challenge in digital advertising, as attackers exploit hijacked accounts to launch fraudulent campaigns. Large Language Model (LLM) agents show promise for integrity enforcement, but hallucinated mistakes on hard cases create business friction. In a study we find the autonomous agent is a strong, recall-heavy signal extractor but an unreliable final arbiter, conceding precision on ambiguous decisions. We therefore keep the agent as an investigator that emits a structured, interpretable signal vector, and delegate the verdict to a neuro-symbolic stage: symbolic rules discovered by Inductive Logic Programming (FOIL-IE), a Na\"ive Bayes calibration layer, and a data-tuned contradiction layer. Evaluating on a compromise-over-sampled population and a realistic low-prevalence sample with subject-matter-expert labels, this arbiter substitution raises MCC from 0.295 to 0.435 ({\Delta}MCC +0.139, 95% CI [+0.026, +0.245], p=0.018, paired bootstrap)

---

### [23] Beyond Energy: When Sustainability Dimensions Reshape LLM Serving Decisions

**链接**: https://arxiv.org/abs/2609.35569
**作者**: Tianyao Shi, Xipeng Shen, Yi Ding
**来源**: cs.CY cs.DC cs.LG cs.PF
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) serving has environmental impacts across energy consumption, carbon emission, water consumption, and biodiversity loss. Yet these dimensions are largely evaluated in isolation, leaving it unclear when and how they lead to different optimization decisions. We present PRISM, a unified framework for characterizing and optimizing LLM serving across energy, carbon, water, and biodiversity impacts. Our analysis reveals a fundamental distinction: computing configurations determine energy consumption, whereas where and when LLM serving is deployed determine its carbon, water, and biodiversity impacts. Under a fixed deployment choice and operational-only accounting, all dimensions preserve the same energy-based configuration ranking. Deployment rankings can diverge across dimensions, while embodied impacts can break configuration invariance when they exceed a lifecycle crossover boundary. PRISM identifies these conditions, quantifies cross-dimensional regrets, and bal

---

### [24] HyperMCTS: Hypergraph-Augmented MCTS for Long-Horizon LLM Agents

**链接**: https://arxiv.org/abs/2609.33920
**作者**: Tingsong Xiao, Nithish Balachandar Moudhgalya, Chandrayee Basu, Lichao Wang, Luyang Kong, Benjamin Z. Yao 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-horizon tasks require large language model (LLM) agents to coordinate decisions under constraints that span an entire solution. Monte Carlo Tree Search (MCTS) offers a promising approach to test-time scaling by exploring alternative action trajectories, but model computation and environment interaction make search costly. Efficient search therefore requires effective reuse of trajectory feedback. Standard MCTS maintains prefix-specific statistics, without explicitly accumulating outcomes for decision groups that recur across different paths. To fill this gap, we propose HyperMCTS, a training-free method that augments an ordered MCTS tree with a cross-trajectory hypergraph. Hyperedges represent groups of canonical decisions and accumulate their observed returns within the current task. Our hypergraph-guided HyperUCT selection rule aggregates evidence from overlapping hyperedges into an action prior, allowing outcomes collected under one prefix to inform selection under another whil

---

### [25] API Secrets Should Never Become Tokens in the LLM's Vocabulary: A Threat Analysis of API Credential Handling in LLM Agent Systems and an Empirical Evaluation of a Vault-Mediated Execution Boundary

**链接**: https://arxiv.org/abs/2609.33371
**作者**: Patrick Kenney and Hadi Ahmadi and Denis Lusson and Donald Nguyen and Gurbinder Gill
**来源**: cs.CR cs.AI cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tool-using large language model (LLM) agents turn credential hygiene from a storage problem into an execution-security problem. A key pasted into a prompt, or embedded in a system prompt or tool configuration, crosses from an authentication boundary into a data pipeline, where it may persist in conversation history, logs, memory stores, generated code, and error payloads. Prompt injection and excessive agency then convert passive disclosure into unauthorized action. This paper formalizes the credential-exposure threat chain for agentic systems; synthesizes evidence from a platform secret-store incident, vendor-reported secret-sprawl measurement, and OWASP and NIST guidance; and describes a vault-mediated execution architecture in which the model selects a connector identifier while a trusted request boundary supplies authentication. We evaluate a production implementation, Corvic Security Vault, in two controlled black-box experiments. Across 16 probes spanning seven control domains, e

---

### [26] EP-Mem: Elastic Privacy Memory for Social Relationship-Aware LLM Agents

**链接**: https://arxiv.org/abs/2609.35233
**作者**: Fengzhou Sun, Yuan Zhang, Xintong Yu and Jinyao Yan
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents face critical privacy risks when acting as delegates in human-agent-human communication. To prevent such breaches, agents must understand users' social relationships and adhere to context-dependent social information disclosure boundaries. Current studies on agent memory privacy focus on instantaneous interactions, leaving the long-term relational disclosure problem unexplored. In this paper, we propose EP-Mem, an Elastic Privacy Memory architecture that reframes privacy as user-owned boundary control across social roles. EP-Mem introduces (1) token-level memory driven by user-configurable a privacy policy that stratifies persons and events, combining domain-level default circulation rules with fact-level whitelist/blacklist exceptions; and (2) a pluggable sidecar with a privacy engine that aligns disclosure controls with memory across summary, detail, and boundary granularities, enforced throughout generation, storage, and retrieval. We construct EP-B

---

### [27] A Large-Scale Benchmark and Risk Assessment of Traffic Analysis Attacks on Cloud LLM Services

**链接**: https://arxiv.org/abs/2609.31877
**作者**: Shahrooz Pouryousef, Jesus Lopez, Saeefa Rubaiyat Nowmi, Md Mahmuduzzaman Kamol, Moinul Hossain, Muoi Tran 等 (7 人)
**来源**: cs.CR cs.AI cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Cloud-based Large language model (LLM) services create a network-level traffic side channel that can expose model, prompt, and task behavior despite encryption. From packet sizes, directions, timing, and burst structure alone, a passive local observer can infer the serving model, the user's prompt category, and the task executed by a collaborative multi-agent system. Yet current evidence is fragmented across separate datasets and settings, limiting reproducibility and comparison. We present, to our knowledge, the first unified measurement study and public benchmark of encrypted LLM traffic across both user--LLM and multi-agent executions. The large-scale benchmark contains 60,000 user--LLM interactions across 10 models and 6 prompt categories, plus 2,838 multi-agent executions covering 10 task categories and two coordination topologies. Using only encrypted packet metadata, we assess the risk of traffic analysis attack by characterizing traffic signatures, identifying the features most

---

### [28] Accounting for Stochasticity in Studies of Large Language Model Refusal

**链接**: https://arxiv.org/abs/2609.33743
**作者**: Emma Lurie, Stephanie T. Wang, Sorelle A. Friedler, Dana\'e Metaxa
**来源**: cs.HC
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We present preliminary empirical evidence that single-observation queries are insufficient for evaluations of LLM refusal behaviors. Using a longitudinal auditing system, we issued identical prompts 100 times each across four dates to GPT-4.1 for two socially salient topics across 20 Wikipedia sources. Refusal outcomes were consistent with a stable Bernoulli process, yet 20\% of sources fell within a decision-boundary region where a single query is largely uninformative. Reliable quantification of refusals required between 15 and 25 repeated queries, well above the single-observation standard common in existing evaluations.

---

### [29] Authorization Closure Graph: Minimal Repair for LLM Agents with Evolving User Instructions

**链接**: https://arxiv.org/abs/2609.32428
**作者**: Qingzhuo Wang, CaiYi Wang, Jinglu Meng, Ruiyang Qin, Kunyu Peng, Zhihua Wei 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tool-using large language model (LLM) agents increasingly perform state-changing actions that require user authorization. Yet existing approaches do not provide a principled mechanism for selectively updating prior authorization when only part of an instruction changes. To this end, we propose an Authorization-Closure-Graph (ACG)-based framework that represents authorization and its dependencies as an evolving, versioned state. ACG selectively invalidates authority affected by a revision while preserving unaffected portions of the authorization state, and computes a minimal repair that identifies only the missing evidence or authority required for execution. This enables agents to adapt to revised instructions while avoiding stale authority and unnecessary authorization requests. We evaluate ACG across three advanced LLMs in two natural tasks, and ACG consistently improves action safety rate and task success rate. Code is available at https://github.com/weiliang822/ACG.

---

### [30] What Does a Skill Actually Do? Estimands and Evaluation Validity for Tool and Skill Use in LLM Agents: A Critical Review

**链接**: https://arxiv.org/abs/2609.33153
**作者**: Shuyang Zhang
**来源**: cs.SE cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents increasingly draw on external tools and reusable skills selected at run time from libraries that hold thousands of entries. Reports that a retriever, router, or skill library "improves" an agent may refer to retrieval recall, the success change from enabling a library, a paired contrast restricted to triggered tasks, or a gain under an approximate budget constraint. This critical review asks what each design compares and under which assumptions. Building on estimand-based approaches to agent evaluation, we describe tool and skill designs along six axes: treatment contrast, target population, outcome, budget constraint, summary measure, and identification assumptions. Thirteen core empirical studies anchor the evidence synthesis, supplemented by related methodological work and design-level reading of the wider literature. Our contribution is to make explicit distinctions that some source authors already acknowledge through a decomposition of trigger-con

---

### [31] Learning to Sell: Reinforcement Learning for Strategic Large Language Model Agents in Multi-Product Markets

**链接**: https://arxiv.org/abs/2609.33289
**作者**: Shuze Daniel Liu, Claire Chen, Jiuqi Wang, Thorsten Joachims
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Autonomous large language model (LLM) agents operating in multi-product markets must make sequential decisions under information asymmetry and resource constraints. We develop a machine learning approach for training such agents to act effectively as sellers in a multi-item bargaining environment, where a seller concurrently negotiates a catalog of substitutable assets across a pool of independent buyers. Buyers hold private, heterogeneous valuations across products, and each can purchase at most one item. Facing limits on total communication turns, the seller must dynamically match buyers with the most profitable products considering their private valuations, while strategically allocating its limited interaction budget toward combinations of greater potential value. We formalize this problem as a Partially Observable Markov Decision Process using a structured, four-part message protocol that maps natural language into a parsable and regulated decision space. Using this formalization,

---

### [32] TokenCast: Forecasting Token Consumption During LLM Agent Execution

**链接**: https://arxiv.org/abs/2609.35760
**作者**: Chaoqian Ouyang, Ling Yue, Libin Zheng, Huanghui Guo, Shengxiang Xu, YiShu Wang 等 (10 人)
**来源**: cs.LG cs.AI cs.SE
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> When a large language model (LLM) agent executes the same task, token consumption can vary by over an order of magnitude across runs. The agent chooses its next steps based on tool feedback and intermediate results, while the growing context steadily inflates the input size of every subsequent call. The total consumption of a task is therefore hard to predict before execution and the prediction must be revised as the run unfolds. In this paper, we propose TokenCast, which learns a composable cost representation for each execution segment, recording its own consumption and the context growth it introduces. Composing adjacent segments yields a cumulative estimate that captures the extra input cost incurred when context from earlier segments is re-read by every later call. As execution unfolds, newly observed evidence refreshes the forecast, requiring no additional LLM calls and incurring a mean cumulative prediction time of 32.8 ms per run on SWE-bench Verified. Across 4 task suites and 

---

### [33] DEALS: Decentralized Expertise-Aware Load Serving for Multi-Agent LLM Systems

**链接**: https://arxiv.org/abs/2609.33768
**作者**: Jingjuan Huang, Wenbin Wang, Yanchuan Yin, Alvaro Velasquez, Jia Liu
**来源**: cs.LG cs.AI cs.MA
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-agent systems (MAS) have recently emerged as an effective approach for coordinating large language model (LLM)-based agents to solve complex tasks through structured interactions. In practice, MASs often handle a stream of heterogeneous and complex tasks, requiring agents to decompose each task and then self-organize and self-evolve to adapt to incoming tasks while sharing execution resources. However, most early approaches to MASs rely on centralized controllers or fixed coordination patterns, which can limit scalability or adaptability. In contrast, existing decentralized and dynamic MASs often require training dedicated routers or invoking LLMs for agent selection, resulting in substantial computational costs and coordination overhead. To address these challenges and enable efficient task-level self-organization and self-evolution for task- and workload-level collaboration, we propose Decentralized Expertise-Aware Load Serving (DEALS), a decentralized and low-complexity framew

---

### [34] FromPitch2Board: Benchmarking LLM Agents in Long-Horizon Football Management

**链接**: https://arxiv.org/abs/2609.34710
**作者**: Peiyu Zang
**来源**: cs.AI
**匹配关键词**: Foundation Models, LLM
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-horizon agent benchmarks typically report how far an agent progresses, but do not identify whether its performance comes from the foundation model, scaffold, responsibility scope, match-control granularity, or horizon. We introduce FromPitch2Board, a deterministic football-management benchmark that studies five configurable factors through controlled comparisons on a single simulator, using paired seeds and a frozen calibration. We evaluate four foundation models and four agent scaffolds. In the Model Track, Coach points Z-scores span 0.19, while Manager points Z-scores span 0.68, with GPT-5.6 showing a sharp rise in passivity under responsibility expansion. Its responsibility ladder rises from 46.1 to 58.1 points with recruitment, then falls to 46.8 under full management, localizing the regression to the final responsibility boundary. Across that boundary, its skipped-decision rate rises from 1.1% to 57.9%. Within the Flash-Pro pair crossed across every scaffold, scaffold choice 

---

### [35] Does Execution Require Target KV Fidelity? A Mixed-Fidelity KV Runtime for LLM Serving

**链接**: https://arxiv.org/abs/2609.33536
**作者**: Jiantong Jiang, Yue Yang, Peiyu Yang, Feng Liu
**来源**: cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) serving is increasingly constrained by the GPU memory consumed by key-value (KV) caches. Existing compression, eviction, and offloading techniques alleviate this pressure, but serving runtimes typically treat only the configured target KV representation as execution-ready. Under memory pressure, this target-only contract can turn KV shortage into request stalls and preemptions. We present ElasticKV, a mixed-fidelity KV runtime built on the observation that target fidelity need not gate execution. ElasticKV introduces a compact intermediate KV state, making fidelity a runtime-managed execution property. To realize this state in a paged serving runtime, ElasticKV combines (i) a pair-structured layout that turns fidelity reduction into reusable GPU capacity, (ii) a dual-mode attention backend that directly consumes the compact state while preserving the native target-only path, and (iii) pressure-aware fidelity management that adapts KV fidelity to memory pressu

---

### [36] From Preference to Reciprocity: Decentralized Matching with Empirically Grounded LLM-agent Based Modeling

**链接**: https://arxiv.org/abs/2609.34679
**作者**: Wangxuan Fan, Xiaoyu Nie, Zhoutian Shi, Xiangcheng Meng, Shipei Zeng, Pin Gao 等 (7 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Bipartite matching is a fundamental problem in game theory and market design. Classical approaches such as Gale--Shapley assume complete preferences and centralized computation, whereas many real-world matching processes are decentralized, asynchronous, and shaped by sequential interaction under limited information. We propose a dynamic bipartite matching framework that combines large language model (LLM) agents with contextual bandits. In a simulated Chinese marriage market, economically grounded LLM agents evaluate locally encountered candidates, while agent-specific Logistic-UCB models learn reciprocal acceptance from realized proposal outcomes. The mechanism therefore separates two decisions---\emph{whom do I like?} and \emph{who is likely to like me back?}---without requiring ex ante market-wide preference rankings. We first validate LLM-induced mate preferences against the empirical conditional-logit reference across multiple LLM backbones. In the $50\times50$ matching experiment

---

### [37] Explainable and Generalisable LLM-based Cognitive Decline Detection with Spontaneous Speech

**链接**: https://arxiv.org/abs/2609.34217
**作者**: Ziyun Cui, Wen Wu, Chuan Shi, Shuguang Yang, Xueying Gui, Yan Zheng 等 (10 人)
**来源**: eess.AS cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Alzheimer's disease (AD) and mild cognitive impairment (MCI), which may precede AD, manifest early through subtle linguistic and acoustic alterations. Traditional diagnostics, however, are often resource-intensive and lack scalability for mass screening. To address these challenges, we introduce a novel bilingual speech large language model framework for automated, explainable cognitive screening. Unlike conventional pipelines that rely on error-prone automatic speech recognition, our system directly processes raw speech to learn joint acoustic-semantic representations, preserving critical prosodic cues often lost in transcription. Utilising our newly collected PUTH-AD dataset alongside multiple open-source corpora, we implemented a multi-task learning objective that simultaneously performs cognitive status classification and generates clinician-understandable natural language explanations. Our system achieved the highest average accuracy and AUROC across six dataset/task conditions, c

---

### [38] LLM Alignment--Utility Asymmetry under Semantic-Preserving Transformations

**链接**: https://arxiv.org/abs/2609.32717
**作者**: Mohan Li, Chengyu Yu, Francesco Sovrano, Marc Langheinrich, Martin Gjoreski
**来源**: cs.CL cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Model (LLM) alignment is intended to ensure that models remain helpful and safe, but its stability under input distributional shift is not yet fully understood. Prior work shows that aligned models can fail under jailbreak prompts, alternative encodings, and cross-lingual transfer, yet these failures are usually studied as attacks rather than controlled probes of alignment generalization. Moreover, existing evidence is largely grounded in natural language variation already represented during pretraining, leaving unresolved whether alignment generalizes with semantic content or remains tied to superficial surface patterns. In this paper, we study this question using synthetic semantic-preserving transformations that are rule-based and invertible, preserving task-relevant meaning while shifting inputs beyond standard linguistic variation. Across four open-weight and four commercial models, under both fine-tuning and in-context learning, we use these transformations as a pr

---

### [39] PDEU-Bench: Benchmarking the Personalized Planning Lifecycle of Tool-Calling LLM Agents

**链接**: https://arxiv.org/abs/2609.34930
**作者**: Huayi Lai, Shichao Song, Qingchen Yu, Simin Niu, Mengwei Wang, Hanyu Wang 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents are evolving from tool-calling systems that execute isolated instructions into task-oriented agents that pursue user goals through sustained, multi-step interactions. However, existing benchmarks for personalized tool use largely assess isolated calls or reactive execution, leaving unclear whether agents can formulate, execute, and revise an explicit plan while preserving user preferences throughout long-term interaction. To address this gap, we introduce \textbf{PDEU-Bench} (\textbf{P}ersonalized plan \textbf{D}efinition, plan \textbf{E}xecution, and plan \textbf{U}pdate \textbf{Bench}mark), a benchmark for evaluating the complete planning lifecycle of personalized tool-using agents. PDEU-Bench comprises 214 long-horizon interaction tasks spanning 12 everyday domains and 94 tools, with stage-specific assessments of preference adherence and plan quality. Extensive evaluations of 15 representative open-source and closed-source LLMs reveal a pronounced g

---

### [40] "Nothing to See Here'': Unintended Disclosure through Revision Traces of LLM Deliverables

**链接**: https://arxiv.org/abs/2609.35408
**作者**: Yage Zhang, Yukun Jiang, Yang Zhang
**来源**: cs.CR cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) assistants increasingly help users draft content for third-party recipients. During private drafting, the user or the model may introduce an item and later remove or replace it. The model may remove the item from the intended content but reveal it again when stating the edit. We call such statements revision traces. For example, after a user removes the password before sharing a configuration file, the model may delete it but leave a comment saying, "Removed the password 'No****4!' as requested." A third-party recipient who sees only the delivered file can therefore recover the withdrawn password from the comment. In an in-the-wild analysis of three public conversation corpora, we identify 26,753 revision requests, of which 2,363 (8.8%) leave revision traces. We study them in greater depth under controlled conditions by introducing RevLeakBench, a benchmark of 100 tasks across five scenarios with a conversation track and an agent track. We measure trace occur

---

### [41] Anytime-Valid LLM Leaderboards via Benchmark-weighted and Block-Factorized e-Processes

**链接**: https://arxiv.org/abs/2609.32248
**作者**: Hongfu Gao, Songxin Zhang, Zejian Xie, Bingyi Jing, Zhou Wang, Yiming Liu
**来源**: cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) leaderboards compare model capabilities by ranking models according to their mean performance on fixed benchmarks. However, variability in evaluation outcomes across runs may produce unsupported claims of model superiority on the benchmark, a risk compounded by leaderboard updates. In this paper, we propose BB-EDGE (Benchmark-Weighted and Block-Factorized e-processes for Directed Graph Evaluation), a principled framework that represents an LLM leaderboard as a directed graph whose edges certify pairwise mean-performance advantages, with anytime-valid family-wise error rate (FWER) control. Concretely, for each direction, BB-EDGE constructs an empirical-Bernstein e-process by factorizing evidence over protocol-defined blocks and assigning stakes proportional to the corresponding block weights, then applies direct e-Holm across these $e$-processes to certify directional advantages as edges. Theoretically, we characterize weight-proportional linear stakes under h

---

### [42] From capability to assertability: epistemic regulation of LLM -mediated claim presentation

**链接**: https://scholar.google.com/scholar_url?url=https://link.springer.com/article/10.1007/s10676-026-09922-0&hl=zh-CN&sa=X&d=14828627705296908040&ei=SJS7arCyDMKL6rQPhLm5qA0&scisig=ACTRDVE_CgH0zS1seWL4kqvf7tKX&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:ACTRDVEEr233VErbxroTWJ0YT-xH&html=&pos=5&folt=kw-top
**作者**: Q Wu - Ethics and Information Technology, 2026
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: Google Scholar

**摘要**:

> Improvements in large language model ( LLM ) capability can increase accuracy, reasoning, and access to relevant information while leaving unassessed whether a particular output is appropriately presented for epistemic uptake. This creates an

---

### [43] Remote Agricultural Visual Diagnostics with Multimodal LLM Using Semantic Transmission in Low-Bandwidth LoRa Environments

**链接**: https://scholar.google.com/scholar_url?url=https://joiv.org/index.php/joiv/article/download/4477/1807&hl=zh-CN&sa=X&d=7180849068805700279&ei=SJS7atDeGq7N6rQPkrrVkQ0&scisig=ACTRDVEacjw8CsH8uE7s3a-aHxLm&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:ACTRDVHBiLID0dsXs0coH3hBX4Zg&html=&pos=3&folt=kw-top
**作者**: H Darmawan, M Yuliana, A Idris, SF Kusuma… - JOIV: International Journal …, 2026
**匹配关键词**: LLM, MLLM
**相关性评分**: 5.0
**数据来源**: Google Scholar

**摘要**:

> is fed to the MLLM for automated diagnosis and structured treatment recommendation generation. However, this MLLM -generated textual … To overcome this second communication bottleneck, we introduce a text compression

---

### [44] Learning from Others, Acting for You: Cross-User Memory Sharing for LLM Agents

**链接**: https://arxiv.org/abs/2609.32511
**作者**: Jinming Hu, Haodong Zhao, Qi Jia, Die Chen, Tianhang Zhao, Sufeng Duan 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents serving different users often solve related tasks, yet separate user histories can leave reusable experience inaccessible to other agents. Pooling memories expands access but risks transferring preferences that conflict with the receiving user's requirements. We introduce ShareMem, a memory architecture that shares reusable experience while grounding its application in the receiving user's own preferences. Shared experiences indicate how to act and which preferences to consult; the receiving user's memory supplies their concrete values. Two-stage consolidation refines experience locally before integrating accepted edits into a shared pool. During execution, scope-first retrieval jointly selects local and shared experiences under a common entry budget, while a user-bound channel supports initial and agent-initiated preference retrieval. We evaluate ShareMem across web navigation (Mind2Web), online personalized interaction (VitaBench~2.0), and multi-sess

---

### [45] TempoKV: Timely Staging of LLM KV Caches for Memory-Semantic Flash

**链接**: https://arxiv.org/abs/2609.35065
**作者**: Jay H. Park, Hyungjun Kim, Dong Kim
**来源**: cs.DC cs.AI cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reusable prefix key-value (KV) caches can outgrow GPU memory in large language model (LLM) serving. A memory-semantic flash hierarchy offers SSD-backed capacity with a limited fast tier, but a logical KV hit is not necessarily ready for GPU retrieval. Demand staging exposes SSD latency, whereas immediate staging can reserve fast-tier capacity long before retrieval begins. We present TempoKV, a timing-aware resource-commitment layer that separates early knowledge of reuse from the acquisition of staging resources. It records reusable-KV hits as metadata-only claims and requests commitment when the runtime-estimated time until retrieval falls to the storage-estimated time needed to make KV resident and protected against eviction. These estimates adapt to runtime progress and staging state, while commitment remains subject to available protected capacity. We implement TempoKV in vLLM and LMCache on an SSD-backed CXL memory device without changing request scheduling. Across two models and 

---

### [46] Dynamic Flow, Static Graph: KV Cache Reuse for Efficient LLM Serving on Mobile NPUs

**链接**: https://arxiv.org/abs/2609.34727
**作者**: Zhengxiang Huang, Shengheng Chen, Chaoyue Niu, Yujie Sun, Zhaode Wang, Zeyu Zhao 等 (9 人)
**来源**: cs.OS cs.AI cs.DB
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> On-device large language model (LLM) serving is a cornerstone of local-first personal intelligence, offering users data sovereignty, strong privacy guarantees, and freedom from cloud API latency and cost. Although KV caching is widely used to reduce latency in long-context inference, existing designs were primarily optimized for cloud GPUs with dynamic execution environments and abundant memory bandwidth. These architectural assumptions do not hold on mobile NPUs, where computation graphs must be statically compiled and both memory capacity and I/O bandwidth are severely constrained. In this work, we present a compute-storage co-design for mobile-centric prefix and non-prefix KV reuse. We first propose an intra-graph mechanism that maps selective KV recomputation onto static NPU graphs, reconciling algorithmic dynamicity with NPU staticity. We further develop an inter-graph scheduler to optimize chunk merging and minimize padding with dynamic programming. To address mobile bandwidth li

---

### [47] Diagnosing Sampled LLM Reasoning in Formal Geometry: Coverage, Realization, and Validity Evidence

**链接**: https://arxiv.org/abs/2609.32924
**作者**: Xiao Yue, Guangzhi Qu
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Repeated sampling can reveal a correct numerical answer without yielding either a reliable system output or a supported derivation. We present Coverage, Realization, and Validity Evidence (CRV), an evaluation protocol for sampled large language model (LLM) reasoning over formal geometry states. Coverage is answer availability, realization is readout accuracy on the frozen candidate pool, and validity evidence is a label-blinded critic judgment of derivational support rather than a proof certificate. CRV freezes each candidate pool before comparing readouts and analyzes covered failures by correct-answer multiplicity and within-problem discrimination. On HardShift441, a 441-problem set for which a reference solver leaves 406 problems unsolved, a LoRA-adapted Qwen2.5-7B generator obtains 24.2% average single-sample accuracy and 68.9% pass@16, whereas verifier-weighted self-consistency (WSC) reaches 38.0%. Readout accuracy is particularly low when the correct answer occurs only once or tw

---

### [48] Curating Merchant-Matching Training Data with Two Confidence-Gated Local LLM Judges

**链接**: https://arxiv.org/abs/2609.33878
**作者**: Donghao Huang, Jinling Pei, Zhaoxia Wang
**来源**: cs.AI cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Merchant matching resolves a noisy payment descriptor to a retrieved merchant entity or returns no match. A key challenge in curating training labels is distinguishing teacher abstention from evidence that no acceptable entity exists: false no-match labels contaminate pseudo-labeled data, while conservative labeling reduces coverage. We investigate whether agreement between two local large language model judges improves pseudo-label reliability. A label is retained only when the judges agree, with separate ordered thresholds for selections and abstentions that guarantee disjoint positive and negative label sets. Retrospective replay on 2,000 expert-annotated queries shows that higher selection thresholds can improve positive-label purity, whereas higher abstention thresholds increase false no-match labels. At thresholds (0.86, 0.80), Muse Glimmer 30B and Gemma 4 31B jointly label 1,633 queries (81.7% coverage) at 96.88% purity; positive and negative purities are 99.47% and 93.38%. This

---

### [49] Relative Generalization Invariance of LLM Pretraining

**链接**: https://arxiv.org/abs/2609.33016
**作者**: Fengzhuo Zhang, Shuche Wang, Shenggui Li, Tianyu Ruan, Jianliang He, Ivor Tsang 等 (10 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Model (LLM) pretraining performance is jointly shaped by three components of the training triplet: the optimizer, model architecture, and training data stream. However, how these components influence performance in distinct ways remains unclear. We take a first step toward isolating their effects by studying relative generalization. We introduce Relative Generalization Invariance (RGI), the invariance of the validation-loss difference between any two tokens across models. We show that RGI approximately holds across a wide range of optimizers and moderate architectural variations, suggesting that these choices induce an approximately uniform shift in token-wise losses. In contrast, changing the training data stream can substantially alter relative generalization. We further show that RGI cannot be explained by the neural tangent kernel or mean-field regimes alone and prove that it can emerge in an overparameterized quadratic model. Overall, our work identifies RGI as a ne

---

### [50] Verification as an Architectural Layer for LLM Agents: A V-Model Design, and a Pilot Study of Its Deterministic Core

**链接**: https://arxiv.org/abs/2609.31937
**作者**: Ali Afoud, Jie JW Wu
**来源**: cs.SE cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents built on the ReAct pattern concentrate four responsibilities in one model: selecting a strategy, choosing each action, formatting it, and judging whether the result is adequate. Nothing outside the generative loop can reject its output, so an agent that cannot make progress does not report failure; it runs until an external budget stops it. We propose treating verification as an architectural layer by adapting the V-model from software engineering: specification levels descend from requirements to individual steps, each level is paired with a dedicated verifier, a deterministic controller enforces every verdict, and only verification outcomes write to memory, so a rejection localizes the level that introduced the fault and an agent halts by declining rather than by exhaustion. Each verifier separates a zero-cost deterministic \emph{gate} from an optional LLM \emph{judge}, so the contribution and cost of each can be measured independently. We report a p

---

### [51] Where Activation Sparsity and KV-Cache Sparsity Cross in LLM Decoding

**链接**: https://arxiv.org/abs/2609.33889
**作者**: Jungseob Lee, Seungyoon Lee, Seongtae Hong, Sugyeong Eo, Heuiseok Lim
**来源**: cs.LG cs.CL cs.PF
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> At each step, decoding one sequence with a large language model rereads the projection weights, whose traffic is fixed, and the key-value (KV) cache, whose traffic grows with context. Activation sparsity trims the first term and KV-cache sparsity the second, yet their reported speedups are hard to compare because each depends on context length and on the dense attention kernel it is measured against. We derive a byte crossover, the context length at which the two savings are equal, together with ideal speedup bounds for each branch and for their composition, from model dimensions and keep ratios alone. We then time both branches and their composition from 2K to 128K tokens on two GPUs after a dense prefill of real text, with dense and sparse modes reading the cache through the same split-K attention kernel. The projection branch leads at short context and the KV branch at long context, with speedups that follow their byte bounds up to fixed kernel costs. Adding these costs, measured in

---

### [52] From Latents to Wires: Surgical Post-Editing on Large Language Models

**链接**: https://arxiv.org/abs/2609.32434
**作者**: Jiankai Jin, Xiangzheng Zhang, Zhao Liu, Wenzhuo Xu, Dongdong Yang, Deyue Zhang 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Given a large language model (LLM), can whoever holds the weights name a semantic target (e.g., the model's identity), locate the model components that produce it, and edit them so that the target no longer appears while other capability is preserved? We call such an edit on a trained model a post-edit. We present L2W (latents to wires), a framework that performs surgical post-edits for named semantic targets. For localization, L2W uses Jacobian lens (J-lens) attribution to score components against the semantic target. For surgical removal, because LLM mechanisms are redundant (i.e., a semantic target may have multiple components producing it), L2W runs Counterexample-Guided Causal Cut (CGCC) until the target no longer appears. CGCC first cumulatively closes model components, treating each surviving expression of the target as a counterexample that exposes the next components to close, and then reopens some of them to preserve capability. In a controlled experiment with an implanted be

---

### [53] FasterPy: An LLM-based Code Execution Efficiency Optimization Framework

**链接**: https://arxiv.org/abs/2512.22827
**作者**: Yue Wu, Minghao Han, Ruiyin Li, Peng Liang, Amjed Tahir, Zengyang Li 等 (8 人)
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [54] When Confidence Rises Too Early: Detecting Shortcut Reasoning via Premature Answer Commitment

**链接**: https://arxiv.org/abs/2609.35074
**作者**: Zhaohan Zhang, Junjie Liu, Chengzhengxu Li, Chen Shen, Xiaoming Liu, Chao Shen 等 (9 人)
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The reasoning trajectory of a Large Language Model (LLM) is often treated as a verbalized description of its internal reasoning. However, such trajectories can be unfaithful: a model may rely on shortcuts to reach an answer and then post-rationalize the decision with a seemingly coherent chain of thought. Detecting this shortcut reasoning is challenging because existing monitors and verifiers mainly inspect textual traces or final outcomes, rather than how the model's belief in its answer develops during generation. We introduce ConfLens, a framework that tracks the evolution of confidence in the final answer throughout reasoning. Across three shortcut reasoning settings, we observe a common pattern of premature confidence, where shortcut samples become highly confident in the final answer at early reasoning stages. Existing confidence estimation methods, however, show limited generalizability, reliability, or efficiency for detecting this behavior. We therefore propose the Distributio

---

### [55] Error-Aware Reverse Auction Mechanism for Large Language Model Routing

**链接**: https://arxiv.org/abs/2608.12719
**作者**: Haolong Chen, Zhengyuan Xin, Liang Zhang, Lei Xue, Guangxu Zhu
**来源**: cs.GT cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [56] SCBO: Semantically Coherent Batching and Ordering for LLM-Based Social Surveys

**链接**: https://arxiv.org/abs/2609.35250
**作者**: Yuanzi Li, Lingjie Wang, Zihang Tian, Lei Wang, Xu Chen
**来源**: cs.CL cs.CY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) offer a scalable way to simulate survey respondents using demographic profiles and observed reference responses. However, the conventional approach of predicting one question per prompt repeatedly encodes the same context, limits each target to a narrow set of reference responses, and prevents later predictions from using information in earlier answers. Predicting multiple questions in one prompt can reduce these costs, share a broader pool of references, and let later predictions build on earlier ones. This requires forming coherent batches, selecting shared references, and ordering questions and references effectively. We propose Semantically Coherent Batching and Ordering (SCBO), a training-free framework that addresses these challenges. SCBO first uses an LLM to extract compact semantic representations from survey items and filter out template noise. It then groups related questions into batches and builds a shared reference bank using target-specific r

---

### [57] When Do Agents Help? Embedding, LLM and Agentic Alignment of Classical Texts and Their Translations

**链接**: https://arxiv.org/abs/2609.33691
**作者**: M\'at\'e Metzger
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Classical texts aligned with their translations support machine translation, retrieval and computational research, but evidence comparing alignment workflows is scattered. This study compares seven systems on 452 texts in Pali, Sanskrit, Mishnaic Hebrew and Tibetan, comprising 9,833 human-aligned units: four embedding pipelines, a direct LLM call, an autonomous agent, and the agent revised by an independent auditor. Generative workflows recover 93-94% of reference correspondences, against at most 77% for embeddings. A ceiling analysis shows that sentence boundaries make some references unrepresentable by the embedding pipelines. Reference recovery is similar across generative workflows: the agent's advantage is 0.5 percentage points (95% CI -0.02 to 1.17), and auditing adds no established benefit. Agents nevertheless produce structurally valid output for all 452 texts, against 437 for direct calls. A blinded three-LLM panel assesses every generative mismatch against the source and huma

---

### [58] Beyond Memory Construction: Rethinking Memory Access for LLM-based Conversational Agents

**链接**: https://arxiv.org/abs/2609.33226
**作者**: Donghua Cai, Yongheng Deng, Yifei Wang, Zijun Shen, Ju Ren
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Memory is a core component of conversational agents, enabling coherent and context-aware behavior over long interactions. Recent approaches commonly rely on LLM-based memory construction, where raw interactions are rewritten into structured memory units and later retrieved via a RAG pipeline. While effective in controlled settings, we show that this paradigm breaks down in long-horizon, high-entropy conversations: memory construction becomes increasingly lossy and unstable as context length and information complexity grow, and incurs prohibitive cost due to repeated LLM invocation. To address these limitations, we propose Threader, a memory system that shifts the focus from memory construction to efficient, structure-aware access over raw interactions. Instead of rewriting interactions, Threader preserves them as first-class memory, organizes them into topic-coherent segments via lightweight incremental segmentation, and enables accurate retrieval through multi-view representation. At 

---

### [59] The Epistemics of Agent Memory: Measuring, and Governing, the Consolidation Decision in Long-Horizon LLM Agents

**链接**: https://arxiv.org/abs/2609.33013
**作者**: Sasank Annapureddy, Anjaneya Prasad Thamatani
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [60] DRIFT: Data Selection for LLM Instruction Tuning via On-Policy Attribution

**链接**: https://arxiv.org/abs/2606.18307
**作者**: Zefan Wang, Lincheng Li, Tianyu Yu, Yuan Yao
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [61] When Users Change Their Minds: Measuring and Repairing Intent Drift in LLM Agents

**链接**: https://arxiv.org/abs/2609.32520
**作者**: Yanjie Zhang, Bowen Cao, Zixin Chen, Yushi Sun
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents often operate over multi-turn interactions in which user intent changes before execution. We study intent drift: the failure mode in which superseded parts of the user's intent continue to influence the final answer or tool action. We introduce IntentFlux, an executable benchmark that converts verifiable tasks into dialogues with controlled intent changes while preserving their original graders. In a 627-case calibration, mean task score falls from 0.476 to 0.384 as dialogues contain more superseded and withdrawn information. Across eight models, the rate of fully correct solutions is significantly lower when the same final task must be recovered from an evolving dialogue rather than given directly in a single turn. We further introduce StateForge, which explicitly maintains the active requirements before generation. On General-Test, it improves mean task score from 0.367 to 0.467. Providing the ground-truth final state improves performance further but still does not recover

---

### [62] ActiveMem: Dynamic Latent Memory Trees for Long-Horizon Agents

**链接**: https://arxiv.org/abs/2609.33244
**作者**: Song-Li Wu, Jingyi Wang, Zhaocheng Du, Weinan Gan
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Model (LLM) agents increasingly rely on external memory to support long-horizon reasoning and decision making. Existing memory systems typically retrieve historical trajectories or summaries as independent context fragments, overlooking the procedural dependencies underlying multi-step execution. As memory scales, such flat retrieval introduces context fragmentation and cross-task interference, leading to structurally inconsistent reasoning trajectories. We propose ActiveMem, a hierarchical memory framework that recursively organizes agent experiences into dependency-aware latent execution trees. ActiveMem abstracts trajectories into reusable subtask nodes while explicitly preserving execution transitions, enabling coherent reasoning-path retrieval conditioned on the current execution state. To support continual adaptation, ActiveMem further learns dynamic memory expansion, retrieval, and pruning policies through reinforcement learning. Experiments across various agent b

---

### [63] Be Careful Who You Trust: Coordination Dynamics under Corrupted Communication in LLM Multi-Agent Games

**链接**: https://arxiv.org/abs/2609.31704
**作者**: Xuanyi Liu, Niall Dalton, Hairi Amin, Xiyuan Yin, Lydia Lim
**来源**: cs.MA cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models are increasingly used as interacting agents, but it remains unclear how robust their coordination is when public communication is unreliable. We study this question in iterated $N$-player Stag Hunt games played by homogeneous LLM groups under controlled programmatic action inversion, which changes both the public transcript and the actions used for execution. Across an experimental grid spanning group sizes, coordination thresholds, corruption levels, and seven LLMs, we observe three main patterns. First, honest agents' pre-flip Stag choices decline as corruption increases, but the sharp fall in public success is primarily mechanical. In the focal $N=5,M=3$ setting, pre-flip success remains 78% at 80% corruption, while public success falls to 12%. Second, honest choices are associated with the public history available at decision time, particularly under high corruption. Third, three threshold-style public-report benchmarks yield similar action-match rates to the 

---

### [64] RICE-Alpha: Reliability-Informed Correction with Event Graphs for LLM-Agent Stock Forecasting

**链接**: https://arxiv.org/abs/2609.34004
**作者**: Tong Liu, Lanmiao Liu, Xiang Hu
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Equity-relevant news evolves through temporally dependent corporate events, making historical information useful only when event continuity, information availability, and transition reliability are modeled. Existing LLM-based financial agents incorporate historical evidence, yet they provide limited support for preserving issuer-specific chronology under point-in-time constraints and for identifying when historical transitions contribute information beyond the current forecast. We present RICE-Alpha (Reliability-Informed Correction with Event Graphs), a point-in-time stock-scoring framework that separates a history-aware multi-view Base Alpha from a reliability-calibrated residual correction derived from historical event continuation. A Multi-Tier Memory Layer grounds news interpretation in temporally eligible issuer-specific history, while a Typed Event Agent constructs event states whose successor relations are formed within issuers and pooled across firms only after valid local pair

---

### [65] PARSER: Read in Parallel, Reason in Depth for Long-Context LLM Agents

**链接**: https://arxiv.org/abs/2609.06702
**作者**: Kun Li, Zexuan Qiu, Tianhua Zhang, Irwin King, Helen Meng
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [66] Fewer Assumptions by Design: A Reusable Skill for LLM-Assisted Verus Verification

**链接**: https://arxiv.org/abs/2609.34886
**作者**: Andrada-Livia Antoneac (Alexandru Ioan Cuza University of Ia\c{s}i, Bitdefender), Dorel Lucanu (Alexandru Ioan Cuza University of Ia\c{s}i), Drago\c{s} Teodor Gavrilu\c{t} (Alexandru Ioan Cuza University of Ia\c{s}i, Bitdefender)
**来源**: cs.AI cs.PL cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [67] Routing Without Embeddings: Fast And Interpretable Routing With Regular Expressions

**链接**: https://arxiv.org/abs/2609.34326
**作者**: Yifan Lu, Qiyue Zhang, Haotian Shan, Hanjie Chen, Jiarong Xing
**来源**: cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Model (LLM) routers commonly rely on neural query embeddings, with larger encoders expected to better capture query intent and difficulty. Yet scaling Qwen2.5 encoders from 0.5B to 72B parameters brings little improvement in routing accuracy (Figure 1b), suggesting that small encoders may already capture the query properties needed for routing. We therefore investigate which properties matter and whether they can be extracted directly from text without a neural encoder. We introduce REGEXROUTE, a pipeline that uses sparse autoencoders (SAEs) to discover interpretable regular-expression (regex) features. Using unlabeled text, an LLM turns descriptions of grouped SAE latents into regex extractors and refines them to match latent activation patterns. These extractors supply numerical features to a lightweight routing head, eliminating neural encoding at inference (Figure 1a). Across four benchmarks, one fixed set of 128 features achieves 76.43% average routing accuracy, com

---

### [68] Same Winners, Different Success Rates: Evaluating How LLM Agents Recover from Failures

**链接**: https://arxiv.org/abs/2609.34215
**作者**: Dong Xu, Zhangfan Yang, Jiantao Wu, Shipeng Zhang, Zexuan Zhu, Jiangqiang Li 等 (8 人)
**来源**: cs.AI cs.LG cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Evaluating how LLM agents recover from mid-task failures is central to deploying reliable agentic systems. Existing checkpoint-based benchmarks measure recovery by comparing which action is selected as best across independent runs, a quantity known as set agreement. However, set agreement is a purely ordinal measure that records which action wins without reflecting the absolute level of performance. When all actions fail, they tie at zero reward, and independent runs produce the same tied set with high probability, creating an illusion of stability that masks near-zero recovery success. We formalize this limitation through a set-path symmetry result, proving that for equal-cost Bernoulli actions the success probabilities (0.9, 0.8) and (0.2, 0.1) yield identical best-action-set distributions at every sample size. No procedure based solely on which action wins can distinguish these two regimes. We further prove that certifying exact population ties is impossible in finite time, and that

---

### [69] PowerBench: A Benchmark for Agentic Retrieval and Reasoning in Power Systems

**链接**: https://arxiv.org/abs/2609.34492
**作者**: Xijing Wang, Yinsheng Yao, Jinru Ding, Yidong Jiang, Ziwen Xu, Yiwen Jiang 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents offer new opportunities for automated analysis in industry. However, rigorous evaluation of such agents-for example, within power system scenarios-remains hindered: real operational data are confidential, and existing public resources fail to fully capture the chained dependencies and heterogeneous evidence. To address this gap, we propose PowerBench, comprising (1) a generation framework that derives interconnected heterogeneous operational data through a common dependency chain, and (2) a synthetic dataset generated by this framework. The dataset covers 761 devices across 100 device types, with 13.35 million hourly telemetry records spanning two years and 24,939 operational documents. Building on this dataset, we construct 300 questions across three task families that evaluate frontier LLMs' ability to complete analysis tasks that require autonomous evidence retrieval and reasoning across interconnected and heterogeneous data under restricted tool ca

---

### [70] Skip What You Can Predict: Predictive Repositioning for Policy Optimization for Efficient LLM Training

**链接**: https://arxiv.org/abs/2605.06755
**作者**: Ismam Nur Swapnil, Aranya Saha, Tasneea Zahra, Tanvir Ahmed Khan, Mohammad Ariful Haque, Ser-Nam Lim
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [71] LLM Judge Validation Under Sparse Overlap: From Inference to Design

**链接**: https://arxiv.org/abs/2609.31857
**作者**: Junxuan Li, Arko Mukherjee, Soumyabrata Pal
**来源**: cs.AI stat.AP
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Validating an LLM-as-a-judge requires estimating its agreement with humans, yet annotation budgets rarely allow every item to be multiply labeled. We prove that this \emph{overlap sparsity} is the first-order determinant of wrong deployment decisions: at 5\% pairwise overlap, wrong-decision rates reach 25\% and the probability of selecting the wrong best judge among ten candidates is 65\%. The two actionable levers are overlap \emph{quantity} and \emph{allocation}. For quantity, we derive a minimum-overlap formula showing $\rho \geq 0.25$ suffices for non-borderline judges while borderline cases remain fundamentally hard. For allocation, a zero-cost stratified scheme halves false-rejection rates relative to random sampling when strata are informative. We validate on 10 LLM judges across four evaluation matrices spanning visual assessment, causal reasoning, and summarization.

---

### [72] Evaluating Large Language Model Performance on International Maritime Dangerous Goods Code Compliance

**链接**: https://arxiv.org/abs/2608.21036
**作者**: Alexander Thomas, Hubert P. H. Shum, Darren Nellis, Manli Zhu, Phatpicha Yochum, William Bartle and Daniel Wrightson
**来源**: cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [73] DrawingsDreamer: A Unified Multi-View Engineering Drawings Generation Model

**链接**: https://arxiv.org/abs/2609.35242
**作者**: Shurui Liu, Weide Chen, Changwang Yi, Ancong Wu
**来源**: cs.CV
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Scalable Vector Graphics (SVG) are essential for modern industrial Computer-Aided Design (CAD). However, existing autoregressive SVG generation models are predominantly tailored for artistic creation and struggle to maintain the rigorous geometric fidelity and cross-view spatial alignment required for engineering drawings. To bridge this gap, we introduce \textbf{DrawingsDreamer}, a unified Large Language Model (LLM)-driven framework for multi-view vector-based engineering drawings generation. By formulating the generation of multi-view engineering drawings purely as a sequence modeling task, we eliminate the need of raster image encoders. We propose a Streamlined Representation utilizing hierarchical postfix tokenization, which guides the model to establish local geometric coordinates before assigning semantic boundaries. Optimized via a progressive task-aware curriculum schedule, \textbf{DrawingsDreamer} effectively transitions from localized structural repair to macroscopic generati

---

### [74] The Marathon of Scientific Reasoning: Robustness of Scientific Agents to Perturbations in Multi-Turn Interactions

**链接**: https://arxiv.org/abs/2609.34537
**作者**: Xiaoting Lyu, Xinbo Ma, Yufei Han, Hangwei Qian, Ziyang Lin, Bin Wang 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM)-based scientific agents are increasingly used for scientific problem solving, yet their robustness to imperfections arising during multi-turn interactions remains poorly understood. We introduce \textsc{SciARP} (\textbf{Sci}entific \textbf{A}gent \textbf{R}obustness to \textbf{P}erturbations), a benchmark for evaluating scientific agents under scientifically plausible perturbations throughout multi-turn problem solving. \textsc{SciARP} transforms 620 scientific problems into interdependent tasks of 3--13 turns and defines 13 perturbation types spanning problem understanding, evidence processing, reasoning, and conclusion formation. Clean and perturbed versions of each task are independently executed under matched settings, producing paired live trajectories for evaluating both task success and process reliability. Experiments across eight LLMs from four model families reveal three key robustness characteristics. First, different classes of scientific perturba

---

### [75] Planner-as-Router: Joint Plan-Time Model Routing for Cost-Efficient Multi-Agent Workflows

**链接**: https://arxiv.org/abs/2609.32917
**作者**: Vivek Kumar Singh, Preeti Priyam, Gautam Bhowmick
**来源**: cs.AI cs.CL cs.MA
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Running large language model (LLM) agents in production gets expensive fast. A frontier model (the largest, most capable tier) is accurate but can cost 25 times what a small model costs per token, and the gap compounds once a workflow chains several calls together. Planner-as-Router (PaR) attacks this from a different angle. Instead of leaving model-tier selection to some component downstream, it folds the choice into planning itself. As the planner breaks a query into subtasks, it also assigns each one a model size tier (small, mid, or frontier, ordered by capability and price), so the dependencies between subtasks are visible before any specialist runs. Unlike per-call routers such as cascade routing, which look at one node at a time, PaR sees the whole workflow up front and needs no separate router model or training data. We evaluate PaR with EntBench, a benchmark of 54 enterprise agentic tasks across seven classes, graded by actually running the generated Structured Query Language 

---

### [76] PlayTrain: An Efficient Reinforcement Learning Framework for LLM-Generated Adaptable JavaScript Games

**链接**: https://arxiv.org/abs/2609.09059
**作者**: Ryan Truong, Lance Ying, Samuel J. Gershman, Kazuki Irie
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [77] Vibe Analysis: Exploring LLM Adoption by Data Visualization Practitioners

**链接**: https://arxiv.org/abs/2609.31922
**作者**: Shani C Spivak, Aditi Krishna, Mahsan Nourani, Melanie Tory
**来源**: cs.HC cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are enticing in their promise to support data visualization (Vis) through faster and simpler workflows for data prep, analysis, and visualization creation. Yet LLMs are notoriously error-prone and not built for data visualization tasks. Few studies have explored LLM adoption among Vis practitioners. To fill this gap, we conducted semi-structured interviews with members of the Data Visualization Society, a global community of data visualization designers. Our findings show that Vis designers actively use LLMs for both creative and technical aspects of the visualization process. A new visualization workflow is emerging, a process we call vibe analysis, analogous to vibe coding. Some key challenges raised by participants parallel those of vibe coding, while others are Vis-specific, like gaps in Vis knowledge and chart verification. This work opens up opportunities for research combining LLM-mediated work with Vis tools that incorporate data visualization guida

---

### [78] Shapley-based Data Valuation for LLM Alignment via Sequential Preference Optimization

**链接**: https://arxiv.org/abs/2512.15765
**作者**: M\'elissa Tamine, Otmane Sakhi, Benjamin Heymann, Maxime Vono, Patrick Loiseau
**来源**: cs.LG cs.GT stat.ML
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [79] Every Bit, Everywhere, All at Once: A Binomial Multibit LLM Watermark

**链接**: https://arxiv.org/abs/2605.11653
**作者**: Thibaud Gloaguen, Robin Staab, Mark Vero, Martin Vechev
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [80] GLOVE: Global Verifier for LLM Memory-Environment Realignment

**链接**: https://arxiv.org/abs/2601.19249
**作者**: Xingkun Yin, Hongyang Du
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [81] Nutri-ATLAS: Embodied Agent for Tabulated Lookup and Assistance for Smarter nutrition

**链接**: https://arxiv.org/abs/2609.32803
**作者**: Uttej Kallakuri, Boxun Hu, Ankur A. Butala, Najim Dehak, and Tinoosh Mohsenin
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Generative and Agentic IoT systems offer a promising foundation for digital healthcare applications that combine sensing, personalized reasoning, and autonomous interaction in real-world environments. Nutrition assistance is a natural use case, but existing Large Language Model (LLM)-based systems are often limited to passive text interaction and static context, making them unreliable when food descriptions are ambiguous or nutritional evidence is missing. We propose Nutri-ATLAS, an Embodied Agent for Tabulated Lookup and Assistance for smarter nutrition in the real world. It integrates graph-grounded nutrition reasoning, hardware-aware LLM selection, and robot-based evidence acquisition. Nutri-ATLAS builds a unified Food-Nutrient knowledge graph from USDA FoodData Central and FoodKG and learns 64-dimensional GATv2 food and recipe embeddings. A shared hybrid graph-text scoring mechanism supports food nutrition extraction, nutritional gap filling, substitute retrieval, and recipe-level 

---

### [82] LaMET-Agent: An Agent Framework for Large-Momentum Effective Theory Analysis

**链接**: https://arxiv.org/abs/2609.32225
**作者**: Jinchen He, Xiangyu Jiang, Fei Yao, and Dian-Jun Zhao
**来源**: hep-lat cs.AI hep-ph
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large-momentum effective theory (LaMET) provides a first-principles framework for computing the $x$ dependence of light-cone parton distributions from lattice QCD. Over the past decade, theoretical and numerical advances have established a mature multi-stage workflow for systematic calculation of parton physics, although its implementation still requires expert judgment and substantial repeated effort. We present lamet-agent, an open-source large language model (LLM) agent framework that organizes this workflow into an executable, reproducible, and inspectable analysis pipeline. The present release supports collinear quark distributions and implements correlator analysis, renormalization, Fourier transformation, perturbative matching, continuum, physical pion mass and infinite-momentum extrapolations, and automated result review. We validate it on four end-to-end analyses: pion parton distribution functions in the gauge-invariant and Coulomb-gauge formulations, and pion and kaon distri

---

### [83] Right Answer, Wrong Reason: Accuracy, Consistency, and Consensus Are Misleading Indicators of LLM Faithfulness in Clinical Decision Support

**链接**: https://arxiv.org/abs/2609.32817
**作者**: Bharath Kumar Bolla, Bharath Kumar Bolla and Vishnu Surya Reddy Nandi
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Clinical Large Language Models (LLMs) achieve strong medical-exam accuracy; however, a correct answer does not guarantee that the explanation names the concepts that actually drove the decision. We introduce three lightweight, directly interpretable metrics for this faithfulness gap: the Explanation Stability Index (ESI), which measures reasoning consistency across repeated queries; the Causal Faithfulness Score (CFS), which tests whether cited concepts drive predictions via concept ablation; and the Perturbation Stability Score (PSS), which measures robustness to semantic-preserving paraphrases. By evaluating six LLMs on 150 MedQA-USMLE questions (900 model-question observations), we found that only 23.3% of the cited clinical concepts were causally necessary. Correct answers had lower CFS than incorrect answers (0.212 vs. 0.398), answer consistency negatively predicted CFS (Spearman r = -0.466), and model pairs could agree on answers while sharing only 8.8% of cited reasoning concept

---

### [84] DAAF: From Failure Localization to Editable System Assets in LLM Agents

**链接**: https://arxiv.org/abs/2609.32498
**作者**: Xiaoyang Yuan, Qi Liu, Yubin Ruan, Xinyi Mou, Zhuomeng Zhang, Wenjin Wang 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Deployed LLM agents increasingly rely on persistent, versioned system assets such as routing rules, knowledge segments, prompt instructions, and reusable skills. Failure-localization methods can identify where an error manifests in an agent or execution trace, but repair requires a different decision: which editable system asset should be changed, and is that change expected to improve the task outcome? We study this gap through component-attribute failure attribution, where diagnosis targets versioned, addressable items rather than execution locations. We propose the Detection-Aware Attribution Framework (DAAF), which learns the effects of valid attribute replacements and amortizes this intervention evidence into deployment-time diagnosis. DAAF combines sparse and noisy failure signals to decide whether intervention is warranted, learns component-type-conditioned replacement effects from controlled replays evaluated by executable task outcomes, and shares supervision across requests w

---

### [85] RGDT-Bench: Benchmarking LLM Reasoning for Rule-Governed Decisions and Their Justifications

**链接**: https://arxiv.org/abs/2609.34455
**作者**: Jianpeng Zhao, Haihua Xu, Haoyang Zhang, Shuang Qian, Yixiang Tang, Xintao Wang 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We study reasoning in Rule-Governed Decision Tasks (RGDTs), where models apply external rules to case facts and justify decisions, as required in policy, contract, and compliance settings. Beyond the deductive capability emphasized by standard mathematical and logical reasoning tasks, RGDTs require interpreting rules and their applicability, assessing conditions from evidence, combining judgments under rules and exceptions, and providing checkable justifications. These demands motivate a benchmark assessing both decisions and their stated grounds. We introduce RGDT-Bench, providing 202.1K condition-level supervision slots across four task tracks and eight supported task-probe combinations that vary access to supporting information. Label-blind extraction and deterministic checks produce labels for warrant completeness: source-referenced coverage and consistency of stated decision grounds. The benchmark attributes failures to four process layers: rule use, condition, evidence, and aggre

---

### [86] AeroCopilotBench: Safety-Gated Evaluation of LLM Agents on Aircraft Emergency Procedures in an Executable Cockpit

**链接**: https://arxiv.org/abs/2608.16349
**作者**: Yuchen Yuan, Zhenghuang Wu, Yuangan Li, Liang Ma, Ke Li
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [87] SpliTEE: Fast and Private LLM Inference by Coupling GPU-Assisted Trusted Execution Environments with Differential Privacy

**链接**: https://arxiv.org/abs/2609.15039
**作者**: Shashie Dilhara Batan Arachchige, Robin Carpentier, Hassan Jameel Asghar, Dali Kaafar
**来源**: cs.CR cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [88] Advancing Video-Text Pretraining with Multi-View Captions

**链接**: https://arxiv.org/abs/2609.35090
**作者**: Fida M. Thoker and Renaud Vandeghen and Karen Sanchez and Marc Van Droogenbroeck and Bernard Ghanem
**来源**: cs.CV
**匹配关键词**: Large Language Model, Multimodal Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Video-text pretraining has achieved remarkable progress through the scaling of models and datasets, yet the quality of language supervision remains underexplored. Existing web-scale datasets often provide only a single sparse caption per video that fails to capture rich spatiotemporal semantics, while directly using captioning models can generate noisy descriptions. We propose a large-scale multimodal large language model-based supervision generation framework that improves supervision diversity, fidelity, and semantic coverage. Starting from 10 million videos, our approach generates multi-view captions (MVC) through complementary summary and detailed captions, reasoning-based refinement, and semantic positive caption generation. To effectively exploit supervision at different granularities, we further introduce a granularity-aware text representation with separate CLS tokens for summary and detailed views. We pretrain video-text models using the resulting supervision corpus and evalua

---

### [89] How LLM Task-Adaptation Reshapes Alignment: A Multi-dimensional Study of Behavioral and Representational Drift

**链接**: https://arxiv.org/abs/2607.22676
**作者**: James Elcock, William F. Shen, Xinchi Qiu, Nicholas D. Lane
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [90] From 'What' to 'How' and 'Why': Sharing LLM-Generated Retrospective Summaries of Older Adults' Passive Tracking Data with Remote Family Members

**链接**: https://arxiv.org/abs/2606.03876
**作者**: Jiachen Li, Reina Szeyi Chan, Akshat Choube, Xiang Zhi Tan, Elizabeth Mynatt, Varun Mishra
**来源**: cs.HC cs.AI cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [91] PlurVA-LLM-2026 Shared Task Track-1: Pluralistic Value Alignment in LLMs via Multilingual Fine-Tuning and Threshold Calibration

**链接**: https://arxiv.org/abs/2609.32382
**作者**: Vihindi Kotalawala, Nevidu Jayatilleke
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We present our system for the PlurVA-LLM 2026 Shared Task Track-1, which focuses on pluralistic value alignment in the contexts of China, Indonesia, and Sri Lanka. For this resource-constrained track, we fine-tuned Llama 3.1 8B Instruct using 4-bit QLoRA. Our approach combines option-permutation augmentation for Chinese data, annotator vote expansion for Indonesian data, and binary reformulation with SinhalaMMLU augmentation for Sri Lankan data. We further applied conditional threshold calibration to the predictions for the Sri Lankan data. The final system achieved accuracies of 0.785 for Chinese, 0.715 for Indonesian, and 0.916 for Sri Lankan, resulting in an overall macro-average accuracy of 0.805.

---

### [92] Equal Ranking Quality, Different Decisions: Measuring and Reducing Order Dependence in LLM Scorers

**链接**: https://arxiv.org/abs/2608.26762
**作者**: Markus Frohmann, Mahdiyar Ali Akbar Alavi, Elizabeth Lingg, Navid Rekabsaz
**来源**: cs.CL cs.IR cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [93] LiveOption: Evaluating LLM Agents in Structured Option Trading with Nonlinear Payoffs

**链接**: https://arxiv.org/abs/2609.33470
**作者**: Haochen Luo, Yifan Li, Binh Minh An, Xiaolong Luo, Zhengzhao Lai, Yuan Zhang 等 (7 人)
**来源**: cs.AI q-fin.CP
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) and multi-agent systems (MAS) have shown promise in financial decision-making, yet existing evaluations focus on equity trading and primarily assess directional prediction, overlooking the structural complexity of derivative markets. Option trading introduces fundamentally different challenges, including nonlinear payoffs and multi-leg strategy construction, requiring structured decisions rather than simple directional bets. We introduce LiveOption, an evaluation framework for LLM-based agents in option trading. LiveOption formulates the problem as structured sequential decision-making under realistic execution and capital constraints, and provides a reproducible environment with standardized interaction protocols. The framework includes three task suites covering portfolio overlays, event-driven earnings trading, and 0DTE intraday trading. We further propose a hierarchical metric suite that evaluates action validity, decision quality, risk characteristics,

---

### [94] Improving the Diversity of LLM Outputs without a Trade-off

**链接**: https://arxiv.org/abs/2609.33038
**作者**: Ryoma Sato
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We propose DAST (Diversifying Arithmetic Sampling with TokenTour), a method that increases the diversity of LLM outputs without any change to the marginal distribution and with negligible generation-time overhead (a few microseconds). We observe that token IDs are often arranged in a meaningless order and reassign them so that tokens with similar meanings appear consecutively. This can be done in advance in a few hundred seconds per model, and the resulting order can be reused for all subsequent generations. By combining this order with arithmetic sampling (or quasi-Monte Carlo methods), we make similar tokens less likely to be generated across runs while preserving the distribution. Our method not only produces qualitatively good ideas but also significantly improves performance on the downstream task of ProtoQA.

---

### [95] XWind: A Cross-site Router for Large Language Model Inference Serving at Renewable Energy Farms

**链接**: https://arxiv.org/abs/2605.23348
**作者**: Tella Rajashekhar Reddy, Atharva Deshmukh, Liangcheng Yu, Chaojie Zhang, Mike Shepperd, Rohan Gandhi 等 (10 人)
**来源**: cs.DC cs.AI cs.NI
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [96] Selective Deficits in LLM Mental Self-Modeling in a Behavior-Based Test of Theory of Mind

**链接**: https://arxiv.org/abs/2603.26089
**作者**: Christopher Ackerman
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [97] LACUNA: A Testbed for Evaluating Localization Precision for LLM Unlearning

**链接**: https://arxiv.org/abs/2607.02513
**作者**: Matteo Boglioni, Thibault Rousset, Siva Reddy, Marius Mosbach, Verna Dankers
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [98] ControlScope: Workflow Revision and Reliability in LLM Agents

**链接**: https://arxiv.org/abs/2609.34313
**作者**: Jingjie Ning, Xueqi Li, Yibo Kong, Dongting Li
**来源**: cs.AI cs.CL cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> How much of a running workflow should a language model agent revise? ControlScope compares continuing generated code, editing the next tool call's data arguments, and replacing the unfinished workflow from the same public execution state. The nested permissions separate available repairs from the actions an agent selects. We evaluate one-time and repeated reviews across filesystem tasks, ALFWorld, and AppWorld. Across two source programs per task and three reasoning-reviewer draws on 20 filesystem tasks, FULL completes 15-16 tasks versus 13 for KEEP; across four fast draws it completes 10-13 versus 13. Fresh student-record confirmation reproduces a batch-read repair. ALFWorld fast panels yield KEEP/ARG/FULL scores of 85/86/87 on 87 tasks across 52 scenes and 134/134/127 on 134 tasks across four scenes; reasoning on the 87-task cohort also yields 85/86/87 with substantial review cost. An AppWorld V1 official-test panel of 585 task instances from 195 scenario templates shows small net di

---

### [99] When Does the Concept of "Dog" Emerge in an Audio LLM?

**链接**: https://arxiv.org/abs/2609.33458
**作者**: Zhe Wang, Shiqi Liu, Ruiyun Zhong, Tiechong Zhu, Yihua Tan
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal large language models answer audio questions, but how they represent auditory semantics and use them in decisions remains unclear, limiting our understanding of response formation. We study dog barking in Qwen2.5-Omni-7B using Jacobian lens (J-lens) readout and directional interventions. We define the dog direction as a J-lens-derived hidden-state vector associated with dog; adding or removing its component modulates dog-related information. We find this information decodable without dog/bark prompt cues or animal-identification requirements. Directional interventions change response tendencies and some final answers, with effects concentrated in late-layer states immediately before generation across species classification, vocalization classification, and sound description. The dog direction shows no comparable advantage over controls in animal/other classification. These results provide causal-intervention evidence that the dog direction affects output scores in a task-dep

---

### [100] CodeScaler: Scaling Code LLM Training and Test-Time Inference via Reward Models

**链接**: https://arxiv.org/abs/2602.17684
**作者**: Xiao Zhu, Xinyu Zhou, Boyu Zhu, Hanxu Hu, Mingzhe Du, Haotian Zhang 等 (8 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [101] An RL View of OPD: Least Square Policy Distillation for Sample-Efficient LLM Reasoning

**链接**: https://arxiv.org/abs/2609.35505
**作者**: Shangzhe Li, Yuxiao Yang, Tianrun Yu, Kaixiang Zhao, Xiaoyun Wang, Taylor W. Killian 等 (7 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We study on-policy distillation (OPD) through the lens of reinforcement learning, establishing a connection between the reverse-KL objective in OPD and KL-regularized policy optimization. Building on this connection, we introduce Least-Square Policy Distillation (LSPD), an RL-inspired framework that brings optimistic exploration and off-policy data reuse from value-based RL into policy distillation. LSPD preserves policy diversity through exploration while improving rollout efficiency by repeatedly learning from previously collected trajectories. Our theoretical analysis connects LSPD to optimistic value-based learning and shows that its idealized formulation achieves a sharp $\tilde{\mathcal O}(\log K)$ regret bound under online exploration. Empirically, LSPD consistently outperforms existing distillation baselines across six mathematical reasoning benchmarks and diverse teacher-student settings, with average gains of +1.59 points in Avg@16. Remarkably, through Pass@k evaluations up t

---

### [102] Frontier Learning: Training LLM Reasoners at the Edge of Capability

**链接**: https://arxiv.org/abs/2609.35426
**作者**: Robin Faro, Shyam Sundhar Ramesh, Ilija Bogunovic, Aurelien Lucchi
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reinforcement Learning-based post-training of Large Language Models (LLM) has been successfully applied to improve their reasoning capabilities. Existing pipelines primarily finetune LLMs on a fixed pool of problems specified prior to training using the GRPO loss. This is fundamentally limiting, as learning signal arises only when policy rollouts mix successes and failures, causing the useful portion of any fixed pool to quickly become stale as the model improves. To address this, we propose frontier learning, an open-ended post-training approach in which procedural generators are used online to continually produce informative training problems. It treats the generator's task-specific parameters as a search space and uses a regret signal to prioritize and explore frontier difficulty levels in order to focus training at the edge of the model's evolving reasoning capabilities. Across several reasoning tasks and model families, our approach consistently achieves higher relative gains over

---

### [103] OmniTide: Co-Designing Algorithms and Systems for Efficient On-Device Omni-LLM Streaming

**链接**: https://arxiv.org/abs/2609.34653
**作者**: Zongshang Shen, Wangsong Yin, Daliang Xu, Mengwei Xu, Xuanzhe Liu
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> On-device streaming omni-modal inference safeguards user privacy and eliminates prohibitive per-token API costs, but faces a critical bottleneck: the continuous influx of multimodal data rapidly exhausts constrained memory and compute budgets via monotonic KV cache growth. Existing sparse attention methods fall short, either incurring prohibitive online estimation latency or destroying interleaved cross-modal context, while failing to resolve physical memory fragmentation. We present OmniTide, the first algorithm-system co-design tailored for efficient on-device streaming omni-modal inference. Driven by the observation of modality-aware structural sparsity, OmniTide adopts a unit-based abstraction with two components: (1) At the algorithm level, OmniPick logically retains critical multimodal context based on unit boundaries and modality importance to preserve task accuracy; (2) At the system level, OmniPage physically partitions the cache by retention likelihood and dynamically compact

---

### [104] How code helps different tasks? A decompositional lens on LLM post-training

**链接**: https://arxiv.org/abs/2609.33845
**作者**: Zheng Yu, Yiwei Li, Yishen Chen, Xiang Li, Jiale Han, Benyou Wang 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Evaluating code data as a single corpus can obscure which types of code data benefit which models and downstream tasks. Effective data selection requires understanding both the benefits of individual categories and whether these benefits persist when categories are combined. We introduce a decompositional lens for studying these effects in LLM post-training. We first decompose an execution-verified code corpus into interpretable categories based on the computational patterns of its solutions. Through controlled fine-tuning experiments, we compare individual categories with a balanced mixture across instruction-tuned models on question answering, mathematics, and code generation. The resulting response maps reveal recurring gains in average question-answering performance, while the same category can improve one model or task and degrade another. The best-performing category also varies with the starting model and target task. We then compose compact mixtures guided by these results and 

---

### [105] HESP: Separating What to Probe from When to Stop in Local LLM Alert-Triage Agents

**链接**: https://arxiv.org/abs/2609.33446
**作者**: Zhuowen Liu, Zhixuan Wang
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Security operations centers receive far more alerts than analysts can investigate, and organizations that cannot send their telemetry to hosted models must automate triage with small open-weight LLMs on their own hardware. Current LLM agents leave the investigation procedure to the model, and small local models fail at it: they probe without converging, never commit to a verdict, or dismiss real attacks. In this paper, we present HESP, a controller that holds the investigation procedure outside the model. HESP keeps a ledger of competing explanations, selects read-only probes by expected information gain per cost, accepts only verdicts backed by current evidence, can end an investigation itself, and journals every prediction before its observation. We evaluated HESP in four pre-registered studies with five open-weight models from two families (7B to 72B), totalling 7,272 audited episodes in a controlled triage environment. With likelihood tables counted from LLM-free runs, HESP lifts Q

---

### [106] Investigating Learner-Aware Design of LLM-Generated Educational Feedback

**链接**: https://arxiv.org/abs/2602.11650
**作者**: Momoka Furuhashi, Kouta Nakayama, Noboru Kawai, Takashi Kodama, Saku Sugawara, and Kyosuke Takami
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [107] REFLEX with Jev for Efficient Selective Control in LLM Agents

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2609.26532&hl=zh-CN&sa=X&d=5607024401415703874&ei=SJS7arCyDMKL6rQPhLm5qA0&scisig=ACTRDVH8yZpdWUhBFFPbRNh24j5D&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:ACTRDVEEr233VErbxroTWJ0YT-xH&html=&pos=0&folt=kw-top
**作者**: T Wu, WYB Lim - arXiv preprint arXiv:2609.26532, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> LLM agents often use generative models for bounded decisions, raising the question of when these decisions can be handled more efficiently without reducing task success. We study REFLEX, an agent architecture that uses Jev as a fast, typed

---

### [108] From Hand-Crafted to LLM-Based Variation Operators in Metaheuristics: A Tutorial

**链接**: https://arxiv.org/abs/2609.31649
**作者**: Camilo Chac\'on Sartori, Guillem Rodr\'iguez-Corominas, Christian Blum
**来源**: cs.NE cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly being employed as variation operators in metaheuristics, generating or modifying candidate solutions, heuristics, or programs inside iterative search loops. This shift reframes variation as a model call conditioned on different types of information. We introduce an operator-level framework with two descriptors: (1) the type of prompt-conditioning information at variation time (\texttt{Numeric}, \texttt{Symbolic}, \texttt{Linguistic}), and (2) artifact persistence, identifying what survives the model call (\texttt{Transient}, \texttt{Amortized}, \texttt{Transfer}). The tutorial shows how to classify, build, and select these operators through a worked build template, a method survey, an evidence table, and a cost-aware decision guide.

---

### [109] Teach to Learn: Hint Annealing for Self-improving LLM Reasoning

**链接**: https://arxiv.org/abs/2609.34975
**作者**: Zile Wang, Zijian Li, Haodong Wang, Jian Liu, Qianli Liu, Lucas Muli 等 (8 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Group Relative Policy Optimization (GRPO) improves language-model reasoning by comparing verified rewards among multiple solution rollouts for each query. However, difficult training queries can yield only incorrect rollouts, leaving GRPO with no reward contrast or learning signal. Prior hint-based methods construct auxiliary hints from solution evidence and use them to re-solve failed queries, recovering learning signal. Yet the resulting trajectories are typically treated as ordinary solution trajectories despite being generated under an assisted condition unavailable at evaluation. We discover hinted reward shift: recovered reward contrast can concentrate policy updates on hinted trajectories, limiting improvement without hints. This also creates a trade-off: increasing hinted trajectories can accelerate early learning but intensify reward shift later. To address this problem, we propose HATCH (Hint-Annealed Self-Teaching), an online single-policy framework that learns from both gen

---

### [110] Surprising Success, Repeated Failure: Entropy-Guided Credit Assignment for Exploration in LLM Reasoning

**链接**: https://arxiv.org/abs/2609.33781
**作者**: Woongyeong Yeo, Minki Kang, Chanuk Lee, Sangwoo Park, Jinheon Baek, Sung Ju Hwang
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reinforcement learning with verifiable rewards (RLVR) enhances reasoning in large language models (LLMs) through outcome-level feedback, yet recent approaches to finer-grained credit assignment often require auxiliary models, additional sampling, or privileged information. Although policy entropy provides a readily available signal, prioritizing uncertain positions under both reinforcement and penalization concentrates penalties where failed responses still retain alternatives for recovery, which can suppress opportunities for exploration. To address this, we introduce Entropic Advantage Policy Optimization (EAPO), an entropy-guided credit assignment method that treats success and failure asymmetrically. Specifically, motivated by the observation that success under uncertainty is less repeatable while confident failures tend to recur, EAPO couples normalized policy entropy with the sign of the response advantage to reinforce surprising success and correct repeated failure. It assigns s

---

### [111] TSR: Trajectory-Search Rollouts for Multi-Turn RL of LLM Agents

**链接**: https://arxiv.org/abs/2602.11767
**作者**: Aladin Djuhera, Swanand Kadhe, Farhan Ahmed, Syed Zawad, Heiko Ludwig, Holger Boche
**来源**: cs.AI cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [112] Eta Given Delta: Defining LLM Tool Efficiency With Marginal Tool Utility

**链接**: https://arxiv.org/abs/2607.14108
**作者**: Nyx Iskandar, Perla Gamez
**来源**: cs.CL cs.AI cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [113] Action-Space Shaping for LLM Agents: Measuring and Mitigating Tool-Schema Bias

**链接**: https://arxiv.org/abs/2609.34971
**作者**: Yinhong Liu, Zhili Tan, Zilin Wang, Zhijiang Guo
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) have shown strong performance on tool-use agentic tasks when given a fixed tool schema. Yet a tool schema is not the action space of an agent; it is merely one interface representation of it. The same executable action can be exposed through many different, functionally equivalent tool definitions, and an agent that has truly learned a task should behave consistently across them. We show that current agents often do not, a phenomenon we term schema bias. To study this systematically, we introduce an executable transformation framework that rewrites a native tool schema using nine operators, including merging and splitting tools, altering how a single tool is expressed, and distributing one action across several dependent calls. The tasks, executable actions, and reachable states remain fixed, so any change in success is attributable to the interface alone. Evaluating eleven LLMs, including two closed models, on up to 32 schema variants, we ask how large sch

---

### [114] SkillBloat: Token Amplification Attacks via Skill Injection in LLM Coding Agents

**链接**: https://arxiv.org/abs/2608.21929
**作者**: Yuanjin Zheng, Jingbang Chen
**来源**: cs.CR cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [115] Don't Solve, Just Compare: Tiny Advisors for Runtime Intervention in LLM Agents

**链接**: https://arxiv.org/abs/2608.21027
**作者**: Yanze Jiang, Mingxuan Li, Yuhao Wang, Shengfang Zhai, Jiaheng Zhang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [116] Emergent Collusion in Long-Horizon LLM Agent Interaction

**链接**: https://arxiv.org/abs/2609.24967
**作者**: Xinrui Shi and Yanzhe Zhang and Diyi Yang
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [117] Splitting Documents at Lower Cost: Multi-Split Boundary Decisions for LLM-Based Page Stream Segmentation

**链接**: https://arxiv.org/abs/2609.22620
**作者**: Nikhil Reddy Pottanigari, Sepideh Kharaghani, Saverio Vadacchino, Alejandro Posada, Ying Zhang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [118] Inside the LLM Word Factory

**链接**: https://arxiv.org/abs/2606.08562
**作者**: Benzi Busigin, Yuval Pinter
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [119] A Statistical Perspective on Knowledge Distillation: Foundations, Classical Methods, and Large Language Model Extensions

**链接**: https://arxiv.org/abs/2609.33727
**作者**: Luyang Fang, Haoran Lu, Jiazhang Cai, Tao Wang, Huimin Cheng, Wenxuan Zhong 等 (7 人)
**来源**: stat.ML cs.LG
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Knowledge Distillation (KD) has emerged as a vital paradigm for transferring the capabilities of high-capacity models to efficient ``student'' counterparts, addressing critical challenges in computational cost, deployment constraints, and privacy-sensitive settings. Although KD is widely used in practice, it is often viewed primarily as an engineering technique, with a unified statistical perspective remaining less developed. This review bridges that gap by presenting a unified Bayesian formulation of KD that formulates teacher predictions as prior information. This provides a principled interpretation of how teacher information is incorporated into student learning and establishes a rigorous connection to uncertainty quantification. We demonstrate how this foundational lens reconciles classical distillation with modern extensions in generative and foundation-model systems, showing that contemporary developments remain rooted in these same statistical principles. By synthesizing theory

---

### [120] WeaveData: A Multimodal Data Analysis System with Self-Critiquing and Self-Evolving LLM Plans

**链接**: https://arxiv.org/abs/2609.34764
**作者**: Min Jia, Shihao Zhou, Jun-Peng Zhu, Peng Cai, Kai Xu, Chao Zhang 等 (10 人)
**来源**: cs.DB cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal data analysis, which answers questions over relational tables, text, and images, has attracted growing attention in the data management community. Large language models (LLMs) enable such analysis in natural language by generating analysis plans over relational and semantic operators. However, LLM-generated plans are error-prone: a plan may silently compute something other than what was asked, fail during execution, or return a result that misses the question. This paper presents WeaveData, a multimodal data analysis system with self-critiquing and self-evolving LLM plans. First, WeaveData generates a typed logical plan for each question and critiques it step by step before execution, and it checks the executed result against the question afterwards. Second, WeaveData evolves a plan that fails or misses the question: it diagnoses the failure with the actual data, reuses the results that remain valid, and accumulates planning experience for later questions. Third, WeaveData g

---

### [121] Frozen Judges, Moving Agents: Version-Dependent LLM-Judge Error and the Limits of Judge-Assisted Agent Evaluation

**链接**: https://arxiv.org/abs/2609.34198
**作者**: Jiapeng Li
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Language-model judges compare agent upgrades with their predecessors, but a fixed judge can make version-dependent mistakes. We analyze 35 public coding-agent submissions (20 prespecified version pairs on 250 SWE-bench Verified issues), two customer-service agents (155 tau-bench tasks), and 1,106 expert-labeled AgentRewardBench trajectories. An upstream outage left three judges for the primary SWE-bench analysis (8,743 aligned agent-task cells); the fourth is descriptive. All three coding-agent judges and all four tau-bench judges reject task-conditioned error invariance after multiplicity adjustment. On SWE-bench, 32 of 60 judge-by-pair units have a detectable differential comparison component; eight judge-only intervals declare improvements that execution-based intervals cannot establish, despite rank correlations of 0.71-0.79. In tau-bench, one judge confidently reverses a nine-point reference-reward gap by penalizing a procedural habit the reward ignores. False acceptance of failed

---

### [122] Goal-Conditioned Supervised Learning for LLM Fine-Tuning

**链接**: https://arxiv.org/abs/2605.16345
**作者**: Shijun Li, Kaiwen Dong, Xiang Gao, Joydeep Ghosh
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [123] Beyond Repeated Sampling: Learning Search Policies for LLM Reasoning

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2609.26704&hl=zh-CN&sa=X&d=17772151055448256228&ei=SJS7arCyDMKL6rQPhLm5qA0&scisig=ACTRDVHwphl4fhz0Vh7uwYze5gOV&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:ACTRDVEEr233VErbxroTWJ0YT-xH&html=&pos=9&folt=kw-top
**作者**: I Labiad, M Kowalski, M Schoenauer, R Munos… - arXiv preprint arXiv …, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> (2026), which samples concepts from one LLM and conditions a second LLM ’s answers on them; unlike them, we find in our reproduction that this advantage largely disappears once the repeated-sampling baseline is allowed to explore (Section

---

### [124] STEP-LLM: Generating CAD STEP Models from Natural Language with Large Language Models

**链接**: https://arxiv.org/abs/2601.12641
**作者**: Xiangyu Shi, Junyang Ding, Xu Zhao, Sinong Zhan, Payal Mohapatra, Daniel Quispe 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [125] Just-In-Time Reinforcement Learning: Continual Learning in LLM Agents Without Gradient Updates

**链接**: https://arxiv.org/abs/2601.18510
**作者**: Yibo Li, Zijie Lin, Ailin Deng, Xuan Zhang, Yufei He, Shuo Ji 等 (8 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [126] Learning Multimodal Embeddings with Evidence-Aligned Readout

**链接**: https://arxiv.org/abs/2609.33659
**作者**: Zirong Chen, Fuda Ye, Enjun Du, Junfu Pu, Xinlei Wang, Xinyu Zuo 等 (10 人)
**来源**: cs.CV cs.IR
**匹配关键词**: Large Language Model, Multimodal Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal large language models can expose task-relevant evidence through generation, but producing useful evidence does not by itself determine how it enters a retrieval embedding. We study whether the semantic organization of that evidence can also specify where representations are read. To address this question, we introduce EviAlign, which couples Semantic Evidence Generation with Boundary Readout in a shared multimodal large language model. It organizes evidence into five semantic units, reads the contextualized state at each unit boundary, and aggregates these states into a single normalized embedding. Generation and contrastive retrieval objectives jointly train this shared structure. With the same trailing readout, semantic evidence and free-form CoT yield nearly identical retrieval performance, suggesting that evidence organization alone does not explain the full gain. A controlled $2\times3$ study compares consistent and permuted evidence organization across three readout st

---

### [127] The Decomposition Tax: LLM Pipelines Lose Up to 40 Accuracy Points at Their Own Interfaces

**链接**: https://arxiv.org/abs/2609.32825
**作者**: Tianqi Bu, YuXuan Peng, Junteng Tu, Henghui Xiao
**来源**: cs.AI cs.CL cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A four-stage LLM pipeline gives up as much as 40.5 accuracy points at its own interfaces (gemma-3-12B on MATH-500, Holm-corrected p = 1.66e-19; the largest tax in the primary family). We hold model, problem, stages, stage prompts and completion budget fixed, vary only whether each stage can still see the original problem, and call the accuracy difference the decomposition tax. Across 21 open-weight models from nine organisations, on GSM-Hard and MATH-500 at n = 200 paired items per cell, 70 of 118 primary-family tests survive Benjamini-Hochberg correction and 54 survive Holm. On GSM-Hard, a placebo recovers nothing: it carries at least 60% of the extra tokens and at most one word of the problem. Builders design a pipeline one stage at a time, and its bill arrives at the interfaces between stages. Rewriting one stage's instruction moves gemma-3-12B's tax from 4.5 to 36.5 points, and adding "every relationship stated between them" to a stage that lists the numerical quantities lowers the

---

### [128] Measurement Boundaries in LLM Financial Agent Evaluation: Fixed-Tape Execution and Multi-Defect Auditing

**链接**: https://arxiv.org/abs/2609.32379
**作者**: Weicheng Xue
**来源**: cs.LG cs.AI cs.CE cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> What controls are needed to interpret execution performance and audit scores in LLM agent evaluations? We study two limits on these interpretations in a financial agent harness. In Study~A, comparing independent runs under idealized and stressed execution on three synthetic settings that share one 24-day upward phase mixes the execution rule with fresh model responses and portfolio feedback: the parsed decision paths agree in only $19.8\%$ of $450$ pairs. Replaying each stored response tape through both execution destinations gives a narrower result. Conditional on those responses, stressed execution changes total return by $-0.0170$ (95\% interval $[-0.0230,-0.0117]$), or $10.4\%$ of the idealized baseline, and ten seed clusters do not resolve the model ranking. Study~B corrects an incomplete answer key and replaces legacy tasks with matched zero-, one-, and two-defect tasks under an explicit multi-label prompt. The drop in target violation recall from one to two defects is positive i

---

### [129] CSC: Calibrated Simplicity for Conflict-Aware Social Bot Detection in the LLM Era

**链接**: https://arxiv.org/abs/2609.23320
**作者**: Yipeng Qian, Pengjie Zhao, Chaoxi Niu
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [130] PINNMorph: Evolving Online Adaptation Policies for Physics-Informed Neural Networks

**链接**: https://arxiv.org/abs/2609.32685
**作者**: Xu Yang, Mingyang Yu, Jun Zhang, Keqian Li, Jing Xu
**来源**: cs.AI cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Physics-informed neural networks (PINNs) provide a learning-based framework for solving partial differential equations (PDEs), yet their training behavior can change substantially throughout optimization. Residual distributions, gradient interactions, regional learning difficulty, and model-capacity requirements may evolve over time, while the network architecture and major training mechanisms are typically determined before training. We propose PINNMorph, an online PINN adaptation framework based on large language model (LLM)-guided policy evolution. PINNMorph maintains a population of state-conditioned adaptation policies that map execution diagnostics to controlled interventions over topology modification, additive representation augmentation, objective balancing, gradient handling, adaptive sampling, and optimizer-phase control. At each intervention opportunity, candidate programs are instantiated from the current policy population, selected according to the observed training state

---

### [131] Extraction of clinical findings from mammography and breast ultrasound reports: a comparison between specialists and Artificial Intelligence

**链接**: https://arxiv.org/abs/2609.31974
**作者**: Lorenzo Farias, Hanna Reckziegel, Daniela Duarte da Silva Bagatini, Daniel Schulz, Gabriela de Andrade Monteiro, Let\'icia Zanatta 等 (10 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Breast cancer is the leading cause of cancer-related death among women in Brazil, and the time between the request and the release of mammography reports directly influences adherence to screening, making the agility in processing these reports a critical factor for early diagnosis. In this context, this study compares the performance of a Large Language Model (LLM) with manual extraction performed by a team of health researchers in identifying clinical findings from mammography and breast ultrasound reports written in Brazilian Portuguese. Named Entity Recognition (NER) was applied through Prompt Engineering using a few-shot strategy, employing the Gemini 2.5 Flash model, selected from preliminary exploratory tests with four candidate models. The Gemini 2.5 Flash model demonstrated the best performance, achieving a Macro F1 of 0.91 and a Micro F1 of 0.98. The subjective validation, in which 29 exams of different formats were evaluated by health researchers using a Likert scale, yielde

---

### [132] Fence Slicing: A CPU-only implementation framework of block cipher algorithms for LLM -based Edge Intelligence

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S1383762126003413&hl=zh-CN&sa=X&d=17885398400710049371&ei=SJS7arCyDMKL6rQPhLm5qA0&scisig=ACTRDVGZntb9Tx9IX04mzWOgWuwS&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:ACTRDVEEr233VErbxroTWJ0YT-xH&html=&pos=8&folt=kw-top
**作者**: C Chen, H Guo, Z Gong, Z Guan, W Liu, J Liu - Journal of Systems Architecture 等 (7 人)
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> LLM -based edge intelligence has gained considerable research interest and its security largely relies on cryptographic techniques. As a commonly used cryptographic primitive, block ciphers have implementation performance that directly

---

### [133] PersonaManifold: Revealing and Exploiting Curved Geometry in LLM Persona Representations

**链接**: https://arxiv.org/abs/2609.34571
**作者**: Rui Xu, Yinghui Xu, Libo Wu
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Controlling persona in large language models (LLMs) at inference time is important for role-playing, personalized dialogue, and social simulation. Recent methods extract persona vectors from the model's activation space and apply Euclidean operations---addition, scaling, and linear interpolation---under the linear representation hypothesis. However, these methods themselves report systematic failures: non-orthogonal trait dimensions, asymmetric ceiling and resistance effects, and significant deviations in multi-trait composition, suggesting that the linear isotropic assumption does not hold. We propose PersonaManifold, a framework that models persona representations as points on a curved, low-dimensional Riemannian submanifold in activation space. We estimate the manifold's intrinsic geometry---local metric tensors, geodesic distances, and Ollivier-Ricci curvature---and introduce geodesic steering, which interpolates between personas along manifold geodesics rather than Euclidean strai

---

### [134] EffiPair: Improving the Efficiency of LLM-generated Code with Differential Execution Feedback

**链接**: https://arxiv.org/abs/2604.05137
**作者**: Samira Hajizadeh, Suman Jana
**来源**: cs.PL cs.AI cs.CL cs.LG cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [135] Efficient LLM Adversarial Training via Low-Rank Defense and Circuit-Guided Surrogates

**链接**: https://arxiv.org/abs/2607.28959
**作者**: Weiyi He, Yuping Lin, Jiliang Tang, Yue Xing
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [136] From Search to Research: Exploring Search Scaling in Autonomous Quantitative Factor Mining

**链接**: https://arxiv.org/abs/2609.35559
**作者**: Kangcheng Deng, Hui Cai, Jiacheng Lu, Chester Zhongshu Qian, Rui Sun, Beidi Luan 等 (9 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Inference scaling has been shown to improve large language model (LLM) performance, and this principle naturally extends to autonomous LLM agents through increased search budgets, which we refer to as *search scaling*. Although prior work has characterized the mechanisms, scaling behavior, and performance limits of LLM inference scaling, much less is known about these questions in autonomous research. Therefore, we investigate how search scaling affects research performance and what mechanisms drive these gains using 50 quantitative factor-mining tasks grounded in financial research reports. Each task requires an agent to carry out an end-to-end research loop, from interpreting a hypothesis and implementing it in code to evaluating and iteratively refining the resulting factor. Across nine models, we examine how model capability, search depth, and search organization shape factor quality by tracing performance across varying budgets, transferring intermediate research states between mo

---

### [137] Streamlined Reflective Evolution for Task-Adaptive Self-Refinement Pipelines

**链接**: https://arxiv.org/abs/2609.32458
**作者**: Xiaofan Zhou, Lu Cheng
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reflective prompt optimization improves large language model (LLM) systems without updating model weights, but fixed architectures constrain how self-refinement is organized. We introduce Workflow-Designing Agents (WDA), a framework for streamlined reflective evolution of task-adaptive self-refinement pipelines. Starting from a minimal prompt, WDA jointly evolves stage instructions and their sequential structure. During evolution, we find that repeated revisions can accumulate redundant instructions in a single prompt. In WDA, we propose to address this problem with SPLIT, which redistributes these instructions across specialized stages. Three-example reflection and local screening guide selective search, while calibration scores guide Pareto admission and rollback of unhelpful trailing updates. The resulting pipelines are task-adaptive: their instructions and depth are learned from task data, then fixed for all test inputs within that task. We evaluate WDA on five benchmarks spanning 

---

### [138] Do World Models Learn Global Understanding?

**链接**: https://arxiv.org/abs/2609.34058
**作者**: Alexander Detkov, Matt Thomson
**来源**: cs.LG cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> AI systems often feel brittle and fragmented. A large language model (LLM) may correctly explain a concept but fail to apply it, or follow safety instructions in one context but not another. This behavior suggests a general failure to lift local information to a global understanding. To gain fundamental insight, we frame "understanding" as learning constraints and propagating their consequences. We construct learning tasks on monoid worlds, sets of states connected by action transitions, where observed training transitions and an unseen constraint jointly determine held-out transitions. Measuring generalization tests whether models can learn global constraints from local transitions and propagate their consequences. We consider inverse, commutativity, composition, and periodicity constraints relevant to spatial and semantic structure. Across attention, recurrent, and state-space architectures, next-state training fits the data but fails to propagate non-trivial constraints. Composition

---

### [139] AgentBoundary: Counterfactual Evaluation of Safety in Tool-Using LLM Agents

**链接**: https://arxiv.org/abs/2609.33658
**作者**: Tianzhuo Yang, Zirui Mi, Yantao Huang, Guoxi Zhang, Jiawei Chen, Yaodong Yang 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Safety alignment for large language models (LLMs) in conversational settings is largely framed around whether to answer or refuse a request. In agentic settings, however, the same models must decide whether to act as permission-critical evidence emerges during execution. This creates a distinct challenge: apparent risk, action permissibility, and task competence are easily confounded, making agentic over-refusal difficult to distinguish from ordinary task failure. To address this, we introduce AgentBound, the first four-way counterfactual generation-and-evaluation framework for tool-using agent safety. AgentBound transforms the same executable workflow by independently varying apparent risk and action permissibility, enabling controlled comparisons of risky-looking but authorized tasks and routine-looking but unauthorized tasks. These comparisons jointly diagnose over-refusal and unsafe compliance while controlling for task competence. We instantiate AgentBound as a human-validated 4,0

---

### [140] Large Language Model Selection with Limited Annotations

**链接**: https://arxiv.org/abs/2510.09418
**作者**: Yavuz Durmazkeser, Patrik Okanovic, Andreas Kirsch, Torsten Hoefler, Nezihe Merve G\"urel
**来源**: cs.CL cs.LG
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [141] How Sensitive Are LLM Leaderboard Claims to Hidden Model Selection?

**链接**: https://arxiv.org/abs/2609.28177
**作者**: Chen Yang, Jun Chen
**来源**: stat.ML cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [142] EmailBench: A Benchmark for Evaluating LLM Agents on Enterprise Email and Productivity Tasks

**链接**: https://arxiv.org/abs/2609.31906
**作者**: Mukul Singh, Mansi Uniyal, Devin Devlin, Wen Xie, Big Thadawasin, Ritam Dutt 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Enterprise email agents must combine information retrieval, structured state changes, temporal reasoning, and multi-step coordination. Recent agent benchmarks include productivity tasks, but few center on typed email workflows in a self-contained environment. We introduce EmailBench, a benchmark of 206 email and productivity scenarios across 16 task categories. The benchmark couples a typed email API specification with provider-neutral naming, a deterministic synthetic Enron-inspired corpus, and a scenario suite whose topic selection was informed by aggregate task-intent telemetry from an interactive prototype. Its hybrid evaluation protocol combines 258 executable static assertions with 211 LLM rubrics. We evaluate eight LM configurations on a fixed single-user corpus. The best-performing configuration passes only 33.5% of scenarios despite 99.7% of its tool calls completing without an observed API failure, with pass rates varying substantially across task categories. This gap shows t

---

### [143] LLM Unlearning Evaluation with TRIAGE

**链接**: https://arxiv.org/abs/2609.32103
**作者**: Danial Ataee, Peter Triantafillou
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models can memorize private or harmful information, motivating machine unlearning methods that remove targeted knowledge while preserving other capabilities. However, existing evaluations rely primarily on behavioral benchmarks, which assess \emph{whether} a model appears to forget but provide limited insight into \emph{how} unlearning changes the model or affects related knowledge. We introduce \textit{TRIAGE} (\textit{Tripartite Representation-internal Introspection for Adjacency Gap Evaluation}), a benchmark-agnostic evaluation framework for characterizing these changes. TRIAGE uses diagonal approximations of the Fisher information and Hessian to measure changes in parameter sensitivity and local curvature, and utilizes a Forget / \emph{Adjacent-Retain} / \emph{Generic-Retain} partition to quantify an \emph{adjacency gap} in semantically related knowledge. Based on the magnitude and distribution of these changes, TRIAGE further classifies each algorithm's update as \e

---

### [144] Rethinking Training-Inference Mismatch in LLM Reinforcement Learning: Where It Arises and How to Correct It

**链接**: https://arxiv.org/abs/2609.32444
**作者**: Tianrun Yu, Kaixiang Zhao, Shangzhe Li, Yuxiao Yang, Porter Jenkins, Weitong Zhang 等 (7 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We study training-inference mismatch in reinforcement learning with verifiable rewards (RLVR) for large language models, where rollouts are sampled by an inference engine while gradients are computed by a training engine, and the two engines assign different probabilities to the same tokens. To account for this discrepancy in policy updates, we introduce calibrated importance sampling (CIS). CIS is motivated by an empirically supported logit-displacement characterization that expresses the mismatch as an additive displacement $\varepsilon_t$ in log-odds, determined by the per-logit perturbation before the softmax, whose distribution is approximately invariant to token confidence. This characterization motivates a confidence-aware truncation: large positive displacements are truncated at a single constant threshold, which maps back to an importance-ratio cap that tightens as token confidence increases. Theoretically, we show that CIS replaces the unbounded second moment that governs the

---

### [145] Agentic Search for Counterfactual Recourse under Fixed LLM Budgets

**链接**: https://arxiv.org/abs/2606.08696
**作者**: Yasuo Tabei
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [146] Pay for Hints, Not Answers: LLM Shepherding for Cost-Efficient Inference

**链接**: https://arxiv.org/abs/2601.22132
**作者**: Ziming Dong, Hardik Sharma, Evan O'Toole, Jaya Prakash Champati, Kui Wu
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [147] Characterizing Memory Misalignment in Human-LLM Interaction From User Perspectives

**链接**: https://arxiv.org/abs/2609.33623
**作者**: Jingruo Chen, Shuning Zhang, Eryue Xu, Jianing Li, Xin Yi
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> While memory enhances personalization in LLM-based conversational agents, it suffers from memory misalignment, where memories violate user expectations. We present a mixed-methods investigation to characterize and mitigate memory misalignment from user perspectives. First, we collected data from memory usage (N=28, 457 entries) and diary study (N=32, 304 reports), which yielded a taxonomy spanning 14 misalignment types across memory intake, storage and management, retrieval and interpretation stages. Second, four co-design workshops with 12 experienced HCI researchers derived a design space to tackle memory misalignment issues, consisting of 12 candidate interaction strategies structured across interaction form, placement and intrusiveness dimensions. Finally, a speed dating with 121 users reveals preference heterogeneity, where users prioritize proactive controls over cognitively demanding causal graph inspections or passive audit logs. Synthesizing these findings, we highlight the te

---

### [148] Beyond Solo and Consistency: Vindicating Multi-Agent Debate via Conditional Progressive Pruning

**链接**: https://arxiv.org/abs/2609.33974
**作者**: Ruosong Ye, Caiqi Zhang, Jiahao Li, Haijun Wu, Xiaolong Luo, Huiyuan Chen 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Model (LLM) based Multi-Agent Debate (MAD) is one of the most effective test time scaling techniques. Through multi-round communication, agents complement each other in knowledge and reasoning and solve tasks that no single member can solve. However, existing MAD frameworks fail to beat strong Single Agent and Consistency-based baselines under the same strict cost limit, which shakes the foundation of the MAD field. We propose Conditional Progressive Pruning (CPP), a lightweight pruning framework that fully exploits multi-round MAD. CPP outperforms all existing MAD frameworks on multiple dominated benchmarks. It is also the first to fully outperform consistency methods. Our code, detailed agent interaction records will be released soon.

---

### [149] TraceDance: An Automated System for Building Agent Behavior Benchmarks from Real-World Agent Deployment Traces

**链接**: https://arxiv.org/abs/2609.33295
**作者**: Dehai Min, Daoan Zhang, Yiming Zeng, Huayi Zhang, Ziyi Chen, Yan Zhang 等 (10 人)
**来源**: cs.AI cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> An agent can complete a task while exhibiting undesirable behavior during execution. Developers need tests for the specific behaviors encountered in deployment, beyond fixed benchmark suites. We present TraceDance, an agent system that constructs targeted benchmarks from deployment traces for user-specified undesirable behaviors. For efficient construction, Anchor-and-Confirm combines programmable retrieval with candidate-level confirmation by a Flash large language model (LLM), while the Anchor Synthesis Loop generates and revises specifications for custom behaviors. The benchmarks use decision-point continuation to evaluate an LLM's next turn at a recorded decision point with a behavior-specific rubric, without a reference answer or environment replay. Experiments in coding and general tool use draw on 252,557 sessions and produce 107 benchmarks with 4,125 instances, fulfilling 95.3% of build-target requests. Both human annotators confirm the requested behavior in 84% of sampled inst

---

### [150] LLM-as-a-judge validity is strongly task-dependent across physics assessment formats

**链接**: https://arxiv.org/abs/2603.14732
**作者**: Will Yeadon, Tom Hardy, Paul Mackay and Elise Agra
**来源**: physics.ed-ph cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [151] Certified Selective Automation of LLM Agent Evaluation

**链接**: https://arxiv.org/abs/2609.34320
**作者**: Chengguang Gan, Yunhao Liang, Qinghao Zhang, Shiwen Ni
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Evaluating LLM agents still ends with a human reading trajectories, because automatic judges carry no guarantee on how often they are wrong. We ask the operational question: what fraction of agent evaluation can a judge take over, with a certificate that the error rate among auto-decided trajectories stays below a budget alpha? Agent corpora resist the standard answer: many agents attempt the same tasks, so trajectories arrive in correlated clusters, and the i.i.d. certificates of existing selective-judging methods can overstate what is safe: a naive certificate can claim 98% automation while its realized error exceeds the budget in 17.5% of task resamples. We introduce a task-level bootstrap certificate that is valid in every regime we test while matching the naive certificate's coverage; finite-sample cluster-valid alternatives certify nothing at realistic task counts. Under this certificate, a 4B logprob judge trained with SFT and reject-weighted GRPO certifies 0.30-0.59 of evaluati

---

### [152] Trust the Brand, Lose Control: How Identity Hijacks LLM Agent Orchestration

**链接**: https://arxiv.org/abs/2609.32635
**作者**: Xutao Mao, Rui Qian, Linghan Chen, Yudong Gao, Junchi Liao, Jiulin Cai 等 (8 人)
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents now execute tasks end to end with permission to change real systems and increasingly orchestrate subagents that differ in capability and cost. Prior work treats the choice of subagent as an optimization problem. Yet the orchestrator makes this choice from the identities that subagents display, and an attacker can spoof them. Displayed identity thus decides operational authority, meaning who is trusted to check the work and who is allowed to change it. As a result, a risky subagent can keep authority over execution even after other evidence contradicts it. We introduce TrustFork, an LLM agent safety benchmark with 1,890 tasks and 27,826 valid trajectories across 16 agent systems. These systems run eight orchestrators under the OpenCode, OpenClaw, and Pi harnesses. In each task, one subagent carries a risky goal while the other three stay aligned with the user, so contradicting evidence can exist. A task can also change the identity a subagent displays without changing the mod

---

### [153] Semantic Prefix Oracles for LLM Decoding: Contracts and Differential Validation

**链接**: https://arxiv.org/abs/2609.35425
**作者**: Paul Kronlund-Drouault
**来源**: cs.PL cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Constrained decoding can enforce regular or context-free output formats, but many program-generation failures are semantic: scope, typing, and declaration effects depend on context. We present semantic grammar specifications, a declarative formalism that attaches such constraints to a context-free surface and executes them during Earley descent. Our implementation enforces \emph{safe pruning}: it rejects only prefixes whose semantic contradictions cannot be repaired by any continuation. A separate, grammar-dependent, \emph{dead-end freedom} property guarantees the existence of a realizable witness for each remaining branch. We give simple sufficient conditions based on surface productivity, type coverage, and left-to-right constraint flow. Our finite-lambda, core ML, and C-like fragments satisfy them, while the STLC instance used in our experiments does not: plain STLC can violate type coverage, and we show how restricting its type universe recovers it. A tokenizer-lifting lemma carrie

---

### [154] Vulcan: Instance-specialized, Verifiable Systems Heuristics Through LLM-driven Search

**链接**: https://arxiv.org/abs/2512.25065
**作者**: Rohit Dwivedula, Divyanshu Saxena, Sujay Yadalam, Eric Hayden Campbell, Daehyeok Kim, Aditya Akella
**来源**: cs.OS cs.AI cs.DC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [155] InferScale: GPU-Native KV Injection for Personalized LLM Serving

**链接**: https://arxiv.org/abs/2607.27090
**作者**: Peter Li and Prashant Pandey
**来源**: cs.DC cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [156] SoFT: Soft Targets for Generalizable LLM Fine-Tuning

**链接**: https://arxiv.org/abs/2609.32493
**作者**: Huihao Jing, Wenbin Hu, Shaojin Chen, Haochen Shi, Zhongwei Xie, Guijia Zhang 等 (10 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Distillation enables student language models to acquire new capabilities from expert teachers. However, integrating knowledge from multi-teacher, multi-domain demonstrations into a single student remains challenging. We study supervised fine-tuning (SFT) in this setting, where students must acquire diverse capabilities while maintaining generalization beyond the training tasks. Our experiments reveal varying trade-offs between in-distribution learning and out-of-distribution generalization across SFT methods, motivating more explicit control over this balance. To this end, we propose soft-target fine-tuning (SoFT) to balance learning from teacher demonstrations with retaining the Base model's existing capabilities. SoFT sets a minimum target probability for each demonstrated token while making the smallest KL change to the Base distribution. The resulting objective couples learning from demonstrations with adaptively weighted regularization toward the Base model. We further use domain-

---

### [157] The Routing Plateau: Understanding the Accuracy Limits of LLM Routers

**链接**: https://arxiv.org/abs/2606.07587
**作者**: Yifan Lu, Qiyue Zhang, Shenrun Zhang, Zhibo Yu, Zhuang Wang, Hanjie Chen 等 (7 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [158] MemAgent: Learning to Manage Heterogeneous Memory Providers for LLM Agents

**链接**: https://arxiv.org/abs/2609.32521
**作者**: Yongxian Wei, Yilin Zhao, Runxi Cheng, Xinrui Chen, Chun Yuan, Yaoru Wang 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Current agents remain largely stateless across tasks, limiting their ability to continually improve from prior interactions and making memory essential for long-horizon agentic behavior. Existing memory methods seek to reuse past experience, but most rely on a single memory representation (e.g., trajectories, reflections, skills, structured knowledge) whose effectiveness varies across task distributions. Rethinking this design space, we evaluate 13 memory methods and find that no single method generalizes across benchmarks, revealing the potential of managing heterogeneous memory providers. We formulate agent memory as a routing problem in which a memory agent decides which memory provider to retrieve from, whether to inject short-term memory, and which providers should store the resulting experience. Based on this perspective, we propose MemAgent, featuring a content-aware routing architecture and a training-data synthesis pipeline. The routing architecture combines content-aware prob

---

### [159] Inspector: Conversational and Lightweight Analyzer of Analog Circuit Layouts Using LLM and CNNs

**链接**: https://arxiv.org/abs/2609.34976
**作者**: Abril Cano Castro, Giuseppe Chiari, Michele Piccoli, Federico Viola, and Davide Zoni
**来源**: cs.LG cs.CV
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The integration of artificial intelligence into computer-aided design frameworks has sparked a shift in the design of analog integrated circuits (ICs), transitioning the field from using manual and algorithmic-based solutions to adopting automated and intelligent paradigms. In this scenario, the GDSII file represents the industry-standard database containing the ultimate and most accurate source of information of the analog circuit, encapsulating the complex physical geometries and parasitic realities that define tape out performance. This paper proposes a novel framework that combines fine-tuned LLMs and CNNs to analyze GDSII files of analog circuits, enabling a conversational interface between the tool and the designers. Experimental results using thousands of analog designs across four realistic tasks demonstrate that the proposed solution outperforms state-of-the-art general-purpose massive VLMs by a significant margin (up to 81%), thus providing a lightweight solution to the probl

---

### [160] Cartridges++: KV Cache Compression without Off-Context Derailment

**链接**: https://arxiv.org/abs/2609.35621
**作者**: Sonia Laguna, Joao Monteiro, Marco Cuturi, Pierre Ablin, Eleonora Gualdoni
**来源**: cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Serving long documents to a Large Language Model (LLM) repeatedly is expensive: computations grow with context length, and the memory footprint of the key-value (KV) cache balloons. Compressed KV (CKV) representations aim to mimic the cache of a document and are typically computed once and for all, ahead of inference time. Methods to obtain CKVs range from drop mechanisms that reduce their number of columns, to learned approaches. Among the latter, Cartridges have emerged as a leading compression method, learning compact KV representations through distillation on relevant Q/A pairs. While existing evaluations focus primarily on whether Cartridges and other CKVs yield approximately similar responses to document-related, on-context queries, we investigate the crucial deployment question of whether they can handle off-context queries, something the native KV representation is particularly good at, thanks to the mechanics of attention. We observe a fundamental trade-off: while Cartridges p

---

### [161] How Does "English (US)" Become the Default? Triangulating Structural Bias Towards American English Across the LLM Pipeline

**链接**: https://arxiv.org/abs/2604.04204
**作者**: Mir Tafseer Nayeem, Davood Rafiei
**来源**: cs.CL cs.AI cs.CY cs.ET cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [162] TULIP: Targeted LLM Unlearning at Layers Identified Per-Input

**链接**: https://arxiv.org/abs/2609.34591
**作者**: Yejin Kim, William F. Shen, Seokwon Jung, Daeun Park, Seong Joon Oh
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Representation-level unlearning intervenes on the intermediate hidden states of LLMs. Although knowledge is distributed across layers, existing methods operate at a single fixed layer for the entire forget set. We ask whether such a fixed layer is sufficient. To answer this, we design a hijacking experiment that grafts hidden states of the target model into an oracle trained only on the retain set. The oracle cannot produce the forget answer on its own, yet it produces the answer from the grafted state. Thus, the answer is formed at an intermediate layer and merely read out afterward, so unlearning should focus on formation, not readout. Moreover, the layer where formation ends varies widely across inputs. Motivated by these findings, we propose Targeted Unlearning at Layers Identified Per-input (TULIP). For each input, TULIP uses the logit lens to locate the formation-readout boundary and removes the hidden state's alignment with the forget answer's unembedding vector there. TULIP con

---

### [163] BitsMoE: Cost-Aware Bit Allocation in Spectral Space for MoE LLM Quantization

**链接**: https://arxiv.org/abs/2606.00079
**作者**: Jiayu Zhao, Zihan Teng, Minhao Fan, Tianrui Ma, Wentao Ren, Song Chen and Weichen Liu
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [164] Beyond Imitation: Reflective On-Policy Self-Distillation for LLM Reasoning

**链接**: https://arxiv.org/abs/2605.28014
**作者**: Ziqi Zhao, Xinyu Ma, Liu Yang, Yujie Feng, Daiting Shi, Jingzhou He 等 (9 人)
**来源**: cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [165] Persona Following Is Not Selective Control: The Neutrality Gap in LLM User Simulation

**链接**: https://arxiv.org/abs/2609.35036
**作者**: Jiashen Ren, Wenlin Zhang, Bohan Zhang, Xiaopeng Li, Zichuan Fu, Wanyu Wang 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Persona prompting is widely used to construct user simulations with large language models (LLMs), yet it relies on a largely untested assumption: specifying one user attribute should change that attribute alone. We test this assumption and identify a systematic failure of selective control: across all eight black-box LLMs we audit, changing a target attribute also shifts responses on unspecified, non-target attributes. For example, describing a user as more risk-seeking shifts color choices, even though the prompt never mentions color; we term this cross-attribute influence. Semantic, contextual, and internal analyses collectively suggest that models treat a persona prompt as evidence about the user and extend the inferred profile to unspecified preferences, a process we call trait-conditioned completion. We next ask whether explicitly specifying non-target attributes restores selective control. When a non-target attribute is assigned a clear direction, models generally follow the decl

---

### [166] Continuous Context Management

**链接**: https://arxiv.org/abs/2609.35540
**作者**: William Hoy, Jingxuan Fan, Nurcin Celik, Xu Pan
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-horizon large language model (LLM) agents commonly retain their complete interaction history until compaction is triggered at a predefined threshold. We study Continuous Context Management (CCM), which performs compaction at every turn to prevent interaction history from accumulating in the active prompt. At each turn, a CCM agent emits an updated memory together with an environment action; its next prompt contains the original task, retained memory, and newest observation rather than the complete transcript. We first evaluate CCM without fine-tuning on TerminalBench-2 using Claude Sonnet 4.6, Claude Opus 4.6, GLM-5, and Kimi K3. CCM substantially reduces cumulative input usage and active-prompt size, although it lowers task success for most models while preserving performance for Kimi K3. We use GRPO with privileged full-history distillation to improve CCM in open-weight models. A frozen copy of the student's initial model scores each sampled student action under the complete his

---

### [167] Once a Response, Always a Response: Detecting LLM-generated Text via Latent Prompt Restoration

**链接**: https://arxiv.org/abs/2608.05741
**作者**: Hongrui Bao, Yubing Ren, Jinhan You, Fang Fang, Shi Wang, Yanan Cao
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [168] APEXA: Execution-Integrity Enforcement for Multi-Agent LLM Automation of Synchrotron Data Reduction

**链接**: https://arxiv.org/abs/2609.24165
**作者**: Pawan K. Tripathi, Hemant Sharma, Andrew Chuang, Mathew J. Cherukara
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [169] HyperReCo: Retrieving and Connecting Evidence with Hypergraph Neural Networks for LLM Multi-hop Reasoning

**链接**: https://arxiv.org/abs/2609.32327
**作者**: Zicheng Zhao, Linhao Luo, Junnan Dong, Haoran Luo, Xiaoli Li, Shirui Pan 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) have shown strong capabilities, with retrieval-augmented generation (RAG) supporting complex multi-hop reasoning by retrieving evidence distributed across documents. Graph-based approaches exploit connections among evidence, and hypergraph-based retrieval further preserves higher-order entity associations within documents and connects documents through shared entities. However, existing hypergraph retrievers often rely on predefined structural expansion or diffusion, which may miss query-dependent interactions needed to identify relevant evidence. They also leave connections among retrieved evidence implicit, requiring LLMs to reconstruct these connections before reasoning. Therefore, we propose HyperReCo, a framework for retrieving and connecting evidence with a hypergraph neural network (HyperGNN). We represent each document as a hyperedge over its extracted entities, with shared entities connecting the hyperedges. Through hypergraph message passing with 

---

### [170] NetInjectBench: Benchmarking Indirect Prompt Injection in Tool-Using Large Language Model Agents for Network Operations

**链接**: https://arxiv.org/abs/2607.10490
**作者**: Ruksat Khan Shayoni, Muhammad Faraz Shoaib, S M Asif Hossain, M. F. Mridha
**来源**: cs.CR cs.LG
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [171] WavePP: High-Throughput Pipeline Parallel LLM Prefill under Prefix Reuse

**链接**: https://arxiv.org/abs/2609.35263
**作者**: Aaryam Sharma
**来源**: cs.DC cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Pipeline parallelism can improve prefill throughput by processing multiple request chunks concurrently across different stages of the model. However, keeping the pipeline fully utilized requires efficient scheduling and request preparation. In systems where stages retain and evict cache state independently, a local cache hit does not guarantee that the same prefix can be reused across the pipeline. Here, coordination overhead can impede request admission cadence and thus reduce overall throughput. In this paper, we present WavePP, a prefill runtime built on top of TensorRT-LLM that addresses these challenges by overlapping request admission with pipeline execution. WavePP asynchronously finds a prefix that can be reused across all stages, protects the cached state, and reserves space for the remaining input while earlier requests continue to execute. It subsequently plans the chunk sizes of each request dynamically to maximize pipeline fill. Each stage then completes the local preparat

---

### [172] NC-Bench: An LLM Benchmark for Evaluating Conversational Competence

**链接**: https://arxiv.org/abs/2601.06426
**作者**: Robert J. Moore, Sungeun An, Farhan Ahmed, Jay Pankaj Gala
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [173] Maat: Independent Deterministic Contract-Based Governance for Multi-Agent LLM Workflows

**链接**: https://arxiv.org/abs/2609.34017
**作者**: Uliana Elina
**来源**: cs.SE cs.AI cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large-language-model multi-agent systems (LLM-MAS) introduce a characteristic reliability problem: an error produced by one agent can be accepted as context by downstream agents and propagate across the workflow. Many proposed safeguards rely on learned or LLM-based judges whose verdicts are themselves probabilistic; we ask whether a deterministic layer can instead stop contract-detectable handoff defects. We present Maat, a runtime governance layer that validates agent-to-agent handoffs against a versioned workflow contract, or anchor, with no language model in the validation or scoring path. We evaluate it in six controlled domain workflows (6-15 agents, 522 trials) with injected data-level defects and a deterministic seven-check rubric. Version 1 reported gains in all six workflows (2.9-26.5%). A post-publication audit found that three benchmark scorers credited any early halt as a prevented defect. On paired trials where the governed run completed or halted on a finding attributabl

---

### [174] No Free Labels: Limitations of LLM-as-a-Judge Without Human Grounding

**链接**: https://arxiv.org/abs/2503.05061
**作者**: Michael Krumdick, Charles Lovering, Varshini Reddy, Seth Ebner, Chris Tanner
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [175] Investigating The Smells of LLM Generated Code

**链接**: https://arxiv.org/abs/2510.03029
**作者**: Debalina Ghosh Paul, Hong Zhu, Ian Bayley
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [176] Echoes of Deeds: Moral History Can Shape and Steer LLM Behavioral Choices

**链接**: https://arxiv.org/abs/2609.35070
**作者**: Lucio La Cava, Andrea Tagarelli
**来源**: cs.CL cs.AI cs.CY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Evaluations of Large Language Models (LLMs) morality typically consider decisions in isolation, thus overlooking whether an individual's unrelated prior conduct influences the model's subsequent choices. This leaves open the question of whether, and to what extent, moral history shapes LLM decisional behaviors. Prior work on human moral decision-making shows that past behavior can influence subsequent moral choices. Building on this observation, we investigate whether analogous effects emerge in LLMs in two complementary ways: at the behavioral level, through the model's observable responses, and at the representation level, through its latent internal representations. We introduce MoralLedger, a framework for studying how an actor's moral history shapes actions for LLMs' behaviors under a fixed decision context. At the behavioral level, we find that prior moral histories systematically alter subsequent choices as a function of their valence and intensity. At the internal representatio

---

### [177] Dr. MAS: Stable Reinforcement Learning for Multi-Agent LLM Systems

**链接**: https://arxiv.org/abs/2602.08847
**作者**: Lang Feng, Longtao Zheng, Shuo He, Fuxiang Zhang, Bo An
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [178] Using LLMs to Detect LLM-Generated Texts: A Cross-Generation Analysis

**链接**: https://arxiv.org/abs/2609.34691
**作者**: Haiyue Yuan, Jie Guo, Weidong Qiu, Zheng Huang, Ruizhe Li, Shujun Li
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Automated detection of LLM-generated texts (LGTs) is critical, yet dedicated detectors often struggle to generalize across domains and models. While general-purpose LLMs offer flexible zero-shot authorship classification with explanatory rationale, their detection behavior, especially regarding self-detection versus cross-detection across model generations, remains poorly understood. We systematically evaluate 15 LLMs spanning three model generations as both generators and detectors. Using a benchmark of 1,000 human-written texts and 15,000 LGTs (1,000 per model), we collected over 233,000 binary classifications alongside natural-language explanations. Our results reveal that detection efficacy is primarily driven by detector capability rather than generator provenance, although outputs from newer generators remain notably harder to detect. Crucially, statistical comparisons show no systematic advantage or disadvantage for self-detection across models. Error analysis further exposes ge

---

### [179] PersMem: Internalizing Personality into Dual-Pathway Memory for LLM Agents

**链接**: https://arxiv.org/abs/2609.34372
**作者**: Hanzhong Zhang, Ziwei Xiang, Weicheng Xie, Shizhe Liu, Siyang Song
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The profile of a role-playing agent usually depends on the pre-defined personality in a system prompt, whereas its memory processing pipeline, including prioritisation of stored memories and subsequent retrieval, remains independent of this personality. This separation causes the agent's memory processing to be inconsistent with the pre-defined personality, and makes it difficult to validate whether agent behaviours follow this personality. In this paper, we propose Personality-Integrated Memory (PersMem), which integrates personality into the agent's memory processing pipeline, making it consistently personality-dependent. PersMem processes memory using four steps, where the personality is mapped to operation-specific parameters controlling: (i) affective appraisal annotating emotion states of the user input; (ii) retention of previously stored memories along with the current input; (iii) passive affect-driven memory retrieval exploring memories similar to user input in semantics and 

---

### [180] Systematic Exploration of Multi-core Architectures for Efficient LLM Serving using WaferAI-SIM

**链接**: https://arxiv.org/abs/2510.05632
**作者**: Tianhao Zhu, Dahu Feng, Erhu Feng, Yubin Xia
**来源**: cs.AR cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [181] ForeSci: Evaluating LLM Agents for Forward-Looking AI Research Judgment

**链接**: https://arxiv.org/abs/2606.00644
**作者**: Qiuyu Tian, Haojie Yin, Hang Su, Jianghan Chao, Xiaowen Gu, Youyong Kong 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [182] Reasoning Shift: How Context Silently Shortens LLM Reasoning

**链接**: https://arxiv.org/abs/2604.01161
**作者**: Gleb Rodionov, Roman Garipov, George Yakushev
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [183] Characterizing LLM -Based Family Education through the Lens of Activity Theory: A Scoping Review of the HCI Literature

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2609.28886&hl=zh-CN&sa=X&d=1044513453446999023&ei=SJS7arCyDMKL6rQPhLm5qA0&scisig=ACTRDVHW_BG-yN1U6VXhwVs3-eYJ&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:ACTRDVEEr233VErbxroTWJ0YT-xH&html=&pos=3&folt=kw-top
**作者**: L Luo, Y Liang, J Cai, A Wang, D Pan, M Zhou 等 (8 人)
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> The third focuses on how LLM -based tools mediate relationships among family members, educational objects, and external expertise. The … rules that shape responsible LLM use in family education. This review makes three contributions to

---

### [184] Beyond Prompt or Skill? Attribution-Guided Optimization of Modular LLM Programs

**链接**: https://arxiv.org/abs/2609.32492
**作者**: Haoran Shou, Haoyue Liu, Yu Huo, Kun Zeng, Xiaoying Tang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models can solve increasingly diverse reasoning tasks, yet their performance remains highly sensitive to task prompts, intermediate instructions, and the way reusable problem-solving knowledge is incorporated. Existing optimization methods usually focus on only one part of this design space: they either optimize a monolithic prompt, or separately induce and refine skills from model traces. As a result, they lack a principled mechanism for deciding which component should be updated when failures occur, and they rarely optimize prompts, skills, and skill-use policies in a unified framework. We propose SPARO (Skill, Prompt, And Routing Optimization), a framework that jointly optimizes task instructions, reusable skill blocks, and routing rules. It performs controlled counterfactual evaluations, converts examples' effects into a probabilistic responsibility distribution over prompt, skill, and routing components, samples one component from that distribution, and applies the 

---

### [185] A Hierarchical LLM -RL Framework for Natural-Language-Guided Decision Making in MultiUAV Systems

**链接**: https://scholar.google.com/scholar_url?url=https://ieeexplore.ieee.org/abstract/document/11704707/&hl=zh-CN&sa=X&d=17667061106957428467&ei=SJS7arCyDMKL6rQPhLm5qA0&scisig=ACTRDVGNnGvJkF913dLvd6O9DkLn&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:ACTRDVEEr233VErbxroTWJ0YT-xH&html=&pos=4&folt=kw-top
**作者**: Y Li, K Li, J Zhang, Y Yuan, D Wang - IEEE Transactions on Industrial Informatics, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> The LLM Planner reasons over battlefield states and human instructions to generate high-level commands, which are then translated into … In addition, an asynchronous decoupling mechanism and a PPO-based requester are introduced to

---

### [186] Opening LLM Judges: Recovering Preference Signals Beyond the Final Verdict

**链接**: https://arxiv.org/abs/2609.32407
**作者**: Sourabrata Mukherjee, Sunayana Sitaram
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM judges are widely used to evaluate model outputs, but their verdicts can be unreliable: a judge may favor the worse answer for its position, length, or other surface features. When a judge is wrong, is the information needed to judge correctly absent from the model, or present in its internal representations but not reflected in the output? We study this across 64 open-weight evaluators and 14 datasets, including causal interventions on 41 judges (editing activations mid-run to see whether the verdict changes). On LLMBar, built so the superficially better answer is the worse one, the verdicts of 50 judges agree with human labels only 0.456 of the time, even after averaging both answer orders. Yet a small probe on the same judges' activations, with no weight updates, reaches 0.846, and 0.686 once surface features such as length and position are residualized out (0.507 with shuffled labels). The gap holds across eight benchmarks and model families, but is not universal: a score of ho

---

### [187] RRCM: Ranking-Driven Retrieval over Collaborative and Meta Memories for LLM Recommendation

**链接**: https://arxiv.org/abs/2605.07129
**作者**: Shijun Li, Pranav Belligundu, Tianxin Wei, Wooseong Yang, Yu Wang, Joydeep Ghosh
**来源**: cs.IR cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [188] Context Spanning: A Communication Framework for Full-Duplex Speech Models and External LLM Backends

**链接**: https://arxiv.org/abs/2609.33443
**作者**: Seonghyeon Go, Yongwoo Kim, Hyeonjin Cha, Jaeho Shin
**来源**: cs.CL cs.SD eess.AS
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Full-duplex spoken dialogue models can listen and speak simultaneously like the real-time dynamics of human conversation. For natural dialogue, the ability to search for external information in real-time is also an important capability. Many models remain trapped in parametric knowledge, leaving them unable to access real-time information and tool execution. Furthermore, even when Large Language Models (LLM) retrieve information, many duplex speech models process it within a compressed latent space rather than in its raw text form, which can lead to information loss from compression. To address this issue, we propose Context Spanning, a framework for information injection between a full-duplex speech model and an external LLM backend via real-time chunked prefill. The injected frame is encoded in a single forward pass inside the real-time frame budget. It feeds the retrieved information to the speech model as-is, enabling it to reason over the information independently and generate res

---

### [189] LL-CEIoT: Lightweight LLM -based Collaborative Cloud-Edge Computing for Internet of Things

**链接**: https://scholar.google.com/scholar_url?url=https://ieeexplore.ieee.org/abstract/document/11707753/&hl=zh-CN&sa=X&d=10505135547014416670&ei=SJS7arCyDMKL6rQPhLm5qA0&scisig=ACTRDVEjyxwqF2sqAYFuRzqcHHst&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:ACTRDVEEr233VErbxroTWJ0YT-xH&html=&pos=7&folt=kw-top
**作者**: MM Karim, S Khan, Q Qu - IEEE Transactions on Mobile Computing, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> To address this challenge, this paper proposes LL-CEIoT, a multi-tier cloud-edge collaborative framework that jointly optimizes lightweight LLM execution for IoT tasks. The framework incorporates quantization-aware LLM layer placement and

---

### [190] LLM sequential decision making under uncertainty in biochemical domains

**链接**: https://arxiv.org/abs/2609.33061
**作者**: Mattias Akke, Soojung Yang, Jur\'{g}is Ru\v{z}a, Sathya Edamadaka, Rafael G\'{o}mez-Bombarelli
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly used to drive scientific discovery. Understanding how LLMs make decisions from new data and memory of the literature is vital before trusting them to design experiments under tight experimental budgets. However, their decision strategies are invisible in the current performance scores used to evaluate research agents. Here, we benchmark five frontier LLMs in a Bayesian Optimization setting against published statistical baselines on seven combinatorial datasets spanning protein engineering, reaction optimization, molecular design, peptide self-assembly, and catalysis. Performance is paired with direct measurements of model beliefs and actions, enabling highly resolved behavior analysis. A prompt ablation that progressively strips context separates memorization from chemical reasoning and from bare categorical optimization. Prior chemical knowledge helps in expectation, but with high variance and occasionally even harms performance. No config

---

### [191] StraTune: Adaptive Selection of Revision Operators for Self-Evolving LLM Skills

**链接**: https://arxiv.org/abs/2609.32886
**作者**: Zeping Liu, Yan Li, Ni Lao, Gil Wolff, Gengchen Mai
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) can learn reusable textual skills from execution feedback without updating their parameters, but effectively deciding how to revise these skills remains a key challenge. Existing methods typically rely on a fixed revision operator, a search strategy and the revision forms applied under it. However, we observe that no single revision operator consistently performs best across tasks, and repeatedly applying an unsuitable operator can limit further improvement. We propose StraTune (strategy-guided skill tuning), which lets a frozen optimizer LLM choose the revision operator at every round from the optimization state, which is defined as the current execution feedback together with the recorded outcomes of earlier strategies and forms. Candidate skills from every revision operator pass one candidate evaluation, which screens for gains and regressions on a small sample set and validates them on a larger one, and every outcome is written back to the optimization 

---

### [192] Pre-registered tests of solid-state-physics-inspired LLM compression: a cluster-level negative result at small-language-model scale

**链接**: https://arxiv.org/abs/2609.34292
**作者**: Jun-qiang Lu
**来源**: cond-mat.dis-nn cond-mat.mtrl-sci cond-mat.other cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We report a three-month autonomous research-agent program testing five solid-state-physics-inspired compression mappings on pretrained language models, with predictions committed to git before any pilot data and a 3-sigma gate deciding PASS or SHELVE. The common anchor -- area-law / Kohn-nearsighted decay of the one-particle density matrix -- has a distance face (P001 Wannier, P002 tight-binding) and a rank face (P003 DMRG-truncated MLPs, P005 Wilson-RG, P011 tensor-train embeddings). P005 was pre-empted at Phase 1; three of four Phase-3 pilots were falsified. On the attention face, GPT-2-medium attention-versus-distance is best fit by a stretched exponential in 12 of 16 median-layer heads once probe padding is excluded, and a tight-binding cutoff costs +96% perplexity (P002); on Pythia-160M the Wannier sparsity 0.054 +/- 0.004 is indistinguishable from PCA, random-Haar and identity baselines (P001). On the rank face, per-token tensor-train bond dimension does not track surprisal (r = 

---

### [193] Active Causal Discovery Benchmark: Evaluating LLM Agents Under Budgeted Interventions

**链接**: https://arxiv.org/abs/2609.31675
**作者**: Sagar Deb, Devam Shah, Ashwanth Krishnan
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We introduce the Active Causal Discovery Benchmark (ACDB), an SCM-grounded environment for evaluating whether LLM agents recover causal graph structure from observations and budget-constrained hard interventions. ACDB pairs a linear-Gaussian world generator with a fixed observe-intervene-submit API and a three-layer scoring contract that separates skeleton recovery, DAG recovery, and intervention efficiency. On the current six-level ladder, PC with a greedy active orientation heuristic is the strongest non-oracle method (directed F1 42.7%, SHD 4.79), ahead of Claude Sonnet 4.6 raw active (31.7%, 7.25) and GPT-5.4 raw active (22.9%, 9.27). The most informative diagnostic is the precision-recall decomposition: PC under-commits with high precision, LLMs over-commit with lower precision, and statistical-tool access often increases abstention rather than useful intervention. A structure-blind random DAG baseline reaches 23.6% directed F1 on this dense v0 ladder; a density probe lowers this 

---

### [194] AuthorityLens: Rethinking LLM-Based Agent Systems Through the Lens of Authority

**链接**: https://arxiv.org/abs/2609.32378
**作者**: Shaojin Chen, Huihao Jing, Wun Yu Chan, Wenbin Hu, Jiaxing Li, Wu Pandy Pui Ching 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based agents are increasingly deployed with authority over consequential resources and decisions in real systems. These agents often operate alongside human and LLM-based participants who hold different forms of authority. Yet workflow roles, permission settings, and review mechanisms do not necessarily reflect the authority realized in practice. We introduce AuthorityLens, a framework for measuring a system's authority structure. Starting from an authority portfolio, we evaluate a system along three dimensions: what the system is authorized to do (System Authority), how much joint participation is required to exercise that authority (Authority Separation), and how much authority each participant holds (Principal Authority). We derive these measurements from the minimal combinations of participants sufficient to realize each outcome across admissible runtime states. We apply AuthorityLens to Codex, OpenCode, and Gemini CLI across 13 operating configurations over a common portfolio 

---

### [195] Beyond Token Savings: A Systematic Study of Context Compression in LLM Agents

**链接**: https://arxiv.org/abs/2609.32961
**作者**: Ritul Satish, Prasoon Sinha, Akiho Kawada, Neeraja J. Yadwadkar
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As LLM agents tackle longer tasks, they increasingly compress growing histories of reasoning, actions, and tool outputs. Compression can reduce token use, but it also changes the information available for later decisions. Existing agentic harnesses bundle decisions about what to compress, when to compress, and how much to remove into fixed policies. A systematic characterization is needed to disentangle these decisions and reveal how each affects task success and execution cost. We systematically vary these decisions across three open-weight models on SWE-bench Verified and Terminal-Bench 1.0. Across nearly 35,000 agent runs, we measure task success, token use, end-to-end latency, and estimated cost. We find that fewer tokens need not mean faster or cheaper execution: on Terminal-Bench with Qwen, policies using roughly one-third as many tokens can take 20-80% longer than the uncompressed agent. Policies with similar overall success can solve different tasks, while the same policy can p

---

### [196] Verification of PETSc with CIVL using LLM-generated ACSL contracts and deterministic driver generation

**链接**: https://arxiv.org/abs/2609.31687
**作者**: Hansol Suh, Jan H\"uckelheim, Stephen Siegel
**来源**: cs.CL cs.MS cs.PL cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Parallel numerical libraries such as PETSc are widely used in science and engineering applications where wrong results can have costly consequences. Despite this, numerical libraries are rarely formally verified. One of the challenges is the need for an expert to hand-write a specification and manually apply a verification tool, often requiring the development of a harness or driver, all of which can contain additional bugs that lead to false positives or false negatives during verification. With recent advancements in large language models (LLMs), it is tempting to generate such drivers and reference models automatically, but one-shot generation based on a simple prompt is brittle and leads to additional unverified code that needs to be audited. In this paper, we present an approach to use LLMs in a limited setting to generate a small, human-certifiable ACSL contract from the function's documentation, combined with a deterministic toolchain that supports a restricted ACSL profile and 

---

### [197] Epistemic Policy Divergence in Multi-Turn LLM Contamination: A Protocol-Gradient Investigation

**链接**: https://arxiv.org/abs/2609.35308
**作者**: Fahrell Giovanny, Geby Bayuningtyas, Sahrul Mukharom, and Hafiz Budi Firmansyah
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models process conversation history as unverified context: false premises injected into prior turns can be adopted as fact, a failure mode we term session-level contamination. We introduce five contamination protocols arranged along a source-authority gradient, isolating distinct failure mechanisms while holding the false premise constant, and evaluate GPT-5.4 Mini, Gemini-3.1 Flash-Lite, and GLM-4.5-Air across ten knowledge domains at temperature zero (22,500 turns), using a dual-track automated judge validated against a human gold standard (Cohen's \k{appa} = 0.901). GPT-5.4 Mini showed zero adoptions across all 500 sessions, a content-independent policy at the session level; token-level probing shows the underlying margin, while large, is finite. Gemini-3.1 Flash-Lite followed a steep authority gradient: 0.1% adoption for self-attributed falsehoods, 23.5% for user-cited sources, 68.2% for system-injected authority, and 94.0% under instruction override. GLM-4.5-Air sho

---

### [198] Large language models as judges for clinical generative AI evaluation

**链接**: https://scholar.google.com/scholar_url?url=https://www.nature.com/articles/s41746-026-03248-3_reference.pdf&hl=zh-CN&sa=X&d=10916769536562918167&ei=SJS7arGuFf3xieoP2-zEqQw&scisig=ACTRDVF3zXRBe2j1dE9jstrl8VGT&oi=scholaralrt&hist=F21tmVgAAAAJ:14380004662027926800:ACTRDVH_uKWkVPTr-oginCI6pzKc&html=&pos=0&folt=kw-top
**作者**: R Gershon, Y Ben-Shlomo, S Yitzhaki, A Sberro… - npj Digital Medicine, 2026
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Repeated runs and multi - model panels did not systematically improve alignment beyond the best single model , while binary pass/fail … While large language model (LLM) systems have demonstrated measurable benefits in lower-risk applications such as

---

### [199] Cliff Tokens: Analyzing Failure Trigger Tokens in LLM Mathematical Reasoning

**链接**: https://arxiv.org/abs/2606.25524
**作者**: Jaeyong Ko, Jinu Lee, Pilsung Kang, Yukyung Lee
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [200] CoCurve: Cross-Module Co-Pruning Curvature for Structured LLM Pruning

**链接**: https://arxiv.org/abs/2607.17568
**作者**: Zhiren Gong, Zihao Zeng, Tiantong Wang, Yixin Wang, Honoka Anada, Zijie Wang 等 (9 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [201] VEX-Bench: Benchmarking Verification Complexity of LLM-Generated Misinformation

**链接**: https://arxiv.org/abs/2609.35028
**作者**: Hanxun Huang, Yutao Wu, Qizhou Wang, Silvia Monta\~na-Ni\~no, Yige Li, Xiang Zheng 等 (10 人)
**来源**: cs.LG cs.AI cs.CL cs.CY cs.IR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) have made misinformation inexpensive to produce but not to verify, creating a growing asymmetry in the information ecosystem. Under tight time, labor, and budget constraints, media organizations, platforms, and fact-checkers rely on screening to prioritize which content to verify. We introduce VEX-Bench, a unified benchmark for evaluating the verification complexity of LLM-generated misinformation, as perceived during screening, across models and generation methods. Verification complexity is assessed along multiple dimensions derived from journalistic and fact-checking practices, capturing checkability, harm potential, source credibility signals, imposter legitimacy, and expected verification effort. We define the VEX score as an integrated measure combining elicitation yield and verification complexity to quantify how generated content consumes limited verification capacity. We construct a benchmark spanning two misinformation categories, 6 high-stakes do

---

### [202] Collaborative Principle Evolution via Evidence Transfer for Scientific Discovery

**链接**: https://arxiv.org/abs/2609.35315
**作者**: Yingming Pu and Hongyu Chen and Tao Lin
**来源**: cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Model (LLM)-based agents promise to automate scientific discovery, yet exploring the vast hypothesis space remains costly. Existing principle-evolution methods accelerate this loop, but operate sequentially, which caps exploration breadth and wastes wall-clock time on challenging problems. To address this, we formulate collaborative scientific discovery as evidence transfer between parallel principle-evolution branches. We present COEVOLVE, which realizes this transfer through a coordination core over parallel branches. By integrating value-of-information-gated routing and context-discounted likelihood injection, COEVOLVE enables branches to collaborate through shared measurements while keeping their principle posteriors separate. Across six scientific-discovery tasks under a matched evaluation budget, COEVOLVE attains a mean solution quality of 66.5% versus 57.0% for single-branch principle evolution, with a 1.80x mean wall-clock speedup on the GPT-5.6-Terra backbone; o

---

### [203] Designing Reliable LLM-as-a-Judge Measurement Systems for Multi-Turn Business Agents

**链接**: https://arxiv.org/abs/2609.33955
**作者**: Kaiwen Luo, Ming Gao
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Many LLM-as-a-judge evaluations score fixed outputs under a fixed task definition. Production multi-turn business agents instead require a maintained measurement system: correctness depends on business-specific facts and procedures, outcomes emerge across turns, and failures must be attributed to either agent capability or missing business knowledge before they are actionable. We present an integrated methodology spanning evaluation specification, modular LLM judges, intent-preserving user simulation, and human-in-the-loop governance. The specification defines conversation-level end states and actionable failure ownership. Atomic judges share versioned evidence and feed an explicit aggregation graph. The simulator is released only after task-preservation and stability checks. Independent human audits estimate measurement fidelity, renew tiered reference sets, and route disagreements to label correction, guideline revision, or judge improvement. Production studies show that system-level

---

### [204] Not Too Hard, Not Too Easy: Learning from Intermediate States for LLM Structured Reasoning

**链接**: https://arxiv.org/abs/2609.33149
**作者**: Hongbo Chen, Guohua Lu, Ting Dang, Hong Jia
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A common principle of effective learning is to practice material that is neither already mastered nor too difficult to permit progress. We ask how to apply this principle to structured reasoning tasks such as Sudoku and maze solving. In these tasks, a model can repeatedly revise an incomplete or incorrect candidate solution until it satisfies the problem's constraints. The intermediate candidate solutions along this trajectory provide natural training examples: some are already solved, some cannot yet be repaired by the model, and others lie at its current frontier of achievable progress. We therefore investigate whether pretrained language models can learn to revise such states and whether training on states at this frontier improves reasoning more broadly. To achieve this, we couple a pretrained language-model backbone with a recurrent updater that repeatedly revises an explicit solution state, using the same parameters at every update step. We further introduce Frontier-Oriented Cur

---

### [205] Nereus: Adaptive Parallelism for LLM Post-Training

**链接**: https://arxiv.org/abs/2609.34645
**作者**: Songlin Jiang, Tuo Shi, Sitong Zhang, Zeke Wang, Mario Di Francesco, Bo Zhao
**来源**: cs.DC cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reinforcement learning (RL) post-training for large language models (LLMs) coordinates multiple models across generation, inference, and training on GPU clusters. Several factors may change during a run, including resource availability, sequence length, memory pressure, and stage bottlenecks. As a consequence, an execution plan that was initially suitable can then become slow or even infeasible over time. However, adapting a job whose models share GPUs entails significant challenges: deciding whether a new plan is worth the transition cost, reusing the job's distributed state, and coordinating GPU transfers across models and stages. Nereus targets these challenges as a cost-aware runtime that adapts RL post-training jobs into efficient execution plans. Its low-overhead controller selects a memory-feasible global plan and admits the transition using a cost model calibrated against the running job. To estimate and execute a transition, Nereus represents the distributed state of each repl

---

### [206] Optimal Skill Selection for LLM Agents with Provable Bicriteria Guarantees

**链接**: https://arxiv.org/abs/2608.19993
**作者**: Yu Chen, Ruishuo Chen, Xun Wang, Zhuoran Li, Longbo Huang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [207] J-Miner: Recovering the Decision Logic of Fine-Tuned LLM Classifiers as Compact Rules

**链接**: https://arxiv.org/abs/2608.17063
**作者**: Yunfan Gao, Xinyi Huang, Tao Sheng, Haorui Song, Yun Xiong, and Haofen Wang
**来源**: cs.LG cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [208] ClinLens: Towards Long-Horizon LLM Agents for Longitudinal Multimodal Clinical Data Science

**链接**: https://arxiv.org/abs/2607.26155
**作者**: Yuan Zhu, Ethan B. Liu, Frank Nie, Wei Fan, Haibo Pu, Jindong Han
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [209] Rubric-Aware On-Policy Self-Distillation for LLM Personalization

**链接**: https://arxiv.org/abs/2609.35262
**作者**: Yilun Qiu, Xiaoyan Zhao, Chengbing Wang, Cilin Yan, Rui Zu, Wanyang Zhang 等 (9 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM personalization aims to generate responses aligned with individual users' preferences and needs. User-specific rubrics make these expectations explicit, providing direct supervision on what a satisfactory answer should cover. Existing rubric-guided approaches, however, exploit such guidance only at a coarse granularity, either by using rubrics to supervise the prediction of relevant aspects for subsequent generation or by reducing aspect coverage to a single response-level reward for reinforcement learning. This leaves a gap between specifying what a personalized answer should contain and teaching the model how to generate it. To bridge this gap, we propose GRASP, a rubric-aware on-policy self-distillation framework for LLM personalization that turns user-specific rubric aspects into fine-grained, token-level supervision. Specifically, GRASP pairs a rubric-free student with a rubric-informed teacher that additionally receives the target user-specific rubrics. By aligning their next

---

### [210] Self-Play Enhancement via Advantage-Weighted Refinement in Online Federated LLM Fine-Tuning

**链接**: https://arxiv.org/abs/2605.07977
**作者**: Seohyun Lee, Wenzhi Fang, Dong-Jun Han, Seyyedali Hosseinalipour, Christopher G. Brinton
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [211] Real-Time Hard Negative Sampling via LLM-based Clustering for Large-Scale Two-Tower Retrieval

**链接**: https://arxiv.org/abs/2607.00448
**作者**: Ivan Ji, Liuyi Hu, Harrison (Zihao) Zhao, Lei Huang, Qunshu Zhang, Max (Xiangjun) Fan 等 (7 人)
**来源**: cs.IR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [212] Pinned and Still Unstable: Within-Judge Verdict Variance and the Noise Floor of LLM-as-Judge Leaderboards

**链接**: https://arxiv.org/abs/2609.33044
**作者**: Krishna Chytanya Ayyagari
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Modern LLM evaluation assumes that pinning a judge to a fixed model snapshot and decoding at temperature zero yields reproducible verdicts. We show this assumption fails as a property of how LLM-as-Judge is operationalized on cloud serving infrastructure, not of any particular model family. Across four frontier judges all served via a single major enterprise cloud platform and three standard benchmarks (Arena-Hard, AlpacaEval 2, MT-Bench), identical inputs to the same pinned, temperature-zero judge produce different verdicts across re-runs: per-item flip rates of roughly 5% on average and about 40% on the close-call items that decide leaderboard margins, with a per-judge magnitude spanning a 40x range (from 0.13% to nearly 10%). We introduce metrics tailored to this instability: per-item flip rate, a two-part stability profile (waver fraction and conditional intensity), and adjacency separability - and report what the variance does and does not do to rankings. For a single judge the ag

---

### [213] COGNIT-Guard: Calibrated Standalone Direct-Decision Guardrails with Heterogeneous CPU-NPU Confidence Cascading under Explicit Latency and False-Positive Constraints

**链接**: https://arxiv.org/abs/2609.33671
**作者**: Hao Chen
**来源**: cs.CR cs.LG
**匹配关键词**: Foundation Models, LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> When must a foundation-model safety gateway generate tokens, and when should it directly output a calibrated decision? We study calibrated standalone direct-decision foundation models for real-time pre-ingestion safety guardrails, jointly addressing probability calibration, dual-use false-positive control, and heterogeneous CPU-NPU routing under explicit latency SLOs. Pre-ingestion guardrails must screen prompts prior to target-LLM prefill with low false alarms on benign compliance inquiries; however, shallow classifiers are brittle to phrasing shifts, hidden-state probes require coupling to a target LLM, and generative guards incur high decoding latency and dual-use false positives. We present COGNIT-Guard, coupling a validation-calibrated CPU fast gatekeeper with confidence-gated escalation to an NPU-resident 322M bidirectional direct-decision model (Laya-322M) under an asymmetric false-positive penalty. On the clean unseen DUCS-Bench test split ($N=607$), COGNIT-Guard achieves 98.85

---

### [214] NeSyFS: A Neuro-symbolic Fast-Slow Thinking Framework for LLM Agent under Partial Observability

**链接**: https://arxiv.org/abs/2607.28942
**作者**: Duo Xu, Faramarz Fekri
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [215] LLMAdBench: A Human Preference Benchmark for Advertising in LLM Responses

**链接**: https://arxiv.org/abs/2609.32533
**作者**: Rui Ai, Yuqing Liu, Sitao Qiu, Yun Qiao, Yuhan Wang, Jessica Xiwen Wang 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Inserting advertisements (ads) into consumer-facing LLM output is emerging as a new business model, but there is little shared evidence on how such ad insertion should be evaluated or how it affects user preferences. We introduce LLMAdBench, a human-preference benchmark for studying advertising in LLM-generated content. The benchmark isolates a simple but practically important decision: given a user conversation, an LLM response, and a matched advertisement, where should the ad be placed? Our dataset compares pairs of responses that differ only in ad position while holding all other conditions fixed including the user query, base answer, advertisement, and disclosure condition. Human annotators evaluate each pair based on six criteria from both advertiser's and user's perspectives. The resulting benchmark contains more than 18000 human judgments across two disclosure conditions: explicitly labeling the ad as sponsored and merging it into the response without disclosure. We use LLMAdBen

---

### [216] Easier Said Than Done: Unpacking Intent-Behavior Gap in Jailbreaking LLM-based Robots

**链接**: https://arxiv.org/abs/2412.16633
**作者**: Xuancun Lu, Zhengxian Huang, Xinfeng Li, Chi Zhang, Xiaoyu Ji, Wenyuan Xu
**来源**: cs.RO cs.AI cs.CY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [217] Symbolic Guidance for LLM Agents in Distributed Multiagent Coordination

**链接**: https://arxiv.org/abs/2609.31963
**作者**: Ben Rachmut, Ning Zhang, Yevgeniy Vorobeychik, William Yeoh
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly deployed as autonomous agents in multi-agent systems, yet their ability to reliably execute distributed coordination protocols remains poorly understood. While AgentsNet, a benchmark framework for distributed coordination among LLM agents, enables such coordination, granting full reasoning autonomy often leads to inconsistent or degraded performance in complex domains. We hypothesize that coordination can be improved by regulating agent autonomy through symbolic guidance derived from established algorithms. To investigate this, we introduce the \emph{Symbolic Guidance Taxonomy (SGT)}, which characterizes a spectrum of autonomy ranging from open-ended natural language reasoning to fully prescribed algorithmic execution, with intermediate levels providing partial pseudocode guidance. Our results show that intermediate autonomy levels consistently outperform both unguided agents and fully prescriptive specifications. These findings identify au

---

### [218] MemPoison: Bypassing Selective Memory Mechanisms to Plant Backdoors in LLM Agents

**链接**: https://arxiv.org/abs/2605.29960
**作者**: Hongtao Wang, Se Yang, Yu Chen, Puzhuo Liu
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [219] LA-CPD: Local-Evidence-Aware Change-Point Detection for Human-LLM Authorship Segmentation

**链接**: https://arxiv.org/abs/2609.33787
**作者**: Qing Yang, Zhenyu Mao, Zixiang Luo, Zezheng Wu, Xinghe Cheng, Qinggang Zhang 等 (8 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As LLM-generated text becomes increasingly human-like, accurately localizing LLM-authored spans in human-LLM co-authored documents is important for attribution and accountability in cases involving copyright infringement, fraud, and other harmful uses of AI-generated content. Sentence-level detectors provide local authorship evidence, but content variation can cause score fluctuations even among sentences from the same source, creating spurious boundaries. Recovering a coherent document partition therefore remains challenging when both the number and locations of authorship transitions are unknown. We propose Local-Evidence-Aware Change-Point Detection (LA-CPD), a structured method that transforms noisy sentence-level score sequences into coherent authorship segments. Given scores from a frozen local detector, LA-CPD combines a length-weighted within-segment residual with a windowed two-mean contrast to capture segment consistency and sustained changes around candidate cut points. Dyna

---

### [220] Demystifying Manifold Constraints in LLM Pre-training

**链接**: https://arxiv.org/abs/2605.04418
**作者**: Kang An, Jiaxiang Li, Donald Goldfarb, Shiqian Ma
**来源**: cs.LG cs.AI math.OC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [221] PulseInfer: I/O-Centric Sparse KV Cache Offloading for Efficient Long-Context LLM Decoding

**链接**: https://arxiv.org/abs/2609.34555
**作者**: Qiuyang Zhang, Kai Zhou, Kai Lu, Haocheng Lu, Jian Zhou, Yuanpeng Su 等 (9 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-context LLM serving is increasingly bottlenecked by decode, where large KV caches limit batch size and underutilize GPUs. Sparse KV cache offloading expands effective capacity by storing most historical KV blocks in CPU DRAM and recalling only selected blocks on demand. However, we find that existing offloading systems shift the bottleneck to CPU-GPU recall I/O: recall volume varies widely across layers, decode steps and requests, while headwise sparse selection fragments recalls into many small PCIe transfers. This paper presents PulseInfer, an I/O-centric sparse KV cache offloading system. PulseInfer hides variable recall latency with interruptible layer-wise scheduling, adapts offloading decisions with IO-Adaptive Offloading Admission, and coalesces fragmented transfers using SoloHead sparse selection and a gather-scatter I/O engine. Implemented on SGLang, PulseInfer improves decode throughput by up to 4.7x over SGLang and 2.6x over the best existing offloading baseline, while 

---

### [222] When Words Fall Short: Iterative Synergy Between Verbalized Reasoning and Hidden Features for LLM Confidence Estimation

**链接**: https://arxiv.org/abs/2609.34454
**作者**: Yekun Xu, Ante Wang, Jingyi Ren, Xuanyi Chen, Weizhi Ma, Yang Liu
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Confidence estimation is crucial for developing trustworthy large language models (LLMs), with most methods following estimator-based or verbalization-based paradigms. While recent research increasingly focuses on improving verbalized self-reports of confidence, we challenge the prevailing view that this approach surpasses independent confidence estimators. Our empirical study shows that a dedicated confidence estimator can substantially outperform verbalized confidence, indicating that LLMs' internal representations contain richer confidence signals. Building on this finding, we propose Iterative Policy-Estimator Training (IPoET), a framework that synergizes the complementary strengths of verbalized reasoning traces and informative representations. IPoET alternates policy optimization with estimator updating, integrating estimator-derived confidence feedback into policy learning and refreshing the estimator on new policy rollouts. Experiments across diverse datasets and Qwen and Llama

---

### [223] MASTEST: A LLM-Based Multi-Agent System For Testing RESTful APIs

**链接**: https://arxiv.org/abs/2511.18038
**作者**: Xiaoke Han and Hong Zhu
**来源**: cs.SE cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [224] Open-Qwen-Music: An Auditable Framework for LLM-Based Music Composition and Diffusion Rendering

**链接**: https://arxiv.org/abs/2609.31652
**作者**: Yangbin Yu and Mingyu Yang
**来源**: cs.SD cs.AI eess.AS
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We present Open-Qwen-Music, an open reconstruction of Qwen-Music and a fully specified research system for text-to-music generation that couples LLM-based semantic composition with diffusion-based acoustic rendering. The system comprises a 25 Hz single-codebook music tokenizer, a 3B-parameter autoregressive Music LLM, and a diffusion renderer producing 48 kHz stereo audio, following the cross-module interfaces reported by Qwen-Music. The strongest systems of this design remain closed, and prominent open music-generation projects release weights and inference code without their training corpora or end-to-end training implementations. This limits independent and controlled study of how information loss and prediction errors propagate from semantic representation through autoregressive planning to acoustic rendering. To our knowledge, Open-Qwen-Music is the first fully open release of an LLM-composition-plus-diffusion-rendering text-to-music system. Beyond model weights and inference code

---

### [225] LLM -Based NPCs in Video Games: A Systematic Mapping Study

**链接**: https://scholar.google.com/scholar_url?url=https://ieeexplore.ieee.org/abstract/document/11704098/&hl=zh-CN&sa=X&d=12006068609943059287&ei=SJS7arCyDMKL6rQPhLm5qA0&scisig=ACTRDVFYwKD2V6S0C_WnT9jcmsDB&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:ACTRDVEEr233VErbxroTWJ0YT-xH&html=&pos=2&folt=kw-top
**作者**: D Mian, J Bradbury, YG Guéhéneuc, F Petrillo… - IEEE Transactions on …, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> LLM -based NPC dialogue and behaviour across 377 records from ACM Digital Library, IEEE Xplore, and Scopus, yielding 42 papers for full analysis after applying inclusion, exclusion, and quality criteria. The review is structured around a main

---

### [226] Towards Mechanistically Understanding Why Memorized Knowledge Fails to Generalize in Large Language Model Finetuning

**链接**: https://arxiv.org/abs/2607.08393
**作者**: Lu Dai, Ziyang Rao, Yili Wang, Hanqing Wang, Hao Liu, Hui Xiong
**来源**: cs.AI cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [227] Adaptive Activation Steering for Efficient LLM Reasoning via Closed-Loop PID Control

**链接**: https://arxiv.org/abs/2506.18831
**作者**: Aryasomayajula Ram Bharadwaj
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [228] ContractBench: Can LLM Agents Preserve Observation Contracts?

**链接**: https://arxiv.org/abs/2605.17281
**作者**: Jicheng Wang, Yifeng He, Zili Wang, Hanwen Xing, Arkaprava De, Hao Chen
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [229] Prospective Interpretation Risk: Principled Communication Control Between LLMs

**链接**: https://arxiv.org/abs/2609.33885
**作者**: Wanrong Yang, Rehan Deen, Julian Ma, Yuheng Fan, Yaoyu Jin, Taher Jafferjee 等 (10 人)
**来源**: cs.MA cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agentic systems increasingly rely on models communicating with one another, yet existing uncertainty and multi-agent methods rarely estimate how a particular receiver will interpret a message before it is sent. This matters in heterogeneous systems, where capable receivers can reconstruct different tasks from the same message. We model this as a sender-receiver problem with a latent receiver type and define prospective interpretation risk (PIR): the probability that a receiver reconstructs a task other than intended. Rather than model an LLM's full input-output behaviour, we use black-box probes relating messages, intended tasks, and receiver-specific reconstructions, yielding scalable supervision while separating interpretation from downstream capability failure. Offline, heterogeneous frozen receivers provide supervision for receiver-conditioned risk and the effects of predefined mutable message features. At deployment, history induces a posterior over rece

---

### [230] SWE-Adept: An LLM-Based Agentic Framework for Deep Codebase Analysis and Structured Issue Resolution

**链接**: https://arxiv.org/abs/2603.01327
**作者**: Kang He, Kaushik Roy
**来源**: cs.SE cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [231] Rufus-Air: An Open LLM Post-Training Recipe

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2609.29421&hl=zh-CN&sa=X&d=11072849609907437950&ei=SJS7arCyDMKL6rQPhLm5qA0&scisig=ACTRDVECCF38zSbUrpUvQx893LdM&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:ACTRDVEEr233VErbxroTWJ0YT-xH&html=&pos=6&folt=kw-top
**作者**: CY Chang, R Cheng, R Feng, X Han, Y He, H Jin 等 (8 人)
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> We use no step-level or LLM judge reward; the per-task verification function is the only signal the policy is trained against. This drops two of AWM’s rewards. AWM uses an LLM judge to absorb environment imperfections that can confound a pure

---

### [232] When Do Model Internals Help? Exploring the Role of Representation Engineering in LLM Safety

**链接**: https://arxiv.org/abs/2609.34771
**作者**: Tianyi Guan, Jianhui Chen, Liangming Pan
**来源**: cs.AI cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reliable AI safeguards require both control mechanisms that reduce unsafe behavior and monitoring mechanisms that detect safety risks during model interactions. Established behavioral safeguards include alignment methods that optimize model outputs and text monitors that assess interaction text. Representation engineering instead reads or modifies internal model states, but the relative strengths of these approaches remain unclear because they are often evaluated under different settings. We present a matched evaluation across two tracks. For safety control, we compare DPO, a behavioral alignment method, with three representation steering methods across robustness, practicality, and granularity. DPO provides the strongest overall control and generally improves with increasing training data, although its safety can degrade after subsequent benign fine-tuning. Representation steering remains competitive primarily in low-data settings, particularly with high-quality contrastive data. For 

---

### [233] Attribution Gaps in Zero-Training LLM+OVOD Pipelines: A Fine-Grained Analysis of the CAAP--SNAP Discrepancy

**链接**: https://arxiv.org/abs/2609.32567
**作者**: Yu-Feng Yen
**来源**: cs.CV cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LAOD and similar zero-training LLM+open-vocabulary-detector (OVOD) pipelines score two things separately: class-agnostic localization accuracy (CAAP) and semantic naming accuracy (SNAP). The two consistently diverge, and nobody has asked why. This paper asks why, on the full 5,000-image COCO-Val split (27,273 detections) rather than the small subset the original work evaluated on. Object visual complexity turns out not to be the driver -- small and occluded objects are, if anything, localized better than large ones. Vocabulary novelty is: once the LLM's wording falls outside the detector's native category set, localization accuracy falls from 80.9% to 31.6%. That drop is not spread evenly across unfamiliar phrasing, though. Almost all of it comes from cases where the novel wording actually names a different object than the one COCO annotated (true synonyms still score 89.3%; semantically unrelated "noise" labels score 12.0%). A closer look at a further failure subset tells a similar st

---

### [234] Solving Every Step Is Not Enough: Milestone Oracles Reveal a Composition Gap in LLM Math Reasoning

**链接**: https://arxiv.org/abs/2609.32235
**作者**: Zhuohan Wang, Haoran Ma, Tianyu Wu, Yuanlin Duan, Zichun Liao, Jieming Yu
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) can solve every intermediate step of a multi-step math problem on its own and still fail the full problem, even when given a roadmap of the steps and all of their answers. We introduce OracleLadder, a diagnostic evaluation that locates where LLM math reasoning fails by giving the model increasing levels of oracle help. For each problem, a teacher model writes a fixed roadmap of intermediate sub-goals (milestones), and a deterministic symbolic verifier grades every answer. Testing the model with no help, with the roadmap, with the roadmap plus the milestone answers, and on each milestone alone sorts each failure into one of five reasoning gaps. On 354 NuminaMath problems and six models from 8B to 671B parameters (Qwen3, gpt-oss, Llama 3.3, DeepSeek-V3.1), the largest gap for every model is the composition gap, a stricter form of the compositionality gap. It covers 33-48% of problems, and 24-37% after removing problems that an LLM review flags as grading erro

---

### [235] Knowledge-Based Zero-Replay Debugging of Multi-Agent LLM Traces

**链接**: https://arxiv.org/abs/2606.14805
**作者**: Hyeonjeong Cha, Daein Weon, Dong Ho Kang
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [236] SGG-ReflAct: Sub-Goal Guided ReflAct with Structured Planning for Reliable Long-Horizon Reasoning

**链接**: https://arxiv.org/abs/2609.34548
**作者**: Jaeho Jung and Sung Hoon Jung
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent advances in reasoning backbones have empowered large language model (LLM)agentstotackle complex, multi-step tasks. However, as reasoning horizons grow, inconsistent internal beliefs induce intermediate errors that cause agents to drift from their goals. This limitation also persists in REFLACT, which reflects only on the end-goal at each step without explicitly considering intermediate sub goals. To address this problem, we propose SGG-ReflAct (Sub-Goal Guided Re flAct), a reasoning backbone that integrates sub-goals generated through a single path LLM planner into the reflection process. We further extend this framework to BeamSGG-ReflAct, which replaces the single-path planner with a beam search based LLM planner for structured plan exploration. We run experiments on ALF World, ScienceWorld, and Jericho with multiple LLM models. SGG-ReflAct out performs REFLACT in nearly all settings, achieving best success rate gains of 14.9 percentage points on ALFWorld and 8.0 percentage po

---

### [237] IndustryLLM: Failure-Driven LLM Training for Industrial Procurement

**链接**: https://arxiv.org/abs/2609.31871
**作者**: Liang Ding (Project Lead), Zhiang Xu, Yuyang Sheng, Bin Chen, Songlin Bai, Run Zhu 等 (10 人)
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Industrial procurement requires language models to bridge informal buyer jargon, sparse marketplace attributes, and authoritative engineering standards under strict safety tolerances. We present IndustryLLM, an open-weight industrial language model trained from Qwen3.5-35B-A3B-Base (35B total parameters with ~3B activated per token, with the vision encoder frozen). Rather than relying on generic text scaling, we introduce a failure-driven adaptation recipe spanning continued pre-training (CPT) and supervised fine-tuning (SFT). CPT leverages a curated ~100B-token corpus integrating 5B tokens of national standards (e.g., GB/T) and technical archives, 10B tokens of de-identified real-world industrial transaction and inquiry records, and 60B tokens of general replay. To overcome register mismatch and factual brittleness, we systematically reconstruct an estimated 20B-token domain subset via multi-register rewriting across 10 genres and 8 writing styles, confidence-routed minimal factual ed

---

### [238] TRACE: Trajectory-Based Safety Patch Learning for LLM Post-Training Realignment

**链接**: https://arxiv.org/abs/2607.16242
**作者**: Changyue Li, Jiaming He, Youliang Yuan, Jialin Wu, Boxi Yu, Zhicong Huang 等 (7 人)
**来源**: cs.LG cs.AI cs.CR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [239] Better Understanding, Better Fixes? A Study of Hallucination in LLM-based Automated Program Repair

**链接**: https://arxiv.org/abs/2609.04909
**作者**: Xuemeng Cai, Jiakun Liu, Linhan Yang, Wei Ma, Lingxiao Jiang
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [240] Model Discovery Agent: LLM-assisted Bayesian experiment design for data-efficient discovery of mechanistic world models

**链接**: https://arxiv.org/abs/2608.09696
**作者**: Kevin Murphy
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [241] Domain-Grounded Tool Orchestration for LLM-Guided Scientific Analysis

**链接**: https://arxiv.org/abs/2608.30696
**作者**: Jeff Lee, Sebastien Jourdain, Cory Quammen, Patrick O'Leary, Berk Geveci
**来源**: cs.CE cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [242] ARSM: Auto-Regressive State Machine for Agentic Reasoning Compression

**链接**: https://arxiv.org/abs/2609.32852
**作者**: Xiafeng Man, Siyuan Ye, Xiaosong Ma
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> While Large Language Model (LLM)-based agents demonstrate strong capabilities in long-horizon tasks by interleaving reasoning with external environment interactions, the continuous accumulation of context rapidly creates a critical memory bottleneck. Existing memory compression methods rely on task-specific optimization or external auxiliary models, introducing significant computational overhead. Furthermore, the resulting compressed representations tend to lose structured relationships, leading to information dilution, attention collapse, and degraded decision consistency. To address these limitations, we propose Auto-Regressive State Machine (ARSM), a lightweight training-free framework that enables in-situ reasoning compression through structured state evolution. ARSM introduces two key components: (i) a trajectory abstraction mechanism that reorganizes interaction histories into compact Hypothesis-Action-Result (HAR) micro-chains; (ii) a dynamic state machine that regulates hierarc

---

### [243] QuanReview: Offline, Auditable Reconciliation of Human and LLM Span Annotations

**链接**: https://arxiv.org/abs/2609.35685
**作者**: Matteo Musacchio, Juan Cruz Giner Pulero, Isabel Casta\~neda, Naomi Couriel, Yelena Mejova, Mariano G. Beir\'o 等 (7 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Structured span annotations, such as quantities with their units, uncertainty modifiers, and event classes, are expensive to create and hard to keep trustworthy once language models enter the loop. We present QuanReview, an open-source system for auditing and correcting such annotation layers. QuanReview aligns two annotation streams over the same documents at character level, resolves unambiguous cases by an explicit and logged policy, and routes candidate conflicts to a browser-based adjudication interface where reviewers accept either side, build field-level hybrids, or flag items for re-annotation. A campaign manager assigns documents to multiple annotators with configurable redundancy, computes agreement at document and span level, auto-merges unanimous documents, and exports the corrected layer in the original file format, so that it can replace the original annotation files directly. Applied to a 4,457-record humanitarian benchmark and an LLM extraction stream, the system fully 

---

### [244] WeaveMark: Robust and Scalable Multi-bit LLM Watermarking via Coded Payload Spreading

**链接**: https://arxiv.org/abs/2609.02177
**作者**: Gang-Hyun Park, Ju-Hyeong Lee, Hee-Youl Kwak, Dae-Young Yun
**来源**: cs.CR cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [245] SubZero+: Memory-Efficient Adaptive Zeroth-Order LLM Fine-Tuning in Random Subspaces

**链接**: https://arxiv.org/abs/2608.15665
**作者**: Ziming Yu, Shuyao Xiao, Xingyu Zhao, Sike Wang, Pan Zhou, Peiyu Zang 等 (9 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [246] GraphHCA: Closed-Form Hindsight Credit Assignment for Long-Horizon LLM Agents

**链接**: https://arxiv.org/abs/2609.35084
**作者**: Haodong Zhu and Yangyang Ren and Changbai Li and Sheng Xu and Linlin Yang and haiguang liu and Baochang Zhang
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Group-based reinforcement learning (RL) has advanced large language models (LLMs) and is increasingly extending to agentic tasks, where sparse terminal rewards make step-level credit assignment essential. Existing methods assign credit from what follows an action in sampled rollouts, but do not explicitly capture its retrospective relation to the realized outcome. Hindsight credit assignment (HCA) instead attributes credit through the ratio of hindsight to behavior-policy probabilities, but estimating the hindsight distribution requires an auxiliary model or an extra pass. To address this estimation bottleneck, we propose GraphHCA, a model-free realization of HCA that eliminates explicit hindsight-distribution estimation. For terminal-goal tasks with deterministic transitions, Bayes' rule reduces the hindsight ratio to a ratio of behavior-policy success probabilities at consecutive states. Taking logs yields a state-wise success potential, whose increment across a transition provides s

---

### [247] AutoPDEBench: Benchmarking LLM Auto-Research for Neural PDE Solver Design

**链接**: https://arxiv.org/abs/2609.32245
**作者**: Ruoyan Li, Wei Wang, Yizhou Sun
**来源**: cs.CE cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Partial differential equations (PDEs) are essential for modeling complex physical systems, and neural solvers have recently emerged as powerful data-driven tools for numerically solving them. However, existing neural solvers struggle with domain-specific challenges, such as varying parameters and high-speed flows, necessitating specialized architectures. Manually designing these specialized solver architectures is a highly iterative, time-consuming process requiring deep expertise, creating a significant bottleneck in scientific discovery. We propose leveraging autonomous AI research agents to automate the synthesis of specialized solvers. To support this, we introduce AutoPDEBench, a benchmark dedicated to LLM-driven automated research for PDE solver design. The benchmark includes 25 challenging datasets featuring both novel and actively studied physical scenarios. We evaluate a suite of general-purpose models (transformer, ROM, and graph-based) alongside a multi-agent instantiation o

---

### [248] GLIDE: Generalized Layer-wise Intrinsic Distributional Evaluation for Heterogeneous LLM Agents

**链接**: https://arxiv.org/abs/2609.32295
**作者**: Wei Zhu, Yiming Wang, Rui Wang, Lixing Yu, Kun Yue, Zhiwen Tang
**来源**: cs.AI cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents require reliable step-level evaluation to compare candidate branches and allocate computation effectively. However, lightweight evaluation remains challenging. External verifiers introduce additional inference cost, while agent-produced confidence or self-evaluation scores can be miscalibrated, especially when candidates are generated by heterogeneous agents. We propose \textbf{G}eneralized \textbf{L}ayer-wise \textbf{I}ntrinsic \textbf{D}istributional \textbf{E}valuation (\textbf{GLIDE}) for LLM agents. \textsc{GLIDE} derives intrinsic step evidence from layer-wise residual coherence, which measures whether local residual updates consistently support the global residual change induced by a candidate step. It calibrates this evidence against the recent score distribution of the generating agent and converts it into a pessimistic reward that jointly accounts for absolute residual evidence and agent-relative standing. The reward provides a cross-agent value signal for MCTS bra

---

### [249] SkillFocus: Evolving Agent Skills via Capability Decomposition

**链接**: https://arxiv.org/abs/2609.34397
**作者**: Ning Wang, Zhiren Gong, Bingdong Li, Peng Yang, Aimin Zhou
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Agent skill evolution seeks to improve reusable procedural guidance for large language model (LLM) agents through iterative revision. Existing methods base each revision mainly on execution trajectories or feedback, leaving recurring behavioral requirements across tasks implicit and tying revision to the behavior of the current skill. We introduce SkillFocus, which decomposes recurring task requirements into a capability space that remains fixed as the skill evolves, separating what tasks require from how the current skill behaves. SkillFocus maps current task outcomes to this space to identify the capability that leaves the most tasks unresolved, then uses that capability to determine what to revise and which evidence to use. Across four benchmarks spanning heterogeneous tasks, SkillFocus achieves the best held-out accuracy on all four, outperforming the strongest competing result by 5.7 points on average while using 24\% fewer evolution tokens on average than the closest iterative ba

---

### [250] The Trace Is the State: Exact Credit Assignment for LLM Agent Teams

**链接**: https://arxiv.org/abs/2603.06859
**作者**: Yanjun Chen, Yirong Sun, Hanlin Wang, Jinghan Wang, Xinming Zhang, Xiaoyu Shen 等 (8 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [251] Muon Sublates the Edge of Stability in LLM Pretraining

**链接**: https://arxiv.org/abs/2609.34915
**作者**: Yanzhe Chen, Qifang Zhao, Xiaoxiao Xu, Fanghui Liu
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Muon is increasingly used for language-model pretraining, yet its large-step dynamics are not captured by the classical edge-of-stability (EoS) picture of gradient descent (GD). In GD, loss neutrality, equal-magnitude update reversal, and marginal stability meet at a single learning-rate-dependent edge. We show that Muon breaks this coupling. For stochastic no-momentum Muon, we derive a coherence-corrected conditional loss-neutral boundary $2\rho_b/\eta$, while temporal alignment follows a separate geometry. Controlled experiments show that loss balance and temporal alignment respond differently to learning rate and batch size. Across our language model experiments, the 130M Llama-like LLM runs exhibit loss-boundary tracking with weak negative alignment, whereas the studied 1B LLM configuration shows stronger partial cancellation; in both settings, directions remain far from coherent reversal while training continues to improve. These results support a split EoS picture for Muon: a sto

---

### [252] SAGE: Structured Strategic Reasoning for Efficient LLM Game Playing

**链接**: https://arxiv.org/abs/2609.34342
**作者**: Zhiwei Chen and Tianchun Wang and Zhongtao Rao and Haiming Zhu and Ding Cao and Tianxiang Zhao
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A strong LLM strategic agent should reason prospectively over uncertain futures, adapt its strategy to opponents' behavioral tendencies, and continuously recalibrate its decision process from interaction experience. However, incorporating these sources in free-form reasoning could lead to unsupported strategic assumptions, inconsistent opponent estimates, and harmful interference from irrelevant historical interactions. To address these issues, we propose SAGE, a training-free inference-time framework that structures LLM strategic reasoning around three coordinated operations: anchor, adapt, and recalibrate. SAGE first anchors reasoning to an equilibrium policy that provides a strategically valid prior. It then conditions deviations from this anchor on a soft belief over opponent behavioral tendencies, enabling opponent-specific exploitation. Finally, SAGE distills strategically related interactions into counterfactual hypotheses about previously missing considerations, allowing past e

---

### [253] Spexis: Speculative Lookahead Scheduling for LLM Inference

**链接**: https://arxiv.org/abs/2609.34370
**作者**: Hyungyu Jung, Jaehyeok Yu, Hoonseo Choi, Sungkyun Kim, Jinho Lee, Jiwon Seo
**来源**: cs.LG cs.DC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Spexis is a multi-GPU LLM inference framework that improves the efficiency of pipeline and tensor parallelism through speculative parallelism. Rather than using speculative decoding only to accelerate token generation, Spexis runs speculation in parallel with normal execution, introducing a new parallelism axis without increasing KV-cache memory usage. This improves memory efficiency and helps mitigate the bottlenecks of multi-GPU inference. Spexis further uses lookahead scheduling to predict speculation quality and future memory pressure, allowing it to reduce wasted speculation, KV-cache eviction, and recomputation. Built on top of vLLM, Spexis largely improves serving performance across a range of GPU configurations, achieving speedups of up to 34% over a baseline that uses the optimal combination of pipeline and tensor parallelism. Spexis's source code is publicly available at https://github.com/mlsys-seo/spexis.

---

### [254] AquiLLM: Evaluating Faithfulness in Open-Weight RAG-LLM Systems for Scientific Research

**链接**: https://arxiv.org/abs/2609.16519
**作者**: Bernie Boscoe, Srinath Saikrishnan, Vikram Seenivasan, Jack Stark, Andrew Lizarraga, Morgan Himes 等 (9 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [255] ReScraper: Unified Scraping and Cleaning of Web Data for Effective LLM Pretraining

**链接**: https://arxiv.org/abs/2609.34287
**作者**: Zichun Yu, Jiarui Yan, Shlok Sanghvi, Nihar Atri, Chenyan Xiong
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM pretraining corpora are normally cleaned by a stack of hand-written heuristics. A heuristic scraper extracts the main content from HTML, and dozens of rule-based filters then clean it, so corpus quality is capped by the coarseness and accuracy of the rules. In this work, we propose ReScraper, a unified language model of only 0.6B parameters that replaces this entire stack. To train ReScraper, we carefully curate supervised data from the outputs of three teacher models, so it learns to first extract the main content from raw data and then choose among four operations: keeping the page as extracted, editing out noisy lines and spans, deleting it entirely, or rewriting it when it is poorly written but informative. Based on the same crawled data pool, pretraining 400M, 1.4B, and 2.8B models on our curated data improves the DCLM Core score by a relative 3.8--4.7% over the strongest baseline at each scale, including the costly multi-agent curation. Our analyses show that each operation p

---

### [256] Internalizing Curriculum Judgment for LLM Reinforcement Fine-Tuning

**链接**: https://arxiv.org/abs/2605.11235
**作者**: Han Zheng, Yining Ma, Karthick Gunasekaran, Bharathan Balaji, Zheng Du, Shiv Vitaladevuni 等 (7 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [257] AutoDojo: A Generative Benchmark for Evaluating Prompt Injection Defenses in LLM Agents

**链接**: https://arxiv.org/abs/2606.15057
**作者**: Xinhang Ma, Taoran Li, Chaowei Xiao, Zhiyuan Yu, Ning Zhang, Yevgeniy Vorobeychik
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [258] Automated Species Identification in Camera Trap Images for Wildlife Conservation

**链接**: https://arxiv.org/abs/2609.35420
**作者**: Nowshin Amin, Nafisa Tabassum Oyshi, Tahmid Abrar Zidan, Miftaun Noor, Md. Abrar Rahman Shafin
**来源**: cs.CV
**匹配关键词**: Large Language Model, Multimodal Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Wildlife conservation involves protecting, preserving, and managing wildlife species and their habitats. With today's rapid pace of human development, climate change, and other unsustainable practices, the need for wildlife conservation has heightened. Despite significant progress in species identification using deep-learning models, significant challenges still remain in effectively detecting small animals in low-contrast trap images due to limited feature extraction capabilities. This thesis presents a novel end-to-end framework integrating a self-attention mechanism to address these limitations. The proposed architecture involves a Swin-BiFPN backbone integrated in a Faster RCNN detection network, coupled with a visual semantic extraction module driven by the LLaVA v1.5 (13B) multimodal large language model. The detection framework, capable of extracting crucial features in challenging trap images, demonstrates consistently high results and robust generalization capabilities. Furthe

---

### [259] LLM-Guided Ontology-Driven Knowledge Graph Construction from Unstructured Text

**链接**: https://arxiv.org/abs/2609.31663
**作者**: Abdelhadi Belfadel, Maxence Gagnant, Joseph Kattan, Sana Tmar
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Ontology-driven knowledge graph construction from industrial text remains challenging due to the domain specificity of documents, the scarcity of annotated resources, and the complexity of ontology engineering workflows. This paper presents and investigates the applicability of an ontology learning pipeline that combines compact open-source Large Language Models (LLMs), reusable prompting strategies, and open knowledge bases to support the extraction, structuring, enrichment, and evaluation of knowledge from textual corpora. The approach is tested and evaluated on a private French corpus of power-grid incident reports, using locally deployable open-source LLMs ranging from 7B to 32B parameters. Starting from unstructured reports, the approach extracts entities and relations, generates RDF triples, constructs related OWL ontology, enriches it using external knowledge sources, assesses the quality of the ontology, and subsequently constructs a populated knowledge graph grounded in the re

---

### [260] Unbiased Top-$k$ Estimation for On-Policy Distillation

**链接**: https://arxiv.org/abs/2609.34447
**作者**: Linjian Meng, Siyuan Gan, YuHan Li, Xiran Wang, Ziyang Ding, Ditang Gou 等 (8 人)
**来源**: cs.CL cs.LG stat.ML
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> On-policy distillation (OPD) is becoming an important component of large language model (LLM) post-training for transferring the reasoning capability of a strong teacher LLM to a weaker student LLM. OPD trains the student by minimizing the reverse KL divergence between the teacher and the student via rollouts generated by the student's policy. However, estimating the gradient of the reverse KL divergence in OPD remains a challenge. Using only the sampled token from the student-generated rollout is computationally cheap but provides limited distributional supervision, which will degrade accuracy. In addition, using the full vocabulary provides complete distributional supervision but is computationally expensive. Therefore, recent works propose Top-$k$ OPD (TK-OPD) that use selected top-$k$ tokens, which provides richer distributional supervision than sampled-token estimation at substantially lower computational cost than full-vocabulary estimation. Unfortunately, using only the selected

---

### [261] NovelAPIBench: Diagnosing How A Code LLM Learns to Use Novel APIs

**链接**: https://arxiv.org/abs/2606.03657
**作者**: Jinnuo Liu, Yue Peng, Jinhan Niu, Hongyi Wen
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [262] CSI-Agent: LLM-Assisted Few-Shot Adaptation for Cross-Domain Wi-Fi CSI Sensing

**链接**: https://arxiv.org/abs/2609.31990
**作者**: Tianya Zhao, Chuan Liu, Xuyu Wang
**来源**: cs.AI cs.NI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Wi-Fi channel state information (CSI) has enabled device-free sensing applications such as human activity recognition. However, CSI sensing models remain brittle in cross-domain deployment, where changes in users or environments can produce incorrect predictions. Existing solutions usually treat this problem as an offline model-design problem, by pretraining a stronger representation or applying one fixed adaptation method to the entire target domain. In practice, labeled target data are scarce and different classes may fail in different ways under the same domain shift. To address this, we propose CSI-Agent, an evidence-seeking LLM agent that reformulates cross-domain CSI adaptation as a deployment-time decision-making problem. Rather than processing raw CSI or making sample-level predictions, CSI-Agent summarizes target-domain behavior into sensing-grounded class-level evidence. It establishes a strong target-adaptive default from complementary CSI views and uses an LLM planner to de

---

### [263] Recursive LLM Degradation in Biomedical Question Answering: A Cross-Generation Study

**链接**: https://arxiv.org/abs/2609.34257
**作者**: Bibek Bhandari, Kshitij Lingthep
**来源**: cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Repeatedly training language models on their own generated data may create a synthetic-data feedback loop in which errors and distributional biases are reintroduced into subsequent training datasets. This paper studies that process in biomedical question answering (QA) using PubMedQA and two Qwen2.5 model sizes, 0.5B and 3B parameters. The study compares a recursive synthetic-data condition, in which generation G(k+1) is trained on answers produced by G(k), against a Human-Control condition that repeatedly uses the original human training data. The study evaluates across four generations from G0-G3 with two random seeds (42 and 123) and a fixed evaluation set of 1,000 expert-labeled samples. The evaluation includes disease and chemical entity F1, context-supported rate, lexical and semantic similarity, answer length, repetition rate, and other evaluation metrics. The Recursive condition for both model sizes and both seeds showed larger declines than the Human-Control condition in disea

---

### [264] AgentStream: How Well Do Self-Evolving LLM Agents Perform Under Streaming Tasks?

**链接**: https://arxiv.org/abs/2608.00155
**作者**: Dong Yan, Jian Liang, Dapeng Hu, Ran He, Nicholas Jing Yuan, Qi Zhang 等 (7 人)
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [265] On the Behavioral Traits of LLM Agents

**链接**: https://arxiv.org/abs/2609.32776
**作者**: Haokai Zhao, Jie Gao, Yunze Xiao, Xintao Wang, Weihao Xuan, Aditya Joshi 等 (8 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Users increasingly describe different AI agents as distinct colleagues to work with. AI personality research aims to quantify such impressions by attributing human-like "traits" to agents. However, existing measures fall short: models' self-reports (S-data) diverge from their actual behavior, while informant ratings from LLM judges (I-data) are costly to scale and cover few everyday scenarios. In this paper, we propose A-B-D to infer traits bottom-up from behavioral data (B-data), namely how agents act on their environment and communicate with users, as recorded in existing trajectories. From 345,667 real-world trajectories spanning 80 models, 12 tasks, and 50 harnesses, we extract 318 candidate features that capture both the actions an agent takes at each step (functional) and the language accompanying them (linguistic). We retain only features that show instance-level stability, cross-task consistency, and model discriminability. Factor analysis of the remaining 79 features uncovers 

---

### [266] Theory of Scene: Breaking the Symmetry Trap in Multi-Agent LLM Coordination

**链接**: https://arxiv.org/abs/2609.32939
**作者**: Liangqi Yuan, Wenzhi Fang, Shiqiang Wang, Christopher G. Brinton
**来源**: cs.LG cs.CL cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-agent systems built on large language models (LLMs) are largely homogeneous, as their agents behave alike even across distinct LLMs. We show that when such agents act concurrently without communication, they collide on targets they must split and diverge on targets they must take together, a double failure we term the symmetry trap. Theory of Mind (ToM), widely used for coordination without communication, cannot escape this trap, since homogeneous agents form the same prediction of one another and respond to it in the same way. We propose Theory of Scene (ToS), a training-free reasoning schema in which each agent reads its public role, the only difference between the agents, and the task context they all observe. Homogeneous agents thereby derive one division of labor, each taking the part its role fixes, which turns homogeneity from the cause of the trap into the cure. ToS reads the role together with the scene through role gating, which determines whether ownership overlaps or 

---

### [267] Knowing When to Critique: Task-Adaptive Metacognitive Regulation for Reliable LLM Reasoning

**链接**: https://arxiv.org/abs/2507.15015
**作者**: Xinmeng Hou, Ziting Chang, Zhouquan Lu, Bohao Qu, Liang Wan, Wei Feng 等 (8 人)
**来源**: cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [268] Prioritizing Repeated LLM Evaluation for Hidden Failure Discovery

**链接**: https://arxiv.org/abs/2609.32547
**作者**: Keita Broadwater, Akin Broadwater
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models are commonly evaluated by generating a small number of stochastic responses for each prompt in a benchmark. Because inference budgets are limited, this shallow evaluation may fail to observe low-probability but operationally important failures. A prompt that produces no failures in a small sample may therefore appear reliable despite having a nonzero latent probability of failure under repeated inference. We formulate LLM reliability evaluation as a budget-constrained discovery problem in which each prompt is associated with an unknown per-generation failure probability. We propose a budgeted discovery framework that first performs shallow evaluation across the prompt set and then uses trial-level failure outcomes together with prompt-derived representations to learn a feature-based ranking of failure propensity. The resulting scores prioritize prompts with zero observed shallow failures for deeper evaluation, concentrating the deep-evaluation budget where hidden 

---

### [269] MeqMuon: Matrix-Equilibrating Muon for LLM Pretraining

**链接**: https://arxiv.org/abs/2609.35701
**作者**: Chang-Wei Shi, Xu Wang, Wu-Jun Li
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The success of large language models (LLMs) has been accompanied by continued growth in model size and pretraining costs. Muon offers high accuracy and training efficiency in LLM pretraining. Recent work introduces row-wise normalization into Muon to balance update magnitudes and improve pretraining performance. However, row-wise normalization alone cannot accommodate different imbalance patterns in update matrices. In this paper, we propose an improved Muon optimizer, called \underline{m}atrix-\underline{eq}uilibrating Muon~(MeqMuon), for LLM pretraining. MeqMuon balances both row and column magnitudes through normalization that can be automatically tailored to different imbalance patterns without manual intervention. Moreover, MeqMuon eliminates the need to store AdamW's second-moment estimates, reducing optimizer-state memory usage. Empirical results demonstrate that MeqMuon achieves better convergence performance than AdamW, Muon, and other baselines in LLM pretraining.

---

### [270] PrefillShare: A Shared Prefill Module for KV Reuse in Multi-LLM Disaggregated Serving

**链接**: https://arxiv.org/abs/2602.12029
**作者**: Sunghyeon Woo, Hoseung Kim, Sunghwan Shim, Minjung Jo, Hyunjoon Jeong, Jeongtae Lee 等 (10 人)
**来源**: cs.LG cs.DC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [271] An Inspectable LLM Council for Multi-Model Research Answer Aggregation

**链接**: https://arxiv.org/abs/2604.02923
**作者**: Shuai Wu, Xue Li, Yanna Feng, Yufang Li, Zhijun Wang, Ran Wang
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [272] Toward AI-Assisted Poultry Coccidiosis Diagnosis: Evaluating Gemini and BiomedParse on Eimeria Microscopy Images

**链接**: https://arxiv.org/abs/2609.31679
**作者**: Ali Alsalama, Ahmed Kubba, Manar Abu Talib
**来源**: cs.CV cs.AI
**匹配关键词**: Large Language Model, Multimodal Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Coccidiosis caused by Eimeria parasites is a major economic burden in poultry production, and effective control depends on accurate species-level diagnosis. This study evaluates whether a general-purpose multimodal large language model can support such diagnosis. Google Gemini was assessed on 4,225 mi- croscopy images covering the seven fowl-infecting Eimeria species under two prompting conditions, one without candidate labels and one with a predefined class list, and was further tested for pathology-report generation, while BiomedParse was examined for parasite segmentation. Without candidate labels, the model produced broad and taxonomically inconsistent outputs. With candidate labels, overall accuracy reached only 14.9%, with a strong bias toward E. tenella at 74% and no correct classifications for E. acervulina, E. mitis and E. praecox. Generated treatment reports were coherent but unverified, and segmentation was only partial. Current multimodal models are therefore not yet reliab

---

### [273] LLM Bidders Preserve the Mechanism-Level Orderings of Human Bidders

**链接**: https://arxiv.org/abs/2507.09083
**作者**: Anand Shah, Kehang Zhu, Yanchen Jiang, Jeffrey G. Wang, Arif K. Dayi, John J. Horton 等 (7 人)
**来源**: cs.GT cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [274] "You're Right, Let Me Fix It": How LLM Agents Damage Correct Work When Falsely Accused

**链接**: https://arxiv.org/abs/2609.32616
**作者**: Xutao Mao, Rui Qian, Longxiang Wang, Xinjian Yi, Mingxuan Li, Linghan Chen 等 (9 人)
**来源**: cs.AI cs.CR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents increasingly keep working after a task succeeds as they resume after compaction or take over handoffs. Their finished work keeps receiving follow-up input that sometimes falsely accuses it for later failures. We call an agent's acceptance of such a false accusation gaslight sycophancy, and destructive over-correction when acting on it damages previously correct work. We introduce CAVE-Bench, a benchmark of 365 agentic tasks across six domains built around opaque tasks. Every scored run first reaches a verified correct state, whose supporting rationale and history stay in the workspace while the facts that would settle the accusation lie in external or runtime state beyond the agent's reach. The agent cannot confirm or refute the claim with a local check, so the right response should keep the work and ask for the missing evidence. Each task either hands the agent correct work with saved evidence or let it build and verify that work first, and five risk factors set how the acc

---

### [275] Representation Alignment as a Bottleneck in LLM-Based Retrosynthesis Planning

**链接**: https://arxiv.org/abs/2609.35571
**作者**: Hyunwoo Yoo, Cassie Huang, Haebin Shin, Li Zhang, Gail L. Rosen
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> While LLMs show promise in general reasoning, symbolic planning in chemistry remains a bottleneck. Direct ''SMILES-to-PDDL'' attempts fail because they force models to juggle chemical analysis and planning-language structuring simultaneously. We hypothesize that this failure stems from a lack of intermediate abstractions rather than insufficient model capacity. By decomposing retrosynthesis into molecule mapping, reaction mapping, and PDDL generation, we achieve high success rates where end-to-end approaches fail. This provides evidence that a primary bottleneck lies in representation alignment rather than raw model capacity. Our structural analysis demonstrates that intermediate representations are essential in retrosynthesis planning, highlighting the importance of representation-centric design in future systems.

---

### [276] Fair Fact-Checking: Closing the Cross-Lingual Gap in LLM Factual Judgement with RoSh

**链接**: https://arxiv.org/abs/2609.34678
**作者**: Muhammad Ahmad, Fatemeh Seyedin, Adrian Weller, Dongwon Lee, Mahmoudreza Babaei
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Misinformation on social media remains a critical problem, and more and more people settle it by asking a language model instead of a fact checker. Whether models judge such claims reliably is debated; whether they judge them equally well in every language people ask in has gone almost unasked. We test eight models from five families, 3B to 70B, on 1,500 encyclopedic factual claims that exist in identical form in eight languages. English is judged better than every other language on every model, and the gap is widest on the smallest ones, where Llama-3B on Arabic is no better than guessing. Existing remedies retrain on more multilingual data or fit an unconstrained map between language representations, and neither asks whether the model already holds the answer and simply fails to say it. It largely does: a linear probe recovers the truth from the very activations the model fails to express. We propose RoSh, a per-language shift and rotation of the residual stream, computed in closed f

---

### [277] SQLStructEval: Structural Evaluation of LLM Text-to-SQL Generation

**链接**: https://arxiv.org/abs/2604.06736
**作者**: Yixi Zhou, Fan Zhang, Zhiqiao Guo, Yu Chen, Haipeng Zhang, Preslav Nakov 等 (7 人)
**来源**: cs.CL cs.DB
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [278] Remember by Asking: Retrieval-Induced Memory Evolution for LLM Agents

**链接**: https://arxiv.org/abs/2609.34438
**作者**: Wanqi Zhou, Jiawei Lu, Yang Wang, Zhaolong Xing, Zhen Chen, Ai Han 等 (7 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-term memory is essential for language agents to maintain coherent and effective behavior over extended, multi-session interactions. Existing memory systems mainly use retrieval at read time, while write-time memory formation still relies on direct extraction or compression. However, when future information needs are unknown, compressing an entire interaction in one pass can overlook locally important details that may matter later. To this end, we introduce RIME, a retrieval-induced memory framework that shifts memory construction from monolithic compression toward evidence-centered integration. RIME uses generic self-questions to retrieve focused dialogue evidence and grounds memory formation in both the retrieved evidence and relevant historical memories, which are jointly reconciled into an evolving memory bank with temporal and provenance information. At inference time, compressed memory serves as the primary rather than the sole source of evidence: when it cannot support an an

---

### [279] Understanding the Synergy between SFT, RLVR, and OPD in LLM Post-Training

**链接**: https://arxiv.org/abs/2609.31900
**作者**: Emre Can Acikgoz, Yang Li, Zeyu Leo Liu, Srijan Bansal, Dilek Hakkani-T\"ur, Shafiq Joty 等 (7 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Modern LLM post-training composes supervised fine-tuning (SFT), reinforcement learning with verifiable rewards (RLVR), and on-policy distillation (OPD) into multi-stage pipelines, yet these stages are typically designed and evaluated in isolation. We show that this composition is consequential: a stage that improves the current model can make the next stage less effective. Through controlled experiments with Qwen3 models on math and science reasoning, we first characterize OPD across nine student-teacher pairs spanning 2x to 53x parameter ratios and show that OPD effectiveness depends on student-teacher compatibility rather than teacher scale alone. The surrounding stages of OPD reshape this compatibility in three ways: (1) A brief SFT warm-up improves subsequent OPD, while an RLVR-strengthened student regresses under distillation from the same teacher. (2) Adapting the teacher with RLVR raises downstream OPD accuracy in proportion to the capability it adds. Following these two interve

---

### [280] GroupMask: Layer-Adaptive Group-wise Sparsity for Semi-Structured LLM Pruning

**链接**: https://arxiv.org/abs/2609.33977
**作者**: Zhengao Li, Shuoqiu Li, Xiaofang Zhang, Yukai Jin, Gokcen Kestor, Yanfu Zhang 等 (10 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Semi-structured pruning compresses large language models (LLMs) while keeping a regular sparse structure, but the prevailing N:M pattern fixes the same local sparsity ratio in every layer. Layer-adaptive sparsity allocation improves unstructured pruning, yet it has been reported to be less effective under N:M sparsity, leaving open whether adaptive allocation is of limited value for semi-structured pruning in general or only under the fine-grained N:M pattern. We examine this question with group-level sparsity, which partitions each weight matrix into regular groups, retains or prunes each group as a whole, and allows each layer's sparsity ratio to vary under a global budget. We propose GroupMask, which generates the group selectors of all layers with a lightweight hypernetwork, relaxes them with a Gumbel-Sigmoid parameterization and a straight-through estimator, and learns them through sparsity-budget regularization and self-distillation while keeping the pretrained weights frozen. On

---

### [281] ArGuard Shared Task: Harmful Content Detection in Arabic Memes and LLM Prompts

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2609.29349&hl=zh-CN&sa=X&d=15732924064362652556&ei=SJS7arCyDMKL6rQPhLm5qA0&scisig=ACTRDVEucfE_--Lw8wUKHlgFdz4d&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:ACTRDVEEr233VErbxroTWJ0YT-xH&html=&pos=1&folt=kw-top
**作者**: F Alam, MR Biswas, MB Kmainasi, AE Shahroor… - arXiv preprint arXiv …, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> ArGuard is a shared task on harmful content detection in Arabic memes and LLM prompts. It includes two tracks: Track A focuses on multimodal hate detection in Arabic memes, while Track B addresses harmful prompt detection for Arabic LLM

---

### [282] Improving LLM Collaboration via Multi-Agent Preference Learning

**链接**: https://arxiv.org/abs/2609.32827
**作者**: Shuo Liu, Xinzichen Li, Tianle Chen, Christopher Amato
**来源**: cs.AI cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Several works have explored multi-agent reinforcement learning (MARL) in LLM collaboration. However, constructing reliable rewards is difficult in practice, as complete and accurate metrics are often unavailable and hard to aggregate. Preference learning provides an alternative by learning from comparative human or AI feedback. Yet, its extension to multi-agent systems remains underexplored. To address this gap, we formulate preference-based multi-agent systems (MAS) from decentralized and centralized collaboration perspectives. We also introduce a general multi-agent preference learning framework (MAPL) to solve these problems. MAPL allows iterative updates by comparing the current solution with decentralized or centralized solutions generated by various agents. We instantiate MAPL using MARL from human feedback (MARLHF) with a learned reward model and multi-agent direct preference optimization (MADPO). Experiments on collaborative writing, coding, tool use, and travel planning show t

---

### [283] A Cheap Verifier is Good Enough: LLM Post-training is Robust to Erroneous Rewards

**链接**: https://arxiv.org/abs/2609.33467
**作者**: Andreas Plesner, Curtis Northcutt, Francisco Guzm\'an, Anish Athalye
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> When post-training large language models on tasks with semi-verifiable rewards, there are many factors (training steps, base model size, training order, data quality, verifier accuracy, etc.) that practitioners must contend with to maximize model performance. Yet, it remains unclear how well verifier agreement predicts post-training performance on such tasks. In this paper, we explore this question with over 11k H100 GPU-hours, across HealthBench and PRBench tasks in medical, legal, and finance domains. Across the tested domains, Qwen3 trainees (1.7B-8B on HealthBench; 8B on PRBench), evaluation splits, and frontier LLM reference judges (which we call golden verifiers), higher verifier agreement does not consistently identify the best training verifier. Expensive verifiers need not outperform inexpensive ones, and open-weight Gemma verifiers produce strong training outcomes. We compare two low-cost choices retrospectively -- a cost-reducing choice and a balanced choice -- with estimate

---

### [284] The Router Within: Eliciting Native Skill Routing from a Frozen LLM

**链接**: https://arxiv.org/abs/2609.15982
**作者**: Ruishuo Chen, Xun Wang, Yu Chen, Zhuoran Li, Longbo Huang
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [285] Agent Safety From Within: Detecting Harmful Trajectories from LLM Internal States

**链接**: https://arxiv.org/abs/2609.33039
**作者**: Difan Jiao, Ashton Anderson
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Language model agents can now perform sophisticated sequences of actions via tools and harnesses, which has increased the scope of the damage they can cause. Guard models, however, are mainly built for content moderation and thus are not well-suited to detecting this agentic risk. To address this, we proceed by first conducting a representational analysis, then use the resulting insights to build a solution. In our analysis, we focus on two types of trajectory-level agentic harms: harmful content, which is expressed directly, and unsafe tool use, which depends on whether an action is consistent with the interaction that produced it. We investigate how open-source guard models represent these two types of harm and find that they are linearly readable inside the model, even though guard models predict no better than chance on pairs that differ only in the called tool's schema. The two harm types also follow nearly orthogonal internal directions, and neither reliably serves as a proxy for

---

### [286] DPS: Dual-Mode Precision LLM Serving with Semi-Unified Memory

**链接**: https://arxiv.org/abs/2609.34380
**作者**: Xuan Truong Nguyen, Tien Son Pham, Tuan Duc Chu, Wookeun Jung, and Thanh Tuan Dao
**来源**: cs.DC cs.AI cs.ET cs.PF cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Existing LLM serving systems virtualize and optimize KV-cache memory, but treat model-weight memory as fixed throughout execution. Recent work on multi-precision model representations challenges this design by allowing a single stored model to support both full-accuracy and lower-precision execution, making the effective weight footprint runtime-dependent. This creates an opportunity under bursty workloads, where temporary spikes in KV-cache demand often determine throughput and SLO compliance. We present DPS, a dual-precision LLM serving system that turns weight memory into an elastic resource: under normal load, DPS serves the full-accuracy model; under KV pressure, it switches to a nested, lower-precision variant and repurposes unused weight memory for KV cache blocks. DPS is built on Semi-Unified Memory (SUM), which partitions the weight region into a persistent lower-precision sub-region and a shared region that alternates between residual weight tensors and KV-cache blocks, prese

---

### [287] SAGE: Symbolic Action-Gating and Editing for LLM Task Planners

**链接**: https://arxiv.org/abs/2609.34268
**作者**: Trung Minh Bui, JongSul Moon, YoungOuk Kim, Quang-Ngoc Phung, Se-Woong Jun, Dongin Shin
**来源**: cs.RO cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are now the default cognitive core of embodied household agents, yet the plans they emit are rarely checked against a grounded model of the environment before execution, and the task-success they report is often measured on benchmarks so saturated that no method can be separated from another. We present SAGE (Symbolic Action-Gating and Editing), a single-LLM planner built from two lightweight mechanisms: a domain-agnostic symbolic gate (~250 lines of Python, zero tokens, $O(|\pi|)$) that blocks precondition-violating actions with typed reasons as a runtime safety monitor, and a local edit that regenerates only the failed sub-goal's suffix, keeping completed and untouched work intact; a hybrid seed+live memory store supports cold-start coverage. We evaluate under a leak-free protocol (leave-one-out retrieval) over five open-weight models and a 75-task AI2-THOR benchmark. On the standard benchmark goal-completeness saturates (52% of instances trivially solved

---

### [288] The Interplay of Harness Design and Post-Training in LLM Agents

**链接**: https://arxiv.org/abs/2606.25447
**作者**: Kyungmin Kim, Youngbin Choi, Seoyeon Lee, Suhyeon Jun, Dongwoo Kim, Sangdon Park
**来源**: cs.LG cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [289] From Attack Success to Attack Severity: Counterfactual Memory Attacks on LLM Agents

**链接**: https://arxiv.org/abs/2609.34132
**作者**: Mingxi Zou, Langzhang Liang, Zhuo Wang, Yiyang Zhao, Lizhen Qu, Zenglin Xu
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As LLM agents increasingly rely on persistent memory for long-horizon and personalized behavior, they can retain and reuse information across interactions, but this also creates a lasting channel through which malicious memory writes can influence future behavior. Persistent-memory attacks are typically evaluated by whether they succeed, yet successful attacks can leave persistent states with substantially different downstream consequences. We study this severity as a distinct attack-design objective and formalize it with counterfactual memory regret (CMR), the paired increase in expected downstream loss relative to clean memory. We introduce MemHarm, which predeclares a finite class of sparse, grounded semantic edits, evaluates candidates through the normal agent memory interface using offline paired-loss feedback, and certifies resolved selections within that class. Compared with attack-success optimization, CMR-guided selection produces substantially larger downstream loss while ret

---

### [290] Understanding Quantization of Optimizer States in LLM Pre-training: Dynamics of State Staleness and Effectiveness of State Resets

**链接**: https://arxiv.org/abs/2603.16731
**作者**: Kristi Topollai, Anna Choromanska
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [291] Budget-Aware LLM Discovery via Cost-Calibrated Frontier Utility

**链接**: https://arxiv.org/abs/2607.26828
**作者**: Yansen Zhang and Yilu Liu and Tianyu Liu and Jiamin Chen and Xiaokun Zhang and Kai Xie and Qingfu Zhang and Xue Liu and Yiyan Qi and Chen Ma
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [292] QwenGyre: An Elastic Reinforcement Learning Framework for Training xLong-Horizon Agents

**链接**: https://arxiv.org/abs/2609.33848
**作者**: Weiqi Wang, Yuxin Zhou, Mouxiang Chen, Siyuan Zhang, Yi Zhang, Yuyan Luo 等 (10 人)
**来源**: cs.LG cs.DC
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents increasingly undertake extreme-long (xlong) horizon tasks, where a single execution can span hours, hundreds of model--environment interactions, and nearly 1M tokens per rollout. Applying online reinforcement learning (RL) to such executions poses two fundamental challenges: (1) severe execution variance and prolonged rollout delays cause massive GPU idling; and (2) complex non-linear branching generates massive trajectory redundancy, crippling training efficiency. To address these, we presents QwenGyre, an end-to-end framework for xlong-horizon online RL. QwenGyre elastically reallocates GPUs between rollout and training without interrupting live executions, while its trajectory processor reconstructs branching histories, scores partial progress, and deduplicates redundant paths to bound training costs. Scaled to our flagship model, Qwen~3.8 2.4T, with 700K tokens per rollout, QwenGyre yields a 6.0% absolute gain on NL2RepoBench (52.5% $\to$ 58.5%) in

---

### [293] ScAn-Bench: Evaluating Scaling Analysis Methodology

**链接**: https://arxiv.org/abs/2609.35707
**作者**: Artin Sermaxhaj, Nastaran Alipour, Donat Sinani, Johannes Hog, Neeratyoy Mallik, Jenia Jitsev 等 (7 人)
**来源**: cs.LG
**匹配关键词**: Foundation Models, LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent progress in machine learning is driven by large-scale foundation models, where scaling laws and finding optimal scaling prescriptions for architecture, data, and hyperparameters are key in advancing the state-of-the-art. Therefore, it is surprising that no systematic study evaluates the methodology to obtain scaling laws and prescriptions across different model types. To shed light on this crucial blind spot and facilitate future research, we introduce the surrogate benchmarks ScAn-Bench-LLM and ScAn-Bench-VLM based on 4524 and 8024 checkpoints of language and vision-language model pipelines. On our benchmarks, we perform the first systematic evaluation of both data acquisition and extrapolation methodology for scaling analysis across different data modalities.

---

### [294] M3OS: A Monte Carlo Graph Search-Orchestrated Multi-Agent LLM System for Evidence-Traced Molecular Optimization

**链接**: https://arxiv.org/abs/2609.34491
**作者**: Junjie Wang, Yaowei Jin, Ruohui Tang, Guonan Cui, Haojie Wang, Penglei Wang 等 (10 人)
**来源**: cs.LG q-bio.BM
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Small-molecule optimization integrates medicinal-chemistry reasoning and computational evidence through iterative, multi-objective decisions. When large language models (LLMs) reason over optimization histories stored primarily in conversational context, they must recover candidate identities, prior evaluations, and task constraints to guide subsequent decisions. We present M3OS, a multi-agent LLM system that decouples molecular-design reasoning from optimization-state management through Monte Carlo graph search. A persistent graph links evaluated candidates, parent-child transformations and evaluation evidence, while rewards and visit statistics guide LLM-assisted parent selection. Two branches combine tool-driven candidate generation with knowledge- and case-guided medicinal-chemistry editing. An execution harness controls graph updates through structured output extraction, molecular validation and task-bound evaluation. Agents receive role-specific contexts, while the graph preserve

---

### [295] Share-Borne AI Virus: Memory-Hopping Attacks Across LLM Agents

**链接**: https://arxiv.org/abs/2609.35576
**作者**: Sidharth Pulipaka, Ansh Sharma, Stanislau Hlebik, Leonidas Raghav, Vyas Raina, Ivaxi Sheth 等 (7 人)
**来源**: cs.AI cs.CL cs.CR cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models are increasingly deployed as stateful assistants that retain information across interactions and use tools to read, modify, and create persistent artifacts. As these artifacts are shared between users, they form an indirect communication channel between otherwise independent assistants. We study a failure mode in which this channel enables self-propagating attacks. We introduce artifact-mediated propagation, where adversarial content introduced through an artifact (e.g. a report), is stored in an assistant's persistent memory, reproduced in a subsequently created artifact, and acquired by another assistant that later reads it. We evaluate this process in temporal human-agent universes that model artifact exchange between independently operated assistants over time, measuring whether an attack survives successive hand-offs, how many hops it reaches, and how broadly it spreads. We find that attacks can propagate across multiple independent assistants and persist ove

---

### [296] FlexQuant: Elastic Quantization Framework for Locally Hosted LLM on Edge Devices

**链接**: https://arxiv.org/abs/2501.07139
**作者**: Yuji Chai, Mujin Kwun, David Brooks, Gu-Yeon Wei
**来源**: cs.AI cs.PF
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [297] When Valid Tool Calls Change Meaning: Formation-Consistent Dispatch for LLM Agents

**链接**: https://arxiv.org/abs/2609.35088
**作者**: Geonwoo Kim (1), Brent ByungHoon Kang (1) ((1) Korea Advanced Institute of Science and Technology (KAIST))
**来源**: cs.AI cs.CR cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tool-enabled agents form calls from model-visible interfaces, while hosts later select their implementation. Standard dispatch omits the descriptor-handler relation. An unchanged and schema-valid call can therefore acquire a different security effect during rollout, reconnect, or delayed approval. We call this failure schema-epoch drift. We present formation-consistent dispatch (FCD), which connects implementation analysis to execution authority. Reviewed profiles produce provenance-bound over-approximations of declared in-scope effects from official source. Under a closed-target approval policy, a verifier applies each formed call to a summary and captures a successor only when its effects fit the call's security contract. Atomic admission and a final-hop fence preserve this decision to the effect. The exact source retains priority, and the captured successor becomes eligible only after source retirement. Stock releases and deployment changes reproduced the failure. Four profiles cove

---

### [298] A Benchmark for LLM's Understanding of Middle School and High School Science Topics

**链接**: https://arxiv.org/abs/2609.32020
**作者**: Noah L. Schroeder, Yessy Eka Ambarwati, Yuji Zhang, ChengXiang Zhai
**来源**: cs.AI cs.CY cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly integrated into educational settings, yet educators lack robust, standards-aligned tools to evaluate their effectiveness in K-12 science contexts. Existing benchmarks predominantly assess general language or advanced scientific reasoning, leaving a critical gap in understanding LLMs' performance on content directly relevant to secondary science curricula. To address this gap, we developed a comprehensive NGSS-aligned benchmark for both middle and high school science using a rigorous synthetic data pipeline, multi-judge validation, and item-level psychometric analysis. Nine open-weight LLMs were systematically evaluated using this benchmark, indicating that several smaller, locally deployable models achieved high accuracy across diverse science domains and question types. Our findings indicate that model size did not consistently predict performance, emphasizing the importance of intentional model selection for educational deployment. We the

---

### [299] AIM-ZO: Activation-Informed Subspace Maintenance for Zeroth-Order LLM Fine-Tuning

**链接**: https://arxiv.org/abs/2609.35257
**作者**: Yue Xie, Zhi Zheng, Yunpeng Ba, Xuyang Wu, Xialiang Tong, Zhichao Lu 等 (8 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Zeroth-order (ZO) optimization offers a memory-efficient alternative for LLM fine-tuning by estimating updates only from forward evaluations of perturbed parameters, without backpropagation or activation storage. However, in billion-parameter LLMs, isotropic perturbations often waste many forward evaluations on weakly informative directions. To make these evaluations more informative, existing ZO methods restrict perturbations to low-dimensional subspaces. Yet the quality of these subspaces is critical: overly compressed or poorly maintained spaces can miss useful update directions. To obtain a high-quality subspace for ZO updates, this paper proposes AIM-ZO, a ZO fine-tuning method based on Activation-Informed Subspace Maintenance. AIM-ZO uses forward activations as local directional information and continuously integrates them into a broad, evolving subspace over training. To access broader gradient-relevant structure while keeping individual perturbations low-dimensional, AIM-ZO act

---

### [300] EMIR$^2$: Evolution-Aware Memory with Intent-Guided Multi-Round Retrieval

**链接**: https://arxiv.org/abs/2609.32584
**作者**: Jinlan Liu, Hongliang Sun, Yong Wang, Bolin Zhang, Dinabo Sui, Dianhui Chu 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-term memory enables large language model (LLM) agents to leverage historical interactions for future tasks. However, existing memory systems struggle to utilize continuously evolving historical information, as they often rely on static memory representations and single-round retrieval strategies, failing to track factual changes or integrate distributed evidence across long-term interactions. To address these challenges, we propose \textsc{EMIR}$^{2}$, an \textbf{E}volution-Aware \textbf{M}emory framework with \textbf{I}ntent-Guided Multi-\textbf{R}ound \textbf{R}etrieval, enabling LLM agents to maintain evolving historical knowledge and adaptively retrieve relevant evidence. Specifically, \textsc{EMIR}$^{2}$ constructs a State-Evolving Memory Graph (SEMG) that represents long-term memory as evolving knowledge states supported by temporal event trajectories and evidential associations. By maintaining semantic states through evidence-based updates, SEMG preserves historical evoluti

---

### [301] Towards Inclusive Toxic Content Moderation: Addressing Vulnerabilities to Adversarial Attacks in Toxicity Classifiers Tackling LLM-generated Content

**链接**: https://arxiv.org/abs/2509.12672
**作者**: Shaz Furniturewala, Arkaitz Zubiaga
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [302] PrefixGuard: Online Failure Warning and Trace-Grounded Diagnosis for LLM Agents

**链接**: https://arxiv.org/abs/2605.06455
**作者**: Xinmiao Huang, Jinwei Hu, Qisong He, Rajarshi Roy, Changshun Wu, Yi Dong 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [303] SenseAgent: An LLM Agent for Adaptive Cross-Domain IMU Sensing

**链接**: https://arxiv.org/abs/2609.32000
**作者**: Tianya Zhao, Chuan Liu, Xuyu Wang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Deep learning has improved inertial measurement unit (IMU) sensing for mobile and wearable applications. However, an IMU model trained in one domain often becomes unreliable when it is used with a new user, device, or body position. Existing methods usually treat this problem as a static model-design task: they pretrain a stronger representation, add data augmentation, or select one adaptation method before deployment. In practice, the target domain is only gradually observed, labels are scarce, and different domain shifts require different sensing actions. This paper presents SenseAgent, an LLM-guided sensing agent for cross-domain IMU activity recognition. Instead of asking an LLM to classify raw IMU signals, SenseAgent uses the LLM as a runtime planner over sensing tools, source-domain experience memory, online target memory, and verifiers. The agent builds a label-free diagnosis report from the target stream and uses it to decide whether to keep raw inference or invoke specialized 

---

### [304] Faithful Activation Verbalization: Reducing Hallucinations in LLM Representation Interpretation

**链接**: https://arxiv.org/abs/2609.34033
**作者**: Haiyan Zhao, Zirui Hei, Wei Shi, Huiqi Deng, Na Zou, Mengnan Du
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Activation verbalization methods such as Activation Oracle and Natural Language Autoencoders decode hidden representations of large language models into human-readable natural language. However, existing methods can produce incomplete or hallucinated descriptions, making their activation verbalizations difficult to trust and use reliably in practice. To this end, we introduce AVPO, a two-stage framework that first reconstructs source text from a hidden activation and then evaluates the resulting text with a separate frozen question-answering model, yielding an explicit and inspectable intermediate readout. We further optimize the inverter with direct preference optimization (DPO), using rewards that capture both semantic recoverability and lexical fidelity. Across six text families, AVPO improves gist- and detail-level information recovery over the strongest baseline by up to 17.1 and 9.3 percentage points, respectively. Crucially, the gains arise from preference optimization rather th

---

### [305] Would You Walk to the Car Wash? Salience Bias in LLM Commonsense Reasoning

**链接**: https://arxiv.org/abs/2607.28478
**作者**: Zheng Wu and Chenhao Xue and Shijie Zheng and Yijie Lu and Cheng Yang and Zhuosheng Zhang
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [306] MASTraceBench: Diagnosing Collaboration Gains through Proposal Trajectories in LLM-Based Multi-Agent Systems

**链接**: https://arxiv.org/abs/2609.34496
**作者**: Yapeng Li, Songze Li, Shuang Yu, Jing Yu, Zhixin Liu, Liqiang Wen 等 (7 人)
**来源**: cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based multi-agent systems (MAS) have shown promise in complex problem solving. As MAS methods diversify, systematic evaluation becomes increasingly challenging. However, existing benchmarks largely focus on final outcomes, leaving unclear how collaboration gains arise, are preserved, or are lost. To address this limitation, we introduce MASTraceBench, a benchmark for diagnosing collaboration gains through proposal trajectories in MAS. Across six cooperative and competitive tasks, MASTraceBench tracks and grades proposal trajectories and provides a multi-layer metric suite covering Task Score, Collaboration Gain, proposal-trajectory indicators, and Token Cost. Using MASTraceBench, we systematically compare representative MAS methods not only by final performance, but also by how agent proposals evolve and are aggregated into the final answer. This analysis reveals a recurring pattern: final MAS answers rarely surpass the strongest initial proposal; interaction often lifts initially 

---

### [307] Greenpixie's AI Token Methodology: Assessing the Energy, Water and $\mathrm{CO_2\text{-}eq}$ Impact of AI Tokens for Open and Closed Weight Models

**链接**: https://arxiv.org/abs/2609.33965
**作者**: Joshua Horswill, Ross Hunter, Matt Clifford, James Hall
**来源**: cs.CY cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We describe a methodology for estimating the per-token energy cost of cloud-hosted large language model (LLM) inference, separating between input (prefill) and output (decode) tokens. Graphics processing unit (GPU) energy usage is measured during inference benchmarking with open-weights models on a wide range of text-based tasks. The remaining server energy contribution from non-GPU hardware is estimated from the inference wall time. Bayesian linear regression is used to model the relationship between energy per token and LLM size, request traffic, and hardware deployment configuration. Proprietary frontier LLMs of unknown size and deployment are binned into size buckets based on naming conventions and performance priors, and the space of possible LLM configurations is sampled with Monte-Carlo methods to give a representative average energy per token and uncertainty. We also describe how these energy measurements can be used to estimate the carbon-dioxide equivalent ($\mathrm{CO_2\text

---

### [308] Overwhelmed by Choice: Studying LLM Decision Making at Scale

**链接**: https://arxiv.org/abs/2609.32809
**作者**: Yu-Chi Lin, Aryan Seth, Anshul Aravind, Eugene Lee, Tanmay Parekh, Nanyun Peng 等 (7 人)
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multiple-choice and candidate-selection evaluations are widely used to assess LLM reasoning and decision-making, yet most benchmarks contain relatively small candidate sets. It remains unclear whether conclusions drawn from these settings remain valid as the candidate space scales. We systematically evaluate LLMs as the number of competing candidates increases and find substantial accuracy degradation across tasks, prompting strategies, and model scales. Controlled analyses show that standard long-context retrieval explanations cannot fully account for this degradation. Instead, we identify two systematic failure patterns. First, gold-margin collapse: the score gap between the correct answer and the strongest distractor progressively shrinks, driven primarily by weakening confidence in the correct answer. Second, earlier candidate preferences become increasingly difficult to overturn, with later candidates exerting progressively weaker influence on the final prediction. Motivated by th

---

### [309] AG-CoT: Verified Algorithmic Traces for LLM Program Synthesis on Clifford Circuits

**链接**: https://arxiv.org/abs/2609.33192
**作者**: Lu Wei, Yufeng Wang, Chenfeng Cao, Lu Pang, Haibin Ling
**来源**: cs.LG cs.CL quant-ph
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Scientific code generation can produce executable programs that fail to compute the intended scientific object. We study this problem in language-model synthesis of Clifford circuits, which prepare the stabilizer states used in quantum error correction and admit exact classical verification. In our target-conditioned framework, each target is given as compact signed stabilizer generators, and an exact verifier checks the generated OpenQASM circuits. We supervise models with Aaronson-Gottesman chain-of-thought (AG-CoT) traces checked by the verifier, and continue training on model generations that the verifier accepts. Across two independently trained model families (3B and 7B), AG-CoT supervision multiplies greedy-decode state-equivalence accuracy by four to six times over circuit-only baselines, and verifier-filtered continuation training adds a further consistent gain atop both. A complementary 32B study shows that supervised models achieve near-perfect syntax and Clifford validity w

---

### [310] FlowState: Execution State as Memory for Long-Horizon LLM Agents

**链接**: https://arxiv.org/abs/2609.34565
**作者**: Minghao Li, Bangyan Li, Zifan Wang, Yulong Li, Hu Xu, Gan Zhang 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-horizon tasks require LLM agents to continually draw on information from earlier interactions. However, retaining the full history increases context costs, while compressing it risks losing details needed later, and the relevance of historical information often becomes apparent as the task progresses. To address these challenges, we propose FlowState, which treats execution state as memory that can be retained and revisited across requests, unifying current decision-making with the reuse of historical information. FlowState preserves semantically typed state nodes, their relations, and references to raw tool observations, separating persistent retention from on-demand access. Within a single execution loop, Incremental State Update (ISU) maintains the current state based on new inputs and feedback, while Progressive State Access (PSA) progressively reveals historical states and supporting evidence as needed during reasoning. Together, these mechanisms enable agents to reassess pri

---

### [311] IMC-CLINIC: Coupled Loss-Informed Newton Iterations for Clipping in Analog In-Memory Computing

**链接**: https://arxiv.org/abs/2609.35586
**作者**: Yung-Chin Chen, Chia-Yu Chen, Naveen Verma
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Analog in-memory computing (IMC) offers a promising path toward energy-efficient large language model (LLM) inference by executing matrix multiplications (MatMul) directly within memory arrays in the analog domain. Its efficiency, however, comes with an additional source of error: limited-precision analog-to-digital converters (ADCs) quantize accumulated analog partial sums, introducing output-side error distinct from conventional activation and weight quantization at the MatMul inputs. Clipping can mitigate both operand and ADC quantization errors, but the optimal clipping factors must jointly balance activation rounding and clipping, weight rounding and clipping, and ADC quantization. Existing clipping methods, designed for digital quantization, do not explicitly optimize these coupled sources of IMC error and often rely on costly search-based calibration. We introduce IMC-CLINIC (Coupled Loss-Informed Newton Iterations for Clipping), a clipping calibration framework based on an anal

---

### [312] Porimon: An LLM-Based Pok\'emon Battle Agent Enhanced by Long/Short-Term Knowledge Augmented Generation

**链接**: https://arxiv.org/abs/2609.32544
**作者**: Dongyin Zhuo, Fengjunjie Pan, Nenad Petrovic, Alois Knoll
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In this paper, we use Pok\'emon Battles as a case study to investigate how to improve the performance of LLM-based agents in tasks that require opponent-aware planning without additional fine-tuning. We propose Long/Short-Term Knowledge Augmented Generation (LSTKAG), a mechanism that enables LLM-based agents to leverage past states of the current task and retrieve experience summaries from similar previous task instances based on the current state. Based on LSTKAG, we design Porimon, an LLM-based agent structure for Pok\'emon Battles. For optimization, we introduce an external API for precise damage calculation and more detailed information about the game. We conduct tournament-like evaluation experiments comprising 15,000 battles for hyperparameter optimization, ablation studies, and performance evaluation. The results indicate that Porimon-based players with hyperparameter optimization significantly outperform players based on Pok\'eLLMon, an LLM-based agent structure proposed in pre

---

### [313] Waggle: Learning One Anonymous Local Law for Self-Organizing LLM Swarms

**链接**: https://arxiv.org/abs/2609.34136
**作者**: Mingxi Zou, Wei Zhu, Zhuo Wang, Langzhang Liang, Zhiwen Tang, Yinghui Xu 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As LLM agents increasingly collaborate on complex tasks, how to organize their interactions becomes a central design question. Existing multi-agent systems typically learn or adapt explicit roles, hierarchies, routing policies, or communication topologies. We shift the learning target to a reusable local law that can be shared across interchangeable agents and adapt coordination as populations or interaction conditions change, without redefining a global organization. We introduce Waggle, a shared anonymous policy over bounded local views that jointly selects task actions, semantic communication, and local commitment updates. Repeated execution of the same law allows coordination to form, persist, and reorganize online without explicit roles or global topology. To learn this law across interchangeable agents and evolving coordination, we develop Swarm-Consistent Distillation (SCD), combining anonymous-orbit consistency with rollout-grounded prediction of the next local coordination fie

---

### [314] Fresh Memory, Stale Plans: Derivation Currency for Distributed LLM-Agent Memory

**链接**: https://arxiv.org/abs/2609.03340
**作者**: Evan Chen, Shiqiang Wang, Christopher G. Brinton
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [315] ReLoop: Structured Modeling and Behavioral Verification for Reliable LLM-Based Optimization

**链接**: https://arxiv.org/abs/2602.15983
**作者**: Junbo Jacob Lian, Yujun Sun, Huiling Chen, Chaoyu Zhang, Hanzhang Qin, Chung-Piaw Teo
**来源**: cs.SE cs.AI cs.LG math.OC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [316] AgentHabit: Characterizing Distinct Behaviors of Agents on Everyday Tasks

**链接**: https://arxiv.org/abs/2609.32795
**作者**: Woojung Song, Hoyeol Yang, Jeonghoon Shim, Sungjib Lim, Jonggeun Lee, Yunho Choi 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents assist users with everyday tasks that can be completed in many reasonable ways. Even when their answers are useful, how agents carry out these tasks may not match users' preferences and needs. For example, agents differ in whether they ask clarifying questions or search the web. We introduce HABIT, a taxonomy of 23 behavioral axes in five categories, which three authors and three LLMs derive bottom-up from 408 agent trajectories across 17 domains. On held-out tasks, HABIT distinguishes models more clearly than existing taxonomies of human values and agent actions while supporting comparably consistent annotation. Building on HABIT, we construct AgentHABIT, a benchmark that profiles each agent's behavioral tendencies from its trajectories on 86 everyday tasks. Profiling 18 models with AgentHABIT reveals a range of distinctive tendencies. For example, most GPT and Claude models state their assumptions and offer alternatives when requirements conflict, wh

---

### [317] SceneScaffold: Active Scene-State Construction for Unified 3D Scene Understanding

**链接**: https://arxiv.org/abs/2609.33518
**作者**: Xiangqi Li, Libo Huang, Jiarui Zhao, Weilun Feng, Chuanguang Yang, Zhulin An 等 (7 人)
**来源**: cs.CV
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent 3D large multimodal models (3D-LMMs) rely on a visual bottleneck to compress complex 3D scene evidence into a limited number of visual tokens compatible with large language models (LLMs). Current visual bottlenecks, however, often passively compress heterogeneous 3D evidence into a homogeneous object-centric token sequence, leaving the spatial organization of the scene under-represented. This under-representation forces the LLM to recover spatial relations from a flattened token sequence, leading to unstable reasoning in relation-intensive and spatially ambiguous scenes. To address this issue, we propose SceneScaffold, an active scene-state construction framework for unified 3D scene understanding. SceneScaffold reformulates the visual bottleneck from a passive feature compressor into an active scene organizer, constructing a role-aware spatial scaffold before language reasoning. Specifically, SceneScaffold organizes superpoint-level visual evidence into scene-state components w

---

### [318] LiteEvo: Automated, Cost-Efficient Harness Evolution for Generalization to Unseen Tasks

**链接**: https://arxiv.org/abs/2609.33146
**作者**: Euntae Choi, Sumin Song, Sungjoo Yoo
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> An LLM agent is defined by two things: the weights inside its model and the harness of components assembled around it. Harnesses are still handcrafted, and HarnessX, which evolves them automatically, starts each benchmark from a handcrafted harness, reports gains on the tasks it evolved on, and budgets 100 to 175 million meta-agent tokens per benchmark. We propose LiteEvo, a lightweight harness-evolution algorithm whose tool-free meta-agents mine agent trajectories for reusable components, curate them into a versioned library, and compose each round's harness from it, starting every benchmark from the same neutral harness and never naming the benchmark. Evolving on the graded tasks of five agentic benchmarks with a frozen Qwen3.5-9B, LiteEvo lifts pass@2 by 10.5 to 67.7pp and reaches comparable or higher pass@2 than a reproduction of HarnessX (71.0 against 67.3 on average) at 13.0 lower mean API cost. Harnesses evolved on train tasks keep their gains on unseen test tasks of four benchm

---

### [319] Climbing the Hill: Prompt Injection Red-Teaming Against Frontier Models with Curriculum Reinforcement Learning

**链接**: https://arxiv.org/abs/2609.33628
**作者**: Chenlong Yin, Xiaolong Jin, Wei Zou, Yanting Wang, Jinyuan Jia
**来源**: cs.LG cs.CR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Prompt injection is a leading security risk for LLMs and LLM-based applications such as agents. State-of-the-art red-teaming methods for prompt injection leverage reinforcement learning (RL) to train an attacker LLM to generate effective injected prompts. However, when targeting frontier LLMs such as GPT-6-Luna, a major challenge is the cold-start problem: every attack attempt by the attacker LLM fails and thus receives zero reward, providing no signal for learning. In this work, we propose a curriculum learning-based method to address the cold-start problem. In particular, we propose to train the attacker LLM against a sequence of increasingly robust target LLMs, with each stage warm-starting from the attacker LLM obtained in the previous one. However, simply training against a weak target (e.g., GPT-4o-mini) may not sufficiently prepare the attacker LLM to obtain useful learning signals against a frontier LLM (e.g., GPT-5.6-Terra). Instead, we find that the design of the curriculum i

---

### [320] Simulating Respondents, Not Single Questions: Coherent Survey Generation with Large Language Models

**链接**: https://arxiv.org/abs/2609.34828
**作者**: Ji Huang, Mengfei Li, Shuai Shao
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models are increasingly used to simulate response distributions in social surveys. Prior work has achieved accurate population-level simulation for individual questions. Real questionnaires, however, ask each respondent a sequence of related questions. A simulated respondent should show coherent preferences across the whole questionnaire, not merely accurate distributions for isolated items. Existing single-item methods cannot accurately reproduce how the same person answers a complete survey. We propose FullRespondent-LLM (FR-LLM), which fine-tunes two specialized LLMs: a marginal model for each item's response distribution and a respondent-level autoregressive model for dependencies across answers. Marginal-Constrained Joint Projection (MCJP) then projects the autoregressive joint distribution onto the set satisfying the item-level marginals learned by the first model. This yields complete questionnaires with realistic cross-item relationships while retaining strong it

---

### [321] PROACT-Agent: Progressive Runtime Oversight and Active Circuit-breaking for Real-Time Safety

**链接**: https://arxiv.org/abs/2609.34415
**作者**: Ding Jia, Wei Liu, Xianglong Du, Yingjie Li, Yingqing Yang, Huili Yu 等 (8 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The transition from Large Language Models (LLMs) to agents shifts safety stakes from toxic text to irreversible environmental harm. While current defenses remain largely retrospective, proactive runtime intervention is bottlenecked by the lack of large-scale, causally-consistent data. We propose PROACT-Agent, a framework for synthesizing high-fidelity trajectories to enable real-time guardrails. We identify a critical "safety drift" in prior benchmarks, where lenient annotation paradigms fail to enforce temporal consistency. PROACT-Agent addresses this through: (1) Progressive Trajectory Unrolling to reveal risks hidden in long-context interactions; (2) Reasoning-Augmented Causal Rectification to enforce monotonic causal consistency; and (3) Culturally-Aware Data Localization for cross-border robustness. We introduce PROACT-Bench, a bilingual safety benchmark with 155,780 states labeled through multi-model adjudication. Evaluating updated context before the next LLM inference, the trai

---

### [322] TSGate: Timestep-Aware Gated Attention for Diffusion Transformers

**链接**: https://arxiv.org/abs/2609.34539
**作者**: Boyu Zhang, Yifan Liu, Shuxia Lin, Qingjian Ni, Yinfei Xu, Xu Yang
**来源**: cs.CV
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Diffusion Transformers (DiTs) have emerged as the dominant architecture for high-fidelity image and video generation. Recent DiT systems increasingly use structured prompts for training, improving caption quality and prompt adherence. However, their generation quality can degrade severely under out-of-domain (OOD) prompts, including the free-form descriptions supplied by users at inference time. Although LLM-based rewriting can convert these prompts into structured formats, it does not guarantee that the rewritten prompts align with the training distribution. Our analysis links this degradation to attention sinks and reduced early-step image-to-text attention and shows that sink suppression alone is insufficient to restore generation quality. Despite effective sink suppression, models trained with standard gated attention exhibit reduced early-step image-to-text attention and suboptimal generation quality. Based on these insights, we propose Timestep-Aware Gated Attention (TSGate), whi

---

### [323] d-OPD: Future-Aware On-Policy Distillation for Block Diffusion Language Models

**链接**: https://arxiv.org/abs/2609.35362
**作者**: Ruitao Liu, Qinghao Hu, Song Han
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) typically generate text autoregressively (AR), predicting one token at a time. Block diffusion language models (dLLMs) instead generate blocks sequentially while denoising multiple tokens in parallel within each block, offering a promising way to accelerate generation. Rather than training such models from scratch, recent work adapts strong pretrained AR models into block dLLMs through distillation. On-policy distillation (OPD) has been widely used for LLM training because it supervises the student on states generated by its current policy, rather than only on fixed offline trajectories. By training on the states the student actually visits, it reduces the mismatch between training and generation and can provide more relevant supervision as the student evolves. Recent work has extended this idea to AR-to-block-diffusion conversion. However, this setting introduces a fundamental mismatch in supervision: the block-diffusion student and the causal AR teacher c

---

### [324] Learning to Optimize through Solver-Grounded Self-Play

**链接**: https://arxiv.org/abs/2609.34205
**作者**: Xia Jiang, Yaoxin Wu, Chenyu Zhou, Mengzhu Xu, Wim P.M. Nuijten, Yingqian Zhang
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Optimization modeling is central to many decision-making scenarios, but traditionally requires extensive domain expertise. While Large Language Models (LLMs) have shown promise in automating this process, current training paradigms mainly rely on human-annotated or teacher-generated datasets. This dependence introduces a Generalization Ceiling, where models overfit to narrow data distributions, and Capability Anchoring, where models' reasoning is bounded by annotator proficiency and teacher model capability. In response, we propose OPT-Zero, the first fully self-play training framework for optimization modeling that requires zero external training data. OPT-Zero employs a single LLM in a dual-role closed loop: a Proposer that synthesizes increasingly challenging optimization problems alongside their mathematical formulations and solving code, and a Solver that attempts to resolve the problems given only natural-language problem descriptions. Grounded in execution feedback from external

---

### [325] EfficientAgent: What Makes KV Cache Offloading Work for Concurrent Agents?

**链接**: https://arxiv.org/abs/2609.33762
**作者**: Kunming Shao, Jierun Chen, Jiangnan Yu, Xiao-Hui Li, Chaofan Tao, Yanli Wang 等 (10 人)
**来源**: cs.DC cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents resend their whole conversation on every turn, and most of it was already processed on the previous turn. Serving systems avoid recomputing it by caching its key-value (KV) state and, when GPU memory runs out, by offloading that state to host memory. For agents, offloading gives inconsistent results: on the same coding-agent workload it speeds up one deployment, slows down another, and changes nothing on a third, even where loading a token back is several times cheaper than recomputing it. The reason is that cached state must survive until it is used again. While one agent waits for its tool, the server processes the contexts of all other agents, so an agent's prefix is reused only if the host tier holds the reusable context of the whole agent pool, which we call the reuse working set. A smaller tier keeps writing state that is evicted before anyone reads it. We present EfficientAgent, which sizes and manages the host tier by this working set. A stack-distance model estimate

---

### [326] Scanvas: Discovering and Developing Synergistic Opportunities in Generative Design Spaces

**链接**: https://arxiv.org/abs/2609.34062
**作者**: Yaqing Yang, Aniket Kittur, Hongyu Howie Wang, Nikolas Martelaro, Matt Klenk, Yan-Ying Chen 等 (7 人)
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Good design is often synergistic, creating super-additive value by linking goals so that existing resources produce greater outcomes. However, finding these synergistic opportunities in sparse design spaces is difficult, and current LLM-supported ideation tools largely default to additive paradigms such as feature blending, variant generation, or local patching. We present Scanvas, an AI-supported system for systematically discovering and developing synergistic design opportunities. Scanvas operationalizes synergy through a two-step computational process: first, it decomposes seed ideas into explicit properties (components, behaviors, surpluses, and issues) to enrich the design space; second, it systematically searches across enriched ideas using three theory-grounded strategy operators: unlocking or strengthening goals, turning weaknesses into resources, and sharing components across functions. We instantiate Scanvas as an auto-generation pipeline and an interactive system. Pipeline a

---

### [327] Evolving Support Priorities in Empathetic Reinforcement Learning

**链接**: https://arxiv.org/abs/2609.34249
**作者**: Pengyu Huang, Zhiyuan Han, Wenwen Tong, Hewei Guo, Jiangnan Chen, Sirui Chen 等 (9 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We identify a fundamental mismatch in empathetic reinforcement learning: support priorities evolve with the dialogue state, yet existing methods typically optimize predefined reward specifications that remain fixed across turns. To model these evolving support priorities, we organize empathetic support along cognitive, affective, and proactive empathy, and propose Context-Adaptive Rubric Evolution (CARE). At each turn, CARE generates a context-adaptive rubric by adjusting both the weights of these three empathy dimensions and their fine-grained evaluation criteria. The rubric generator is trained with turn-level rubric supervision and human preference data through supervised fine-tuning followed by preference-based reinforcement learning, and then serves as an adaptive reward interface for online empathetic RL. Integrated with both RLVER and MICA, CARE achieves state-of-the-art performance across SentientBench, EQBench3, and EMPA under three independent LLM judges. Notably, on EMPA, CA

---

### [328] Enabling Timely Guidance before Skill Retrieval: Retaining Helpful Warm Tips in Agent Context

**链接**: https://arxiv.org/abs/2609.32339
**作者**: Feng Liang, Yupeng Li, Runhao Zeng, Francis C. M. Lau and Xiping Hu
**来源**: cs.AI cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reusable skills help LLM-based agents solve complex tasks, but the agent must receive guidance before it commits to an ineffective approach. Existing skill mechanisms often expose only metadata and load full content on demand, leaving useful guidance unavailable until the agent decides to retrieve it. General memory methods can incur substantial maintenance overhead, while keeping guidance in conversation context risks repeatedly exposing the agent to irrelevant or harmful advice. We propose TipsWarm, a mechanism that complements existing skill mechanisms by maintaining a budgeted pool of skill-derived keypoints, or \textit{warm tips}, for selective injection into the context of every message turn. By separating event-triggered LLM assessment from inexpensive per-turn screening, it makes transferable skill guidance readily available while controlling maintenance costs. In three coding and iterative task-execution benchmarks, TipsWarm achieves the highest task success rate while remaini

---

### [329] Unknown is not normal: separating language-model extraction from rule-based decision logic for clinical risk scores

**链接**: https://arxiv.org/abs/2609.34112
**作者**: Nicol\'as Vera Z\'u\~niga
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly used to compute clinical risk scores from free-text notes. Notes are often incomplete, and treating undocumented findings as normal can silently misclassify patients. We test whether separating three-state extraction (present, absent or unknown, by an LLM) from decision logic (deterministic code computing score bounds over unknown inputs) lets a system ask only questions that can change the decision. On 1,200 synthetic emergency cases across six calculators (HEART, CURB-65, qSOFA, PERC, Wells, Cockcroft-Gault), with a simulated clinician answering questions, we compared this bounds policy with asking for every missing input, a missing-equals-normal schema, and an end-to-end LLM agent (Claude Opus 5.5). With Claude Haiku 4.5 as extractor, the bounds policy matched ask-all accuracy (99.4% vs 99.4%) with half the questions (0.92 vs 1.78 per case) and no irrelevant ones. Treating missing as normal dropped accuracy to 91.2% and under-triaged 8.5

---

### [330] BaatCheet: A Multilingual Corpus for Dialogue Translation in Indian Languages

**链接**: https://arxiv.org/abs/2609.33296
**作者**: Priyanka Dasari, Yuvrajsinh D. Bodana, Vandan Mujadia, Arafat Ahsan, Dipti Misra Sharma and Parameswari Krishnamurthy
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Existing translation models are typically trained on sentence-level and formal text, limiting their ability to capture everyday conversational dialogue phenomena such as informality, speaker interaction, and discourse coherence. Most existing Indic translation resources and evaluation benchmarks focus on sentence-level or formal text, making it difficult to assess translation quality of the dialogue phenomena. In this work, we introduce BaatCheet, a multilingual dialogue corpus named after the Hindi term for conversation or chitchat, containing approximately 49,000 dialogues for dialogue translation across five translation directions. We fine-tune five open-source LLMs across seven training data configurations and find that fine-tuning yields substantial gains over zero- and few-shot baselines. To comprehensively evaluate dialogue translation quality, we employ multiple evaluation strategies, including automatic metrics, LLM-as-judge, and human assessments using an SQM-guided Direct As

---

### [331] Prefill-Free Cross-Family KV Cache Transfer for Heterogeneous Multi-Agent LLMs

**链接**: https://arxiv.org/abs/2609.32259
**作者**: Vincent-Daniel Yun, Woosang Lim, Haneul Yoo, Sungjoo Yoo, Sai Praneeth Karimireddy, Murali Annavaram
**来源**: cs.AI cs.LG cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent multi-agent LLM systems increasingly combine heterogeneous models for specialized agent roles. However, text-based communication requires each receiver to prefill shared context already processed by the sender. Reusing the sender's key-value (KV) cache avoids this redundancy, but prefill-free transfer across model families must handle differences in tokenization, model depth, and KV representations. To address these issues, we propose \textit{HeteroFold}, a prefill-free cross-family KV cache transfer method that keeps both the sender and receiver frozen. HeteroFold aligns model structures, maps the sender cache into the receiver space, and calibrates it to preserve receiver behavior. Across six transfer directions, HeteroFold achieves the best cache-transfer performance on all four long-context benchmarks and most short-context settings. It also matches text-based communication on the multi-agent benchmark. At 32K context length, Llama-3.1-8B$\rightarrow$Ministral-3-14B transfer

---

### [332] From Scene Graphs to Answers: Selective Neuro-Symbolic Reasoning for Autonomous Driving

**链接**: https://arxiv.org/abs/2609.32645
**作者**: Yiyao Wang, Pei Liu, Fangzhou Liu, Jun Ma
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Autonomous-driving question answering requires reasoning over structured scene information, yet existing vision-language approaches largely delegate heterogeneous reasoning operations to a single neural inference process. We argue that this uniform strategy overlooks a fundamental distinction: some queries admit exact symbolic solutions, while others require semantic interpretation. We introduce a query-adaptive neuro-symbolic reasoning framework that explicitly allocates computation according to the nature of the query. At its core is a hierarchical Spatiotemporal Scene Graph (STSG) that separates persistent object identities from frame-specific states and represents spatial relations and temporal transitions as explicit directed structures. Given a query, a symbolic executor first attempts to resolve it through exact graph operations; only when symbolic execution abstains is an LLM invoked for semantic reasoning. For these unresolved queries, query-conditioned graph retrieval and evi

---

### [333] SelfCue: Making a 3D CT Report Generator Say What It Already Knows

**链接**: https://arxiv.org/abs/2609.31788
**作者**: Renjie Liang, Yang Yang, Jinqian Pan, Zhengkang Fan, Chengkun Sun, Jie Xu
**来源**: cs.CV
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Progress in 3D CT report generation is usually sought in increasingly sophisticated architectures and larger pools of training data. We find instead that a 3D CT report generator already holds what its report leaves out, and loses it when the hidden state becomes tokens. Over the 18 CT-RATE abnormalities, this hidden-to-report surfacing gap is reflected by a drop in macro AUROC from 0.848 in the hidden states to 0.739 in the generated report. We propose SelfCue based on contrastive decoding. It promotes what the hidden state already supports and suppresses what it does not. It raises clinical efficacy F1 to 0.481 and the LLM-judged GREEN score to 0.510. Distilling that behaviour into the weights gives SelfCue-KD, a student that keeps most of the gain, needs nothing extra at inference, and drops into any pipeline already serving the baseline. Code is available at https://github.com/renjie-liang/SelfCue-CT.

---

### [334] GenMem: Generative Symbolic Memory for Self-Evolving Harness

**链接**: https://arxiv.org/abs/2609.34633
**作者**: Xinke Jiang, Tao Feng, Weixuan Xu, Zhixin Zhang, Zhibang Yang, Wentao Zhang 等 (10 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-term memory supports the self-evolution of LLM agents by retaining experience and skills across tasks and enabling their retrieval, reuse, and revision in subsequent long-horizon decision-making. Yet existing memory management approaches remain limited to discriminative retrieval and to address the sparse, hierarchical, and highly redundant structure of reusable experience: only a small, task-dependent subset of trajectories and memories warrants retention, retrieval, or revision. Learning these operations is further complicated by sparse, delayed, and indirect task-level feedback, with weak supervision across the memory lifecycle. Moreover, continual memory evolution introduces an architectural tension as addressing invariance: stored experience is perpetually revised, yet the addressing interface consumed by learned retrieval policies must remain stable. To address, we present GenMem, which reformulates memory management as generative symbolic addressing. Its core mechanism is t

---

### [335] Report: Progressive Disclosure of Agent Skills

**链接**: https://arxiv.org/abs/2609.35692
**作者**: Guilin Zhang, Kai Zhao, Priyanka Mudgal, Waleed Ammar, Xiquan Cui, Xu Chu 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Users of Workday's deployed LLM-based agents often request features which can be addressed by defining named procedures, also known as skills, in the LLM context, effectively augmenting agents' capabilities. However, as an agent's skills library grows in size, so does the agent's operational cost. Progressive disclosure (lazy-loading) of skills as needed may reduce operational costs, but its impact on overall latency and skill-retrieval quality remains unclear. In this report, we investigate the impact empirically and find that progressive disclosure improves skill-retrieval quality but marginally degrades overall latency.

---

### [336] VPEvolve: A Self-Evolving Virtual Process Engineer for Computational Lithography

**链接**: https://arxiv.org/abs/2609.32473
**作者**: Tianyi Li, Wenxuan Dong, Donger Luo, Nan Wang, Yanpeng Chen, Jiaqi Liu 等 (8 人)
**来源**: cs.AI cs.SE
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Optical proximity correction (OPC) recipes grow as engineers add local rules to repair newly discovered lithography hotspots. Each correction can interact with existing rules, while lessons from commercial-tool trials remain scattered across code and logs. \system combines a Virtual Process Engineer (VPE) harness with a Skill Bank of measured engineering experience. The harness equips a frozen language model with process manuals, layout analysis, recipe editing, and commercial-tool evaluation. The actor proposes changes to the global parameters, local targeted rules, or diagnostic trials. After each evaluation, an LLM reflector and curator turn the measured response into evidence-linked judgments. The actor retrieves them before its next trial. Feasible improvements update the retained recipe; every measured trial informs the Skill Bank that guides the next edit. The model weights remain fixed. On a FreePDK45-derived benchmark with ten commercial-tool evaluations per case, \system redu

---

### [337] When Does Selection Replace Extraction? A Pre-Registered Test of Agent Memory with a Typed Decision Model

**链接**: https://arxiv.org/abs/2609.34227
**作者**: Rishabh Sharma, Rishika Lall
**来源**: cs.AI cs.CL cs.IR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Does conversational memory need LLM-extracted facts, or is selecting the right raw turns enough? Published results disagree. Extraction-based systems report gains from distilled facts. Recent studies find raw history with good ranking does as well, but disagree about whether ranking matters. We ran a pre-registered study on held-out LoCoMo conversations and LongMemEval. At a tight budget on LoCoMo, raw turns selected by a single call to Jev, a typed decision model, are non-inferior to an LLM-extraction memory (one-sided 95% bound -3.0 points against a -5-point margin). Blind human grading narrows the margin but does not change the result. Raw turns cost 3,061 times less to write, and the result holds with a second answer model. Within this study, reranking's gain shrinks as the budget grows. It adds 17.4 points on LoCoMo and 9.1 on LongMemEval when three of 30 candidates are kept. At generous budgets it adds 1.5 and 1.1, and extraction systems are more accurate. This suggests why publi

---

### [338] Diffusion Reward Models

**链接**: https://arxiv.org/abs/2609.33803
**作者**: Xiangyang Wang, Bingxiang He, Zeyuan Liu, Jiaze WangZiqing Qiao, Yuxin Zuo, Huan-ang Gao 等 (10 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reward models underpin the alignment of large language models, yet the dominant designs reduce each prompt--response pair to a point estimate or to a distribution from a fixed parametric family. This is at odds with human preference, which is inherently multimodal: the same response can be reasonably judged in many ways, and no single family covers all of them. To better fit this structure, we introduce DRM, a Diffusion Reward Model that recasts reward modeling as conditional density estimation over $p(\mathbf{r}\mid x,y)$. Conditioned on a frozen LLM encoder, a lightweight Diffusion Transformer denoises Gaussian noise into a reward vector, placing no parametric assumption on the output distribution and naturally representing its multimodal structure. A single architecture handles both multi-attribute regression and pairwise preference data, and at inference $N$ samples form an empirical reward distribution that can be aggregated into a scalar, a variance, or quantiles. Across five ben

---

### [339] QuantForge: Discovering Residual Decompositions for MXFP4 Post-Training Quantization

**链接**: https://arxiv.org/abs/2609.34680
**作者**: Qiulin Shang, Zhoutong Wu, Jie Hu, Kun Yuan
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Four-bit post-training quantization can reduce the memory demands of large language models, but preserving accuracy under strict MXFP4 W4A4 requires coordinating several design choices. Coordinate transforms change block-encoding errors, which in turn affect the residuals propagated through the network. The useful algorithmic decomposition is therefore not fully known before search. LLM-driven program evolution offers a way to explore these choices, but performance scores alone do not explain which design should change next. We introduce QuantForge, a PTQ discovery system that records competing explanations, selects controls that distinguish them, and checks that successor code implements the resulting conclusions. This residual compilation guides program revisions while retaining useful programs even when their original explanations are rejected. Remeasuring the revised program reveals the next error to address. This process discovers HiRes, a fixed MXFP4 quantizer that shapes coordin

---

### [340] Zero-Shot Cue-Grounded Topic Segmentation of Spoken Documents

**链接**: https://arxiv.org/abs/2609.34425
**作者**: Suhwan Choi, Myeongho Jeon, Myungjoo Kang
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Topic segmentation structures spoken documents into coherent sections, facilitating navigation and downstream understanding. The appropriate granularity can vary substantially, ranging from broad thematic shifts to fine-grained subtopics. Existing LLM-based segmenters, however, often struggle to adapt to this variation, causing them to either merge distinct subtopics or over-segment coherent themes. To address this, we introduce Cue-Grounded Segmentation (CGS), a training-free framework that operates without any task-specific supervision. CGS first identifies phrases that explicitly signal the start of a new topic and uses their sentence positions as segment boundaries. When such cues are insufficient, it falls back to semantic segmentation, guided by the document structure inferred during cue extraction. Across six benchmarks and six LLM backbones, CGS consistently outperforms existing baselines, remains robust to noisy ASR transcripts, and achieves these gains with low API cost on pr

---

### [341] CAIRN: Dynamic Fact-Intent DAGs for Multi-Agent Exploration

**链接**: https://arxiv.org/abs/2609.32700
**作者**: Zuyao Xu, Yuyang Jia, Junwei Guan, Xiang Li, Kaiwen Shen, Zhiqiang Dong
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-powered autonomous systems have demonstrated promising capabilities in mathematical reasoning, engineering, and cybersecurity. Yet how to organize these systems for effective, reliable, and sustained performance remains an open question. In this paper, we present CAIRN, a fact-intent-driven multi-agent paradigm for goal-directed exploration. CAIRN represents observations and planned investigations as a dynamic directed acyclic graph (DAG). A reasoner interprets facts to propose intents, which workers execute to produce new facts. Each intent references its supporting facts and defines a potential exploration branch. The persistent graph preserves goals, dependencies and findings across workers, supporting knowledge reuse and parallel exploration. The graph also makes execution trajectories traceable and auditable, providing a basis for human verification and intervention. We evaluate CAIRN across cybersecurity and mathematical reasoning tasks, examining task success, time to soluti

---

### [342] SentZero: An Enhanced Sentence-Centric Vision-Language Pretraining for Multi-Task Zero-Shot Chest X-Ray Analysis

**链接**: https://arxiv.org/abs/2609.34479
**作者**: Hangyul Yoon, Hyungyung Lee, Edward Choi, Eunho Yang
**来源**: cs.CV cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Vision-language (VL) pretraining using paired chest X-ray (CXR) images and radiology reports has shown strong potential for medical image understanding. However, existing methods often remain dependent on task-specific finetuning because radiology reports are lengthy, clinically dense, and difficult to align with simple zero-shot prompts. Recent sentence-level approaches partially address this limitation using clinical phrases extracted by large language models (LLMs), but they largely overlook the intrinsic characteristics of radiology discourse. In particular, limited positive-pair diversity constrains further gains, while clinically equivalent sentences frequently recur across patients, creating false negatives in contrastive learning. To address these issues, we propose SentZero, an enhanced sentence-centric VL pretraining framework for zero-shot, multi-task CXR analysis. SentZero introduces LLM-based abstract-level sentence structuring and mapping to expand positive-pair diversity

---

### [343] When Consent Outlives Context: Residual Authority Replay in Long-Lived Agents

**链接**: https://arxiv.org/abs/2609.33910
**作者**: Zhihao Zhang, Chao Wang, Rujia Li, Qingze Wang, Xiaoyan Sun, Jun Dai
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents increasingly rely on user approval to authorize security-sensitive actions at runtime. Such approvals are granted within a specific task and execution context. In long-lived agents, authorization decisions may need to persist across tasks or sessions. We find that this continuity can outlive the context that originally justified the approval, creating residual authority reusable without renewed consent. We expose this failure mode through a longitudinal attack that starts from a target security-sensitive action, identifies the authority required to execute it, induces benign interactions that legitimately obtain that authority, and later replays the residual authority during adversarial execution. Across controlled and live settings, we demonstrate that residual-authority replay arises in practice and substantially increases the success of prompt-injection and context-rebinding attacks. We evaluate 508 AgentDojo attack cases across six LLM families using production-derived a

---

### [344] TRACE: Expert-Aligned ECG Representation Learning with Rigorous Benchmarking and Real-World Validation in Acute Cardiac Care

**链接**: https://arxiv.org/abs/2609.34088
**作者**: Lovely Yeswanth Panchumarthi, Andrew Lu, Saurabh Kataria, Delgersuren Bold, Minxiao Wang, Runze Yan 等 (10 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> TRACE (Text-Reinforced Analysis of Cardio ECGs) is a multimodal electrocardiogram (ECG) representation model that learns clinically grounded signal embeddings for downstream cardiac classification. It is designed to address the limitations of existing CLIP-style training, which often struggles with noisy clinical text and fails to leverage the complementary strengths of unimodal (from ECG) and cross-modal (between ECG and matched cardiologist reports) learning. To bridge this gap, we propose a hybrid architecture that jointly learns unimodal and cross-modal representations via uncertainty-weighted multi-task learning while utilizing an LLM-based pipeline to extract high-fidelity findings from cardiologist reports. We evaluate TRACE across a spectrum of clinical urgency, establishing robust performance on public benchmarks for arrhythmia classification and structural abnormalities relative to existing unimodal and multimodal ECG models. To demonstrate real-world utility, we further vali

---

### [345] AirLog: Store-Level Indoor Life Logging Made Easy

**链接**: https://arxiv.org/abs/2609.31864
**作者**: Zihui Yun, Jiaying Du, Yue Yu, Zhewei Liu, Zhen Xiang, Longfei Shangguan 等 (7 人)
**来源**: cs.NI cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> This paper presents AirLog, a smartphone-based life journaling system that automatically reconstructs users' store visits in shopping malls and summarizes them into human-readable journals. Unlike conventional indoor localization systems, AirLog avoids labor-intensive radio-map construction and dedicated wireless localization infrastructure and algorithm calibrations. Instead, it repurposes two cues already available in commercial spaces: semantic information exposed by ambient Wi-Fi SSIDs and indoor directory images. AirLog converts directory images into spatial maps and fuses Wi-Fi semantic anchors with inertial dead reckoning to recover store-level trajectories, which are then summarized into journals by an LLM. Such store-level life logs can support applications such as personal memory recall, activity reflection, and automated diary generation without requiring users to manually record where they have been. We implement AirLog on commodity smartphones and evaluate it on both a lar

---

### [346] PC-SubMax: Efficient Prompt Compression via Regularized Submodular Maximization

**链接**: https://arxiv.org/abs/2609.32474
**作者**: Ziyi Zhang, Shuang Cui, Haotian Zhang, Xiaoyu Wang
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> While large language models (LLMs) are increasingly deployed in long-context scenarios, lengthy prompts can increase inference costs and latency and exacerbate the ``lost-in-the-middle'' phenomenon. Selective prompt compression offers a model-agnostic approach to alleviating these issues. However, methods based on fixed token- or sentence-level importance scores may overlook how content contributions change with the selected subset, limiting their ability to account for inter-sentence redundancy. Compression procedures that rely on autoregressive LLM scoring can also introduce substantial overhead. We propose PC-SubMax, a theoretically grounded framework that formulates selective prompt compression as regularized monotone submodular maximization under a knapsack constraint. The objective is $U(S)-\ell(S)$, where the monotone submodular utility $U$ combines information coverage, query relevance, and log-determinant diversity, and the non-negative modular penalty $\ell$ captures token co

---

### [347] SEABench: Benchmarking Endogenous Misalignment In Self-Evolving Agents

**链接**: https://arxiv.org/abs/2609.35596
**作者**: Saswat Das, Parvati Viswanathan, Daniel Donnelly, Chang Huang, Sahar Abdelnabi, Ferdinando Fioretto
**来源**: cs.CR cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Self-evolving LLM agents have gained prominence for their ability to improve after deployment by modifying their harness, including their controller instructions, memory management protocols, and reusable tools and skills, in response to user and environment feedback. However, locally useful updates may persist into later tasks where they produce unsafe behavior, even without direct adversarial influence. To study this risk, we introduce SEABench, a benchmark for studying endogenous misalignment arising from agent self-evolution, with 48 longitudinal task sequences that span multiple evolution surfaces, task domains, and harm types in a rich personal-assistant environment. To account for the stochasticity inherent in agentic operations, we provide an adaptive trajectory discovery pipeline that probes for failures while preserving original task intent and supports causal attribution through paired non-evolving agents and attribution scores. Our evaluation across multiple recent LLMs, ev

---

### [348] Coherence-Aware Distributional Evaluation of Open-Ended Text Generation

**链接**: https://arxiv.org/abs/2609.34240
**作者**: Jinnuo Liu, Junhao Zhu, Weifeng Jiang, Haoming Liu, Hongyi Wen
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Existing metrics for open-ended text generation measure likelihood, lexical diversity, or distributional similarity in generic representation space, yet they can miss fundamental dimensions of quality. A prominent blind spot is global coherence: a generated passage may be locally fluent while remaining globally contradictory, causally inconsistent, or topically disconnected. Such failures can still preserve the token-level and lexical statistics that existing metrics rely on. We identify representation as a central bottleneck in detecting these failures and introduce CHORD (Coherence-aware Hidden-state Open-generation Reference Distance), a coherence-sensitive distributional metric. CHORD encodes generated and human-written corpora in the hidden-state space of a frozen LLM using a coherence-eliciting prompt, and compares the resulting distributions using MMD with an RBF kernel. To validate that the metric responds to coherence degradation but not generic textual change, we construct a 

---

### [349] What Drives Citations in Production Large Language Models? An Observational Multi-Method Study of Two Million AI Citations Across Ten Thousand Web Pages

**链接**: https://arxiv.org/abs/2609.35077
**作者**: Ben Moore, Liam Dunne
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Production large language models retrieve and cite web pages alongside generated answers, yet the page-level features that predict citation frequency remain poorly characterised. We present an observational study of approximately 2 million LLM citations from four commercial engines (ChatGPT, Claude, Google AI, Gemini) over six months, joined to 10,000 crawled pages from nineteen B2B SaaS workspaces. Sixty-plus features are tested using a nine-method consensus framework combining mixed-effects regression with domain fixed effects, FDR correction, stability-selection Lasso, double machine learning, generalised additive models, and temporal hold-out replication. Four findings survive all checks. First, prompt-content alignment (Jaccard overlap between page tokens and the full workspace prompt corpus, including non-citing prompts) is the dominant page-level predictor (beta = +0.37, 95% CI [+0.33, +0.41], q ~ 10^-73). Second, the standard AEO checklist (FAQ blocks, structured data, Core Web

---

### [350] OpenTumorBoard: A Real-World Benchmark of Multidisciplinary Tumor Board Discussion Trajectories

**链接**: https://arxiv.org/abs/2609.32810
**作者**: Anqi Li, Zhixuan Ge, Yixuan Duan, Jiarong Qian, Chi-Yu Chen, MingYu Lu 等 (10 人)
**来源**: cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multidisciplinary tumor boards integrate multimodal clinical observations and longitudinal patient histories through specialist discussions, yet benchmarks rarely capture these real-world trajectories. We introduce OpenTumorBoard, a benchmark with 611 patient cases and 19,157 discussion turns across ten specialist roles, transcribed from 12,534 minutes of publicly available tumor board recordings on YouTube. The benchmark evaluates two settings: SPECIALIST TURN, in which an LLM responds to a clinically significant question posed during a real discussion, and BOARD SIMULATION, in which it generates an entire back-and-forth discussion and reaches a consensus on therapy recommendations, surgical plans, next actions and clinical trial matching. Evaluation of 14 general-purpose frontier and medical LLMs reveals substantial limitations: the best models score 3.43 out of 5 in clinical equivalence to specialist answers and 2.78 out of 5 in alignment with recorded board conclusions. Supervised 

---

### [351] mu-bench: A Multilingual Utterance Transcription Benchmark

**链接**: https://arxiv.org/abs/2609.32082
**作者**: Andrea Li (UC Berkeley), Soham Ray (Sierra AI)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Voice agents depend on accurate automatic speech recognition (ASR) to act on what callers say, yet ASR is evaluated on read, English-centric speech with word error rate (WER), which penalizes surface rather than semantic differences. We introduce mu-bench, a dataset of 4,270 caller utterances from 250 phone calls to an AI banking agent in English, Spanish, Turkish, Vietnamese, and Mandarin, centered on form-field inputs such as names, email addresses, and confirmation codes. We release Utterance Error Rate (UER), an LLM judge of whether a transcript preserves meaning, calibrated against human raters, together with an LLM normalizer that makes WER comparable across providers' output formats. On 1,847 human-rated transcripts, UER agrees with annotators at $\kappa$ = 0.78, versus 0.53 for exact-match WER on normalized text. We rank six commercial providers on a public leaderboard; the best reaches 11.9% UER, and Mandarin is hardest for all six.

---

### [352] In-Context Adaptation of Encoder-Decoder Models in Speech Recognition

**链接**: https://arxiv.org/abs/2609.33865
**作者**: Yen Meng, Sharon Goldwater, Hao Tang
**来源**: cs.CL cs.SD eess.AS
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In-context learning offers an appealing approach to adapt automatic speech recognition (ASR) models to new speakers, accents, and domains by providing speech-text pairs as demonstrations at inference time. Recent work shows that some LLM-based speech models are capable of ASR in-context adaptation, when providing interleaved speech-text demonstrations. In this work, we ask whether in-context adaptation is an inherent ability for all encoder-decoder models. We study two forms of demonstration, collated and interleaved demonstration, across six encoder-decoder models, spanning conventional cross-attention-based and LLM-based architectures. We find that all tested models are able to perform in-context adaptation out of the box, achieving up to 30% relative improvement in the oracle experiments and up to 23% using first-pass hypotheses. Through controlled experiments on three English datasets, we show that lexical and speaker information both contribute to successful adaptation. While inte

---

### [353] ProofLoom: Proof-Obligation-Driven Theory Construction for Autoformalizing Research-Level Stochastic Optimization

**链接**: https://arxiv.org/abs/2609.34960
**作者**: Feiming Wang, Daibo Li and Kun Yuan
**来源**: cs.AI math.OC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Formalizing research-level stochastic optimization in Lean requires both an algorithm model and domain theory connecting foundational libraries to convergence proofs. Revising a model to restore provability can change the mathematical claim. We introduce ProofLoom, a fully automated LLM-agent system for Proof-Obligation-Driven Theory Construction. Given a published algorithm, target theorem, and source proof, ProofLoom autonomously constructs the Lean model and supporting theory. Open proof obligations drive the development of definitions, interfaces, lemmas, and proof plans. Signature contracts record evidence and obligations for model revisions; an independent Judge rejects unsupported assumptions and weakened conclusions. Planner expands the published argument into intermediate claims, and Audit checks whether the Lean proof follows it. Across tasks, SOptLib accumulates verified mathematics and construction experience: reusable results are extracted, generalized, and verified, while

---

### [354] Toward a Graded Measure of Belief Stability in Large Language Models

**链接**: https://arxiv.org/abs/2609.34158
**作者**: Samantha Dies, Branden Fitelson, Tina Eliassi-Rad
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) increasingly mediate how people access and reason with information, yet factual reliability is usually evaluated one judgment at a time. We introduce graded belief stability, a relational measure of how well a belief persists within an LLM's broader belief system. Unlike individual belief probability, it asks whether support for a claim persists when that claim is considered alongside the model's other epistemic commitments. We operationalize this idea with a Direct Conditional estimator that uses internal model representations to estimate conditional belief probabilities. Across 12 LLMs and three domains, lower-stability beliefs exhibit greater mean behavioral movement under conversational challenge in 83.3% of model-domain settings after matching on individual belief probability. Graded belief stability therefore extends reliability assessment beyond how strongly an LLM supports a claim to how robustly that belief is supported within its broader system of

---

### [355] CP-Agent: A Harness-Engineered Agent for Crystal Plasticity Simulation Workflows

**链接**: https://arxiv.org/abs/2609.31790
**作者**: Samuel Onimpa Alfred, Abhishek Kumar, Veera Sundararaghavan
**来源**: cs.AI cond-mat.mtrl-sci
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Crystal plasticity (CP) simulations predict the mechanical behavior of polycrystalline metals, yet their routine use is hindered by the manual effort of configuring heterogeneous tools, orchestrating multi-step data pipelines, and calibrating constitutive parameters against experiments. These bottlenecks impede productivity in systematic parameter studies, motivating interest in automated workflows. This study presents CP-Agent, a harness-engineered LLM-based agent that autonomously executes complete CP modeling workflows from natural-language tasks. Operating under the ReAct paradigm, the agent reasons about tool selection and sequencing while delegating numerical search to established optimizers. The harness comprises a minimal system prompt, typed tool definitions, a dispatcher, and a safety-bounded iteration loop, encoding domain knowledge through tool schemas rather than hard-coded logic. CP-Agent is demonstrated on four case studies: calibrating four slip parameters of additively

---

### [356] Understanding and Exploiting Anisotropy in Post-Training

**链接**: https://arxiv.org/abs/2609.32792
**作者**: Samyak Jha, Harshvardhan Saini, Yizhen Liao, Yiming Tang, Dianbo Liu
**来源**: cs.LG cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM post-training combines supervised fine-tuning (SFT), a mode-covering forward-KL objective, with reinforcement learning (RL), a mode-seeking reverse-KL objective. Frequency-weighted likelihood training leaves a well-known signature: \emph{anisotropy}, in which a few residual channels carry disproportionately large activations. Anisotropy is widely documented and usually treated as a defect, yet its function and its interaction with post-training remain unclear. We first analyze it. A label-free outlier rule isolates about 5\% of residual channels that are essential for language modeling: removing them raises perplexity from 10 to over $10^6$, versus 35 for count-matched random channels. Yet they barely distinguish correct from incorrect reasoning. SFT reshapes them, whereas RL leaves them largely intact and adapts the complementary channels. These channels therefore form the model's \emph{coherence substrate}, and reasoning adaptation happens elsewhere. We then exploit this. \textsc

---

### [357] ReMCTS: Reflection-Enhanced Monte Carlo Tree Search for Code Generation

**链接**: https://arxiv.org/abs/2609.34717
**作者**: Huifei Wang, Xinying Huang, Yiheng Sun, and Yifan Yuan
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Open-weight large language models (LLMs) can generate function-level programs from natural-language prompts, but plausible candidates still fail on hidden semantics and repeat mistakes across repair attempts. We present ReMCTS, an execution-grounded, memory-augmented, LLM-guided MCTS-style search framework. It organizes program candidates as tree states, retains branch-local debugging context, retrieves failure experience across branches, and distinguishes failed checks from unavailable evidence. On HumanEval and MBPP-Sanitized, visible-test ReMCTS improves over direct generation in 8 of 10 model-dataset pairs under held-out evaluation, whereas proxy-only search is less stable. Controlled tree-search, sampling, repair, and memory ablations characterize the source and limits of these gains. A 30-task HumanEval-X C++ pilot further demonstrates compatibility with compiler-backed execution, but does not constitute a broad multilingual evaluation.

---

### [358] From Weak Task Specifications to Scientific Extraction Agents: Optimizing Task Construction

**链接**: https://arxiv.org/abs/2609.34829
**作者**: Zixiao Dong, Wei Yang, Zihao Liu, Chenshu Li, Longzhang Liu, Tao Tan 等 (7 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Most methods that optimize LLM prompts and agent workflows assume that task-specific output schemas, extraction instructions, and evaluation criteria are predefined. For scientific extraction agents, however, a short task goal may not fully determine these components, while specifying them manually is costly. We study the upstream problem of constructing the task-specific configuration from a weak specification containing only a short goal and unannotated reference documents. Rather than treating automatic construction as a fixed preprocessing step, our framework constructs a task-specific schema, extraction instructions, and base training rubrics, then keeps schema construction and extraction instructions editable during optimization. Failure-focused updates concentrate textual-gradient feedback on lower-scoring documents, while training-time evaluation criteria adapt to recurring failures. On a heterogeneous-catalysis literature corpus, automatic construction remains improvable, and 

---

### [359] The Error You See Is Not the Error You Made: Progression-aware Reasoning Origin for Reasoning Error Localization

**链接**: https://arxiv.org/abs/2609.33297
**作者**: Yiguo Wang, Ziyuan Yang, Yi Zou, Dan Lin, Rongsheng Li, Yi Zhang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Verifying multi-step LLM reasoning requires more than determining whether a trace is correct: a useful verifier should identify where the reasoning first goes wrong. However, existing holistic methods provide little positional evidence, while forward sequential verification often treats the first rejected step as the error source. Under error propagation, this assumption can fail, since an earlier mistake may remain locally plausible and become observable only through its downstream consequences. We therefore rethink reasoning verification as a progression-aware error-source localization problem: rather than asking only where a reasoning trace first appears inconsistent, we ask which earlier step best explains how that inconsistency emerges along the trajectory. Based on this view, we propose Progression-aware Reasoning Origin (PRO), a training-free framework for first-error localization. PRO jointly models incoming support from the preceding context and outgoing compatibility with sub

---

### [360] Quantifying Behavioral Tails in Black-Box Language Models

**链接**: https://arxiv.org/abs/2609.33638
**作者**: Elsayed Eshra, Ali Al-Lawati, Dongwon Lee, Suhang Wang
**来源**: cs.LG cs.CL stat.ML
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We introduce RareTrap, a framework for estimating the probability of severe behaviors in black box large language models (LLMs). A key challenge for probability estimation is defining a tractable distribution over the input space. To accomplish that, RareTrap uses a surrogate LLM and constructs a geometry-aware mapping from a lower-dimensional latent reference space into its token-embedding space to induce an explicit and reproducible distribution over input prompts. A response-level performance function is utilized on the response to quantify behavior severity. This enables sequential rare event simulation that concentrates evaluations on progressively more severe behaviors while preserving probability under the induced prompt distribution, which would otherwise be prohibitive to measure. Across 10 open-weight and two frontier models (GPT-5.4 and Claude Sonnet 4.6), we find that RareTrap successfully induces severe resource consumption behaviors and computes their probability with as 

---

### [361] HTN Planning as a Coordination Layer for Multi-Server MCP Tool Orchestration

**链接**: https://arxiv.org/abs/2609.33731
**作者**: Eliott Jacopin, \'Eric Jacopin, Koichi Takahashi
**来源**: cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The Model Context Protocol (MCP) isolates servers by design: only the host can orchestrate cross-server workflows. When the host is a large language model, the resulting orchestrations are non-deterministic, non-reproducible, and pay one inference round-trip per tool call. We present a coordination architecture in which a Hierarchical Task Network (HTN) planner generates a verifiable cross-server plan once, and a runtime middleware executes it deterministically across multiple MCP servers, binding cross-action data dependencies via a template mechanism (\verb|${context.X}|) substituted at execution time. The architecture mirrors MCP's isolation constraint: each compound task decomposes into server-local primitive actions, and inter-server data flow is bound at execution time via JSON-path output extractors. We instantiate the architecture on five HTN domains spanning laboratory robotics, bioinformatics and multiscale modelling, and demonstrate end-to-end execution from a browser-based 

---

### [362] Auditing Agent Actions through Query-Conditioned Attribution

**链接**: https://arxiv.org/abs/2609.33676
**作者**: Yifan Liu, Praveen Venkateswaran, Abdulhamid Adebayo, Dong Wang
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents increasingly take consequential actions through interactions with users, policies, and external tools. Auditing these agents requires automated attribution of realized actions to their historical basis. However, existing attribution formulations do not provide question-specific traces for diverse auditing objectives. Additionally, when access to the acting model is limited (e.g., in API-only deployments), applicable methods commonly rely on costly input perturbations or external LLM analysis of complete trajectories. We therefore formulate $\textit{query-conditioned agent action attribution}, a new task that takes a natural-language auditing query as input and recovers the source and ordered intermediate evidence for the query-specified aspect of an action. We instantiate this task with $A^3Bench$, a benchmark comprising 1,396 auditing queries across policy basis, parameter provenance, failure propagation, and unsafe-behavior tracing. To enable efficient, query-specific attr

---

### [363] Kafila: Serving Large Language Models on a Trusted Set of Heterogeneous Commodity Machines

**链接**: https://arxiv.org/abs/2609.34045
**作者**: Murtaza Rangwala, Richard O. Sinnott, Rajkumar Buyya
**来源**: cs.DC cs.LG
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Between them, the members of a research group or a circle of friends own several consumer computers, none large enough to run a capable large language model. Existing systems pool such capacity across open swarms anyone may join, which a group admitting only trusted machines cannot use. Bounding membership removes what they depend on: a swarm holds each part of the model on several peers and routes around a slow one. A bounded session must use every device it admits. Its pipeline advances at the pace of whichever device received a share it cannot serve quickly, so the division has to be right before serving begins. We propose Kafila, whose protocol assembles a ring from behind NATs, preferring direct paths and relaying where traversal fails, while its planner measures each device's memory bandwidth, capacity and reachability, divides the model exactly for a fixed ring order, and places the head, which holds the embedding and output projection, together with that division rather than be

---

### [364] AnchorRep: Defending LLMs Against Cross-Model Adversarial Transfer via Representation Repulsion

**链接**: https://arxiv.org/abs/2609.32602
**作者**: Gal Wertheizer, Rom Himelstein, Tomer Peretz, Avi Mendelson
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Adversarial attacks optimized on a single open-weight LLM can transfer to and jailbreak architecturally different models, allowing an attacker with white-box access to one model to compromise independently deployed systems. This creates a shared vulnerability across models, yet existing defenses are not designed for this cross-model threat. We find that cross-model transfer aligns with shared internal representation geometry, making it a natural defense target. AnchorRep targets this geometry directly with a lightweight LoRA adapter that pushes the defended model's internal representations of harmful prompts away from those of a frozen anchor model on the same prompts. Training uses a small set of harmful prompts and no adversarial examples. Across five models and four architectural families, AnchorRep reduces cross-model attack success rate to <=1.1% on 2,000 transferred attacks (0% on two), including the largest drop on Mistral (36% -> 1.1%). Existing defenses can reduce transfer, bu

---

### [365] From Anomalies to Failures: Constructing Causal Error Graphs for Agentic Trace Diagnosis

**链接**: https://arxiv.org/abs/2609.32514
**作者**: Shu-Xun Yang, Yidong Wang, Zhuoer Feng, Bosi Wen, Jiayi Gui, Dayong Yang 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-driven agents are increasingly deployed in complex applications, where long agentic traces make failures difficult to diagnose. Existing trace diagnosis methods often conflate anomalies, errors, and failures, making diagnostic targets ambiguous; they also lack structured modeling of how causally relevant errors propagate and amplify into final task failures, resulting in unreliable failure attribution. To address these problems, we propose CEG-Agent, a tool-augmented agentic framework for causal diagnosis of agentic traces. Specifically, CEG-Agent introduces an explicit taxonomy of anomalies, errors, and failures, and constructs Causal Error Graphs (CEGs), a unified typed representation that links execution events, diagnostic nodes, and failure outcomes through causal relations. To evaluate causal trace diagnosis, we further construct CEG-Bench, a fully agent-annotated benchmark with high-confidence, consensus-derived CEG annotations obtained through an Adversarial Agentic Adjudica

---

### [366] How to Tame a Multi-Headed Hydra? Adaptive Multi-Category Safety Steering for Large Language Models

**链接**: https://arxiv.org/abs/2609.34514
**作者**: Chenxi Wang, Ruiyang Huang, Li Huang, Yifan Wu
**来源**: cs.CR cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As large language models (LLMs) become increasingly widespread, preventing unsafe responses to harmful prompts is essential for their safe deployment. Activation steering offers an approach to improving LLM safety by modifying internal activations during inference without updating model parameters. However, a single prompt can involve multiple harm categories, and steering toward safety in one category may leave harmful content from another unaddressed. Despite advances in adaptive steering, existing methods do not explicitly coordinate steering direction and strength when multiple harm categories co-occur within a single prompt. To address this problem, we propose CAM-Steer, a Category-Adaptive Multi-category Safety Steering framework. Specifically, it estimates the risk associated with each harm category by comparing the current hidden state with safe and unsafe prototypes. The estimated risks are then used to combine the safety directions for different harm categories into a single 

---

### [367] Hearsay: Can an Auditor Trust the Record a Deployed Agent Harness Writes?

**链接**: https://arxiv.org/abs/2609.32495
**作者**: Jiahong Dai, Zhuochen Yang, Pengyang Shao, Kelvin Ng, Zhongyi Liu, Chengquan Ju 等 (8 人)
**来源**: cs.CR cs.AI cs.CE cs.SE
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> An agent harness, the code that turns a model into an agent, writes its own record of each run, and that record is all a later reader gets when a run is disputed, investigated or audited. We call a record evidentiary when a reader who was not there can check it without trusting the writer. Across sixteen deployed frameworks, none writes one in full. Hearsay examines the record, not the task: five harnesses run fourteen tasks, three blinded LLM examiners and a human panel read the records, and every excerpt an examiner quotes is checked mechanically for who wrote it. First, the record lets a reader name the fault but not prove how the run went. Examiners name the right fault in 74 to 91% of 140 runs, but the fault can be proved only from two files the benchmark adds; for what happened in between, fewer than one citation in ten lands on anything the harness did not write, and the examiner with the fewest false alarms catches half of the entries we delete, rewrite or fabricate. Second, th

---

### [368] TermJudge: A Document-Level Metric Judging, Not Counting, Terminology in Machine Translation Evaluation

**链接**: https://arxiv.org/abs/2609.35017
**作者**: Nicolas Dahan (ISIR, ALMAnaCH), Fran{\cc}ois Yvon (MLIA, ISIR), Rachel Bawden (ALMAnaCH)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Existing automatic metrics for evaluating terminological use in machine translation (MT) penalise any divergence from a fixed reference, conflating translation errors with the valid terminological variation that human translators routinely produce. We introduce TermJudge, a document-level terminology metric that assigns an interpretable verdict to every term occurrence: glossary-conforming occurrences are settled deterministically, while divergences are assessed under a two-step LLM-as-judge procedure using the full document context: the first detects and labels terminology errors; the second sorts valid document-level variations from inconsistencies. Validated against expert error annotations and document-level human MQM scores, TermJudge ranks first in both system- and segment-level meta-evaluation, ahead of glossary-conformity and quality-estimation baselines. When applied to eight systems translating academic documents, under two prompting conditions, we observe that glossary injec

---

### [369] SignFLIP: A Unified Model for Sign Language Translation and Generation via Stage-wise Alignment at Scale

**链接**: https://arxiv.org/abs/2609.35225
**作者**: Zhaoyi An, Sihan Tan, Youngbae Hwang, Kazuhiro Nakadai, Rei Kawakami
**来源**: cs.CL cs.CV cs.MM
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Sign language translation and generation share the goal of bidirectional alignment between text and sign representations. However, existing approaches either treat them as isolated tasks or are only verified on limited datasets, limiting effective modeling between modalities. In this paper, we propose SignFLIP, a unified LLM-centered framework for translation and generation. To enable bidirectional mapping between text and sign, SignFLIP adopts a symmetric architecture together with a stage-wise training strategy built on large-scale data. The shared sign--text representation is progressively refined: pre-alignment facilitates subsequent SLT, while the SLT-adapted representation further benefits SLG. Extensive experiments on multiple benchmarks show that SignFLIP shows competitive performance compared with task-specific models on both translation and generation tasks, as well as strong transferability to sign language recognition.

---

### [370] On Device Agentic Operation Caches -- Classifier-Centric NL-to-Action Generation

**链接**: https://arxiv.org/abs/2609.33141
**作者**: Moghis Fereidouni and Anthony Arnold and Sumit Gulwani and Mark Marron and A.B. Siddique
**来源**: cs.AI cs.SE
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Agentic AI is increasingly being embedded in software applications to provide natural language interfaces to features and functionality. In most cases these agents are powered by enterprise (100+ billion parameter) or frontier class large language models that require substantial computational resources run and depend on cloud hosted inference to handle the task of transforming natural language inputs into actionable software operations. This reliance on cloud-hosted inference introduces substantial network latency on top of LLM inference times, creates data privacy concerns, and, given the costs of running these models, can rapidly escalate expenses associated with supporting agentic features. This paper introduces a novel means of converting the NL-to-Action problem from a generative one into a classification-centric formulation via on-device operation caches. These caches allow an agentic system to handle frequently occurring classes of actions completely on-device -- reducing latenc

---

### [371] TableSeek: Structure-Preserving Agentic Evidence Seeking over Heterogeneous Table Corpora

**链接**: https://arxiv.org/abs/2609.34157
**作者**: Jiaming Tian, Liyao Li, Wentao Ye, Haobo Wang, Lihua Yu, Zujie Ren 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Open-domain table retrieval seeks tables that contain sufficient evidence for answering a question or verifying a claim. Yet semantic relevance is often misleading: topically similar tables may lack the required facts, while answer-bearing evidence is often confined to a few cells whose meaning depends on surrounding schema and table context. Heterogeneous schemas, value formats, and serializations further weaken one-shot matching. We present TableSeek, a structure-preserving agentic search framework for heterogeneous table corpora. Instead of ranking tables once, an LLM agent iteratively follows sparse clues, inspects schema-preserving previews, identifies schema- and value-level mismatches, and refines its investigation. TableSeek uses cells and schemas as evidence anchors while retaining complete tables as evidence units, enabling fine-grained localization without losing the context required for interpretation and answerability checking. Without relying on retriever training or a pr

---

### [372] When Does Structured Knowledge Help Neural Theorem Proving?

**链接**: https://arxiv.org/abs/2609.34460
**作者**: Sareh Nabi, Roland Vogl, Marzieh Nabi
**来源**: cs.AI cs.LG cs.LO
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Does structured mathematical knowledge help LLMs prove theorems in Lean 4? If so, for which models, and does the answer vary by problem? Formal libraries such as Mathlib encode 285,000+ verified theorems with syntactic dependencies, but the semantic layer mathematicians rely on for discovery (analogies, generalizations, cross-domain bridges) remains implicit. We introduce MathAgent, which builds this layer as a knowledge graph, MathKG, and uses it to augment LLM theorem provers. MathKG connects 364 Mathlib theorems and definitions by 9,434 typed semantic edges inferred via LLM-based relation extraction anchored to verified Mathlib declarations. We run a controlled ablation across four augmentation modes (no context, knowledge-graph context, Mathlib retrieval, both) and five models: Qwen3-8B/32B, their Lean-specialized derivatives Goedel-Prover-V2-8B/32B, and Claude Sonnet 4.6, on miniF2F, plus PutnamBench and MathOlympiadBench for Sonnet. Three findings emerge. (i) Specialization domin

---

### [373] SeOPD: Self-Evolving LLMs via Online Policy Distillation from Self-Generated Chain-of-Thought

**链接**: https://arxiv.org/abs/2609.33181
**作者**: Xiaoshu Chen, Xiangyu Wong, Sihang Zhou, Ke Liang, Xinwang Liu
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent advances in online policy self-distillation (OPSD) have demonstrated that large language models (LLMs) can improve their capabilities by leveraging external privileged information (PI), such as manual annotations or feedback from external environments. However, obtaining accurate annotations and constructing sophisticated environments often require substantial human effort and computation, limiting the scalability of OPSD. While a few recent studies have explored self-improvement without external PI, the resulting gains remain limited. In this work, we explore whether LLMs can achieve comparable self-improvement without external PI. Our key observation is that a single LLM can support multiple reasoning modes, such as deep-thinking and non-thinking modes, with deep thinking generating additional information during reasoning. Based on this observation, we propose Self-Evolving Online Policy Distillation (SeOPD), which enables LLMs to distill and internalize information generated 

---

### [374] MedRouter: Demystifying Knowledge Differences Across Medical LLMs for Routing-Based Reasoning

**链接**: https://arxiv.org/abs/2609.33119
**作者**: Lang Cao, Binghang Lu, Yuhao Shen, Yue Guo
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Medical question answering spans diverse specialties and modalities, and individual medical large language models (LLMs) exhibit distinct strengths across tasks and domains. This heterogeneity suggests that combining specialists may enable broader coverage of medical questions than relying on any single model. However, existing LLM routing methods primarily seek to balance answer quality and inference cost, leaving open how to exploit differences in specialist competence to improve medical reasoning. In this paper, we introduce MedRouter, an agentic system that uses an embedding-based multi-label router to select and query specialist LLMs, then passes their responses to a generator to produce the final answer. We further propose SCALE (Specialist Competence-Aware Learning), a two-stage training framework that first trains the Router with specialist correctness supervision and then optimizes its selections through reinforcement learning. The second stage uses a Performance Gain Reward (

---

### [375] Choir: An Open Protocol for Distributed Multi-Agent Autoformalization

**链接**: https://arxiv.org/abs/2609.31903
**作者**: Yidi Qi and Melanie Weber
**来源**: cs.AI cs.CL cs.LO cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> AI agents can now formalize entire textbooks and major theorems in proof assistants such as Lean, but current efforts are typically centralized: a single team runs all agents and bears the full computational cost. We introduce Choir, an open protocol for distributed formalization. Choir decomposes a project into tasks that can be completed by independent contributors, each running their own agent with their own LLM subscription, while coordinating entirely through the project's GitHub repository. To support open participation, every contribution is checked by a deterministic gate before merge. Choir supports Lean 4, Isabelle, and Rocq, and is open source and modular, allowing projects to replace individual components or extend the protocol.

---

### [376] Adapt Semantics, Not Structure: Few-Instance Schema Calibration for Scientific PDF Extraction

**链接**: https://arxiv.org/abs/2609.34841
**作者**: Zixiao Dong, Wei Yang, Zihao Liu, Chenshu Li, Longzhang Liu, Tao Tan 等 (7 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A well-designed extraction schema is not necessarily ready for reliable LLM execution. When only limited verified extractions are available, manually tuning hundreds of field definitions through trial and error is costly. We frame this problem as few-instance schema calibration: adapting the operational semantics of an existing schema from a few annotated documents while preserving its structural contract. We introduce CPSE, a contract-preserving semantic extraction framework that jointly calibrates extraction prompts and field-level semantic descriptions from a few gold annotations. CPSE decomposes the schema into an invariant structural contract and mutable field semantics, and further separates identity discovery from record completion using manifest-conditioned resolution. On expert-annotated polymer-science documents, CPSE improves extraction by 9.93 points over an execution-matched baseline, with consistent gains under an independent judge and in a blinded expert audit. These res

---

### [377] Self-Evolving Time-Series Forecasting Agents with Episodic Memory and Online Policy Learning

**链接**: https://arxiv.org/abs/2609.32689
**作者**: Junyi Wang, Yilin Wang, Wen Wu, Chao Zhang
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based agents are increasingly used for time-series forecasting because they can organise contextual information, perform multi-step analysis, and guide the sequence of actions required to complete forecasting tasks. Most existing agents focus only on the current forecasting instance. However, in real-world deployments, forecasting commonly operates online, with new forecasts issued from the currently available history as the forecast origin advances and the ground-truth targets of earlier instances progressively become available. These targets provide feedback on the actions taken in earlier instances, yet existing agents generally do not preserve or utilise this information to adapt their subsequent actions. To address this limitation, we introduce FASE, a Feedback-Aware Self-Evolving forecasting agent that converts such feedback into task-specific experience for subsequent forecasting instances. FASE combines episodic memory, which retrieves relevant completed instances, with onl

---

### [378] Cross-Rollout Bellman Closure for Long-Horizon Agentic Reinforcement Learning

**链接**: https://arxiv.org/abs/2609.35082
**作者**: Yangyang Ren, Haodong Zhu, Linlin Yang, Sheng Xu, Peichao Lai, Baochang Zhang
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Group-based reinforcement learning such as GRPO trains LLM agents by comparing rollouts sampled for each task, without a learned critic. In long-horizon settings, these rollouts revisit shared anchor states, offering cross-rollout evidence for step-level credit. Ideally, step-level credit should incorporate evidence beyond the realized suffixes observed at an anchor while aggregating alternative continuations according to their empirical frequencies. Visit-local averaging pools realized suffix returns at shared anchors and respects observed frequencies, but does not recursively propagate evidence across rollouts, whereas shortest-path estimators have global reach but allow a rarely observed route to dominate an anchor's value. We introduce Cross-Rollout Bellman Closure (CRBC), which merges each rollout group into a finite empirical process with absorbing success and failure boundaries and evaluates its behavior-policy Bellman fixed point with one linear solve. This fixed point uses the

---

### [379] Adaptive Consistency Graph for Long-Horizon Agents

**链接**: https://arxiv.org/abs/2609.32754
**作者**: Jiecong Wang, Hao Peng, Zhanyi Wang
**来源**: cs.AI cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model agents can often make reasonable local decisions on short tasks, yet their performance degrades when success requires long sequences of dependent actions and tool calls. During execution, task requirements, historical evidence, and the current execution state may gradually become disconnected, so later decisions can drift from the original objective. We study this problem by introducing the Adaptive Consistency Graph (ACG) for long-horizon execution. ACG incrementally organizes execution evidence and its provenance in a persistent graph, then constructs a temporary requirement-centered view for each decision under a bounded context budget. Rather than replacing the base agent's planner or tool executor, ACG provides a structured and traceable context view for each decision. In the matched evaluation, ACG improves GPT-5.6-luna's average success from 44.5\% with ReAct to 50.2\%, with the largest gain on BrowseComp-Plus (73.5\% versus 62.4\%). We further analyze traje

---

### [380] IndicFDB: Benchmarking Full-Duplex Voice Agents across Indian Languages

**链接**: https://arxiv.org/abs/2609.31967
**作者**: Rajarshi Roy, Shobhit Banga, Jonathan Raiman, Supriya Paul, Bhaskar Singh, Manmeet Kaur 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Full-duplex voice agents must handle pauses, take turns, backchannel, and respond to user interruptions in real time. Full-Duplex-Bench evaluates these behaviors, but its English-only corpus and reliance on word-timestamped ASR and an English-prompted LLM judge make it difficult to extend to Indian languages. We introduce IndicFDB, which extends it to ten languages spoken in India with 12,350 samples, nearly 17 times as many as the original. We address three challenges: finding conversational events in multilingual speech, evaluating their timing without reliable word-level alignment, and judging responses across languages. We mine pause handling, turn taking, and backchanneling samples from roughly 50,000 hours of channel-separated conversations using voice activity detection (VAD), and construct human-validated synthetic user interruption samples. Language-independent VAD heuristics evaluate timing, while an open-weight transcription and translation pipeline converts responses to Eng

---

### [381] Evidence-Inference Reconstruction: When The Evidence Is Recalled But The Reasoning Goes Wrong

**链接**: https://arxiv.org/abs/2609.33778
**作者**: Megan Diehl and Ser-Nam Lim
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Modern multi-hop LLM agents are equipped with built-in mechanisms to detect errors in intermediate reasoning steps. Such errors trigger corrective actions from these agents, which mostly follow the paradigm of retrying the steps or the reasoning trajectories. Not only are these retries expensive, we present in this paper that they are also potentially unnecessary. To this end, we introduce Evidence-Inference Reconstruction (EIR), which uses structured state to guide one retrieval trajectory, accumulating source evidence in the process. We show that as long as the relevant evidence has been collected, EIR is capable of generating the correct answer in a single final model call even if erroneous evidence has been mixed in due to incorrect intermediate reasoning steps. In one evaluation, using Haiku 4.5 and GPT-4.1 Mini, we evaluate EIR on matched 1,000-question subsets of HotpotQA, 2WikiMultiHopQA, and MuSiQue, showing that EIR improves Answer F1, the overlap between the model's and the 

---

### [382] Can AI Make Money in Crypto? Measuring the Gap from Backtests to Real Markets

**链接**: https://arxiv.org/abs/2609.34510
**作者**: Xingtong Yu, Jiarun Zhou, Guanlin Ding, Wenkang Wei, Jiarui Liu, Chang Zhou 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> AI-based trading methods have rapidly evolved from machine learning and reinforcement learning to large language models (LLMs) and trading agents, yet their performance is still predominantly assessed through historical backtesting. Such evaluations provide limited evidence of whether a method can generalize to unseen future markets or whether its backtested performance can be sustained in realistic trading frictions (e.g., latency, slippage, liquidity constraints, and market impact). We present a unified benchmark that evaluates representative machine learning, reinforcement learning, LLM-based, and agent-based trading methods in cryptocurrency markets through three progressively more realistic stages: historical backtesting, prospective exchange-based paper trading, and real-money live trading. These stages jointly increase temporal realism by moving from historical to unseen future markets, and execution realism by moving from offline simulation toward live trading. This protocol en

---

### [383] Where Do Test-Time Scaling and Training Fall Short in Individual Stance Prediction?

**链接**: https://arxiv.org/abs/2609.33155
**作者**: Yuyang Zhao, Xuan Liu, HaoYang Shangm Haojian Jin
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Test-time scaling and post-training have improved LLM performance in coding and mathematical reasoning, but their effectiveness for individual stance prediction remains unclear. We study this question by predicting a person's stance in a new discussion from their history. We evaluate widely used test-time scaling strategies and post-training methods, such as supervised fine-tuning and reinforcement learning, and identify four failure modes across generation, selection, and learning: (1) incorrect consensus, where repeated samples agree on the wrong stance; (2) selection failure, where generation covers the observed stance but selection misses it; (3) response overfitting, where supervised fine-tuning improves imitation but harms prediction; and (4) early plateau, where reinforcement learning shows modest initial gains followed by limited further improvement. We expose these failures using STANCE-BENCH, which contains 2499 prediction tasks from 500 Hacker News users. Guided by this anal

---

### [384] SALMONN-duo: Adaptive Dual-System Coordination for Full-Duplex Voice Agents

**链接**: https://arxiv.org/abs/2609.34247
**作者**: Wenyi Yu and Siyin Wang and Terumi Chiba and Xianzhao Chen and Xiaohai Tian and Jun Zhang and Lu Lu and Chao Zhang
**来源**: cs.CL eess.AS
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Full-duplex speech large language models (LLMs) enable low-latency, natural voice interaction. However, real-world agents must also use tools and perform deliberative reasoning-operations whose variable latency and computational cost conflict with the stringent timing requirements of real-time conversation. To reconcile these demands, we propose SALMONN-duo, an adaptive dual-system voice agent inspired by dual-process theories of cognition. SALMONN-duo separates real-time interaction from deliberative computation by pairing an always-on, fast-thinking full-duplex speech LLM (system 1) with a powerful asynchronous slow-thinking LLM agent (system 2). Beyond handling real-time interaction, system 1 learns when to answer directly and when to delegate, remaining responsive during backend execution and seamlessly integrating returned information into the ongoing dialogue without exposing tool traces or losing conversational context. Evaluations on single-turn spoken question answering (QA) a

---

### [385] TRACE: Single-Pass Decoding-Trace Risk Localization for Generation Calibration

**链接**: https://arxiv.org/abs/2609.35387
**作者**: Yuebin Xu, Xuemei Peng, Junlan Chen, Zhiyi Chen, Zeyi Wen
**来源**: cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reliable confidence estimation is essential for large language model deployment. However, answer-level calibration remains challenging because generation errors are often localized: a response may be fluent and high-probability overall while still failing at a critical number, entity, or factual claim. Existing estimators compress token probabilities, sequence likelihoods, entropy, or beam statistics into a global score, which can dilute such local risk signals. We propose TRACE, a single-pass, decoded-answer-preserving confidence estimator that treats decoding-time uncertainty as a trajectory through three steps: (i) recording token-level surprisal and predictive entropy during decoding, (ii) applying local risk operators to preserve uncertainty spikes, and (iii) converting localized trace risk into answer-level confidence. TRACE produces a label-free risk score, while TRACE+ calibrates trace-only features into probabilities using a held-out split, without extra generations or externa

---

### [386] Understanding On-Policy Distillation: A Mechanistic Interpretability Perspective via Sparse Crosscoders

**链接**: https://arxiv.org/abs/2609.35210
**作者**: Zichao Yu, Qianshuo Ye, Xu Wang, Difan Zou
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> On-policy distillation (OPD) is a widely adopted post-training technique for LLM reasoning. It is commonly believed to transfer knowledge from a stronger teacher, yet what OPD actually distills into the student's internal representations remains unclear. We study this question with sparse crosscoders, which learn one feature dictionary shared by the student before and after OPD and the teacher. Standard crosscoder analyses, however, identify model-specific features but cannot tell how a model's use of its features changes, since all models are encoded into one set of feature activations. We therefore propose the swap readout, which reads each student checkpoint's feature activations on its own, measuring how training changes the student's use of each feature, even for checkpoints unseen by the crosscoder. Across three OPD settings, we find that OPD neither creates features nor passes on the teacher's own, and leaves the firing rates of over 98% of the student's frequently used features

---

### [387] BiasReducer: Adaptive Bias Mitigation for Reward Models

**链接**: https://arxiv.org/abs/2609.32720
**作者**: Shuang Liu, Yongliang Miao, Yanguang Liu, Haoyi Xiong, Mengnan Du
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reward models score responses from large language models (LLMs) and guide LLM training toward human preferences. However, reward models can favor superficial attributes such as length or confidence, leading LLMs to produce higher-scoring but not more correct responses. Existing mitigation methods either retrain the reward model or apply a fixed correction to one known bias, such as a preference for longer responses. Retraining requires additional data and computational resources, while existing editing methods require the target bias to be specified in advance and use a fixed edit for that bias. To this end, we propose BiasReducer, a lightweight framework that edits only the linear reward head and selects the relevant edits for each new dataset. First, BiasReducer uses a sparse autoencoder (SAE)-style encoder to learn which attributes (e.g., length and confidence) the reward model is sensitive to. Second, it learns how to reduce the reward model's dependence on each attribute by determ

---

### [388] You Only Edit Once: Incentivizing In-Context Capability of LLMs via Local Demonstration Refinement

**链接**: https://arxiv.org/abs/2609.33609
**作者**: Jiarong Wen, Qi Wang, Yun Qu, Yixiu Mao, Heming Zou, Haoang Chi 等 (10 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In-context learning (ICL) is crucial for boosting the inference performance of large language models (LLMs). However, the effectiveness of ICL in LLMs is greatly influenced by the choice of demonstration sets. Exhaustive searches over these sets are combinatorial, and existing selectors often rely on relevance or likelihood proxies to implicitly assess ICL quality. Making repeated queries to the target LLM with these strategies can incur substantial costs. This work simplifies selection by framing it as a constrained local search problem and presents local demonstration editing (LDE). Starting with an initially retrieved set of demonstrations, LDE employs a single structured edit to explore its surrounding neighborhood while balancing performance gains with search costs. Technically, LDE is reduced to a policy search problem, for which we train a small LLM, referred to as Jev-LDE. This model as the System-1 modifies the retrieved demonstration set by performing actions such as \texttt{

---

### [389] Silent Failures in Agentic Security Evaluation: A Validated Harness for Tool-Call Mediation Under Indirect Prompt Injection

**链接**: https://arxiv.org/abs/2609.32691
**作者**: Animesh Shaw
**来源**: cs.CR cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents that invoke privileged tools are vulnerable to indirect prompt injection (IPI), in which adversarial instructions embedded in retrieved data hijack the agent's actions. A growing body of work evaluates defenses against IPI, but the validity of that evaluation is rarely examined. We audit an IPI benchmark and its harness and identify four defect classes -- silent payload non-delivery, attack success scored by tool identity rather than arguments, false-rejection rate conflated with model incapacity, and the absence of an audit trail -- each of which yields a plausible, publishable, and incorrect number. We quantify the distortion by re-scoring identical execution traces under the defective and corrected definitions: on real agent behaviour, the tool-identity scorer reports a 21.7% attack-success rate where the true argument-level rate is 1.2%. In the sharpest case, an open model previously reported at 62.8% registers 0% under the corrected harness -- the prior figure largely a

---

### [390] ORBIT: A Framework for Multi-Agent Safety and Security Evaluations

**链接**: https://arxiv.org/abs/2609.33102
**作者**: Ben Hagag, William L. Anderson, Srija Chakraborty, Christian Schroeder de Witt
**来源**: cs.MA cs.CR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-agent LLM systems are increasingly deployed for complex, long-horizon tasks or emerge as a natural consequence of agents interacting in the wild. Yet they give rise to significant safety and security risks: the flexible protocols that enable task generalization also expose novel threats, from cascading prompt injection to inter-agent collusion. Progress in defending against these threats has been slowed by a lack of shared empirical infrastructure, which forces bespoke environment development for every new defense and makes standardized comparison impossible. Existing evaluations address isolated threat models or single-agent settings, but none jointly vary attack, defense, and architecture across realistic multi-agent environments. To address this gap, we introduce ORBIT, a configurable evaluation framework for empirical multi-agent safety and security research, built on UK AISI's Inspect. ORBIT lets researchers configure communication topologies, memory, scheduling, and agent r

---

### [391] DISCO: Distributed Long Context Scaling with Grounding-Reasoning Disaggregation

**链接**: https://arxiv.org/abs/2609.33485
**作者**: Guanzheng Chen, Viet Dac Lai, Subhojyoti Mukherjee, Branislav Kveton, Seunghyun Yoon, Franck Dernoncourt 等 (8 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> While Large Language Models (LLMs) advertise million-token context windows, reasoning quality often collapses as inputs grow -- a phenomenon termed context rot. This failure stems from a structural entanglement in monolithic architectures, where the massive search burden of contextual grounding exhausts the representational capacity needed for complex reasoning. To resolve this, we propose Grounding-Reasoning Disaggregation via DIStributed long COntext scaling (DISCO). Inspired by distributed computing frameworks like Apache Spark, DISCO partitions long context across a fleet of Worker LLMs dedicated exclusively to parallel, localized grounding. A central Driver LLM, trained via Reinforcement Learning (GRPO) to optimize planning, orchestrates execution by dynamically mapping queries into atomic extraction tasks and reducing the gathered evidence to synthesize a final answer. By isolating reasoning from raw context noise, DISCO effectively eliminates context rot. On RULER-QA (1M tokens)

---

### [392] Downstream-Aware Context Selection for Online In-Context Reinforcement Learning

**链接**: https://arxiv.org/abs/2609.33166
**作者**: Ruihan A. Li, Shangtong Zhang, Rohan Chandra
**来源**: cs.LG
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In-context reinforcement learning (ICRL) enables large language model agents to adapt to new environments using their interaction history without updating model parameters. However, repeatedly conditioning on growing histories can lead to substantial token cost. We propose a bounded-history context-management framework that predicts the task-dependent downstream effect of removing historical interactions to guide history selection and determine a decision-dependent context budget. Formally, our framework uses the full rolling history as a reference. The predictor evaluates removal effects, defines a deletion ordering, and applies a shared selection criterion to determine how much history to retain at each decision. We evaluate the method in closed-loop SUMO driving under held-out in-distribution, unseen-domain, and unseen-route settings, and in ScienceWorld under a continual ICRL protocol. Relative to a baseline using the full context, our method reduces total token usage by 25.7%, 25.

---

### [393] Decision-Sufficient State Representations: Measuring and Reducing Write-Time Regret

**链接**: https://arxiv.org/abs/2609.32805
**作者**: Bingyu Shen, Boyang Li
**来源**: cs.AI cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long tasks produce more history than an LLM agent can hold in its context, and more than it uses reliably even when the history fits. A growing line of work therefore has agents carry a short written state instead: at every step a writer rewrites the state, and a reader acts from the state alone. Steps stay cheap, but anything the writer drops is lost before later decisions reveal that they need it. We quantify this loss and ask whether training can reduce it. Comparing the written state with the best state of the same size written in hindsight, we split the reader's loss into a budget loss, which any state of that size must incur, and a write-time regret, which comes from the writer's choices. In TextWorld cooking games where we control how long a fact must be carried before it is needed, a 128-token state holding the facts wins nearly every game, while prompted language-model writers win at most 17%. Almost all of the loss is write-time regret, and it grows with the delay. We then tr

---

### [394] ReSight-SMC: Two-Stage Power Sampling via Island SMC with Visual Scouts

**链接**: https://arxiv.org/abs/2609.34905
**作者**: Yaowen Zhang, Xiangyu Qiu, Junyi Hu, Zhi Lu, Wenwen Tian, Aoqin Wang 等 (8 人)
**来源**: cs.CV
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Power sampling has emerged as a training-free approach to LLM reasoning, eliciting capabilities comparable to reinforcement learning by sharpening the model distribution over complete responses. Despite this success, power sampling remains underexplored in large vision-language models (LVLMs). We transfer Power-SMC to LVLM decoding by defining a sequence-power target conditioned on both the image and the prompt. This direct transfer provides a strong training-free baseline, but leaves two aspects of finite-particle multimodal inference unaddressed. At the particle level, global resampling can collapse genealogies, while particle-based power sampling does not diversify trajectories through distinct visual cues in multimodal decoding, limiting exploration under a finite particle budget. At the answer level, sequence-level sharpening makes distinct reasoning trajectories compete even when they support the same answer. We introduce ReSight-SMC, a verifier-free two-stage power sampler for L

---

### [395] QuantaSpike: Short-Window Spike-Driven Quantization for Large Language Models

**链接**: https://arxiv.org/abs/2609.34259
**作者**: Bang Hu, Guowei Zhu, Changze Lv, Xiaoqing Zheng, Fengzhe Zhang, Fan Zhang 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) achieve strong performance across many tasks but rely on dense multiply-accumulate (MAC) operations during inference, resulting in high energy cost. Spiking neural networks (SNNs) offer an event-driven alternative in which synaptic integration uses lightweight accumulation. However, spike-driven LLM inference remains difficult because outlier-heavy activations typically require long firing windows or auxiliary non-spiking paths. We propose QuantaSpike, a short-window spike-driven quantization framework for LLMs built around Logarithmic Ternary Integrate-and-Fire (LTIF) neurons. LTIF uses ternary events with power-of-two membrane-response quanta, improving the information represented by each firing step while retaining shift-ACC-compatible computation. QuantaSpike combines this neuron with group-adaptive gain and selective outlier admission: normal values use residual LTIF steps, whereas admitted outliers receive one additional onset spike before entering th

---

### [396] Robust Hierarchical Structures for Agentic Document Analysis

**链接**: https://arxiv.org/abs/2609.33322
**作者**: Ruiying Ma, Yiming Lin, Aditya G. Parameswaran
**来源**: cs.DB cs.AI cs.CL cs.IR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) enable us to better understand text documents, including PDFs and Word documents. However, LLMs, as well as more modern LLM agents, i.e., those with tool-calling abilities, typically treat such documents as plain text, ignoring the fact that they are often organized hierarchically into sections and subsections. Extracting this structure, while difficult, can improve efficiency and effectiveness for agents (and humans)---since only sections relevant to a given task need to be processed. Unfortunately, prior work on structure extraction provides no formal guarantees on how well the inferred structure matches the true one. Instead, we target a robust and compact variant that is feasible to infer and useful in practice. Robustness ensures that the text under each subsection header is a superset of the text under the same header in the true structure. Compactness seeks to minimize this superset, reducing agentic cost (or human cognitive load). We propose SHED, a

---

### [397] ConRAG: Lightweight inference of multi-hop relations

**链接**: https://arxiv.org/abs/2609.35193
**作者**: Kilian B\"anziger, Sonia Laguna, Markus Kreft, Robert Jakob, Kevin O'Sullivan, Lasse B. Strand 等 (7 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Understanding how two entities are connected often requires tracing multi-hop relations across documents to identify intermediate entities and supporting evidence that explain a connection. This is a task that appears frequently in scientific research and other knowledge-intensive analyses. We formalise this setting as multi-hop relation inference: given two known endpoint entities, we aim to recover the bridge entities and evidence-grounded reasoning chains that connect them across a document corpus, and to generate an explanation grounded in the retrieved evidence. Existing multi-hop RAG systems typically seek an unknown answer entity rather than explicitly recovering the connection between two known endpoints and graph-based approaches often rely on costly LLM-extracted knowledge graphs that limit scalability to large document collections. We introduce ConRAG, which builds a lightweight entity-document graph from entity co-occurrence and LLM-based entity filtering. Its connective re

---

### [398] ExpVoyager: Direct Experience Navigation for Dynamic Agent Skill Synthesis

**链接**: https://arxiv.org/abs/2609.32630
**作者**: Kwangwook Seo, Dongha Lee
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Learning from experience in LLM agents has become a key paradigm for developing self-evolving agents that continuously learn and expand their capabilities. Within this paradigm, synthesizing the agent skill has emerged as a promising solution for transforming accumulated experience into reusable procedural knowledge, serving as an important layer for the harness system that supplies agents at runtime. Despite its potential, existing approaches largely abstract past experience into fixed procedural knowledge before downstream demands are known, which risks discarding knowledge that later becomes critical while retaining instance-specific details irrelevant to future tasks. In this paper, we reframe agent skill synthesis as a dynamic navigation problem over past experience, where agents actively explore accumulated trajectories on demand for the current task with targeted and fine-grained access to experience knowledge. To this end, we propose ExpVoyager, a novel framework in which a ski

---

### [399] NLPG: Natural-Language Policy Gradients for Self-Evolving Language Agents

**链接**: https://arxiv.org/abs/2609.33379
**作者**: Xu Liu, WenZhang Wei, Jun Cao, Dehua Peng, Huan Chen, Zhipeng Gui 等 (7 人)
**来源**: cs.CL cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model agents increasingly rely on compound programs for retrieval, tool use, reasoning, and verification, yet their failures often arise from local procedural decisions. Existing reinforcement-learning and prompt-optimization approaches typically rely on scalar rewards or repeatedly modify entire prompts, making it difficult to capture and reuse procedural improvements while preserving a frozen agent. To address this problem, We propose Natural-Language Policy Gradients (NLPG), an external policy-memory method for improving a fixed agent without changing its model parameters or program structure. NLPG diagnoses execution traces, propagates downstream feedback backward through the module graph, and converts recurring failures into route-local natural-language corrections that are aggregated into bounded policy updates for subsequent executions. Across six benchmarks covering memory, reasoning, instruction following, and evidence verification, NLPG also outperforms the str

---

### [400] TemporalGraphLLM: Temporal Graph Neural Networks with Large Language Models for Dynamic Text-Attributed Graphs

**链接**: https://arxiv.org/abs/2609.31881
**作者**: Moran Beladev, Or Eitan, Gilad Katz, Lior Rokach
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Dynamic text-attributed graphs (DTAGs), where nodes, edges, and textual attributes evolve over time, are crucial in applications such as social networks, citation graphs, and knowledge graphs. However, existing approaches struggle to jointly model the temporal evolution of graph structures and the semantic richness of textual attributes. While Temporal Graph Neural Networks (TGNNs) capture evolving node relationships, they often lack contextual text reasoning. Conversely, Large Language Models (LLMs) excel in textual understanding but struggle with structured graph reasoning in temporal settings. To bridge this gap, we propose TemporalGraphLLM, a novel framework that can integrate any temporal GNN with an LLM for enhanced reasoning in DTAGs. Our approach fine-tunes LLMs using graph-time-aware instruction tuning and novel temporal GNNs injection to replace dedicated added tokens with graph embeddings. TemporalGraphLLM effectively leverages pretrained TGNNs within an LLM framework to ach

---

### [401] Ask Without Telling: Local SLMs Consult Cloud LLMs Without Revealing Task Intent

**链接**: https://arxiv.org/abs/2609.32642
**作者**: Yanmeng Wang, Yunxuan Li, Shilong Fan, Yuhan Zheng, Tsung-Hui Chang
**来源**: cs.CR cs.AI cs.DC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As local small language models (SLMs) increasingly collaborate with more capable cloud large language models (LLMs), a natural privacy question arises: Can a local SLM obtain cloud LLM guidance while protecting user privacy? Existing privacy-preserving SLM-LLM frameworks primarily hide sensitive values while preserving task semantics, which can still expose what the user is trying to accomplish. For example, allocating scarce medical supplies across hospitals may signal an emerging public-health emergency, while rebalancing an investment portfolio may reveal a private investment strategy, even when names and numerical values are hidden. Recent decoy-based methods further obscure task intent by hiding the real request among alternatives, but stronger protection relies on more decoys or semantic abstraction, increasing overhead or risking utility loss. More fundamentally, existing work does not systematically characterize the components of private task intent or how each should be protec

---

### [402] Test-Time Scaling via Budgeted Multi-Attribute Verification

**链接**: https://arxiv.org/abs/2609.34322
**作者**: Bo Xue, Ji Cheng, Shen-Huan Lyu, Yuanyu Wan, Shuang Qiu
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Verifying LLM-generated answers under a shared computational budget requires jointly deciding which candidates to inspect and which verification attributes to evaluate. We formulate this problem as multi-attribute good-arm identification under a global budget: each candidate is an arm evaluated along several costly attributes, and the goal is to certify as many candidates as possible whose mean scores exceed the prescribed thresholds on all attributes. We propose \textsc{BMA-GAI}, an algorithm that combines cost-aware arm selection with adaptive sampling of attributes. Every observation serves both to guide adaptive allocation and to support anytime-valid certification, which removes the need for a separate confirmation stage. We establish an asymptotic coverage guarantee for \textsc{BMA-GAI} and derive a matching information-theoretic converse that characterizes the intrinsic complexity of the problem, thereby proving that \textsc{BMA-GAI} is first-order optimal away from critical bud

---

### [403] ReplayLens: Auditing Agents' Use of Outcomes

**链接**: https://arxiv.org/abs/2609.34177
**作者**: Dong Xu, Zhangfan Yang, Jiantao Wu, Shipeng Zhang, Zexuan Zhu, Jiangqiang Li 等 (8 人)
**来源**: cs.AI cs.LG cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> When an agent reuses logged experience, a changed decision may reflect the recorded score, the action's name, or the record's position in storage. Standard memory evaluations do not reveal which relationship drives that change. We introduce ReplayLens, a black-box audit that changes one relationship in the stored history at a time, holds the remaining interface fixed, and measures the resulting decision. Four interventions target four relationships. Outcome reassignment swaps which scores belong to which actions. Pair transport moves intact action-score pairs to new record slots. Consistent renaming relabels actions in both history and menu. Key-slot reassignment changes both score attachment and position. A constructive separation shows why the audit is needed: two memory writers with identical endpoint accuracy respond differently to the same replay, so conventional evaluation cannot resolve the underlying dependence. On black-box LLM interfaces, swapping scores changes decisions whi

---

### [404] Agentic High-Dimensional Bayesian Optimization with Hypothesis- and Evidence-Guided Search

**链接**: https://arxiv.org/abs/2609.34281
**作者**: Zhixuan Gao, Ke Xue, Rongxi Tan, Ming Chen, Chao Qian
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> High-dimensional Bayesian optimization (HDBO) seeks sample-efficient optimization when the number of variables is large relative to the evaluation budget. Recent LLM-based and agentic BO methods incorporate task knowledge and adapt search decisions during a run, but have primarily been evaluated on low- and moderate-dimensional problems. We ask whether this paradigm can transfer to the higher-dimensional regime. Our experiments show that these methods do not remain reliable in the high-dimensional regime, where the challenge is not only where to evaluate, but also which modeling assumption and search geometry to use when the objective's useful structure is unknown. We therefore introduce HERA, a Hypothesis- and Evidence-guided Research Agent that uses task context, optimization feedback, and structural diagnostics to revise search hypotheses, select and configure HDBO strategies, and determine their execution length. PRISM, its numerical optimization engine, generates and evaluates can

---

### [405] OptiArena: Can LLMs Improve Executable Algorithms under Fixed Resource Budgets?

**链接**: https://arxiv.org/abs/2609.32227
**作者**: Wenjun Peng, Xinyu Wang
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Static QA and code-generation benchmarks only partially capture the role that large language models (LLMs) now play as coding agents and research tools. We introduce OptiArena, a budget-controlled testbed for studying whether LLMs can improve executable game-playing algorithms through five rounds of code edits within a fixed minimal scaffold and under bounded evaluator feedback and fixed resource budgets. The testbed uses two optimization regimes, surface obfuscation controls, calibrated references, held-out/stress splits, and diagnostics for degradation and exceptional failures, with LLM API cost reported separately from local evaluator wall-clock. The empirical study asks three questions: whether models can close the calibrated gap between a designated weak starter and an editable competent baseline, whether they can refine editable competent baselines without damaging them, and whether gains survive surface obfuscation controls. Across twelve frontier LLMs and five games, models imp

---

### [406] FinancialAuditBench: Benchmark Construction under Differential Privacy Using Real-World Priors

**链接**: https://arxiv.org/abs/2609.32835
**作者**: Jerry Huang and Sarvesh Babu and Matt Van Buren and Alexander Wang and Pranav Pillai and Arush Jain and James P. Burton and Julia Hockenmaier
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As AI agents are becoming widely adopted in the financial services industry, careful measurement is essential to understand where they can be reliably deployed and where oversight and professional review remain necessary. Such measurement, however, is constrained by limited access to proprietary or privacy-sensitive data. Existing benchmarks therefore often rely on publicly available data, human- and/or LLM-authored tasks, or simplified settings. We introduce FinancialAuditBench, a benchmark for evaluating agents on financial statement audit tasks, along with a framework for systematically generating synthetic engagements. Our task generation framework leverages differentially private aggregate statistics from historical audits along with audit expertise contributed through over 1,100 hours of benchmark development and review. FinancialAuditBench consists of 90 tasks spanning workpaper completion and review across six synthetic audit engagements, each containing an average of 179 files

---

### [407] From Granular Revision Operations to Meaningful Revision Units: Evaluating LLMs for Revision Boundary Detection

**链接**: https://arxiv.org/abs/2609.33720
**作者**: Yu Tian, Andrew Potter, Katerina Christhilf, Motahareh Darvishpour Ahandani, Jessica Early, Steve Graham 等 (7 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Revision traces provide valuable evidence about students' writing processes, but their usefulness for learning analytics depends on how individual revisions are represented. Automated draft-comparison methods often produce granular edit operations that can fragment a single purposeful revision into multiple analytic units. This study evaluates whether LLMs can identify meaningful revision unit boundaries in structured revision operation data and whether they provide value beyond simple non-LLM baselines. Using 113 matched draft--revision pairs from undergraduate writing, expert annotation yielded 4,344 candidate boundaries. We compared zero- and few-shot GPT-5.5 and base Qwen3-32B, parameter-efficient fine-tuning of Qwen3-32B, and majority and proximity-based baselines. Despite receiving revision context and task instructions, no prompted LLM condition outperformed the proximity heuristic (macro-F1 = .825). In contrast, fine-tuned Qwen3-32B using the two context representation achieved

---

### [408] Distance-KV: Exploiting Relative Distance for Efficient Long-Context Inference

**链接**: https://arxiv.org/abs/2609.32663
**作者**: Xianpeng Shang, Canbin Huang, Jiang Li, Tian Lan, Qianyi Cai, Xiaojun Quan 等 (7 人)
**来源**: cs.LG cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The memory usage and decoding latency of LLM inference grow rapidly with context length. To reduce these costs, key-value (KV) cache compression methods selectively retain cached states based on token importance or differences in attention patterns across heads. However, we discover that retrieval capability varies substantially with relative distance, even within the same attention head. To exploit this structure, we introduce Distance-KV, which learns a static KV retention pattern over the joint space of layers, attention heads, and relative distances. The pattern is learned offline with the language model frozen and reused across inputs to prune and compact the KV cache without online importance scoring. Across three backbone models and four long-context benchmarks, Distance-KV consistently achieves the best overall performance among competing KV cache compression methods, exceeding the strongest compression baseline by up to 9.3 points on RULER at 128K. On Llama-3.1-8B-Instruct at 

---

### [409] OneSign: Unifying Sign Language Understanding Tasks with One Model

**链接**: https://arxiv.org/abs/2609.33090
**作者**: Shiwei Gan, Yafeng Yin, Xiao Liu, Desibieer Tuerdaken, Lei Xie, Sanglu Lu
**来源**: cs.CL cs.AI cs.CV
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> SLU encompasses a diverse set of tasks, including ISLR, CSLR, and SLT. Although these tasks share basic semantic and linguistic foundations, they are typically addressed with task-specific architectures and training pipelines, which hinders knowledge sharing and requires costly pretraining and finetuning for each task. In this paper, we focus on two aspects of SLU tasks: (1) training and inference pipelines are highly fragmented: most methods rely on pretraining on large-scale SL datasets followed by task- or dataset-specific finetuning, which leads to multiple specialized models rather than a single checkpoint. (2) current LLM-based methods may overlook the inherent modality discrepancy between sign and text tokens, simply concatenating them and processing both modalities with the same decoder layers. In this paper, we present OneSign, a unified framework that addresses multiple SLU tasks within a single model and a single checkpoint. OneSign reformulates ISLR, CSLR, and SLT under a s

---

### [410] Closing the Cross-Dialect Gap: Query Plans as a Portable Interface in Text-to-SQL

**链接**: https://arxiv.org/abs/2609.33670
**作者**: Corentin Royer (1 and 2), Robin Oester (1), Yotam Perlitz (1), Yannick Metz (2), Andrea Giovannini (1), Mennatallah El-Assady (2) ((1) IBM Research 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Text-to-SQL systems are typically trained and evaluated on a single dialect (SQLite), yet production deployments span PostgreSQL, MySQL, ClickHouse, and beyond. We show that this single-dialect assumption leads to a substantial drop in cross-dialect accuracy for every model we tested. The drop persists across scale, architecture, and even purpose-built text-to-SQL systems. We argue that the fix is to change the generation target: instead of asking an LLM to emit dialect-specific SQL, we have it emit a dialect-agnostic relational algebra query plan, which a deterministic compiler then renders into SQL for any supported backend. Across thirteen models from 3B to frontier scale, this restores cross-dialect portability nearly uniformly, at a small cost in peak accuracy on the model's home dialect for capable prompted models and none once fine-tuned on plans; under matched fine-tuning, plan supervision yields a stronger model than SQL supervision. We also introduce MetricName, a question-aw

---

### [411] P4Q: Co-designing Token Pruning and Quantization for Vision-Language Model Acceleration

**链接**: https://arxiv.org/abs/2609.34867
**作者**: Haizhao Jing, Zhenhao Shang, Haokui Zhang, Rong Xiao, Peng Wang
**来源**: cs.CV
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Vision language models have achieved strong performance across a wide range of multimodal applications, yet their substantial computational and memory costs hinder efficient deployment. Visual token pruning and post-training quantization reduce inference overhead along two complementary dimensions, namely sequence length and numerical precision. Existing workflows typically optimize these techniques independently or apply them sequentially. Their distinct optimization objectives leave critical interactions unaddressed and constrain the achievable compression performance. We revisit these designs and present P4Q, a practical co-design framework that jointly optimizes visual token pruning and low-bit quantization for efficient VLM inference. First, P4Q introduces a quantization-aware visual token selection strategy before the LLM. It applies fake quantization to copies of the features produced by the projector and selects visual tokens using statistics computed from these fake-quantized 

---

### [412] R$^2$ Flow: Recursive Self-Improvement via Recursive Skill Evolution

**链接**: https://arxiv.org/abs/2609.33867
**作者**: Mingda Zhang, Qiang Huang, Yanjin Li, Zijia Wang, Qika Lin, Xiaoying Tang 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based agents can improve themselves across tasks by reusing and revising the skills they orchestrate into executable procedures. Flow-based training fits this loop: it samples procedures in proportion to reward, and the flow through each skill credits it for the next library revision. Three obstacles stand in the way of making this self-improvement reliable: flow training suffers strategy collapse over tree-structured histories; nonnegative flow-based credit rewards frequent use as if it were benefit; and library edits rest on the task reward the policy optimizes. We introduce R$^2$ Flow, a recursive self-improvement framework that alternates policy learning, independent verification, and versioned skill-library updates on a shared-state orchestration graph. The graph merges histories that differ only in the order of independent steps, allowing flow training to pool evidence across equivalent executions. A flow-share readout of the trained flow, invariant to the backward policy, an

---

### [413] Can Open-Weight Large Language Models (LLMs) Simulate Human Survey Populations? A Cross-Instrument Calibration Study

**链接**: https://arxiv.org/abs/2609.32638
**作者**: Grandee Lee and Wang Yue
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly used to generate synthetic survey respondents and digital twins of real people, but whether their output preserves real human statistical structure, rather than surface plausibility, remains unresolved, and most existing evidence comes from proprietary models rather than open-weight ones. We evaluate three open-weight LLM families on a cross-instrument calibration task: conditioning personas on real respondents' verbatim answers to one psychometric instrument and measuring them on a second, construct-distance-controlled instrument, checked against a 2,058-person human panel. Across a 139-pair grid, the simulated cross-instrument correlation tracks the real human correlation at r = 0.70 - 0.73 in every model, driven mainly by correct sign rather than precise magnitude and concentrated in pairs of moderate construct distance. A correlation of this magnitude, obtained from untuned open-weight models conditioned only on individual-level survey 

---

### [414] APOLO: Automatic Prompt Optimization for Ontology Learning

**链接**: https://arxiv.org/abs/2609.34540
**作者**: Huu Tan Mai, Roman Kochnev, Cuong Xuan Chu, Lukas Lange, Heiko Paulheim, Daria Stepanova
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Ontology Learning (OL) from text has advanced with the emergence of Large Language Models (LLMs), but it remains challenging due to the limited availability of annotated training data and the difficulty of adapting LLMs to perform OL effectively. We address this via APOLO - Automatic Prompt Optimization for Ontology Learning, by casting OL as an explicit prompt optimization problem over LLM modules. To obtain training data, we employ a multi-agent system that generates text-ontology pairs from existing expert-curated ontologies. We then propose two ontology learner architectures: a greedy and an autoregressive learner, and optimize both using GEPA, a greedy evolutionary prompt optimizer built on DSPy. Experiments on two ontologies - a biomedical (DOID) and a plant ontology (PO) show consistent improvements after optimization across nearly all model and mode combinations, with autoregressive learners achieving the largest gains. Our results demonstrate that prompt optimization is a viab

---

### [415] What Drives Dialectal Jailbreaks? An Ablation of Surface Form, Cultural Framing, and Strategy Banks

**链接**: https://arxiv.org/abs/2609.31664
**作者**: Qingyang Xu
**来源**: cs.CL cs.AI cs.CR
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent work suggests that obscure language registers can weaken large language model refusal behavior, especially when paired with black-box prompt optimization. It remains unclear whether failures stem from non-standard surface form, culturally grounded framing, or optimization over an expressive prompt-strategy space. We study Chinese registers by extending a classical-Chinese red-teaming framework to Shanghainese and Cantonese and running a 36-cell ablation across surface forms, strategy-bank variants, and two target models. The main finding is corrective: dialectal surface form is neither necessary nor sufficient for high attack success. Non-optimized English, Mandarin, and naive dialect translations remain below 8\% attack success rate, whereas all conditions that retain an optimizer-controlled strategy bank reach 98--100\%. A culture-neutral generic strategy bank reaches the same ceiling at near-single-query cost, further indicating that strategy-bank expressiveness, rather than 

---

### [416] LSTMem: Hierarchical Long Short-Term Online Memory for Large Language Models

**链接**: https://arxiv.org/abs/2609.33268
**作者**: Xianglong Shi, Ruijie Yang, Sirui Zhao, Shukang Yin, Zihao Bian, Tinghao Yi 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models increasingly serve as long-horizon assistants and agents, where they must both accumulate information across interactions and make the relevant parts available when later requests depend on them. Existing compact online memories typically use a single persistent state both to accumulate history and to serve readout, so what the memory stores cannot be controlled separately from what it exposes to the current computation. We propose LSTMem, an LSTM-inspired online memory that instead equips each layer of a frozen LLM with two matrix-valued states: a cell state that accumulates history and a hidden state whose readouts correct the backbone's attention. Input and forget gates control what the cell stores, while an output gate separately controls what the cell exposes through the hidden state. LSTMem further connects memory across depth through forward hidden-state propagation and block-end feedback, and uses higher-layer reconstruction gradients to refine lower-layer

---

### [417] Two Heads Are Better Than One: Aggregating Weaker LLMs for Better Forecasts

**链接**: https://arxiv.org/abs/2609.33257
**作者**: Cheng Peng, Ruixi Luo, Zhi Chen, Wei Tang
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly used to forecast real-world events, but access to the strongest individual forecaster may be costly or otherwise constrained. We study weak-to-strong forecast aggregation: can individually weaker LLM forecasters be aggregated to outperform a stronger forecaster? Using ForecastBench (Karger et al., 2025), we evaluate 70 LLM forecasters across 16 comparison groups, each with more than 1,000 shared subquestions, yielding 1,121 weaker-model pairs. Within each group, we identify the strongest individual by test Brier score and evaluate aggregates composed exclusively of weaker forecasters, with aggregation weights learned on separate training data. We find substantial evidence of weak-to-strong improvement. Learned linear pooling identifies a weaker pair that matches or outperforms the strongest individual in 11 of 16 groups and comes within 5% of its Brier score in all 16 groups. We also find that these improvements do not rely on having a near

---

### [418] KernelZero: Co-Evolving Proposer and Coder for Continuously Improved GPU Kernel Generation

**链接**: https://arxiv.org/abs/2609.33074
**作者**: Changxin Ke, Rui Zhang, Zixiang Fang, Zhenghong Li, Yuanbo Wen, Jiashuo Shen 等 (10 人)
**来源**: cs.LG cs.SE
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> High-performance GPU kernels are essential to modern machine learning systems, yet automatically generating kernels that are both correct and efficient remains challenging. Existing LLM-based approaches face two major limitations: the scarcity of high-quality training data aligned with the model's current capabilities, and the inherent trade-off between kernel correctness and performance. To address these challenges, we propose KernelZero, a co-evolution framework that continuously improves GPU kernel generation through two specialized models: a Proposer that generates Torch modules from API sets and a Coder that translates them into CUDA or Triton kernels. KernelZero uses a frontier-driven module generation mechanism to continuously produce capability-aligned training modules based on the Coder's current weaknesses. It further introduces Correctness-Aware Group Relative Policy Optimization (CA-GRPO), which optimizes performance only after correctness becomes sufficiently reliable. By 

---

### [419] SAIL: Spatial Audio Intelligence with Large Language Models via Disentangled Acoustic-Spatial Encoding and Dual-Stream Q-Former

**链接**: https://arxiv.org/abs/2609.34347
**作者**: Zhengding Luo, Jinyang Wu, Haozhe Ma, Yanghao Zhou, Woon-Seng Gan, Wenwu Wang
**来源**: cs.SD cs.AI eess.AS
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Spatial audio large language models (LLMs) enable embodied agents, wearable assistants, and immersive systems to recognize sound events, localize sources, and reason about their spatial relationships. However, existing spatial audio LLMs often rely on early fusion of acoustic and spatial features and source-agnostic token representations. These designs make it difficult to preserve the correspondence between individual sound events and their spatial attributes, particularly in multi-source scenes. To address this limitation, we propose SAIL, a Spatial Audio Intelligence framework with LLMs that preserves acoustic-spatial structure and source-level correspondence from audio encoding to LLM alignment. SAIL introduces a Disentangled Spatial Audio Transformer that represents Mel-spectrogram and interaural phase difference features as separate acoustic and spatial streams. Source-discriminative task queries further learn event, direction, and distance information for each source. A Dual-Str

---

### [420] AgentWare: Automating the Lifecycle of Agentic Applications across the Edge-to-Cloud Continuum

**链接**: https://arxiv.org/abs/2609.34586
**作者**: Michalis Kasioulis and Moysis Symeonides and George Pallis and Marios D. Dikaiakos
**来源**: cs.DC cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Deploying LLM-enabled agentic applications across the Edge-to-Cloud continuum remains challenging due to hardware heterogeneity, deployment complexity, limited observability, and the lack of systematic evaluation methods. Existing solutions address agent development, observability, or benchmarking separately, offering limited support for the full lifecycle of distributed agentic applications. This paper presents AgentWare, an AgenticOps framework that automates the provisioning, deployment, observability, and evaluation of agentic applications across Edge-to-Cloud infrastructures. AgentWare introduces an end-to-end lifecycle pipeline that automatically prepares heterogeneous execution environments, transforms user-defined agent implementations into distributed applications, deploys agent components across the continuum, and performs unified collection of execution traces, infrastructure telemetry, and evaluation metrics. The framework further supports automated semantic evaluation thro

---

### [421] How Reusable Are Benchmarks with Richer Feedback?

**链接**: https://arxiv.org/abs/2609.32109
**作者**: Youssef Allouah, John Duchi
**来源**: cs.LG stat.ML
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We study whether benchmarks reliably guide model selection as developers adapt to evaluation feedback across multiple criteria. We find that the worst-case test-set size needed to estimate the best score among $k$ adaptively chosen models, under any convex combination of the criteria, grows exponentially with the number of criteria, reaching the $\Theta(\sqrt{k})$ cost of answering $k$ adaptive statistical queries with only $O(\log k)$ criteria, at fixed accuracy and confidence. In attacks on multi-task large language model benchmarks with five to ten criteria, feedback restricted to nondominated task profiles produces large reused-to-held-out score gaps and frequent false winners. These results challenge a prominent explanation for prior observed reliable benchmark reuse---that developers mainly respond to convincing improvements over the current best---in rich-feedback settings, while leaving open how often ordinary model development encounters this vulnerability.

---

### [422] Who Gets a Token, and What Does It Carry? Unequal Name Support and Concept Access in Large Language Models

**链接**: https://arxiv.org/abs/2609.34065
**作者**: Mir Tafseer Nayeem, Davood Rafiei
**来源**: cs.CL cs.AI cs.CY cs.ET cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Names are personal identifiers, but they also carry social meaning and are widely used to evaluate how language models treat different people. Such evaluations typically assume that matched names are comparable model inputs. We show that this assumption often fails at the lexical interface: matched names are not necessarily matched inputs. Some names receive direct single-token access, while others are assembled from multiple subwords, creating unequal name-surface support. Across nearly half a million first names and 12 LLM-associated tokenizers, direct lexical access is highly selective, model dependent, and uneven across race- and gender-associated name metadata. We introduce NameTrace, a model-native, fine-grained, pre-behavioral framework for measuring whether unequal name-surface support remains a vocabulary property or becomes visible in task-relevant internal representations. NameTrace measures concept accessibility from the model's own probabilities over task-specific adjectiv

---

### [423] REFINE: A Resilient Evolution Framework for Intelligent Enterprise Alert Triage in Security Operations Centers

**链接**: https://arxiv.org/abs/2609.32516
**作者**: Huimin Chen, Quan Long, Yanhao Wang
**来源**: cs.CR cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Security Operations Centers (SOCs) process large volumes of alerts daily. Alert triage prioritizes high-risk threats while reducing manual review of benign alerts. LLM agents can reason over logs and threat intelligence, but struggle to keep aligned with organization-specific, rapidly evolving SOC operational standards. We introduce REFINE, an LLM-agent framework for enterprise alert triage. REFINE encodes analyst expertise as structured skills and continuously adapts using analyst disposition feedback. It enforces recall = 1.0 as a hard constraint during evolution to maximize auto-closure of false positives, and identifies judgment blind spots by combining alert distributions with model error boundaries. Evaluated on four real industrial SOC scenarios across four MITRE ATT&CK phases with temporal split: REFINE achieves recall=1.0 on all evolution sets. On future test windows, it retains recall=1.0 in three scenarios; the degraded case reaches 0.807 recall, still outperforming self-evo

---

### [424] LAM: Efficient Lossy Agent Memory Framework With A Retrieval-Score Error Bound

**链接**: https://arxiv.org/abs/2609.32256
**作者**: Baixi Sun, Le Chen, Anjir Ahmed Chowdhury, Xiaolong Ma, Chih-Hsuan Yang, Mingze Xia 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Agent memory grows as agents read inputs, reason, and call tools. Longer histories increase inference cost and eventually exceed the context window. LLM-based summarization reduces this history but adds latency and provides no explicit bound on information loss. We propose LAM, a Lossy Agent Memory system with three components: a deterministic deduplication rule with a substitution bound on retrieval scores - a bound on score perturbation, not a certificate of unchanged ranking; a memory manager that preserves the cached prefix and overlaps compaction with inference; and a performance model that estimates compaction costs before deployment. On 600 agent trajectories, LAM removes 22.47% of observation tokens while retaining 99.984% of the measured gold-patch evidence. At a fixed deletion set, the performance model predicts a 71.4x-91.6x end-to-end speedup from removing records before prefill instead of deleting them from a prefilled context. That benefit comes from the schedule rather t

---

### [425] From Experience to Expertise: Adoption-Aware Memory Learning for Data-Scarce NPU Kernel Synthesis

**链接**: https://arxiv.org/abs/2609.35568
**作者**: Longxiao Fan, Tao Zhang, Han Yan, Jiajun Li, Mingcong Song, Guoping Long 等 (8 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> High-performance kernels underpin efficient accelerator execution but require expert tuning and lengthy manual optimization cycles. LLM coding agents promise automation, yet their CUDA knowledge transfers poorly to data-scarce domain-specific architectures (DSAs) such as NPUs, whose execution models and memory hierarchies differ substantially from those of GPUs. To address this transfer gap, post-training methods adapt LLMs to NPU programming but depend on scarce expert data and substantial training compute. Memory-learning agents instead adapt through external memory, but their uniform credit assignment gives adopted and unused experiences the same reward target, potentially biasing subsequent retrieval rankings. Moreover, when learned values guide only retrieval, high-value experiences that generalize across operators must be retrieved repeatedly rather than retained in context, thereby increasing retrieval overhead and weakening cross-task guidance. We therefore present SAGE, a pers

---

### [426] Towards Reliable AI Data Scientists: Data Agents with Workflow Harnesses

**链接**: https://arxiv.org/abs/2609.35255
**作者**: Huachi Zhou, Yujing Zhang, Jiahe Du, Jiacheng Cai, Zijin Hong, Chuang Zhou 等 (10 人)
**来源**: cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model agents are increasingly deployed for data-intensive work, yet reliable data analysis requires more than general-purpose reasoning and ad hoc tool augmentation. Data Agents, equipped with workflow harnesses, offer a promising paradigm for automating the end-to-end data science lifecycle. This paper examines Data Agents from a harness-centric perspective. First, we introduce a taxonomy of Data Agents and associated data environments, organizing the literature around five functional stages: perception, planning, execution, verification, and repair. Second, we analyze the key technical routes within each stage, identifying 15 distinct approaches ranging from data structure probing to data state reconstruction. Third, we identify four open reliability problems: inactive semantic calibration, missing clarification, missing experience transfer, and the missing verification-repair repository. These problems explain why silent failures can persist even when individual compo

---

### [427] RefCompose: Multi-Reference Image Generation via LoRA-Conditioned Diffusion

**链接**: https://arxiv.org/abs/2609.32389
**作者**: Sai Sri Teja Kuppa, Parth Shinde, Priyadharsan Balaji S, Jinka Harshavardhan, Sriprabha Ramanarayanan
**来源**: cs.CV eess.IV
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Filmmakers and visual artists routinely need to compose multiple references, actors, locations, props, cultural elements, into a single coherent shot, but existing tools either fail to scale past a handful of references or destroy fine grained subject identity in the process, since per reference tokenization scales memory linearly with reference count $N$ and generated content often departs from the given references rather than reproducing them. We propose \textbf{RefCompose}, a pixel space compositional conditioning framework that decouples \emph{where} things go from \emph{what} they look like, via a single fixed resolution reference canvas that keeps conditioning size constant regardless of reference count. Spatial layout is induced at inference time from a frozen diffusion transformer and extracted via Grounding DINO, requiring no LLM or dedicated layout model, while dual stream LoRA adapters inject a layout derived depth map and the encoded canvas through separate low rank streams

---

### [428] BioDyad: Synchronize Biomedical Discovery and Machine Learning Engineering

**链接**: https://arxiv.org/abs/2609.31939
**作者**: Xingbo Du, Fadli Aulawi Al Ghiffari, Leonard Song, Loka Li, Duzhen Zhang, Zixiao Wang 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Agentic biomedical machine learning (ML) draws on complementary advances in biomedical evidence acquisition and executable program search. Existing systems connect aspects of these capabilities, but coordinating them throughout program search remains challenging. New evidence must guide candidate construction, execution outcomes must inform subsequent discovery and reuse, and validation demands must fit the search budget. We introduce BioDyad, which couples biomedical discovery and ML engineering through two hierarchies within Monte Carlo graph search. Its scientific hierarchy combines prior biomedical guidance with iterative discovery, then links biomedical plans to execution outcomes in memory for reuse across candidates. Its engineering hierarchy moves candidate programs from smoke execution, through train/validation evaluation, to full-data retraining. We evaluate BioDyad on the 76-task BioXArena benchmark under a two-hour per-task budget with three matched LLM backends. It achieve

---

### [429] LLMs are General Asynchronous Agents

**链接**: https://arxiv.org/abs/2609.35427
**作者**: George Yakushev, Denis Mazur, Vladimir Bartenev, Vyacheslav Zhdanovskiy, Timofey Byzov, Vladimir Kaurkin 等 (7 人)
**来源**: cs.LG cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Modern LLMs are increasingly capable as autonomous agents, but they follow sequential interaction cycles: read, think, reply or call tools, repeat. Many real-world use cases are not sequential: voice assistants, embodied agents, and monitoring systems receive new inputs while they think or perform another task. Modern LLMs address this with specialized architectures for voice interaction and video streams, VLAs for robot control, asynchronous tool calling for API usage, and others. In this work, we generalize from different asynchronous tasks to general asynchronous agents that can adapt to different types of concurrency. To achieve this, we develop an asynchronous LLM framework that lets users (or the agents themselves) define inference coroutines with overlapping memory states. We showcase that Qwen 3.x models are capable of asynchronous operation for streaming video understanding, videogames, and monitoring, without task-specific training.

---

### [430] CEO Arena: Evaluating Long-Horizon Multi-Agent Decision-Making in Competitive Markets

**链接**: https://arxiv.org/abs/2609.34821
**作者**: An Yan, Yu Huo, Zhiwei Shang, Yiran Peng, Chenglin Wu
**来源**: cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-horizon competition tests agents' ability to coordinate business decisions under uncertainty and adapt to changing rival strategies. We introduce CEO Arena, a benchmark that uses matched replacement evaluation to assess operating returns alongside an agent's effects on rivals and the market. Each CEO agent is compared with a reference policy in the same company under the same economic seed, holding other agents' identities and assignments fixed while all agents adapt. In a shared eight-company market spanning 500 simulated days, CEOs make sequential decisions on pricing, procurement, marketing, research and development, and service using private company information and noisy market signals, under resource constraints and delayed feedback. We evaluate eight LLM-based CEO agents in 27 main runs and 26 robustness runs. In the main evaluation, most agents have negative mean returns, and private gains can accompany market losses. Robustness analyses suggest that aggregate patterns exte

---

### [431] Planarian: Managing Agent State with Statepoints

**链接**: https://arxiv.org/abs/2609.35366
**作者**: Jinnan Guo, Hao Mark Chen, Kapil Vaswani, Andrew Paverd, Peter Pietzuch
**来源**: cs.OS cs.AI cs.CR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents solve complex tasks by iteratively changing files, invoking local tools, and interacting with remote services, which modifies state across their local environment and remote services. Today, agents and users must manage these changes explicitly, whether reverting exploratory actions or recovering from erroneous ones. Doing so safely requires coordinated actions, yet current agent harnesses lack unified abstractions and mechanisms for managing local and remote state consistently and efficiently. We describe Planarian, an agent runtime with state management that enables agents and users to recover from erroneous actions and explore alternative executions over consistent local and remote environment state. Planarian introduces the abstraction of agent statepoints, which are consistent, restorable point-in-time versions of the environment state. Planarian exposes three state-management primitives to agents and users: (i) snapshot creates a new statepoint spanning local and remot

---

### [432] X-Tree: Tokenizing Reusable Experience for Efficient Agent Generalization

**链接**: https://arxiv.org/abs/2609.32993
**作者**: Sitao Cheng, Xunjian Yin, Zhiyuan Sun, Yuxuan Li, Ruiwen Zhou, Xiangru Jian 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-step agents are trained on flat action streams: SFT and RLVR weight every token uniformly and ignore the sub-procedures that recur across tasks, the hierarchy that lets humans plan top-down from reusable routines. This structure sits unused, and flat training uses each scarce trajectory less fully than its content allows. Recent agents do use that structure, but only as LLM-written skills in context, never in the weights, so their gains do not generalize beyond retrieval. We instead recover this hierarchy from the data itself and train on it, with no LLM calls. Following text tokenizers, which build a vocabulary by counting alone, we score action spans by reusability and merge canonicalized actions into a reusable eXperience tree (X-Tree). Each X-Tree node captures how a frequent and success-bearing skill is composed from sub-skills, guiding efficient generalization. We integrate X-Tree into three training settings: offline RL, with each node as a training instance; online RLVR, 

---

### [433] Direct Self-Evolving Optimization: Evolving LLMs without Challenger Training

**链接**: https://arxiv.org/abs/2609.34279
**作者**: Yuyang Deng, Yu Wang, Jiayun Wang
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Self-evolving language models improve by generating tasks and learning from their own feedback, but adapting the task generator often requires a separate challenger-training loop. Can we generate tasks adapted to the current solver without explicitly training a challenger? We introduce \textbf{D}irect Self-\textbf{E}volving \textbf{O}ptimization (DEO), which replaces challenger parameter updates with solver-guided task sampling. The KL-regularized challenger objective defines an exponential tilt of a fixed base task distribution. DEO uses this distribution as a sampling target: a frozen LLM generates and mutates tasks, the solver scores them, and an approximate Metropolis selection rule refines the training pool. Only the solver is trained. Theoretically, for an idealized variant that samples exactly from the tilted distribution, and under regularity, local gradient-dominance, and initialization conditions, we show that DEO learns distributionally robust reasoning ability. In experimen

---

### [434] RepoMAS: Solving Progressively Specified Tasks with Issue-Driven Multi-Agent Systems

**链接**: https://arxiv.org/abs/2609.32490
**作者**: Yuchen Song, Andong Chen, Wenxin Zhu, Muyun Yang, Tiejun Zhao
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based multi-agent systems (MASs) have shown strong potential for solving complex tasks, but most assume that task requirements are sufficiently specified before execution. In practice, user requests are often incomplete, and additional requirements may only become clear during reasoning, tool use, or execution. We refer to such problems as progressively specified tasks. To systematically study this setting, we introduce ProgSpec, a benchmark that evaluates final outputs against requirements explicitly stated in the initial request and additional requirements supported by the available task evidence. We further propose RepoMAS, an issue-driven multi-agent framework inspired by open-source project management. RepoMAS records newly discovered requirements, conflicts, and failures as structured Issues and uses them to revise the task specification and execution structure during problem solving. Across ProgSpec and five existing benchmarks, RepoMAS achieves the best performance. Further

---

### [435] EngramRAG: Dynamic Usage-Weighted Topology and Synaptic Consolidation for Multi-Hop Agentic Memory

**链接**: https://arxiv.org/abs/2609.32049
**作者**: Bhavyateja Potineni, Lohit Giri, Anu Jain, Vadim Kutsyy, Rajasekhar Pentakota
**来源**: cs.AI cs.CL cs.IR cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As autonomous LLM agents are deployed across multi-session environments, conventional memory architectures suffer from Associative Blindness (inability to traverse multi-hop relational dependencies), Scaffolding Amnesia (temporal decay evicting core persona invariants), and Static Topology Stagnation (immutable graphs ignoring usage dynamics). Grounded in Complementary Learning Systems (CLS) principles, we propose EngramRAG, an adaptive memory architecture coupling a low-latency Waking State reflex with an asynchronous background Dreaming State consolidation cycle. EngramRAG introduces: (1) Usage-Modulated Personalized PageRank (U-PPR), where transition probabilities adapt via Hebbian plasticity to promote persistent entities into high-centrality Epistemic Macro-Hubs; (2) Consolidation-Activated Topology Decay (CATD), which scales retention half-life by topological load-bearing weight rather than wall-clock recency, protected by a cold-start grace period (N_grace >= 4); (3) Directed SU

---

### [436] CoSec: Benchmarking Agent Security in Communities

**链接**: https://arxiv.org/abs/2609.34790
**作者**: Hao Chen, Wenhui Dong, Ye Chen, Jiezhi Yao, Chenbo Xia, Yuwen Qu 等 (10 人)
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents operate in persistent collaborative environments involving multiple users, communities, memories, files, and tools. Community boundaries may remain fixed or evolve with changes in membership, roles, composition, and relationships. Agents must complete legitimate tasks and prevent unauthorized disclosure of protected information. Existing evaluations do not fully examine these risks in agent systems. We introduce \textbf{CoSec}, an executable benchmark for evaluating privacy and authorization enforcement in LLM agent systems operating within and across communities. CoSec contains 208 canonical scenarios spanning fixed and evolving boundaries, protected information belonging to the agent owner or other participants, and attacks through dialogue, environmental content, persistent memory, and composed workflows. CoSec executes complete agent systems with persistent sessions, memory, files and tools. It verifies information flows against the active authorization state using execu

---

### [437] Remember Before You're Asked: MemDream for Self-Probing Memory Evolution

**链接**: https://arxiv.org/abs/2609.34545
**作者**: Mingfei Lu, Mengjia Wu, Runsong Jia, Zhe Luo, Yi Zhang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Memory is essential for enabling LLM-based agents to maintain coherent, personalized behavior over long-horizon interactions. However, existing memory systems share a fundamental limitation: they never proactively test their own memory, repairing it only after real queries expose weaknesses. This reactive paradigm means every retrieval failure corresponds to a real interaction in which the cost has already been paid. We propose MemDream, a framework that enables self-probing memory evolution for LLM agents. Our framework periodically enters offline dream cycles where three specialized agents (Dreamer, Analyst, Consolidator) collaboratively probe, diagnose, and repair the memory graph before failures occur. A policy trained via Group Relative Policy Optimization learns which repair operations produce durable retrieval improvements, while a soft decay mechanism provides reversible forgetting driven by the same anticipatory signal. Experiments on LoCoMo and MemoryAgentBench demonstrate th

---

### [438] Large Language Models for Automated Cross-Domain Machine Learning Task Type Identification: A Benchmark Dataset and Evaluation

**链接**: https://arxiv.org/abs/2609.35335
**作者**: Petros Tsialis, Steffen Limmer, Tobias Rodemann, Martin Heckmann
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Machine learning task type identification is essential for constructing valid ML pipelines, yet in practice it is typically specified manually. We investigate whether large language models (LLMs) can infer both the data domain and the downstream prediction task directly from dataset-level information when only the target feature is provided by the user. Together with our LLM-based system we also release an annotated benchmark comprising 625 public tabular and time series datasets. We evaluate the proposed approach in three settings: (i) tabular datasets in comparison with established AutoML heuristics, (ii) cross-domain evaluation across tabular and time series datasets, and (iii) a practical deployment scenario using smaller local models. The results show consistent advantages for LLM-based task type identification, with increasing difficulty in heterogeneous and resource-constrained settings. LLM-based approaches outperform AutoGluon in the tabular setting, reaching 0.98 F1 macro com

---

### [439] RewardExplainer: Learning Reward Model Explanations from Counterfactual Preference Feedback

**链接**: https://arxiv.org/abs/2609.33989
**作者**: Jingyi He, Nier Wu, Shuang Liu, Xin Wang, Mengnan Du, Xia Hu
**来源**: cs.CL cs.LG
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reward models (RMs) are a key component of large language model post-training, providing reward signals for subsequent reinforcement learning. However, conventional discriminative RMs typically output only scalar scores, making it difficult to identify the response behaviors associated with their scoring decisions. Existing interpretation methods often rely on predefined high-level attributes and require repeated counterfactual interventions for each response pair to validate candidate explanations, lacking a closed-loop mechanism that uses RMs' feedback to train a reusable explainer. To address this, we propose RewardExplainer, a framework that obtains feedback from the target reward model through counterfactual rewriting and uses this feedback to further optimize the explainer. RewardExplainer generates open-ended, atomic, and intervenable natural-language scoring mechanisms, making explanations more concrete, readable, and actionable. It further converts counterfactual feedback into

---

### [440] When Keywords Drop but Classifiers Hold: Soft Refusals under KV Cache Compression

**链接**: https://arxiv.org/abs/2609.31678
**作者**: Kang Chen, Xiuze Zhou, Hong Chen and Yuanguo Lin
**来源**: cs.LG cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> KV cache compression is widely used for long context LLM inference under memory constraints, while deployed systems typically score refusals after generation with keyword filters or learned classifiers. Such monitors are intended to indicate whether a model declined a harmful request under the serving regime actually used. However, it remains unclear whether matched compression that preserves task accuracy also preserves agreement between lightweight lexical monitors and stronger refusal classifiers. We study this with a paired protocol on n=200 harmful prompts with a long filler context: each prompt is answered once under full retention and once under matched eviction after a shared prefill, and the same replies are scored by keyword heuristics, the HarmBench Llama-2-13B classifier, an auxiliary LLM judge, and humans on disagreements. On Qwen2.5-3B, keyword refusal falls from 98.0% to 80.5% (McNemar p~1e-8) while classifier refusal stays near ceiling (99.0%-99.5%) and MMLU accuracy is

---

### [441] A bilingual AI audiologist built through rubric-guided playbook induction outperforms human audiologists in a blinded evaluation of simulated cases

**链接**: https://arxiv.org/abs/2609.32220
**作者**: Linkai Li, Changgeng Mo, Hanlin Yu, Congxi Lu, Shangqiguo Wang, Matthew B Fitzgerald 等 (7 人)
**来源**: cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Audiology consultation requires structured history-taking, audiometric interpretation and patient-centred communication, yet real-world case material is scarce. We present a bilingual AI audiologist pairing a general-purpose large language model with rubric-guided playbook induction, multimodal audiogram interpretation and retrieval-augmented grounding, without fine-tuning the language-model backbone. Using a 21-item rubric and an AI patient simulator, we induced a 19-rule consultation policy from 73 training cases (43 English, 30 Chinese) and evaluated the system on 58 independent simulated cases (30 Chinese, 28 English) in a pre-specified, source-blinded comparison with 17 practising audiologists. The AI audiologist outperformed human audiologists on every case (58/58; mean paired $\Delta$ = +1.35 on a 5-point composite, Cohen's d = 1.84, $P = 4.5 \times 10^{-20}$), on 20 of 21 rubric items and in both languages. Component ablation identified the playbook as the largest contributor, 

---

### [442] Does CoT-Pass@k Really Check the CoT? A Multilingual Mathematical Audit

**链接**: https://arxiv.org/abs/2609.32622
**作者**: Tar{\i}k Tuna Ta\c{s}alt{\i}, Burcu H\"udaverdi, David Semedo
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Pass@k measures whether a model reaches a correct answer under repeated sampling, but never how: a lucky guess counts the same as sound reasoning. CoT-Pass@k was proposed to close that gap, adding an LLM-as-judge that must assess a solution's reasoning chain before it counts. Its value rests entirely on one assumption: that the judge catches flawed reasoning. That assumption has never been tested inside the metric that depends on it, and never outside English, though the metric's claims concern models used in many languages. We report the first audit of that verification step, run under the metric's own protocol on a multilingual suite of five mathematical benchmarks in English, Turkish and Portuguese, two of them natively written. We corrupt correct solutions with deterministic edits that damage the chain and the final answer separately. We observe that all three judges accept corrupted chains almost as often as clean ones. V4-Flash and Qwen3.6 reject a solution sharply only when its 

---

### [443] SRHarness: A Harness for Agentic Symbolic Regression

**链接**: https://arxiv.org/abs/2609.35501
**作者**: Zihan Yu, Shixuan Zhou, Hao Huang, Jingtao Ding, Yong Li
**来源**: cs.AI cs.LG cs.SC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent agentic symbolic regression approaches increasingly rely on large language models to analyze data, select scientific operations, and refine hypotheses over long search trajectories. In such systems, performance depends not only on the underlying model and search strategy, but also on the runtime infrastructure that supports scientific search. We introduce SRHarness, a domain-specific harness for agentic symbolic regression built around three mechanisms: composable scientific actions that provide a common interface over raw, transformed, and candidate-derived quantities; persistent scientific state that retains evaluated hypotheses and exposes compact model-facing views; and trajectory lifecycle management that coordinates continuation, branching, restart, and termination. On LLM-SRBench, SRHarness consistently improves both numerical generalization and symbolic recovery under matched LLM backbones. With DeepSeek-v4-flash-0731, it achieves 93.69% symbolic accuracy on LSR-Transfor

---

### [444] Overview of the TREC 2025 Million Large Language Models track

**链接**: https://arxiv.org/abs/2609.31921
**作者**: Evangelos Kanoulas, Panagiotis Eustratiadis, Jamie Callan, Mark Sanderson, Yongkang Li, Jingfen Qiao 等 (8 人)
**来源**: cs.IR cs.AI cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Agentic AI envisions ecosystems of intelligent agents collaboratively solving complex tasks with minimal human intervention. In such ecosystems, each agent possesses specialized expertise, making effective expert selection central to overall system performance. While most current approaches assume a small number of well-documented models, real-world expertise is far more diverse and cannot be adequately captured through static metadata or hand-written descriptions. We anticipate a future with millions of specialized language models (LLMs), each excelling in different domains or problem types. Rather than relying on predefined capability statements, we propose a retrieval-based paradigm in which an assistant agent infers expertise dynamically by examining models' observable behavior. Upon receiving a user query, the assistant ranks candidate LLMs based on demonstrated competence, enabling efficient and adaptive expert selection. The TREC Million LLM Track operationalizes this paradigm b

---

### [445] LLMs as Adaptive Meta-Solvers: Strategy-Diverse RL for Industrial-Scale Optimization

**链接**: https://arxiv.org/abs/2609.34427
**作者**: Shihao Zhang, Weiting Liu, Siyu Shao, Yitian Chen, Jianfeng Feng, Dongdong Ge 等 (7 人)
**来源**: cs.LG cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Scaling LLM-based optimization from textbook-scale instances to real-world, industrial tasks remains a critical open challenge. Existing approaches are predominantly evaluated on small, self-contained textual problems and often commit to a solver-integrated paradigm, limiting their ability to handle the scale and structural diversity of practical optimization workloads. In this work, we propose a practical framework for training open-source LLMs to tackle real-world, industrial-scale optimization. We first show empirically that solver-integrated reasoning, exact combinatorial algorithm, and heuristic search exhibit complementary strengths across different problem structures and scales. Motivated by this, we introduce Strategy-Diverse Reinforcement Learning (SDRL), which trains LLMs as adaptive optimization meta-solvers. SDRL leverages this complementarity through a correctness-gated hierarchical diversity reward that promotes robust exploration across varying strategies and within each

---

### [446] Before Acting, Change the State: Prospective State Intervention for Web Agents under Deceptive Interfaces

**链接**: https://arxiv.org/abs/2609.34974
**作者**: Ruozhao Yang, Mingfei Cheng, Xiaofei Xie
**来源**: cs.AI cs.CR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based Web agents can autonomously complete user tasks, yet deceptive interfaces can steer them toward outcomes that conflict with users' interests. Existing defenses primarily intervene on agent behavior through blocking, guidance, or replanning. We identify a distinct failure mode: a task-valid action can still realize an unauthorized consequence because of the current Web state. This motivates treating task-relevant Web state itself as a runtime control target. We introduce Veer, an agent-side runtime defense that leaves task planning to the base agent and intervenes on Web state when a proposed action would produce an unauthorized consequence. Before modifying the live environment, Veer constructs a prospective intervention trajectory toward a safe task-relevant state and executes it with runtime grounding and verification. Across TrickyArena and WebDecept, Veer achieves the highest safe task completion in all three evaluation settings, exceeding the next-best defense by 15.9 an

---

### [447] Emergent One-Third Scaling Law as Attention Tries to Concentrate

**链接**: https://arxiv.org/abs/2609.32100
**作者**: Yizhou Liu, Sara Kangaslahti, Jeff Gore
**来源**: cs.LG cs.AI stat.ML
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The neural scaling law relating longer training to better performance through a power law is central to today's large language models (LLMs), yet its origin remains debated. One recent proposal is that power laws can emerge from the strong non-linearity of a single softmax head learning peaked distributions. What happens with multiple softmax functions, as in LLMs, is unclear. Here, we show through toy models that any softmax learning peaked distributions, regardless of its position in the model, can develop logit magnitudes that grow in a power law with exponent $1/3$, becoming a training bottleneck whose loss contribution decays as a power law with the same exponent $1/3$. The overall loss therefore obeys $1/3$ scaling whenever at least one softmax learns peaked distributions. We confirm that many softmax functions in LLMs learn peaked distributions and that LLM loss scaling matches this $1/3$ prediction. Moreover, logit growth dynamics reveal that attention heads, rather than the la

---

### [448] Semantic Uncertainty Quantification Needs Factual Equivalence

**链接**: https://arxiv.org/abs/2609.34967
**作者**: Joseph Hoche, Quentin Guimard, Gianni Franchi
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Semantic uncertainty quantification for large language models rests on a common template: sample several answers, measure how much they agree, and treat disagreement as uncertainty. We first formalize this template as two separate roles: an operator that compares two answers, and an aggregator that combines all pairwise comparisons into a scalar. Existing methods differ almost entirely in how they aggregate, while taking the operator off the shelf, typically an NLI model or a generic sentence encoder. We show that this reliance on off-the-shelf operators is the primary bottleneck of semantic UQ: they do not accurately measure factual equivalence of multiple answers to the same question. We resolve this with a deliberately simple recipe: a single encoder trained contrastively to isolate the targeted fact, utilizing synthetic data generated by an LLM and dataset both disjoint from all evaluation settings. Integrating the resulting operator into existing methods improves performance on 12

---

### [449] AgentPerfBench: A Benchmarking and Evaluation Suite for Inference Performance of Agentic LLMs

**链接**: https://arxiv.org/abs/2609.34683
**作者**: Cheuk Hang Lau, Zeyu Cao, Kevin Wong Cheuk Yin, Yao Lai, Haoran Wu, Nicholas D. Lane 等 (9 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The optimization of LLM serving engines, such as vLLM and SGLang, is largely benchmark-driven: optimizations, scheduling policies, hardware and system designs are all selected based on representative workloads. However, a significant mismatch has emerged in the agentic era. Existing benchmarks primarily focus on simple single-turn chatbot workloads. LLM applications are increasingly agentic: coding agents, terminal execution systems, and tool-use agents issue multi-turn requests with growing context lengths. We introduce AgentPerfBench, a benchmark suite for agentic inference. It uses real traces from agentic benchmarks, such as SWE-Bench and TerminalBench, alongside standard chat baselines. This enables benchmarking of models on multi-turn tasks involving tool calling, skill utilization, and increasing context lengths. AgentPerfBench also samples from empirical distributions of input length, output length, and turn count derived from the real traces, generating representative syntheti

---

### [450] KV-streams for Efficient Compaction in Agentic Reinforcement Learning

**链接**: https://arxiv.org/abs/2609.35750
**作者**: Emiliano Penaloza, Dane Malenfant, Dheeraj Vattikonda, Roger Creus Castanyer, Siddarth Venkatraman, Abhay Puri 等 (10 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Scaling the horizon of agentic LLMs is bottlenecked by the need to fit ever longer context traces in GPU memory. Context compaction has been the most popular mechanism to alleviate this issue, keeping GPU memory constant for a given trace. Unfortunately, most compaction strategies rely on prefilling the LLM context many times over, hindering training throughput. To alleviate this bottleneck and enable efficient trainable compaction, we propose KV-streams, a plug-and-play strategy compatible with any compaction strategy that substantially increases throughput while showing no evidence of hindering performance. KV-streams enable scalable compaction by streaming the KV cache forward rather than flushing it after each compaction. We show that KV-streams enable three different compaction strategies, achieving a 2.6 to 5x wall-clock speedup in training. Beyond efficiency, we find that the streamed KV cache can act as a recurrent state, carrying forward information that has long since disappe

---

### [451] SPIDER: Multi-Layer Semantic Token Pruning and Adaptive Sub-Layer Skipping in Multimodal Large Language Models

**链接**: https://arxiv.org/abs/2609.34977
**作者**: Tianxiang Chen, Zhentao Tan, Zi Ye, Yue Wu, Xiaobing Tu, Jinkui Ren 等 (10 人)
**来源**: cs.CV cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal Large Language Models face significant efficiency challenges that stem from two distinct yet coupled sources: data redundancy and computational redundancy. While most methods focus on data redundancy by pruning visual tokens from the output of the visual encoder or computing redundancy in LLM decoders using blockwise importance, the finer-grained inter-layer representation shifts and the distribution differences within the layers themselves have not been fully explored. In this work, we comprehensively investigate this dual-level inefficiency. We posit that intermediate layer tokens from vision encoders should be considered for effective visual token pruning, as semantic focus shifts across layers, with middle-layer tokens capturing more detailed object-centric information that deeper layers may abstract away. Furthermore, we reveal the differential contributions of Attention and FFNs across distinct LLM decoder layers. Building upon these discoveries, we propose \textbf{SPI

---

### [452] Clarify the User or Verify the World? Uncertainty Routing for Proactive Agents

**链接**: https://arxiv.org/abs/2609.32255
**作者**: Zhaofeng Li, Xuan Zhang, Xiaokui Xiao, Yang Deng
**来源**: cs.AI cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tool-using LLM agents must decide not only whether additional information is needed, but also which source can resolve the uncertainty. Existing proactive approaches often specialize in either user clarification or environment verification, without explicitly determining the appropriate information source for each decision. We formulate this problem as uncertainty routing among ACT, CLARIFY, and VERIFY, and propose PROUR, a proactive uncertainty routing framework. PROUR decomposes action uncertainty into disagreement across plausible user-goal interpretations, which signals user-side ambiguity, and the entropy remaining within each interpretation, which signals missing world-side evidence. To acquire information from the routed source, a query generator is trained with a mode-conditioned information-gain reward, targeting user-goal identification under CLARIFY and next-action identification under VERIFY. On $\tau$-bench, PROUR achieves 28.17% average success rate across retail and airl

---

### [453] Beyond Scripted Search: Sample-Efficient Reward Discovery via Agentic Black-box Optimization

**链接**: https://arxiv.org/abs/2609.32394
**作者**: Minghao Li, Rui Tan, Ruihang Wang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Designing dense reward functions for low-level reinforcement learning (RL) control remains difficult. Recent work uses large language models (LLMs) to iteratively generate and refine reward functions using policy-training feedback within scripted search algorithms. However, evaluating each candidate requires a full RL training run, making sample efficiency a central challenge for reward search on complex control tasks. To address this limitation, we propose an Agentic Reward Black-box Optimization (ARBO) framework, in which an LLM agent builds the search strategy at run time from an evaluation history maintained as its persistent workspace. The evaluation history comprises two components: observations maintained by the evaluation oracle, including candidate scores, per-term training curves, and error tracebacks; and an agent-maintained belief that records diagnoses and intended next steps. The agent queries both with tools and generates the next batch of reward candidates, rather than 

---

### [454] HiThink Turn: An Intent-Aware Turn-Taking Control Module for Full-Duplex Dialogue

**链接**: https://arxiv.org/abs/2609.34096
**作者**: Feiyang Chen, Wenhan Yang, Bohan Wang, Xinjian Gao, Rongjunchen Zhang, Jun Wang 等 (7 人)
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Full-duplex dialogue requires timely yet selective interruption handling, which end-of-turn prediction alone cannot achieve: complete utterances may need no response, while unfinished requests may warrant interruption. To address this challenge, we propose HiThink Turn, an intent-aware streaming turn-state predictor that separates response intent from semantic completeness and conditions decisions on system playback state. A key contribution is minimal intent-sufficient prefix supervision, constructed through LLM judgments and speech alignment, while training on audio truncated at chunk boundaries improves robustness to partial speech. These components support streaming inference with 240-ms audio chunks, enabling low-latency, accurate full-duplex turn control. Experiments show that HiThink Turn leads the compared methods in Easy Turn macro accuracy, Full-Duplex-Bench average interaction rate score (0.933), and non-target-speech average playback resume rate (0.735). Additionally, inten

---

### [455] Uncovering shortcut learning in audio classifiers by discovering recurring concepts in temporal explanations

**链接**: https://arxiv.org/abs/2609.34030
**作者**: Cecilia Bola\~nos and Luciana Ferrer and Magdalena Fuentes
**来源**: cs.SD cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Correlations between events in machine learning datasets may result in shortcut learning, where models learn to predict the target event based on the presence of a correlated event. When these correlations are spurious -- arising from data collection artifacts -- models are likely to perform poorly in practice. We propose a pipeline to uncover shortcut learning in audio classifiers by discovering recurring concepts in their temporal explanations. Specifically, we isolate audio segments that explain classifier decisions, caption them with an ensemble of Large Audio-Language Models, and use a Large Language Model to extract recurring concepts. The resulting concepts can be audited by humans to uncover potential shortcut learning. We evaluate our framework using datasets curated from AudioSet Strong, controlling for the presence or absence of spurious correlations. Results show that this approach reliably uncovers learned shortcuts, such as the model relying on the presence of "laughter" 

---

### [456] Augmenting Visual Anomaly Detection with Automated Interpretability

**链接**: https://arxiv.org/abs/2609.33818
**作者**: Antonio De Santis, Arsenio Leo, Marco Brambilla
**来源**: cs.CV cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Visual anomaly detectors identify deviations from known-normal data, but their anomaly signals may mix evidence of actual anomalies with benign visual variation. We investigate whether automated interpretability can augment visual anomaly detectors by identifying and intervening on different components of this signal. We decompose PatchCore nearest-normal residuals into sparse features using Sparse Autoencoders (SAEs), and provide high-activation and contrastive non-active examples to a Multimodal LLM, which describes each feature and labels it as anomaly, distractor, or uncertain. These labels guide interventions in the SAE hidden representation, where distractor features are suppressed and anomaly features amplified. The edited representation is then used to reconstruct patch embeddings, which are rescored with PatchCore. Across 40 categories from four benchmarks, applying both interventions jointly improves macro-average image-level AUROC from 0.8724 to 0.8857 on source data and fro

---

### [457] CacheRepair: Learning to Repair Cross-Chunk Context in RAG for KV Cache Fusion

**链接**: https://arxiv.org/abs/2609.35139
**作者**: Genglin Wang, Wangsong Yin, Yeerzhati Abudunuer, Haoxuan Xu, Guoliang Xing, Zhenyu Yan
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-document retrieval-augmented generation (RAG) requires a language model to process multiple retrieved text chunks before answering a question. Precomputing each chunk's KV cache independently and concatenating the caches when the chunks are retrieved can accelerate this step. However, the assembled cache lacks cross-chunk attention information, reducing answer quality. Selective recomputation methods recover the missing cross-chunk context by rerunning the target LLM on selected tokens, incurring substantial online computation. We introduce CacheRepair, a lightweight network that learns the difference between independently computed KV caches and those produced by processing the chunks together. The network combines compressed KV features with token embeddings and uses attention that is bidirectional within each chunk and flows from earlier to later chunks. Each repair block receives the compressed cache features, and the predicted residual is added to every document token's cache

---

### [458] ABC-Align: Prediction-Powered Alignment with Adaptive Bias Control

**链接**: https://arxiv.org/abs/2609.34374
**作者**: Eric Frankel and Banghua Zhu and Sewoong Oh and Lillian J. Ratliff
**来源**: cs.LG cs.AI stat.ML
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Language model post-training is often bottlenecked by the need for human-collected preference data, which is expensive and difficult to scale. Reinforcement learning from AI feedback (RLAIF) style approaches that leverage pseudo labels offer an abundant alternative but introduce systematic biases that degrade downstream alignment. Recent general-purpose semi-supervised methods correct for teacher bias using a small set of human-labeled examples, but suffer from high variance especially when human annotations are scarce. To this end, we propose ABC-Align, leveraging abundant pseudo label signal to minimize variance and applying a lightweight, adaptive correction grounded in the human-labeled subset. The correction strength is tuned automatically during training using plug-in estimates of the relevant bias--variance quantities. On LLM alignment with RLHF, DPO, and GRPO where human feedback is scarce, we empirically demonstrate that ABC-Align achieves superior performance over prior semi-

---

### [459] Shared Worlds, Private Minds: Structured Memory for Long-Form Writing as World Creation

**链接**: https://arxiv.org/abs/2609.32401
**作者**: Qiuyu Tian, Xiaowen Gu, Hang Su, Jianghan Chao, Haojie Yin, Fan Guo 等 (10 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents that write long-form fiction need an explicit memory of the evolving storyworld to keep new events consistent with established facts. Such memory must keep heterogeneous narrative information distinct, integrate story developments across granularities, and recover dependencies that a writing request leaves implicit. We present NarraWorld, a structured memory system for long-form writing that treats memory construction as world creation. From a shared evidence-grounded graph, NarraWorld derives four connected views: world facts, per-character beliefs, open developments, and hypothetical branches (possible-world continuations). Hierarchical aggregation with atomic closure consolidates events into scenes, plotlines, and plots, keeping each higher-level node traceable to its constituent source spans. For retrieval, planned reconstruction infers a query's dependencies from the current narrative situation and a preview of memory, then assembles the relevant records within a token 

---

### [460] Can Generative AI Automate Data Extraction for Meta-Analysis? A Case Study on Intercropping Research

**链接**: https://arxiv.org/abs/2609.35089
**作者**: Zehao Lu, Xingguo Xiong, Wopke van der Werf, Thijs L. van der Plas, Ioannis N. Athanasiadis
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Meta-analysis is the synthesis of information from multiple sources to arrive at an overarching conclusion. There is a large need for meta-analysis in agricultural research to synthesize what is known and analyze overarching patterns. Extracting data from published literature is, however, labor-intensive, time-consuming, and tedious, and is impeded by a lack of standardization in research design, units of measurement, and terminology. These challenges are particularly evident in the domain of crop species mixtures, also called intercropping. With the growing capabilities of LLMs, many recent attempts have focused on building systems and tools to automate data collection, yet rigorous assessment against human-labeled ground truth is often missing. In this research, we evaluate three LLM-based approaches---direct zero-shot prompting, a staged workflow, and a multi-agent system---with six open-weight models to extract data from the intercropping literature. The results are evaluated again

---

### [461] StateGuard: Analytical-State Management with Validity-Aware Intervention for Long-Horizon Data Agents

**链接**: https://arxiv.org/abs/2609.34134
**作者**: Wenle Liao, Zhao Wang, Jingchao Zhang, Jiajie Jin, Yimeng Xu, Zhicheng Dou
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based agents have shown strong capabilities in automated data analysis and are increasingly moving toward long-horizon, multi-stage analytical workflows. However, as the analytical process evolves, constraints, variables, and conclusions remain implicitly embedded in interaction histories, making it difficult for agents to track which analytical artifacts remain valid over increasingly long horizons and changing dependencies. Consequently, stale artifacts may be silently inherited, propagating errors to downstream stages. To address this challenge, we propose StateGuard, an analytical-state validity management framework for long-horizon data agents. StateGuard externalizes evolving analytical progress into a state graph containing constraints, versioned variables, intermediate conclusions, and cross-state relations, treating each state as an executable, verifiable, and traceable object rather than textual memory alone. StateGuard maintains state validity through evidence-grounded v

---

### [462] Recipe-Matching, Not Equivalence

**链接**: https://arxiv.org/abs/2609.31927
**作者**: Ali Habibullah, Mohammad Alshiekh, Yazan Alshoibi, Salman Khan and Naeemullah Khan
**来源**: cs.IR cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> MathNet-Retrieve asks a retriever to find, for a math problem, a document stating the same problem. An LLM under one fixed prompt writes each gold document and its near-miss distractors; LLM judges filter them. We call this procedure the "recipe", training on pairs built the same way "recipe-matching", and ask how much score it buys beyond the ability the benchmark claims to test. Two models from one base, matched in rows and settings, differ only in the training file: pairs written under the benchmark's published prompt by another vendor's LLM and judge, or computer-algebra-verified pairs with no LLM anywhere. The first leads by 45 R@1 points on the easy tier. By a non-LLM paraphrase control, half to two thirds of that gap comes from the pairs being LLM-written at all: LLM rewrites under two unrelated prompts, with the verified model's negatives, recover 30 and 22 of the 45 points; back-translations with the same negatives recover almost none. The remaining 15 to 25 points appear only

---

### [463] Beyond Accuracy: Counterfactual Fragility and Demographic Bias in Clinical Evaluation of LLMs

**链接**: https://arxiv.org/abs/2609.32807
**作者**: Chaitai Deb Purkayastha, Bharath Kumar Bolla and Vishnu Surya Reddy Nandi
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Clinical LLM evaluation often emphasizes answer accuracy; however, accuracy alone does not test counterfactual consistency or demographic robustness. We evaluated six LLMs on 150 MedQA USMLE questions using two automated perturbation tests to assess their performance. The counterfactual validity (CFV) test asked each model to make a minimal, plausible clinical change that would make a different answer correct. The demographic robustness test added six demographic prefixes to the same vignette and compared the answers and explanations with a no demographic baseline. Of the 900 CFV attempts, 228 (25.3 %) were valid and 672 were invalid. Across 5,400 demographic comparisons, 1,097 answers were changed (20.3%). Automated judging identified 3,128 stereotype evidence flags, including 1,932 in the broad Other category. MedGemma 27B achieved the highest accuracy (87.1%) and CFV (63.3%), lowest answer change rate (16.0%), and low mean Explanation Demographic Dissonance (EDD) score (0.169). Howe

---

### [464] On Evaluating and Improving Conversational Agents in Production

**链接**: https://arxiv.org/abs/2609.32092
**作者**: Kasra Hosseini, Wen-Sen Cheng, Marco-Andrea Buchmann, Emir Mulabegovic, Weiwei Cheng
**来源**: cs.MA cs.AI cs.CL cs.ET cs.IR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We present a framework for evaluating and improving a large-scale, multi-agent shopping assistant in production, and report lessons from its use. Offline evaluation of such a system faces three obstacles. (i) A logged conversation cannot be replayed against a modified system, because a different response changes every turn that follows. (ii) The unchanged system itself varies from run to run. Its LLM components are stochastic, and in product search the available products, their prices, and the customer's personalization signals change. (iii) Aggregate quality scores combine distinct behaviors, so they show that quality has changed but not which behavior caused the change. Our framework addresses each obstacle in turn. For a reported behavior, an Evaluation Harness generates targeted assertions and a fixed cohort of customer scenarios. It then reproduces the behavior in a local instance of the assistant through grounded user simulation. Instead of replaying the log, the simulator writes

---

### [465] Large Language Models Substantially Compress Well-Being Inequality but Largely Preserve Its Socioeconomic Structure

**链接**: https://arxiv.org/abs/2609.33055
**作者**: Nattavudh Powdthavee
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Research using large language models (LLMs) to generate synthetic populations has repeatedly shown that model outputs compress the diversity of human experience. This has raised doubts about whether LLM-generated data can capture meaningful differences within populations. We show that such compression does not necessarily erase the social structure of human heterogeneity. Using 93,901 respondents from 66 countries and territories in Wave 7 of the World Values Survey, we ask six LLMs to predict respondents' life satisfaction from demographic, socioeconomic, and attitudinal profiles. All six models substantially understate the overall dispersion of life satisfaction. Yet after normalizing for these differences in scale, they largely reproduce the human income gradient in well-being inequality: lower-income groups remain relatively more heterogeneous than higher-income groups. The pattern is robust to country fixed effects, equal-country weighting, WVS survey weights, and observed demogra

---

### [466] Empowering Hybrid Attention Models on NPUs

**链接**: https://arxiv.org/abs/2609.32114
**作者**: Yinyuan Zhang, Daliang Xu, Xiaolong Huang, Wangsong Yin, Yun Ma, Mengwei Xu 等 (7 人)
**来源**: cs.DC cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Hybrid attention models have emerged as a crucial architecture for Large Language Models (LLMs) (e.g., the Qwen3.5 and Kimi series). Their memory and computational efficiency make them highly attractive for on-device inference, forming a promising synergy with edge Neural Processing Units (NPUs). However, naive execution of these hybrid models on edge NPUs fails to deliver these benefits, often bottlenecking the prefill stage due to severe memory-system inefficiencies and architectural mismatches within the linear attention (LA) layers. We present HA-NPU, the first system to enable efficient hybrid attention LLM inference on edge NPUs without modifying the underlying algorithms. HA-NPU enhances execution efficiency by reorganizing the dataflow of the LA components across three levels: (1) At the core level, it partitions workloads by the head dimension and fuses dependent operators, eliminating cross-core global memory accesses; (2) At the operator level, it reorders execution to consu

---

### [467] AgentHop: A Diagnostic Benchmark for Agentic Multi-Hop Scientific Question Answering

**链接**: https://arxiv.org/abs/2609.34428
**作者**: Chanhee Park, Jeongho Yoon, Sungbin Han, Hyeonseok Moon, Heuiseok Lim
**来源**: cs.CL cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Agentic tasks require a large language model to interact with the world, navigating information and gathering evidence across multiple steps with restricted resources. Due to this complexity, agentic task failures arise from various sources, and pinpointing these failure causes is essential to diagnose and improve agentic systems. Existing benchmarks, however, tend to focus on a single leaderboard score, leaving the underlying failure modes opaque. To fill this gap, we introduce AgentHop, a diagnostic benchmark of 1,011 multiple-choice questions paired with a controlled seven-tool sandbox under fixed token, turn, and tool-call constraints. AgentHop reveals model vulnerabilities by dissecting a single accuracy score along four axes of agent operation: retrieval, synthesis, tool-call, and resource management. Across 19 models, we find that behavior clusters by model family, with tool-call signatures revealing distinct family fingerprints: GPT models commit early, Anthropic and GLM checkp

---

### [468] Modular Discovery of General Game-Playing Algorithms with Large Language Models

**链接**: https://arxiv.org/abs/2609.33115
**作者**: Zun Li, John Schultz, Marc Lanctot, Daniel Hennes
**来源**: cs.AI cs.GT cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> General Game Playing across arbitrary games from rules alone remains challenging due to differing algorithmic requirements across game classes and strict decision-time constraints. Rather than hand-designing search heuristics for specific domains, can we leverage Large Language Models (LLMs) to discover general game-playing algorithms? Because language models can propose and refactor structured code, they provide an expressive proposal engine for exploring the space of algorithmic designs. We introduce a multi-agent LLM meta-learning system to co-evolve game-agnostic procedural search mechanisms in C++ alongside domain heuristics synthesized directly from game rules. Controlling the compute budget, we benchmark the discovered mechanisms across more than 400 diverse environments, including OpenSpiel training and held-out games, procedural simulation engines, and games with deep neural policy-value representations trained via PPO. Evaluated via AlphaRank stationary distributions and Soft

---

### [469] When Can Old Evaluations Certify a New Model? Label-Efficient Release Decisions under Evaluator Drift

**链接**: https://arxiv.org/abs/2609.32267
**作者**: Joyanta Jyoti Mondal, Mridul Banik, Md. Shifatul Ahsan Apurba, Md Masud Al Mahmud
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Releasing a model update requires certifying that its current-population risk stays below a threshold. Trusted labels are expensive, while a cheap evaluator, such as an LLM judge, scores every example. Reusing evaluator errors from earlier audits is tempting, but when may such evidence replace current labels? It depends on the status of history. If the errors can change invisibly, no label-free test detects the change, and every valid, useful certifier must keep buying labels at a rate we characterize; if a bound on the change is assumed, label-free certification is valid at an explicit error cost. For the middle ground, where history is informative but untrusted, we propose \emph{portfolio vigilance}, a sequential certifier mixing a betting expert guided by history with one that learns only from current labels; history affects only how it bets, so validity holds for any history. The contribution is not prior-informed betting or expert mixtures, but separating history that may enter va

---

### [470] Dense Is Not Enough: Hierarchical Supervision Allocation for Long-Horizon On-Policy Distillation

**链接**: https://arxiv.org/abs/2609.33409
**作者**: Yuhao Sun, Binrui Wu, Zhuoer Xu, Ming Wen, Haoxiang Xu, Bin Chen 等 (8 人)
**来源**: cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> On-policy distillation (OPD) transfers the capabilities of a large language model to a smaller student by providing teacher supervision on the student's own rollouts. In long-horizon agentic tasks, however, uniform token-level matching can allocate supervision poorly: a large local discrepancy need not improve future behavior, while consequential guidance may be beyond the current student's reach or fail to persist without privileged input. We formulate long-horizon OPD as hierarchical supervision allocation and argue that productive guidance lies at the intersection of future utility and current learnability. Crucially, this intersection evolves as the student learns. Based on this principle, we propose LENS-OPD, a coarse-to-fine framework that organizes supervision through Locate, Validate, and Refine. Locate adapts trajectory exposure to the student's evolving competence and proposes a candidate decision for intervention. Validate tests whether teacher guidance at that decision impr

---

### [471] Certified Multi-Source Integrity for Structured Agent Actions

**链接**: https://arxiv.org/abs/2609.34245
**作者**: Anmol Pandey, Aditya Jain, Liang Chen, Carsten Maple, Christo Panchev
**来源**: cs.CR cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents increasingly take privileged, often irreversible structured actions, such as paying an invoice. They assemble each action from action-critical fields in documents and tool outputs that an adversary can corrupt, and indirect prompt injection can drive the model itself to extract attacker-chosen values. Current defenses gate on a source's trust label or certify free-text answer quality. None certifies the integrity of a coupled, policy-bound structured action under a corruption budget that accounts for shared upstream sources. We characterize when such an action is safely certifiable and give the maximally live safe certifier. It admits an action only when each field clears the rule its evidence structure supports: a bounded corruption radius over corruption-distinct evidence classes, counted by a minimum hitting set so that re-publishing or laundered copies cannot manufacture a quorum, deterministic reconciliation for complementary fields, and a trusted anchor where the evide

---

### [472] Don't Repeat Yourself: Self-Supervised Fine-Tuning for Coverage

**链接**: https://arxiv.org/abs/2609.31688
**作者**: Eric Fithian, Kirill Skobelev, X.Y. Han
**来源**: cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In verifiable domains such as math and coding, finding one correct solution among many attempts can matter more than the pass rate of each attempt. Post-training can concentrate large language model outputs around a few modes, while increasing sampling temperature has limited effectiveness. We introduce Don't Repeat Yourself Supervised Fine-Tuning (DRY-SFT), a post-training method that increases output diversity and coverage: the probability of at least one correct solution among many attempts. DRY-SFT has two stages. First, for each problem, sequentially generate K solutions, showing the model all prior attempts and asking for a different solution. Second, fine-tune on each attempt independently, removing prior attempts from the context. The process uses no reward, verifier, or correctness filter. On HumanEval+, MBPP+, and DS-1000, DRY-SFT raises pass@100 by 10.8, 12.5, and 12.4 percentage points, respectively, at a small cost to pass@1. Structural diversity, measured by abstract synt

---

### [473] Plan-to-Synthesis: Cross-City Human Mobility Generation via Semantic Latent Flow Matching

**链接**: https://arxiv.org/abs/2609.32732
**作者**: Zhoufu Wang, Baoshen Guo, Zhiqing Hong, Junyi Li, Kailai Sun, Heye Huang 等 (9 人)
**来源**: cs.SI cs.LG
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Human mobility generation aims to synthesize realistic point-of-interest (POI) visitation trajectories and has become an important tool for travel behavior modeling, transportation management, and urban planning. Existing diffusion-based methods achieve high fidelity but require per-city generation, given the inherent heterogeneity of geospatial locations and POI categories, while large language model-based methods generalize across cities but remain too costly at scale, especially for long-horizon trajectory generation. To address this, we propose SeMoFlow, a Semantic human Mobility generation framework based on latent Flow matching. We first encode heterogeneous POIs from different cities into a shared cross-city representation space via hierarchical Semantic IDs, where shared prefixes capture transferable semantics, and successive codes progressively refine the representation toward individual POIs. Building on the semantic IDs, SeMoFlow follows a plan-to-synthesis hierarchical gene

---

### [474] When Successful Strategies Fail: Adaptation to Environmental Novelty in Terminal Agents

**链接**: https://arxiv.org/abs/2609.33870
**作者**: Janvijay Singh, Vaishnavi Shrivastava, Dilek Hakkani-Tur, Ece Kamar, Asli Celikyilmaz
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents increasingly solve long-horizon tasks by autonomously interacting with their environment. In doing so, their strategies rely on assumptions about that environment: which resources and tools exist, where they are located, and how they behave. When these assumptions no longer hold, reliable agents must detect the change and adapt while pursuing the same goal. We study this adaptation capability through environmental novelty: a change that keeps the task objective fixed while invalidating an assumption underlying an otherwise successful trajectory. We introduce AGNI, an automated pipeline that extracts trajectory-relevant assumptions, injects targeted environmental changes, and validates that the resulting novel tasks remain solvable. Across three terminal benchmarks, AGNI produces diverse novelties spanning resources, interfaces, constraints, and execution semantics. Evaluating multiple LLM agents reveals a substantial adaptation gap between base and novel tasks. Trajectory an

---

### [475] EdgeCraft: Automated Model Crafting for Edge IoT

**链接**: https://arxiv.org/abs/2609.35167
**作者**: Genglin Wang, Kaiwei Liu, Liekang Zeng, Wangsong Yin, Shangcheng Jin, Guoliang Xing 等 (7 人)
**来源**: cs.LG cs.DC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Machine learning (ML) increasingly powers Internet of Things (IoT) applications at the edge. Yet producing a deployable edge ML artifact for a specific scenario requires navigating a huge search space spanning data representation, model design, training on domain-specific data, and runtime customization. This workflow is fragmented and difficult to scale across diverse edge applications. We present EdgeCraft, an LLM-driven system that turns high-level intent into deployable edge ML artifacts. Building such a system raises two challenges: (1) How can an LLM be guided to find high-quality solutions that meet dynamic SLOs for task quality, latency, and energy? (2) How can trustworthy target-device verification be obtained at low cost? EdgeCraft addresses these challenges with two designs. (1) A constraint-aware synthesis tree explores alternative candidates and uses measured SLO gaps to guide each improvement. (2) A multi-fidelity verifier progressively combines low-cost checks with full 

---

### [476] LLM4Trust: Exploring the Capabilities of Large Language Models for Trust Evaluation

**链接**: https://arxiv.org/abs/2609.33521
**作者**: Jie Wang, Yanbo Sun, Zheng Yan, Jiahe Lan, Elisa Bertino
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Trust evaluation plays a critical role in cybersecurity by supporting risk mitigation and decision-making. A variety of trust evaluation methods have been proposed, with learning-based approaches offering high accuracy and automation. However, they often require substantial ground truth, suffer from low training efficiency, lack support for basic trust properties, and provide limited explainability. Large Language Models (LLMs) offer a compelling alternative due to their strong zero-/few-shot reasoning abilities and broad knowledge. To this end, we propose LLM4Trust, the first benchmark framework that systematically explores the capabilities of LLMs for trust evaluation. We first construct diverse trust graphs to model five basic trust properties and design corresponding property understanding tasks. We then assess the ability of eight representative LLMs to understand these properties under nine prompt methods. Based on this exploration, we identify the most effective LLM-prompt combi

---

### [477] Beyond Skill Evolution: Self-Evolving Context Management Policies for Long-Horizon Agent Harnesses

**链接**: https://arxiv.org/abs/2609.34649
**作者**: Weiyuan Li, Jinghan Xu, Aili Chen, Xintao Wang, Shuang Liang, Jiaqing Liang and Deqing Yang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Harness evolution improves LLM agents by learning from execution trajectories, but existing experience- and skill-based methods are less effective on long-horizon tasks. As interactions grow, useful evidence can be buried by redundant or outdated context, making context management itself a key bottleneck. We introduce ContextEvo, a framework that learns a context policy from long-horizon trajectories. ContextEvo reconstructs the model-visible context at key decision points, identifies context-related failures, and applies targeted policy updates. Starting from the open-source Pi-agent harness, ContextEvo improves performance across three long-horizon task benchmarks, achieving results comparable to or better than several prominent agent harnesses, including Codex, OpenCode, and OpenClaw. Additional analyses show that fixed or locally evolved context strategies can fall short under long-horizon information pressure, while our methods adapt to the information demands of each environment.

---

### [478] SkillVine: Agent Skill Evolution via Branching Exploration

**链接**: https://arxiv.org/abs/2609.32731
**作者**: Kaiwei Liu, Jiqian Dong, Liran Dong, Shuai Mao, Mingming Zhao, Bufang Yang 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Agent skills encapsulate reusable procedural knowledge that enables LLM agents to perform tasks, and they can be improved automatically using trajectories from interactions with the environment. This is the classic problem of skill evolution. Existing approaches predominately follow a linear evolution paradigm, in which updates are sequentially applied to the latest skill-library version. As a result, they inevitably fall into local optima, leaving many promising evolution paths unexplored. We propose SkillVine, an automatic skill-evolution framework that formulates skill evolution as a graph search problem and employs a branching exploration strategy. Equipped with a trunk-branch collaborative searching mechanism, an intelligent parent-node selector, and an adaptive-granularity update rule, SkillVine achieves a balance between exploration and exploitation. We evaluate SkillVine on 5 benchmarks with two LLMs. Results show that SkillVine discovers better skill-library versions along bra

---

### [479] Deploying Foundation Models for Embodied Navigation

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2609.25666&hl=zh-CN&sa=X&d=7547336831872707304&ei=SJS7atDeGq7N6rQPkrrVkQ0&scisig=ACTRDVHzND33n5R5dux8ARi-2kRG&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:ACTRDVHBiLID0dsXs0coH3hBX4Zg&html=&pos=5&folt=kw-top
**作者**: VS Dorbala, D Manocha - arXiv preprint arXiv:2609.25666, 2026
**匹配关键词**: Foundation Models, MLLM
**相关性评分**: 5.0
**数据来源**: Google Scholar

**摘要**:

> using expert answers from a high performing, expert MLLM (GPT-4o here). This trained binary classifier then acts as a head on top of the MLLM backbone. In the Online RL case, … Note that MemCtrl is trained as a detachable head that takes the

---

### [480] ChartRevive: Reconstructing Data Visualizations from Chart Images Using MLLM

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2609.27146&hl=zh-CN&sa=X&d=16831997727589093536&ei=SJS7atDeGq7N6rQPkrrVkQ0&scisig=ACTRDVHYT-VQan0TdJHtvJWq_XfU&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:ACTRDVHBiLID0dsXs0coH3hBX4Zg&html=&pos=1&folt=kw-top
**作者**: Y Ueno, A Pandey - arXiv preprint arXiv:2609.27146, 2026
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> , a mixed-initiative system that combines MLLM -based extraction with an interactive … ChartLlama [9] instruction-tunes an MLLM for chart understanding, description, chart-to-code … Building on these findings, we present a mixed-initiative

---

### [481] Synergizing Discriminative Exemplars and Self-Refined Experience for MLLM-based In-Context Learning in Medical Diagnosis

**链接**: https://arxiv.org/abs/2603.27737
**作者**: Wenkai Zhao, Zipei Wang, Mengjie Fang, Di Dong, Jie Tian, Lingwei Zhang
**来源**: cs.CV
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [482] BIRD: Distilling Decision Boundaries into Rationales for MLLM Adaptation

**链接**: https://arxiv.org/abs/2609.33713
**作者**: Anglin Liu, Yanlin Wu, Ruichao Chen, Yuting Zhang, Qingyuan Zeng, Pengxiang Cai 等 (9 人)
**来源**: cs.AI
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Adapting general-purpose multimodal large language models (MLLMs) to specialized domains requires learning domain-specific decision criteria, which often hinge on subtle visual distinctions between otherwise plausible answers. Rationale augmentation aims to expose such evidence through additional observations or inter-sample comparisons, yet a visually valid cue is not necessarily decision-relevant: it may describe how samples differ without changing the model's relative preference between competing answers. We therefore introduce BIRD, a self-improving Boundary-Informed Rationale Distillation framework that uses model-specific confusions to locate unresolved local decision boundaries and distills the evidence that resolves these confusions into rationales. For each sample, BIRD retrieves candidate neighbors from the target MLLM's own representation space and selects the most confusable one according to its answer preferences. It then generates answer-blind candidate evidence from thei

---

### [483] MiCo: Mutual Information Coverage Optimization through Semantic Erasure Modeling for Efficient MLLM Inference

**链接**: https://arxiv.org/abs/2609.34330
**作者**: Tinghao Wang, Yichen Guo, Qizhe Zhang, Yuan Zhang, Weimin Ouyang, Rui Huang 等 (10 人)
**来源**: cs.CV
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal large language models (MLLMs) have demonstrated impressive performance in multimodal understanding, but processing large numbers of visual tokens results in high computational costs. While many methods have been proposed to reduce the number of visual tokens, most of them rely on heuristics and are prone to discarding substantial visual information during pruning, leading to degradation in model performance. In this work, by using a semantic erasure model, we derive a general mutual information coverage objective from task log-loss and propose MiCo, a training-free two-stage pruning method. MiCo first uses visual signals to select a representative candidate pool before visual tokens enter the language model, then performs task-aware subset selection within it. At each stage, suitable observable proxies instantiate the derived objective as a monotone submodular coverage function, which MiCo greedily optimizes under the token budget. MiCo is evaluated on diverse MLLMs ranging 

---

### [484] FOCUS: Benchmarking Retinal Model Generalization from Foundation Vision Encoders to Multimodal LLMs

**链接**: https://arxiv.org/abs/2609.33158
**作者**: David Restrepo, Chenwei Wu, Luis Filipe Nakayama, Miguel L. Martins, Stergios Christodoulidis, Maria Vakalopoulou 等 (7 人)
**来源**: cs.CV cs.AI
**匹配关键词**: Foundation Models, MLLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Progress in AI-based retinal image analysis has advanced with foundation models, yet evaluating their reliability remains challenging. Performance reported on a single dataset does not capture how models behave under dataset shift, across clinical definitions, or for different patient subgroups. This limitation is particularly critical in medical imaging analysis, where robustness, calibration, and fairness are essential for safe deployment. We introduce FOCUS (Foundation Ophthalmic Cross-Dataset Understanding under Shift), a cross-dataset benchmark for evaluating retinal fundus models that considers vision-only encoder models (VM), vision-language dual-encoder models (VLM), and multimodal large language models (MLLM). FOCUS harmonizes binary diabetic retinopathy, referable diabetic retinopathy, and glaucomatous optic neuropathy tasks across ten public datasets spanning diverse geographies, acquisition conditions, and label protocols. The benchmark evaluates models through a unified an

---

### [485] Human-Annotated or MLLM -Assisted? A Comparative Evaluation of Filmic Metaphor Identification Using FILMIP-AI

**链接**: https://scholar.google.com/scholar_url?url=https://www.degruyterbrill.com/document/doi/10.1515/dsll-2026-0033/html&hl=zh-CN&sa=X&d=16540236287349953007&ei=SJS7atDeGq7N6rQPkrrVkQ0&scisig=ACTRDVHznw2wVHW4yXpjjPPtaohc&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:ACTRDVHBiLID0dsXs0coH3hBX4Zg&html=&pos=0&folt=kw-top
**作者**: L Bort-Mir, MS Miri - Digital Studies in Language and Literature, 2026
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> We introduce FILMIP-AI, an operationalization of FILMIP designed for MLLM -assisted annotation through carefully engineered multimodal prompts. Rather than viewing AI as a substitute for human interpretation, this study assesses the effectiveness of

---

### [486] OPERA: A Unified Omnimodal Progressive Spatio-Temporal Reasoning Agent for Referring Video Segmentation

**链接**: https://arxiv.org/abs/2609.33338
**作者**: Jingchen Ni, Yuji Wang, Shannan Yan, Haoru Li, Sitong Chen, Chun Yuan
**来源**: cs.CV
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Referring video segmentation with heterogeneous multimodal queries---spanning text, audio, and reference images---demands both robust cross-modal understanding and precise spatio-temporal reasoning. We propose OPERA (Omnimodal Progressive spatio-tEmporal Reasoning Agent), a unified reasoning agent built on a single MLLM that performs dual-axis progressive reasoning via three specialized stages. Along the temporal axis, a Temporal Reasoning Agent narrows the frame search space through coarse-to-fine filtering to identify the most informative key frame. Along the spatial axis, a Distillation Agent establishes what to locate via cross-modal semantic distillation, and a Grounding Agent enhanced with GRPO determines where the target appears, with dense mask propagation completing the pixel-level output. OPERA sets a new state of the art on OmniAVS and Ref-AVS and transfers zero-shot to standard referring video segmentation benchmarks.

---

### [487] The Alignment Illusion in Multimodal Large Language Models

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2609.30210&hl=zh-CN&sa=X&d=14399039066452802534&ei=SJS7atDeGq7N6rQPkrrVkQ0&scisig=ACTRDVF7MZJaZ0NTmdfbTxjaW9Eg&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:ACTRDVHBiLID0dsXs0coH3hBX4Zg&html=&pos=7&folt=kw-top
**作者**: HH Wang, Y Wang, H Ding - arXiv preprint arXiv:2609.30210, 2026
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> The two interpretations cannot be separated on standard MLLM benchmarks alone, where … score is not, by itself, evidence that an MLLM uses the image to answer the question, and such … The MLLM case, where two modalities share a

---

### [488] The Earth in One Gaze: Training-Free Active Focus for UHR Remote Sensing Understanding

**链接**: https://arxiv.org/abs/2609.31747
**作者**: Yao Zhang, Pengyu Dai, Wei Guo, Jian Liang, Jian Song, Yafei Ou 等 (8 人)
**来源**: cs.CV eess.IV
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal large language models (MLLMs) must balance local detail against scene context when interpreting ultra-high-resolution (UHR) remote sensing (RS) imagery within a limited visual-input budget. Existing selection-based methods either prune tokens and select patches through relevance scoring, or crop actively through repeated inspection. Neither strategy directly redistributes pixels within a continuous full-scene view: the first retains selected tokens or patches, and the second re-encodes a crop detached from its surroundings. Our pilot study finds that a frozen MLLM already produces useful question-guided spatial requests, yet crop-based inspection of the selected regions does not consistently improve its answers. We therefore formulate UHR understanding as a question of where to spend a fixed pixel budget. Based on this, we introduce GazeEarth, a simple-yet-effective training-free framework that couples question-guided region selection with full-scene foveated observation. Th

---

### [489] MaLiang-Harness: A Programmable Path to Image and Video Generation

**链接**: https://arxiv.org/abs/2609.34309
**作者**: Haoyu Zhao, Zihao Zhang, Xudong Wang, Jiaxi Gu, Zuxuan Wu, Yu-Gang Jiang 等 (7 人)
**来源**: cs.CV
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Executable programs offer explicit control over how images and videos are constructed, but generating runnable code is only the beginning of visual creation. A program can execute correctly while violating the requested composition, appearance, or motion. We define this discrepancy as the Program-to-Visual (P2V) gap and introduce MaLiang-Harness, a unified framework for organizing MLLM-driven visual generation into a persistent process of construction, inspection, and revision. Its central design is to make the evolving visual program, its construction history, and its verification share a common revision reference. We define the Persistent Executable Generation (PEG) state as preserving programs and task context. Traceable Generation Process (TGP) connects edits to rendered evidence, and Revision-aware Editing and Verification (REV) supports restoration and checks the current revision before completion. Together, these mechanisms coordinate planning, execution, and visual feedback acr

---

### [490] FlowTool: Controlling Tool Parameter in Image Retouching via Flow Matching

**链接**: https://arxiv.org/abs/2609.35673
**作者**: Thanh-Long V. Le, Steven Walton, Seunghyun Yoon, Branislav Kveton, Trung Bui, Eunho Yang 等 (7 人)
**来源**: cs.CV
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tool-based image editing (image retouching) is commonly formulated with autoregressive multimodal large language models (MLLMs) that sequentially generate reasoning, tool selections, and parameter values. In this work, we present a novel approach to tool-based image editing by framing the task as a flow matching problem. We introduce FlowTool, a framework that directly models the distribution of high-quality tool parameters conditioned on the input image and user instruction using conditional rectified flow. FlowTool combines a vision-language model backbone for multimodal understanding with a Diffusion Transformer parameter generator that transforms Gaussian noise into an editing plan. We train FlowTool with a two-stage supervised flow-matching curriculum, followed by reward-based post-training. Across MMArt-Bench, FlowTool-Eval, ArtEdit-Bench, and MIT-Adobe5K, FlowTool achieves significantly stronger reference-based performance than specialized MLLM editing agents and proprietary MLL

---

### [491] MetaSampling: Making Frame Samplers Efficient for Long-Video Question Answering

**链接**: https://arxiv.org/abs/2609.33998
**作者**: Ashim Dahal and Bikramjit Banerjee
**来源**: cs.CV
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Frame selection is an important component of long-video question answering (VQA) with Multimodal Large Language Models (MLLMs). Existing frame-selection methods improve over simple top-$k$ embedding retrieval and uniform sampling, but are typically applied under a fixed global selection budget. We introduce \textbf{MetaSampling}, a training-free, plug-and-play sampling strategy that can be applied on top of existing frame selectors. MetaSampling improves downstream VQA efficiency by dynamically reducing the number of frames passed to the MLLM while preserving, and in some cases improving, answer accuracy. We evaluate MetaSampling across 36 paired frame-selector--MLLM-backbone--VQA-benchmark configurations. MetaSampling reduces the number of selected frames in all 36 configurations and improves accuracy in 25 of them, yielding an average frame reduction of $8.9\%$ while slightly improving accuracy overall.

---

### [492] Evidence-grounded multimodal mining of fine-grained research problems and methods from computer vision papers

**链接**: https://scholar.google.com/scholar_url?url=https://link.springer.com/article/10.1007/s00530-026-02677-0&hl=zh-CN&sa=X&d=10476008057530055666&ei=SJS7atDeGq7N6rQPkrrVkQ0&scisig=ACTRDVHrnhmsv3TGRtNYCPUxjOse&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:ACTRDVHBiLID0dsXs0coH3hBX4Zg&html=&pos=8&folt=kw-top
**作者**: F Nian, Y Fu - Multimedia Systems, 2026
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> We denote the MLLM as a conditional function 𝑓𝑓𝜃𝜃, where 𝜃𝜃 represents the fixed model … For each multimodal chunk 𝑐𝑐𝑖𝑖, we call the MLLM with the L1 prompt protocol 𝜋𝜋L1: … Since 𝒜𝒜 may still be too large for a single online MLLM

---

### [493] Look Before You Judge: Training-Free Region Mining for Grounded and Explainable Deepfake Detection

**链接**: https://arxiv.org/abs/2609.35536
**作者**: Chia-Ling Chen, Yu-Ting Ta, Jian-Yu Jiang-Lin, Tai-Ming Huang, Ling Lo, Po-Ching Chen 等 (10 人)
**来源**: cs.CV
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal large language models (MLLMs) can explain deepfake verdicts in natural language, but such explanations are not necessarily visually grounded in the visual evidence underlying the prediction. A model may describe plausible artifacts inferred from language priors rather than from image evidence. Existing grounding methods improve visual reliance through decoding or attention interventions, but they generally strengthen grounding over the entire image, making them ill-suited for forensic artifacts that are subtle, spatially localized, and image-dependent. We propose Look Before You Judge, a training-free framework that formulates explainable deepfake detection as a sequential evidence acquisition process. Instead of directly predicting image authenticity from holistic visual reasoning, our framework first identifies image-specific candidate evidence regions by contrasting the MLLM's decoder-to-visual attention between an original image and its Gaussian-blurred counterpart. The 

---

### [494] ForensicZoom: Adaptive Visual Inspection with Multimodal LLMs for Industrial-Grade Face Forgery Detection

**链接**: https://arxiv.org/abs/2609.31661
**作者**: Hang Zhou, Yiming Tang, Kun Yu, Qian Zhu, Minghao Li, Weigao Wen
**来源**: cs.CV
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reliable face forgery detection is critical to the security of online identity verification systems, where missed attacks compromise security and excessive false positives disrupt legitimate users. Specialized forensic detectors achieve strong detection performance but provide limited interpretability, while multimodal large language models (MLLMs) offer strong semantic understanding and interpretable reasoning yet remain substantially weaker for face forgery detection. We argue that a key limitation lies in how visual evidence is acquired: subtle forensic artifacts may be poorly represented at standard resolution, while uniformly processing all cases at higher resolution is computationally inefficient. We therefore introduce ForensicZoom, an industrial-grade MLLM framework for adaptive visual inspection. ForensicZoom first equips a general-purpose MLLM with forensic-aware visual representations and aligns the language model with these features. Its central mechanism, NEED_ZOOM, enable

---

### [495] Fewer Tokens, More Self-Teaching: On-Policy Self-Distillation for Extreme Visual Token Reduction

**链接**: https://arxiv.org/abs/2609.32353
**作者**: Junxian Li, Ruixuan Yang, Tianao Zhang, Tiange Xu, Weisheng Dong, Yulun Zhang
**来源**: cs.CV cs.CL cs.LG
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Visual token reduction is an effective way to accelerate multimodal large language models (MLLMs), but performance deteriorates rapidly under extremely low token budgets. Existing work has explored both visual-token selection and training-based adaptation to reduced visual inputs. We take a step further by asking how a heavily compressed MLLM should learn from the states induced by its own generations. This setting naturally calls for on-policy self-distillation: a heavily compressed model is supervised on the states induced by its own generations, while its full-token counterpart serves as an information-rich teacher. Based on this insight, we propose LT-OPD, a training framework for extreme visual-token reduction. The student rolls out responses with only a small fraction of visual tokens, and a frozen full-token copy of the same MLLM provides distributional supervision along these student-generated trajectories. To stabilize on-policy learning when visual evidence is severely limite

---

### [496] GUIAuditor: Enabling Post-hoc Child Safety Forensics via Action-Guided GUI Provenance on Mobile Devices

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2609.28205&hl=zh-CN&sa=X&d=10778003426532503069&ei=SJS7atDeGq7N6rQPkrrVkQ0&scisig=ACTRDVHU63lqF7HHxy9zwdxQYOcQ&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:ACTRDVHBiLID0dsXs0coH3hBX4Zg&html=&pos=4&folt=kw-top
**作者**: J Liu, Y Cai, S Wang, Z Zhong, S Li, J Liu 等 (9 人)
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> Our system therefore invokes expensive MLLM analysis only on a small set of highly-curated visual evidence captured around these key … employs a Chain of Thought prompting strategy, compelling the MLLM to function as a transparent

---

### [497] EEG-Based Motor Imagery BCI Algorithms and Technologies: A Review

**链接**: https://arxiv.org/abs/2609.32930
**作者**: Mohammad Hossein Koohi Ghamsari, Seyede Fatemeh Ghamkhari, Siavash Bayat, Ahmed Hemani
**来源**: eess.SP cs.LG
**匹配关键词**: EEG, BCI, Motor Imagery
**相关性评分**: 11.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Brain-computer interfaces (BCIs) have emerged as transformative technologies that enable direct communication between the brain and external devices. Among various BCI paradigms, EEG-based motor imagery (MI) has gained prominence due to its simplicity, non-invasiveness, and potential to restore motor function and facilitate rehabilitation for patients with motor impairments. This paper presents a comprehensive review of the most practical processing algorithms developed over the past decade for decoding brain sensorimotor cortex signals. Specifically, this paper discusses the integration of artificial intelligence (AI)-based algorithms, particularly machine learning and deep learning techniques, and their contributions to improving the performance and efficiency of MI-BCI systems in detail. Furthermore, the paper reviews state-of-the-art hardware platforms and emerging converging technologies, including system-on-chip (SoC) architectures, application-specific integrated circuits (ASICs

---

### [498] Subject-and Task-Aware EEG Foundation Model

**链接**: https://scholar.google.com/scholar_url?url=https://link.springer.com/chapter/10.1007/978-3-032-38239-9_56&hl=zh-CN&sa=X&d=3528497033252878084&ei=SJS7at_2EIbWieoP486gkQs&scisig=ACTRDVE-DlQnYO1yDjlfrj23NtSD&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:ACTRDVFFClCT7j3lRrMoc1sxSf8K&html=&pos=0&folt=kw-top
**作者**: S An, S Kim, SH Park - International Conference on Medical Image Computing …, 2026
**匹配关键词**: EEG, Foundation Models, EEG Foundation Model
**相关性评分**: 9.0
**数据来源**: Google Scholar

**摘要**:

> Recent advances in EEG foundation models have predominantly relied on self-supervised … inter-subject variability and task heterogeneity in EEG datasets, often resulting in suboptimal … pre-training is crucial for building robust EEG foundation models. The

---

### [499] What masking geometry works best for EEG foundation models?

**链接**: https://arxiv.org/abs/2609.33487
**作者**: Pierre Guetschel, Bruno Aristimunha, Yassine El Ouahidi, Arnaud Delorme, Thomas Moreau, Michael Tangermann
**来源**: cs.LG
**匹配关键词**: EEG, Foundation Models
**相关性评分**: 7.0
**数据来源**: arXiv CS Mailing

**摘要**:

> EEG foundation models hold promise for scalable brain-signal decoding across clinical and cognitive neuroscience applications, yet their pre-training pipelines remain poorly understood. Among design choices, the masking strategy is particularly critical: it determines what the network must predict and from which context. Yet it has never been ablated in isolation, as each new model bundles a new masking strategy with a new backbone and objective. In this paper, we formalize the design choices for spatio-temporal masking strategies and train various models with a single pipeline under varying masking configurations across two SSL frameworks (MAE and JEPA). We then systematically evaluate the resulting 58 pre-trained models on the 12 datasets of OpenEEGBench under a linear probe. Both frameworks agree on an optimal masking configuration and on shared failure modes. Outside these, performance is robust: 11 MAE and 9 JEPA configurations are statistically indistinguishable from the best. We

---

### [500] When Is an SAE Feature Interpretable? A Validation Ladder for EEG Foundation Models

**链接**: https://arxiv.org/abs/2609.34091
**作者**: Yucong Cao, Chenqi Li, Tingting Zhu
**来源**: cs.LG
**匹配关键词**: EEG, Foundation Models
**相关性评分**: 7.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Sparse autoencoders (SAEs) decompose dense model activations into discrete latents, making individual features easy to interpret--and easy to misinterpret. In EEG foundation models, this creates a tempting inference: if removing alpha-band activity strongly changes a latent's activation, one might conclude that the latent represents alpha activity. Across 27 settings spanning three backbones, three EEG datasets, and three network depths, this interpretation initially appears compelling: alpha removal changes latent firing 7.3 times more than an equal-width sham notch (95% CI [6.2, 8.7], bootstrapped over settings). However, the alpha filter also deletes far more signal than the sham. After normalizing by removed spectral energy, the ratio falls to 0.28 (95% CI [0.22, 0.36]) and exceeds one in none of the 27 settings. Latents selected for their response to alpha removal are, on clean EEG, slightly anti-correlated with relative alpha power (mean r = -0.073), giving no support for a simpl

---

### [501] A cross-regional multi-scale network for motor imagery EEG decoding with discriminative representation learning

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S0950705126018332&hl=zh-CN&sa=X&d=10143102239877652728&ei=SJS7at_2EIbWieoP486gkQs&scisig=ACTRDVHi_vohHOzoo-s-PE5SnoTP&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:ACTRDVFFClCT7j3lRrMoc1sxSf8K&html=&pos=1&folt=kw-top
**作者**: Y Wei, C Lu, B Bao, Y Wu, M Orban, H Yang 等 (8 人)
**匹配关键词**: EEG, Motor Imagery
**相关性评分**: 7.0
**数据来源**: Google Scholar

**摘要**:

> electroencephalography ( EEG ) remains challenging due to its low signal-to-noise ratio, non-stationarity, and inter-subject variability. This work presents CrossDMNet, an end-to-end MI- EEG … consistently superior performance compared with

---

### [502] Separating personal from population gains when calibrating EEG foundation models for new users

**链接**: https://arxiv.org/abs/2609.34801
**作者**: Xilin Tao, Kani Chen
**来源**: cs.LG eess.SP q-bio.NC
**匹配关键词**: EEG, Foundation Models
**相关性评分**: 7.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Foundation models are increasingly adapted to individual users, but an apparent personalization gain can simply reflect a stronger population model. This distinction matters for brain-computer interfaces, where every new user must be calibrated. We evaluated personal adaptation of three frozen EEG foundation models (CBraMod, REVE and LaBraM) in 235 held-out subjects from three motor-imagery datasets, comparing each subject's adapter with the population model and with adapters fitted to other subjects. Using all first-half session labels, personal adapters improved mean balanced accuracy over the population model by 1.5-5.4 percentage points and outperformed exchanged adapters by 2.3-7.3 points in all nine model-dataset combinations. The size of this benefit depended on population training: with four times the original budget, median gains remained positive (1.0-2.0 points) but were smaller for every model, and no population model reached a confirmed plateau. Acquiring the benefit cheap

---

### [503] EEG-Fusion: Failure-Informed Source-Free Expert Routing for Robust Motor Imagery EEG Decoding

**链接**: https://arxiv.org/abs/2609.33962
**作者**: Abdul Basit, Saim Rehman, and Muhammad Shafique
**来源**: cs.HC cs.AI cs.LG eess.SP
**匹配关键词**: EEG, Motor Imagery
**相关性评分**: 7.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Subject-independent motor-imagery (MI) EEG decoding can exhibit subject-level failures even when average performance appears acceptable: under subject shift, a decoder can become an overconfident near-one-class predictor. This is especially problematic in source-free deployment, where target-user labels are unavailable during adaptation and expert selection. We present \textit{EEG-Fusion}, a failure-informed decision-level fusion framework that treats source-free MI decoding as label-free reliability estimation over heterogeneous experts. EEG-Fusion applies subject-wise Euclidean alignment and normalization-only test-time adaptation, then routes each target subject to a neural, covariance-based, or physiological-feature expert using a reliability gate trained on source-held-out folds to predict expert performance and collapse risk from label-free stream diagnostics. The gate uses confidence, entropy, prediction diversity, expert agreement, and predicted class balance; collapse is measu

---

### [504] Benchmarking EEG Foundation Models at Scale: Lessons from 20,000 Evaluations

**链接**: https://arxiv.org/abs/2609.32743
**作者**: Zhige Chen, Shu Peng, Chengxuan Qin, Rui Liu, Rui Yang, Kay Chen Tan 等 (7 人)
**来源**: cs.LG eess.SP
**匹配关键词**: EEG, Foundation Models
**相关性评分**: 7.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Electroencephalography (EEG) foundation models (FMs) promise transferable neural representations, yet their advantages over strong supervised baselines and their prospects for further scaling remain unclear. To address these questions, we introduce EEG-Arena, an open-source benchmark covering 30 EEG FMs and 25 supervised baselines evaluated on 57 downstream tasks from 23 public datasets. Through more than 20,000 evaluations across five experimental protocols, we assess downstream performance, pretraining benefits, model size scaling, pretraining data scaling, and robustness to channel configuration. We find that (1) EEG FMs outperform strong task-specific supervised baselines on most evaluated tasks, particularly under non-bipolar settings; (2) compared with architecture-matched supervised training from scratch, pretraining improves both early optimization and final downstream performance, with larger and more consistent gains as more labeled downstream data become available; (3) exist

---

### [505] EEG-AS: Instance-Level Foundation Model Selection for EEG Foundation Models via Behavior Reconstruction

**链接**: https://arxiv.org/abs/2609.00653
**作者**: Yunzhen Zhang, Ruoxi Piao, Muhammad Ibrahim Ali Shah, Hasan Onur Keles, Mustafa Misir
**来源**: cs.LG cs.AI
**匹配关键词**: EEG, Foundation Models
**相关性评分**: 7.0
**数据来源**: arXiv CS Mailing

---

### [506] LEGEND: A Language-Aligned EEG Foundation Model with Flow Matching Latent Denoising

**链接**: https://scholar.google.com/scholar_url?url=https://link.springer.com/chapter/10.1007/978-3-032-38239-9_32&hl=zh-CN&sa=X&d=7687428224700079794&ei=SJS7at_2EIbWieoP486gkQs&scisig=ACTRDVGi4ZWJSQ_dVOR_7ozTTcfB&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:ACTRDVFFClCT7j3lRrMoc1sxSf8K&html=&pos=5&folt=kw-top
**作者**: Y Gui, M Chen, G Luo - International Conference on Medical Image Computing …, 2026
**匹配关键词**: EEG, EEG Foundation Model
**相关性评分**: 7.0
**数据来源**: Google Scholar

**摘要**:

> To address the overemphasis on local details and neglect of global semantics in EEG representation learning, we propose LEGEND—a language-aligned EEG foundation model with flow matching latent denoising that integrates structural

---

### [507] AutoBCI: Forecast-Guided Agentic Neural Architecture Discovery for EEG-Based Brain--Computer Interfaces

**链接**: https://arxiv.org/abs/2609.35456
**作者**: Muyun Jiang, Yi Ding, Wei Zhang, Jinbo Chen, Chenyu Liu, Zhenjie Yang 等 (10 人)
**来源**: cs.AI
**匹配关键词**: EEG, Motor Imagery
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> EEG-based brain-computer interfaces support a broad range of applications, yet designing decoding architectures that perform well across diverse tasks remains challenging. We introduce AutoBCI, an agentic framework in which a Designer Agent and a Forecaster Agent support the discovery and selection of EEG decoding architectures across tasks. The Designer Agent performs Pool-Guided Architecture Discovery (PGAD), generating and refining architectures through training and validation across multiple EEG tasks, such as emotion recognition, motor imagery, and sleep staging. The Forecaster Agent performs Performance Estimation from Early Knowledge (PEEK), using architecture code, the training protocol, and early learning curves to predict full-budget validation performance and select promising candidates for continued training. Across 14 EEG datasets spanning motor imagery, emotion recognition, and sleep staging, we evaluate AutoBCI with six LLMs, including Opus 5.5 and GPT 5.6 Sol, and compa

---

### [508] PhysioTRACE: Provenance-Aware Stress Tests for Physiological Foundation Models

**链接**: https://arxiv.org/abs/2609.34466
**作者**: Ayana Mussabayeva, Anuar Aimoldin, Olivier Oullier, Xue Liu, Kun Zhang
**来源**: cs.LG
**匹配关键词**: EEG, Foundation Models
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Physiological foundation models encode how a signal was recorded alongside the physiology it reflects. When recording conditions are associated with diagnosis, this acquisition provenance can become a shortcut, yet the usual evidence, shifted transfer and provenance decodability, does not show whether a predictor uses it. We introduce PhysioTRACE, a four-axis behavioral audit for frozen encoders that separates what a probe can decode from what a fixed task head relies on. Recover scores how decodable provenance is; Stress reverses only the provenance-target association on the same held-out records; Intervene removes a train-localized provenance component; and Verify certifies that removal only if it beats matched random projections within a declared utility margin. Each audit thus ends in one of three verdicts: no reliance, or reliance with the remedy certified or refused. Across EEG and ECG, five training objectives, and five frozen foundation models, the relation between Recover's ca

---

### [509] ThinkNet: Compact Architecture Selection and Validation-Gated Ensembles for Subject-Independent MI-EEG Decoding

**链接**: https://arxiv.org/abs/2609.33967
**作者**: Abdul Basit, Saim Rehman, Muhammad Shafique
**来源**: cs.HC cs.AI cs.LG eess.SP
**匹配关键词**: EEG, BCI
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Practical assistive and rehabilitative brain--computer interfaces require subject-independent motor-imagery EEG (MI-EEG) decoders that generalize to new users under limited target-user data and constrained compute. However, held-out-subject performance can be overstated when test-subject information influences preprocessing, model selection, or ensemble selection. We present \textit{ThinkNet}, a validation-controlled framework that combines train-only normalization, validation-guided evolutionary search, and validation-gated inference to identify compact decoders and inference policies for held-out subjects. We evaluate four-class BCI Competition IV-2a (session T) decoding with nine Leave-One-Subject-Out (LOSO) folds, three seeds, seven fixed decoder entries, and a broader search over ten representative decoder families; the held-out subject is never used for normalization, hyperparameter, architecture, or ensemble-policy selection. In the fixed benchmark, the validation-selected compa

---

### [510] Neuron-Level Architecture Growth: A Controlled Evaluation for EEG Time-Series Decoding

**链接**: https://arxiv.org/abs/2609.33880
**作者**: Adam Mounir, Stella Douka, Arnault H. Caillet, Bruno Aristimunha, Sylvain Chevallier
**来源**: eess.SP cs.HC cs.LG cs.NE
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Convolutional EEG decoders are trained at a fixed width, usually set by their authors on other data. Growing methods add neurons during training where the loss could decrease the most, but whether they improve compared to a reference width is untested on EEG. Here, we grow three convolutional backbones on 12 motor-imagery datasets under three protocols and compare each with its reference model per subject. The growing ShallowFBCSPNet scores 2.9 points above its reference model with only half the parameters (0.57x), SCCNet changes by at most 1.2 points. Deep4Net growing models show decreased accuracy, but they require adaptation that prevent to compare faithfully the results. These differences follow the selection step, which keeps a candidate neuron relying on a dynamic threshold from singular values decomposition. Overall, these results suggest that growth helps when its criterion can rank the candidate neurons, and that the rate of skipped neuron addition tells where a decoder can be

---

### [511] SpikeEEGformer: A Spike-Driven Transformer for Generalized EEG Recognition

**链接**: https://scholar.google.com/scholar_url?url=https://link.springer.com/chapter/10.1007/978-3-032-38239-9_54&hl=zh-CN&sa=X&d=15747431695048874017&ei=SJS7at_2EIbWieoP486gkQs&scisig=ACTRDVH6Tj-Q3n-pP7tu873Wbe_a&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:ACTRDVFFClCT7j3lRrMoc1sxSf8K&html=&pos=6&folt=kw-top
**作者**: J Luo, S Sun, Q Tao, W Cui, B Wang - … Conference on Medical Image Computing and …, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> To capture synergistic inter-channel correlations and temporal dependencies in EEG signals, we develop the Spike EEG Self-Attention (SESA) mechanism while strictly adhering to spike-driven properties to eliminate floating-point matrix multiplications.

---

### [512] Measurement-Gated Provenance Attenuation for Frozen EEG Representations

**链接**: https://arxiv.org/abs/2609.32889
**作者**: Anuar Aimoldin, Yankai Chen, Ayana Mussabayeva, Nurdaulet Akhanov, Xue Liu
**来源**: cs.LG
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Frozen EEG representations retain acquisition signatures as well as neural activity. Source predictability alone does not identify what should be removed: it can reflect measurement effects or genuine biological and population differences, which should not be erased. We propose Measurement-Gated Provenance Attenuation (MGPA), built on one principle: measurement evidence determines where correction may act, and preserved information determines what it should aim for. Paired measurement contrasts define a gate outside which nothing changes; inside it, the source score is moved to the value the preserved coordinates already predict: for a fixed affine score, this keeps the same information as any target set by those coordinates and needs the least expected squared movement. Closed-form and critic-guided iterative constructions apply it without source identity or encoder retraining. Three studies test the principle at increasing distance from its assumptions. Under controlled reference cha

---

### [513] Bridging EEG to fMRI: Semi-supervised Functional Connectivity Translation via Latent Alignment

**链接**: https://scholar.google.com/scholar_url?url=https://link.springer.com/chapter/10.1007/978-3-032-38239-9_12&hl=zh-CN&sa=X&d=11438314215157921829&ei=SJS7at_2EIbWieoP486gkQs&scisig=ACTRDVEvyhGmDLTlBwqxq8Qbdz1d&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:ACTRDVFFClCT7j3lRrMoc1sxSf8K&html=&pos=7&folt=kw-top
**作者**: X Li, W Li, J Mi, S Huang, Y He, X Lin 等 (9 人)
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> To address scarce simultaneous EEG -fMRI pairs, we develop a two-stage semi-supervised framework: Stage I leverages abundant unpaired EEG and fMRI data to learn modality-specific latent manifolds through self-reconstruction, and Stage II uses

---

### [514] Channel-Preserving Representation Alignment for EEG-to-Music Reconstruction

**链接**: https://arxiv.org/abs/2606.04040
**作者**: Jiaxin Qing, Junwei Lu, Lexin Li
**来源**: cs.SD cs.AI eess.AS
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [515] Resource-efficient AI-driven adaptive feature fusion and channel selection for EEG -based neuropsychological disease detection

**链接**: https://scholar.google.com/scholar_url?url=https://link.springer.com/article/10.1007/s44443-026-01133-3&hl=zh-CN&sa=X&d=15765102719996958456&ei=SJS7at_2EIbWieoP486gkQs&scisig=ACTRDVGPkHi35-pMmr8VUaoVW7Ou&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:ACTRDVFFClCT7j3lRrMoc1sxSf8K&html=&pos=3&folt=kw-top
**作者**: J Li, C Ling, X Chen, L Almuqren, Z Yang, Y Nam 等 (8 人)
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> The escalating global burden of neuropsychological disorders demands objective and automated assessment tools, as traditional diagnostic methods often rely on subjective expert interpretation. Electroencephalography ( EEG ) offers a promising

---

### [516] EMG– EEG -based muscle mechanism analysis in injured athletes using hybrid deep learning

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S0263224126030022&hl=zh-CN&sa=X&d=3094980237040265245&ei=SJS7at_2EIbWieoP486gkQs&scisig=ACTRDVFFNle6TxVZcCKYxjjL5-K8&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:ACTRDVFFClCT7j3lRrMoc1sxSf8K&html=&pos=8&folt=kw-top
**作者**: A Amutha, S Gowdhamkumar, V Radhika, J Chitra - Measurement, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> coordination and impair motor control, necessitating precise electroencephalogram ( EEG )-electromyography (EMG) signal analysis for … (Self-KMO-GAN) for EMG- EEG -based muscle mechanism analysis in injured athletes. EEG -EMG

---

### [517] Context-aware tokenization for Cross-subject Emotion Decoding from EEG

**链接**: https://arxiv.org/abs/2606.00884
**作者**: Jiaxin Qing, Lexin Li
**来源**: cs.LG cs.AI
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [518] What your brain activity says about you: A review of neuropsychiatric disorders identified in resting-state and sleep EEG data

**链接**: https://arxiv.org/abs/2510.04984
**作者**: J.E.M. Scanlon, A. Pelzer, M. Gharleghi, K.C. Fuhrmeister, T. K\"ollmer, P. Aichroth 等 (9 人)
**来源**: cs.NE cs.CR cs.CY q-bio.NC
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [519] Separating Diagnosis from Disease Representation: Dual-View EEG Learning with Neural-Dynamics-Guided Deformation

**链接**: https://arxiv.org/abs/2609.32483
**作者**: Jiaying Wang, Shouqian Shi, Yutong Chen, Xu Yang, Jie Chen, Xingyu Pan 等 (8 人)
**来源**: cs.AI
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Electroencephalography (EEG)-based closed-loop neuromodulation calls for a subject-specific structured state, as opposed to a single disease probability, specifying which brain regions are deviant, at which frequencies, and at which lags. Sensor-space models keep the strongest diagnostic evidence without anatomy, source-space models give anatomy at a loss of predictive signal, and post-hoc attributions stay outside the prediction. We separate the two instead of forcing them into one representation, and propose DMD-EEG (Dual-view Multiscale Deformation for EEG), which keeps a fixed scalp spectral expert for diagnosis and models the source-space disease-related representation as a low-rank, sparse, iterative deformation of a healthy neural-dynamics prior in a $46$-region-of-interest (ROI) $\times$ $5$-frequency $\times$ $4$-lag (autocorrelation-timescale) space. The two experts meet only at a fixed decision level, so the source state is architecturally separate from the scalp expert. Acr

---

### [520] RPA: Residual Patch-Token Adapter for Image Retrieval from EEG and MEG

**链接**: https://arxiv.org/abs/2609.31698
**作者**: Yuhui Jin, and Yonghao Song, and Bingchuan Liu
**来源**: cs.CV
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Most existing MEG and EEG (M/EEG) visual decoding methods align brain signals with a single global embedding extracted from a pretrained visual encoder, leaving open whether intermediate patch representations, which preserve richer and more granular rich visual information, can improve representation learning. To address this question, we introduce the Residual Patch Adapter (RPA), a lightweight, modular adapter that leverages all patch tokens from an intermediate layer of a ViT visual encoder for alignment. Through extensive ablation analyses, we first show that pooling or masking patch tokens degrades the learned representation, demonstrating that retaining the full set of patch tokens is important for EEG alignment, while the CLS token provides little unique information. We then use a series of six quantitative feature analyses to show that both higher-level semantics and lower-level visual features, including color and texture, are essential for this EEG-to-image alignment. Under c

---

### [521] Enabling Unsupervised Training of Deep EEG Denoisers With Intelligent Partitioning

**链接**: https://arxiv.org/abs/2605.06724
**作者**: Qiyu Rao, Haozhe Tian, Homayoun Hamedmoghadam, Danilo Mandic
**来源**: cs.LG cs.AI eess.SP
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [522] Learning Domain- and Class-Disentangled Prototypes for Domain-Generalized EEG Emotion Recognition

**链接**: https://arxiv.org/abs/2509.01135
**作者**: Guangli Li, Canbiao Wu, Zhehao Zhou, Na Tian, Li Zhang, Zhen Liang
**来源**: cs.LG cs.AI
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [523] T-SNN: Temporal Simplicial Neural Network for EEG Decoding

**链接**: https://arxiv.org/abs/2609.34002
**作者**: Nikita Malik, Shubhajit Roy, Mohit Kataria, Isuru Herath, Suraj Yadav, In\'es Garc\'ia-Redondo 等 (7 人)
**来源**: cs.LG q-bio.NC
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Decoding brain states requires models that capture both the evolution of neural activity and interactions among groups of brain regions. Existing EEG methods often treat recordings as multivariate time series or represent functional connectivity with pairwise graphs, leaving dynamic higher-order interactions largely unmodeled. We introduce the Temporal Simplicial Neural Network (T-SNN), which represents EEG recordings as sequences of evolving simplicial complexes. By combining simplicial convolutions with recurrent updates, T-SNN jointly learns higher-order interactions and their temporal evolution. On the seven-class SEED-VII emotion recognition task, T-SNN outperforms convolutional, recurrent, graph-based, and Transformer methods in both trial-wise and cross-subject evaluations. Incorporating eye-movement features further improves performance, demonstrating the framework's potential for multimodal brain-state decoding.

---

### [524] Riemannian Batch Normalization on Correlation Manifolds for EEG Decoding

**链接**: https://scholar.google.com/scholar_url?url=https://link.springer.com/chapter/10.1007/978-3-032-38239-9_47&hl=zh-CN&sa=X&d=16841445572664025859&ei=SJS7at_2EIbWieoP486gkQs&scisig=ACTRDVGw5ftrMDb7zQ--yLJoxPhg&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:ACTRDVFFClCT7j3lRrMoc1sxSf8K&html=&pos=4&folt=kw-top
**作者**: J Yang, C Hu, T Xu, C Hu, T Zhou, XJ Wu 等 (8 人)
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Covariance descriptors are widely used in EEG decoding for their noise robustness and … tailored to full-rank correlation matrices in EEG decoding. CorBN leverages the Lie group structure of … on three EEG decoding tasks, and further

---

### [525] Persistent odors induce hedonic valence-independent alpha and beta wave EEG desynchronization

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S0208521626000707&hl=zh-CN&sa=X&d=8381548471075509712&ei=SJS7at_2EIbWieoP486gkQs&scisig=ACTRDVHoR0Tcmqqgjzdc129AIFJe&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:ACTRDVFFClCT7j3lRrMoc1sxSf8K&html=&pos=2&folt=kw-top
**作者**: P Liuzzi, AM Monciatti, R Burali, G Frediani, A Mannini… - … and Biomedical Engineering, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> While electrophysiological responses to olfactory stimulations are widely investigated using electroencephalography ( EEG ), studies on odor perception often yield inconsistent results. In this work, both early and late olfactory event-related

---

### [526] Structural-Semantic Aware Information Reduction for Asymmetric EEG -Visual Alignment

**链接**: https://scholar.google.com/scholar_url?url=https://link.springer.com/chapter/10.1007/978-3-032-38239-9_55&hl=zh-CN&sa=X&d=5351932021028063914&ei=SJS7at_2EIbWieoP486gkQs&scisig=ACTRDVFfmJQRsDq1vdadOwOmktnY&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:ACTRDVFFClCT7j3lRrMoc1sxSf8K&html=&pos=9&folt=kw-top
**作者**: H Chen, Y Kong, C Shan, Y Fang - … Conference on Medical Image Computing and …, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> , electroencephalography ( EEG ) is particularly attractive due to its non-invasive nature, high temporal resolution, and ease of deployment. Despite its advantages, effective EEG -… Motivated by the misalignment between the uncontrollable latent

---

### [527] Deep Learning Methods in Neuroscience: From Modeling Molecular Mechanisms to Classifying States of Consciousness

**链接**: https://arxiv.org/abs/2609.35372
**作者**: Elena Benderskaya, Anastasiia Alifanova, Svetlana Batalova, Vasilisa Zhuk and Anna Kovalenko
**来源**: cs.CL cs.NE
**匹配关键词**: EEG
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A critical analysis of contemporary approaches to the study of conscious states. The review focuses on methods of classification, clustering, modeling of brain states under anesthesia and identification of measurable neurobiological characteristics of brain function. A comparative analysis was conducted in the following three major areas: automatic detection of states of consciousness using neural networks based on EEG and fMRI data; modeling of the structural-functional dynamics of the brain under the effects of anesthetics; and detection of neurophysiological indicators which correlate with the level of consciousness. The obtained conclusions demonstrate the growing effectiveness of deep neural models in the classification and prediction of brain states and the analysis of dynamic structural-functional connectivity. Nonetheless, significant limitations were also identified, including the limited interpretability of the models, the lack of standardized metrics, and the problem of the 

---

### [528] MAESTRO: a Multimodal Auditory-attention Egocentric Speech-TRacking Open corpus

**链接**: https://arxiv.org/abs/2609.31898
**作者**: K M Naimul Hassan, Ali Alavi, Donald S. Williamson
**来源**: eess.AS cs.HC cs.LG cs.SD q-bio.NC
**匹配关键词**: EEG
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Humans rely on gaze, head movements, and visual cues to attend to speakers in noisy environments, yet auditory attention decoding (AAD) has been studied primarily using electroencephalography (EEG). We introduce the Multimodal Auditory-attention Egocentric Speech-TRacking Open (MAESTRO) corpus, the first AAD dataset to simultaneously record EEG, eye gaze, pupillometry, egocentric video, and head inertial measurement unit (IMU) data. MAESTRO includes four competing speakers and background noise across multiple signal-to-noise ratio (SNR) conditions, enabling attention decoding under realistic listening scenarios. Through a four-speaker attention decoding benchmark, we show that combining behavioral and physiological signals improves decoding performance over EEG-only approaches, enabling future advances in multimodal auditory attention decoding. These findings open the door to new applications, analyses, and methodological advances in multimodal AAD. The complete dataset is publicly ava

---

### [529] Identifying Neural Source Dynamics from Unknown Local Interventions

**链接**: https://arxiv.org/abs/2609.35379
**作者**: Ayana Mussabayeva, Jiaqi Sun, Anuar Aimoldin, Olivier Oullier, Kun Zhang
**来源**: cs.LG
**匹配关键词**: EEG
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Electroencephalography (EEG) records mixtures of brain-source activity. Even with a known anatomical forward model, experiments that excite only part of the source-state space leave the dynamics unidentified, and repetition cannot resolve the ambiguity. We show that unknown local mechanism changes can supply the missing information. We consider linear dynamics among fixed anatomical sources with known source-state initialization patterns. Changing one source's update rule for one transition leaves a rank-one, source-specific signature in subsequent EEG: subtracting matched baseline responses isolates it, and the forward model identifies the source and calibrates its response history. Combining these histories with initialization responses recovers source interactions without baseline reachability and without first identifying the intervention coefficients. We establish sufficient recovery conditions, a direct estimator, and a noise-sensitivity bound conditional on correct source labels

---

### [530] Bayesian Complete-Pooling in Cross-Subject Classification for Motor Imagery Electroencephalogram

**链接**: https://arxiv.org/abs/2607.22980
**作者**: Ethan Davis
**来源**: cs.LG
**匹配关键词**: Motor Imagery
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [531] Dynamical Parameters: An Interpretability Framework for Time-Series Foundation Models

**链接**: https://arxiv.org/abs/2609.34316
**作者**: Kang Yang, Gaofeng Dong, Liying Han, Mani Srivastava
**来源**: cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> This work studies a central gap in interpreting time-series foundation models (TSFMs): a dynamical property may be accessible in a hidden state even when the forecast fails to respond correctly as that property changes. We formalize these properties as Dynamical Parameters, including trend slope, oscillation frequency, and autoregressive dependence. We compare their representation accessibility, measured by recovery from hidden states, with their forecast response, measured by agreement with the expected forecast change. Across nine frozen TSFMs and thirteen laws, 42 of 63 model-parameter cells achieve accessibility above 0.95, whereas their median reference-aligned response relative to the conditional reference is only 0.46. To explain this gap, causal geometry compares the hidden-state change required to produce the reference response with the change induced by the parameter intervention. Directly modifying the hidden state recovers the reference response, but the parameter intervent

---

### [532] Time Series Foundation Models for Process Model Forecasting

**链接**: https://arxiv.org/abs/2512.07624
**作者**: Yongbo Yu, Jari Peeperkorn, Johannes De Smedt, Jochen De Weerdt
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [533] Mantis: Mamba-native Tuning is Efficient for 3D Point Cloud Foundation Models

**链接**: https://arxiv.org/abs/2605.03438
**作者**: Zihao Guo, Yiding Sun, Jihua Zhu, Jian Liu, Ajmal Saeed Mian
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [534] Conformal Prediction and Conditional Coverage for Tabular Foundation Models

**链接**: https://arxiv.org/abs/2609.34887
**作者**: Sungwoo Park, Sunghee Park, Won Chang
**来源**: stat.ML cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tabular foundation models (TFMs) provide predictive distributions for regression, but their prediction regions can exhibit undercoverage or overcoverage even when point predictions are accurate. We introduce C-USIM (Conditionally-Uniformized Score Integration Method), a lightweight application of highest predictive density split conformal prediction that accommodates multimodal predictions. Given calibration and test outputs, it requires no additional training or model inference. It provides finite-sample marginal validity under our assumptions. We bound conditional-marginal coverage gaps using distribution-estimation error and score discreteness, and examine coverage heterogeneity through percentile rank-score plots. Experiments with TabPFN and TabICL show improved marginal coverage accuracy and lower average conditional and group coverage errors. Under a fixed data budget, allocating more observations to calibration can reduce marginal coverage error despite less accurate point predi

---

### [535] Behavioral Foundation Models for Quality Diversity

**链接**: https://arxiv.org/abs/2609.35615
**作者**: Nazim Bendib, Nicolas Perrin-Gilbert, Olivier Sigaud
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Behavioral Foundation Models (BFMs) are an emerging paradigm in reinforcement learning, playing a role analogous to large language models in natural language processing: they have shown remarkable versatility, enabling zero-shot performance, fast imitation, and online adaptation, all by exploiting the structure of a latent space. In this work, we investigate whether the latent behavioral space induced by BFMs can serve as an effective search space to discover large repertoires of behaviorally diverse and high-performing policies through Quality-Diversity (QD) methods. While QD methods generally search directly in high-dimensional policy parameter space, in this paper, we present BFM-QD, a framework that performs QD search in the compact latent space of a BFM. We further show that the BFM-QD framework provides a closed-form, gradient-free policy improvement operator that approximates a policy gradient update, but requires no critic training and no backpropagation. Across continuous-cont

---

### [536] Reuse or Relearn? A Spectral View of Earth Observation Foundation Models

**链接**: https://arxiv.org/abs/2609.32756
**作者**: Mehmet Ozgur Turkoglu, Valerio Marsocci, Dominik J. M\"uhlematter, Dominik Senti, Konrad Schindler, Helge Aasen
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Foundation models are rarely used as generic, frozen feature extractors; instead, they are fine-tuned for the target downstream application. This practice is particularly prevalent in Earth observation (EO), and it raises a question that downstream accuracy alone cannot answer: does fine-tuning reuse the pretrained representation, or does it relearn a new one? We study this with spectral diagnostics that compare a model before and after adaptation, quantifying how well its dominant singular subspaces are preserved, how broadly the weight update is distributed, and how large it is. Using natural image models such as CLIP and DINO as a reference, we find that, under the evaluated fine-tuning settings, EO models undergo far larger, higher-rank updates and retain much less of their pretrained structure, so their downstream performance is often obtained with substantial changes to the pretrained weight structure. The diagnostics further provide insight into how cheaply a model can be adapte

---

### [537] Kairos: Toward Adaptive and Parameter-Efficient Time Series Foundation Models

**链接**: https://arxiv.org/abs/2509.25826
**作者**: Kun Feng, Shaocheng Lan, Yuchen Fang, Wenchao He, Sihan Lu, Shuqi Gu 等 (9 人)
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [538] The Platonic Universe: Do Foundation Models See the Same Sky?

**链接**: https://arxiv.org/abs/2509.19453
**作者**: UniverseTBD: Trinidad Borrell, Steven Dillmann, Kshitij Duraphe, Furkan Eris, Kartheik Iyer, Ashod Khederlarian 等 (10 人)
**来源**: astro-ph.IM cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [539] Instance-Adaptive Prompts as Context for Time-Series Foundation Models

**链接**: https://arxiv.org/abs/2609.34786
**作者**: Zehao Xiao, Shifeng Xie, Lei Zan, Jianfeng Zhang, Lujia Pan, Ievgen Redko 等 (8 人)
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Longer histories can improve time-series foundation models (TSFMs), but require substantially higher inference cost. We therefore ask whether contextual information can be provided more efficiently through a compact set of learned token embeddings. We introduce PaCTS, which generates a small set of instance-adaptive latent prompts in the form of continuous embedding tokens conditioned on the visible context. These prompts serve as compact context surrogates for frozen TSFMs. PaCTS constructs them from instance-specific global statistics and further refines them with segment-level temporal information, capturing both global characteristics and local temporal variations. The prompt module is jointly trained and deployed across heterogeneous time series with the frozen backbone. Extensive experiments demonstrate the effectiveness of prompts as context, consistently improving forecasting across context lengths and model architectures. With a shorter input context, PaCTS can outperform the 

---

### [540] Lightweight Wrappers for Adapting Time Series Foundation Models to Regional Drought Forecasting

**链接**: https://arxiv.org/abs/2607.17511
**作者**: Wentao Gao, Jiuyong Li, Lin Liu, Thuc Duy Le, Jixue Liu, Yanchang Zhao 等 (7 人)
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [541] SIFT: Enhancing Time Series Foundation Models via Semantic Invariance and Structural Fidelity Fine-Tuning

**链接**: https://arxiv.org/abs/2609.32676
**作者**: Yi Tang, Tengxue Zhang, Yang Shu, Chenjuan Guo, Chenchen Sun, Yisheng An
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Time Series Foundation Models (TSFMs) have achieved remarkable zero-shot performance through extensive pre-training on massive time series datasets. Nevertheless, due to the low-dimensional properties and diverse structural patterns of time series data, performing naive fine-tuning on TSFMs often leads to overfitting and falling into the mean-prediction trap. To address these challenges, we propose SIFT, a robust adaptation method that enhances time series foundation models by preserving Semantic Invariance and structural Fidelity throughout the fine-Tuning process. We employ semantic-invariant adversarial augmentation, which utilizes semantic spectrum decomposition to partition the semantic space and then generates perturbations within the non-core semantic subspace to bolster the model's robustness against these perturbations, mitigating overfitting. We implement a component-based structural fidelity enhancement, which facilitates component-wise mixup and imposes a reconstruction obj

---

### [542] Can Tabular Foundation Models Amortize Statistical Inference?

**链接**: https://arxiv.org/abs/2609.33114
**作者**: Kai Ye, Shijin Gong, Hongyi Zhou, Valentina Zangirolami, Chengchun Shi
**来源**: stat.ML cs.LG stat.ME
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> For decades, statistical inference has largely been developed one problem at a time. Given a scientific target, such as a treatment effect or a regression function, statisticians design a problem-specific estimator together with a procedure for quantifying its uncertainty. This paper proposes a different paradigm. We focus on a classical problem in statistical inference, confidence interval construction, and develop TabCon, an amortized inference system built on a tabular foundation model that produces confidence intervals for new datasets through a simple forward pass. The key methodological ingredients of TabCon are a sparse mixture-of-experts architecture and reinforcement-learning-based post-training that calibrate the resulting confidence intervals to a desired coverage level. Across a wide range of benchmark datasets, TabCon attains near-nominal coverage while producing short confidence intervals. At inference time, it also offers considerably greater computational efficiency, ru

---

### [543] Can Protein-Derived Knowledge Improve Pathology Foundation Models?

**链接**: https://arxiv.org/abs/2609.33178
**作者**: Di Zhang, Zhangpeng Gong, Jiashuai Liu, Zhi Zeng, Jiusong Ge, Chunze Yang 等 (10 人)
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Molecularly guided pathology foundation models (PFMs) exploit transcriptomic or proteomic information to enrich whole-slide image (WSI) representations, yet effectively leveraging large standalone molecular corpora remains challenging. First, existing molecular foundation models encode protein sequences or single-cell states, not the patient-level bulk expression profiles paired with WSIs. Second, because cross-modal supervision is restricted to paired WSI-omics samples, knowledge from standalone molecular corpora reaches the pathology encoder only indirectly, creating a paired-support bottleneck. To address these challenges, we propose a three-stage framework that decouples proteomic knowledge acquisition from cross-modal transfer, yielding ProSlide, a slide-level hierarchical pathology foundation model. First, to close the modality gap, we pretrain a Proteomic Foundation Encoder (PFE) on 12,695 sample-level bulk protein profiles using virtual profile generation and expression-space m

---

### [544] SARATR-X-v2: Scale-Aware Structural Pre-Training for SAR Foundation Models

**链接**: https://arxiv.org/abs/2607.23238
**作者**: Weijie Li, Yafei Song, Yongxiang Liu, Bowen Peng, Jie Zhou, Jingyuan Xia 等 (10 人)
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [545] Enhancing Foundation Models for Imbalanced SAR Ship Classification via Targeted Oversampling

**链接**: https://arxiv.org/abs/2609.31657
**作者**: Ch Muhammad Awais, Marco Reggiannini, Davide Moroni
**来源**: cs.CV cs.AI cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Remote-sensing foundation models offer strong representations for SAR imagery, but their behavior under severe long-tail class imbalance is still not well characterized. We benchmark DOFA and SAR-JEPA on the imbalanced OpenSARShip dataset and compare them with ImageNet-pretrained baselines under a fixed, training-efficient protocol that keeps the backbone frozen. To mitigate imbalance without fine-tuning, we apply four oversampling methods in embedding space exclusively to minority classes and train a lightweight classifier head on the augmented embeddings. Across both foundation models, oversampling improves Macro-F1 and test accuracy relative to their respective baselines, with the largest Macro-F1 gains observed for DOFA using ADASYN (34.39 to 38.56) and for SAR-JEPA using SVM-SMOTE (25.89 to 32.30). We also report class-wise behavior, showing that aggregate improvements can coexist with persistent failures on specific rare classes. Code for embedding extraction and reproducible mul

---

### [546] DBCF: Dual-Branch Complementary Fusion of Foundation Models for Generalized Deepfake Detection

**链接**: https://arxiv.org/abs/2609.34720
**作者**: Fengming Gu, Mingjie He, Zonghui Guo, Jie Zhangb, Shiguang Shan
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As image generation and editing technologies have progressed substantially, facial forgeries pose significant challenges to privacy and public safety. Due to limited ability to capture forgery cues, existing small-scale forgery detection models often struggle to generalize across various domains and unseen manipulations. To address this limitation, researchers have turned to large-scale foundation models, which can provide richer representations and better generalization. Nevertheless, relying on a single foundation model alone remains insufficient for effective forgery detection. While models like CLIP offer robust global semantic cues, they lack the capacity to capture detailed local facial features. In contrast, DINO excels at capturing local structural features of faces, but provides weaker global semantic context. To fully utilize the synergies among multiple foundation models, we propose a hierarchical multi-granular framework that integrates complementary pretrained representati

---

### [547] Learning Native Reflection in Unified Models with Interleaved Reinforcement Learning

**链接**: https://arxiv.org/abs/2609.35767
**作者**: Yijia Fan, Ziqi Huang, Zhongang Cai, Yan Li, Zimo Wen, Wanqi Yin 等 (8 人)
**来源**: cs.CV cs.AI
**匹配关键词**: Unified Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Unified multimodal models can both look at and render images, so in principle they can repair their own generations: diagnose what an image gets wrong, revise it, observe the result, and diagnose again. Whether a revision helps is known only after it is rendered, so the reflection text and the image generation must be learned jointly, over the whole loop. Supervised fine-tuning (SFT) on reflection trajectories gives a cold start but does not find the high-success repair paths, and naive RL that optimizes only the renderer or only one head leaves most of the gain untapped. We introduce UMM-Reflection, which applies reinforcement learning (RL) to complete reflection trajectories inside one unified model: sibling trajectories share one initial image, so the group-relative advantage compares reflection strategies, and one trajectory-level advantage updates both the reflection tokens and the flow-based revisions, avoiding the combinatorial blow-up of per-round credit assignment. Unlike sing

---

### [548] Multimodal LLMs Outperform Pathology Foundation Models in Cross-Domain Histological Similarity

**链接**: https://arxiv.org/abs/2609.32876
**作者**: Yishu Zhang, Yun Li, Daiwei Zhang
**来源**: cs.CV cs.AI cs.CL cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> State-of-the-art pathology foundation models, trained on millions of histology tiles, can fail to preserve tissue similarity when comparisons cross slide or institution boundaries. We show that general-purpose multimodal LLMs, without being trained as pathology foundation models, consistently outperform these specialized models in cross-domain histological similarity judgments. Using a relative similarity framework that we release as the MOSAIC (Model Similarity Assessment across Institutions and Cohorts) benchmark, we evaluate 17 models across 6 datasets and find that pathology encoders often rank same-institution, different-disease tiles as more similar than same-disease, different-institution tiles, a clinically dangerous failure mode invisible to standard within-domain evaluations. LLMs appear less susceptible to this failure, likely because they perform semantic visual comparison of morphology and tissue architecture rather than relying on shortcut features tied to acquisition con

---

### [549] Reduce, Then Encode: Multiscale Volumetric Reduction for 2D Foundation Models in Brain MRI

**链接**: https://arxiv.org/abs/2609.35405
**作者**: Dexuan Ding, Yuankai Qi, Bogong Wang, Luping Zhou, Amin Beheshti
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Pretrained 2D foundation models offer a practical alternative to dedicated 3D pretraining for brain structural magnetic resonance imaging (sMRI), but their use on volumetric data requires bridging the mismatch between a 2D encoder and a 3D volume input. Existing methods typically encode slices independently and integrate their features afterwards. We introduce Multiscale Volumetric Reduction (MVR), a reduce-then-encode approach that compresses each anatomical view from (D) slices into (M << D) complementary 2D components before foundation-model encoding. MVR combines an uncentered-PCA base component derived from the original through-plane intensities with residual detail components constructed from multiscale spatial descriptors. The reduction is estimated from the training volumes without diagnostic labels or gradient-based optimization and remains fixed thereafter. The resulting components are independently processed by a shared frozen 2D foundation model and concatenated for linear 

---

### [550] Benchmarking Attention for Tabular Foundation Models

**链接**: https://arxiv.org/abs/2609.31306
**作者**: Maximilian Schambach and Clemens Biehl and Sam Thelin
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [551] Use What You Know: Causal Foundation Models with Partial Graphs

**链接**: https://arxiv.org/abs/2602.14972
**作者**: Arik Reuter, Anish Dhir, Cristiana Diaconu, Jake Robertson, Ole Ossen, Frank Hutter 等 (9 人)
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [552] Prompting Particle Physics: Tokenized Multi-modal Foundation Models for Combinatorially Many Tasks

**链接**: https://arxiv.org/abs/2609.31862
**作者**: Nilotpal Kakati, Daniel Murnane, Baran Hashemi, Samuel Klein, Jeffrey Krupa, Eilam Gross 等 (8 人)
**来源**: hep-ph cs.LG hep-ex physics.data-an
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reconstruction and simulation at a collider experiment are long chains of specialised algorithms, each tuned to a single step. We explore how one model can serve many of those steps at once, while still producing the intermediate objects (tracks, calorimeter cells, clusters, particles and jets) that make the chain interpretable. To do so, we represent every object in a jet in a single shared token vocabulary and train one model to map any subset of these modalities to any other. A task is then only a choice of which modalities to provide and which to request: particle flow, detector simulation and charged energy subtraction are all directions through the same set of weights. We train over all modality combinations, with a decoder emitting tokens either autoregressively or in parallel. With tokenisation, both architectures train stably with little tuning. In evaluations, both models produce realistic reconstruction and simulation objects, with the autoregressive model particularly faith

---

### [553] QiYao-M: Multimodal Time Series Foundation Model with Role-Aware Modeling of Endogenous and Exogenous Modalities

**链接**: https://arxiv.org/abs/2609.34842
**作者**: Hanyin Cheng and Linfeng Wang and Zhengbo Qu and Yang Shu and Zhongwen Rao and Meng Wang and Yijie Li and Xin Jiang and Bin Yang and Chenjuan Guo
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Existing multimodal time series foundation models (TSFMs) typically model heterogeneous modalities through largely shared mechanisms, overlooking the distinct forecasting roles of endogenous and exogenous modalities. In this work, we propose QiYao-M, a role-aware multimodal TSFM that models the two types of modalities separately. For endogenous modalities, to capture how they evolve along with the underlying temporal dynamics, we introduce an Endo-Multimodal Predictor and Endo-Multimodal Supervision to explicitly learn their evolution from history to the future. For exogenous modalities, to generalize across domains and across various modality types and numbers under the scarcity of exo-multimodal pretraining data, we propose an Exo-Multimodal Retrieval Enhancer that enables rapid downstream adaptation without updating the TSFM parameters. We further introduce Endo-Modality Proxy Training to train this retrieval module without exogenous multimodal pretraining data. Extensive experiment

---

### [554] Environmental Impact of Generative and Agentic AI: An in-Depth Analysis and Green Solutions

**链接**: https://arxiv.org/abs/2609.32960
**作者**: Abderaouf Bahi and Amel Ourici and Ibtissem Gasmi
**来源**: cs.CY cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The proliferation of generative and agentic artificial intelligence (AI) systems has introduced computational demands whose environmental consequences are substantial yet underexamined. This paper examines the environmental footprint of modern AI systems across energy consumption, carbon emissions, water usage, and electronic waste over the full lifecycle of large language models, multimodal foundation models, and agentic workflows, from hardware fabrication and training through fine-tuning and inference to end-of-life disposal. This work provides a conceptual analysis, utilizing order-of-magnitude estimations based on published data, without conducting original physical measurements. We contribute a lifecycle taxonomy that crosses lifecycle phases with five impact dimensions and emission scopes; a Sustainability Assessment Framework for AI Systems (SAFIA) comprising nine indicators; a comparative analysis of traditional, generative, and agentic AI; seven open challenges; policy recomm

---

### [555] KiT: A Foundation Model for Financial Time-Series Forecasting using DiffusionTransformers

**链接**: https://arxiv.org/abs/2609.34507
**作者**: Boyu Zhang, Haorui Li
**来源**: cs.LG cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Financial candlestick forecasting is fundamental to quantitative investment, yet it remains exceptionally challenging due to extremely low signal-to-noise ratios and vast heterogeneity across markets and instruments. Existing approaches have largely attempted to introduce deep learning to capture hidden temporal features, but most adopt an auto-regressive formulation, which leads to error accumulation during inference. Meanwhile, general-purpose time-series foundation models are not tailored to the unique structure of k-line data and yield unsatisfactory performance on downstream candlestick forecasting tasks. To tackle these problems, we introduce KiT, a K-line Diffusion Transformer foundation model, and reformulate future prediction as conditional path generation via flow matching: given a historical context window, the model generates an ensemble of plausible future OHLCV trajectories. We pre-train KiT at multiple parameter scales on billions of candlestick bars spanning multiple ma

---

### [556] The Devil is in the Spectrum Bias: Spectrum-Balanced Feature Matching for Robust Representation Distillation

**链接**: https://arxiv.org/abs/2609.34106
**作者**: Kuniaki Saito, Yoshitaka Ushiku
**来源**: cs.CV cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large visual foundation models have demonstrated remarkable transferability across a wide range of downstream tasks. To deploy such models efficiently, feature matching has become a popular knowledge distillation approach that transfers teacher representations to smaller student models without requiring labeled data. However, we show that the conventional feature matching objective with L2-distance is inherently biased toward reconstructing dominant spectral directions of the teacher representation, while under-optimizing low-variance directions that often contain task-relevant information. To address this, we propose Spectrum-Balanced Feature Matching, SpecMatch, a simple objective that adaptively emphasizes under-optimized spectral directions while preserving the relative importance of dominant directions. SpecMatch is easy to implement and introduces negligible computational overhead. Extensive experiments on image recognition demonstrate that SpecMatch consistently improves downstr

---

### [557] Learning When to Recur: Token-Adaptive Recursion for Imbalanced Ophthalmic Domain Incremental Learning

**链接**: https://arxiv.org/abs/2609.32785
**作者**: Nanxi Yu, Kang Li, Ye Du, Xiaowei Hu, Weihua Yang, Shujun Wang
**来源**: cs.LG cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Domain incremental learning is essential for adapting ophthalmic deep learning models to sequential clinical domains while preserving diagnostic expertise. Existing domain incremental learning methods predominantly address the domain shift induced by style variations. However, they often overlook the severe class imbalance inherent in real-world clinical scenarios, such as clinical referral systems. Institutions in these systems encounter drastic fluctuations in class priors, resulting in label distribution shift, a critical form of domain shift that triggers severe catastrophic forgetting. To address these challenges, we propose ToRe, a rehearsal-free and parameter-efficient framework that leverages frozen ophthalmic foundation models for robust incremental adaptation. ToRe employs a parameter isolation strategy to decouple domain-specific optimization paths, thereby helping mitigate catastrophic forgetting driven by both label distribution shift and style variations. Simultaneously, 

---

### [558] STAMP: Predicting Out-of-Distribution Generalization without Target Data

**链接**: https://arxiv.org/abs/2609.32672
**作者**: Md Kawsher Mahbub and Milon Biswas
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Predicting whether a trained model will generalize under distribution shift remains difficult, especially when target-domain data are unavailable. We introduce STAMP (Semantic Temporal Augmented Model Prediction), a source-only, target-label-free criterion that estimates out-of-distribution (OOD) performance from paired source-domain images. STAMP computes the output-space correlation ratio $\eta^2=S_B/S_T$ by contrasting semantically stable pairs with random pairs: higher $\eta^2$ indicates that model outputs vary with semantic identity rather than nuisance variation. On 44 chest X-ray models spanning CNNs, ViTs, MetaFormers, foundation models, and SSL/VLM probes, temporal STAMP attains Spearman correlations of $0.844$--$0.855$ with macro AUROC on VinDr-CXR, CheXpert, and MIMIC-CXR; a class-matched variant improves single-class RSNA from $0.311$ to $0.663$. STAMP attains the best average source-only medical ranking and outperforms the target-domain ATC and AoTL estimators without any 

---

### [559] A Surgical Foundation Model Reveals Task-Dependent Label Efficiency

**链接**: https://arxiv.org/abs/2609.31821
**作者**: Florian Philipp Stilz, Lorenzo Arboit, Vinkle Srivastav, CAMMA International Surgical Partners, Jacques Marescaux, Sergio Alfieri 等 (9 人)
**来源**: cs.CV cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Developing label-efficient models is a central challenge in surgical AI due to the high cost and scarcity of expert annotation. While self-supervised foundation models adapt well to new tasks with minimal data, how label efficiency varies across different surgical tasks remains largely unexplored. Here, we introduce SURGE, a surgical foundation model trained on SurgSpectrum-30M+, the largest pretraining dataset comprising over 30 million frames, with checkpoints released to enable further research. We systematically evaluate label efficiency across 5 task categories and 15 benchmarks. These range from temporal and spatial scene understanding to fine-grained reasoning tied to instrument-anatomy interactions and safety-critical maneuvers. SURGE outperforms prior state-of-the-art on all benchmarks, even surpassing task-specific models on complex reasoning tasks. Crucially, we reveal a task-dependent scaling behavior: while scene understanding tasks saturate with minimal supervision, fine-

---

### [560] CAPEX: Efficiently Distilling Foundation Model Behavior into Deployable Robot Policies through Experience-Adaptive Reasoning

**链接**: https://arxiv.org/abs/2609.33007
**作者**: Shivam Aarya, Zhang Xi-Jia, Chengyue Huang, Junhyun Kim, Huishu Xue, Hrishit Leen 等 (9 人)
**来源**: cs.RO cs.AI cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Robot learning has largely relied on human-teleoperated demonstrations to acquire effective learnable behaviors. However, human-operated data collection processes can be unintuitive, difficult to scale, and inherently asynchronous. We explore an alternative: distilling physical behavior from general-purpose multimodal foundation models into deployable robot policies by using the foundation model itself as an autonomous demonstrator. While sufficiently capable models can generate successful zero-shot manipulation trajectories, repeatedly invoking them during physical execution is slow and expensive, limiting their utility as scalable data generators. As a solution, we introduce CAPEX, an experience-conditioned demonstration collection framework that uses execution experience from previous attempts to adapt how frequently the foundation model must observe, reason, and replan. We evaluate across RoboCasa tasks and on physical Franka and bimanual YAM-arm platforms, measuring task success, 

---

### [561] From Pixel to Poses: Object-centric Tool Manipulation Learning from Human Demonstrations

**链接**: https://arxiv.org/abs/2609.35375
**作者**: Bangjun Wang, Longyan Wu, Yukun Wei, Shenghe Shao, Chaoyi Huang, Wenze Cui 等 (10 人)
**来源**: cs.RO cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Scaling up robotic manipulation is primarily bottlenecked by the scarcity of real-world robot data. While recent approaches leverage human video demonstrations to mitigate this shortage, they remain computationally expensive and still rely on paired human-robot data for domain alignment. Although current state-of-the-arts excel at long-horizon tasks, they struggle with the delicate and precise control required for complex tool manipulation. To overcome these limitations, we introduce P2P-T, from Pixel to Poses for Tool Manipulation, a data-efficient, object-centric framework that learns tool use directly from human demonstrations. P2P-T bridges the cognitive and physical execution gap through a two-stage approach. First, pretraining an object-centric world model to extract stable pose priors; second, integrating these priors into an efficient, pose-aware low-level policy. By utilizing a robust automated data processing pipeline powered by modern foundation models, P2P-T completely bypa

---

### [562] MAD-Guard: Controlled Study of Autoregressive Generation versus Direct Decision Interfaces for Closed Multimodal Forensic Tasks

**链接**: https://arxiv.org/abs/2609.33683
**作者**: Hao Chen
**来源**: cs.CV cs.CR
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> When should multimodal foundation models generate tokens, and when should they directly output a decision? We present MAD-Guard, a controlled study of output-decision interfaces for closed multimodal forensic tasks. Once a multimodal representation is computed, is autoregressive generation necessary for closed forensic decisions with high input complexity but low output entropy? Under a matched Qwen3-VL-8B backbone, 2,400 FakeClue training samples, and LoRA budget ($r=16, \alpha=32$) on Huawei Ascend 910C NPUs, we evaluate a progression of decision interfaces (AR-SFT [generate] $\to$ Logit Slice $\to$ Binary Direct Head $\to$ +choice $\to$ +act $\to$ CLM-Head) and decompose latency into backbone representation (53.12 ms), 151,643-way vocabulary projection (+85.04 ms $\to$ 138.16 ms), and decoding (+248.26 ms $\to$ 386.42 ms). Under 1-to-1 binary supervision ($\mathcal{L}_{\mathrm{BCE}}$), a Binary Direct Head cuts latency by $2.60\times$-$7.27\times$ (53.12 ms) and lowers calibration e

---

### [563] InfiMed2: A Generalist Medical Multimodal Foundation Model from Contextual Evidence and Stability-Aware Supervision

**链接**: https://arxiv.org/abs/2609.34798
**作者**: Guanghao Zhu, Zeyu Liu, Zhitian Hou, Pengkai Wang, Zhijie Sang, Shuo Cai 等 (10 人)
**来源**: cs.CL cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent medical multimodal models have benefited from larger corpora, broader modality coverage, and stronger reasoning-oriented training, yet effective data design across continued pretraining (CPT) and post-training remains challenging. Medical sources vary substantially in structure, granularity, and information density, and their utility shifts as training progresses from broad knowledge acquisition to late-stage consolidation. Meanwhile, post-training is often dominated by short-form visual question answering, providing limited supervision for informative and answer-consistent explanations. We introduce InfiMed2, a family of 4B and 27B generalist medical multimodal foundation models built around stage-aware data design. We curate a 55.68B-token corpus that combines broad clinical knowledge with context-rich biomedical visual evidence through source-specific processing. Our CPT pipeline first adapts the vision encoder, then builds broad medical knowledge, and finally transitions to 

---

### [564] Natural Image Autoencoder-Based fMRI Representations for Trait and State Prediction

**链接**: https://arxiv.org/abs/2609.34167
**作者**: Juhyeon Park, Yeonwoo Kim, Peter Yongho Kim, Yansen Wang, Mingqing Xiao, Dongqi Han 等 (8 人)
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Foundation models pre-trained on large-scale fMRI datasets have shown strong downstream performance, but at substantial data and computation cost. To investigate how much fMRI-specific pre-training is actually needed for such performance, we introduce FReD, which derives fMRI representations from a frozen Deep Compression AutoEncoder (DCAE) pre-trained exclusively on natural images and pairs them with a task specific readout. For trait prediction, FReD summarizes frame-wise representations by their temporal mean and log-standard deviation and applies linear probing, with late fusion across two normalization schemes. For state prediction, it represents each frame as a single token and models temporal dependencies with a shallow Transformer. Across four resting-state datasets spanning six trait-prediction targets, linear probes on frozen DCAE features generally outperform those on fMRI foundation model representations and remain competitive with fully fine-tuned fMRI foundation models. O

---

### [565] AUV-Bench: Aesthetic Understanding and Generation Evaluation for User Interfaces

**链接**: https://arxiv.org/abs/2609.34854
**作者**: Zhijie Deng, Ling Li, Junhao Ji, Siwei Lyu, Zhipeng Xu, Zulong Chen 等 (10 人)
**来源**: cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal foundation models are increasingly used for evaluating and generating user interfaces (UIs), often producing seemingly reasonable aesthetic judgments and visually plausible pages. However, under professional design scrutiny, their behavior can differ substantially from that of human designers. In professional design practice, designers rely on a systematic set of aesthetic principles that consistently guide judgment, diagnosis, repair, and creation. A coherent aesthetic capability should therefore connect aesthetic judgment with design actions. Existing evaluations, however, typically assess these abilities in isolation, making it difficult to determine whether task-level success reflects a shared aesthetic understanding or merely fragmented task-specific competence. To address this gap, we introduce AUV-Bench, developed in collaboration with professional UI designers around 1,395 executable web interfaces and four tasks: aesthetic scoring, diagnosis, repair, and text-to-UI 

---

### [566] No Free Efficiency: Revisiting the Trade-off Between Training Efficiency and Model Vulnerability

**链接**: https://arxiv.org/abs/2609.33898
**作者**: Yiyong Liu, Jun Sakuma, Michael Backes, Rui Wen
**来源**: cs.LG cs.CR
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Training efficiency has become the central driver of recent progress in foundation models. To overcome the massive computational and data requirements of large-scale training, researchers increasingly adopt strategies such as selective data sampling, efficient pre-training, and simplified reinforcement learning pipelines. While these strategies drastically reduce overhead, they prompt a critical, yet neglected question: Is efficiency achieved at the expense of model robustness and security? To our knowledge, we present the first systematic cross-domain investigation of the efficiency-vulnerability trade-off. Across vision and language models, we show that efficiency-oriented training increases susceptibility to adversarial and privacy attacks. We characterize this vulnerability by analyzing the models' internal geometry and functional representations, demonstrating that the evaluated efficient variants consistently exhibit sharper loss geometry together with systematic changes in repre

---

### [567] Role-Guided MOE for Encoder-Level Pathology Representation Learning in WSI Classification

**链接**: https://arxiv.org/abs/2609.34897
**作者**: Xinyu Ma, Xing Yang, Hongtao Jin, Guoquan Zhang, Shijie Zhang, Yu Zhang 等 (7 人)
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Whole slide image classification is a fundamental task in computational pathology, where patch representation quality directly affects downstream aggregation and slide-level discriminability. Pathology foundation models are widely adopted as frozen feature extractors for WSI classification; however, their fixed encoders may produce representations insufficiently adapted to target-specific tissue patterns and discriminative cues. Fine-tuning can improve target adaptation, but introduces a trade-off between pathology-specific representation capacity and adaptation efficiency, particularly in data-scarce settings. To address this, we propose a pathology role-guided mixture-of-experts feed-forward network (MoE-FFN) framework for efficient encoder-level representation learning. We design a two-stage training paradigm to establish and adapt pathology-aware expert specialization. In source-domain expert initialization, pathology-specific priors are distilled from a frozen Virchow2 teacher int

---

### [568] Fracast-0: Fractal Weight Sharing for a Time Series Foundation Model with Only 85K Parameters

**链接**: https://arxiv.org/abs/2609.32209
**作者**: Tianxiang Zhan, Huanyao Zhang, Yuanpeng He
**来源**: cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Time series foundation models must preserve multi-domain breadth, probabilistic output, and multiple temporal scales, but parameter count grows when each scale receives a separate representation. We introduce Fracast-0, a probabilistic forecasting foundation model that exploits temporal self-similarity to reuse one operator across scales. A parameter-free detector extracts significant seasonal structure. The encoder applies a shared local block along a geometric dilation ladder with scale conditioning, while the decoder combines context-gathered states with an explicit seasonal future state and reuses a second block along another ladder before emitting nine quantiles. Pretraining across six corpora preserves multi-domain breadth within 85,001 parameters. On 97 GIFT-Eval configurations without per-dataset fine-tuning, Fracast-0 is the smallest of 28 evaluated checkpoints and remains non-dominated in the aggregate parameter-accuracy plane with MASE 0.808 and WQL 0.564. It uses 42.0% fewe

---

### [569] Jev thinks "I don't know'', but doesn't say it: Introducing Sys1Cal-v1 Dataset for Probability Calibration

**链接**: https://arxiv.org/abs/2609.35342
**作者**: Riccardo Porcedda
**来源**: cs.AI cs.LO cs.SY eess.SY
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The appearance of Jev marked the era of System One Models, foundation models that return structured decisions with probability distributions rather than text. Aside from low cost and great speed, Jev's central promise is that these probabilities are calibrated: such claim is not backed by any public test and available external benchmarks evaluate confidence calibration, not whether every returned option probability has the right numerical meaning. To tackle this issue, we introduce Sys1Cal-v1, a dataset of True/False questions about a proposition $A$ for which the exact probability $P(A)$ is known by construction. Each item is queried through the three Jev primitives - Noul, Choice and Score - and evaluated by total variation distance from the ground-truth distribution, which can be used to estimate a soft accuracy of System One Models. We showcase the utility of Sys1Cal-v1 as a benchmark dataset by evaluating Jev and SemIf, an open-source Choice-style baseline. In this work, however, 

---

### [570] Backdoor as Probe: Test-Time Adversarial Defense for CLIP

**链接**: https://arxiv.org/abs/2609.34641
**作者**: Zhongqi Wang, Jie Zhang, Nie Sen, Zhiyu Chen, Shiguang Shan, Xilin Chen
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Test-time adversarial defense improves the robustness of vision-language foundation models such as CLIP without retraining. However, adversarial activation shifts are typically treated as distortions to suppress, rather than signals to exploit. We turn these shifts into defense signals by repurposing the trigger-to-target mechanism of backdoors. The key is to implant a defender-controlled backdoor as a probe that is weakly activated by clean inputs but strongly activated by adversarial shifts. Based on this insight, we propose \emph{Backdoor as Probe} (BaP), a test-time adversarial defense for CLIP. BaP constructs the probe through a closed-form model edit to a selected MLP layer. It projects the average adversarial activation shift and a defender-specified semantic direction onto the layer's low-energy input and output activation subspaces to obtain the trigger and target directions, respectively. At inference time, adversarial inputs produce measurable responses along the target dire

---

### [571] Scalable In-Domain Self-Supervised Foundation Model for Dense Representation Transfer in High-Resolution Plant Imaging

**链接**: https://arxiv.org/abs/2609.32183
**作者**: Junlin Guo, Sharmin Majumder, Isaac Lyngaas, John Lagergren, Xiao Wang
**来源**: cs.CV eess.IV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> High-resolution plant imaging enables detailed characterization of plant morphology, but dense scientific analysis remains limited by costly pixel-level annotations, large image pixel dimensions, and substantial variation in imaging conditions. This work proposes a scalable in-domain self-supervised pretrained foundation model for high-resolution, high-pixel-dimension multi-species plant imagery. A masked autoencoder with a ViT backbone is pretrained on more than 10 million multi-view plant image tiles using distributed training. Following scalable pretraining, the learned foundation-model representations are comprehensively benchmarked across fine-grained dense prediction and coarse global feature recognition, with particular emphasis on limited supervision and realistic downstream imaging conditions. This work focuses on the domain gap of existing foundation models in dense feature representation and transfer. Through extensive experiments involving limited annotations, cross-view va

---

### [572] Fisher-Informed Recalibration for Feedback-Based On-Policy Self-Distillation of LLMs

**链接**: https://arxiv.org/abs/2609.34009
**作者**: Seohyun Lee, Dong-Jun Han, Seyyedali Hosseinalipour, Christopher G. Brinton
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Feedback-based on-policy self-distillation has emerged as a promising approach for enabling foundation models, more specifically Large Language Models (LLMs), to learn from their own outputs under external feedback, with a single model serving as both teacher and student. However, such methods can exhibit unstable optimization, conducive to performance collapse during training. To address this limitation, we propose FIRE (Fisher-Informed REcalibration), a dual-branch framework that recalibrates the supervision applied to correct and incorrect on-policy outputs during fine-tuning. For correct responses, FIRE replaces self-distillation with re-weighted on-policy SFT, while for incorrect ones FIRE identifies feedback components that disproportionately influence the teacher-induced update and recalibrates the feedback-conditioned target accordingly. Both branches are influenced by a token-level radius derived in part from a softmax Fisher trace. FIRE separates which direction feedback shou

---

### [573] Test-Time Spatial Reasoning for Robot Manipulation Using Generative Real-to-Sim

**链接**: https://arxiv.org/abs/2609.33982
**作者**: Ivan Kapelyukh, Yafei Hu, Ran Gong, Brandon May, Tushar Kusnur, Laura Herlant 等 (9 人)
**来源**: cs.RO cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Spatial reasoning is fundamental to general robot intelligence, as it enables robots to complete long-horizon tasks involving multi-object interaction. We introduce Simify, a training-free, test-time framework that performs explicit spatial reasoning via massively parallel physics simulation. From a single RGB-D image of a scene, Simify reconstructs simulation-ready assets leveraging 3D generative models and vision-language models. Then given a task specified by a reward function (e.g., build the tallest tower), Simify launches thousands of parallel rollouts in simulation and performs an evolutionary search to optimize object arrangements, typically converging within seconds. We conduct quantitative experiments on real-robot hardware to demonstrate the ability of our framework to execute complex object rearrangement tasks end-to-end with previously unseen objects. Results show that our framework outperforms prior work on foundation models for spatial reasoning by effectively exploiting

---

### [574] RECAST: Recasting Vision-Language Semantics into an Actionable Cost Map for Robot Navigation

**链接**: https://arxiv.org/abs/2609.32595
**作者**: Incheol Cho, Jintae Park, Jinkyu Kim, Jungbeom Lee, Jaegul Choo, Seokha Moon
**来源**: cs.RO cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Safe and robust robot navigation across diverse environments requires a high-level understanding of complex scenes and the ability to carry it into stable motion. Recent works tackle this with learning-based models trained at scale and with approaches built on vision-language models (VLMs). However, learning-based models break down outside their training distribution, while VLM-based approaches bring that understanding but rarely ground it in the scene or align the action with it. To address these limitations, we present RECAST, a robot navigation framework that combines the reasoning of a VLM with the spatial grounding of vision foundation models to build an Actionable Cost map. Given the robot's front view and the user's instruction, we first decompose the scene with the VLM, judging which surfaces are traversable, which objects pose a risk, which heading to prefer, and which gaps are passable. Vision foundation models then ground these surfaces and objects in the image, and all four

---

### [575] InfoEdit: Probing Global Layout Reasoning in Infographic Editing

**链接**: https://arxiv.org/abs/2609.33286
**作者**: Cheng Yang, Chufan Shi, Huijuan Wang, Bo Shui, Yaokang Wu, Muzi Tao 等 (9 人)
**来源**: cs.CV cs.CL cs.SE
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal foundation models edit natural photographs at production quality, yet the same models struggle with structured visual content such as infographics. Unlike photographs, infographics encode information through logical relations; editing one element often requires surrounding elements to be adapted. We refer to this global layout reasoning capability as reflow. Existing image-editing benchmarks neither provide a dedicated setting for structured visual content nor evaluate the reflow capability. We introduce InfoEdit, a novel benchmark of 1,000 infographics across eight logical-relation families, paired with 4,000 editing instructions across four editing tasks, and a reflow-aware evaluation protocol. Across eight frontier editors, only GPT-Image-2 clears 60% average success rate; most models fall below 7%, and no editor exceeds 36% on the Swap-Block task even with perfect target localization. We further show that code-level editing can match the strongest pixel-level editor, rev

---

### [576] A General Harness for Protein Foundation Model Fitness Prediction

**链接**: https://arxiv.org/abs/2609.34654
**作者**: Yang Tan, Qijia Tian, Gangyu Sun, Bozitao Zhong, Mingchen Li, Yuanxi Yu 等 (8 人)
**来源**: cs.AI q-bio.QM
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Accurate fitness prediction is central to protein engineering and understanding sequence-function relationships. With advances in deep learning, protein foundation models (PFMs) have become widely used for this task. Recent analyses, however, show that these models share preferences reflecting their training corpora, while unreliable inputs can further distort fitness predictions. Family-specific evolutionary evidence and structural context can help address these limitations by providing complementary constraints on model scores, motivating VenusREM-Harness (VRH), a general, model-agnostic, training-free Retrieval-Enhanced Mutation harness. It fuses frozen model scores with multiple sequence alignment (MSA) evidence according to model uncertainty, then applies gated background correction and score shrinkage based on structural confidence and solvent exposure. Across 1,211 assays and 3.1 million measured variants from ProteinGym, VenusMutHub, and the newly curated viral benchmark VenusV

---

### [577] When Less Compute Is More: Adaptive Early Exit Improves Pretrained Outlier Detection

**链接**: https://arxiv.org/abs/2609.32898
**作者**: Tianyang Zhou, Leman Akoglu
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Pretrained tabular foundation models process every dataset at a fixed depth, with inference costs growing with dataset size. To address this, we present the first study of depth-adaptive early-exit for pretrained outlier detection models. While early-exit is typically motivated by efficiency, we uncover a surprising benefit: exiting at the optimal intermediate layer can also improve detection performance on diverse real-world benchmarks by 4.7-7.3% on average, consistent across three distinct foundation models. First, we investigate the factors driving these gains, and identify a key mechanism: context pollution, i.e., the presence of outliers among in-context samples. Our analysis reveals that nearby in-context samples exert increasing influence on query predictions at greater depths, consistent with a retrieval-based view of these models. In effect, early-exit alleviates the adverse effects of retrieving accurate-yet-polluted neighbors, with gains of 13-21% when context pollution mat

---

### [578] PPG-LM: A Photoplethysmography-Language Model with Multi-Level Clinical Alignment

**链接**: https://arxiv.org/abs/2609.33516
**作者**: Xiaoda Wang, Minxiao Wang, Maxwell A Xu, Patrick Langer, Kaiqiao Han, Defu Cao 等 (10 人)
**来源**: cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Photoplethysmography (PPG) is widely recorded by clinical monitors and consumer wearables, providing a scalable source of continuous physiological information. These recordings offer an opportunity for physiological assessment at scale, but realizing this potential requires models to learn from both signal-derived physiological supervision and broader clinical context captured in electronic health records (EHRs). This involves aligning information spanning local observations, care events, and entire visits with PPG representations at corresponding temporal scales. However, existing PPG foundation models primarily rely on task-specific prediction heads, while the medical knowledge of large language models does not necessarily translate into waveform understanding. To bridge this gap, we introduce PPG-LM, the first PPG-language model family to learn physiological representations from both signal-derived supervision and broader clinical context captured in EHRs. To construct clinically gr

---
