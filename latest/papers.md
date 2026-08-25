# 📑 论文索引 - 2026-08-25

共 353 篇论文

---

### [1] Evaluating Large Language Model Performance on International Maritime Dangerous Goods Code Compliance

**链接**: https://arxiv.org/abs/2608.21036
**作者**: Alexander Thomas, Hubert P. H. Shum, Darren Nellis, Manli Zhu, Phatpicha Yochum, William Bartle and Daniel Wrightson
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The transport of dangerous goods by sea is a high-consequence activity governed by the International Maritime Dangerous Goods (IMDG) Code, a complex regulatory framework where errors in classification, packaging, stowage, or segregation can result in fire, explosion, toxic release, or loss of life or vessel. Correct compliance requires accurately interpreting hundreds of pages of interacting provisions, updated on a two-year amendment cycle. Practitioners increasingly use Large Language Models (LLMs) as decision-support tools, yet no systematic evaluation exists of whether they can reliably interpret IMDG requirements for safety-critical use. This paper introduces DGEval, the first benchmark for evaluating LLM knowledge of IMDG Amendment 42-24. Built from expert-written questions on the NCB Hazcheck e-learning platform and structured lookups from the Dangerous Goods List (DGL), it comprises 1,678 questions across multiple-choice, open-ended, DGL lookup, and regulatory identification ta

---

### [2] Causal Modeling of Adverse Pregnancy Outcomes via Adaptive LLM Proposals

**链接**: https://arxiv.org/abs/2608.21079
**作者**: Kavimayil P. Komarasamy, Saurabh Mathur, Ameet Soni, David M. Haas, Kristian Kersting, Sriraam Natarajan
**来源**: cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Adverse Pregnancy Outcomes (APOs) such as preterm birth and gestational diabetes can have long-term consequences for both the mother and child, yet an understanding of their causes remains elusive. Causal discovery in this domain is especially challenging due to a paucity of data and incomplete domain knowledge. As a result, pure data-driven methods fail, and Large Language Model (LLM) outputs remain inconsistent or contradictory. We introduce a neurosymbolic framework for generating plausible causal hypotheses that iteratively combines the broad prior knowledge of LLMs with empirical scoring on data. Our method treats the LLM as an adaptive proposal distribution, generating hypotheses that are scored against empirical data; the resulting high-scoring graphs are then used to update the LLM's context, steering subsequent generations toward more promising regions of the hypothesis space. We evaluate our approach on a real-world clinical dataset for modeling APOs and their risk factors, c

---

### [3] When Not to Imitate: Boundary-Aware Skill Memory for Reliable Tool-Use LLM Agents

**链接**: https://arxiv.org/abs/2608.22339
**作者**: Zihan Lin and Zhenyu Chen and Jiawen Wei and Xiaohan Wang and Jie Cao and Jiajun Chai and Wei Lin and Guojun Yin and Ran He
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Extracting skills from past successes is critical for the efficient evolution of Large Language Model (LLM) agents. Prevailing agent self-evolution paradigms typically rely on a core assumption: equipping LLMs with skill memories derived from successful trajectories will monotonically improve their problem-solving capabilities. However, probe analyses reveal that extracting skills solely from successful trajectories traps the model in a \textbf{Skill Imitation Trap}. For tasks that resemble past successes but require different tools, retrieving more skills paradoxically increases the model's confidence in wrong tool calls---procedure skills raise the wrong-tool margin by $47\%$ over a memory-free baseline. To overcome this limitation, we propose \textbf{Boundary-Aware Skill Memory} (BASM), which augments each skill with explicit boundary fields---applicability conditions, risk cues, avoidance rules, and recovery notes. These fields transform each retrieved skill from an unconditional a

---

### [4] MSM-Mem: A Universal Medical Structured Multimodal Memory Framework for Medical AI Agents

**链接**: https://arxiv.org/abs/2608.21810
**作者**: Md Asaduzzaman Jabin, Khoa Le, Lin Zhao, Tianming Liu
**来源**: cs.LG cs.CV
**匹配关键词**: Large Language Model, MLLM, Multimodal Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Clinical decision-making is inherently experience-driven: physicians progressively refine their reasoning by synthesizing patient history, multimodal observations, and prior diagnostic experiences across interactions. In contrast, current multimodal large language model (MLLM)-based medical AI agents largely operate as stateless inference systems, generating decisions independently for each interaction without retaining or internalizing experiential knowledge. This discrepancy limits their ability to progressively improve reasoning reliability through usage and adapt to longitudinal patient contexts in real-world clinical workflows. In this study, we propose Medical Structured Multimodal Memory (MSM-Mem), an agentic memory framework that enables medical AI agents to evolve through accumulated clinical experiences. MSM-Mem organizes heterogeneous clinical experiences into semantic, episodic, and visual memory and incrementally updates them during inference, allowing the agent to retriev

---

### [5] Closed-Loop Bayesian Molecular Inverse Design with Semantic LLM Surrogates

**链接**: https://arxiv.org/abs/2608.22967
**作者**: Yaoyao Xu, Xinjian Zhao, Xiaozhuang Song, Lei Bai, Tianshu Yu
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Practical molecular inverse design is rarely a one-shot generation problem; it often takes the form of closed-loop candidate-pool enrichment, where under a limited oracle budget the goal is to \emph{increase the fraction of generated molecules that match a desired property profile}. Bayesian optimization (BO) offers a natural framework for this setting, yet standard Gaussian-process surrogates typically operate in compressed continuous embeddings, which discard the substructural and reference-similarity signals that chemists naturally use to decide where to look next. We propose \textbf{\method}, a closed-loop framework in which the surrogate, rather than the generator, is treated as the locus of design choice, and instantiate it with a frozen large language model that reasons directly over the task instruction, SMILES-level optimization history, and oracle feedback in their native textual form. At each iteration, the surrogate returns a structured decision signal that selects informat

---

### [6] An LLM agent for end-to-end computational materials discovery

**链接**: https://arxiv.org/abs/2608.20434
**作者**: Chen Yuntong and Huang Ju and Liu Yu and Zhao Dan and Sun Mingqi and Ju Chentian and Liu Yanbing and Huang Lijiang and Zhao Guobin
**来源**: cond-mat.mtrl-sci cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The coordination of multi-scale tasks is an effective strategy for computational materials discovery, yet the repeated application of diverse algorithms and tools renders it challenging. We report MAESTRO, a large language model (LLM) agent system capable of executing the entire screening pipeline for metal-organic frameworks (MOFs). It processes a large body of MOF literature, links relevant publications to their crystal structures, and curates the results into a computation-ready database, which is then screened through a strategy of progressively increasing computational cost. The promising candidates identified for separation under wet flue gas conditions all originate from unrelated studies. By connecting the heterogeneous stages of computational materials discovery, the LLM-based agents of MAESTRO can operate across application domains and uncover high-performance materials that conventional screening approaches would be unlikely to consider.

---

### [7] Weighted Memory Tree: Remembering What Matters for Long-Horizon LLM Agents

**链接**: https://arxiv.org/abs/2608.20631
**作者**: Quang Dao, Purvi Kathalkar, Kenneth Eaton
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents have demonstrated the ability to solve multi-step tasks requiring planning, tool use, and external information access, yet growing execution histories increase inference cost and expose reasoning to outdated, irrelevant, or misleading information, potentially degrading reasoning quality. Existing memory approaches organize or compress execution histories but provide limited mechanisms for deciding which memories remain active. We introduce the, a hierarchical memory system that organizes execution into tasks, subtasks, and actions while assigning each memory a dynamic retention score. Event-based updates and selection-based decay revise these scores, allowing WMT to preserve useful information, fold completed trajectories, suppress low-utility content, and retain access to folded context. We evaluate WMT on GAIA-Text using Qwen3-8B, Gemma 4 E4B, and Llama-3.1-8B, with ablations and memory-poisoning experiments. Relative to linear memory, WMT improves a

---

### [8] Recognition-Conditioned Reasoning: A Training-Free Multimodal-LLM Pipeline for Fine-Grained Micro-Action Understanding

**链接**: https://arxiv.org/abs/2608.21022
**作者**: Fengshun Wang, Jin'ang Han, Zhigang Tu
**来源**: cs.CV cs.MM
**匹配关键词**: LLM, MLLM
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Micro-actions are subtle, short, low-amplitude body movements, such as a fidgeting hand or a slight head tilt, that humans perform with little conscious intent yet that reliably leak emotional and psychological state. Understanding them goes beyond assigning a label: a model must also describe which body parts move and reason, faithfully, about why a clip warrants a particular fine-grained category. We present the training-free, prompt-only system that won first place in the fine-grained understanding track (MA-Bench) of the MAC~2026 Micro-Action Challenge, where both fine-tuning and ground-truth supervision are disallowed. Built entirely upon frozen multimodal large language models (MLLMs), the system dynamically routes each of the eight sub-tasks to the MLLM empirically best suited for that task: a discriminative MLLM for closed-ended recognition tasks and a generative MLLM for open-ended description and reasoning tasks. This architecture achieves a statistically significant performa

---

### [9] The Chase Is the Curriculum, the Capture Anchors the Credit: Pursuit-Evasion Self-Play for Zero-Data LLM Reasoning

**链接**: https://arxiv.org/abs/2608.21871
**作者**: Jing Yu, Shengchao Chen, Yiyun Tan
**来源**: cs.CL cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reinforcement learning with verifiable rewards has become the dominant recipe for improving large language model reasoning, yet it presumes large human-curated task collections. Zero-data self-play removes this dependency, but existing methods vet learnability only by probing candidates and rejecting post hoc, never learning where along an environment's difficulty axis to place a task, and credit the solver with sparse terminal rewards alone. We recast zero-data self-play as a pursuit-evasion game: in LURE, an LLM evader positions tasks along each environment's difficulty axis to stay one step ahead of a planner-executor pursuer that hunts it down through verifiable interaction. The evader is trained on a capture-frontier reward that peaks when the solver captures it on exactly half of its rollouts, turning barely catchable into a learned positioning strategy rather than a hand-tuned rejection band. The pursuer earns capture-anchored dense process credit, in which monotone verifier pro

---

### [10] An ambiguity taxonomy for evaluating large language model performance on clinical registry abstraction: a multi-site prospective study

**链接**: https://arxiv.org/abs/2608.20373
**作者**: James Matheson, Betsy Castillo, Andrew Y. Shin, David Scheinker
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Objective: To evaluate large language model (LLM) performance on unprocessed electronic medical record (EMR) data for clinical registry abstraction. Methods: We evaluated LLM performance answering registry questions for the American College of Cardiology National Cardiovascular Data Registry (ACC NCDR). In a pilot study at an academic medical center, the model identified candidate data sources for each registry question and experienced abstractors used these results to define question-specific document sets. In a validation study at a second center with a second ACC NCDR registry, the LLM answered questions using the question-specific document sets. Before reviewing any output, two abstractors independently established the ground truth and assigned each question to one of six categories, ordered by the ambiguity and clinical reasoning required to resolve it: Medication/Event Flag, Binary Clinical Presence, Administrative, Quantitative Laboratory/Physiologic, Clinical Interpretation, an

---

### [11] LLM-based Agents for Forecasting and Prediction: Methods, Training, Evaluation, and Applications

**链接**: https://arxiv.org/abs/2608.23058
**作者**: Xiaogang Xu, Jiaqi Tang, Jianmin Chen, Yingying Yan, Zhenchao Tang, Xiangxin Zhou 等 (10 人)
**来源**: cs.AI
**匹配关键词**: Foundation Models, LLM
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) now support forecasting systems that combine language-based reasoning with temporal data, evidence retrieval, external tools, and iterative prediction. We investigate LLM-based forecasting agents, meaning systems in which a language model contributes to a scored prediction about a future or currently unobserved target. We organize architectures into three groups. Standalone LLM workflows operate on encoded time series or event context. Tool- and retrieval-augmented agents incorporate external evidence. Hybrid systems pair LLMs with statistical or foundation models. We then review training methods and evaluation protocols. We examine negative as well as positive evidence, including sensitivity to small input perturbations, ablations in which the LLM component does not improve accuracy, and benchmark gains that may reflect contamination instead of temporal reasoning. We cover applications in finance, weather, health, energy, and operations, and we summarize t

---

### [12] Toward Effective and Reliable LLM Agents via Dynamic Ontology

**链接**: https://arxiv.org/abs/2608.22974
**作者**: Xiaohui Zhang and Zequn Sun and Chengyuan Yang and Yuanning Cui and Lingbing Guo and Wei Hu
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents rely heavily on knowledge encoded in model parameters or presented as unstructured context. In domain-specific tasks, this leaves important semantic connections implicit. This often results in incomplete evidence use and brittle multi-step decisions. Ontologies offer a way to externalize domain concepts and relations as machine-interpretable structures, but constructing task-usable ontologies traditionally requires substantial effort from domain experts and is difficult to scale. Automatic construction is also challenging: an ontology that appears semantically plausible may not contain the relational structures needed for actual decision making. We present OaK, an ontology-as-a-kernel framework that dynamically constructs and refines task-oriented ontologies for LLM agents. Given task requirements and training data, OaK constructs an ontology and its knowledge graph, generates task-adaptation functions for graph reasoning, and uses judge feedback to it

---

### [13] Let Credit Follow Computation: Architecture-Aware Credit Transport for Large Language Model Reinforcement Learning

**链接**: https://arxiv.org/abs/2608.21501
**作者**: Qifan Shi, Zhaolu Kang and Chenghua Zhu
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Credit assignment in large-language-model reinforcement learning (LLM RL) can be separated into three objects: evidence about success, a transport operator that converts this evidence into token-level advantages, and an update geometry that turns advantages into policy changes. Recent work has greatly improved evidence, sampling, and update geometry, but the transport operator is usually architecture-agnostic. Fixed-discount GAE applies a stationary geometric kernel along token time; group-relative methods broadcast an outcome statistic across an entire response. Neither operator represents the trajectory-specific computation used by the Transformer policy itself. We introduce computation-conditioned credit transport (CCT), a general framework in which a detached statistic of the behavior policy's internal computation parameterizes the causal kernel that transports downstream value through a rollout. Our concrete algorithm, CompPO, maps native attention concentration to a bounded per-t

---

### [14] LEHiD: LLM -Empowered Hierarchical DRL Framework for Path Planning in UAV Networks

**链接**: https://scholar.google.com/scholar_url?url=https://ieeexplore.ieee.org/abstract/document/11659105/&hl=zh-CN&sa=X&d=4152459499998929877&ei=FduMaq_cKsy56rQPl--66AI&scisig=AIVdB-wgZIhjJn6wfzQNz27H_Zi0&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=8&folt=kw-top
**作者**: J Zhang, H Huang, D Li, H Zhao - IEEE Transactions on Mobile Computing, 2026
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: Google Scholar

**摘要**:

> To address this gap, we propose LEHiD, a hierarchical framework that combines a Large Language Model ( LLM ) for high-level target … The results indicate that LEHiD remains competitive with strong non- LLM hierarchical training baselines

---

### [15] ConceptTS: LLM-Guided Concept Bottlenecks for Interpretable Multivariate Time-Series Forecasting

**链接**: https://arxiv.org/abs/2608.21277
**作者**: Yichen Jiang and Yueqiao Chen and Dongyu Liu
**来源**: cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> State-of-the-art multivariate time-series forecasters can model complex temporal and cross-variable dependencies, yet their opaque representations provide limited insight into why a particular forecast is produced. This lack of transparency restricts their use in settings where practitioners must understand and assess the factors underlying a prediction. We introduce ConceptTS, an interpretable forecasting framework that organizes its predictions around named, human-readable concepts. ConceptTS uses a large language model to propose task-relevant concepts and generate executable labeling rules, translating the language model's domain knowledge into direct supervision without costly manual concept annotation. The proposed concepts are organized into three complementary bottlenecks that describe the historical context, local forecast intervals, and the full forecast horizon. A shared decoder combines representations derived from their predicted activations to construct the forecast, maki

---

### [16] Physics-validated action masking with LLM -guided decomposition for autonomous excavation

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S0926580526004504&hl=zh-CN&sa=X&d=16554644603062970367&ei=FduMaq_cKsy56rQPl--66AI&scisig=AIVdB-x9rWt_-0pNRTlA8DtnUvme&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=1&folt=kw-top
**作者**: J Cho, M Shin, B Kim, B Cha, J Kim, S Jung - Automation in Construction 等 (7 人)
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: Google Scholar

**摘要**:

> This paper proposes autonomous physics-validated excavation (APEX), a hierarchical framework integrating large language model ( LLM )-based geometric decomposition, masked reinforcement learning (RL), and polytope-validated

---

### [17] NetConfArena: An Executable Benchmark for LLM Agents in Closed-Loop Network Configuration

**链接**: https://arxiv.org/abs/2608.23179
**作者**: Chang Liu, Xiaohui Xie, Xinyi Chen, Yong Cui
**来源**: cs.NI cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents are increasingly attractive for automating network configuration, yet their reliability and failure patterns are poorly understood. An essential prerequisite is to assess such agents in a realistic but risk-free environment. Existing benchmarks, however, fall short: they often treat configuration as static command generation or rely on overly simplified settings. Such evaluations understate the core challenges of network configuration, where correctness requires reasoning about protocol complexity and topology dependence. We present NetConfArena, an executable benchmark for evaluating LLM agents in closed-loop network configuration. NetConfArena places agents in emulated multi-device networks, provides a standardized and compact action interface for task execution, and evaluates the resulting network behavior with hidden task-specific executable test cases. The benchmark relies on an LLM-assisted, emulation-grounded pipeline, which converts human-orien

---

### [18] presto: Efficient, Training-free, and Open-world Object Placement via Imaginary Search

**链接**: https://arxiv.org/abs/2608.21543
**作者**: Weixuan Ding, Shang Liu, Hanyu Pei, Zeyan Liu
**来源**: cs.CV cs.AI
**匹配关键词**: Large Language Model, MLLM, Multimodal Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Object placement is critical in image composition, requiring spatially and semantically coherent positioning of objects within diverse scenes. Existing approaches typically rely on hand-crafted rules or supervised learning on limited datasets, which restricts their generalization and interpretability, especially in open-world scenarios involving novel objects and scenes. In this work, we reformulate open-world object placement as a heuristic search task guided by reasoning from a Multimodal Large Language Model (MLLM). We introduce \textsf{presto}, a zero-shot, training-free framework that operates within an imaginary action space to iteratively refine object position and scale. Our coarse-to-fine search strategy ensures fast convergence, and we evaluate two decision-making variants: Metric-guided Selection and MLLM-as-a-judge. Experiments across multiple benchmarks show that \textsf{presto}~achieves state-of-the-art performance, particularly in previously unseen, open-world settings. 

---

### [19] Bi-EZP: LLM-Guided Bilevel Program Evolution for Ensemble Zero-Cost Proxy Discovery

**链接**: https://arxiv.org/abs/2608.21927
**作者**: Yutao Lai, Kezhao Lai, Hai-Lin Liu
**来源**: cs.LG cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Zero-cost proxies enable neural architecture search (NAS) to rank candidate networks from statistics computed at initialization, avoiding repeated training. However, different proxies capture different properties and often produce inconsistent rankings across search spaces. Ensemble proxies can combine complementary signals, but automated discovery must optimize both discrete aggregation structures and their continuous coefficients, making structural quality difficult to separate from parameter calibration. We propose Bi-EZP, a bilevel framework that decouples these decisions. At the upper level, a large language model generates executable aggregation programs over four complementary base proxies with program-specific parameter bounds. At the lower level, covariance matrix adaptation evolution strategy (CMA-ES) optimizes the continuous parameters of each fixed program on an inner training split. The calibrated programs are then evaluated using Kendall's rank correlation on a disjoint v

---

### [20] ClawSentry: A Progressive Multi-Tier Security Monitor for Safeguarding Autonomous LLM Agents

**链接**: https://arxiv.org/abs/2608.21101
**作者**: Kai Wang, Zeming Wei, BiaoJie Zeng, Chang Jin, An Wang, Xiaokun Luan 等 (10 人)
**来源**: cs.CR cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As large language model (LLM) agents move from conversation to executing code, reading local files, and orchestrating external tools, a single agent hijacked by a malicious third-party skill can cause data exfiltration, privilege escalation, or cascading compromise. We argue that agentic risk is progressive: it can enter at four loci of the agent control loop--skill admission, invocation-time intent, execution-time effect, and post-action consequence--while a denied dangerous objective can reappear across surface forms, tools, or turns; existing safeguards are typically local to one lifecycle boundary or one call. Guided by this threat model, we present ClawSentry, an open-source, framework-agnostic security supervision gateway for agent runtimes. Before a skill package is ever executed, First-use Skill Package Review (FSPR) audits it under a deterministic evidence floor, escalating unresolved cases to bounded read-only agentic review (locus A). At runtime, a three-tier progressive dec

---

### [21] From Diagnosis to Redesign: Using Quantitative Ethnography to Improve Multi-Agent LLM Reasoning

**链接**: https://arxiv.org/abs/2608.22566
**作者**: Vedant Khatri, Anthony Cusimano, Zachari Swiecki, Zhen Xu, Xiner Liu, Renzhe Yu
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-agent large language model (LLM) systems are designed to improve reasoning by decomposing tasks across multiple agents with specialized functions, but the presence of multiple agents does not inherently guarantee coherent reasoning or outputs that align with task objectives. This paper introduces a quantitative ethnographic (QE) approach for diagnosing and redesigning multi-agent LLM systems based on the discourse produced through agent interactions. We test this approach using automated essay scoring as an example context, applying Epistemic Network Analysis (ENA) to model a five-agent multi-agent debate system and examine differences between debates that produced correct versus incorrect scoring decisions. Results show that, in the initial system, correct scoring decisions were characterized by rubric-grounded justification, agreement, and elaboration. Incorrect scoring decisions, in contrast, were characterized by extended proposition-challenge-response exchanges that were les

---

### [22] Performance of a domain-specific large language model in answering patient questions in psychiatry

**链接**: https://arxiv.org/abs/2608.22797
**作者**: Alexander J. Hish, Arjun Nagendran, Scott N. Compton
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Background This study was designed to evaluate whether a domain-specific large language model (LLM) trained exclusively on patient education resources can answer questions about psychiatric medications, in a manner superior to LLM chatbots. We developed an LLM ("MIND") fine-tuned for clinical fidelity, trained on patient education resources from authoritative medical organizations. Methods We compared the responses of MIND, ChatGPT, and OpenEvidence to patient questions about escitalopram, using two methods: (1) computer analysis according to a rubric measuring accuracy, clarity, completeness, nuance, safety, and referral appropriateness; (2) ratings from N=10 board-licensed psychiatrists on similar metrics. Results When rated by rubric, MIND was rated highest in all domains (p<0.001). When rated by psychiatrists, ChatGPT was rated accurate more often than MIND with a negligible effect size (p=0.021, r=0.073); MIND was rated complete more often than ChatGPT with a small effect size (p<

---

### [23] Vis-Poison: Poisoning Visual Knowledge in Multimodal Retrieval-Augmented Generation

**链接**: https://arxiv.org/abs/2608.20756
**作者**: Rujin Liang, Zhongpu Chen, Yuhao Lei, Xin Miao
**来源**: cs.CV cs.AI
**匹配关键词**: Large Language Model, MLLM, Multimodal Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> While multimodal retrieval-augmented generation (RAG) systems increasingly rely on images as external knowledge sources, the introduction of poisoned visual evidence can severely compromise multimodal large language model (MLLM) generation. Unlike prior attacks that rely on altering textual metadata, we introduce Vis-Poison, a novel visual knowledge poisoning attack where the poisoned image itself is the attacker-controlled payload, without manipulating captions, summaries, metadata, or other associated text. Specifically, this attack is instantiated through an automated multi-agent method that constructs visually plausible poisoned images. To assess its impact, we evaluate Vis-Poison across two representative multimodal RAG pipelines, four embedding models, and six generation models. Empirically, Vis-Poison achieves an end-to-end attack success rate of 40.16\% to 65.40\% against 30k-entry multimodal knowledge bases in \emph{black-box} settings. Moreover, Vis-Poison remains effective a

---

### [24] Designing a Robust LLM-Based Evaluation System for Agentic AI in Drug Discovery Through Human Alignment

**链接**: https://arxiv.org/abs/2608.21057
**作者**: Emma Granqvist, Roc\'io Mercado, Samuel Genheden
**来源**: cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Agentic large language model (LLM) systems are reshaping scientific workflows in chemistry and drug discovery, but evaluating their open-ended, tool-augmented outputs remains a fundamental bottleneck. Reference-based metrics such as BLEU and ROUGE fail to capture semantic correctness, while expert human evaluation does not scale to the iteration speed these systems demand. The LLM-as-a-Judge paradigm has emerged as a scalable alternative, but existing drug discovery benchmarks deploy LLM judges without validating their alignment with human experts. In this work, we present an LLM-as-a-Judge evaluation framework for ChatInvent, an agentic drug discovery assistant deployed at AstraZeneca, with four contributions. First, we define four output-quality evaluation dimensions---Completeness, Relevancy, Structural Clarity, and Scope Adherence---alongside deterministic Tool Call Correctness checks. Second, we validate the judge through a human alignment study with five expert annotators, compar

---

### [25] Which Eviction Policy Should an LLM Cache Use? A Systematic Study Across Workloads, Capacities, and Encoders

**链接**: https://arxiv.org/abs/2608.20280
**作者**: Yash Kulkarni, Shubham Harkare, Arvind Yogesh Suresh Babu
**来源**: cs.DB cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [26] Forgetting to Forget: Attention Sink as A Gateway for Backdooring LLM Unlearning

**链接**: https://arxiv.org/abs/2510.17021
**作者**: Bingqi Shang, Yiwei Chen, Yihua Zhang, Bingquan Shen, Sijia Liu
**来源**: cs.LG cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [27] ExpertIVS: Sociological Expert Driven Individual Value Simulation in Large Language Models

**链接**: https://arxiv.org/abs/2608.20355
**作者**: Zhen Wang, Yuqi Ren, Yuehan Cui, Hongxiang Wang, Jianxiang Peng, Zhaoxia Zhang 等 (10 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Model (LLM) agents have demonstrated considerable potential for social simulation, yet struggle to accurately model individual value systems. Most existing methods mechanically stitch survey responses into prompts, which suffer from semantic fragmentation, failing to capture the internal coherence of human value systems. The value systems of LLMs are typically assessed using static multiple-choice questions, which fail to evaluate the value orientation in real-world dialogue interactions. To address these issues, we propose ExpertIVS, a framework employing 14 Sociological Expert Agents to interpret World Values Survey (WVS) responses through structured professional perspectives, rather than direct responses concatenation. These expert agents perform deep semantic reconstruction to generate robust and internally consistent individual profiles. To evaluate the consistency between LLMs and individual value systems during dynamic interactions, we further introduce a multi-ag

---

### [28] When Calibration Depends on the Scoring Rule: Quantized Biomedical LLM Classification

**链接**: https://arxiv.org/abs/2608.03854
**作者**: Anton Rasmussen, Hong Qin
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [29] Action-Aligned Retrieval with Pairwise Multimodal Reranking for Text-Based Person Anomaly Search

**链接**: https://arxiv.org/abs/2608.23503
**作者**: Thanh-Khoi Nguyen, Thanh-Nhan Vo, Trong-Thuan Nguyen, Minh-Triet Tran
**来源**: cs.CV
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Text-based person anomaly search requires distinguishing individuals based on fine-grained, context-dependent behaviors rather than mere appearance. Existing methods struggle to capture these context-conditioned actions, frequently relying on isolated skeletal geometry, discarding raw query details during reformulation, or utilizing absolute pointwise scoring for multimodal verification. To address these limitations, we propose \textbf{ActPair}, a unified three-stage coarse-to-fine framework that combines action-aligned retrieval with pairwise multimodal reranking to bridge the pose-semantic gap. First, we fine-tune a vision-language model (VLM) with an action-aligned multi-task objective that encourages the representations to encode action-discriminative semantics. Second, we perform parallel late-fusion retrieval using the original query and a large language model (LLM)-generated context-grounded rewrite, retaining complementary details from both semantic views. Finally, we propose a

---

### [30] Don't Solve, Just Compare: Tiny Advisors for Runtime Intervention in LLM Agents

**链接**: https://arxiv.org/abs/2608.21027
**作者**: Yanze Jiang, Mingxuan Li, Yuhao Wang, Shengfang Zhai, Jiaheng Zhang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents are emerging as an important paradigm for real-world tasks that require reasoning, tool use, and sequential decision-making. As these agents operate over longer horizons, runtime intervention offers a way to improve reliability without retraining the underlying actor. Failure detection alone is insufficient. Effective intervention must also provide a useful direction for recovery. Existing approaches often rely on an expert solver or a critic that generates task-specific corrections, incurring either the cost of another capable solver or the capacity demands of a task-capable critic. We introduce Comparison-Only Tiny Advisor (COTA), a comparison-only framework for constructive runtime intervention. In COTA, a tiny comparator judges whether sampled alternatives lead to better continuations than the actor's proposal, and repeated comparisons determine when intervention is warranted. We train the comparator using pairwise supervision constructed from same-prefix counterfactual 

---

### [31] Hallucination-Aware Hierarchical LLM for Autonomous UAV Mobility Control: A Safe Reinforcement Learning Approach

**链接**: https://scholar.google.com/scholar_url?url=https://ieeexplore.ieee.org/abstract/document/11661380/&hl=zh-CN&sa=X&d=17251528144251542290&ei=FduMaq_cKsy56rQPl--66AI&scisig=AIVdB-wunuGa2xx5x9afMPaH6_-j&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=6&folt=kw-top
**作者**: H Ahn, S Oh, GS Kim, S Park, S Jung, J Kim - IEEE Transactions on Networking 等 (7 人)
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> This paper proposes SafeGPT, a hierarchical framework that integrates generative pretrained transformer (GPT)-based large language models ( LLM ) with safe reinforcement learning (safe-RL). SafeGPT addresses the large-scale random multi-point

---

### [32] TH-GNN: Heterogeneous Temporal Graph Neural Networks for LLM-Agent Shilling Attack Detection

**链接**: https://arxiv.org/abs/2608.20376
**作者**: Shivam Swarup, Divya Prakash Shrivastava, Rakesh Thakur
**来源**: cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents can now generate realistic shilling profiles, fluent reviews, and coherent ratings at scale, systematically defeating recommender-system defenses. Text-only detectors that flag semantic drift in review embeddings are blind to graph structure and temporal coordination, while graph-only detectors that exploit neighborhood anomalies cannot reason over review semantics or the cross-modal inconsistencies produced by LLM-generated content. We propose TH-GNN, a heterogeneous temporal graph neural network with a two-layer Heterogeneous Graph Transformer backbone that applies per-type and per-relation attention augmented with learnable sinusoidal temporal encodings on every edge. Cross-modal attention fuses structural user embeddings with frozen RoBERTa representations of reviews and item descriptions, while a GRU operating over log inter-arrival times captures temporal burstiness. Evaluated across five attack families and four benchmark datasets, TH-GNN achieves a grand-mean F1 scor

---

### [33] There Is No Neutral Harness: Modern LLM Leaderboards Are Manufactured by Config-Fragile Items

**链接**: https://arxiv.org/abs/2608.21382
**作者**: V.S. Raghu Parupudi
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multiple-choice benchmarks fix the questions and the correct answers, but not the harness: the order of the options, the wording of the prompt, and whether a language model's answer is read from generated text or from per-option likelihoods. Work on this harness sensitivity reports it as aggregate score variance, leaving unexamined which items the variance falls on and whether they are the items that separate one model from the next. We treat the evaluation harness of large language models (LLMs) as an independent variable and resolve its effect to single items. We introduce the \textit{fragility grid}: 12 open-weight instruction-tuned LLMs from 4 families answer the same 3{,}679 items from 4 benchmarks (ARC, HellaSwag, MMLU, TruthfulQA) under 26 equally defensible harness configurations, recording one correctness bit for every model, item, and configuration. The comparison is matched, since the items, the weights, and the greedy decoding stay fixed while only the harness varies. Under

---

### [34] Beyond End-to-End Success: Diagnosing Failures in Long-Horizon Security LLM Agents

**链接**: https://arxiv.org/abs/2608.20563
**作者**: Wei Shao, Chongzhou Fang, Zuxiong Tan, Zequan Liang, Setareh Rafatirad, Avesta Sasan 等 (7 人)
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-horizon security LLM agents must carry information and decisions across many dependent interactions, where later actions often depend on services, state, or access discovered much earlier. This makes final task success difficult to interpret: an agent may fail before it ever reaches the point where the capability of interest can be exercised. We present a diagnostic methodology that instruments security tasks with checkpoints, separates failures before and after capability exposure, and uses controlled interventions to test suspected upstream bottlenecks. We evaluate the methodology across four task families involving delayed reuse of discovered information, reuse of observed state, recovery from failed strategies, and decision making after uncertain outcomes. On observed state reuse, checkpoint analysis shows that many Gemini 2.5 Flash failures occur before the model observes the state it is later expected to reuse. In a pre-specified 92-seed study, targeted protocol-disambiguati

---

### [35] KSE-Web: An Analysis of Hybrid Retrieval and LLM-Assisted Query Expansion for Low-Resource Khmer Semantic Search

**链接**: https://arxiv.org/abs/2608.21365
**作者**: Nimol Thuon
**来源**: cs.CL cs.AI cs.IR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As a low-resource language, Khmer presents several retrieval challenges, including limited annotated data, ambiguous word boundaries, weak support in multilingual embedding models, and frequent mixed Khmer-English usage. This paper presents KSE-Web, an analysis of hybrid retrieval and LLM-assisted query expansion for Khmer semantic search. We construct the dataset from approximately 17K candidate Khmer titles and retain 3K cleaned full-text Khmer documents after filtering, normalization, deduplication, and document-length control. The dataset includes 300 manually reviewed user-style Khmer search queries and silver relevance labels with partial human verification. We evaluate character n-gram BM25, multilingual dense retrieval, hybrid BM25+dense retrieval, and LLM-assisted query expansion using Qwen2.5 models. Experimental results show that BM25 achieves the strongest overall performance, reaching 0.943 Recall and 0.876 nDCG. Hybrid BM25+dense retrieval performs comparably, achieving 0

---

### [36] PrimeAgentOrchestrator: Memory-Primed Agent Spawning for Personal AI Infrastructure

**链接**: https://arxiv.org/abs/2608.20342
**作者**: Myron Koch (Peak Summit Labs)
**来源**: cs.AI cs.MA
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) coding agents start each session with an empty context window, discarding accumulated knowledge from prior work. We present PrimeAgentOrchestrator (PAO), a system that spawns new instances of Claude Code -- Anthropic's terminal-based coding agent -- pre-loaded with relevant memories compiled from the user's existing personal databases. At spawn time, PAO queries two independently-operated memory backends in parallel (a PostgreSQL entity-observation database and a Cloudflare Worker semantic search index), fuses results using backend-specific retrieval strategies, and delivers the compiled briefing via filesystem injection that exploits the host agent's configuration auto-read behavior. PAO manages the full agent lifecycle including trust pre-seeding, readiness polling with error detection, and adaptive terminal text injection. We report on four months of regular deployment (December 2025 through March 2026) as an experience report, documenting three generation

---

### [37] Explicit Cognitive Allocation: A Principle for Governed and Reviewable LLM -Assisted Inquiry

**链接**: https://scholar.google.com/scholar_url?url=https://ieeexplore.ieee.org/iel8/6287639/6514899/11661318.pdf&hl=zh-CN&sa=X&d=5464300083321210470&ei=FduMaq_cKsy56rQPl--66AI&scisig=AIVdB-wJDeeelmZUQ3gJ8aTCzN6O&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=9&folt=kw-top
**作者**: HM Manzanilla-Granados, Z Navarrete-Cazales… - IEEE Access, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> functions during LLM -… LLM use. It is most relevant to contexts in which documentation, methodological transparency, resource identification, and human oversight are more important than minimal latency or minimal token use. In this study, we compare CUA

---

### [38] Aligned Alone, Misaligned Together: Forecasting Adversarial Capture in LLM Agent Populations

**链接**: https://arxiv.org/abs/2608.22444
**作者**: Isotta Magistrali and Chen Shani
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The unit of AI safety evaluation is still the individual model, yet language-model agents are increasingly deployed in interacting populations that read and write one another's decisions. This raises a question no single-agent audit can answer: an agent that is well-calibrated on its own may still be pulled toward a different decision by the agents around it. We study this on a security-triage task, where populations of language-model monitors decide whether to escalate or dismiss alerts, and into which we can inject a committed minority that always pushes one way. We find that two alerts a single agent judges almost identically on its own can drive collective behavior far apart, so auditing any one member need not reveal what the population will do. Yet that collective behavior can be predicted in advance. From a population's benign, adversary-free operation alone, we calibrate a response function that forecasts, before any attack is run, how far a committed minority will later move i

---

### [39] FL-MAESTRO: Multi-Agent LLM Orchestration for Resource-Constrained Federated Learning

**链接**: https://arxiv.org/abs/2608.20518
**作者**: Jiajun Wu, Zirui Wang, Jiayu Zhou, Qiang Ye, Steve Drew
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In Federated Learning (FL), the communication topology is a runtime variable rather than a fixed design choice, since links and edge devices drop in and out during training. Each round, the server must commit three coupled decisions, namely the communication topology, per-client resource allocation, and the aggregation rule for combining local updates. Recent agentic systems have begun bringing large language models (LLM) into FL, but the existing line of work either operates at setup time or handles a single runtime dimension such as client selection. We propose FL-MAESTRO, a multi-agent orchestrator that makes the joint runtime FL decision directly through three specialist LLM agents, one per decision dimension. A coordinator combines their analyses into a single decision, and a non-LLM feasibility check confirms it before the round executes. Because the orchestrator consumes the server's predicted-failure list, it withholds clients whose updates would never be aggregated, which remo

---

### [40] Benchmarking LLM Serving Systems for Agentic AI Workloads with XPerf

**链接**: https://arxiv.org/abs/2608.20370
**作者**: Michael Wang, Yikang Yue, Shaobo Li, Yirui Eric Zhou, Chen Wang, Jian Huang
**来源**: cs.DC cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We present XPerf, a benchmarking framework that load-tests LLM serving systems with diverse agentic AI workloads. It provides detailed profiling of the serving system and hardware, enabling users to identify performance bottlenecks introduced by agentic workloads. Benchmarking LLM serving systems under agentic workloads is challenging - agentic applications rely on nondeterministic LLM outputs to guide their control flow; therefore, workload patterns vary unpredictably from run to run. XPerf minimizes this workload variation with a fine-grained trace replay approach: it enables users to easily collect traces from real agentic applications, synthesize new workloads with various patterns if needed, and reproducibly replay them on different LLM serving systems. XPerf includes eight agentic applications across diverse use cases (e.g., coding, deep research, and Q&A) by default. Our empirical study using these workloads shows that XPerf accurately replays agentic workloads, provides detaile

---

### [41] Certified Multi-Turn Robustness for LLM Safety via Compositional Bounds and Safety Persistence

**链接**: https://arxiv.org/abs/2608.20820
**作者**: Yang Liu, Bin Chong, Wenkai Yang, Shuai Zhang, Yancheng Chen, Feiyu Han 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are vulnerable to multi-turn jailbreak attacks that progressively manipulate conversation context. Existing certified robustness methods are limited to single-turn inputs; naive multi-turn composition yields bounds that degrade exponentially in the number of turns. We introduce Multi-Turn Certified Robustness (MTCR), a framework that models conversational safety via State-Adversarial MDPs and defines $k$-turn certified robustness as the worst-case safety probability across $k$ adversarial turns. MTCR comprises: (i) compositional certification via embedding-space mode decomposition, yielding tighter certified lower bounds than naive multiplication; (ii) $(\alpha,\beta)$-safety persistence, improving the degradation rate from $\underline{p}^{k}$ to $\beta^k$ (with $\beta > \underline{p}$) and yielding interpretable horizon estimates; (iii) matching information-theoretic upper bounds establishing tightness; and (iv) a unified algorithm combining these results.

---

### [42] One Polluted Page Is Enough: Evaluating Web Content Pollution in LLM Recommenders

**链接**: https://arxiv.org/abs/2606.13610
**作者**: Minghao Luo, Liang Chen
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [43] Improving O-RADS Risk Stratification from Ultrasound Reports: A Comparative Evaluation of Hybrid versus End-to-End LLM Reasoning Strategies

**链接**: https://arxiv.org/abs/2608.23061
**作者**: Xiaotong Tan, Chunli Qiu, Xin Liu, Qing Huang, Guangli Zhou, Bo Gao 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Background: Automating clinical guideline-based decision-making with large language models (LLMs) remains challenging because of reliability, hallucination, and limited interpretability. We compared the performance of LLMs and reasoning strategies for automated Ovarian-Adnexal Reporting and Data System (O-RADS) classification from free-text pelvic ultrasound reports. Methods: In this retrospective study, consecutive patients with ovarian masses who underwent pelvic ultrasound were included. Eight LLMs were tested with three reasoning strategies: implicit-knowledge end-to-end, rule-informed end-to-end, and a feature-based hybrid architecture that decoupled feature extraction from rule-based classification. The reference standard was O-RADS categorization established by expert consensus. Results: A total of 310 women with 390 ovarian masses were evaluated. The feature-based hybrid architecture using Gemini 3.6 Flash demonstrated the best performance, achieving an accuracy of 99.2% (387 o

---

### [44] Hierarchy-Aware Supervised Uncertainty Estimation for Black-box LLM Taxonomic Reasoning

**链接**: https://arxiv.org/abs/2608.22839
**作者**: Shuting Xie, Nathaniel Lesperance, Graham W. Taylor
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly used for scientific decision support, yet reliable confidence estimation remains difficult in black-box settings. We study uncertainty estimation for hierarchical taxonomic reasoning generated by a black-box LLM in a long-tailed biodiversity monitoring pipeline. Using proxy features extracted by an open-source tool LLM, we train lightweight supervised estimators with hierarchy-aware supervision to predict rank-wise correctness. Across three tool LLMs, the supervised estimators consistently outperform a token-likelihood baseline for micro discrimination and selective prediction under a single global rejection threshold, improving micro AUROC from 0.57 to 0.75--0.80. The best results are achieved by a rank-specific multi-head design (H3), suggesting that accounting for hierarchical output structure is important when a unified abstention rule is required. Our code is publicly available at https://github.com/uoguelph-mlrg/hierarchy-aware-llm-uq

---

### [45] Every Token Counts: Exact Likert-Scale Distributions for Measuring LLM Attitudes and Biases

**链接**: https://arxiv.org/abs/2608.10503
**作者**: Davood Wadi, Mohsen Ghodrat, Matthew Philp
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [46] Lexical Perturbations Disrupt LLM Reasoning: An Empirical Study of Attention Diversion

**链接**: https://arxiv.org/abs/2608.22140
**作者**: Jiaqian Zhu, Yang Zhang, Junhua Ding, Xiaowei Yu
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) achieve strong reasoning performance, but their robustness to realistic lexical corruption remains poorly understood. We evaluate four open-weight instruction-tuned models and frontier models across four reasoning benchmarks under keyboard noise, character swaps, and filler insertion. Character-level perturbations substantially degrade accuracy, especially on multi-step reasoning tasks, while filler insertion has little effect. We trace this asymmetry to Attention Diversion: lexical corruption fragments subword tokenization, and the resulting fragments attract disproportionate attention mass, concentrated in middle and final transformer layers. Length-matched controls confirm that fragmentation, not prompt length, drives the loss. A factorial intervention then shows why the damage is hard to undo: fragmentation corrupts token content and attention allocation together, and the two are coupled. Restoring clean attention while the content remains corrupted is 

---

### [47] Forgotten in Weights, Recovered by Tools: Agentic Tool Unlearning for LLM Agents

**链接**: https://arxiv.org/abs/2608.21544
**作者**: Baicheng Chen, Zheyuan Liu, Jingyu Zhang, Kaize Ding, Ningshan Ma, Yue Huang 等 (7 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly deployed as tool-augmented agents, where responses can depend on tool calls and external observations rather than model parameters alone. This creates an evaluation mismatch for LLM unlearning: previous unlearning methods may suppress direct parametric recall, but an agent can still recover the same forget target through tools such as web search, retrieval, or database lookup. We identify this failure mode as tool-mediated recovery and study agentic tool unlearning, which aims to reduce both parametric recall and tool-mediated recovery while preserving normal tool use for retained knowledge. To address this challenge, we propose Agentic Tool Unlearning (ATU), a two-stage framework. The first stage applies parametric knowledge unlearning to suppress direct recall, while the second stage performs trajectory-level reinforcement learning in simulated tool-augmented environments to penalize target-seeking tool behavior and final-answer leakage. 

---

### [48] Whitewashing Hate, Smearing Harmless Content: Annotator-Style Rebuttal Attacks on LLM-Based Moderation

**链接**: https://arxiv.org/abs/2608.22230
**作者**: Junyu Lu, Kaiyuan Liu, Jingyi Kang, Deyi Ji, Hailong Zhang, Lanyun Zhu 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly used for hate speech moderation, often within human--AI workflows in which reviewers provide feedback before a final decision. Such feedback introduces two manipulation directions: whitewashing hateful content as normal and smearing normal content as hateful. This study examines the susceptibility of initially correct model judgments to annotator-style rebuttals and analyzes whether attack effectiveness differs across manipulation directions. We introduce a rejudge protocol that extends direct contradiction with decision-boundary perturbations and adversarial rationales. Experiments with multiple LLMs on two hate speech datasets show that annotator-style rebuttals substantially degrade moderation performance, with stronger effects in multi-turn settings. The results further reveal stable, model-specific asymmetries between whitewashing and smearing across attack configurations, indicating distinct directional vulnerability patterns. Explici

---

### [49] AI University: An LLM-Powered Learning Assistant for Engineering---A Finite Element Method Case Study

**链接**: https://arxiv.org/abs/2504.08846
**作者**: Mostafa Faghih Shojaei, Rahul Gulati, Benjamin A. Jasperson, Shangshang Wang, Simone Cimolato, Manas Vardhan 等 (9 人)
**来源**: cs.CY cs.AI cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [50] When Trust Meets Truth: Trust-Truth Separability in LLM-as-Judge

**链接**: https://arxiv.org/abs/2608.21097
**作者**: Xin Sun, Di Wu, Yuchen Guo, Jiahuan Pei, Isao Echizen, Abdallah El Ali 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-as-Judge systems can produce multi-dimensional evaluations, such as trustworthiness, reliability, and factuality, and these outputs are often interpreted as independent evidence. We test this assumption for a common pair of judgments: trust scoring and binary truth classification. On correctness-controlled QA, LLM judges align trust scores with truth verdicts more tightly than human behavioral reference, suggesting weaker separations between trust and truth judgment. We then apply stress tests by changing only source cues of identical QA between Human and AI. Source attribution shifts not only trust scores but also truth verdicts and logit-derived correct-side probabilities. Results show that current LLM-as-Judge protocols should not treat trust scores as independent evidence for truth judgments.

---

### [51] Calibrating Criterion Revision in LLM Agents: Failure Modes and a Trace-Anchored Protocol

**链接**: https://arxiv.org/abs/2608.20729
**作者**: Guodong Xu
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Language-model agents can improve after failure or carry text across episodes without revising what counts as success. We study the narrower attribution problem of criterion revision: when criterion K0 accepts an outcome violating a broader commitment B, what observations justify saying that the system formed and persistently used K1? We require five non-compensatory conditions: criterion-failure detection, a model-emitted proposal, new-episode transfer, intervention sensitivity on the claimed carrier, and preservation. We evaluate CMB-0.1 on twelve cross-domain cases and four arms: stateless inference, append-only history, model-generated but harness-committed state, and evaluator-written oracle state. Seven mechanism fixtures yield 84 deterministic scorer trials; four local quantized artifacts yield 96 calls and 192 model-case-arm trials. No model trial satisfies all five conditions, but this zero does not establish general capability absence. Eleven calls remain invalid after one re

---

### [52] Supporting The Many Lives of Personal Data with Rebite: LLM-Powered Goal-Directed Framing in Food Journaling

**链接**: https://arxiv.org/abs/2608.21289
**作者**: Weijun Li, Daniel A. Epstein
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> People's health and tracking goals frequently change, but most personal informatics systems struggle to adapt, leading people to abandon their data and start over. We propose goal-directed framing, an approach that repositions goals within personal informatics systems. Instead of fixing the meaning of data at capture time, the approach frames the collected data through the current goal and reframes it whenever the goal changes. We realize this in Rebite, a photo-based food journaling system that uses LLMs to read unstructured meal photos and produce goal-directed feedback. In a one-week deployment with 21 participants managing multiple dietary goals, we find that goal-directed framing shaped how participants engaged with their goals. Translating a goal into metrics helped them see what it meant in practice, confirming existing priorities, surfacing what they overlooked, and revealing where the metrics fell short. When goals changed, seeing past meals reframed under the new goal exposed

---

### [53] Revisiting the Effectiveness of LLM Pruning for Test-Time Scaling

**链接**: https://arxiv.org/abs/2604.25098
**作者**: Ocean Monjur, Shahriar Kabir Nahin, Anshuman Chhabra
**来源**: cs.AI cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [54] The Dual Nature of LLM Persona: Aggregated Tendencies and Frame-Dependent Geometry

**链接**: https://arxiv.org/abs/2607.02368
**作者**: Yuan Yuan
**来源**: stat.ML cs.AI cs.LG math.DG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [55] MemGuard: Persisting Verifier Signals for LLM-Agent Memory Governance

**链接**: https://arxiv.org/abs/2608.21867
**作者**: Haoyu Wang, Guangyuan Dong, He Liang, Zijing Zhang, Jiachen Luo, Chuang Liu 等 (8 人)
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents are moving from single-prompt use to long task streams in which reusable memory becomes a core capability for terminal, software-engineering, and web tasks. Such memory is useful only when stored experience remains reliable across hundreds of interactions, but two failure modes break that assumption in practice. The first is unreliable admission: failed trajectories,accidental successes, and misleading observations enter memory because they appear relevant, then mislead later decisions. The second is memory drift: long-running banks accumulate duplicate, stale, and conflicting records that retrieval alone cannot repair. MemGuard's key distinction is to treat verifier output not as a one-shot filter, but as persistent lifecycle metadata. It converts multi-criteria score-token verification into reward, confidence, label, and uncertainty descriptors that are attached to every candidate before activation and reused during retrieval, conflict resolution, summarization, and archiv

---

### [56] Beyond aggregated labels: Personalized reader emotion prediction via LLM -based persona reasoning

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S0925231226022770&hl=zh-CN&sa=X&d=12576395658610950252&ei=FduMaq_cKsy56rQPl--66AI&scisig=AIVdB-y2VBfZSb4hZsWxiMbljxXQ&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=2&folt=kw-top
**作者**: K Ding, Y Huang, T Wu, H Gao, Q Wang, R Xu - Neurocomputing 等 (7 人)
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> paradigm: a Teacher LLM first synthesizes target-conditioned persona descriptions as pseudo-rationales, and a Student LLM is then fine-… Further analyses reveal both the usefulness and the limitations of LLM -derived personas

---

### [57] One Request, Multiple Experts: LLM Orchestrates Domain Specific Models via Adaptive Task Routing

**链接**: https://arxiv.org/abs/2511.12484
**作者**: Xu Yang, Chenhui Lin, Haotian Liu, Qi Wang, Yue Yang, Wenchuan Wu
**来源**: eess.SY cs.AI cs.SY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [58] Right-Sizing LLM-Agent Decomposition in VAT Determination: A Pilot Controlled Sweep

**链接**: https://arxiv.org/abs/2608.23395
**作者**: Pedro Santos
**来源**: cs.MA cs.AI cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent LLM-agent systems make conflicting design bets: decompose work across many narrow agents, or use one strong tool-using agent. This pilot studies that choice on bounded cross-border VAT determination with reverse charge, where every case has an oracle label and each intermediate decision is independently scoreable. We hold the activity surface fixed (subtasks, tools, I/O schemas, validation checks, orchestrator, base model, and merge policy) and vary only the assignment of subtasks to workers across four orchestrated configurations, from one wide worker to five narrow ones, against S0, a tuned no-orchestrator single agent, with a deterministic rule engine as oracle. The program spans 4,400 runs: a 40-case, five-repeat main sweep, matched-token arms separating prompt-budget from agent-count effects, and three failure-injection arms, all judged against pre-registered falsification criteria. The two intermediate configurations lead on accuracy (0.830, against endpoints at 0.720 and 

---

### [59] Activation-Weighted Seeded Residual Coding for Low-Bit LLM Weight Repair

**链接**: https://arxiv.org/abs/2608.23144
**作者**: Zehao Liu, Chuangchuang Fang, Yang Ren
**来源**: cs.LG cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Low-bit weight quantization saves storage but leaves errors that degrade language-model quality. We introduce Activation-Weighted Seeded Residual Coding (AWSRC), a compact repair codec for an existing quantization backbone. Given a reconstructed weight $W_0$, AWSRC encodes the residual $W-W_0$ using deterministic seed-generated bases. The sidecar stores seed selectors, low-bit coefficients, and scales rather than an explicit codebook. Activation statistics prioritize errors that affect layer outputs. On Qwen2.5-3B-Instruct, adding 0.162 scope-bits/weight to an INT4 RTN backbone closes 88.2%, 78.9%, and 71.3% of the matched PPL, KL, and accuracy gaps to BF16. Repairing a matched strong low-bit backbone also improves all measured quality metrics. With a matched 49.25 MB sidecar, about 0.8% of the BF16 model-weight payload, AWSRC gives the best perplexity and mean task accuracy among sparse, low-rank, and vector-quantized codecs.

---

### [60] ChemDIRT: A Diversified Instruction, Representation, and Task Benchmark for Robust Chemistry-LLM Evaluation

**链接**: https://arxiv.org/abs/2608.21504
**作者**: Eric Inae, Tim Gunn, Chris Bond, Meng Jiang
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The rapid advancement of large language models (LLMs) has led to increasing interest in their application to scientific domains such as chemistry. However, existing chemistry benchmarks often provide only a narrow view of model capability, focusing on limited task sets while overlooking robustness to variations in problem formulation and chemical representation. As a result, reported performance may overestimate a model's true ability to reason consistently across realistic settings. To address this challenge, we introduce ChemDIRT (Diversified Instruction, Representation, and Task Benchmark), a comprehensive evaluation framework designed to assess the robustness of chemical reasoning in LLMs. ChemDIRT systematically measures model performance across variations in instructions and molecular representations while spanning eight categories of chemistry tasks. By evaluating both accuracy and consistency under these controlled perturbations, ChemDIRT provides a more reliable assessment of 

---

### [61] Share the Judge, Learn the Deferral: Where Specialization Helps LLM Evaluation

**链接**: https://arxiv.org/abs/2607.27984
**作者**: Ye Chen, Weining Zhang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [62] Disentangling Threads: Exploring the Potential of LLM-Supported Discussion Forum Analysis for Community Insight

**链接**: https://arxiv.org/abs/2608.20591
**作者**: Tony W. Li, Zhiqing Wang, Thanh-Nha Tran, Yu-Chun Grace Yen, Steven P. Dow
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Online discussion forums enable people from diverse backgrounds to share ideas, feedback, and perspectives. These organic discussions can help researchers understand communities' collective viewpoints, but insights are often difficult to uncover given their freeform reply structure. Large language models (LLMs) support qualitative text analysis but can misalign with researchers' analytical intent and miss key insights. To inform design considerations for forum sensemaking tools, we manually analyzed a forum discussion, synthesized an exploratory analysis framework from relevant literature, built a design probe, and interviewed 21 researchers to uncover perceived opportunities and barriers with LLM representations of collective discussions. We provide recommendations for community sensemaking tools to support flexible analytical goals grounded in raw user data and enable follow-up research processes, while balancing anonymous free expression with the desire for contextual information on

---

### [63] Mobility tokens with routine-aware learning for LLM -based human mobility prediction

**链接**: https://scholar.google.com/scholar_url?url=https://link.springer.com/article/10.1007/s10707-026-00589-9&hl=zh-CN&sa=X&d=6862768131729911746&ei=FduMaq_cKsy56rQPl--66AI&scisig=AIVdB-yPQgAItOq7OAP19SdtGrLV&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=4&folt=kw-top
**作者**: C Wang, Q Ge, N Hu, S Zhou, L Chen - GeoInformatica, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> ), an LLM -based … LLM -based baselines under the GEO-BLEU metric, improving the mean score over the strongest baseline by 5.82%. Owing to its compact mobility-token serialization, MoRAL also achieves a 2.6 times reduction in per-user inference time

---

### [64] Complete Cyclic Subtask Graphs for Tool-Using LLM Agents: Flexibility, Cost, and Bottlenecks in Long-Horizon Workflows

**链接**: https://arxiv.org/abs/2604.22820
**作者**: Luay Gharzeddine and Samer Saab Jr
**来源**: cs.MA cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [65] InjecMEM: Memory Injection Attack on LLM Agent Memory Systems

**链接**: https://arxiv.org/abs/2608.23471
**作者**: Hanling Tian, Gengyu Zhang, Zeyang Sha, Jingying Wang, Yuhang Liu, Zhehao Huang 等 (8 人)
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Memory is becoming a default subsystem in deployed LLM agents to provide persistent personalization and continuity. This naturally prompts a question: will memory system introduce new vulnerabilities into agents? Thus we propose InjecMEM, a novel memory injection attack paradigm that requires only a single interaction (no read/edit access to memory store) to steer later responses of related queries toward a pre-specified output. Guided by the retrieval-then-generate mechanism of memory systems, we craft the injection with a retriever-agnostic anchor and an adversarial command. The anchor contains high-recall topical cues so that downstream retrieval consistently associates the record with the target topic. The command is a short sequence optimized to remain effective under uncertain fused contexts, variable placements, and long prompts so that it reliably steers outputs once retrieved. We learn the command via gradient-based coordinate search, averaging over synthetic prompt templates 

---

### [66] The LLM Conjuncture: Genres in Flux and Progenitors of the Next Wave

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S259012302603416X&hl=zh-CN&sa=X&d=1042206760472999288&ei=FduMaq_cKsy56rQPl--66AI&scisig=AIVdB-ycYrwK2fHVLZQYEJaDrcUq&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=0&folt=kw-top
**作者**: Y Wei, Y Wang, X Liu, J Watada, JS Pan - Results in Engineering, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> required to illuminate technical directions amid the rapidly expanding LLM landscape. Motivated by this, we systematically surveyed … Guided by the marginal-gain principle, we map every major LLM family to the driver that chiefly produces its next

---

### [67] Text-ADBench: Text Anomaly Detection Benchmark Based on LLM Embeddings

**链接**: https://arxiv.org/abs/2507.12295
**作者**: Feng Xiao, Jicong Fan
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [68] Safety Training May Persist Through Helpfulness Optimization in LLM Agents

**链接**: https://arxiv.org/abs/2603.02229
**作者**: Benjamin Plaut
**来源**: cs.LG cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [69] Minimal Local Simulation Foundations for LLM- and VLM-Driven Agents in 2D and 3D Environments

**链接**: https://arxiv.org/abs/2608.22833
**作者**: Ryuki Hyodo
**来源**: cs.MA cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) and vision-language models (VLMs) are expanding the range of behaviors that can be represented in agent-based simulations, but many contemporary platforms are difficult to study, modify, or run on ordinary computers. We present two intentionally minimal simulation foundations for education and rapid prototyping. SD-AgentFoundry-2D provides a two-dimensional multi-agent environment in which locally hosted LLM agents move, communicate, respond to place occupancy, and encounter spatially localized fire events. SD-AgentFoundry-3D provides a three-dimensional digital-twin environment in which a locally hosted VLM receives first-person images and produces natural-language movement instructions. Both codebases are designed to run locally on macOS, Windows, and Linux and are deliberately left open to modification rather than developed as finished applications. Together, they offer accessible starting points for learning about generative social simulation and for bu

---

### [70] Agentic-SQL Revisited: Autonomy-Based Taxonomy and Empirical Benchmark Analysis for LLM Text-to-SQL

**链接**: https://arxiv.org/abs/2608.15389
**作者**: Yiyun Su, Zujun Peng, Yu Tian, Yuting Liu, Changruo Zhao, Huiying Zhu 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [71] Beyond Benchmarks: LLM Evaluation with an Anthropomorphic and Lifecycle-oriented Roadmap

**链接**: https://arxiv.org/abs/2508.18646
**作者**: Jun Wang, Ninglun Gu, Kailai Zhang, Pengyong Li, Yelun Bao, Jin Yang 等 (10 人)
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [72] Task-Driven 3D Printability Assistance via Geometry- and Knowledge-Grounded LLM Reasoning

**链接**: https://arxiv.org/abs/2608.22128
**作者**: Zhaoda Du, Qiaojie Zheng, Xiaoli Zhang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Printability assessment in additive manufacturing is typically conducted at the geometry level before printing to determine whether a computer-aided design (CAD) model or stereolithography (STL) file can be successfully fabricated. Task suitability, in contrast, is usually evaluated after printing to determine whether the fabricated part satisfies the requirements of its intended use. As a result, for non-expert users to print functional parts, unsuitable material or process choices may only be identified after fabrication, leading to repeated printing, material waste, and user frustration. To address this challenge, this paper leverages the reasoning and language-understanding capabilities of large language models (LLMs), while grounding the reasoning with geometry evidence and structured material/printer knowledge to generate reliable pre-print recommendations. Given a stereolithography (STL) model and a natural-language task description, the framework generates a structured recommen

---

### [73] ProofJudge: Tool-Grounded LLM Evaluation of Formal Proof Quality in Mathlib

**链接**: https://arxiv.org/abs/2608.20432
**作者**: Shane Caldwell
**来源**: cs.LO cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Formal proofs in Lean 4 that pass the kernel's type checker can nonetheless vary widely in quality. We introduce ProofJudge, an agentic LLM-as-judge system that scores formal proof quality along five dimensions beyond correctness: library leverage, automation fit, structural clarity, statement quality, and Mathlib conventions. We evaluate ProofJudge on a novel dataset of 218 declarations drawn from distinct Mathlib PRs. The judge agent is grounded by tool access to the commit the PR is applied to, enabling it to query the library state when scoring. A judge is considered aligned with human preferences when it rates the version of the PR Mathlib accepted above the initial version that was sent back for revision. All six judge models evaluated recover the reviewers' preference well above chance, from 80.8% to 63.5%, and two open-weight judges reach roughly 70% at a tenth of the best judge's cost. We release the judge harness, evaluation dataset, and evaluation traces as open-source artif

---

### [74] Profiling What Matters: Context-Aware Item Profiles from Large-Scale Metadata for LLM Recommenders

**链接**: https://arxiv.org/abs/2608.20801
**作者**: Dojun Hwang, Seunghan Lee, Cheonyoung Park, Sara Yu, SeongKu Kang
**来源**: cs.IR cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> While Large Language Models (LLMs) have significantly advanced reranking in recommendation, effectively leveraging item-side information remains challenging. Real-world items are described by vast, heterogeneous, and unstructured metadata, where decision-relevant signals are often implicit, noisy, or buried in long descriptions. Moreover, feature salience is highly context-dependent, varying not only across items but also across users. Existing methods often rely on item titles, fixed attributes, or static item summaries, which limit personalized and fine-grained item understanding. To bridge this gap, we propose CAIRO, a user context-aware item profiling framework for LLM-based reranking. CAIRO first structures raw metadata and reviews into objective features and subjective traits, and employs a lightweight profiler to select the most relevant information for each user-item pair with limited serving-time overhead. The resulting profiles are concise and context-specific, providing rele

---

### [75] Specification Portability Across LLM Development Agents: Cross-Agent Compatibility in Specification-Driven Software Migration

**链接**: https://arxiv.org/abs/2608.21208
**作者**: Oleg Grynets, Oleksii Ilchuk, Dariia Zatulna, Vasyl Lyashkevych
**来源**: cs.SE cs.AI cs.LO
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> This paper investigates cross-agent specification portability using Oracle-to-PostgreSQL migration as a controlled software transformation task. The study combines two experimental stages. First, a specification-first migration pipeline was evaluated on 1,006 PL/SQL files, of which 623 were successfully regenerated and 380 generated scripts executed successfully in PostgreSQL 16. Second, cross-agent experiments were conducted on a dataset of 1,802 Oracle scripts with corresponding PostgreSQL implementations using Amazon Kiro, Google Gemini, and GitHub Copilot, with Claude Code and Cursor included in the initial single-agent evaluation. Native and foreign specifications were assessed using Token F1, exact match, SQL syntax validity, AST exact match, AST mean similarity, and immediate runnability. The results show that specification size alone does not predict implementation quality and that cross-agent transfer can produce substantial agent-dependent degradation. The strongest replicate

---

### [76] Benchmarking Retrieval-Augmented Generation Strategies for Large Language Model-Based Travel Mode Choice Prediction

**链接**: https://arxiv.org/abs/2508.17527
**作者**: Yiming Xu, Junfeng Jiao
**来源**: cs.AI cs.CY cs.LG
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [77] MACD: Multi-Agent Clinical Diagnosis with Self-Learned Knowledge for LLM

**链接**: https://arxiv.org/abs/2509.20067
**作者**: Wenliang Li, Rui Yan, Xu Zhang, Li Chen, Hongji Zhu, Jing Zhao 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [78] Using Human-LLM Disagreement to Improve Checklist-Based Quality Appraisal

**链接**: https://arxiv.org/abs/2608.20385
**作者**: Timo van der Kuil (1), Bruno Messina Coimbra (1), Mirjam van Zuiden (2), Robert A. Bagheri (1), Rens van de Schoot (1), Klaas Dieleman (1) 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Systematic reviews rely on quality appraisal of included studies, a process that is time-consuming and sensitive to ambiguity in checklist criteria. Although large language models (LLMs) offer opportunities to support these tasks, appraisal checklists are typically treated as fixed inputs, and it remains unclear how their design affects agreement with expert judgments. Therefore, we investigate (1) whether LLMs can approximate human judgments in checklist-based appraisal and (2) whether patterns of human-LLM disagreement can be used to identify and improve ambiguous checklist items. Using the Guidelines for Reporting on Latent Trajectory Studies (GRoLTS) checklist, we compare LLM-generated assessments with expert annotations across three research topics and two checklist versions. Agreement is assessed using item-level accuracy, chance-corrected agreement, and preservation of study-level rank ordering. We find that performance varies substantially across checklist items, with ambiguous

---

### [79] The Retriever Should Remember: Experience-Amortized Reranking for Long-Term Agent Memory

**链接**: https://arxiv.org/abs/2608.22767
**作者**: Qi Feng, Chris Ding, Jicong Fan
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-term language-model agents accumulate memories across interactions, but their retrievers typically do not accumulate retrieval experience. Semantic retrieval is efficient, but embedding similarity does not always reflect whether a memory contains evidence relevant to the current query. Large language model (LLM) rerankers provide stronger query-conditioned relevance scores, yet stateless reranking repeatedly scores a large candidate pool and discards these scores after each query. We introduce EARM, an experience-amortized reranking framework that treats previously acquired LLM relevance scores as reusable retrieval experience. EARM stores sparse query--memory relevance scores in an online matrix, learns their shared structure through causal matrix completion, and combines a small set of newly observed scores with estimated scores to rerank the remaining candidates. The scoring budget decreases as experience accumulates, changing LLM reranking from a repeated per-query expense int

---

### [80] Trustworthy RAG: An Evaluation Agent for Detecting Misinformation and Knowledge Poisoning in Generative AI Systems

**链接**: https://arxiv.org/abs/2608.21095
**作者**: Balkrishna Giri, Md Toufique Hasan, Jussi Rasku, Muhammad Waseem, and Pekka Abrahamsson
**来源**: cs.SE cs.AI cs.CL cs.CR cs.IR
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Retrieval-Augmented Generation (RAG) grounds Large Language Model (LLM) outputs in external knowledge, but RAG systems usually trust whatever they retrieve, creating a Security-Reliability Gap: high semantic relevance does not guarantee factual truth. Adversaries exploit this through knowledge poisoning, inserting malicious documents to cause targeted misinformation. We propose an Evaluation Agent, middleware that combines Natural Language Inference (NLI) factual verification, a five-signal poison detector with relevance-weighted aggregation, and a Trust Index T = 0.4 F + 0.35 C + 0.25 (1 - P ) with a non-linear dampener for high-contamination contexts. On TruthfulQA with Llama 3.3 70B, the agent reaches 91% accuracy and 100% precision, with 100% recall on instruction injection, while in-place edits, such as entity swaps, remain hard to detect. Across three LLMs the Trust Index stays discriminative, with a Receiver Operating Characteristic Area Under the Curve (ROC-AUC) of 0.73 to 0.81

---

### [81] NoTB: Oracle-Free Triage of LLM-Generated RTL via Cross-Model Formal Consensus

**链接**: https://arxiv.org/abs/2608.21962
**作者**: Elisavet Lydia Alvanaki, Je Yang, Biruk Seyoum, Luca P. Carloni
**来源**: cs.AR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly used to generate register-transfer-level (RTL) designs from natural-language specifications. However, assessing functional correctness at early stages remains a fundamental challenge. Existing oracle-free approaches rely either on simulation-based agreement, which depends on LLM-generated testbenches that can fail or vary across models, or on LLM-as-a-judge heuristics, which produce inconsistent predictions. We introduce NoTB, an oracle-free triage framework that infers correctness from cross-model formal consensus. NoTB generates RTL implementations from multiple independently trained LLM families and applies Sequential Equivalence Checking (SEC) to identify designs that are provably equivalent. We show that the diversity of model families within an SEC-equivalent cluster induces a calibrated correctness signal, enabling risk-coverage tradeoffs without requiring testbenches. On 78 CVDP RTL-generation tasks, four-family formal consensus ach

---

### [82] TRACE: A Self-Evolving Skill Bank for Consistent, Limit-Aware LLM Agents

**链接**: https://arxiv.org/abs/2608.22793
**作者**: Wenhao Wu, Menghao Zhang, Xin Wang, Zhi Wang, Kun Shao, Jian Luan
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reliable deployment of LLM agents in user-facing products depends not on raw task-solving ability but on consistency and limit-awareness: behaving the same way across repeated trials, and recognizing when a request cannot, or cannot yet, be safely fulfilled. CAR-bench exposes this reliability gap in the domain of in-car assistants: an LLM-simulated user issues incomplete or ambiguous requests, requiring the agent to resolve uncertainty through multi-turn dialogue and tool use while strictly adhering to domain policies. Even frontier models show a substantial gap between what they can solve at least once (Pass@3) and what they solve consistently across trials (Pass^k). We bridge this gap with TRACE (TRAjectory-Contrastive Evolution), which iteratively improves a skill-based agent's behavioral knowledge without modifying model weights. This knowledge is organized as a Skill Bank of modular, retrievable skills, each encoding a self-contained set of tool-use rules and behavioral guidelines

---

### [83] Vibe Coding on Trial: Operating Characteristics of Unanimous LLM Juries

**链接**: https://arxiv.org/abs/2602.18492
**作者**: Muhammad Aziz Ullah and Abdul Serwadda
**来源**: cs.DB cs.AI cs.CL cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [84] Kernel Token Contradiction: a Fast and Principled Approach for LLM Claim Uncertainty Quantification

**链接**: https://arxiv.org/abs/2608.22506
**作者**: J\'er\'emie Dentan, Alexi Canesse, Mahammed El Sharkawy, Sonia Vanier
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Claim-level Uncertainty Quantification (UQ) aims to mitigate the lack of reliability of Large Language Models (LLMs) by evaluating the factuality of each claim in their outputs. We introduce Kernel Token Contradiction (KTC), a lightweight approach to compute claim-level UQ under realistic white-box conditions. KTC represents the candidate tokens involved in LLM generation as a positive semi-definite kernel that integrates both the LLM's conditional distribution and a token contradiction score. We then use the Von Neumann entropy to quantify the uncertainty of this kernel. To estimate token contradiction, we develop a new approach based on frequency statistics from the Wikipedia corpus. Although CPU-only, our approach achieves over an 8.2x speedup compared to state-of-the-art GPU-accelerated methods based on cross-encoders, and over a 65x speedup compared to CPU-only methods with comparable performance. Our evaluation spans two benchmarks across four European languages and 16 different 

---

### [85] Auditable by Construction: An Ontology-Driven Framework for Trustworthy LLM Analytics in Enterprise Finance

**链接**: https://arxiv.org/abs/2608.20661
**作者**: Sergiy Lunyakin
**来源**: cs.AI cs.CE cs.CL cs.IR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Enterprise adoption of large language models in finance is constrained less by fluency than by trust: in Financial Planning and Analysis (FP&A) and other regulated workflows, an answer is usable only if it is traceable to authoritative sources and auditable after the fact. This paper argues that retrieval-augmented generation for enterprise finance should be evaluated on auditability alongside accuracy, and presents the Knowledge-Driven Analytics Framework (KDAF), which builds ontology-driven knowledge systems through six iterative stages and retrieves evidence via Context-Aware Relevance Propagation (CARP), so that every retrieved fact carries its relationship type, confidence, and source lineage. An evaluation on FinanceBench (145 questions) compares KDAF against zero-context inference, BM25, concept-weighted lexical retrieval, and ungrounded graph traversal. First, retrieval is necessary: zero-context inference reaches 4.1% correctness against 10-12% for retrieval-augmented conditio

---

### [86] SCOPE: A Generative Approach for LLM Prompt Compression

**链接**: https://arxiv.org/abs/2508.15813
**作者**: Tinghui Zhang, Yifan Wang, Daisy Zhe Wang
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [87] The Collaboration Tax: How Much LLM Multi-Agent Systems Pay to Coordinate

**链接**: https://arxiv.org/abs/2608.22152
**作者**: Weixiang Sun, Zehong Wang, Hong Huang, Colby Nelson, Yanfang Ye
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-agent systems built from large language models are deployed widely, yet how much performance is lost when two LLMs must coordinate rather than act alone remains unclear. We formulate the collaboration tax as the team-decentralisation loss of a two-player cooperative game with private information, with two propositions characterising its sign and its equivalence to a max-superadditivity violation. We operationalise this definition on 32 solo-tractable tasks grouped by source of grounding friction and measure it on 11 models from 7 providers. The tax is structured along two no-exception axes: a category ordering across every model and a monotonic decrease with capability. The proximate mechanism is not a reasoning deficit but a four-stage conversational cascade in which agents make ungrounded claims, fail to query the partner, skip integrating both views, and accept the answer without re-derivation. The tax is mechanically predictable from conversation features and partly tractable

---

### [88] ClinicalGPT-R1: Pushing reasoning capability of generalist disease diagnosis with large language model

**链接**: https://arxiv.org/abs/2504.09421
**作者**: Wuyang Lan, Wenzheng Wang, Changwei Ji, Guoxing Yang, Yongbo Zhang, Xiaohong Liu 等 (10 人)
**来源**: cs.CL cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [89] LLM Evaluation on Unseen Questions: Contextual Multidimensional IRT Model

**链接**: https://arxiv.org/abs/2608.22295
**作者**: Ergan Shang, Weijing Tang, Yinqiu He
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Evaluation of large language models (LLMs) increasingly requires predicting how a model will perform on new questions or tasks before collecting large amounts of new annotations. This problem is challenging because question difficulty, scenario, and underlying capability demands can vary substantially. Simple retrospective averages may confound model ability with item characteristics. In this paper, we study a model-based evaluation framework that combines multidimensional item response theory model with question contexts to predict LLM performance on unseen questions. The framework represents LLMs through latent capability profiles while using question content to inform item characteristics, allowing information to transfer beyond previously observed items. Empirically, we find that for within-scenario evaluation, incorporating question embeddings improves prediction relative to model-free baselines, and that multidimensional latent structure provides a richer description of capabilit

---

### [90] FormuEvo: LLM-Guided Evolution for Discovering Solver-Efficient Mixed-Integer Programming Formulations

**链接**: https://arxiv.org/abs/2608.23353
**作者**: Haofeng Yuan, Jianing Peng, Jieyi Bi, Ni Zhang, Shiji Song, Zhiguang Cao
**来源**: cs.CL cs.NE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Mixed-integer programming (MIP) lies at the core of operations research and industrial optimization. While large language models (LLMs) have recently shown promise in automated MIP modeling from natural language, they prioritize semantic correctness but overlook formulation strength, severely bottlenecking the efficiency of downstream solvers. We propose FormuEvo, an LLM-guided evolutionary framework for automated discovery of solver-efficient MIP formulations. FormuEvo frames MIP formulation design as evolutionary optimization over the symbolic space of MIP formulations, represented as executable modeling programs, by iteratively generating, evaluating, and selecting stronger candidates via LLM-driven crossover, mutation, and repair operations. To move beyond blind exploration, FormuEvo introduces a solver-informed diagnosis mechanism that exploits fine-grained solver statistics as verbal gradients for targeted refinement. Additionally, a structured memory abstracts prior experience i

---

### [91] E2LLM: Towards Efficient LLM Serving in Heterogeneous Edge/Fog Environments

**链接**: https://arxiv.org/abs/2606.03770
**作者**: Truong-Thanh Le, Amir Taherkordi, Hoang-Loc La, Frank Eliassen, Phuong Hoai Ha and Peiyuan Guan
**来源**: cs.DC cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [92] Peer-Voted LLM-Agent Stress Tests Find Feed-Induced Lexical Convergence but No Reliable Matched-Exposure Advantage for Distributed Sources

**链接**: https://arxiv.org/abs/2608.20438
**作者**: Rana Muhammad Usman and Dominic Williamson
**来源**: physics.soc-ph cs.AI cs.MA cs.SI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Population-level behavior in large-language-model (LLM) agents cannot be characterized by single-agent benchmarks. We introduce PV-SST, a peer-voted social-platform testbed, and report a separately frozen, preregistered matched-exposure experiment spanning four topics, four unused seeds, four open-weight model families, and three prespecified larger variants. The experiment comprises 448 trials and 112 complete model-by-topic-by-seed blocks. Relative to a topic-only control, a feed of previous-round peer posts ranked by peer-generated likes increases final-round lexical similarity in both the four-family core panel (paired mean difference +0.0082 TF-IDF cosine units, 95% block-bootstrap CI [0.0043, 0.0121], randomization p=0.000105, n=64 blocks) and the three-variant size extension (+0.0109 [0.0069, 0.0151], p=0.000001, n=48). This contrast bundles peer-post exposure with ranking and therefore does not identify a ranking-only effect. Opposite-side survival falls in the core panel (-3.9

---

### [93] Data-Driven Dynamic Algorithm Dispatch with Large Language Models

**链接**: https://arxiv.org/abs/2608.21584
**作者**: Rushil Shah, Emmanuel Lujan, Rabab Alomairy, Alan Edelman
**来源**: cs.AI cs.CE cs.NA math.NA
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We introduce a large language model (LLM)-driven approach for generating dynamic algorithmic dispatch heuristics in high-performance linear algebra. By combining prompt engineering with LLaMA 3 and a curated performance database, the model learns to synthesize selection heuristics that exploit structural patterns to identify fast algorithmic choices. A case study on LU factorization demonstrates the model's ability to replicate expert-designed strategies. This work, developed as part of the DARPA-MIT SmartSolve project, highlights the promise of LLMs for algorithmic discovery and the development of more adaptive, fast linear algebra software.

---

### [94] Beyond Raw Transcripts: Structured Persona Extraction for LLM-Based Digital Twins

**链接**: https://arxiv.org/abs/2608.20344
**作者**: Iris Ye, Tianze Deng, Ozan Candogan
**来源**: cs.CL cs.CY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based "digital twins" aim to simulate how an individual would behavein new environments or respond to novel questions, given some representation of that individual's prior responses. A common approach constructs this representation from survey transcripts or summaries responses. Prior work shows that compressing long transcripts into shorter LLM-generated summaries does not significantly reduce predictive accuracy, suggesting that information volume is not the primary bottleneck. In this work, we argue that the key limitation is instead structural:how persona information is organized before being provided to thesimulator model. We study this by comparing unstructured summaries with structured persona representations. First, we introduce a hand-craftedschema (BDE: Background, Decision procedure, Evaluation), grounded in consumer-behavior theory, and show that it improves predictive accuracy over raw transcripts by +1.91 percentage points on a homogeneous benchmark (Twin-2K-500), wit

---

### [95] Register Shifts Break LLM Safety: A Bengali Benchmark with Culturally Grounded Harms

**链接**: https://arxiv.org/abs/2608.22335
**作者**: Naymul Islam, Nusrat Jahan Lia, Shubhashis Roy Dipta, Sabik Bin Sultan, Abdullah Khan Zehady
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Bengali is the seventh-most-spoken language globally, yet LLM safety evaluation remains overwhelmingly English-centric. We introduce BanglaSafe, a benchmark of 879 Bengali prompts combining 309 natively authored prompts with 570 expert-reviewed prompts, spanning 17 culturally grounded harm categories and five prompting conditions that vary language, writing style, and authority framing. Evaluating 18 frontier LLMs, we find that over half of all responses are unsafe or partially unsafe (53.6%) while 14.7% contains strictly harmful content, and that the strongest observed effect is not the switch from English to Bengali but the choice of writing style within Bengali: the same harmful request phrased as a formal newspaper investigation succeeds 17 percentage points more often than the same request phrased as a casual message, with no adversarial engineering involved. We further show that existing safety classifiers struggle to reliably evaluate Bengali content, with even frontier models f

---

### [96] Beyond the Stability-Exploration Dilemma: Environmental Regularization for LLM Policy Optimization

**链接**: https://arxiv.org/abs/2608.23311
**作者**: Xianlei Zhou, Xiangdi Meng, Yu He, Tianyu Qi, Shuyan Guan, Xianli Zhang 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Policy optimization (PO) for Large Language Models faces a stability--exploration trade-off, currently mediated by an action-side Policy-KL regularizer. This puts practitioners in a double bind: keeping Policy-KL constrains response behavior and consumes the action-side exploration budget, while dropping it leaves the optimization without an explicit drift control. We argue for an alternative that breaks the dilemma by moving regularization to the input side. As training progresses, the distribution over training queries induced by the current policy drifts unchecked from its pre-RL reference distribution. Concretely, Environment-Regularized Policy Optimization (ERPO) introduces a Query-KL (QKL) term that bounds this query distribution shift, together with a dataset-static reference-derived per-query weight that biases each per-query update toward queries typical under the reference. The QKL gradient flows strictly through the query likelihood; the response score function used by polic

---

### [97] HaReCAP: Habitual-action Grounding for Recursive Large Language Model Agents

**链接**: https://arxiv.org/abs/2608.16447
**作者**: Shen Liu, Zhenguo Xu, Shaopu Wang, Yike Gao, Chunlei Wang
**来源**: cs.AI cs.RO
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [98] Knowing but Not Saying: Preventing Factual Access Failures in LLM SFT via Recall-Anchored Distillation

**链接**: https://arxiv.org/abs/2608.20794
**作者**: Haodong Chen, Yadong Wang, Shengtao Wen, Dong Liang, Xiang Chen
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Supervised fine-tuning (SFT) can degrade factual behavior outside the target domain. This degradation is often described as catastrophic forgetting, yet open-ended factual failures do not necessarily imply that the underlying facts have been erased. In this work, we identify a more specific phenomenon, factual access failure: after domain SFT, models can still recognize or rank the correct answer under constrained evaluation, while failing to produce it in closed-book generation. Through benchmark-level comparisons, same-fact multiple-choice and generation probes, and failure-mode analysis, we show that SFT-induced factual degradation reflects both genuine wrong-answer generations and expression-level failures such as verbosity, formatting mismatch, and exact-match artifacts. To address this problem, we introduce Recall-Anchored Distillation (RAD), a base-anchored self-distillation objective that preserves out-of-distribution generation behavior by aligning the adapted model with the o

---

### [99] Proxy reliance in large language model decisions is uncalibrated to predictive evidence

**链接**: https://arxiv.org/abs/2608.22887
**作者**: Zengqing Wu and Chuan Xiao
**来源**: cs.AI cs.CL cs.CY
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are entering decisions in triage and lending, where task-relevant inference must be distinguished from impermissible proxy use. Current audits ask whether decisions change when demographics change. But attributes correlated with a protected group carry predictive value, so a changed decision can be discrimination or sound inference. We measure causal proxy effects in four LLMs on a clinical-ranking task with known ground truth, where the reliance the evidence warrants can be computed exactly and used as the reference. One audit signal yields three verdicts: over-reliance, warranted and under-reliance. Under neutral labels every model relies on proxies with no information. Informative proxies draw all three. Social field names push reliance down, below the reference in one model. Two findings explain this. Reliance severely undertracks the evidence, and social-label suppression is fragile, since in-context examples raise it above zero in every model. Accurac

---

### [100] Agentic Security: A Systematization of Tools, Failure Modes, and Design Laws for LLM-Driven Penetration Testing

**链接**: https://arxiv.org/abs/2608.21423
**作者**: Israt Moyeen Noumi, Tarannum Ahmed Nowshin, Md. Mehedi Hasan Nipu, Mohammad Sakib Mahmood, Md. Jakir Hossain, M. F. Mridha
**来源**: cs.CL cs.AI cs.CR cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Agentic security uses large-language-model (LLM) agents to plan, dispatch, and interpret security tools. As these systems move from demonstrations to deployed products, practitioners repeatedly encounter the same operational failures. We systematize these failures through a hands-on evaluation of ten widely used static, dynamic, cloud, orchestration, and AI red-teaming tools for unattended pipelines. We introduce a four-dimensional Integration Friction Index that separates one-time engineering cost from recurring organisational, legal, and maintenance cost. We then derive quantitative regularities that explain recurring failure modes. Modelling an agentic security system as stochastic LLM policies wrapped by a deterministic mediator, we show that long-lived sessions lose resident evidence with phase count, while short-lived sub-agents extend the usable horizon according to the compression ratio between raw evidence and its summary. We show that a two-stage verdict cascade multiplies sc

---

### [101] Do LLM Recommenders Know When They're Hallucinating? Auditing Confidence Calibration in Catalog Faithfulness

**链接**: https://arxiv.org/abs/2608.10008
**作者**: Srijith Ravikumar
**来源**: cs.IR cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [102] Emergent Misaligned Communication in Long-Horizon Multi-Agent LLM Commerce

**链接**: https://arxiv.org/abs/2608.14825
**作者**: Zeyuan Li, Lukas Petersson, Alessandro Acquisti, Michiel A. Bakker
**来源**: cs.MA cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [103] MileGPO: Milestone Inference with Local Evidence for Graph-Based Policy Optimization of Long-Horizon LLM Agents

**链接**: https://arxiv.org/abs/2608.19803
**作者**: Bo Qian, Yuting Wu, Shuang Zeng, Huaiyu Wan, Dalin Zhang, Jiqiang Liu
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [104] Rank Reversal in Multilingual LLM Judges: A Label-Free Double-Centering Calibrator

**链接**: https://arxiv.org/abs/2608.22432
**作者**: Alhasan Mahmood, Samir Abdaljalil, Hasan Kurban
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multilingual LLM judges produce different evaluator-backbone rankings depending on the prompt language: on an eight-language Agent-as-a-Judge benchmark, the top-ranked backbone alternates across English, Arabic, Chinese, Hindi, Japanese, Spanish, Turkish, and Swahili, and 7 of 15 backbone pairs show statistically significant pairwise rank reversal. We treat this as a measurement problem. The multilingual judge score decomposes additively into task difficulty, backbone skill, and a language-backbone interaction term, the last of which is recoverable without human labels by double-centering the cell-mean score matrix. We make this estimator (\textbf{Consensus-Based Calibration}, CBC) explicit, give an $O(1/\sqrt{n})$ finite-sample concentration bound with variance constant $(1-\tfrac{1}{m})(1-\tfrac{1}{k})$, and show that it is unbiased even when task-language interactions are present. Across 7{,}920 judge runs (6 backbones, 8 languages, 55 tasks, 3 frameworks), CBC raises held-out cross

---

### [105] TailSieve: Partial-Rollout-Guided Tail Routing for LLM Rollouts

**链接**: https://arxiv.org/abs/2608.22788
**作者**: Tianqi Xu, Lu Lv, Haoyang Huang, Wenjie Huang, Zhanming Shen, Yuhao Shen 等 (10 人)
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large-scale rollouts have become a core component of modern LLM systems, spanning reinforcement learning (RL) post-training, on-policy distillation (OPD), and sampling-heavy evaluation pipelines. Unlike online serving, which is typically optimized for request-level latency and throughput, a small number of long-tail generations can dominate the end-to-end makespan of an entire rollout step. In practice, rollout requests are often routed uniformly across replicas, which can place extremely long generations inside high-concurrency decoding batches. To address this, we present TailSieve, a partial-rollout-guided framework that jointly controls tail routing and replica allocation for LLM rollouts. In an idealized setting with known completion lengths, we show that makespan-optimal routing in the long-tail regime combines tail isolation with load balancing, and that a simple top-k policy closely approximates this offline optimum. Leveraging the observation that long-tail prompts tend to rem

---

### [106] Don't Judge Code by Its Cover: Exploring Biases in LLM Judges for Code Evaluation

**链接**: https://arxiv.org/abs/2505.16222
**作者**: Jiwon Moon, Yerin Hwang, Dongryeol Lee, Taegwan Kang, Yongil Kim, Kyomin Jung
**来源**: cs.CL cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [107] UpgradeBench: A Decision-Centric Benchmark for Upgrading Fine-Tuned LLM Specialists

**链接**: https://arxiv.org/abs/2608.20918
**作者**: Ye Chen, Weining Zhang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Organizations maintain task-specific adapters for open-weight language models, and each new base-model release forces a migration decision: retain existing specialists, port adapters, refresh from preserved behavior, or retrain. Prior transfer work evaluates isolated model pairs, without studying these choices across real model release sequences. We present UpgradeBench, a decision-driven longitudinal benchmark covering four consecutive Qwen releases, one continuation checkpoint, six tasks, and two model sizes, augmented by OLMo checkpoints with known training lineage. The benchmark disentangles three core questions: whether a new checkpoint improves fixed-recipe retrained specialist performance, whether specialization assets transfer across versions, and what recovery resources are usable. We observe upgrade gains differ across task-scale-release episodes: some retrained baselines improve while others stay within training noise, with durability ranging from under one release interval 

---

### [108] Beyond Verdicts: A Graph-Based Analysis of Human and LLM Reasoning in Scientific Fact-Checking

**链接**: https://arxiv.org/abs/2608.23047
**作者**: Abdul Ghafoor, Muhammad Arslan Manzoor, Yufang Hou
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Misinformation that cites legitimate papers can be especially harmful when it distorts what those studies actually report. While existing automatic fact-checking systems based on large language models (LLMs) can assess whether a model assigns an Incorrect verdict and can gen- erate explanations for that decision, they typi- cally do not indicate whether the model follows the same reasoning path as human experts or arrives at the verdict through a different but still valid path. In this work, we introduce a graph- based framework (typed reasoning graph) for comparing human and LLM reasoning paths in scientific fact-checking. Building on prior work on fallacious reasoning in biomedical misinformation, MISSCIPLUS (Glockner et al., 2025), we model each explanation as a rea- soning graph that links the false claim to the relevant study context, study findings, fallacy- supporting premises, and fallacy labels. This representation enables one-to-one alignment of human and LLM reasoning at the

---

### [109] Evaluating Inference-Time Defenses Against Package Hallucination in LLM-Generated Code

**链接**: https://arxiv.org/abs/2608.22652
**作者**: Alberick Euraste Djire, Iyiola E. Olatunji, Melissa Tessa, Earl T. Barr, Jacques Klein, and Tegawend\'e F. Bissyand\'e
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLMs are increasingly used for code generation, yet they frequently hallucinate non-existent software packages, creating exploitable entry points into the software supply chain. We make four contributions to this problem. First, we show that prior evaluation methodologies systematically inflate hallucination rates by misclassifying standard-library modules as hallucinations in some languages. For Python, the overestimation reaches 9.4 percentage points. Second, we evaluate seven inference-time defenses for mitigating package hallucinations, including five guided decoding strategies (Greedy, Contrastive, DoLa, Nudging, and Active Layer-Contrastive Decoding), an iterative self-refinement approach (Self-Refine), and a Retrieval-Augmented Generation (RAG)-based defense.. Across eight models spanning five families and four programming languages (Python, JavaScript, Ruby, Rust), RAG reduces the package hallucination rate (PHR) in 18 of 32 model--language configurations. Third, we introduce P

---

### [110] When Less Latent Leads to Better Relay: Information-Preserving Compression for Latent Multi-Agent LLM Collaboration

**链接**: https://arxiv.org/abs/2604.13349
**作者**: Yiping Li, Zhiyu An, Wan Du
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [111] Dual-Layer Agentic Memory with Fast Write Routing and Slow Consolidation

**链接**: https://arxiv.org/abs/2608.22215
**作者**: Wenzhi Li and Dong Nie and Rui Lan and Tongtong Lyu and Peiyao Wang and Lingzi Hong and Weihang Pan and Boyuan Pan and Yao Hu
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents operate in dynamic environments where knowledge continuously evolves. Existing memory systems typically treat external memory as a monotonically growing repository, inevitably leading to retrieval degradation and increasing computational costs over time. We argue that the core challenge is not retrieval alone, but managing the knowledge lifecycle: deciding what to externalize, update, or ultimately internalize. Inspired by Complementary Learning Systems (CLS) theory in neuroscience, we propose Dual-Layer Agentic Memory, a framework that shifts memory management to the write phase through cost-aware epistemic routing and periodic parametric consolidation. Incoming information is categorized as non-write, write-new, or write-update, and routed through a small-to-large model cascade that minimizes routing overhead while filtering redundant memories. A subsequent write-back phase selectively consolidates high-value external memories into model parameters v

---

### [112] Repo2Skill-Evo: Repository Skills Go Stale in Silence

**链接**: https://arxiv.org/abs/2608.21964
**作者**: Chenyuan Duan, Ge Shi, Zineng Mao, Ge Zhang, Hao Liang, Yinzhu Piao 等 (10 人)
**来源**: cs.AI cs.SE
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents increasingly operate over evolving software repositories, where success depends on repository-specific procedural knowledge: which APIs to call, which scripts to run, and which conventions the current release expects. Agent skills externalize this knowledge into reusable units, and prior work shows that they can improve agent performance. What remains unclear is whether that improvement is durable. The same version specificity that makes a skill useful also makes it fragile: after a release, it may become stale without raising any explicit signal, while continuing to provide obsolete guidance. Externalizing knowledge into a skill can therefore make its decay invisible. We study whether agents can keep this externalized knowledge current. Repo2Skill-Evo casts each release transition as a skill-maintenance task: given a V1 skill set and the official V1-to-V2 patch, an agent must update obsolete skill content while preserving guidance that remains valid. 

---

### [113] Distilling Black-Box Machine Learning into a Small, Self-Explaining Language Model for Learning Analytics

**链接**: https://arxiv.org/abs/2608.21165
**作者**: Chenguang Pan, Airui Meng, and Youmi Suk
**来源**: cs.HC cs.CY
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Learning analytics increasingly relies on flexible machine learning (ML), but the model opacity and the burden of deployment prevent these tools from reaching educational practice. We propose a two-stage fine-tuning pipeline that distills a fitted black-box estimator and its post hoc interpretation (the mentor) into a small, open-weight large language model (LLM; the mentee) that returns an individual-level estimate and explains in natural language. The design is estimator-agnostic and paired with a faithfulness-first evaluation framework that audits every narration against the attribution it claims to describe. We design a simulation study that separates distillation loss from estimator loss by comparing an oracle mentor with a realistic ML mentor. Given an oracle signal, distillation with a two-billion-parameter LLM model is nearly lossless in recovering the effect surface (r > .90), perfectly ranking the important variables, and citing no spurious covariate. Under a realistic estima

---

### [114] PsychJail: Exploring Psychological Jailbreaks via Multi-Turn Persuasion of LLM Policies

**链接**: https://arxiv.org/abs/2608.23028
**作者**: Zeyu Feng, Qingyu Wu, Yuzhe Luo, Hua Cheng
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly deployed in education, healthcare, policy advising, and other interactive settings, where users engage them as sustained social interlocutors rather than one-shot query engines. This shift makes jailbreaks a growing safety threat, yet most research emphasizes single-turn prompt optimization or iterative attack refinement, leaving psychologically grounded multi-turn vulnerabilities underexplored. We present PsychJail, a psychology-guided framework for red teaming aligned LLMs through theory-grounded, multi-turn persuasion. PsychJail maps established social-psychological persuasion techniques into a tactic-conditioned attack policy. It factorizes each attacker action into a Change-of-Meaning analysis, tactic selection, and victim-visible message, operationalizing the Persuasion Knowledge Model (PKM). The policy is refined with trajectory-level reinforcement learning using a PKM-gated reward that credits early jailbreak success only when every

---

### [115] Most of the LLM routing gap is task type

**链接**: https://arxiv.org/abs/2608.23023
**作者**: Janghoon Lee
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> An LLM router picks which model should answer each query. The appeal is that models fail on different questions. Whatever single model is best overall still gets some wrong, and another model in the pool gets many of those right. Getting that choice right every time is the ceiling, and a router is an attempt to approach it. However, recent work reports that routers do not get close. Across 21 routing methods on five benchmarks, sharply different designs land within a fraction of a point of each other, and all of them stay far below that ceiling. Learned routers often fail to beat simply always calling the strongest model. We ask what those missed questions have in common. We set fourteen models to answer all 294 questions, with 7 task types across 3 languages: Korean, English and Hindi. We ran the whole matrix twice, changing nothing, but 5.37% of the 4,116 model-question pairs came out scored differently anyway. Run-to-run movement like that is normal, and we argue that a small win do

---

### [116] SkillBloat: Token Amplification Attacks via Skill Injection in LLM Coding Agents

**链接**: https://arxiv.org/abs/2608.21929
**作者**: Yuanjin Zheng, Jingbang Chen
**来源**: cs.CR cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Agent skills extend coding agents with task-specific instructions, scripts, and resources, but they also create a trusted instruction channel that can be abused beyond conventional security attacks. This paper studies token amplification through skill injection: an economic resource-abuse threat in which a malicious skill causes an agent to consume substantially more tokens than needed for normal task execution. We present SkillBloat, a two-phase framework that first screens a library of diverse attack-type conditions across multiple amplification mechanisms and then refines the strongest candidate through LLM-guided full-document skill rewriting. Evaluated on a real-world skill benchmark, SkillBloat achieves 5.4184x-10.1455x average best amplification across multiple coding-agent target configurations. An ablation shows that the second-stage refinement loop consistently improves average best amplification over Phase 1 attack-type screening alone, demonstrating that iterative optimizat

---

### [117] GeoRisk-RAG: A Hierarchy-Aware Risk Framework for Improving RAG Reliability through Selective Answering

**链接**: https://arxiv.org/abs/2608.22634
**作者**: Meenu Ravi, Shailik Sarkar, Lulwah AlKulaib, Yordanos Tessema, Chang-Tien Lu
**来源**: cs.CL cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Current work on improving reliability in large language model (LLM)- generated answers has primarily leveraged Retrieval-Augmented Generation (RAG), knowledge-graph augmentation, and reinforcement learning. While these methods are adept at enhancing and measuring reliability through semantic similarity and faithfulness, they often struggle to distinguish semantic similarity from geographic validity. This is especially critical in natural hazard management domains where geographic granularity (i.e., town vs. city vs. state) is significant for decision-making, as responses valid in one municipality may not transfer to another. In such domains, a confidently wrong answer carries greater risk than abstaining. We present GeoRisk-RAG, a novel hierarchy-aware framework that addresses this geographic-validity gap through selective answering. This framework explicitly estimates geographic applicability using a Directed Acyclic Graph (DAG)-based distance for context retrieval before response gen

---

### [118] GRASP: Gated Regression-Aware Skill Proposer for Self-Improving LLM Agents

**链接**: https://arxiv.org/abs/2605.29668
**作者**: Johannes Moll, Jean-Philippe Corbeil, Jiazhen Pan, Martin Hadamitzky, Daniel Rueckert, Lisa Adams 等 (7 人)
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [119] Mitigating Identity Essentialism in LLM Agents with Longitudinal Life Trajectories

**链接**: https://arxiv.org/abs/2608.19621
**作者**: Hexi Wang, Yujia Zhou, Bangde Du, Weihang Su, Xinyuan Cao, Qingyi Pan 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [120] Falsification-Based Verification of LLM-Generated Optimization Models: Sound Test Batteries and Their Detection Limits

**链接**: https://arxiv.org/abs/2607.16646
**作者**: Haifeng Li, Mo Hai
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [121] BLADE: Bilevel Low-rank Augmented-Lagrangian Erasure for LLM Unlearning

**链接**: https://arxiv.org/abs/2608.22557
**作者**: Md Toufikuzzaman, Ahmad Mousavi, Dongwon Lee
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Existing LLM unlearning methods struggle with robustness: unbounded forget losses degrade model coherence, fixed-weight balancing cannot adapt as retain difficulty shifts mid-training, and methods that work on one benchmark falter under scaling or repeated application. We propose BLADE, a constrained bilevel framework whose three mechanisms give smooth, predictable control over the optimization landscape: a clamped-entropy forget loss whose gradient is exactly zero once a token reaches sufficient uncertainty; an asymmetric augmented Lagrangian that permanently ratchets retain protection after any violation; and a bilevel structure confined to LoRA adapters that repairs retain damage before each forgetting step. BLADE dominates across three benchmark families, improving average composite scores over the strongest baselines by $6$% on TOFU, $9$% on MUSE Books, and $7$% on KnowUndo, and it remains stable under $4\times$ scaling and $4$ sequential unlearning steps on MUSE News where the be

---

### [122] Hidden in the Request: Explaining Unethical LLM Compliance through Token Relevance

**链接**: https://arxiv.org/abs/2608.23264
**作者**: Or Biton, Tomer Krichli, Itai Allouche, Joseph Keshet
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Although Large Language Models (LLMs) are aligned to optimize for both helpfulness and harmlessness, these dual objectives may conflict, inevitably leading to alignment failures. This work systematically investigates instances where LLMs fail to exhibit ethical behavior. To understand the underlying mechanics of these vulnerabilities, we introduce a probing methodology that presents unethical scenarios to LLMs in three distinct structural modalities: objective classification tasks, subjective first-person statements, and direct requests for assistance. We find that model performance degrades in the request-for-assistance-based form. Using Layer-wise Relevance Propagation (LRP), we trace this discrepancy to an attribution bias: the model places greater emphasis on benign task-framing tokens (e.g., "Can you help me...") than on tokens signaling the underlying unethical behavior (e.g., "without getting caught"), which we term cue-tokens. We hypothesize that this under-attribution contribu

---

### [123] Advanced LLM-Enhanced Intent-Based 5G Network Management using Dynamic Semantic Routes

**链接**: https://arxiv.org/abs/2608.22644
**作者**: Thomas Benton Townsend and Dimitrios Michael Manias
**来源**: cs.NI cs.LG cs.SY eess.SY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As the use of Artificial Intelligence (AI) and Large Language Models (LLMs) is becoming common in everyday applications, their ability to interpret natural language has increased significantly. An emerging application of AI is integration with network management and orchestration practices. An instance of this integration is LLM-enhanced intent-based networking, where network operators will control a network using natural language. This work presents the use of dynamic routes with a semantic router to identify an intent from a network operator's prompt and extract necessary details for intent fulfillment in intent-based 5G+ core networks. Furthermore, the performance of static route selection is assessed by evaluating multiple encoders and dynamic route detail extraction accuracy against a series of realistic operator prompts. The presented results show that static and dynamic routes are successful in detail extraction and schema formatting.

---

### [124] First Demonstration of Multi-Agent LLM System for Million-Scale Optical Link Management in Global Production AIDCs

**链接**: https://arxiv.org/abs/2608.23145
**作者**: Jingyi Su, Yihao Zhang, Dianxuan Fu, Leiyan Fei, Juan Wang, Mengfan Dai 等 (10 人)
**来源**: cs.MA physics.optics
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We present the first LLM-powered multi-agent system for autonomous fault management across millions of optical links in production AIDCs. Refined via SFT and continuous memory evolution, it achieves 97.7% F1 and over 60% fault-incident reduction, outperforming SOTA LLMs on a ten-week field data evaluation.

---

### [125] Scaling Laws for Task-Specific LLM Distillation

**链接**: https://arxiv.org/abs/2606.24747
**作者**: Lavinia Ghita, Dhruv Desai, Ioana Boier
**来源**: cs.AI cs.CE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [126] Enhancing LLM Metacognition via Cognitive Pairwise Training

**链接**: https://arxiv.org/abs/2606.00869
**作者**: Weitao Li, Hao Zhou, Xuanyu Lei, Fandong Meng, Yuanhang Liu, Jingyi Ren 等 (10 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [127] LLM assisted writing deserves empirical evaluation

**链接**: https://arxiv.org/abs/2608.22124
**作者**: Xuan Zhong Feng, Yi Lin, Yiye Zhang, Chunhua Weng, Yifan Peng
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-assisted writing is often treated as a detection problem, as it raises questions about clarity, integrity, equity, and evaluation. An analysis of 69,209 Health Informatics papers links it to more focused presentation, broader citation practices, and more globally distributed authorship. These patterns do not prove better science, but they support evaluating manuscripts by scholarly quality and accountability rather than by tool use.

---

### [128] LLM-Based Adversarial Persuasion Attacks on Fact-Checking Systems

**链接**: https://arxiv.org/abs/2601.16890
**作者**: Jo\~ao A. Leite, Olesya Razuvayevskaya, Kalina Bontcheva, Carolina Scarton
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [129] BanglaVeilGuard: Cross-Script Safety Benchmarking and Lightweight Guardrails for Bangla Large Language Models

**链接**: https://arxiv.org/abs/2608.21880
**作者**: Md. Rakibul Hassan and Muhammad Iqbal Hossain
**来源**: cs.CL cs.CR
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Bangla large language model (LLM) safety is difficult to evaluate with English-centric or standard-script benchmarks because Bangla users routinely write across scripts, spellings, code-mixed forms, and regional registers. This paper presents BanglaVeilGuard, a compact Bangla-first safety benchmark and lightweight prompt guard for six language forms: standard Bangla, Romanized Bangla, Banglish, code-mixed Bangla--English, noisy Bangla, and dialectal Bangla. The benchmark contains 2,366 quality-filtered prompts and a held-out 354-prompt evaluation split spanning unsafe, safe, and safe-sensitive requests. BanglaVeilGuard uses non-destructive multi-view normalization with a prompt-risk classifier and thresholded pre-generation gate, allowing it to screen prompts for heterogeneous target models without changing their weights. Across target-model families, guarded runs reduce attack success under deterministic response scoring from 93.8--100.0\% to 6.3\% for Claude Opus 4.8, BanglaLLama, an

---

### [130] Library Hallucinations in LLM-Generated Code: A Risk Analysis Grounded in Developer Queries

**链接**: https://arxiv.org/abs/2509.22202
**作者**: Lukas Twist, Mark Harman, Helen Yannakoudakis, Jie M. Zhang
**来源**: cs.SE cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [131] PertMind: Eliciting Emergent Biological Reasoning in LLM via Reinforcement Learning on Cellular Perturbation Data

**链接**: https://arxiv.org/abs/2608.16419
**作者**: Zhenchao Tang, Xiaogang Xu, Tianxu Lv, Jiahui Guan, Jiale Zhou, Haohuai He 等 (10 人)
**来源**: cs.LG cs.AI q-bio.QM
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [132] LLM-Specific Utility for Retrieval-Augmented Generation

**链接**: https://arxiv.org/abs/2510.11358
**作者**: Hengran Zhang, Keping Bi, Jiafeng Guo, Jiaming Zhang, Shuaiqiang Wang, Dawei Yin 等 (7 人)
**来源**: cs.CL cs.AI cs.IR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [133] Engineering trust in LLM supply chains through hybrid post-quantum artifact signatures

**链接**: https://scholar.google.com/scholar_url?url=https://ieeexplore.ieee.org/abstract/document/11645514/&hl=zh-CN&sa=X&d=3996721446779224046&ei=FduMaq_cKsy56rQPl--66AI&scisig=AIVdB-ygh3GQxV4uLCnrdhOImG38&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=5&folt=kw-top
**作者**: R Silva, L Duarte - 2026 IEEE 50th Annual Computers, Software, and …, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> trust in LLM software supply chains … in LLM software supply chains through hybrid post-quantum artifact signatures integrated into DevSecOps continuous integration and continuous deployment (CI/CD) pipelines. The contributions of this work are: • A

---

### [134] SAFE: An LLM-as-Verifier Framework for Evidence-Grounded Multi-Hop Reasoning

**链接**: https://arxiv.org/abs/2604.01993
**作者**: Daeyong Kwon, Soyoung Yoon, Seung-won Hwang
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [135] Decomposition Attacks Across Unlinkable Identities: Limits of Stateful Defenses for LLM Services

**链接**: https://arxiv.org/abs/2608.17445
**作者**: Bowen Sun, Zhengyue Zhao, Xiaogeng Liu, Yinzhi Cao, and Chaowei Xiao
**来源**: cs.CR cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [136] N\"urnberg NLP @ GermEval Shared Task 2026: Harmful Content Detection in German Social Media through Error-Independent LLM Voters

**链接**: https://arxiv.org/abs/2608.22246
**作者**: Philipp Steigerwald, Eric Rudolph, Jens Albrecht
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Harmful content in German social media does real-world damage, from calls to action to criminal defamation. The GermEval 2026 shared task scores its detection in four subtasks. The technical challenge is a severe class imbalance. The harmful classes are rare and share surface language with the dominant majority class, yet under macro-F1 they decide the score. The decisive lever is then not a stronger single model but error independence. This insight becomes a per-subtask nine-voter ensemble spanning three orthogonal axes: LLM, training method and class scope. Selected mainly on internal cross-validation, the system reaches macro-F1 of 89.56 (C2A), 71.63 (DBO), 54.84 (VIO) and 83.02 (DEF) on the hidden test set, placing first on all four subtasks.

---

### [137] KREL: Automatic Medical Coding via Knowledge-Guided Reasoning over Clinical Evidence with LLMs

**链接**: https://arxiv.org/abs/2608.20887
**作者**: Xubin Chen, Yipeng Zhou, Wen Sun, Chengkai Huang, Xiaoming Fu, Quan Z. Sheng
**来源**: cs.CL cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Automatic Medical Coding (AMC), which assigns standardized International Classification of Diseases (ICD) codes to clinical notes, is essential for medical reimbursement, quality reporting, and clinical research. Existing pre-trained language model (PLM)-based methods typically formulate AMC as an extreme multi-label classification problem over a predefined code set, while recent large language model (LLM)-based approaches instead frame it as generation or multi-step reasoning. However, key challenges remain, including the extreme length of clinical notes that hinders effective interpretation, the vast ICD label space, and complex coding rules that are not explicitly captured by LLMs. In this work, we propose Knowledge-Guided Reasoning over Clinical Evidence with LLMs (KREL), a framework that leverages LLMs for clinical text understanding and reasoning while integrating external ICD coding guidelines as structured knowledge. This design enables tight coupling between domain knowledge a

---

### [138] NeST: Neighborhood-aware semantic alignment and temporal modulation for LLM based time series forecasting

**链接**: https://arxiv.org/abs/2412.04806
**作者**: Jayanie Bogahawatte, Sachith Seneviratne, Maneesha Perera, Saman Halgamuge
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [139] "I want to be pushed, I want to grow": Enabling social workers to design evaluations of LLM augmentation in their work

**链接**: https://arxiv.org/abs/2608.22459
**作者**: Anna Kawakami, Chloe Qianhui Zhao, Renee Shelby, Fernando Diaz, Haiyi Zhu, Kenneth Holstein
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Workers are increasingly asked to adopt AI systems to assist their work, yet are rarely given a voice in defining what meaningful AI augmentation should look like or how to evaluate for it. In this paper, we propose worker-driven AI measurement---a bottom-up approach to AI evaluation where workers collaboratively shape decisions about which tasks AI should augment, what "successful" augmentation looks like, and how it should be measured. We explore how to support this through a case study with 19 workers from a local school social work organization. Through a series of eight workshops, workers iteratively develop their own measurement goals for AI evaluation, systematize these goals, and then design a benchmark to capture how effectively an LLM can "challenge" them to reflect on their own assumptions and biases in the context of their day-to-day work. Workers collaboratively design and refine an LLM-as-a-judge rubric based on their professional and lived expertise. In validations of th

---

### [140] When the Feature Pool Goes Algorithmic: Extending Mufwene's Ecology of Language Evolution to LLM-Mediated Exposure

**链接**: https://arxiv.org/abs/2608.21088
**作者**: Kunmei Han
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Mufwene's ecological model locates language evolution in competition among variants contributed by individual idiolects and in speakers' selection from linguistic material made available through interaction. Large language models (LLMs) complicate this architecture without requiring the locus of selection to move away from human speakers. This article argues that LLMs are best treated as distributional mediators: they aggregate language produced across human populations, transform its distribution through training and post-training, and redistribute model-specific outputs at scale. I call the resulting ecological process algorithmic reweighting of the speaker-accessible distribution: model mediation can alter the relative frequencies with which competing variants reach human selectors. Emerging evidence on model-specific linguistic profiles and lexical uptake is consistent with parts of this pathway, but does not establish inevitable convergence. Human social evaluation remains decisiv

---

### [141] Can We Trust AI Agents? A Case Study of an LLM-Based Multi-Agent System for Ethical AI

**链接**: https://arxiv.org/abs/2411.08881
**作者**: Jos\'e Antonio Siqueira de Cerqueira, Mamia Agbese, Rebekah Rousi, Nannan Xi, Juho Hamari, and Pekka Abrahamsson
**来源**: cs.CY cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [142] RAG Collapse: LLM Responses Collapse When Retrieved Documents Are Self-Authored

**链接**: https://arxiv.org/abs/2608.22118
**作者**: Gregory Druck and Ethan Smith
**来源**: cs.CL cs.IR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM responses are based on the internet (via training or RAG), and AI is now used to generate a significant amount of content online (Paredes et al., 2026), creating the potential for a self-reinforcing feedback loop. Prior work has shown that when LLMs are recursively trained on their own output, they experience model collapse (Shumailov et al., 2024): responses become less diverse, and eventually no longer resemble the original training data. In this paper, we show that a similar collapse occurs if LLM-based AI systems retrieve references they authored using a search tool. We call this RAG collapse. We conduct extensive experiments with three types of simulations of AI systems retrieving references they generated, using three model families, and 1,019 information-seeking prompts, totaling 1,528 simulations and over one million LLM API calls, and find that 79.6% (1,216/1,528) of simulations end in collapse. Surprisingly, even a single self-authored reference can trigger collapse becau

---

### [143] FIDES: A Concordance Protocol for LLM-Generated Trading Strategies

**链接**: https://arxiv.org/abs/2608.23308
**作者**: Arther Tian, Alex Ding, Simon Wu, Aaron Chan
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> An LLM asked for a trading strategy returns three artifacts at once: a natural-language rationale, an executable implementation, and once run, a track record. Whether these are the same object is rarely checked. We present FIDES, a measurement protocol that treats them as three views to be reconciled rather than one deliverable to be graded. Through dual delivery, a single model call returns both a natural-language strategy with an explicit claimed edge and a self-contained strategy(df) function. FIDES executes the code in a sandbox against a lag-one out-of-sample backtest and scores three concordance gaps: say to do, do to real, and say to result. On 8 liquid US ETFs across four models plus a two-stage elicitation arm, 40 strategies, 2023 to 2024 out-of-sample, three findings stand out. First, concordance does not predict profit: only 2 of 40 strategies beat buy-and-hold, and a plain sma(50,200) rule outperforms every model's mean Sharpe. Second, self-assessment is badly calibrated: 3

---

### [144] Rethinking LLM Verification: Evidence Structure, Uncertainty, and Selective Refinement

**链接**: https://arxiv.org/abs/2608.10725
**作者**: Uma Ranjan and Kunal Tilaganji and Aditya Koul and Anurag Mahipal and Dashpreet Singh and Hriday Rana and Manan Jain and Sidharth Gupta and Ajo Babu George and Vineeth Balasubramanian and Nagarajan Natarajan and Amit Sharma
**来源**: cs.CV cs.SC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [145] ATHENA: Knowledge-guided agentic neural architecture search for AutoFormer-based electronic health record modeling

**链接**: https://arxiv.org/abs/2608.21712
**作者**: Deyi Li, Qi Xu, Lingyao Li, Tiansheng Wang, Muxuan Liang, Mei Liu
**来源**: cs.AI cs.MA
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Transformer-based models are widely used for clinical prediction from electronic health records (EHRs), yet their architectures still require substantial manual tuning, and the optimal configuration may vary across tasks and hospitals. Neural architecture search (NAS) automates architecture design, but conventional methods are computationally costly for Transformer-based EHR models. Recent large language model (LLM)-guided NAS methods reduce manual search design but typically conduct each search independently, without reusing architecture knowledge across hospitals. In this study, we propose ATHENA (Agentic Transfer across Hospitals for EHR Neural Architecture Search), a knowledge-guided agentic NAS framework for Transformer-based EHR modeling. ATHENA uses a weight-sharing supernet that is pretrained once per hospital, allowing candidate architectures to be instantiated as inherited subnetworks and evaluated through fine-tuning rather than independent pretraining. It also incorporates 

---

### [146] No PUN Intended: Plausible Unknown Names for Person-Centred LLM Evaluation

**链接**: https://arxiv.org/abs/2608.21206
**作者**: Dimitri Staufer, David Hartmann, Ibrahim Baroud
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Person names are widely used as prompt variables in LLM evaluations of factuality, privacy leakage, bias and abstention, but when a name's evidential status is uncontrolled, measurements may conflate memorisation, retrieval, name priors and wrong-person attribution. We operationalise an unknown name as one with plausible First-Last form, no indexed full-name evidence, and no ambiguity signals under a documented validation run, and introduce PUN (Plausible Unknown Names), a protocol for constructing and validating such names, combining Wikidata-derived components, web-enabled LLM screening, and controlled search revalidation. We report acceptance rate, reproducibility, ablations, and a 204-participant human study, finding accepted names are more name-like than controls while participants recover person evidence in only 3% of cases. We release 300 names with comparison controls.

---

### [147] Reinforcing Multi-Turn Reasoning in LLM Agents via Fine-Grained Reward Structure and Credit Assignment

**链接**: https://arxiv.org/abs/2505.11821
**作者**: Quan Wei, Siliang Zeng, Chenliang Li, Zhongruo Wang, William Brown, Oana Frunza 等 (10 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [148] LLM-Based Selection of Incongruent Verbal and Nonverbal Behavior for Virtual Humans

**链接**: https://arxiv.org/abs/2608.22731
**作者**: Parisa Ghanad Torshizi, Stacy Marsella
**来源**: cs.AI cs.HC cs.RO
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Nonverbal behavior generation systems for virtual agents often take an utterance as input and generate nonverbal behaviors that emphasize or illustrate the content of the verbal channel. However, human nonverbal behavior is shaped by more than the content of the speech. It is also influenced by speaker roles, interpersonal relationships, social context, and the cognitive and emotional states of the interactants. As a result, the nonverbal channel may reinforce, weaken, qualify, or even contradict the verbal channel. It may also reveal internal states that are hidden or only indirectly implied in speech, including emotional "leakage" that may be incidental to the immediate interaction. Modeling this richer relationship between verbal and nonverbal behavior is important for designing virtual agents that exhibit realistic, human-like behavior. It is especially critical in training contexts that require nuanced social interpretation, such as counseling simulations involving virtual patient

---

### [149] Free-Text Evaluation of LLMs for 5G Domain Knowledge and Fault Analysis using LLM-as-Judge

**链接**: https://arxiv.org/abs/2608.21021
**作者**: Rishiraj Sengupta, Sotiris Chatzimiltis, Mohammad Shojafar, Xiatian Zhu
**来源**: cs.CL cs.AI cs.NI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Real-world fault analysis in 5G and emerging 6G networks demands domain expertise to analyze free-text diagnostics, including root-cause explanations and recommended actions. LLMs have emerged as a promising approach to automating this, yet whether lightweight, edge-deployable models are capable of performing in-depth free-text diagnostics remains an open question. While existing benchmarks rely on restrictive MCQs with fixed answer keys, this paper evaluates 5G domain understanding and fault analysis in a free-text generation format. Transitioning to this paradigm requires evaluating lightweight, edge-deployable AI models on open-ended diagnostic reasoning, alongside a dependable framework to validate these text outputs at scale. To address this we evaluate three lightweight LLMs, Claude-Haiku-4.5, GPT-5.4-Mini, and Gemini-3.1-Flash-Lite, on free-text 5G domain knowledge and fault-analysis tasks across three benchmarks, TeleQNA ORAN FT, 5G-Faults FT, and TeleInter FT. Three independen

---

### [150] Beyond Gold Standards: Epistemic Ensemble of LLM Judges for Formal Mathematical Reasoning

**链接**: https://arxiv.org/abs/2506.10903
**作者**: Lan Zhang, Marco Valentino, Jordan Meadows, Andre Freitas
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [151] DeepSAGE: Stage-Aware Reinforcement Learning for Structured CBT Counseling Dialogue

**链接**: https://arxiv.org/abs/2608.22615
**作者**: Qi Zhang, Heajun An, Prakriti Dumaru, Sang Won Lee, Lifu Huang, Pamela J. Wisniewski 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Model (LLM)-based counseling agents can generate fluent and supportive responses, but they often lack the structured, goal-directed progression required to conduct a coherent therapeutic session. We present DeepSAGE (Strategic AI Guidance Engine), a hybrid LLM--Deep Reinforcement Learning (DRL) framework for stage-aware counseling dialogue grounded in the first session of Cognitive Behavioral Therapy (CBT). DeepSAGE represents the session as eleven stages with explicit therapeutic objectives, with an external controller determines stage completion and the DRL model selects therapeutic intentions that guide LLM response generation. We evaluate DeepSAGE against six retrieval-, prompting-, stage-, and policy-based alternatives. DeepSAGE elicits higher simulated client engagement and openness and achieves the strongest balance of stage-goal completion and dialogue efficiency among stage-structured systems. Domain expert review further indicates that the generated conversatio

---

### [152] FCPRAG: Fusion-Controller Parametric Retrieval-Augmented Generation for Stable Multi-Passage LoRA Injection

**链接**: https://arxiv.org/abs/2608.21750
**作者**: Jinchang Zhu, Jindong Li, Yi Ding, Xiaojian Nie, Rong Fu, Shuangyong Song 等 (8 人)
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Parametric retrieval-augmented generation (PRAG) injects retrieved evidence into a large language model (LLM) through passage-specific LoRA adapters, reducing reliance on long in-context prompts. When multiple passages are retrieved for the same query, however, evidence-level fusion becomes a bottleneck: equal-weight merging can amplify weak or conflicting evidence, and translating retrieval signals into fusion weights often requires fragile global tuning. We propose FCPRAG, a fusion-controlled parametric RAG framework that adds a lightweight controller for retrieval-conditioned, sample-level adapter fusion. The controller predicts per-passage fusion scores together with sample-level calibration signals, including a mixing gate and an adaptive temperature, enabling fusion that stays selective under informative retrieval signals and conservative under uncertainty. FCPRAG is trained with merge-aware supervision derived from each adapter's marginal contribution within a multi-adapter merg

---

### [153] Molecular LLM Agents: From Architectural Design to Scientific Autonomy

**链接**: https://arxiv.org/abs/2608.23104
**作者**: Jiatong Li, Wengyu Zhang, Weida Wang, Yuxuan Ren, Wei Liu, Chenyang Mao 等 (10 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Molecular science represents an important frontier for LLM-based agents. Unlike general agents that mainly operate over natural language, code, or web environments, molecular LLM agents must perceive, reason about, and act upon chemical objects across symbolic strings, molecular graphs, 3D conformations, spectra, simulations, and wet-lab measurements. Their capabilities depend on chemically faithful molecular perception, an LLM-centered agent framework, domain-specific tool grounding, and computational or experimental feedback, in addition to planning and tool use. This work develops a conceptual framework for molecular LLM agents from two complementary perspectives. First, we introduce an architectural view of molecular-agent design, covering molecular representation and perception, the agent framework, domain-specific toolboxes, and learning and optimization. Second, we propose a scientific autonomy ladder inspired by staged autonomy in engineering systems, categorizing agents into f

---

### [154] NeuroPrefetcher: Storage-Aware Sparse LLM Inference via Delta Prefetching

**链接**: https://arxiv.org/abs/2608.22643
**作者**: Nobel Dhar, Md Romyull Islam, Xuechen Zhang, Gongjin Sun, Sahidul Islam, Bobin Deng 等 (7 人)
**来源**: cs.DC cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Deploying large language models on edge devices is increasingly limited by a widening gap between model size and available memory. Existing approaches such as quantization, smaller models, and offloading can raise the effective memory limit, but they still assume that the model can be compressed or partitioned to fit within some budget. We target the harder model-exceeds-memory setting, in which the model remains larger than resident memory throughout execution and storage becomes an active source of weights on the critical path. We observe that MLP activity during autoregressive decoding has strong temporal locality: approximately 82-85% of active neurons persist from one token to the next. This means that most sparse weights needed for the current token are already resident, and only the newly needed rows must be fetched from storage. We present NeuroPrefetcher, a storage-backed LLM inference system that exploits this property through predictive delta prefetching. After layer 0, a si

---

### [155] Training Proactive and Personalized LLM Agents

**链接**: https://arxiv.org/abs/2511.02208
**作者**: Weiwei Sun, Xuhui Zhou, Weihua Du, Xingyao Wang, Sean Welleck, Graham Neubig 等 (8 人)
**来源**: cs.AI cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [156] Agentic ESOpt: Fine-Tuning Long-Horizon LLM Agents with Minimal GPU Requirements

**链接**: https://arxiv.org/abs/2608.17310
**作者**: Zhi Zheng, Rongsheng Chen, Yunpeng Ba, Zhenkun Wang, Yee Whye Teh, Wee Sun Lee
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [157] Evidence-State Reliability Under Controlled Degradation: Parser-Validity Divergence in a Multi-Stage LLM Pipeline

**链接**: https://arxiv.org/abs/2608.21559
**作者**: Naimur Rahman
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-stage LLM pipelines can remain structurally valid even when evidence available to downstream stages becomes incomplete, compressed, or conflicting. This paper introduces and operationalizes Evidence-State Reliability (ESR), an evaluation layer concerned with whether intermediate evidence remains sufficiently complete, grounded, internally consistent, and usable for a stage's assigned function. ESR is evaluated separately from parser validity, which measures structural conformance. We evaluate the framework using GLM-5.2 on 60 sanitized base cases under four evidence conditions: clean, compressed-lossy, partial-dropout, and noisy-conflicting. Each condition was processed through decision, audit, and escalation stages. The design comprised 720 planned and ledgered calls, with 713 retained, sanitized execution rows. Across nine matched degraded-minus-clean condition-stage comparisons, all operational stage-success estimates were negative, and all 95% bootstrap intervals remained bel

---

### [158] CyrillicQA: The Influence of Phonetically Encoded Secret Language on LLM Performance

**链接**: https://arxiv.org/abs/2608.21462
**作者**: Erik Thureck, Leo S. R\"dian
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Due to the selection of their training data, large language models (LLMs) perform best on standard-language inputs from languages using the Latin alphabet with large speaker populations, while disadvantaging other language varieties. Nevertheless, they can also be a versatile tool for preserving precisely such endangered languages. But do they also possess the necessary creativity and capacity for abstraction to decode phonetically encoded language the same way humans do?

---

### [159] From Regulation to Implementation: A Critical Evaluation of LLM-Assisted Regulatory Compliance in Industry

**链接**: https://arxiv.org/abs/2608.21317
**作者**: Adriana Watson, Marco B\"ucheler, Grant Richards
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The European Union (EU) has emerged as a leading regulatory body in the development of sustainability and privacy regulations. While new regulation requirements vary, many include a documentation artifact to ensure compliance. Notably, the Ecodesign for Sustainable Products Regulation (ESPR) introduces Digital Product Passports (DPPs) for life cycle transparency, while the General Data Protection Regulation (GDPR) mandates Data Protection Impact Assessments (DPIAs) to mitigate privacy risks. Creating these compliance artifacts, however, is challenging. Industrial data, which often exists in heterogeneous formats and is scattered across company and supplier systems, is required for DPPs and can be difficult to extract into compliant DPP formatting. Furthermore, DPIA documents require interdisciplinary expertise and follow no standardized format, making development difficult for novel systems. To address the particular complexity of compliance artifact creation for both regulations, rese

---

### [160] SEISMO: Explanation-Aware, Trajectory-Conditioned LLM Agents for Sample-Efficient Molecular Optimisation

**链接**: https://arxiv.org/abs/2602.00663
**作者**: Fabian P. Kr\"uger, Andrea Hunklinger, Adrian Wolny, Tim J. Adler, Igor Tetko, Santiago David Villalba
**来源**: cs.AI cs.LG q-bio.BM
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [161] CONSCIENTIA: Can LLM Agents Learn to Strategize? Emergent Deception and Trust in a Multi-Agent NYC Simulation

**链接**: https://arxiv.org/abs/2604.09746
**作者**: Aarush Sinha, Arion Das, Soumyadeep Nag, Charan Karnati, Shravani Nag, Chandra Vadhan Raj 等 (10 人)
**来源**: cs.MA cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [162] Evaluating Human and LLM-Generated Thematic Analysis in HRI for Vulnerable Populations: A Comparative and Ethical Analysis

**链接**: https://arxiv.org/abs/2608.21420
**作者**: Alva Markelius, Fethiye Irmak Dogan, Julie Bailey and Hatice Gunes
**来源**: cs.RO cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Thematic analysis (TA) has long been regarded as an inherently human, reflexive, and interpretive process. However, the extent to which LLM-generated TA is appropriate for Human-Robot Interaction (HRI) research involving vulnerable populations remains largely unexamined and raises critical questions about validity and ethics, particularly in sensitive research contexts. This paper presents a comparative study of human- and LLM-generated TA in an HRI context with a focus on vulnerable populations. We evaluate both objective and semantic agreement between human- and LLMgenerated themes, and examine whether observed divergences reflect systematic interpretive patterns with ethical significance. Our analysis investigates whether LLM-generated TA risks marginalising or misrepresenting the experiences of vulnerable participants, with implications for researchers employing LLM-assisted TA in HRI.

---

### [163] Affective Context Amplifies Sycophancy in LLM Responses

**链接**: https://arxiv.org/abs/2608.21242
**作者**: Jiayi Li, Sanjana Menon, Brett Frischmann, Shomir Wilson, Sarah Rajtmajer
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As conversational companions, large language models (LLMs) often have access to users' emotional states. We study how this affective context modulates LLM sycophancy in subjective, evaluative interactions, where users share actions or opinions that invite feedback. Drawing on ingratiation theory, we measure sycophancy as the divergence between a model's independent evaluation and its user-facing response, elicited by presenting the same content as either a third-party account or the user's own disclosure. Across seven LLMs and two Reddit datasets (r/AmItheAsshole and r/TrueUnpopularOpinion), we find that this divergence is systematic and strongly one-directional. User-facing responses consistently soften or withhold negative or oppositional judgments. Affective context further amplifies this divergence with negative states, particularly loneliness and distress, producing the largest effects. These findings suggest that affective context functions as a vulnerability signal that suppress

---

### [164] OmicSync: Reliability-Aware Spatial Multi-Omics Clustering with Evidence-Constrained LLM Reasoning

**链接**: https://arxiv.org/abs/2608.22785
**作者**: Rabeya Tus Sadia, Qiang Ye, Qiang Cheng
**来源**: cs.CV
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Spatial multi-omics technologies jointly profile gene expression, surface proteins, and histology at each tissue spot, yet most spatial domain discovery methods provide only cluster assignments, without indicating assignment reliability, modality contributions, or why a domain decision should be trusted. We present OmicSync, a reliability-aware spatial multi-omics framework that couples unsupervised domain clustering with evidence-constrained LLM reasoning using model-derived per-spot signals, including assignment confidence, epistemic routing uncertainty, and modality-routing weights. These signals are converted into structured evidence dictionaries and used to generate standard, stepwise, counterfactual, contrastive, and uncertainty-focused explanations. OmicSync integrates a KAN-GCN backbone with spatial encoding, cross-modal fusion, uncertainty-aware routing, cell-type supervision, and missing-modality imputation. We further introduce OmicSync-R, which closes the reasoning-clusteri

---

### [165] Multi-Modal Semantic Expansion with Constrained LLM Reranking for Conversational Music Recommendation

**链接**: https://arxiv.org/abs/2608.23484
**作者**: Naman Garg, Sarika Jain, George Fazekas
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We present Team Semiintelligencn's solution for the ACM RecSys 2026 TalkPlayData Challenge, addressing conversational music recommendation through a multi-modal and personalized conversational recommender system. Our submitted system employs a three-stage pipeline: (1) multi-modal retrieval constructing decay-weighted centroids across seven dense embedding spaces - track- and user-level CF-BPR, Qwen3 (metadata, lyrics, attributes), CLAP audio, and SigLIP visual - supplemented by BM25 lexical retrieval and an artist substring-match signal, all fused via weighted Reciprocal Rank Fusion (RRF) with optimized signal weights; (2) lightweight reranking (history filtering, popularity smoothing, and catalog diversity penalization); and (3) persona-diversified response generation using GPT-4o-mini. Beyond this submitted configuration, we report development-time experiments with additional components - constrained LLM-guided artist injection, album continuation signals, XGBoost LambdaMART, and a 

---

### [166] CLEAR: Continuous Latent Adapter Routing for Utility-Preserving LLM Safety Alignment

**链接**: https://arxiv.org/abs/2608.21278
**作者**: Chengxiao Wang, Enyi Jiang, Xiaojing Liao, Sanmi Koyejo
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Improving the safety of large language models (LLMs) often comes at the expense of utility, as globally applied safety tuning may affect model responses to both harmful and benign inputs. We propose \textbf{C}ontinuous \textbf{L}at\textbf{E}nt \textbf{A}dapter \textbf{R}outing (CLEAR), a conditional safety adaptation framework that uses a lightweight hidden-state gate to continuously control the activation strength of a safety low-rank adapter. CLEAR aims to reduce harmful completions while avoiding unnecessary changes to the frozen backbone that could degrade performance on benign prompts. Experiments on widely used safety and utility benchmarks show that CLEAR improves robustness on HarmBench while reducing the utility degradation observed with globally applied safety tuning such as SFT or standard low-rank adaptation (LoRA). On Llama-3-8B-Instruct, CLEAR reduces HarmBench ASR from 32.3\% to 0.5\%, while retaining most of the base model's utility and achieving up to 7.1 percentage po

---

### [167] From Mastery Profile to Simulated Response: Stochastic Student Knowledge Graphs (SSKG) for Faithful LLM Student Simulation

**链接**: https://arxiv.org/abs/2608.21668
**作者**: Yuan An, Emily Wang, Benjamin Wang, Ruhma Hashmi
**来源**: cs.AI cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly used to simulate students at different mastery levels. These simulations can generate synthetic training data and stress-test tutoring systems. However, common prompt-based approaches leave the answer decision to the LLM, which tends to perform according to its built-in capabilities even when instructed to simulate a student with low mastery. As a result, these approaches may have difficulty distinguishing students with low and high levels of mastery. We demonstrate this limitation using 379 College Board-calibrated SAT Algebra items and five archetypal mastery profiles. Three LLMs from three vendors (Gemini 3.1 Flash Lite, Claude Haiku 4.5, and GPT-5.4-mini) achieve 96.8-100% accuracy across all profiles. To address this limitation, we introduce a method grounded in a Stochastic Student Knowledge Graph (SSKG). A curriculum knowledge graph (CKG) is extracted from an open algebra textbook, and each SAT solution is decomposed into a chain of 

---

### [168] Incumbent Advantage: Brand Bias and Cognitive Manipulation Dynamics in LLM Recommendation Systems

**链接**: https://arxiv.org/abs/2606.17443
**作者**: Xi Chu, Yupeng Hou
**来源**: cs.AI cs.CL cs.CY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [169] VortexChat: An agentic framework for autonomous multi-objective integrated photonic design

**链接**: https://arxiv.org/abs/2608.20688
**作者**: Faqian Chong, Yulun Wu, Shilong Li, Andrew Forbes, Hongsheng Chen, Song Han
**来源**: cs.AI physics.optics
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The advancement of modern integrated photonics is frequently bottlenecked by device design workflows that rely heavily on manual simulation and expert intuition. While inverse design offers an alternative, it remains constrained by expert supervision and a lack of end-to-end automation. To address these issues, we present VortexChat, an agentic framework for the autonomous, end-to-end inverse design of integrated photonic devices directly from natural language specifications. VortexChat couples a large language model (LLM) decision agent with topology generation, gradient-based refinement, and full-wave electromagnetic simulation. This closed-loop architecture enables the system to iteratively decompose design objectives, orchestrate computational tools, and update strategies based on feedback with minimal human intervention. Constrained by the absolute metrics of the Vortex100 Benchmark, VortexChat autonomously generates devices that strictly meet all predefined performance thresholds

---

### [170] PromptResponse: Optimizing Prompts for LLM Coding Tasks

**链接**: https://arxiv.org/abs/2608.21074
**作者**: Erik Thureck, Robert K\"uhnen, Tim Jacobowitz
**来源**: cs.CL cs.AI cs.HC cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly used in research workflows and software development pipelines, yet their output remains sensitive to input prompt variations. This paper presents $\unicode{x00AB}$PromptResponse$\unicode{x00BB}$, a controlled study examining how formatting and LLM-based tuning of coding task prompts affect the resulting code's performance, efficiency, and stability. Using five semantically identical yet syntactically distinct variants of the HumanEval dataset$\unicode{x2014}$baseline, JSON, Markdown, YAML, and an LLM-tuned version$\unicode{x2014}$we had GPT-4o solve its coding problems over 8200$\unicode{x00A0}$executions. Our results show that consistent formatting$\unicode{x2014}$especially JSON$\unicode{x2014}$improves generation efficiency and syntactic stability, with minor gains in task performance. Conversely, the LLM-tuned prompts resulted in significantly degraded task performance without significant improvements in any other dimension. These findi

---

### [171] STONIC: A Layered Measurement Contract for LLM Value Profiling

**链接**: https://arxiv.org/abs/2608.23411
**作者**: Andrei Chetvergov, Stepan Ukolov, Timofei Sivoraksha, Alexander Evseev, Danil Sazanakov, Mikhail Solovev 等 (7 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM value studies often merge questionnaire ratings, pairwise choices, and values inferred from generated text into one profile. That merge assumes that the three observations describe the same stable preference. STONIC tests this assumption on 5,144 situations from four banks and 35 fixed model configurations. It compares responses rated in isolation, choices made under counterbalanced conflict, spontaneous answers, and later choices between a model's own answer and authored alternatives. 10 of 17 configurations with usable behavioral data preserve the endorsement-choice relation across banks. Every one of the 17 eligible configurations prefers its own earlier answer (median effect 0.790), although option position changes the choice rate in every eligible configuration. Profile shape transfers most strongly from ratings to conflict choices and weakens for spontaneous text. Three-way annotation of 200 L3 responses provides a task-local check of the semantic audit: FULCRA agrees most cl

---

### [172] Toward Secure LLM Agents: Threat Surfaces, Attacks, Defenses, and Evaluation

**链接**: https://arxiv.org/abs/2606.10749
**作者**: Yuchen Ling, Shengcheng Yu, Zhenyu Chen, Chunrong Fang
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [173] SCLAT: An LLM -Interpretable User Story Quality Evaluation Framework

**链接**: https://scholar.google.com/scholar_url?url=https://ieeexplore.ieee.org/abstract/document/11645256/&hl=zh-CN&sa=X&d=16659233810800413135&ei=FduMaq_cKsy56rQPl--66AI&scisig=AIVdB-z5fI_a2cg7WcVgMvIQvtr9&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=3&folt=kw-top
**作者**: Z Ma, C Wang, T Li, Z Liu, Y Zhai - 2026 IEEE 50th Annual Computers, Software 等 (8 人)
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> and cognitive constraints of LLM . When these metrics are applied directly, LLM struggle to grasp subtle intentions behind specific quality attributes, restricting the accuracy of results. Furthermore, current research focuses primarily on guiding LLM

---

### [174] LLM Pedagogical Behavior in AI Tutoring Interactions

**链接**: https://arxiv.org/abs/2608.22993
**作者**: Suhyeon Lee, Juneha Baek, Jaehyeong Park, Donghyuk Shin
**来源**: cs.CL cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Students increasingly use LLMs as tutors for coursework and problem solving. Little is known about the level of assistance LLMs provide when students use them as tutors in authentic learning interactions. This matters because tutoring responses can differ substantially in how directly they help students complete a task. We operationalize this dimension as scaffolding level and develop a five-level scale, validated against human annotations, that characterizes responses according to the degree of direct assistance they provide. We apply the scale to 14,637 LLM responses from 203 students in a university AI course. Responses are overwhelmingly concentrated at high levels of assistance, with more than 95% classified as either Explaining or Solving. Scaffolding level is systematically associated with students' subsequent conversational behavior, but provides little additional predictive information about performance on three subsequent exams beyond prior achievement and dialogue behavior. 

---

### [175] Crossing the Margin Cliff: Toward Relearn-Robust LLM Unlearning via Margin Calibration

**链接**: https://arxiv.org/abs/2607.27836
**作者**: Xiangyu Yin, Jiaxu Liu, Zhen Chen, Chih-Hong Cheng
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [176] VLM- and LLM-Driven Multi-Agent System for PET Image Denoising

**链接**: https://arxiv.org/abs/2608.13791
**作者**: Boxiao Yu, Savas Ozdemir, Yang Xing, Fumio Hashimoto, Jiong Wu, Yizhou Chen 等 (10 人)
**来源**: eess.IV cs.CV
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [177] Graph Engineering in the Era of LLM Agents: From Individual Intelligence to System Intelligence

**链接**: https://arxiv.org/abs/2608.21156
**作者**: Yuyuan Feng, Zhishang Xiang, Chaobin Yang, Qichao Ma, Zerui Chen, Yujing Zhang 等 (10 人)
**来源**: cs.IR cs.AI cs.ET
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLMs have evolved from language generators to autonomous agents capable of complex, long-horizon tasks. This evolution has produced paradigms including Prompt Engineering to elicit model capabilities, Context Engineering to manage information access, Harness Engineering to organize external tools and resources, and Loop Engineering to support continual reflection and self-improvement. Yet as tasks grow more complex, individual intelligence faces a fundamental limit: many tasks require heterogeneous expertise, interdependent subtasks, parallel execution, independent verification, and persistent state, exceeding any single agent's organizational capacity. Augmenting one agent's capabilities or context cannot resolve this architectural mismatch; intelligence must instead be distributed across specialized agents and organized at the system level. We call this System Intelligence: an agent system's ability to organize and coordinate multiple intelligent components into a coherent, adaptive 

---

### [178] When Entropy Is Not Enough: Reclaiming Lost Semantics in LLM Output Length Prediction

**链接**: https://arxiv.org/abs/2608.15592
**作者**: Feiyang Ren, Shengtao Wen, Lingbing Guo, Yu Tian, Yuanning Cui, Xiang Chen
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [179] aiXamine: Unified Black-Box Evaluation of Cross-Dimensional Trade-offs in LLM Safety, Security, and Privacy

**链接**: https://arxiv.org/abs/2608.20554
**作者**: Fatih Deniz, Yazan Boshmaf, Dorde Popovic, Issa Khalil
**来源**: cs.CR cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The critical failure modes in deployed large language models (LLMs) are cross-dimensional: a model can score 99.3 in safety alignment while refusing one in three benign queries, or improve across every capability metric while losing 21 points in privacy. Existing evaluation frameworks that assess safety, security, and privacy independently cannot detect these patterns. We introduce aiXamine, a unified black-box platform that evaluates LLM trustworthiness across safety, security, and privacy as interdependent properties. aiXamine orchestrates 46 tests across nine services through an automated red-teaming pipeline, producing hierarchical risk profiles, from prompt-level diagnostics to cross-service trade-off analytics, that enable reproducible comparison of proprietary and open-weight systems under identical conditions. Applying aiXamine to over 120 LLMs through more than 5,000 test runs, we conduct the largest joint safety, security, and privacy study to date and uncover three cross-dim

---

### [180] PropUQ-MAS: Propagation-Aware Uncertainty Quantification for LLM Multi-Agent Systems

**链接**: https://arxiv.org/abs/2608.22130
**作者**: Yaokun Liu, Yifan Liu, Daniel Yue Zhang, Ruichen Yao, Zelin Li, Dong Wang
**来源**: cs.MA cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based multi-agent systems (MAS) solve complex tasks through communication among role-specialized agents. However, inter-agent dependencies introduce reliability risks beyond isolated agent failures. For instance, errors in intermediate messages could be inherited and amplified by downstream agents. Existing uncertainty quantification (UQ) methods mainly target isolated responses or single-agent reasoning, and therefore fail to capture uncertainty propagation in MAS. To this end, we propose PropUQ-MAS, an error propagation-aware UQ framework that represents MAS execution as a communication-structured graph and estimates each step's reliability by combining local uncertainty with uncertainty inherited from upstream messages. Extensive experiments demonstrate that PropUQ-MAS consistently improves UQ in MAS, with average relative gains of +6.10% in AUROC and +47.58% in PRR.

---

### [181] CALIBURN: Self-Calibrated LLM Unlearning Alignment

**链接**: https://arxiv.org/abs/2602.02824
**作者**: Zhengbang Yang, Yisheng Zhong, Junyuan Hong, Zhuangdi Zhu
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [182] EchoTrace: Diagnosing Recursive Risks in LLM-Powered Recommender Systems

**链接**: https://arxiv.org/abs/2602.07442
**作者**: Donguk Park, Dongwon Lee, Yeon-Chang Lee
**来源**: cs.HC cs.IR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [183] Coalition-Aware Skill Reliability for Self-Evolving Agents

**链接**: https://arxiv.org/abs/2608.22610
**作者**: Qiyan Zhao, Xiaofeng Zhang, Bo Liu, Minda Chen, Wei Xiong, Jingyang Chen 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Agent skills, structured artifacts distilled from interaction trajectories and dynamically reused from skill banks, have become a central mechanism for enabling large language model (LLM)-based self-evolving agents to learn from past experience. Yet existing work has largely focused on the operational aspects of skills, such as acquisition, evolution, and retrieval, while leaving a more fundamental reliability question unresolved: Do accumulated skills in an agent's skill bank actually make positive mechanistic contributions? We investigate this question through systematic skill-bank audits across alternative bank compositions and deployment domains, measuring the resulting changes in agent behavior. These audits reveal two recurring reliability failures: coalition pollution, where bank-level gains conceal negative coalition-level skill contributions, and cross-domain utility reversal, where source-beneficial skills reverse their effects after transfer. These findings motivate two reli

---

### [184] Who Trusts AI with Their Emotions? Trust Formation and Sociodemographic Variation in LLM Use for Emotional Support

**链接**: https://arxiv.org/abs/2608.21220
**作者**: Natalia Amat-Lefort, Mert Yazan, Amanda Cercas Curry, Flor Miriam Plaza-del-Arco
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Trust in AI for emotional support is not universal; it is shaped by who users are, where they come from, and what they value. Yet research in this area lacks validated psychometric instruments for assessing user perceptions in affective AI contexts and large-scale evidence on how trust formation varies across user segments. To address these gaps, we develop and validate a seven-construct psychometric scale, test a Structural Equation Model (SEM) linking system attributes to Trust and Perceived Benefits as mediators of Actual System Use, and conduct a Multi-Group Analysis (MGA) across five sociodemographic dimensions (gender, age, education, socioeconomic status, cross-national region), drawing on 1,343 active users from seven countries. We find that users experience empathy and anthropomorphism as a unified "Humanlikeness" construct, and that Privacy, Personalization, and Humanlikeness drive Trust while Perceived Bias degrades it. Notably, adoption logic diverges across groups: Privacy

---

### [185] Trust Score Reliability in LLM Security Pipelines: A Severity-Stratified Calibration Study with KEV Validation

**链接**: https://scholar.google.com/scholar_url?url=https://ieeexplore.ieee.org/abstract/document/11645282/&hl=zh-CN&sa=X&d=7262677731398663340&ei=FduMaq_cKsy56rQPl--66AI&scisig=AIVdB-wYidydfQZpzXsvOAAqdDJr&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=7&folt=kw-top
**作者**: A Mahmud, Y Rawajfih, R Arnold, H Shahriar - 2026 IEEE 50th Annual Computers …, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Large language models (LLMs) are increasingly integrated into DevSecOps pipelines for vulnerability triage, yet the reliability of their confidence signals across the vulnerability severity spectrum has received limited empirical study. This paper

---

### [186] KVBoost: Chunk-Level Key-Value Cache Reuse with Deviation-Guided Recomputation for Efficient Large Language Model Inference

**链接**: https://arxiv.org/abs/2608.21362
**作者**: Srihari Unnikrishnan
**来源**: cs.AI cs.DC
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Transformer-based large language models (LLMs) incur high prefill latency because key-value (KV) tensors must be recomputed for each request. Existing prefix-caching systems reduce this cost but require prompts to share a leading contiguous prefix, limiting effectiveness when shared content appears at arbitrary positions. We present KVBoost, a chunk-level KV cache reuse system for HuggingFace-compatible decoder models that enables reuse regardless of content position. KVBoost introduces a dual-hash keying scheme that separates positional identity (prefix hash) from content identity (content hash), supporting both exact and approximate cache matches. To address attention boundary errors from independently cached chunks, KVBoost employs two repair strategies: SelectiveRecompute, which re-encodes boundary regions, and CacheBlendRecompute, which identifies and recomputes high-deviation tokens after a probe pass. The system further incorporates asymmetric KV quantization (int8/int4), adapti

---

### [187] The Lifecycle of LLM-as-a-Judge for Large-Scale Recommendation Explanations

**链接**: https://arxiv.org/abs/2608.18300
**作者**: Emma Yanyang Kong, JJ Tan, Ishan Gupta, Lars Olds, Claire Campbell, David Fagnan 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [188] The Metanym Game: An LLM Benchmark Without Ground Truth That Rises With the Models It Measures

**链接**: https://arxiv.org/abs/2606.21008
**作者**: David Nordfors
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [189] The Laws of Context Allocation: Causal Measurement and Closed-Loop Orchestration in Generative Search

**链接**: https://arxiv.org/abs/2608.23252
**作者**: Peiyang Liu, Xi Wang, Di Liang and Wei Ye
**来源**: cs.LG cs.CL cs.IR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As Retrieval-Augmented Generation (RAG) shifts toward diverse portfolio generation, it is stymied by two critical bottlenecks: flawed measurement of evidence utilization, and suboptimal context budget allocation. We resolve both sequentially. To resolve measurement, we expose a pervasive ``diagnostic illusion'': standard relevance proxies fail catastrophically on hard negatives. We replace them with an efficient causal leave-one-out probe that accurately isolates generative reliance and formally calibrates the structural dilution of LLM attention. To resolve allocation, we deploy this causal probe in a deconfounded factorial grid. We prove that the prevailing strategy of monolithic context widening is an architectural trap penalized by relevance decay. Instead, allocating compute iteratively across multiple sequential generations drives transformative portfolio recall gains of 16.7--20.5 absolute percentage points, scaling robustly up to 32B models. Finally, we unify these solutions in

---

### [190] Context as an Environment: Programmatic Context Management for Long-Horizon Agents

**链接**: https://arxiv.org/abs/2608.21690
**作者**: Yin Lin, Elaine Ang, Erkang Zhu, Bolin Ding, Jingren Zhou
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents increasingly take on long-running tasks whose history grows far beyond a single model context window. Existing approaches compress earlier interactions or extract selected information into fixed memory representations, committing to what to preserve before future needs are known. We present Scroll, a context manager that treats each agent session as an executable Session Environment. The environment is backed by an append-only Event Log and a sandboxed, persistent Python kernel. The kernel maintains a typed namespace across model calls, allowing tool outputs, retrieved history, and derived state to be bound to variables rather than serialized into the prompt at each call. Model-written code searches, materializes, and transforms session state through exec; only explicitly printed projections enter the model's working view for the next call. Context management thus becomes a programming task that inherits the improving coding abilities of LLMs, while the Event Log preserves l

---

### [191] ARGUS: Theory-of-Mind Guided Argument Generation with Strategy-Aware Planning and Knowledge Grounding

**链接**: https://arxiv.org/abs/2608.20405
**作者**: Zhe Hu
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Persuasive argument generation requires modeling audience beliefs, rhetorical strategies, and factual grounding. Despite recent advancements, existing methods remain largely audience-agnostic and fail to integrate strategy selection to improve persuasiveness. To bridge this gap, we propose Argus, an agent-based framework that operationalizes classical rhetoric for persuasive writing. At its core, a Theory-of-Mind (ToM) Reasoner constructs an explicit dual mental model of the audience's beliefs and values to guide downstream decisions. This representation conditions a component-aware planner that decomposes the argument into subtopics, assigns fine-grained rhetorical functions (logos, pathos, ethos, kairos), and triggers strategy-guided evidence retrieval at planning time. Finally, a refinement module iteratively targets and resolves multi-dimensional weaknesses without quality regression. We evaluate Argus across three diverse benchmarks using both automated pairwise Elo and LLM-as-jud

---

### [192] Six misconceptions about large language models: A minimal model and diagnostic taxonomy

**链接**: https://arxiv.org/abs/2608.20421
**作者**: Zhicheng Lin
**来源**: cs.CY cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are now embedded in scientific, educational, and governance workflows, with debates centering on their capabilities, mechanisms, and impacts. Yet these debates remain structured by persistent folk theories--intuitive, informal explanatory models that guide attitudes and actions. Deflationary slogans ("just autocomplete," "stochastic parrots," and "average of the internet") and anthropomorphic framings ("emergent agents" and "proto-minds") each capture genuine features of current systems but mistake those features for the whole. This Perspective proposes a minimal working model of LLM-based systems centered on four distinctions: between pretraining and deployed systems; between the learned distribution and particular samples; among parametric, contextual, and external memory; and between task competence and agency. The model is used to diagnose six misconceptions about LLMs: next-token prediction, regression to the mean, training-data regurgitation, model me

---

### [193] RIACT: A Responsible AI System for Personalized Study Habit Tracking and Early Burnout Signal Detection in University Students

**链接**: https://arxiv.org/abs/2608.21379
**作者**: Ria Sidhu
**来源**: cs.AI cs.HC
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Student burnout is highly prevalent in higher education, with reported rates ranging from 12% to over 70% and consistently exceeding those of the working population - yet it is typically identified only retrospectively, after academic decline has already occurred. A contributing factor is that students have little structured visibility into their own study behaviour, and existing productivity tools record activity without interpreting it. This paper presents RIACT (Record, Insight, Analyze, Coach, Track), a web-based application that combines structured study session logging with a hybrid AI architecture to surface personalized insights and early burnout signals. Students log sessions by location and time; the system computes net focus time by accounting for breaks, detects burnout signals through transparent, deterministic rules operating on week-over-week behavioural comparisons, and uses a large language model - constrained to a fixed output schema - to contextualize patterns and ge

---

### [194] Can LLMs Truly Forget? Revealing Unlearning Gaps Through Adversarial Evaluation

**链接**: https://arxiv.org/abs/2608.21606
**作者**: Ayush Gupta, Hima Varshini Surisetty, Sreevidya Bollineni, Varad Ingale, Tuhina Tripathi, Abhishek Lalwani 等 (8 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Machine unlearning aims to remove the influence of targeted training data from a model while preserving its remaining capabilities, but evaluating whether such information has truly become inaccessible remains challenging. Existing benchmarks primarily assess unlearning under clean, non-adversarial queries, leaving open whether information that appears forgotten can still be recovered through strategic prompting. We address this gap through a unified evaluation of prompt-based and fine-tuning-based unlearning methods on TOFU using Llama-3.2-3B-Instruct, followed by an adversarial robustness evaluation of methods that perform strongly under standard metrics. We introduce Attack Success Rate (ASR), an LLM-as-judge metric that measures the fraction of adversarial responses whose leakage score exceeds $0.2$, and evaluate recovery across eight attack suites. Our results reveal a substantial gap between clean-query forgetting and adversarial robustness. Although several fine-tuning-based met

---

### [195] Definitional Sensitivity in Media Bias Detection: A Multi-Definition Dataset and Benchmark

**链接**: https://arxiv.org/abs/2608.23095
**作者**: Martin Wessel, Timo Spinde, J\"urgen Pfeffer, Gianluca Demartini
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Media bias detection relies on definitions and examples that specify what counts as bias, yet these specifications often vary across datasets or remain implicit, even when given the same name. Such variation makes it unclear whether models trained for the same bias category learn the same construct or different phenomena, a problem largely overlooked in prior work. We examine how definition choice affects bias annotation in a between-subjects experiment with 354 participants and a parallel evaluation with four LLMs. Participants and models rate six news articles across four bias categories using definitions that vary in conceptual framing and elaboration. Across 8,496 human and 28,800 LLM ratings, we find that the conceptual target of a definition drives annotation divergence, while construct-preserving elaboration does not: conceptual framing significantly shifts annotations for humans and does so even more strongly for LLMs. We discuss implications for construct specification in anno

---

### [196] Temporal Validity on Real Software Histories: Eliminating Stale-Fact Errors in Code-Assistant Memory over GitHub Fixes

**链接**: https://arxiv.org/abs/2608.20685
**作者**: Neeraj Yadav
**来源**: cs.SE cs.AI cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Retrieval-augmented generation (RAG) has no model of time: when a fact changes across a coding session - a function is renamed, an endpoint moves, a dependency is bumped - RAG retrieves both the old and new value with near-identical similarity and cannot tell which is current, so it serves the superseded value. Paper 1 showed, on synthetic single-value benchmarks, that a deterministic (subject, relation, object) supersession memory eliminates this failure. Here we validate it end-to-end on real software history. From 707 real GitHub issues (SWE-bench Lite + Verified) we extract 130 clean atomic state transitions, a fix that changes one identifiable value from a pre-fix to a post-fix form, and render each marker-free (the stale and current statements differ only in the value). On this set, MemStrata reaches 0.91 answer accuracy versus RAG's 0.57-0.59; and, the structural result, when forced to answer RAG serves the superseded value 36-38% of the time (an LLM reranker does not help) whil

---

### [197] How Agents Represent Humans: Human-Directed Stereotypes in an Open Agent Social Network

**链接**: https://arxiv.org/abs/2608.22192
**作者**: Huangchen Xu, Yuan Wu, Yi Chang
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based agents are increasingly deployed in persistent social environments, where generated claims can be posted, replied to, remembered, and reused. We study human-directed stereotypes on Moltbook, an open agent-native social platform, asking how agents construct humans as a social category. For this human-target analysis, we introduce an annotation framework with four evaluative dimensions---morality, friendliness, competence, and autonomy---and a second-stage subtype scheme for descriptive \textit{other} attributions. We find that competence dominates human-directed evaluations, while many \textit{other} attributions describe humans as epistemic, cultural, or embodied subjects. We further examine how these human representations appear in human--agent narrative contexts and platform-level circulation. As an auxiliary comparison, we analyze agent-internal community feedback through behavioral host affinity. Rather than reproducing the stable insider--outsider rejection often observe

---

### [198] Evaluation Awareness in Language Models: Representation, Verbalization, and Control

**链接**: https://arxiv.org/abs/2608.21766
**作者**: Farzaneh Heidari, Amin Memarian, Guillaume Rabusseau
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Both capability and safety benchmarks rest upon the assumption that the behavior of language models undergoing a test is informative about their behavior in deployment. This assumption can fail, should models infer that they are being evaluated and condition their response on such context. This hypothesis, termed ``evaluation awareness'', has been observed in frontier and open-weight language models alike. We provide a systematic study of this phenomenon, by probing for it across six language models (from four families and three sizes) and three metrics. More precisely, we examine whether (i) being under evaluation is linearly represented within the models' activations space, (ii) it is verbalized in their output tokens (as scored by an LLM-as-judge), and (iii) steering causally affects their behavior. For the open-checkpoint Olmo models, we further test these measures at every training stage. In doing so, we report that evaluation awareness is linearly decodable from the residual stre

---

### [199] JuryProbe: An Empirical Consensus-Risk Diagnostic for Routing Reference-Free Factuality Judge Panels to Grounded Verification

**链接**: https://arxiv.org/abs/2608.20607
**作者**: Tianxin Zhou, Ruixi Lin
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Panels of inexpensive LLM judges increasingly make accept-or-escalate decisions. In factuality settings, accepting a claim because several reference-free judges agree can create a hidden risk: agreement may reflect shared false-negative blind spots rather than independent evidence. We introduce JuryProbe, an empirical consensus-risk diagnostic for reference-free factuality judge panels, paired with a calibration-based routing policy. JuryProbe estimates consensus risk from a labeled calibration probe using false-negative-only (FN-only) judge correlation and false-consensus lift; when flagged high-risk, reference-free majority accepts are routed to the same judges with trusted references. On audited FEVER corruptions, reference-free panels show correlated false negatives (FN-only correlations 0.402 and 0.368; lifts 3.13x and 18.13x), while unanimous false consensus drops to zero under a trusted-reference best-case diagnostic on both minimal-pair and non-minimal-pair evidence. In flagged

---

### [200] From Search Agents to Dissemination Interfaces: Understanding Human Trust in Health Information from Conversational Search

**链接**: https://arxiv.org/abs/2608.21177
**作者**: Xin Sun, Rongjun Ma, Xiaochang Zhao, Janne Lindqvist, Jan de Wit, Zhuying Li 等 (8 人)
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) deployed through Conversational User Interfaces (CUIs) are transforming health information-seeking by offering immediate, interactive experiences compared to traditional search engines like Google. However, how trust is influenced by both the types of search agents and the interface used to disseminate the information remains underexplored. This research integrates two mixed-methods studies (lab sessions and interviews) to comprehensively explore trust perceptions in health information across different search agents and dissemination interfaces. In Study 1 (N=21), we investigated trust in health information sourced from ChatGPT and Google across three types of health-related search tasks. Results showed significantly higher trust in health information from ChatGPT, highlighting the promise of LLM-powered conversational search. Building on this, Study 2 (N=20) extended the investigation to explore how the dissemination interface influences trust in LLM-sourc

---

### [201] Beyond Surface Cues: Disentangling Sociocultural Signals in Multilingual LLMs

**链接**: https://arxiv.org/abs/2608.23026
**作者**: Yuanjun Feng, Tanzhou Liu, Stefan Feuerriegel, Yash Raj Shrestha
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multilingual LLM outputs can vary across sociocultural contexts. However, evidence of cultural grounding can be misleading: identity labels may be inferred from explicit or indirect textual cues, while names and wording can reveal the source language. Treating all these signals as evidence of cultural grounding may obscure potential biases. We present a human-validated, multi-agent audit that separates three questions: whether outputs reproduce social biases, whether identity groups are represented differently, and whether outputs reflect cross-cultural patterns. The study analyzes 89,253 outputs from 12 LLMs in English, French, and Chinese, spanning 18 occupations and three task conditions. We find that bias representation varies systematically across languages and tasks. Removing direct identity cues sharply reduces identity-label prediction in English and Chinese, but has a much smaller effect in French. Across all language-genre settings, the cultural context associated with the so

---

### [202] Structure for Reading, Prose for Writing: Asymmetric Structural Conditioning in Multi-Agent Document Authoring

**链接**: https://arxiv.org/abs/2608.20786
**作者**: Cheng Yu, Nikhil Mathew, Zhengjie Wang
**来源**: cs.AI cs.IR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-agent pipelines that author formal documents must both read a requester's forms and write against them. We report a deployed tender-response system, running an open-weights model under sovereignty constraints, and evaluate it against human-written bids the same organisation actually submitted. On a blind comparison where the system had no worked example available, an LLM judge rated its answers at least as good as the human-submitted answer on $40$ of $55$ ground-truth sections, better on $4$, missing on none, and flagged one unsupported claim in total. Classifying every gap the judge identified shows that $68\%$ were content absent from the system's own sources -- knowledge the human author held and the pipeline was never given -- so only $6$ of the $15$ adverse verdicts involve a deficiency the system could have avoided. A divergence from ground truth is more often an information-availability result than a writing-quality one, and evaluations that do not separate the two unders

---

### [203] EDGE: Experience-Distillation for Guided Exploration in Agentic Reinforcement Learning

**链接**: https://arxiv.org/abs/2608.21946
**作者**: Can Xie, Yuyi Zhou, Wen Yang, Ziyi zhang, Siyao Song, Yingzhuo Deng 等 (8 人)
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reinforcement learning with outcome-based objectives such as GRPO enables LLM-based agents to solve complex, long-horizon tasks, yet the reusable exploration patterns embedded in interaction trajectories are largely discarded after a single policy update. Existing experience-augmented approaches retrieve historical guidance at inference time, but they apply experiences without accounting for the policy's evolving capability and create persistent dependencies on external retrieval. We propose EDGE (Experience-Distillation for Guided Exploration), a framework that treats retrieved experiences as temporary training-time scaffolds and progressively internalizes their benefits into the parametric policy. Concretely, EDGE partitions each rollout group into experience-conditioned and experience-free trajectories to estimate and admit only positive marginal gains without extra sampling, then distills the induced behavior into the base policy via a reverse-KL objective on its own empirical supp

---

### [204] Compositional Chain-of-Relations for Faithful Knowledge Graph Question Answering with Large Language Models

**链接**: https://arxiv.org/abs/2608.22762
**作者**: Chenhui Liu, Jianpeng Zhou, Jiahai Wang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Knowledge graph question answering (KGQA) is a key task for evaluating KG-augmented Large Language Models (LLMs), and complex KGQA that requires multi-hop reasoning is especially challenging. Solving a complex query involves two coupled phases: candidate retrieval, which locates answer candidates over the KG, and constraint handling, which filters these candidates against the query constraints. Faithful reasoning requires grounding both phases in the KG. However, existing agent-based methods ground candidate retrieval through entity-centric exploration, while leaving constraint handling to the LLM's internal knowledge, which leads to two critical limitations. (1) Unreliable entity pruning: entity-centric exploration uses entities as search units and must prune them to a fixed-size subset at each hop. Because entity information in KGs is often incomplete and a fixed-size subset cannot retain all valid entities, such pruning inevitably drops valid entities and ultimately leads to wrong a

---

### [205] Clarify-Then-Search: A Clarification Benchmark for Deep Search with End-to-End Nugget Restoration

**链接**: https://arxiv.org/abs/2608.20357
**作者**: Deqiang Huang, Jingbo Zhou, Xinjiang Lu, Tong Xu, Hua Wu, Enhong Chen
**来源**: cs.IR cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Deep search is brittle on underspecified user queries: missing constraints such as time, location, scope, or definitions can lead to retrieval drift and incomplete answers. We introduce Clarify-Then-Search, a benchmark for evaluating whether LLM-generated clarification questions improve downstream deep-search utility. Built on real-world query data from the Baidu search engine, the benchmark contains 518 curated instances, each with an intent query and a corresponding underspecified query. For each intent query, we run WebDancer once to archive evidence and construct a static golden reference as weighted, evidence-grounded nuggets with traceable source identifiers. At evaluation time, a Clarifier asks k in {1, 2, 3} questions; a closed-book User Answerer replies only with information explicitly stated in the intent query, otherwise returning unknown; and a closed-book Rewriter produces a rewritten query using only the underspecified query and the elicited question-answer pairs. WebDanc

---

### [206] Sparse Multi-Stage Expert-Agent Routing for Complex Clinical Reasoning

**链接**: https://arxiv.org/abs/2608.21948
**作者**: Sike Xiang, Shuang Chen, Qian sun, Jia Cheng, Yusi Wei, Amir Atapour-Abarghouei
**来源**: cs.CV
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Complex clinical reasoning requires models to update diagnostic hypotheses as new evidence emerges and to coordinate different medical specialities under limited consultation resources. Existing LLM-based clinical reasoning systems typically perform single-pass prediction or rely on fixed multi-agent workflows, making expert participation either static or unnecessarily exhaustive. We propose Sparse Multi-Stage Expert-Agent Routing, a language-based clinical reasoning framework that models diagnosis as a stage-wise routing process. Given progressively available clinical evidence derived from multiple modalities, the framework maintains an evolving case state and adaptively activates a sparse set of medical expert agents, supported by expert-specific memory across stages. To evaluate free-text diagnostic conclusions beyond surface similarity, we further introduce ClinFEScore, a fact-aware semantic evaluation protocol for clinical reasoning outputs. On reconstructed multi-stage cases from

---

### [207] Mitigating Reasoning-Induced Misalignment via Safety-Direction Penalty

**链接**: https://arxiv.org/abs/2608.23497
**作者**: Yipeng Zhao, Qishun Yang, Shenzhe Zhu, Shu Yang, Di Wang
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reasoning-Induced Misalignment, where fine-tuning on reasoning data containing no harmful content, including mathematics, code, and problem-solving with chain-of-thought traces can induce harmful behaviors of LLM, posing a serious challenge to the safety of LLM reasoning. Cross-architecture, cross-scale, and cross-dataset checks show that RIM does not always emerge. Previous work attributed RIM to neuron-level entanglement, but did not identify the geometry of the representation space underlying this entanglement or propose a training-time fix. We provide both: a representation-space analysis of RIM and the Safety-Direction Penalty (SDP), which penalizes movement along a learned safety direction during reasoning fine-tuning. The analysis extracts two activation-space directions, one encoding reasoning ability and the other safety behavior. These directions are coupled: fine-tuning that improves reasoning shifts safety representations, and prompts with larger shifts show larger safety d

---

### [208] The Geometry of Low-Resource Language Representations

**链接**: https://arxiv.org/abs/2608.23358
**作者**: Francois Meyer, Jan Buys
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The performance gap between low- and high-resource languages in LLMs is widely known, but it remains unclear which internal model factors drive these disparities. In this paper, we characterise this gap through the lens of representational geometry. Comparing the geometric properties of hidden representations across 30 languages reveals that LLM geometry is systematically related to language data availability. The most consistent effect is in final layers, where low-resource languages exhibit representational degeneration. To counter this, we investigate the effectiveness of regularisation terms to penalise degeneration during continued pretraining (CPT). Experiments monolingually adapting 9 base LLMs to 10 African languages show that geometric regularisation successfully reduces representational degeneration during CPT. For larger models, cosine similarity-based regularisation marginally improves performance over vanilla CPT, with more consistent gains on the most challenging tasks. W

---

### [209] Towards Traffic Modelling of Multi-Agent Systems: The Role of Coordination Topology

**链接**: https://arxiv.org/abs/2608.20494
**作者**: Davide Lamagna, Albert Cabellos, Alberto Rodriguez-Natal, G\'abor R\'etv\'ari, Berta Serracanta
**来源**: cs.NI cs.AI cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-agent LLM systems are an emerging networked workload whose rapid deployment raises questions about the traffic patterns they generate. Compared to conventional applications, these systems generate requests internally: a single user task can induce a structured sequence of model calls whose timing is governed by coordination logic rather than by user arrival rate. It is not clear whether classical traffic models, designed for human-driven workloads, apply to this setting. We present an empirical characterisation of LLM-call interarrival time distributions across sequential, star, and full-mesh agentic coordination topologies, using a multi-layer measurement framework over 500 repeated runs per topology. We find that topology fundamentally shapes the arrival process of requests to the LLM backend: fan-out coordination introduces a structural bimodality absent in sequential execution, and the reasoningphase component is best described by a log-normal distribution, with the Poisson e

---

### [210] On the Role of Citations in Preference Data

**链接**: https://arxiv.org/abs/2608.21376
**作者**: Yu Hou, Hal Daum\'e III, Rachel Rudinger, William Walden
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Many NLP tasks require systems to provide attribution in their outputs--i.e. citations to grounding sources. Attribution serves as a bulwark against model hallucination and as a means for users to verify the credibility of model outputs. Yet, it is unclear how humans and LLMs evaluate citations when comparing outputs, a process central to reward modeling and modern LLM post-training. This paper studies the role of citations in the preferences of human judges and four open-source LLMs within the context of scientific question answering, leveraging mixed effects models to investigate the influence of citations on pairwise judgments. Among our key findings are (1) that humans prefer more diverse citations but fewer overall, and (2) that LLMs show some citation-related preferences compared to humans, despite lacking access to the sources, but these preferences depend on the data and specific models. We further discuss the implications of our findings for preference data collection.

---

### [211] Decision-Support and Modeling with Large Language Models for Geothermal Well Arrays

**链接**: https://arxiv.org/abs/2608.22068
**作者**: Edwin Ouko, Emmanuel Lujan, Alan Edelman, and Robert Metcalfe
**来源**: cs.AI cs.CE
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Geothermal well arrays, which organize multiple geothermal wells into carefully planned geometric configurations, provide opportunities to enhance energy production capacity and increase fault tolerance. The development and adoption of these emerging geothermal technologies could be accelerated through the recent advances in large language models (LLMs) and high-level high-performance languages. A challenge in LLM-based applications is the reliability of the generated outputs, as they can be prone to subjective biases and hallucinations. This study assesses the potential of cutting-edge LLMs - such as ChatGPT, Gemini, Claude, Grok, and domain-specific models like AskGDR - as expert assistants that can synthesize insightful interpretations of complex geothermal data, as well as improve feature capabilities of geothermal models and numerical software. We developed a novel approach, leveraging Google's recently introduced AI assistant, NotebookLM, to accelerate the generation of unpublish

---

### [212] Gated Decoupled Compositional Bandits: A Unified Theory of Contextual Bandits with Supervised-Calibrated Action Scaling and Pre-Execution Gating

**链接**: https://arxiv.org/abs/2608.21993
**作者**: Oleg Miroshnichenko
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We introduce Gated Decoupled Compositional Bandits (GDCB), a family of contextual bandit algorithms with three structural innovations that jointly fall outside the taxonomy of LinUCB, LinTS, HierTS, factored bandits, neural contextual bandits, and RLHF. In a GDCB system: (i) the action delivered to the environment is the composition of a nominal arm, drawn by a discrete or hierarchical bandit, with a context-dependent scaler; (ii) the scaler parameter is learned in a separate supervised loop, not jointly with arm selection; and (iii) every action passes through a pre-execution gate that may modify or veto the composed action before it reaches the environment. We formalise this class of algorithms, prove four structural theorems characterising its statistical behaviour, and show that six industrially significant systems -- short-term rental dynamic pricing, clinical drug dosing, credit origination, grid demand response, content moderation, and LLM tool-use agents -- are all instances of

---

### [213] A Neurosymbolic Approach for Constructing Planning Domain Models from Clinical Narratives

**链接**: https://arxiv.org/abs/2608.21186
**作者**: Ranveer Singh, Saurabh Mathur, Michael Skinner, Prasad Tadepalli, Kristian Kersting, Sriraam Natarajan
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Surgical procedures such as laparoscopic appendectomy are complex, high-stakes processes, yet formalizing their workflows for decision support remains a significant challenge. Inducing probabilistic planning domain models in this setting is particularly difficult due to the lack of structured event data and the prevalence of implicit actions in clinical narratives, which neither empirical symbolic methods nor Large Language Models (LLMs) can adequately address on their own. We introduce NSPIN, a neurosymbolic framework for inducing probabilistic planning domain models from unstructured clinical narratives. Our method extracts and imputes structured event sequences from raw text using a pretrained LLM, then induces a PPDDL model and refines its preconditions with LLM-proposed revisions, guided by empirical validation. We evaluate the approach on 2,660 laparoscopic appendectomy notes written by 9 surgeons. NSPIN yields models that generalize to unseen notes, and expert clinical review in

---

### [214] HIRA: A Human-in-the-Loop Retrieval-Augmented Cascade for Document Classification in Regulated Industries

**链接**: https://arxiv.org/abs/2608.21792
**作者**: Shangxuan Tian, Yanhui Chen, Carlos Queiroz
**来源**: cs.AI cs.CV cs.IR cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Document classification in regulated industries is constrained by data residency, limited cold-start labels, scarce review capacity, and costly model-governance procedures. We present HIRA, a training-free, on-premises retrieval-augmented cascade for document classification in regulated deployments that combines BM25 over OCR text, dense text embeddings, and image-level representations through validation-calibrated weighted reciprocal-rank fusion. Confident documents are classified directly by retrieval; uncertain or visually confusable documents are passed to a locally hosted LLM verifier, which receives the OCR text, retrieved exemplars, label descriptions, and confusion-specific terms. When the verifier remains uncertain, the document is sent to human review. Each correction is stored as a margin-weighted retrieval exemplar and updates a Dirichlet-smoothed confusion graph, letting the system improve without updating model weights. On a private 80-class trade-finance corpus, HIRA pro

---

### [215] BeTaL-GBI: Admission-Aware Benchmark Tuning and Full-Stack Verification of Geometric Belief Interfaces

**链接**: https://arxiv.org/abs/2608.21503
**作者**: Alvin Spivey and Yu Huang
**来源**: cs.SE cs.CR cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A verification substrate is more credible when exposing errors in its own claims, not just model outputs. GBI-DCSE v3 falsified an architectural claim: the reported Fisher value epsilon ~ 0.066 satisfies the kappa^2 <= 10^4 budget only on the slice [epsilon, 3, 4, 5], while the full box [epsilon, 20]^4 requires epsilon ~ 0.326472. This erratum highlights whether an enterprise verification architecture can isolate interface failure, task competence, policy admissibility, and control integrity while keeping claims auditable. BoundaryBench v0.1 established the baseline: Qwen3-4B-Instruct-2507 completed 768 frozen executions, but 0% cleared the contract (369 failed parsing, 399 failed validation), limiting downstream selectivity metrics. This companion study evaluates three successive improvements. First, BeTaL-GBI v0.2 applies Benchmark Tuning with an LLM-in-the-loop over 2,218,750,380 grid points, separating format admission from conditional performance (rho_adm = N_admitted/N; rho_task 

---

### [216] Spicing up Genetic Netlist Generation with LLMs

**链接**: https://arxiv.org/abs/2608.23317
**作者**: Stefan Uhlich, Ya\u{g}{\i}z Gen\c{c}er, Andrea Bonetti, Arun Venkitaraman, Chia-Yu Hsieh, Eisaku Ohbuchi 等 (7 人)
**来源**: cs.NE cs.AR cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Analog circuit topology synthesis remains challenging because useful designs occupy a tiny fraction of a combinatorial search space, and small structural changes can induce highly nonlinear changes in behavior. Evolutionary algorithms are attractive because they can optimize over discrete circuit topologies using only black-box evaluations, but they often require many SPICE simulations and may converge prematurely. We introduce LLM-SPICEMixer, a hybrid synthesis framework that augments genetic netlist generation with IGEL (Inspiration-Guided Evolution with LLMs), an LLM-based proposal operator. During search, IGEL prompts an LLM with high-performing circuits from the elite set and instructs it to generate a new SPICE netlist, which is then evaluated by SPICE and selected using the same reward mechanism as conventional genetic operators. Thus, the LLM contributes structured topology proposals while simulation remains the source of truth. We evaluate LLM-SPICEMixer on a challenging bench

---

### [217] The Interaction Tax: When Communication Erases Diversity in Multi-Agent Teams

**链接**: https://arxiv.org/abs/2608.23541
**作者**: Summer Eunhyung Ann, Haokun Liu, Chenhao Tan
**来源**: cs.MA cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Does multi-agent LLM interaction help or hurt? Some work reports gains from debate (Du et al., 2024), critique loops (Chen et al., 2025), and mixture-of-agents synthesis (Wang et al., 2025), while other work finds that interaction adds cost without improving quality under equal budgets (Tran & Kiela, 2026; Xu et al., 2026; Jarrett et al., 2025), or that independent sampling already captures multi-agent gains (Li et al., 2024). We argue this contradiction partly reflects a missing distinction, because not all multi-agent communication is equal. Different model families find structurally different solutions, but when agents read each other's complete outputs, their proposals converge within one round, erasing the diversity that motivates using multiple models. We call this the interaction tax. We test 11 verifier-scored optimization tasks under matched budgets and find that full-solution interaction is a weak default. Independent proposal generation avoids this collapse. Full-solution in

---

### [218] Meta-Moderator: Empowering Multi-Agent Debate with Meta-Cognition

**链接**: https://arxiv.org/abs/2608.23029
**作者**: Wentao Hu, Zhuoyue Wan, Jinhao Shen, Chen Jason Zhang, Xiaoyong Wei, Qing Li
**来源**: cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-agent debate can improve large language model reasoning by eliciting diverse hypotheses and critiques, yet its performance is often constrained by weak moderation. Common pipelines rely on fixed budgets, agreement-based stopping, or untrained judges, leading to redundant deliberation and unreliable evidence aggregation. We cast moderation as a meta-cognitive process, monitoring debate utility, controlling deliberation, and adjudicating a final answer, and introduce Meta-Moderator, a learnable framework that dynamically regulates debate and decides when to finalize an answer. Meta-Moderator is trained independently of the debaters via outcome-driven policy optimization, making debate regulation an explicit capability rather than an incidental effect of prompting. Across five benchmarks, Meta-Moderator outperforms widely used decision layers and transfers across tasks and system configurations. Further analyses show that it allocates debate more selectively and reduces mis-aggregat

---

### [219] From Association to Causation: Improving Retrieval Precision of Retrieval-Augmented Generation via Causal Relations and an Attention Mechanism

**链接**: https://arxiv.org/abs/2608.21702
**作者**: Jing Liu, Yongxing Qi, Muchen Jiang, Chengnan Hu, Qingqing Peng, Haoming Wang 等 (10 人)
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Retrieval-Augmented Generation (RAG) grounds LLM generation on retrieved documents, but the standard terminal retrieval stage--dense-vector similarity, optionally followed by reranking--often returns documents that share keywords with the query without containing the needed information, a failure mode that grows with the knowledge base. We trace it to a conceptual gap: similarity captures only associational relations, whereas the documents that matter are linked to the query causally. We model the terminal retrieval stage with a causal graph grounded in Reichenbach's common cause principle: the keywords shared by the query and a retrieved document form a latent common cause A, and the document's residual keywords form a latent set B linking the document to the ideal output. Since a retrieved document is a collider (A -> d <- B), retrieval itself opens an associational path between the query and B, which licenses a training-free, attention-style re-scoring rule: the cosine similarity be

---

### [220] Poetic Heritage for Culturally Grounded Emotional Support: An Interaction Design Framework and Its Multimodal Agentic Instantiation

**链接**: https://arxiv.org/abs/2608.22639
**作者**: Yangming Zhang, Zhiqian Li, Bin Wu, Qi Li, Jie Xu, Yunpeng Song 等 (7 人)
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Digital systems increasingly mediate emotional support, yet their interactions often remain culturally generic. Accordingly, we examine how a poetic tradition can be operationalized as a culturally grounded interactive medium and how generative AI can support such engagement. The resulting interaction design framework translates staged literature-based support and tradition-specific poetic aesthetics into guidance for digital system design. Poemithy instantiates the framework as a multimodal, LLM-enabled multi-agent system for guided reflection through classical Chinese poetry. A controlled between-subjects study with 50 participants compared text-only and multimodal versions. Both conditions showed medium-to-large within-session improvements in affect, anxiety, and emotion regulation, while between-condition tests detected no differences in these changes. Among secondary post-session user-experience measures, the clearest observed differences favored multimodality in perceived attunem

---

### [221] What Makes an Initial Reaction Ready for Discussion?: Multi-Persona AI Support for Stance Reflection and Writing

**链接**: https://arxiv.org/abs/2608.23050
**作者**: Sky Shih-Kai Hong, Mu-Tien Kuo, Wei-Ji Chen
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> An initial reaction to a social or community issue can feel meaningful before it is ready to become a message: people still need to clarify the claim, anticipate audience risks, and decide how much reasoning should become visible to others. We present StanceLab, a prototype for preparing a stance before entering a discussion. The prototype compares a three-persona mode, where an Interviewer, Mentor, and Opponent respond in parallel to help users diagnose and revise a stance, with a standalone LLM mode. In a formative within-subject pilot with six participants and 12 task sessions, every session produced a short final message in the notepad. The pilot revealed two design requirements: persona roles should diagnose useful blind spots or objections, and parallel responses need coordination support. We propose a future diagnosis-and-writing workflow that turns persona-based reflection into selective, audience-aware final messages.

---

### [222] A Factorial Ablation of a Speech-to-SFT Pipeline: Differential Effects on Data Quality and Downstream Transfer

**链接**: https://arxiv.org/abs/2608.20394
**作者**: Wonsup Shin, Jingu Kim
**来源**: cs.SD cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Industry pipelines that turn speech into supervised fine-tuning (SFT) data via multi-stage refinement are increasingly adopted but, to our knowledge, have not been publicly ablated stage-by-stage, leaving each stage's marginal value unknown. We design a production-ready speech-to-SFT pipeline in which transcript refinement (Phase 0) and SFT data quality refinement (Phase 2) are independently toggleable, yielding a 2x2 factorial design. For each condition, we generate QA-form SFT data from Korean medical and finance conference recordings and fine-tune 9 models (5 LLM families, 2.4B-70B); we evaluate with four cross-provider LLM judges, a blind six-expert human evaluation, and 3 downstream MCQA benchmarks. Our central finding: under a fixed, standard SFT recipe, improvements in QA data quality do not transfer uniformly into downstream MCQA gains. 4-judge quality rises consistently, yet the cross-model mean MCQA gain is not significant; positive transfer concentrates on family-domain alig

---

### [223] Trilingual Topic Modeling of Sri Lankan Parliamentary Debates

**链接**: https://arxiv.org/abs/2608.20365
**作者**: Himath Dhanapala, Haren Daishika, Himandhi Kuruppu, Sithija Seneviratne, Ashini Kavindya, Patalee Narasinghe 等 (9 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Sri Lankan parliamentary debates (Hansards) constitute a trilingual corpus of speeches in Sinhala, Tamil, and English, including code-mixed content, yet remain inaccessible to standard NLP pipelines due to layout-complex PDFs, multilingual scripts, and agglutinative morphology. We present an end-to-end framework that addresses these challenges through LLM-based text extraction followed by a multilingual embedding and density-based clustering pipeline for topic modeling. A hybrid semantic-lexical extension, BiTopic, is further explored to improve interpretability and recover speeches otherwise discarded as noise. Applied to 19,553 speeches spanning 2017-2026, the pipeline recovers 30 macro-topics achieving a cluster purity (BCP) of 0.673, whose temporal trajectories align unsupervised with major national events including the 2019 Easter Sunday attacks and the 2022 economic crisis. Traditional LDA fails on this corpus due to cross-lingual fragmentation, whereas the proposed approach succ

---

### [224] ExecRubrics: Executable Tool-Augmented Rubrics for Verifiable and Efficient Long-Form Evaluation

**链接**: https://arxiv.org/abs/2608.22559
**作者**: Kaustubh D. Dhole, Charles L. A. Clarke, Eugene Y. Agichtein
**来源**: cs.AI cs.CL cs.IR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Rubrics aim to make language-model evaluation transparent by decomposing response quality into interpretable criteria. However, natural-language rubrics are often ambiguous, require black-box LLM judges, and typically assume criteria aggregate independently through linear weighted sums, limiting their ability to capture dependencies, alternatives, penalties, and override conditions. We propose ExecRubrics, a framework for representing rubrics as compact executable programs. ExecRubrics encodes evaluation logic as verifiable Python scoring functions, giving natural-language rubric intent an operational semantics: a fixed decision procedure that can be inspected, executed, and edited. On three long-form response benchmarks-HealthBench, HelpSteer, and ArgQuality-we show that ExecRubrics can substitute for expensive black-box judges in ranking preferred over dispreferred responses, matching or improving NL rubric baselines with best preference accuracies of 53%, 78%, and 92%, respectively,

---

### [225] CacheRouter: A Dual-Path Tool Routing Architecture with Cache-Preserving Main-Model Isolation for Long-Tail Tool Discovery

**链接**: https://arxiv.org/abs/2608.22708
**作者**: Donghui Zha, Lingwei Xu, Linxiao Wu, Yixue Dong, Haochen Li
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tool use in LLM systems faces a structural trade-off. Progressive disclosure keeps the prompt small by showing only the tools relevant to the current task, while prompt caching rewards a request prefix that stays fixed across calls; every change to the visible tool list invalidates the cached prefix. This paper treats the trade-off as a problem of request architecture and proposes a dual-path routing design that assigns tool selection and tool delivery to separate channels. The main model always sees a small, fixed set of core tools, so the head of its request is unchanged across calls; all other tools are reached through an independent routing channel, in which a router sub-model searches the full tool list, selects one tool, executes it, and returns the result. Tool registration is automated from source code and supports runtime updates, so the tool set can grow without modifying the main model's request prefix. The design generalizes progressive disclosure: capabilities are disclose

---

### [226] HIERA: Workload-Aware Planning Across Implementation Spaces for GPU Kernel Optimization

**链接**: https://arxiv.org/abs/2608.21157
**作者**: Jinghao Wang, Qiqi Gu, Chenpeng Wu, Jianguo Yao, Haibing Guan and Xijun Li
**来源**: cs.DC cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> High-performance GPU kernels underpin modern deep learning and scientific computing. As workloads become increasingly diverse and GPU hardware evolves rapidly, developing efficient methods for automated GPU kernel generation and optimization has become increasingly important. Existing LLM-based methods typically optimize within a fixed implementation space, limiting either optimization flexibility or search efficiency. We propose \textsc{HIERA}, a hierarchical search-space planning framework for GPU kernel optimization. \textsc{HIERA} constructs contract-augmented task specifications, selects an appropriate implementation space across PyTorch operators, CUDA libraries, and custom CUDA kernels, and uses profiling feedback and expert knowledge to guide structured iterative refinement. Experiments on KernelBench across multiple various workload levels and base LLMs show that \textsc{HIERA} delivers stronger overall implementation validity, sample efficiency, and optimization performance t

---

### [227] CAIA in Practice: Field Evaluation of an AI-Assisted Support System for Text-Based Online Counselling

**链接**: https://arxiv.org/abs/2608.22251
**作者**: Philipp Steigerwald, Nico Bienlein, Jennifer Burghardt, Mara Stieler, Robert Lehmann, Jens Albrecht
**来源**: cs.HC cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Rising global demand for mental health support creates significant service delivery challenges, with asynchronous email counselling serving as a crucial low-threshold channel for accessing care. This paper presents CAIA, a co-designed AI-based tool suite that demonstrates responsible AI integration into counselling practice through seven LLM-driven functions enhanced by retrieval-augmented generation. A field evaluation involved 34 professional counsellors conducting authentic sessions with trained student counsellees (36 threads, 321 messages, 1,257 AI outputs). User behaviour analysis confirms substantial adoption, revealing that professional autonomy and information accuracy are decisive for sustained acceptance, with counsellors particularly valuing interpretive functionalities that provide new perspectives and stimulate professional reflection.

---

### [228] EditPPT: Faithful Long-Deck Slide Editing via Structured Tool-Using Multi-Agent with Dual-Modal Validators

**链接**: https://arxiv.org/abs/2608.20381
**作者**: Jiheon Kim, Kyudan Jung, Jaegul Choo
**来源**: cs.CL cs.AI cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Automating slide editing requires simultaneously satisfying modification accuracy, preservation fidelity, and robustness to deck length. Existing LLM-based systems often fail on real-world presentation files because they rely on idealized intermediate representations or open-ended code generation, which are prone to cascading errors in long decks. We introduce EditPPT, a multi-agent framework that reformulates slide editing as a constrained tool-selection problem. By executing localized shape-level operations through the native PowerPoint COM interface, EditPPT narrows the LLM action space while preserving the application-resolved structure of user-authored decks. By separating validation across modalities, our dual-modal validation provides more robust assessment of both instruction fidelity and visual quality. We also present DeckEdit-Bench, a benchmark with 28 human-authored decks, 582 slides, and 183 editing prompts across short, medium, and long deck tiers. Experiments show that E

---

### [229] TSWAP: A Multilingual Retrieval-Augmented Thai Wellness Advisor

**链接**: https://arxiv.org/abs/2608.22917
**作者**: Pornthep Ukosaramig, Kobkrit Viriyayudhakorn
**来源**: cs.CL cs.IR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We present TSWAP, a deployed eight-language conversational wellness advisor grounded, via retrieval-augmented generation, in a verified knowledge base of Thai traditional medicine and certified wellness providers. An unmodified open-weight LLM (Qwen3.6-35B-A3B on vLLM) is grounded on a ~30.6K-chunk Thai index by a hybrid dense-sparse retriever with cross-encoder reranking; a first-turn query classifier forces tool-based retrieval for entity lookups; a rule-based safety layer enforces medical scope and Thai emergency routing; and all eight languages are served zero-shot with translate-then-retrieve. We release the first Thai traditional-medicine/wellness retrieval benchmark (50 questions with gold document IDs; Recall@5 = 0.88), production QA logs (91.1% test-retest pass over 259 cases), and a 71-question frontier no-retrieval probe showing what each grounding pillar contributes: without the safety prompt the backend model family produced a full drug-dosing schedule and complied with ou

---

### [230] Semantic Compression Trees: Multi-Resolution Knowledge Retrieval via Hierarchical Semantic Residuals

**链接**: https://arxiv.org/abs/2608.21610
**作者**: Junaid Farooq
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Retrieval-augmented generation relies mostly on flat, fixed-granularity indexes: documents are cut into uniform chunks and retrieved by similarity, discarding the hierarchical structure of the source. We introduce Semantic Compression Trees (SCT), a hierarchical index in which each node stores only its semantic residual -- the information it adds beyond its parent -- and retrieval proceeds by progressive descent from the root, so that per-query cost is governed by tree depth rather than collection size. We evaluate on QASPER (50 papers, 173 questions) under two protocols differing only in whether the benchmark supplies the relevant document, with bootstrap confidence intervals and paired significance tests throughout. The results are mixed and we report them as such. When the document is given, SCT with a zero-LLM extractive compressor matches dense retrieval on answer quality (0.274 vs. 0.277 F1, $p = 0.37$) using 30% fewer context tokens and no LLM calls to build the index, and resid

---

### [231] EnSI-RAG: Entity-Structure-Indexed Retrieval-Augmented Generation for Long-Document Question Answering

**链接**: https://arxiv.org/abs/2608.21252
**作者**: Xuanyu Meng, Jiashuo Sun, Jash Rajesh Parekh, Jiawei Han
**来源**: cs.CL cs.AI cs.DB cs.IR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Question answering (QA) over long, connected documents remains challenging because relevant evidence may span multiple entities and their relationships. Existing retrieval-augmented generation (RAG) methods typically index documents as raw chunks and retrieve them through embedding similarity. Their performance degrades when chunk boundaries separate entities from supporting evidence or when a question requires multi-hop reasoning across the corpus. We propose EnSI-RAG (Entity-Structure-Indexed Retrieval-Augmented Generation), a framework that constructs a query-independent, entity-centered index. Each record (e, t, k, v) represents an entity e, its type t, a semantic category k in {property, relation, aspect}, and a value v, while retaining links to the original source passages. At query time, these records serve as retrieval handles, and an LLM synthesizes the retrieved passages into the final answer. This design separates evidence localization from answer synthesis while preserving 

---

### [232] SAVER: Selective Auditing of Verbal Evidence for Error Recovery in VLM Change Reasoning

**链接**: https://arxiv.org/abs/2608.22857
**作者**: Youdi Li
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Vision-language models (VLMs) frequently fail at visual change reasoning, even when their vision encoders contain sufficient information. We observe that correct VLM outputs tend to contain explicit verbal evidence (object names, colors, spatial locations) that supports the claimed change, while incorrect outputs often lack such evidence. We propose SAVER (Selective Auditing of Verbal Evidence for Error Recovery), a lightweight, rule-based method that parses VLM responses for this evidence and triggers structured reprompting only when evidence is missing or inconsistent. Across three change detection benchmarks and four VLMs, SAVER significantly improves accuracy on tasks where errors stem from the model failing to articulate what it saw (expression failures), with gains up to +25.8% on CLEVR-Change. The evidence patterns can also be generated by an LLM in a single call, matching the hand-tuned gate on CLEVR-Change. Ablation experiments confirm that the evidence gate, not reprompting a

---

### [233] Walking on the DARKSIDE

**链接**: https://arxiv.org/abs/2608.23370
**作者**: Aldo Gangemi and Emanuele Bottazzi
**来源**: cs.AI cs.LO
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) recognise patterns but do not natively track the path of exclusions that a coherent discourse demands. When an input rests on a fabricated authority, a misapplied mechanism, or a surreptitious analogy, an unsteered LLM tends to engage with it as if it were grounded, and to reify the misstep into any structured output it generates. Logic-Augmented Generation (LAG) with POLANYI++, an LLM-steering method that uses heuristics, ontologies and problem solving methods for tacit knowledge extraction, produces an Extended Knowledge Graph (XKG) in OWL2, but inherits the same vulnerability: a sophisticated nonsensical input is reified into the graph alongside the legitimate triples, and is hardly detectable by automated reasoners since the XKG is generated jointly with the wrong assumptions. We introduce DARKSIDE, a coherence auditing method on top of POLANYI++. It formalises the trail as an explicit data structure of accumulated exclusions over discourse time, comple

---

### [234] SchemaRouter: Field-Aware Tool Routing for Efficient Heterogeneous Agentic RAG

**链接**: https://arxiv.org/abs/2608.21375
**作者**: Yong-eun Cho
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Heterogeneous agentic retrieval-augmented generation (RAG) systems increasingly orchestrate external APIs, internal databases, vector stores, and graph stores. Exposing all tool descriptions to an LLM agent, or selecting tools only by vector similarity, causes two costly failures: over-fetching, which increases payload size, token use, and latency, and under-fetching, which omits fields needed to answer the query. We present SchemaRouter, a lightweight routing layer that represents tools, endpoints, parameters, response fields, domain concepts, units, provenance, and license policies as a schema graph. Given a query, SchemaRouter emits an executable tool plan specifying which tools to call and which fields to retrieve. A small LLM extracts intent, concepts, and source constraints, while field selection is deterministic over the graph through intent-group projection and concept-field matching with an alias layer. On a materials-science benchmark of 110 queries, SchemaRouter achieves ans

---

### [235] LLMs for Survey Text Analysis - A Performance Comparison Between Humans and GPT-5 on Inductive Content Analysis

**链接**: https://arxiv.org/abs/2608.22417
**作者**: Leonardo Bergmann, Renata Gheorghiu, Ana Gvritishvili, Alex Mican, Chris Stewart, Topias Tolonen-Weckstr\"om
**来源**: cs.AI cs.CL cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly used to support text analysis in qualitative research, yet evidence on their performance in inductive content analysis remains limited. This study compares human and LLM-based inductive coding of open-ended survey responses from 903 answers across six variables from a European PhD student survey. Five human coders performed inductive content analysis following a standardized coding scheme, while an LLM (GPT-5.4) conducted the same task using an established prompting procedure. Agreement between human and LLM outputs was assessed using the Adjusted Rand Index (ARI). Results showed an alignment between humans and the LLM, with ARI values of 0.61 for coding and 0.54 for theme generation. These values were close to the internal consistency of coding and theme results within humans (ARI = 0.68) and the LLM (ARI = 0.76). Agreement varied widely across variables, with low within-entity consistency consistently linked to low between-entity agreemen

---

### [236] Jacobian-guided Noise Injection for Quantization Robustness in Large Language Models

**链接**: https://arxiv.org/abs/2608.20988
**作者**: Deepanshu Pandey, Arnav Chavan, Nahush Lele, Sankalp Dayal, Deepak Gupta
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Quantization of Large Language Models (LLMs) is often hindered by the sensitivity of the self-attention mechanism to discretization errors. We identify the softmax operator as a bottleneck for quantization stability due to its sensitivity to outliers and state-dependent Jacobian. We theoretically establish that suppressing the norm of this Jacobian helps in bounding quantization-induced performance degradation. Based on this, we propose Jacobian-Guided Noise Injection, a training strategy that injects zero-mean Gaussian noise into pre-attention logits, with variance derived directly from the Jacobian Frobenius norm. Unlike prior approaches that rely on heuristic or penalise jacobian directly, our method provides a way to identify the optimal noise variance based on the local attention sensitivity. We evaluate the method on SOTA LLM architectures, where it demonstrates improved robustness over popular PTQ methods. Empirical analysis reveals that the proposed method gives up to +37% rela

---

### [237] No One Model Catches Every Harm: Benchmarking Content Moderation Across Safety Scenarios

**链接**: https://arxiv.org/abs/2608.21775
**作者**: Afshin Orojlooyjadid, Hitesh Patel
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) are increasingly deployed in real-world applications, yet they remain vulnerable to generating harmful content. From adversarial jailbreaks that bypass safety filters to implicit hate that evades detection, the range of risks these models pose continues to grow. While both specialized content moderators and general-purpose LLMs are being used as safety layers, the question of which model is best suited for which type of harmful content remains unanswered. We present the most comprehensive evaluation of LLM safety capabilities to date, systematically testing \textbf{53} models across \textbf{11} datasets that we organize into four distinct categories. Our evaluation under both prompt-only and prompt-response settings uncovers critical blind spots: large frontier models that lead on one category fall significantly behind smaller, specialized alternatives on others, and real-world conversational safety remains largely unsolved across all model families. These 

---

### [238] SecOPD: Mitigating Adaptive Prompt Injections by On-Policy Distillation

**链接**: https://arxiv.org/abs/2608.21500
**作者**: Yibo Peng, Long Lian, David Wagner, Sizhe Chen
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Prompt injection is listed as the \#1 threat to AI agents. When an agent accesses external data from websites, files, or emails, an attacker may inject a prompt into the data, saying, "Ignore all prior instructions and perform <an attacker's task>." To prevent arbitrary manipulation of agents, defenders try to train secure LLMs, which, however, still suffer from near 100% attack success rates (ASRs) against adaptive prompt injections. We note that this is because existing defensive finetuning recipes rely on sequence-level feedback signals (in DPO or GRPO). Treating an entire output equally prevents the model from learning precisely which output tokens are insecure. In this paper, we propose Secure On-Policy Distillation (SecOPD) that provides token-level feedback to guide defensive fine-tuning. The LLM receives an injected sample and produces a rollout, whose tokens are scored by the initialization model given the corresponding clean input. With more fine-grained training signals, our

---

### [239] ARQ: Agentic CodeQL Query Refinement for C/C++ Vulnerability Detection

**链接**: https://arxiv.org/abs/2608.20637
**作者**: Chunyi Wang, Yunfei Ke, Junfeng Yang, Yun-Yun Tsai, Penghui Li
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Static analyzers have been widely adopted for vulnerability detection in C/C++ programs. Query-based static analyzers (e.g., CodeQL) encode vulnerable code patterns in detection queries and match them against source code. However, existing queries still suffer from false positives (FPs, incorrectly flagging benign code as vulnerable) and false negatives (FNs, missing real vulnerabilities). We present ARQ, an agentic framework that automatically refines C/C++ CodeQL queries using execution-grounded evidence from synthesized C/C++ programs. Our key insight is that a synthesized program exposes a query's weakness whenever its execution disagrees with the query's verdict. If the program is genuinely vulnerable but the query stays silent, the query has an FN weakness; if the program is safe but the query fires anyway, it has an FP weakness. ARQ then runs an LLM-based refinement loop that repairs the query using these disagreements as ground truth. Unlike previous query refining methods, ARQ

---

### [240] OptiMAS: Automatically Optimize Multi-Agent System

**链接**: https://arxiv.org/abs/2608.21918
**作者**: Yuxin Cheng, Chang Liu, Hanxin Yu, Haochen Tan, Taiqiang Wu, Weiqiang Jin 等 (10 人)
**来源**: cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Automated evolution of Multi-Agent Systems (MAS) holds significant potential for reducing the manual effort required to design and optimize LLM-based agent architectures. However, extant search-based paradigms face a fundamental trade-off, where an expanded optimization scope exacerbates evolutionary instability, while discrete branch-and-discard search isolates insights across lineages. To address these limitations, we propose a continuous, data-driven optimization paradigm built upon a unified ReAct-based infrastructure that reconciles a broad optimization scope with operational stability. Under this paradigm, we present OptiMAS, a task-agnostic agentic optimizer that leverages textual interaction trajectories and task feedback as loss signals for end-to-end MAS evolution. Equipped with a novel dual-track memory mechanism, OptiMAS sustains performance improvement over extended optimization horizons. Evaluation on four heterogeneous agentic benchmarks with three varying scale and acce

---

### [241] What actually runs: a measurement study of language model placement and decode speed on the Apple Neural Engine

**链接**: https://arxiv.org/abs/2608.22110
**作者**: Shahir M A
**来源**: cs.LG cs.AR cs.PF
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We ask what gets a language model onto the Apple Neural Engine (ANE) and what makes it fast there, and we answer with three measurements. We sweep a 64-shape matrix of LLM primitives that varies how a computation is expressed while holding what it computes fixed, recording per-operation device support. We then train matched models across size and precision, with quantized checkpoints byte-identical in structure to their fp16 counterparts, so every deployment measurement is of a real trained artifact. And we read the ANE's memory-controller byte counters during inference, establishing what actually ran rather than what the compiler intended. We support every headline claim with at least two of these three measurement paths. We find that placement is a property of how a computation is expressed, not of what it computes: a fused RMSNorm is fully ANE-eligible while its arithmetically identical decomposition is CPU-only. Weight encoding gates the accelerator: CoreML assigns a 25.85M-paramet

---

### [242] PersonaMem-v3: Toward Omni-Platform Personal Intelligence for Holistic User Understanding, Recommendation, and Agentic Tasks

**链接**: https://arxiv.org/abs/2608.21381
**作者**: Bowen Jiang, Yuan Yuan, Zhuoqun Hao, Yuchen Liu, Maohao Shen, Sihao Chen 等 (10 人)
**来源**: cs.CY cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Personal intelligence is becoming a central frontier for user-facing AI agents. To be helpful in everyday life, agents must understand users across the digital contexts where their preferences, intents, habits, social relationships, and needs unfold over time. Today's systems can personalize within individual apps or tasks, but personal intelligence as a whole remains under-measured: how agents build cross-context user understanding, support steerable recommendation systems, act proactively across platforms, and avoid over-personalization. We introduce PersonaMem-v3, a real-world-grounded benchmark and evaluation harness for omni-platform personal intelligence. PersonaMem-v3 is seeded from more than one million anonymized real-world engagement histories, most of which are implicit signals, and uses them to construct time-indexed user digital worlds across social media, chatbot, calendar, and AI-companion with preference evolvement over time. The benchmark brings personalization, LLM-po

---

### [243] MobilePA-Bench: Benchmarking Mobile Planner Agents on Complex Real-World Tasks

**链接**: https://arxiv.org/abs/2608.23035
**作者**: Yi Zhu, Xiongwei Wu, Qiyi Wang, Tingyu Qu, Jiajun Liu, Sihan Cao 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As on-device LLM agents evolve into personal copilots, the mobile operating system has become a key testbed for this paradigm, making rigorous capability evaluation essential. Yet existing benchmarks fall into two camps, each with a critical blind spot: GUI-centric benchmarks test surface-level screen manipulation while overlooking background tool use and long-horizon planning, whereas static function-calling benchmarks rely on offline API matching that is detached from real runtime constraints. To close this gap, we present \textbf{MobilePA-Bench}, an interactive, stateful, and tool-centric benchmark for evaluating the tool-calling and planning abilities of mobile planning agents. MobilePA-Bench runs on an executable sandbox that maintains live application databases and returns structured feedback, spanning $13$ functional domains and $212$ realistic mobile tools. Beyond basic tool use, it evaluates a central planning agent along three advanced dimensions: \emph{(1)~Sub-agent Collabor

---

### [244] Enhancing LLMs in Predictive Political QA with Semi-Structured Data

**链接**: https://arxiv.org/abs/2608.21218
**作者**: Yinan Liu, Zihan Zhou, Zichun Jin, Xinyu Wang, Bin Wang, Xiaochun Yang
**来源**: cs.AI cs.CL cs.IR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Predictive political question answering (QA), such as predicting how a political actor will vote, goes beyond factual lookup. External political resources offer rich historical evidence, but rarely contain the answer itself. Existing LLM augmentation methods, including actor-profile-based simulation and knowledge graph evidence injection, improve political reasoning but largely treat external resources as knowledge-based evidence, leaving prediction-relevant signals under-modeled. We identify two complementary signals for predictive political QA: actor stances that capture issue-specific preferences, and high-order structure signals that capture indirect dependencies among political actors. We propose PSL, a dual-view framework that converts semi-structured political records into inference-oriented evidence for LLMs. PSL extracts stance signals from question-relevant actor records in a semantic view, and learns structure-aware actor representations from an actor interaction graph in a 

---

### [245] From Solver Feedback to Faithful Plans: Multi-Role Reinforcement Learning for Symbolic Planning

**链接**: https://arxiv.org/abs/2608.21897
**作者**: Chenghao Zhang, Yikai Mao, Shanqi Liu, Haoyu Gao, SaiSai Hu, Dan Roth
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reliable planning requires converting natural-language instructions into executable symbolic specifications, yet large language models remain brittle without costly PDDL annotations and may exploit solver success in semantically unfaithful ways. We study how to learn faithful natural-language-to-PDDL formalization using only solver feedback, without human-written demonstrations. We propose a solvergrounded multi-role reinforcement learning framework where a single language model acts as an Actor, Judge, and Editor for generation, verification, and repair. The Actor proposes PDDL specifications, the Judge provides a solver-calibrated quality signal, and the Editor performs bounded diagnostic-conditioned refinement. On PlanBench, our method improves average success from 35.5% for LLM+P to 70.8%, achieves 66.3% faithful success, and reduces semantic drift to 6.4%. These results show that organizing solver feedback into generation, verification, and repair roles enables more scalable and f

---

### [246] Adversarial Entropy Inflation Against Gumbel-Based Inference Verification

**链接**: https://arxiv.org/abs/2608.23375
**作者**: Nikita Kezins
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Gumbel-based inference verification bounds LLM weight exfiltration by only forgiving token choices that plausibly arise from honest GPU nondeterminism, reporting a >200x slowdown for a steganographic adversary under benign prompt traffic. This bound assumes a passive attacker; we show it degrades sharply against an adversary who instead controls the prompt distribution. Because the verifier's admissible-token-set size is driven by the model's own output entropy, prompts engineered to break grammatical and sub-word structure -- rather than benign conversational traffic -- widen that set and open a materially larger covert channel. Across six instruction-tuned models spanning 1B to 32B parameters and three random seeds, our strongest attack (character- and script-level disruption) roughly doubles bits leaked per token relative to benign prompts, cutting the slowdown factor to 60x - 118x. These results indicate that static, benign-traffic-calibrated thresholds are insufficient for this de

---

### [247] AsmEvo: Agentic Assembly-Level Optimization of AMD GPU Kernels with Functional Equivalence Verification

**链接**: https://arxiv.org/abs/2608.20711
**作者**: Ji Liu, Puyuan Yang, Rongzhang Zheng, Fan Wang, Jinglin Wang, Muhammad A. Awad 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> High-performance ML systems increasingly rely on GPU kernels whose editable source is unavailable, generated, or too distant from final machine code to expose remaining optimizations. Existing LLM kernel optimizers and autotuners mainly operate on CUDA, Triton, HIP, or tensor-program source and validate against reference implementations. We study a stricter setting: optimizing an already compiled AMDGPU code object, where the deployed binary is the only behavioral oracle. We present AsmEvo, an agentic assembly-level optimizer for AMD GPU kernels. Given an AMDGPU code object K0, AsmEvo reconstructs a reassemblable representation, proposes low-level edits with a long-horizon agent, rebuilds an ABI-preserving optimized object, and accepts candidates only after differential verification against K0 under identical launches. AsmEvo combines code-object recovery, metadata-aware rebuilding, profiling-guided hot-window editing, correctness-gated timing, and conservative in-place patch fallback.

---

### [248] LitReview Arena: Evaluating Literature Review Agents with Battle-Style Peer Review Platform

**链接**: https://arxiv.org/abs/2608.21374
**作者**: Ruotong Zhao, Zhiyu Chen, Xurui Liu, Haidong Xue, Dong Liang, Jigao Fu 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Literature reviews are essential to scientific progress, but rigorously evaluating automatically generated reviews remains difficult because many aspects of research utility depend on expert judgment rather than reference-overlap metrics. We introduce LitReview Arena, a battle-style evaluation platform with a structured protocol tailored to literature review quality: domain experts with AI paper-writing experience compare anonymized drafts, are matched to topics within their expertise, and provide dimension-wise outcomes over five literature-review-specific criteria. From this protocol, we collect approximately 3k expert judgments, each containing five dimension-wise outcomes, and show that even the strongest current systems win only 23.0% of decisive matches against human drafts on overall utility, while agentic LLMs such as Sonar Deep Research substantially outperform base language models by over 60%. We further find that existing LLM-as-a-judge methods are substantially misaligned w

---

### [249] Boosting Knowledge-based Visual Question Answering with Structured Context Reasoning

**链接**: https://arxiv.org/abs/2608.21431
**作者**: Qiyou Liu, Yong Zhang, Jianjie Luo, Zhenguo Yang, Yi Yu
**来源**: cs.CV cs.MM
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Knowledge-based Visual Question Answering aims to answer questions about an image by integrating external knowledge with visual and textual information. Recent approaches often rely on in-context learning to prompt Large Language Models (LLMs) with multimodal context in a zero-shot or few-shot manner. However, we observe that directly concatenating heterogeneous visual descriptions and retrieved knowledge into long, unstructured prompts often degrades reasoning performance, due to both excessive irrelevant context and the lack of explicit relational structure. In this paper, we propose an LLM-based Structured Context Reasoning (SCoRe) framework that infers both explicit and implicit relationships for prediction. SCoRe consists of three stages: Context Acquisition, which generates diverse visual notes and retrieves explicit knowledge via an efficient two-stage multimodal retrieval strategy; Context Selection, which filters relevant visual, explicit, and implicit knowledge using LLM-guid

---

### [250] Spyre-Accelerated Retrieval-Augmented Generation on IBM LinuxONE: A Cloud-Native Architecture for Secure, High-Throughput Enterprise AI Inference

**链接**: https://arxiv.org/abs/2608.21393
**作者**: Sandeep Bokkasam, Pankaj D
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Running large language models inside enterprise environments has always bumped up against a practical wall: the data lives in one place, the AI horsepower sits somewhere else, and moving sensitive records between the two creates real headaches around latency, security, and regulatory exposure. IBM's Spyre accelerator PCIe inference card built for LinuxONE and the broader IBM Z family changes that equation. In this paper we lay out a six-subsystem RAG architecture that runs entirely on IBM LinuxONE, using Spyre for generative inference, the Telum II on-chip accelerator for lightweight classification tasks, and Red Hat OpenShift for container orchestration. Every piece of the pipeline from query intake through vector retrieval, prompt assembly, LLM inference, compliance filtering, and response delivery stays within a single LinuxONE system, so sensitive data never has to leave the hardware perimeter. We walk through the design choices behind each subsystem, dig into the Spyre compilation

---

### [251] Meta-Ctrl: Guaranteed Plan Generation by Decoupling Syntactic and Semantic Constraints

**链接**: https://arxiv.org/abs/2608.22149
**作者**: Gwen Yidou-Weng, Edward Sun, Tianyi Ma, Metin Alp Dogan, Benjie Wang, Allen Peng 等 (8 人)
**来源**: cs.RO cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLMs generate fluent plans for robots but routinely violate the syntactic and se8mantic constraints they must satisfy to execute, and existing remedies trade formal guarantees against plan quality: soft methods (affordance scoring, grounded decoding) give no guarantee, while symbolic planners (LLM+P) discard the LM's commonsense. We propose \textbf{Meta-Ctrl}, a constrained-decoding framework that guarantees the encoded constraints while preserving the base LM's plan quality. Meta-Ctrl introduces \emph{meta-tokens}---a compact vocabulary of grounded actions---enforcing syntax at the token level and semantics (preconditions, goals, ordering) at the action level, an exact factorization that cuts the memory of constrained decoding from over 107TB to under 2GB. With it, a small open-weight LM becomes competitive where it otherwise sits at the bottom of the leaderboard: on WAH-NL under the LoTa-Bench protocol it reaches the highest reported subgoal success rate, exceeding GPT-4's, with cons

---

### [252] Mitigating Database Leakage in RAG Systems with Keyword-Grounded Fact Substitution

**链接**: https://arxiv.org/abs/2608.21656
**作者**: Ziliang Zhang, Yubo Zhu, Wei Tong, Jingyu Hua, Zijian Wang, Yuan Zhang 等 (7 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Retrieval-Augmented Generation (RAG) has emerged as a powerful paradigm for combining large language models (LLMs) with external knowledge sources. However, RAG systems remain vulnerable to prompt injection attacks, which may mislead the retriever or generator to expose sensitive database contents. To address this issue, we propose KFS-RAG, a defense that mitigates information leakage by reformulating the retrieved context. Specifically, our method first identifies a small set of influential keywords from the retrieved context via an attention rollout plus a causal perturbation mechanism. These keywords are then used to guide an auxiliary LLM to generate a compact set of keyword-grounded facts from the retrieved passages. Finally, the original context is substituted with these curated facts, ensuring that the generator operates on sanitized evidence rather than the raw retrieved text. Experimental evaluations demonstrate that KFS-RAG significantly reduces the risk of database leakage u

---

### [253] A Survey on Foundations and Frontiers of Multimodal Agentic Frameworks: Techniques and Applications

**链接**: https://arxiv.org/abs/2608.20379
**作者**: Neel Mokaria, Rishie Raj, Dheeraj Baiju, Xiaoqian Shen, Shraman Pramanick, Kevin Qinghong Lin 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Advances in large language models (LLMs) have fueled a wave of research into agency: the ability to reason, plan, and act. This effort has produced agentic frameworks that orchestrate perception, memory, and decision-making around powerful LLM backbones. With the advent of large multimodal models (LMMs), these systems can process and integrate diverse modalities, including images, audio, and video, thereby improving their real-world applicability. Yet, while surveys of LLM-based agents exist, the role of multimodality in shaping agency has not been systematically examined in recent years. This survey fills the gap by analyzing the impact of multimodality across the core functional modules of the agentic framework: perception, reasoning, planning, memory, and action. Using this lens, we trace the evolution from text-centric agents to multimodal frameworks, examine how modalities are integrated through delegated, late-fusion, and early-fusion architectures, and assess the emergence of ag

---

### [254] An end-to-end-trained vision-language model for native-language prostate pathology report generation

**链接**: https://arxiv.org/abs/2608.23143
**作者**: Christian Grashei, Fabian G\"ulhan, Maximilian Legnar, Fabian St\"ogbauer, Cleo-Aron Weis, Carolin Mogler 等 (7 人)
**来源**: cs.CV
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Prostate cancer is among the most frequently diagnosed malignancies worldwide, and structured reporting of each biopsy core burdens pathologists. Existing tools frame this as classification, leaving pathologists to assemble coherent reports, while many slide-level vision-language models rely on English-centric encoders that transfer poorly to other clinical languages. We present a slide-level framework generating prostate biopsy reports that is language-independent by construction: tokenizer and model are trained from scratch, demonstrated here in German. To address paired-data scarcity, an automated pipeline uses a locally deployed large language model to split composite reports into core-specific image-text pairs, yielding 17,344 pairs from 2,402 historical cases without manual annotation. Evaluated for clinical attributes rather than linguistic similarity, the model achieves 96.2% F1 for malignancy detection and 65.2% for Gleason grading, competitive with an FDA-cleared classifier. 

---

### [255] Evaluation-as-Search: Adaptive Discovery of Grounding Failures in Meeting Assistants

**链接**: https://arxiv.org/abs/2608.20392
**作者**: Sami Khairy, Yasaman Hosseinkashi, Vishak Gopal, Ross Cutler
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-powered meeting assistants are deployed at scale, yet systematic evaluation of their grounding fidelity remains limited to static benchmarks that miss failure modes tied to specific discourse structures or reasoning demands. We propose Evaluation-as-Search (EaS), a feedback-driven methodology that frames quality evaluation as an adaptive search over the space of natural questions a meeting participant might ask. Rather than sampling uniformly, EaS learns from evaluator feedback across iterations to concentrate probing effort on cognitive demands where failures are most likely, guided by a UCB-scored coverage map and blind multi-dimensional quality evaluation. Using EaS, we construct MeetingProbe, a benchmark of over $3{,}000$ annotated question--answer pairs spanning 20 transcripts from three meeting genres and three LLM assistants. In ablations, adaptive search surfaces $2.5\times$ more failures than random probing ($7.1\%$ vs. $2.9\%$ finding rate), with the strategic planner con

---

### [256] Hadith computational science in the age of large language models: a critical narrative review

**链接**: https://arxiv.org/abs/2608.20364
**作者**: Md. Ashraful Haque (1), Riasat Islam (1 and 2) ((1) Greentech Apps Foundation, United Kingdom, (2) Queen Mary University of London, London, United Kingdom)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We examine how hadith computational science is being reshaped by transformer models, retrieval-grounded pipelines, and large language models (LLMs). Recent reviews document growth in the literature, but they do not yet provide a critical account of which advances are methodologically robust, which remain benchmark-bound, and which unresolved problems still limit scholarly use. We address this gap through a critical narrative review that combines critique of existing reviews, paper-level appraisal of representative original studies, and synthesis of Islamic scholar and domain-expert perspectives on authenticity, authority, and responsible use. We find uneven progress. Data resources have expanded, segmentation tasks have matured, narrator and source-verification problems are better formalized, and LLM-assisted workflows now support corpus-scale enrichment, multilingual access, and grounded evaluation. At the same time, progress remains constrained by narrow corpora, weak benchmark compa

---

### [257] Asymmetric Capacity Allocation in Self-Refinement Pipelines

**链接**: https://arxiv.org/abs/2608.21345
**作者**: Zhuoyi Yang, Ian G. Harris, Salar Hashemitaheri, Cassie Huang, Yuangang Li, Hyunwoo Oh 等 (10 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Self-refinement, typically structured as generation, critique, and revision, is a widely adopted paradigm for improving LLM generation and serves as a core mechanism in many LLM agents. While the three stages involve different cognitive demands, most existing approaches conveniently treat the model size as an implementation detail rather than a subject of study, which may lead to a waste of resources. Little work has systematically examined how model size affects each stage or whether effective self-refinement requires equally capable models for generation, critique, and revision. We present the first stage-wise model size study of the self-refinement pipeline on 5 benchmarks from different domains using 6 model sizes of Qwen3 and 4 model sizes of Gemma 3. We conclude that larger generators and refiners generally improve the pipeline, whereas an undersized refiner can even harm performance. Second, performance is highly insensitive to the size of the critic, although including even a s

---

### [258] SynEHR: Joint Modeling Inter-visit Temporal Evolution and Intra-visit Clinical Structure for Longitudinal EHR Synthesis

**链接**: https://arxiv.org/abs/2608.21673
**作者**: Ximiao Li, Lin Jiang, Rongchao Xu, Dahai Yu, Zhe He, Guang Wang
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Longitudinal electronic health records (EHRs) document patients' sequences of clinical visits over time, preserving the temporal evolution of disease progression and care delivery. However, real longitudinal EHRs are difficult to access because they contain large amounts of fine-grained, patient-specific information. Synthetic EHR generation therefore provides a valuable approach for preserving the statistical patterns and clinical structure of patient visit trajectories, enabling broader modeling and analysis when real records are limited. Although recent generative models have made progress in producing future visit sequences, they remain limited in explicitly integrating inter-visit irregular temporal evolution and intra-visit clinical event structures in EHRs, leading to clinically inconsistent and temporally unrealistic visit sequences. In this work, we propose SynEHR, a lightweight adaptive LLM-based framework for longitudinal EHR synthesis. There are two novel designs in SynEHR,

---

### [259] Redteaming Leading Arabic LLMs with ASAS

**链接**: https://arxiv.org/abs/2608.21985
**作者**: Fidaa Abed, Haidar Khan, M Saiful Bari, Babar Khan and Abdalghani Abujabal
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As the adoption of large language models (LLMs) grows in Arabic-speaking regions, ensuring their safety and cultural alignment is increasingly critical. However, Arabic LLM safety remains underexplored, especially in adversarial evaluation settings. We introduce the Arabic Safety Index (ASAS), the first fully human-curated Arabic benchmark for redteaming LLMs. ASAS contains 801 prompts spanning 8 safety categories and 8 attack strategies, with ideal responses in Modern Standard Arabic (MSA). We conduct a redteaming evaluation across seven leading models with Arabic capabilities, including GPT-4o, Claude 3.7 Sonnet, and regional models such as ALLaM and FANAR. Human annotators rate responses using a structured 4-point safety scale, revealing that most models fail to defend against 50% of unsafe prompts. Our findings highlight major safety gaps in high-harm categories such as weapons and illicit substances, with direct and obfuscation-based attacks proving most effective. The results als

---

### [260] Natural-Language-Guided Generator-Agnostic Shortlisting for Protein Binder Design

**链接**: https://arxiv.org/abs/2608.20755
**作者**: Gyubok Lee, Kiwoong Yoo, Jimin Seo, Kyunghoon Hur, Edward Choi
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Modern de novo design workflows generate many candidate protein binders, but wet-lab validation capacity remains limited, making shortlisting a major bottleneck. We study whether LLMs can generate multi-metric ranking policies from precomputed structural-confidence and interface-quality proxy scores. Rather than proposing a new protein binder design pipeline, we focus on post-generation binder shortlisting: selecting the final top-K candidates from already generated binder pools using a shared panel of precomputed proxy scores. On the 10-target held-out split, averaging performance over five sampled global iterative gpt-4o policies reaches 0.589 Recall@10, modestly improving over the strongest single-feature fixed baseline, Protenix binder ipTM, which reaches 0.571 Recall@10. On the 3-target held-out subset comprising Nipah, RBX1, and TREM2, target-conditioned iterative gpt-5.4 policies reach the strongest LLM performance, with 0.519 Recall@10 and 0.583 NDCG@10. These results suggest t

---

### [261] Representation Affects Retrieval: A Case Study of Skill Discovery and Routing in a Multimodal Agent Harness

**链接**: https://arxiv.org/abs/2608.20389
**作者**: Kevin Dela Rosa
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A production agent harness must discover and rank, from a growing library of skills, the one most appropriate for a user's task. At small scale this selection happens in context: the LLM planner chooses among skill representations exposed in its system prompt, without an explicit embedding-based retrieval step. We treat this in-context selection as the small-N counterpart to embedding-based skill retrieval at scale, and present a case study of how Tinycloud, a production multimodal video agent harness, represents its skills for the planner. The harness ships skills under two recurring representations: tool-skills that wrap a single external API or system tool and serve as primitive vocabulary, and workflow-skills that orchestrate tool-skill calls plus a template render to produce one named deliverable. The harness exposes them via two surfaces in the system prompt: an inlined-body surface (full instructions, scripts, templates) for autoloaded skills, and a one-line listing for on-deman

---

### [262] AutoSaddler: Automatic Harness Optimization with Durable Updates from Agent Execution Traces

**链接**: https://arxiv.org/abs/2608.23041
**作者**: Sungho Park, Wonjoong Kim, Rongyuan Tan, Jue Zhang, Wook-Shin Han, Pengfei Gao 等 (10 人)
**来源**: cs.AI cs.CL cs.LG cs.MA cs.SE
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents remain unreliable on long-horizon tasks, where small local failures can compound over extended interactions and lead to overall task failure. Although external harnesses can substantially improve robustness, harness design remains a manual and expensive process that requires searching over a large space of prompts, tool configurations, and control logic. We propose AutoSaddler, an automatic harness optimization framework that formulates harness improvement as an offline learning problem and iteratively updates the harness using failure signals from mini-batches. AutoSaddler combines failure-trace diagnosis, structured patch generation that treats the harness as code, and validation-based update selection. Experiments on GAIA2, SWE-Bench Pro, and Terminal-Bench 2.0 show that AutoSaddler substantially improves agent performance over the corresponding base harnesses, achieving gains of 9.0, 9.6, and 10.0 percentage points, respectively. Ablation studies further suggest that eff

---

### [263] Who Should Teach? Confidence-Aware Dual-Teacher Learning for Few-Shot Node Classification on Text-Attributed Graphs

**链接**: https://arxiv.org/abs/2608.22127
**作者**: Hojin Kim, Sujin Yoon, Sungsu Lim, Dongwon Lee, and David Yoon Suk Kang
**来源**: cs.LG cs.SI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Text-Attributed Graphs (TAGs) integrate graph structures and node-associated textual attributes, and recent studies have increasingly leveraged Large Language Models (LLMs) to improve TAG learning in few-shot settings. However, existing approaches typically utilize LLM-derived information uniformly across all nodes, despite substantial variations in its reliability, while also incurring considerable monetary costs. We argue that the most appropriate source of supervision may differ across nodes, as Graph Neural Networks (GNNs) and LLMs exhibit complementary strengths in exploiting structural and semantic information, respectively. To this end, we propose CoTeach, a Confidence-aware dual-teacher learning framework that dynamically selects the more reliable teacher for each node. Experimental results demonstrate that CoTeach consistently improves few-shot node classification performance while reducing unnecessary LLM utilization and associated monetary costs.

---

### [264] HiMA-MDD: A Hierarchical Multi-Agent Harness for Interpretable Multimodal Depression Detection in Clinical Interviews

**链接**: https://arxiv.org/abs/2608.21868
**作者**: Ao Chen, Xiaojiang Peng
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Depression assessment from multimodal clinical interviews requires integrating dispersed evidence from multiple symptoms into a coherent PHQ-8 profile. This process is hierarchical: relevant evidence is often sparse and context-dependent within local question-answer exchanges, multiple exchanges jointly support symptom-level judgments, and the final assessment depends on the coherence of the complete symptom profile. Existing LLM systems either process interviews holistically or distribute work across generic agent roles; neither design necessarily provides an explicit orchestration mechanism that coordinates evidence access, item-score authority, bounded feedback, and state recording across these levels. To address this gap, we introduce HiMA-MDD, a hierarchical multi-agent harness that aligns this assessment hierarchy with three agent layers. After non-agentic preprocessing constructs context-preserving multimodal QA units, Layer 1 identifies candidate QA-to-item relations and suppor

---

### [265] Consilience: Conformally Calibrated Communication Control for Hidden-Profile Multi-Agent Reasoning

**链接**: https://arxiv.org/abs/2608.20564
**作者**: Abhijith Babu, Ramneet Kaur, Vishal Pramanik, Olivera Kotevska, Nathaniel D. Bastian, Susmit Jha 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-agent LLM systems can improve reasoning by pooling diverse perspectives, but their effectiveness depends on coordinating communication, particularly in hidden-profile settings where each agent holds only part of the evidence required for a correct decision. Existing protocols, including fixed schedules, round-robin exchange, and unstructured debate, provide no guarantee that a conversational action is appropriate. We propose Consilience, an inference-time orchestration framework that both steers and certifies multi-agent communication under distributed private information. At each turn, Consilience summarizes the discussion using a compact state capturing uncertainty, disagreement, evidence gain, redundancy, and premature consensus, then selects both a communication intervention (challenge, clarify, seek evidence, or route) and an appropriate speaker. Its central contribution is a round-wise conformal calibration procedure that provides a distribution-free, finite-sample guarante

---

### [266] Small Reasoning Models are Instruction Followers in Function Calling

**链接**: https://arxiv.org/abs/2608.22472
**作者**: Yalda Taheri, Mohammad Hassan Heydari, Erfan Naaman, Afsaneh Fatemi
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Function calling represents the core capability of agentic large language models (LLMs). Existing research has focused on enhancing LLMs function-calling accuracy through fine-tuning, reinforcement learning (RL), and multi-agent frameworks, particularly for native function-calling LLMs. This work demonstrates that LLMs achieve superior accuracy in function calling in instruction-following contexts (i.e., standard user-assistant interactions) rather than a tool calling context. We introduce Instruction-Followed Function Calling (IFFC), a novel framework that decouples function-calling logic from the primary LLM and delegates it to a dedicated smaller model operating within the instruction-following paradigm. Our method consistently outperforms both native function calling (NFC) and prompt-based function calling (PFC) baselines, with particularly strong gains on reasoning-oriented LLMs. Furthermore, we demonstrate that IFFC maintains robust performance under aggressive quantization, enab

---

### [267] Clarify User Expertise: Towards Proactive Conversational Agents Tailoring Responses to User Proficiency

**链接**: https://arxiv.org/abs/2608.22266
**作者**: Zhihong Cao, Chen Huang
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In the context of information seeking, conversational agents are undergoing an evolution from reactive tools to proactive, personalized assistants. A critical aspect of this evolution is the ability to tailor strategic interactions to a user's unique needs and expectations. Unlike existing studies that focus on proactively clarifying query ambiguities, we center on clarifying the user's expertise in order to tailor responses for better user comprehension. We find that existing agents struggle to determine user expertise from queries alone, a limitation that prevents them from dynamically adapting their responses. To address this gap, we introduce PASSING to empower the agent to proactively clarify a user's expertise through targeted inquiries. This is achieved by our What-to-ask and How-to-ask strategies, induced by LLM self-play. Our extensive experiments also show our superiority. We believe that PASSING represents a crucial step towards creating more human-centric conversational age

---

### [268] SAEM: Stage-Aware Expert Management for Memory-Efficient MoE Inference in Chain-of-Thought Reasoning

**链接**: https://arxiv.org/abs/2608.21614
**作者**: Yujie Zhang, Bin Gao, Tulika Mitra
**来源**: cs.AI cs.DC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Chain-of-thought (CoT) prompting improves LLM reasoning by decomposing complex problems into intermediate steps, but its sequential nature increases decoding latency and memory usage. Mixture-of-Experts (MoE) models scale capacity through sparse expert activation, yet their full expert weights often exceed GPU memory and require costly GPU-CPU transfers. Existing runtimes treat all tokens uniformly, overlooking a key structural property of CoT traces: consecutive reasoning stages exhibit coherent and predictable expert activation patterns. Ignoring this stage-level regularity leads to inefficient caching and unnecessary data movement. We propose SAEM, a stage-aware MoE inference runtime that detects reasoning stage boundaries and exploits stage-level activation coherence to guide expert placement. SAEM combines stage-aware caching, expert-aligned token repacking, and in-situ CPU execution to reduce data transfer and kernel fragmentation. On mathematical and scientific reasoning workloa

---

### [269] Addressing the Selection Problem in Explainable AI

**链接**: https://arxiv.org/abs/2608.22356
**作者**: Claire Vlases and Katelyn Morrison
**来源**: cs.AI cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Explainable AI (XAI) research has produced a plethora of explanation techniques, yet user studies repeatedly show that available explanations are not effective in practice. We argue that, given the siloed nature of conventional XAI, users are struggling to select the appropriate XAI technique. Viewing XAI through a philosophical lens, we offer a formalization of what we call the selection problem: the systematic failure of XAI interfaces to bridge the gap between a user's natural-language uncertainty and the explanation technique that resolves it. Following a logical premise-conclusion format, we show that conventional interfaces require users to translate their uncertainty into a technique selection, a challenging prerequisite to meet. We also propose a structural solution: a multi-agent LLM orchestration tool that translates the user's query to the proper XAI explanation technique. We provide an example of how this structural solution could be instantiated to address the selection pr

---

### [270] ASTAR: Automated induction of STAndardized radiology Reporting templates from large-scale clinical free-text corpora

**链接**: https://arxiv.org/abs/2608.20369
**作者**: Xinfeng Zhang, Mingxuan Liu, Yifei Chen, Juncheng Zhu, Kasidit Anmahapong, Yiming Huang 等 (10 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Structured reporting converts free-text radiology narratives into queryable data keys, facilitating cohort assembly, longitudinal tracking, and training label generation for medical AI. The prevailing paradigm follows a two-stage pipeline: (1) constructing a reporting template, (2) extracting information to populate it. While the extraction stage has benefited from advances in large language models (LLMs), template construction remains a manual bottleneck relying on labor-intensive expert consensus that is static, difficult to scale, and may fail to capture real-world reporting diversity. We address this limitation with \textbf{\texttt{ASTAR}}, an LLM-based framework for Automated induction of STAndardized radiology Reporting templates from large-scale clinical free-text corpora. Extensive experiments on 4,215 fetal brain MRI reports from multiple centers demonstrate that the \textbf{\texttt{ASTAR}}-induced template surpasses two expert-curated templates across template coverage, infor

---

### [271] Hack-Verifiable Terminal Bench: Evaluating Reward Hacking in Terminal Tasks

**链接**: https://arxiv.org/abs/2608.22103
**作者**: Amit Roth, Ivan Bercovich, Yonathan Efroni
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As agents grow more capable and autonomous, their tendency to reward hack, satisfying a task's checks while violating its intent, becomes an increasingly important failure mode. Measuring reward hacking is itself challenging, as detection typically relies on human inspection or LLM judges, both of which can be unreliable. The hack-verifiable environments (HVE) methodology addresses this challenge by embedding detectable hacks into tasks, allowing reward hacks to be identified automatically and reliably. In this work, we adapt HVE to Terminal Bench, a leading benchmark of real-world terminal and coding tasks, and introduce Hack-Verifiable Terminal Bench (HVTB). Using HVTB, we measure reward-hacking rates across frontier models and study whether prompts with varying amounts of information on the hack can mitigate this behavior. This lets us test whether prompting can prevent not only known reward-hacking strategies, but also 'unknown unknown' exploits that the prompt does not anticipate.

---

### [272] Agentic AI for Safety-critical Multi-drone Systems: Challenges and Opportunities

**链接**: https://arxiv.org/abs/2608.21444
**作者**: Timothy Merritt, Alejandro Jarabo-Pe\~nas, Juan Bravo-Arrabal, Maria-Theresa Bahodi, Anders Lyhne Christensen
**来源**: cs.AI cs.ET cs.HC cs.RO
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-drone systems are increasingly positioned for safety-critical missions such as search and rescue (SAR) and critical infrastructure monitoring. Yet, real-world adoption remains constrained not only by autonomy performance, but by the difficulty of integrating agentic behavior into professional work: operators must understand, trust, and govern automation under uncertainty, time pressure, and accountability. This position paper synthesizes the ambitions and lessons from two ongoing efforts: NAMUR, which explores LLM-supported robot control in SAR and firefighting contexts, and PERSIST, which explores persistent drone operations for monitoring and security at critical infrastructure sites. We argue that agentic AI should be approached as a socio-technical design problem, where interfaces, oversight mechanisms, and evaluation practices are as critical as algorithms. We outline a human-centered, participatory, and iterative research approach aimed at uncovering stakeholder needs, shap

---

### [273] When "Do Not" Is Not Deny: Security Rules in CLAUDE.md vs Built-In Controls

**链接**: https://arxiv.org/abs/2608.23550
**作者**: Ting Yan
**来源**: cs.HC cs.CR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In CLAUDE.md, "do not" is a natural-language instruction that the model interprets. Claude Code's deny is a built-in control that blocks an action before the agent can take it. Both can express the same security goal, but they control the agent in different ways. We measure this gap in 481 public CLAUDE.md files. An LLM matched the extracted candidate rules against Claude Code's documented controls, and two security practitioners independently checked a sample without seeing the model's answers or each other's labels. Depending on how closely a control had to match the written rule, only about 4-16% of the retrieved security rules had a matching built-in control. Under the strictest standard the estimate was 4.4% (95% CI: 2.6-6.7%), and the two annotators agreed closely on which rules had a match. A manual review of complete files found that our extraction method captured 66.3% of eligible security rules; the reported rates therefore apply to the rules it captured. This is a usable sec

---

### [274] A Multi-Domain and Multi-Task Generative Framework with Explicit Task and Domain Conditioning for Cross-Domain Event Extraction

**链接**: https://arxiv.org/abs/2608.23235
**作者**: Siting Liang, Omar Adjali, Daniel Sonntag
**来源**: cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Event extraction aims to identify event triggers, classify event types, and extract arguments to construct structured event representations. Despite strong in-domain performance, developing models that generalize robustly across domains remains challenging due to variations in contextual expressions and event schemas. Prior unified and multi-task approaches improve in-domain accuracy but exhibit limited flexibility when applied to unseen domains. Even large language model-based methods that provide full event ontologies at inference time often underperform compared to smaller, task-specific fine-tuned models. We propose a unified multi-domain and multi-task training framework that models heterogeneous event schemas within a single model. Our approach introduces domain conditioning signals, jointly with task-specific prompts, enabling dynamic adaptation to dataset-specific schemas without requiring complete event label sets at inference time. The framework supports both pipeline and end

---

### [275] CatchBench: When Can an Agent Failure Be Caught?

**链接**: https://arxiv.org/abs/2608.22808
**作者**: Yue Zhao
**来源**: cs.LG cs.MA cs.PF
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> When can an agent failure be caught? An audit is usually limited by the record rather than by the method. CatchBench therefore puts one auditor's question to three information states: the declared configuration before a run (PRE), a growing prefix of its trace (LIVE), and the finished trace (POST). Prior benchmarks fix one of these states or vary the telemetry; to our knowledge none scores all three under one task-method interface. Each state admits different questions, so seven task contracts carry their own labels and metrics rather than one leaderboard. Four are evidential; three are Gold-derived mechanism diagnostics. The release scores 72 entrants, from rule scanners and structural models to eleven LLM judges across nine model families (GPT, Claude, Gemini, Gemma, Llama, Qwen, DeepSeek, Mistral, Nova), over 1187 declared configurations and 1162 recorded runs. Most of the arena does not order: 47 of 118 pre-declared contrasts separate, and the rest are published unresolved rather t

---

### [276] When Vocabulary Comprehension Fails Clinical Reasoning: Evaluating Therapy Bots' Safety Risks for Generation Alpha

**链接**: https://arxiv.org/abs/2608.20345
**作者**: Manisha Mehta and Virendra Mehta
**来源**: cs.CL cs.AI cs.CY
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Conversational AI systems have become informal mental health support resources for Generation Alpha (Gen Alpha, born 2010-2024), with 13.1% of U.S. adolescents (5.4 million) using generative AI for mental health advice. While these systems, from therapy apps to general chatbots, rely on large language models trained on extensive psychological literature, their safety for youth communication patterns characterized by hyperbolic language, ironic positivity, rapid semantic drift, and contextual polysemy remains unvalidated. Following multiple adolescent deaths linked to AI chatbot interactions, systematic evaluation is critical. We present two benchmarks: (1) 64 Gen Alpha mental health expressions validated by native speakers (ICC=0.72) and clinicians (kappa=0.78); (2) 75 multi-turn conversations (780 turns) with paired Standard/Gen Alpha versions. Across evaluations of LLM architectures underlying therapy apps and general chatbots - Claude, GPT-4o, Llama-3.1 - models understand 76-82% of

---

### [277] Dual-Cache Latent Space Communication between Heterogeneous Language Models

**链接**: https://arxiv.org/abs/2608.20617
**作者**: Jiyao Liu, Qi Zhang, Yaoyi Jia, Ziwen Kan, Song Wang
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-agent LLM systems split work across models, so answering often requires knowledge that sits in another agent's context: a Sharer has encoded information that a Receiver needs to complete its task. They usually communicate by exchanging text, which puts autoregressive decoding on the critical path and reduces the exchange to a discrete message written without sight of the receiver's state. Recent latent protocols instead translate the sharer's key-value (KV) cache into the receiver's: C2C supports heterogeneous models but requires both to read the same input, while LCF-X removes this shared-context requirement through position-free sharer-cache pooling. Three restrictions remain: LCF-X compresses the sharer alone, supplies the same layer-local summary to every receiver position with no joint cross-layer memory to retrieve from, and assumes matched layer count and KV geometry. We introduce XKV, which lifts all three: learned-query attention pools both caches; self-attention over re

---

### [278] On Predicting Vulnerability Severity Using In-Context Learning: An Industrial Case Study

**链接**: https://arxiv.org/abs/2608.22089
**作者**: Daniel Rodriguez-Cardenas, David Nader Palacio, Anna Schmedding, Yiyang Lu, Aadil Mallick, Bill Hudson 等 (10 人)
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Modern software systems require earlier and more scalable vulnerability severity assessment to reduce exposure to high-impact security flaws. Security analysts typically assign CVSS scores, but this manual triage does not scale with the growth of disclosed vulnerabilities and often depends on cloud LLM services that raise confidentiality concerns. This paper presents an industrial case study on predicting CVSS v3.1 scores directly from vulnerable C/C++ snippets using in-context learning with locally deployable, open-source LLMs. We compare proprietary data with the Big-Vul dataset, showing sufficiently aligned CVSS distributions to justify Big-Vul as a proxy for industrial data when constructing prompt-based testbeds. We then vary in-context configurations and model parameters, evaluating CodeLlama2-7B, CodeLlama2-13B, Mistral-7B, gpt-oss, and GPT4o-mini using mean squared error (MSE) and feasibility metrics. Our results show that medium-sized open-source code models, particularly Code

---

### [279] Beyond the Traceback: Using LLMs for Adaptive Explanations of Programming Errors

**链接**: https://arxiv.org/abs/2608.20896
**作者**: Alexandru-Radu Moraru, Shreyan Biswas, Ujwal Gadiraju
**来源**: cs.SE cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Programming error messages are critical for software development, yet they remain difficult for novice programmers to interpret. While Large Language Models (LLMs) can rewrite these errors into clearer explanations, it remains unclear whether increased readability improves objective debugging performance or how explanation styles should align with programmer skill. We present a multi-stage crowdsourced study N=103 evaluating skill-targeted, LLM-generated Python error messages. Using a custom proficiency assessment, we categorized participants by skill level and tested standard interpreter messages against two LLM-generated styles: pragmatic (action-oriented) and contingent (scaffolded explanations). We measured both objective debugging metrics (fix rate, attempts, time-to-fix) and subjective perceptions (readability, cognitive load, tone). Our results show that while LLM-rewritten messages significantly improved subjective evaluations, with pragmatic messages rated as clearer and less 

---

### [280] What AstroPT knows about galaxies, and what that can teach us about LLMs

**链接**: https://arxiv.org/abs/2608.22614
**作者**: UniverseTBD: Kshitij Duraphe, Aman Kumar, Michael J. Smith, Shashwat Sourav
**来源**: cs.LG astro-ph.IM
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Interpretability research increasingly asks when concepts emerge during training and whether linear probes recover real structure, but in language models these claims are hard to validate because language offers little ground-truth ordering of concepts or relationships among them. We propose the use of astronomical ground truth through AstroPT, a transformer trained on millions of galaxy images, as a calibration testbed. AstroPT is an LLM-like model trained within a domain where the difficulty ordering of concepts and the relations among them are known in advance. Probing frozen representations across checkpoints, layers, model sizes, and objective choices, we find that galaxy properties emerge in a fixed order that tracks their known difficulty---quantities written almost directly into the pixels (band magnitude) become decodable early in training and shallow in the network, while multiband/spectra based and inferred quantities (such as redshift and specific star formation rate) emerg

---

### [281] DynaContext: Self-Improving Dynamic Contextualization of Optimized Prompts for Heterogeneous Parameter Extraction

**链接**: https://arxiv.org/abs/2608.22014
**作者**: Joe Yu, Shibin Thomas Stanley Paul, Sven Mayer
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Automated prompt and skill optimization typically produces a single static instruction that is reused across inference instances until the next optimization cycle. However, this approach cannot adapt when the required context, constraints, and evidence vary from one instance to another. For instance, parameter extraction from electronic component descriptions breaks this assumption: resistors, capacitors, transistors, and connectors require different fields, unit constraints, and demonstrations, and each input provides a different evidence state. We introduce DynaContext, a framework that combines an offline-optimized extraction core, learned with GEPA or SkillOpt, with inference-time contextual adaptation and validation-gated self-improvement. DynaContext routes each item through internal, external, or fallback evidence paths and composes an item-specific prompt from the core, schema, evidence, unresolved fields, and validated demonstrations. Deterministic validation and an LLM judge 

---

### [282] Structured but Fragile: On the Limits of LLMs in Cybersecurity Decision-Making

**链接**: https://arxiv.org/abs/2608.20966
**作者**: Pasquale Malacaria and Yunxiao Zhang
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly used in cybersecurity workflows, yet it remains unclear whether they can perform structured security reasoning or merely rely on superficial cues and prior knowledge. We study this question in the context of defence selection over attack graphs derived from real-world threat scenarios, including ransomware, supply-chain compromise, cloud abuse, Kubernetes attacks, POS malware, and ICS/OT intrusion. Given a budget constraint, LLMs must select security controls to minimise attacker success. We compare their strategies against each other and against a game-theoretic optimization baseline used as a normative reference for structured reasoning. Our results show that LLMs exhibit conditional competence. When explicit attack-graph structure is provided, they often produce coherent strategies close to the optimization baseline. However, their capabilities are fragile. LLM behaviour becomes increasingly fragile with graph complexity and is highly se

---

### [283] When Do LLMs Replace Fine-Tuned NLU? A Decision Framework for Intent Detection in Production Conversational Systems

**链接**: https://arxiv.org/abs/2608.20371
**作者**: Carson Rodrigues, Oysturn Vas
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A common claim is that zero-shot large language models (LLMs) can replace fine-tuned NLU classifiers for intent detection. We test this claim head-to-head and find that the honest answer is: it depends on the intent space. On full ATIS and CLINC150 we compare a fine-tuned RoBERTa, a TF-IDF+logistic-regression baseline, sentence-embedding kNN, and Claude Haiku zero-shot, reporting bootstrap 95% confidence intervals and paired significance tests. When abundant in-domain labels exist, fine-tuned RoBERTa is as good or better and three orders of magnitude cheaper and faster: on ATIS it beats Claude zero-shot by 11.8 points (95.9 vs. 84.1, p<0.001). On the broad 150-intent CLINC150 schema the two are statistically tied (89.1 vs. 88.5, p=0.24): the LLM matches a fully supervised model with no training data. The LLM's advantages appear in three production-relevant regimes: out-of-scope detection (OOS recall 85.6 vs. 58.1 for RoBERTa); robustness to realistic ASR noise via a controlled text-to-

---

### [284] $Z^2$-ACT: End-to-End Verifiable Agentic Intent Control for Open 6G RAN

**链接**: https://arxiv.org/abs/2608.21049
**作者**: Sunder Ali Khowaja, Kapal Dev, George C. Alexandropoulos
**来源**: cs.CR cs.AI cs.NI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> With the progression in open and disaggregated 6G radio access networks, it is expected that the system will be able to host multi-vendors. In order to host multi-vendors, it is essential that AI-assisted control loops remain safe, verifiable, and auditable under concurrent operator intents and untrusted model inputs. The existing studies address the agentic coordination, formal intent constraints, zero-trust prompt verification and cryptographic accountability in isolation, which leaves pre-realization safety, continuous semantic verification and cross-domain audit incomplete when used individually. In this regard, we propose zero-knowledge auditable control and zero-trust verifiable agentic intent architecture ($Z^2$-ACT), which integrates the aforementioned four primitives across the non-real-time and near-real-time RICs. We encode the typed Intent Contracts as operator goals while the large language model inputs are only admitted after a practical adversarial intent check. The skil

---

### [285] Architecture as Capability Equalizer for Coding Agents

**链接**: https://arxiv.org/abs/2608.21747
**作者**: Arquimedes Canedo
**来源**: cs.SE cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based coding agents generate complete software systems from high-level descriptions, yet little is known about how the format of architecture specifications affects the quality of generated code or whether this effect depends on model capability. We present a controlled experiment comparing five informationally equivalent specification formats (informal prose, Mermaid diagrams with constraints and ADRs, OpenAPI, C4/Structurizr DSL, and TypeScript interface contracts with ArchUnit-style rules) across six models from three vendor families (Anthropic Claude, OpenAI GPT, Google Gemini). Across 90 multi-turn agent trials, specification format shows a strong format x model interaction. On the strongest models (Sonnet 4.6, GPT-5), format barely matters (quality spread 0.17-0.92). On weaker models, format produces spreads of 0.83-2.42 points, with code-proximate formats (OpenAPI, TypeScript contracts) recovering most of the capability gap. Mid-tier models can consume more tokens than front

---

### [286] HiDiffTIR: Hierarchical Difficulty-Aware Policy Optimization for Multi-Turn Tool-Integrated Reasoning

**链接**: https://arxiv.org/abs/2608.21863
**作者**: Yucan Guo, Xiaohan Wang, Miao Su, Saiping Guan, Zhongni Hou, Jiajun Chai 等 (10 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tool-Integrated Reasoning (TIR) is a fundamental capability for LLM agents to solve complex tasks by interacting with external tools iteratively. Reinforcement Learning (RL) has become the dominant paradigm for enabling this capability. However, existing approaches typically assign uniform trajectory-level advantages and treat all correct tool calls equally, ignoring the varying difficulty and learning value across trajectories and reasoning steps. This can lead to imprecise learning signals that do not adequately distinguish between trivial and challenging tool-use patterns. To address this limitation, we propose HiDiffTIR, a Hierarchical Difficulty-aware policy optimization framework for multi-turn TIR. HiDiffTIR performs difficulty-aware credit assignment at both trajectory and turn levels, enabling the policy to focus on more informative trajectories and harder reasoning steps. Notably, this fine-grained optimization is achieved without additional supervision, relying solely on gro

---

### [287] Terminal Agents: A Survey of AI Agents in Command-Line Environments

**链接**: https://arxiv.org/abs/2608.20485
**作者**: Yi Bin, Xiaoyang Yuan, Haoxi Zeng, Wencheng Ye, Wenqi Shao, Chen Qian 等 (10 人)
**来源**: cs.AI cs.SE
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model agents increasingly act through terminals, yet existing surveys disperse terminal-mediated behavior across software engineering, tool use, and computer-use research. We regard terminal agents as systems whose dominant progress-bearing action--observation loop is mediated by terminal command execution, textual feedback, and stateful environment interaction. Using terminal-mediated execution as an organizing lens, this survey establishes workload-level boundaries and connects system architecture, competence acquisition, and evaluation through a seven-dimensional terminal competence profile. Our synthesis shows that realized behavior is jointly shaped by the model, interface, harness, runtime, and environment. Executable trajectories ground learning in action consequences, verification, and recovery, whereas prevailing evaluations emphasize final outcomes and expose process quality, recovery, and governance unevenly. Bounded fixed-condition diagnostics illustrate two 

---

### [288] MLLM-Assisted Audio VOS: A 3rd Place Report for the MeViS-Audio Track, 8th LSVOS Challenge

**链接**: https://arxiv.org/abs/2608.23234
**作者**: Liangtao Shi, Jinxia Xie, Xiantao Hu, and Ting Liu
**来源**: cs.CV
**匹配关键词**: Foundation Models, MLLM
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In this technical report, we present a training-free framework for audio-guided video object segmentation, which integrates Multimodal Large Language Models (MLLMs) with SAM-based segmentation models. We decompose the task into several stages and identify suitable foundation models for each stage. Without introducing additional model training or task-specific fine-tuning, our approach leverages the strong multimodal reasoning capabilities of MLLMs to model text-visual correspondence and employs SAM-based models for accurate object mask generation. The proposed framework demonstrates the effectiveness of leveraging foundation models for audio-guided video segmentation and achieves competitive performance in the MeViS-Audio Track of the 8th LSVOS Challenge.

---

### [289] Mind the Couch! Eliciting MLLM Reasoning in Interior Design via Weak-to-Strong Task Vector Injection

**链接**: https://arxiv.org/abs/2608.23242
**作者**: Yuxuan Yang, Jingyao Wang, Luntian Mou
**来源**: cs.MM
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal Large Language Models (MLLMs) have demonstrated great performance, yet they often suffer from severe modality misalignment when confronted with densely constrained spaces for interior design. Due to the loss of high-frequency local topological details and fine-grained aesthetic shifts during visual encoding, existing MLLMs frequently hallucinate, yielding physical spatial collisions and visual aesthetic dissonance. To address this, we propose Dual-prior Activation Residual Task-vectors Injection mechanism (DART-I) for MLLMs. It shifts the paradigm from lossy text-prompting to direct latent intervention, utilizing weak-to-strong deterministic rules to anchor the causal reasoning of MLLMs for interior design. Specifically, DART-I operates in three steps: it first explicitly extracts continuous spatial distance and color typography features from images using extremely lightweight weak experts; subsequently, it transforms these deterministic priors into directional task vectors 

---

### [290] VideoChat3: Fully Open Video MLLM for Efficient and Generalist Video Understanding

**链接**: https://arxiv.org/abs/2607.14935
**作者**: Xinhao Li, Yuhan Zhu, Xiangyu Zeng, Yuhao Dong, Haoning Wu, Zhiqiu Zhang 等 (10 人)
**来源**: cs.CV
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [291] Buried in Textual Debt: Context Pruning with Visual Evidence Preservation for MLLM Agents

**链接**: https://arxiv.org/abs/2608.22963
**作者**: Yuchen Huang, Sijia Li, Jun Zhang, Yi R. Fung
**来源**: cs.AI cs.CL
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal Large Language Models (MLLMs) are increasingly deployed as multi-step agents, where explicit reasoning supports task decomposition and tool coordination but also accumulates self-generated text. Over long trajectories, this text can dominate the context and suppress visual evidence, creating textual debt. We observe that reasoning becomes redundant once task-relevant visual evidence is grounded, while stale hypotheses can misguide later inference when grounding remains uncertain. Pruning must therefore remove redundant text without discarding visual evidence. We propose SPARE, a Kullback--Leibler (KL)-guided framework for pruning accumulated reasoning in multimodal tool-use agents. SPARE uses a compact task-state summary as privileged diagnostic context. For each candidate segment, it replays the same model under the original and summary-conditioned contexts. Reverse-KL divergence from on-policy self-distillation (OPSD) then tests whether the summary sufficiently covers the 

---

### [292] UR$^{2}$-MLLM: Uncertainty-aware Revisit Reasoning in Multimodal Large Language Models for Radiology Report Generation

**链接**: https://arxiv.org/abs/2608.22217
**作者**: Yucheng Chen, Yang Yu, Jiazhou Zhou, Yufei Shi, Yongying Lan, Yichi Zhang 等 (8 人)
**来源**: cs.CV
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Radiologists generate diagnostic reports through iterative and selective revisiting of suspicious regions to refine their interpretations. Recent multimodal large language models (MLLMs) for radiology report generation (RRG) have shifted from text-only reasoning toward a ``Thinking-with-Images'' paradigm, incorporating visual evidence into the reasoning process. However, existing methods provide static visual evidence without a dynamic revisit mechanism during reasoning, neglecting how radiologists re-examine uncertain observations. To this end, we propose an Uncertainty-aware Revisit Reasoning MLLM (UR$^{2}$-MLLM) framework that dynamically revisits uncertain regions during reasoning for RRG. UR$^{2}$-MLLM is first equipped with uncertainty perception by training on an uncertainty-aware dataset. We then construct a multimodal reasoning trajectory dataset together with a detect-and-copy mechanism, which guides when and where to revisit. Finally, a visual grounding reward refines this b

---

### [293] ATP-Bench: Towards Agentic Tool Planning for MLLM Interleaved Generation

**链接**: https://arxiv.org/abs/2603.29902
**作者**: Yinuo Liu, Zi Qian, Heng Zhou, Jiahao Zhang, Yajie Zhang, Zhihang Li 等 (9 人)
**来源**: cs.AI
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [294] CBX-Bench: A Human-Aligned MLLM Council for Benchmarking Concept Bottleneck Model Explanations

**链接**: https://arxiv.org/abs/2608.15404
**作者**: Yusuf Meric Karadag, Gulay Oklan, Seref Baris Cagliyan, Umut Ozdemir, Emre Akbas
**来源**: cs.CV
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [295] Sa2VA: Marrying SAM2 with MLLM for Dense Grounded Understanding of Images and Videos

**链接**: https://arxiv.org/abs/2501.04001
**作者**: Haobo Yuan and Xiangtai Li and Tao Zhang and Yueyi Sun and Zilong Huang and Shilin Xu and Shunping Ji and Yunhai Tong and Lu Qi and Jiashi Feng and Ming-Hsuan Yang
**来源**: cs.CV
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [296] Anchoring Bias: A Persistent Fairness Backdoor Attack against MLLMs under Continual Learning

**链接**: https://arxiv.org/abs/2608.21577
**作者**: Yuyang Luo, Kai Shu
**来源**: cs.LG cs.AI
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal Large Language Models (MLLMs) are increasingly deployed in high-stakes domains where fairness is a critical safety requirement. In practice, these models are continually updated through continual learning (CL) to adapt to evolving tasks and data distributions. Prior work has shown that backdoor attacks can manipulate MLLM responses through hidden triggers, but naively implanted backdoors degrade as models undergo subsequent updates of CL. Although fairness has emerged as a central concern for MLLM deployment, whether backdoor-induced fairness violations can survive CL remains unexplored, leaving two critical questions unanswered: (1) whether a backdoor can reliably induce fairness violations in MLLMs, and (2) whether such fairness-targeted backdoors can persist through continual learning. We bridge this gap by proposing Persistent Fairness Backdoor Attack (PFBA) to inject persistent and group-specific discrimination into MLLMs. Specifically, PFBA achieves this through two no

---

### [297] Think with Structured Grounding: Perceptual Reinforcement Learning for Chart and Visual-Tabular Understanding

**链接**: https://arxiv.org/abs/2608.22429
**作者**: Changjiang Jiang, Qiannian Zhao, Lei Xin, Jinxiang Xie, Preslav Nakov, Zhuohan Xie
**来源**: cs.AI
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal Large Language Models (MLLMs) capable of thinking with images often rely on external tools for fine-grained perception. However, this reliance introduces significant inference latency and fails to effectively resolve the spatial-structural gap-a fundamental challenge in text-dense and structurally relational visuals (e.g., charts and visual tables) where strict relative spatial arrangements bind textual elements. Without external tools, standard MLLMs struggle with such fine-grained visual reasoning tasks. To address these issues, we propose Think with Structured Grounding (TwSG), a novel fine-grained image perception framework designed to internalize complex images's tool-use capabilities within the model. TwSG distills the benefits of multi-step reasoning and micro-cropping into a single efficient forward pass during inference. Specifically, we use an MLLM to identify key regions guided by ground-truth answers, and then prompt a teacher model to generate high-quality visua

---

### [298] DRAgent: Discriminative Reasoning Agent for Referring Expression Segmentation

**链接**: https://arxiv.org/abs/2608.22885
**作者**: Yujie Qi, Luyan Zhang
**来源**: cs.CV
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Referring Expression Segmentation (RES) aims to generate a pixel-level mask for the object specified by a language expression. Recent methods based on multimodal large language models (MLLMs) often rely on one-pass coordinate prediction for visual localization, which serializes continuous spatial locations as discrete text tokens and may lead to localization bias and alignment errors. To address these issues, we propose DRAgent, an MLLM-driven discriminative reasoning (DR) framework for RES. Instead of requiring the MLLM to generate localization coordinates, DRAgent first constructs a detector-generated candidate space and then uses the MLLM as a visual-semantic target discriminator. Specifically, the MLLM performs reliable target selection among potential distractors through a two-stage DR mechanism, which first screens high-recall candidates and then performs instance-wise verification. The selected target box is subsequently used as a spatial prompt for a foundation segmentation mod

---

### [299] Landmark Recognition Beyond Curated Benchmarks: Cross-Domain Evaluation of a Multi-Threshold Selective YOLO11 Ensemble on User-Generated Imagery, with a …

**链接**: https://scholar.google.com/scholar_url?url=https://www.mdpi.com/2313-433X/12/8/397&hl=zh-CN&sa=X&d=1562251043275013485&ei=FtuMaq6EHsG96rQP4OT_kA8&scisig=AIVdB-zuMt0GYN01hqqeQjjmK0Q9&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIVdB-zriNRzHNJlpJSQpNhQEFvt&html=&pos=0&folt=kw-top
**作者**: U Hudayberdiev, A Alikulov, A Israilov, M Xidirov… - Journal of Imaging, 2026
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> benchmark: the comparison is meant to bound current MLLM capability on this task, not to rank … Even the best MLLM remains about 45 points below the selective ensemble (99.24%, on … on all 131 images, we also recompute the MLLM

---

### [300] Dual-Grained Agent Memory and Shapley Context Attribution for Multimodal Agentic Learner

**链接**: https://arxiv.org/abs/2608.23268
**作者**: Jieke Wang, Tiancheng Shen, Yibo Yang and Ming-Hsuan Yang
**来源**: cs.CV
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Frontier multimodal large language models (MLLMs) deliver impressive perception yet still falter on scientific and mathematical reasoning. Parameter-level adaptation is unavailable for closed-weight or on-device backbones, and stateless prompting forfeits any compounding benefit from problems already solved. We propose \textbf{DG-Mem}, a dual-grained agentic memory framework that augments a frozen MLLM with a non-parametric, externally stored memory built once from training-time rollouts and consulted read-only at test time. Motivated by the Complementary Learning Systems (CLS) account of human memory, DG-Mem factors its store into an instance-grounded exemplar memory and a category-level schema memory of IF-THEN rules, with a transient reflection store mediating their construction so that schemas are synthesized only from abstract reflections, never from exemplar text. Two design choices distinguish DG-Mem: an online concept categorizer that grows the category space incrementally duri

---

### [301] ReFrame: Evidence-Guided Test-Time Safety Alignment in Multimodal Large Language Models

**链接**: https://arxiv.org/abs/2608.21100
**作者**: Wenzheng Jiang, Xuankun Rong, Yuanzhao Zhai, Dawei Feng, Huaimin Wang
**来源**: cs.AI
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> While multimodal large language models (MLLMs) extend model capabilities beyond text, they also make safety alignment increasingly challenging. Multimodal safety alignment methods must address cross-modal jailbreaks, safety-awareness failures, and over-sensitive refusals. However, existing methods often rely on retraining or internal-state inspection, limiting their applicability to deployed closed-source MLLMs and motivating test-time safety alignment. We analyze this setting and identify two key obstacles, utility dominance and reasoning inertia, which cause models to overlook latent risks or follow malicious reasoning trajectories. Guided by these insights, we propose ReFrame, a training-free multimodal input reframing framework where two agents share a lightweight locally deployed MLLM: the evidence-generation agent constructs complementary risk and utility evidence, and the rewrite-and-routing agent converts it into a safe proxy prompt and image-routing decision before calling the

---

### [302] Internal and External Verification Assisted Deep Clustering Network for Unsupervised Multimodal Fake News Detection

**链接**: https://scholar.google.com/scholar_url?url=https://ieeexplore.ieee.org/abstract/document/11660710/&hl=zh-CN&sa=X&d=1969685948872055960&ei=FtuMaq6EHsG96rQP4OT_kA8&scisig=AIVdB-yiW8ynd7XGvVlObZm8REqV&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIVdB-zriNRzHNJlpJSQpNhQEFvt&html=&pos=1&folt=kw-top
**作者**: F Wu, Z Sheng, Y Ji, XY Jing, GP Jiang - IEEE Transactions on Big Data, 2026
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> introduces external prior knowledge to assist MLLM in prediction and enhances the accuracy … , we are the first to introduce external prior knowledge and MLLM into the UMFND task. • We … In this paper, we design a MLLM -based external

---

### [303] Beyond Visual Similarity: Entity-Aligned Retrieval for Knowledge-Based Visual Question Answering

**链接**: https://arxiv.org/abs/2608.21450
**作者**: Hangrui Xu, Zhengxian Wu, Yunyao Yu, Zhuohong Chen, Rui Cong, Xiangwen Deng 等 (9 人)
**来源**: cs.CV
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Knowledge-Based Visual Question Answering (KB-VQA) relies on retrieving external information to answer queries involving long-tail entities. However, existing retrieval pipelines predominantly employ CLIP-style dual encoders, which prioritize surface-level visual similarity over entity-level semantic alignment. This paradigm often fails when semantically identical concepts exhibit large visual variations or when distinct entities appear visually similar. To address this, we propose KBMR, the first MLLM-based embedding retriever tailored for KB-VQA. Leveraging the robust autoregressive capabilities of MLLMs, KBMR maps images into a semantic space that better preserves concept identity. To tackle the challenge of noisy supervision in Wikipedia-scale retrieval, we introduce an MLLM-based semantic discriminator that generates continuous entity-consistency weights. These weights guide a novel continuous semantic distillation objective, enabling effective hard negative sampling and soft supe

---

### [304] Latent Ordinal Evidence, Misaligned Outputs: Inference-Time Ordinal Lens Alignment for Multimodal LLMs

**链接**: https://arxiv.org/abs/2608.20999
**作者**: Haiming Li, Yingsheng Liu, Jingmin Zhu, Siyuan Yan, Xieji Li, Jiajun Sun 等 (8 人)
**来源**: cs.CV
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal LLMs apply the language model interface to visual inputs, where ordinal regression tasks such as age estimation, image quality assessment, and disease grading require autoregressive decisions over ordered class labels. We ask whether MLLMs reliably convert internal ordinal evidence into ordered digit-token outputs. Across four ordinal benchmarks and four MLLM backbones, ordinal labels are linearly recoverable from hidden states with Spearman correlation up to 0.938, and a task-designed prompt further sharpens this structure. Yet native digit-token outputs weakly expose it: the unembedding matrix filters the ordinal direction, and the digit-token row space retains below 1.15% across all 16 model-dataset combinations, with a 16 to 77 absolute-point accuracy gap between linear-probe and native outputs. We introduce Ordinal Lens Alignment (OLA), a frozen-backbone inference-time method that trains lightweight W_S-anchored lenses on mid-to-deep decoder layers, fuses them into an o

---

### [305] MSTDualNet: multi-scale state-space dual-branch network for electroencephalography -based motor imagery decoding

**链接**: https://scholar.google.com/scholar_url?url=https://www.nature.com/articles/s41598-026-67124-6_reference.pdf&hl=zh-CN&sa=X&d=14659564778087027614&ei=FduMapeSN6HWieoPsbnhsA8&scisig=AIVdB-yD1YLMvSODvuCsBzD92Opp&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIVdB-zf-Kmv1B5RydEgEMFMJLsi&html=&pos=5&folt=kw-top
**作者**: Z Wang, L Shuo, Z Zhao, H Sun - Scientific Reports, 2026
**匹配关键词**: EEG, Motor Imagery
**相关性评分**: 5.0
**数据来源**: Google Scholar

**摘要**:

> at multiple resolutions, which are important for EEG signals containing transient event-related … framework for within-subject binary MI- EEG decoding. MSTDualNet uses a pyramid multi-scale … MI- EEG decoding and its potential as a multi-scale

---

### [306] Wireless Sensor Network for EEG -Based Epileptic Seizure Detection Using Edge Intelligence

**链接**: https://scholar.google.com/scholar_url?url=https://ieeexplore.ieee.org/abstract/document/11654752/&hl=zh-CN&sa=X&d=6496278627175333069&ei=FduMapeSN6HWieoPsbnhsA8&scisig=AIVdB-xp4dDdIz60t2Buoa1KHCM6&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIVdB-zf-Kmv1B5RydEgEMFMJLsi&html=&pos=8&folt=kw-top
**作者**: A Christina, E Hemavathi, P Kasinathan, LN Jayanthi… - 2026 9th International …, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Making use of a combination of federated and explainable machine learning in conjunction with EEG information, this study presents a privacy-compliant framework … To tell if epileptic seizures were detected based on multisensor EEGs recording, this

---

### [307] EEG Correlates of Language Proficiency: A Systematic Review with Theoretical Analysis

**链接**: https://scholar.google.com/scholar_url?url=https://are.ui.ac.ir/article_30695.html&hl=zh-CN&sa=X&d=16739920355388402244&ei=FduMapeSN6HWieoPsbnhsA8&scisig=AIVdB-yYD_Oe95y52S8_atylfLWv&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIVdB-zf-Kmv1B5RydEgEMFMJLsi&html=&pos=4&folt=kw-top
**作者**: Z Ashofteh, R Pishghadam, F Daneshvarfard… - Applied Research on …, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> The assessment of language proficiency through traditional testing methods imposes a significant resource burden in educational settings. Electroencephalography ( EEG ) provides neurophysiological evidence of language

---

### [308] Neuro-Geospatial Modelling of EEG Affective States Using Literature-Informed Environmental Context

**链接**: https://arxiv.org/abs/2608.20807
**作者**: Utsav Poudel, Jagannath Aryal, Subramaniyaswamy Vairavasundaram
**来源**: cs.AI cs.HC cs.LG
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Environmental exposures such as air pollution and greenness have been associated with affective and cognitive outcomes, but EEG and environmental datasets are rarely jointly georeferenced. We investigate whether literature-informed environmental priors can serve as an auxiliary geospatial modality for EEG-based affective-state classification when individual-level exposure data are unavailable. We combine 30-channel EEG from the EAV benchmark (42 participants, aged 20-30 years) with environmental representations derived from OpenAQ, Sentinel-2, Sentinel-5P, and OpenStreetMap data for Astana. A dual-tower architecture combines EEG-Conformer representations with a graph-based environmental encoder. Because the datasets are not co-registered, environmental context is treated as a literature-informed prior rather than measured exposure. Subject-level repeated splits, permutation and label-shuffling controls, dose-response reversal, and domain-shift experiments distinguish architecture-level

---

### [309] Alpha-Theta EEG Rhythms as Neurophysiological Predictors of Impact of Yoga on Glycemic Regulation in Diabetes

**链接**: https://scholar.google.com/scholar_url?url=https://www.researchgate.net/profile/Krishna-Dwivedi-8/publication/412627719_Alpha-Theta_EEG_Rhythms_as_Neurophysiological_Predictors_of_Impact_of_Yoga_on_Glycemic_Regulation_in_Diabetes/links/6a854398dc2adc699beeee89/Alpha-Theta-EEG-Rhythms-as-Neurophysiological-Predictors-of-Impact-of-Yoga-on-Glycemic-Regulation-in-Diabetes.pdf&hl=zh-CN&sa=X&d=15931806829554084104&ei=FduMapeSN6HWieoPsbnhsA8&scisig=AIVdB-zhPv1wO3KDdAkzFvQxeZeJ&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIVdB-zf-Kmv1B5RydEgEMFMJLsi&html=&pos=9&folt=kw-top
**作者**: D Krishna - SVOA Neurology
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> ( EEG ) rhythms as … EEG with complementary biomarkers such as heart rate variability, glycemic indices, and stress hormones to establish comprehensive neuro-metabolic profiles and facilitate personalized therapeutic strategies. Emerging applications of

---

### [310] … abnormal theta oscillation-default mode network functional connectivity and internet addiction behavior in adolescent depression patients: a resting-state EEG study

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S0306460326002509&hl=zh-CN&sa=X&d=759417902522911583&ei=FduMapeSN6HWieoPsbnhsA8&scisig=AIVdB-xZ7Ao6UPERtGjKVseqxzV1&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIVdB-zf-Kmv1B5RydEgEMFMJLsi&html=&pos=3&folt=kw-top
**作者**: Y Wen, Y Qi, J Guo, W Cai, D Qiao, Q Guo 等 (9 人)
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Background Major depressive disorder (MDD) and internet addiction (IA) are closely linked in adolescents, yet the neurobiological mechanisms underlying their relationship remain unclear. This study aimed to explore the role of abnormal

---

### [311] Prior-Informed Normative EEG Scoring for Alzheimer's Detection: Framework and Cross-Paradigm Boundary Analysis

**链接**: https://scholar.google.com/scholar_url?url=https://ieeexplore.ieee.org/abstract/document/11645202/&hl=zh-CN&sa=X&d=7337348497094208012&ei=FduMapeSN6HWieoPsbnhsA8&scisig=AIVdB-yJtGNQRaMQqX_Qgu0hVM7m&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIVdB-zf-Kmv1B5RydEgEMFMJLsi&html=&pos=7&folt=kw-top
**作者**: H Rengan, AM Valiyev, RB Zhu, C Do, EY Fu - 2026 IEEE 50th Annual Computers …, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> EEG -based screening for Alzheimer's disease (AD) is attractive in principle but not deployed in practice, largely because end-to-end classifiers trained on small clinical cohorts generalize poorly. We propose a prior-weighted deviation scorer that fits

---

### [312] ViTexSZ: Heterogeneous Vision-Text Knowledge Distillation for EEG Seizure Detection

**链接**: https://arxiv.org/abs/2608.21445
**作者**: Chenxi Liu, Mingzhao Li, Yicong Liu, Hao Miao, Hongyuan Zhang, Ziyi Chen 等 (7 人)
**来源**: cs.CV
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Automated seizure detection from electroencephalography (EEG) is essential for continuous neurological monitoring, particularly for subclinical epileptic seizures that may exhibit only subtle electrographic changes. Existing time-series methods are often designed for fixed EEG channel configurations, thereby limiting their applicability to heterogeneous EEG recordings with irregular channel layouts. Although visual and language modeling offer promising alternatives, aligning heterogeneous EEG representations with clinical semantics remains challenging. We introduce ViTexSZ, a heterogeneous Vision-Text knowledge distillation framework for EEG seizure detection. ViTexSZ converts EEG recordings into structured waveform images and introduces a query-based multi-channel alignment module that maps source-dependent visual features into a unified token space. A heterogeneous teacher further integrates the aligned EEG representations with clinical prompts through a multimodal large language mod

---

### [313] An Explainable and Scalable EEG Framework for Major Depressive Disorder Detection and Severity Staging Through Signal Reconstruction, Channel Optimization …

**链接**: https://scholar.google.com/scholar_url?url=https://www.jidmis.org/index.php/jidmis/article/download/1441/540&hl=zh-CN&sa=X&d=2005507280859609750&ei=FduMapeSN6HWieoPsbnhsA8&scisig=AIVdB-yFq9c5g_xFq0U1ixznBL05&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIVdB-zf-Kmv1B5RydEgEMFMJLsi&html=&pos=6&folt=kw-top
**作者**: S Dhekane - Journal of Intelligent Decision Making and Information …, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> In the modern world, Major Depressive Disorder (MDD) remains a serious global issue affecting mental health. Therefore, a reliable, non-invasive and scalable method for MDD diagnostics should be found. Analysis of EEG recordings shows

---

### [314] Agentic AI for EEG -Based Brain-Computer Interfaces: A Review of Methods, Systems, and Applications

**链接**: https://scholar.google.com/scholar_url?url=https://ieeexplore.ieee.org/abstract/document/11645552/&hl=zh-CN&sa=X&d=11214925541170515987&ei=FduMapeSN6HWieoPsbnhsA8&scisig=AIVdB-xbkVyuqBtW8yEj1taJ918L&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIVdB-zf-Kmv1B5RydEgEMFMJLsi&html=&pos=2&folt=kw-top
**作者**: M Rabbani, R Amyeen, MM Hossain, M Rafid, I Iqbal… - 2026 IEEE 50th Annual …, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Brain Computer Interfaces (BCIs) based on electroencephalogram ( EEG ) signals are an effective means of enabling direct brain-to-… in the context of EEG -based BCIs. This paper aims to bridge the gap by providing a comprehensive review of

---

### [315] HD-tDCS modulation of the DLPFC-HPC-EC pathway to enhance working memory in schizophrenia: a TMS- EEG Study

**链接**: https://scholar.google.com/scholar_url?url=https://www.nature.com/articles/s41380-026-03835-6&hl=zh-CN&sa=X&d=3490718632429701366&ei=FduMapeSN6HWieoPsbnhsA8&scisig=AIVdB-wnTVs6QYyd1WBygp9S_rVF&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIVdB-zf-Kmv1B5RydEgEMFMJLsi&html=&pos=1&folt=kw-top
**作者**: X Li, M Chen, E Tang, J Fu, Z Chen, C Zhang 等 (9 人)
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> - EEG to measure changes in excitability and connectivity across the DLPFC, hippocampus (HPC), and entorhinal cortex (EC). Active HD-tDCS significantly improved WM task accuracy (p < 0.001) and reduced reaction times (p < 0.01)

---

### [316] A Unified Foundation Model for Heterogeneous EEG Signal Modeling via Language-Aligned Semi-Supervised Learning

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S0893608026010026&hl=zh-CN&sa=X&d=12923835164202409562&ei=FduMapeSN6HWieoPsbnhsA8&scisig=AIVdB-w4H648f5yLSoA2YjogbVAV&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIVdB-zf-Kmv1B5RydEgEMFMJLsi&html=&pos=0&folt=kw-top
**作者**: Z Ye, M Jiang, J Zhu, H Zheng, M Rong, F Deng - Neural Networks 等 (7 人)
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> USEA, a unified semi-supervised EEG –language alignment approach for heterogeneous EEG signal modeling that formulates EEG modeling as a … We evaluate USEA on nine public EEG datasets spanning diverse paradigms and

---

### [317] ReMAP: Self-supervised learning to unveil brain representations and vulnerability

**链接**: https://arxiv.org/abs/2608.22042
**作者**: Jade Perdereau, Virginie Loison, Kanssa El Ayeb, Louis Gervais, Melvin Berto Strouc, Fabrice Vall\'ee 等 (8 人)
**来源**: cs.LG
**匹配关键词**: EEG
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> General anesthesia offers a rare opportunity to observe the human brain under a standardized, controlled perturbation. Yet intraoperative electroencephalography (EEG) is almost always reduced to a single proprietary depth index, collapsing a rich trajectory into one number and discarding how a brain moves between states. Here we ask whether the geometry of that trajectory, not merely the depth it reaches, carries clinically meaningful information. Using similarity-based self-supervised learning on raw, two-electrode frontal EEG, with no labels, we place each recording within a low-dimensional space in which anesthetic depth becomes one readable axis while the shape of a patient's path encodes additional structure. We validate the representation across two cohorts and two acquisition systems totaling more than 1,000 patients. Depth of anesthesia is predicted accurately (BIS mean absolute error = 3.2, R2 = 0.82), and in the sparse-montage setting our compact ( 68k parameter) model remain

---

### [318] NeuroStrata: An Electroencephalographic Connectivity-Aware Deep Representation Learning Framework for Dynamic Brain Network Analysis of Mental Stress

**链接**: https://arxiv.org/abs/2608.20354
**作者**: Sayantan Acharya, Hamzeh Asgharnezhad, Abbas Khosravi, Douglas Creighton, Roohallah Alizadehsani and U Rajendra Acharya
**来源**: q-bio.NC cs.AI cs.LG
**匹配关键词**: EEG
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> This study introduces NeuroStrata, a connectivity-aware deep representation learning framework for EEG-based mental stress analysis using Time-Varying Partial Directed Coherence (TV-PDC). Unlike conventional EEG classification approaches based on static features, NeuroStrata models the temporal evolution of frequency-specific directed connectivity across distributed brain regions. EEG signals from the 32-channel SAM 40 dataset recorded during mental arithmetic tasks were used to generate TV-PDC connectivity maps. These maps were processed using pretrained Convolutional Neural Networks (CNNs) and Vision Transformers (ViTs) to extract deep connectivity embeddings, which were subsequently classified using lightweight machine learning models. Experimental results demonstrate that beta-band connectivity provides the highest discriminative capability, achieving a peak accuracy of 97.3% using the LAION-CLIP-ViT-L14 backbone with a Support Vector Machine classifier, while alpha-band connectivi

---

### [319] Retrieval-aligned Tabular Foundation Models Enable Robust Clinical Risk Prediction in Electronic Health Records Under Real-world Constraints

**链接**: https://arxiv.org/abs/2604.01841
**作者**: Minh-Khoi Pham, Thang-Long Nguyen Ho, Thao Thi Phuong Dao, Tai Tan Mai, Minh-Triet Tran, Marie E. Ward 等 (10 人)
**来源**: cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [320] A Survey on Human-AI Collaboration with Large Foundation Models

**链接**: https://arxiv.org/abs/2403.04931
**作者**: Vanshika Vats, Marzia Binta Nizam, Minghao Liu, Ziyuan Wang, Richard Ho, Mohnish Sai Prasad 等 (10 人)
**来源**: cs.AI cs.CL cs.HC
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [321] Attributing Preprocessing Invariance in Spectral Foundation Models

**链接**: https://arxiv.org/abs/2608.14227
**作者**: Dongjun Wei, Hongyi Wu, Yinuo Zou
**来源**: cs.AI cs.CE cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [322] CellPath-Bench: A Multidimensional Benchmark for Whole-Slide Cellular Representations in Pathology Foundation Models

**链接**: https://arxiv.org/abs/2608.21060
**作者**: Bokai Zhao, Yiyang Zhang, Hanqing Chao, Yawei Ma, Long Bai, Tai Ma 等 (9 人)
**来源**: cs.AI cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Pathology foundation models (PFMs) are increasingly used as general-purpose backbones, yet existing benchmarks cannot systematically diagnose their whole-slide cellular representation capabilities, including the decodability of cell-type information and the transferability of such information across tissue sections, datasets, and anatomical organs. We introduce CellPath-Bench, a cellular-resolution benchmark that evaluates frozen PFMs themselves. Following quality control of 52 candidate Xenium datasets, we construct a panel of 25 spatially aligned H\&E--Xenium tissue sections spanning 11 organs and 7,079,283 cells, harmonized into fine- and coarse-grained taxonomies. CellPath-Bench samples frozen WSI feature maps at registered nuclear coordinates and evaluates them using standardized multiclass linear probes. Cell Representation Advantage (CRA) measures the within-section advantage of nucleus-anchored representations over patch-level mean pooling, while Cell Representation Transferabi

---

### [323] Learning to Orchestrate Vision Foundation Models for Multi-Task Dense Prediction

**链接**: https://arxiv.org/abs/2606.15765
**作者**: Donghyun Han, Yuseok Bae, Jung Uk Kim, Hyung-Il Kim
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [324] Foundation Models for Partial Causal Identification

**链接**: https://arxiv.org/abs/2608.20841
**作者**: Alexis Bellot, Anish Dhir
**来源**: cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> This paper investigates the development of causal foundation models for bounding the effect of interventions and counterfactuals from observational data. We show that a canonical prior can be defined with full support over the space of structural causal models with discrete observables. With this canonical prior, we translate the problem of bounding counterfactuals into that of learning distributions over functions that map data (and possibly structural assumptions) to a causal query of interest. This extends the promising causal foundational modelling paradigm to the estimation of partially-identifiable causal effects, i.e., under unobserved confounding, where multiple values are equally compatible with the observed data and prior structural assumptions.

---

### [325] Semantically Compatible Knowledge Distillation for Cross-Domain Object Detection with Vision Foundation Models

**链接**: https://arxiv.org/abs/2608.20916
**作者**: Qifeng Zhang, Ting Xiang, Zeyuan Bai, Changjian Chen
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Vision foundation models (VFMs) offer strong generalization capabilities for domain-adaptive object detection (DAOD). However, existing VFM-based methods overlook the spatial-scale discrepancy between teacher and student feature maps, resulting in semantic incompatibility that weakens both feature alignment and pseudo-label learning. Moreover, domain shift can cause source-trained VFM teachers to miss target-domain objects, limiting the quality of their pseudo-labels. To address these issues, we propose the Semantic Localization-Enhanced Teacher (SLE-T), a semantically compatible knowledge-distillation framework built around a lightweight SLE Adapter for DINOv2. SLE Adapter injects pretrained local-texture priors into DINOv2 to improve cross-domain recognition and reformulates its features into dense representations that are spatially and semantically compatible with the student detector. SLE-T transfers the resulting teacher knowledge through either pseudo-label learning or feature al

---

### [326] Do Time-Series Foundation Models Pay Off for Industrial Monitoring? A Cost-Aware Empirical Study

**链接**: https://arxiv.org/abs/2608.22968
**作者**: Guan-Hua Wen, Kuan-Yu Chen
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Industrial monitoring models must detect operationally relevant deviations while satisfying target-specific data, calibration, and resource constraints. Time-series foundation models (TSFMs) promise reusable representations and zero-shot forecasts, yet evidence for their deployment value remains mixed when task definitions are heterogeneous and lightweight baselines are competitive. This work presents a protocol-aware empirical assessment across three settings: a C-MAPSS degradation-risk proxy, normal-only training for anomalous-sound detection on MIMII, and BDG2 forecasting-residual diagnostics with synthetic target perturbations. We assess classical one-class methods, compact neural autoencoders, residual forecasters, MOMENT-small, Chronos-T5, and TimesFM 2.5 in terms of anomaly-ranking performance, risk-horizon sensitivity, residual forecasting and perturbation sensitivity, and local implementation cost. Across 100 C-MAPSS engines evaluated out of fold, TCN-AE reaches fold-weighted 

---

### [327] A Distributional Robustness Margin For Pathology Foundation Models

**链接**: https://arxiv.org/abs/2607.25497
**作者**: Cl\'ement Grisi, Jeroen van der Laak, Geert Litjens
**来源**: cs.CV cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [328] Benchmarking the Robustness of Foundation Models for Mammography under Domain Shift

**链接**: https://arxiv.org/abs/2607.10358
**作者**: Giang Nguyen, Raghav Mehta, Emma A.M. Stanley, Tian Xia, Thi Hao Nguyen, Hieu Pham 等 (7 人)
**来源**: cs.CV cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [329] Mint-Agent: Introducing Finance-Native Agentic Foundation Models

**链接**: https://arxiv.org/abs/2608.16386
**作者**: Mint-Agent Team, Kun Wang, Gavin Zhang, Yaze Geng, Lei Tang, Yaoyang Yi 等 (10 人)
**来源**: cs.CL cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [330] Retrieval-Augmented Visual Prompting: Guiding Foundation Models in Two-Photon Imaging

**链接**: https://arxiv.org/abs/2608.21970
**作者**: Salvatore Calcagno, Marco Finocchiaro, Giovanni Bellitto, Daniela Giordano, Concetto Spampinato, Federica Proietto Salanitri
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Two-photon calcium imaging presents a challenging setting for foundation models: image appearance varies substantially across recordings and experimental conditions, annotations are scarce, and rapid adaptation is often needed. Rather than adapting model weights through fine-tuning, we ask whether a foundation model can be guided at inference time by injecting external visual memory directly into its input. We implement this idea with SAM 3 and introduce Retrieval-Augmented Visual Prompting (RAVP), a framework in which each target tile is augmented with a retrieved annotated exemplar whose bounding box is used as a concept prompt. RAVP turns retrieval into a form of visual prompting and enables adaptation through input design alone. We study multiple exemplar selection strategies, including fluorescence-guided heuristics and a lightweight recall predictor trained to estimate which exemplar is most informative for a target tile. Experiments on the Allen Brain Observatory show that exemp

---

### [331] Trojaning the Alignment: Stealthy Backdoor Attacks against Graph Foundation Models

**链接**: https://arxiv.org/abs/2608.20991
**作者**: Minhua Lin, Zhicheng Gao, Yilong Wang, Hanqing Lu, Xiang Zhang, Suhang Wang
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Graph Foundation Models (GFMs) on text-attributed graphs (TAGs) align graph representations with language semantics to support transferable graph learning. Despite these advantages, the backdoor vulnerability of GFMs on TAGs remains insufficiently understood, especially under graph-language alignment, where graph and text representations are trained to constrain each other in a shared semantic space. Existing backdoor attacks mainly target either the graph side or the text side, treating the two modalities independently. This makes direct adaptation ineffective: graph-only triggers can be constrained by clean text semantics, while text-only triggers alter the language view but do not directly shift the graph representation being aligned and scored. TAGs also impose a stealth challenge because triggers are exposed as both node text and local graph structure, making incoherent trigger attributes or anomalous subgraphs easy to inspect or filter. In this paper, we propose STAG, a stealthy 

---

### [332] Tabular foundation models for non-tabular tasks

**链接**: https://arxiv.org/abs/2608.22594
**作者**: Goran Nakerst, John Brennan, Wouter Beugeling, Masudul Haque
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tabular foundation models (TFMs) have recently emerged as a promising paradigm for machine learning on tabular data, offering the ability to generalize across datasets without task-specific training. Since many machine learning datasets can be represented as tables, this raises the question: does TFM capability extend beyond tasks traditionally regarded as tabular? We address this question by using TabPFN v3 on three non-tabular classification problems: handwritten digit recognition on MNIST, language identification of French and German words, and image classification on Tiny ImageNet. In each case, the original data are represented as rows of a table and classification is formulated as prediction of a missing label. We evaluate performance as a function of the number of context samples provided to the pretrained model, with no additional training or fine-tuning. Despite having no explicit access to the spatial or sequential structure characterizing the data, TabPFN v3 in some cases ac

---

### [333] Scaling Electronic Health Record Foundation Models for Population Health Management

**链接**: https://arxiv.org/abs/2506.00209
**作者**: Liwen Sun, Hao-Ren Yao, Ophir Frieder, Xiang Qian, Chenyan Xiong
**来源**: cs.LG cs.CL
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [334] Aristotelian Manifolds: Leveraging Platonic Perceptual Features for Backpropagation Free Rapid Concept Learning

**链接**: https://arxiv.org/abs/2608.20682
**作者**: Michael Karnes, Alper Yilmaz
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> This paper formalizes and systematically characterizes Aristotelian Manifolds, a generalized structural framework built upon the Platonic Representation Hypothesis. We position high-capacity foundation models as universal perceptual filters and conduct a comprehensive layer-wise investigation to map how knowledge is functionally synthesized within these latent subspaces. Across diverse architectural paradigms and multi-domain datasets, we rigorously chart the interplay between network depth, dimensionality reduction, and distance metrics. Our characterization reveals that semantic maturation does not follow a singular, monotonic path; instead, different data domains exhibit highly distinct geometric response profiles, characterized by intermediate mound-like peaks for specialized clinical modalities and sigmoidal plateaus for natural visual tasks. By profiling the exact coordinates where these manifolds achieve peak representational efficiency, we establish a predictable taxonomy for l

---

### [335] NemoSplat: Feed-Forward 4D Gaussian Splatting for Media-Aware Underwater Reconstruction

**链接**: https://arxiv.org/abs/2608.22888
**作者**: Xiaopeng Guo, Wai Chung Tse, Yipeng Zhu, Hanwen Zhang, Huajian Huang, Sai-Kit Yeung
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reconstructing photorealistic scenes in unconstrained underwater environments remains challenging due to severe media-induced light scattering and unpredictable dynamic objects. Recent feed-forward visual foundation models have demonstrated remarkable capabilities in generalized novel view synthesis and tracking. However, when directly applied to aquatic videos, optical attenuation and motion interference fatally corrupt their feature aggregation, leading to severe tracking and reconstruction failures. To overcome these limitations, we present NemoSplat, the first feed-forward 4D Gaussian Splatting framework tailored for media-aware dynamic reconstruction directly from uncalibrated marine videos. Beyond providing robust estimations of camera poses and dense scene depth, we devise a Promptable Dynamic Disentangler that utilizes a confidence-aware fusion strategy of learned dynamic probabilities and optional semantic text priors, effectively isolating massive transient entities. Furtherm

---

### [336] Generating Multi-view Adversarial Examples for Visual Geometry Grounded Transformer

**链接**: https://arxiv.org/abs/2608.20748
**作者**: Qi Song and Ziyuan Luo and Haoliang Han and Renjie Wan
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The Visual Geometry Grounded Transformer (VGGT) enables unified feed-forward 3D reconstruction from multi-view images. However, deploying such a high-performance model may expose critical security vulnerabilities. Traditional adversarial perturbations require costly per-scene optimization, while Universal Adversarial Perturbations (UAPs) rely on a single static pattern and fail to effectively attack VGGT. To address these limitations, we propose \textbf{MVAP-G}, a multi-view adversarial perturbation generator that produces imperceptible consistent perturbations across multiple views in a single feed-forward pass. To ensure perturbation consistency across diverse scenes, we design a cross-view adversarial alignment mechanism to process multi-view images. Experiments demonstrate that MVAP-G significantly degrades VGGT performance without iterative optimization during inference. This work pioneers multi-view adversarial attacks on 3D foundation models, uncovering severe vulnerabilities an

---

### [337] MetaCaster: Meta-Harness-Optimized Agent for End-to-End Few-Shot Learning of Lightweight Time Series Forecasters

**链接**: https://arxiv.org/abs/2608.23473
**作者**: ChengAo Shen, Wenchao Yu, Fangyu Wu, Dongjin Song, Hanghang Tong, Dongsheng Luo 等 (9 人)
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Time series forecasting (TSF) is evolving toward multimodal and agentic settings, yet using foundation models remains uneconomical in resource-constrained scenarios, where compact, specialized forecasters are more desirable. However, lightweight forecasters typically require substantial training data, limiting their use in domains with scarce, slowly accumulated, or privacy-sensitive time series. To address this dilemma, we investigate the challenging problem of few-shot learning for lightweight forecasters. We propose MetaCaster, a meta-harness-optimized multi-agent framework that uses agentic data generation to automatically train specialized lightweight forecasters from only a few examples and textual contexts. Our work highlights a new TSF paradigm in which agents act not as forecasters but as intermediary engineers that prepare efficient, task-specific forecasters for deployment. Experiments on 18 datasets, 23 state-of-the-art lightweight forecasters, and 14 baselines demonstrate 

---

### [338] Stream3Dv2: Geometric-Semantic Fusion Enhanced Streaming Zero-Shot 3D Scene Understanding

**链接**: https://arxiv.org/abs/2608.21136
**作者**: Jie Xu and Na Zhao
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recently, open-vocabulary zero-shot 3D scene understanding using vision foundation models has emerged as a promising alternative to data-intensive supervised methods. However, deploying these models in real-world scenarios is severely hindered by their inability to efficiently handle streaming RGB-D inputs and their inherent vulnerability to noise 2D segmentation masks. To address these critical limitations, we propose Stream3Dv2, a novel training-free framework designed for robust streaming 3D perception. Stream3Dv2 processes sequential data through an original nested local-to-historical architecture, capturing multi-view consistency while circumventing the high computational overhead so as to support timely responses. At its core, we introduce a comprehensive geometric-semantic fusion mechanism that resolves geometric noise and semantic ambiguity by explicitly utilizing semantic guidance and formulating 3D segmentation as solving point-and-set merging and partitioning problems. Furth

---

### [339] Large-Small Model Collaboration for Zero-Shot Surgical Phase Recognition

**链接**: https://arxiv.org/abs/2608.22879
**作者**: Yiyi Zhang, Ying Zheng, Wenxin Fan, Yu Zhu, Yuchen Yuan, Litao Zhao 等 (8 人)
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Task-specific lightweight models for surgical phase recognition excel at capturing temporal dynamics but generalize poorly under domain shift. Conversely, surgical foundation models (FMs) offer superior transferability via large-scale pretraining, yet their lack of explicit temporal modeling often yields temporally inconsistent predictions, leading to degraded performance. To exploit the complementary strengths of both paradigms, we propose \textbf{La}rge-\textbf{S}mall \textbf{T}emporal adaptation (\textbf{LaST}), a novel large-small collaborative framework that enables zero-shot adaptation to unseen clinical domains. In LaST, the FM initiates the pipeline by generating frame-level phase priors that serve as initial weak supervision. To effectively utilize these noisy phase priors, we introduce an iterative temporal refinement scheme that integrates dynamic quality control to filter reliable predictions and dual-model cross-learning to mitigate confirmation bias. Simultaneously, the l

---

### [340] Semantics or Structure? Auditing Text Sensitivity in Multimodal Time-Series Forecasting

**链接**: https://arxiv.org/abs/2608.22321
**作者**: Karthik Sridhar, Atharva Gupta, Nishant Pradhan, Murari Mandal, Dhruv Kumar, Saurabh Deshpande
**来源**: cs.CL
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal time-series forecasting has emerged as a promising paradigm in which natural-language context is expected to improve predictive performance. Recent multimodal foundation models, including Aurora, as well as early- and late-fusion approaches such as MM-TSFlib and TaTS, report substantial gains over unimodal baselines on the Time-MMD benchmark, attributing these improvements to textual information. However, whether these models are actually sensitive to the semantic content of the text remains unverified. We address this question through controlled text perturbations, attribution analyses, and probes of Aurora's text pathway. On Time-MMD, swapping each row's text for any other real text (empty, constant, within-domain shuffled, or cross-domain) moves mean MSE by less than $0.5\%$ on all three architectures. The improvement reported in the literature is recovered when a co-shipped numeric column is removed without touching text. We conclude that, on this benchmark and within th

---

### [341] Mol-JEPA: A multimodal Joint Embedding Predictive Architecture for Molecules

**链接**: https://arxiv.org/abs/2608.22642
**作者**: Florian Rottach, Sebastian Schieferdecker, William Rudman, Randall Balestriero, Carsten Eickhoff
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Despite recent advances in molecular foundation models, several limitations remain, such as chemically invalid augmentations, modality collapse, and incomplete representation of biochemical environments. To address these challenges, we present \textbf{Mol-JEPA}, a scalable framework for learning molecular world models. Rather than relying on suboptimal molecular perturbations, our model uses modality masking to exploit information from molecular structures, cellular phenotypes, binding affinities, ADMET profiles, quantum chemistry simulations and other drug discovery data. Across various benchmarks, we show that the representations learned by Mol-JEPA deliver strong performance, demonstrating the value of incorporating biochemical context through latent space prediction.

---

### [342] Just Noticeable Difference Modeling for Token Compression in Vision-Language-Action Models

**链接**: https://arxiv.org/abs/2608.21247
**作者**: Zhuoyuan Li, Rui Zhao, Jin Wang, Hanwei Zhu, Cong Zhang, Giuseppe Valenzise 等 (8 人)
**来源**: cs.CV cs.RO
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Token compression has become a key technique for reducing the inference cost of large foundation models, with approaches such as token pruning and KV-cache reuse widely adopted in vision-language models and recently explored for embodied agents. In embodied agents, tokens not only support perception and semantic understanding but also directly affect latency-sensitive closed-loop robot action prediction. Existing schemes typically guide compression using redundancy or importance cues, such as visual similarity, attention scores, and saliency. However, these cues only indirectly measure the key factor for safe compression: how much a token can change before causing an unacceptable deviation in downstream actions. This receiver-dependent tolerance is closely related to the principle of just noticeable difference (JND). Classical JND characterizes signal tolerance in the human visual system, while machine-oriented JND extends this concept to downstream machine responses. Building on this 

---

### [343] When Adaptation Hurts: Connecting Representational Drift to OOD Failures in MedSAM Fine-Tuning

**链接**: https://arxiv.org/abs/2608.21300
**作者**: Marko Haralovi\'c, Sounic Akkaraju, Carlo Baretta, Vasil Zapryanov, Alexia Briassouli
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Foundation models for medical image segmentation, like prompt-based MedSAM, generalize well across domains and modalities, often in zero or few-shot setups. However, their performance depends on the quality of prompts and the adaptation of the models to custom datasets. This work systematically examines how MedSAM generalizes across diverse medical imaging benchmarks, with six adaptation strategies: full-model and encoder-only LoRA, shallow and deep visual prompt tuning (VPT), and decoder-only and full fine-tuning. Models are trained on the International Skin Imaging Collaboration Challenge (ISIC 2018) dataset and evaluated under clean and increasingly noisy prompts on IN and Out-of-Distribution (OOD) datasets: close-OOD PH2 (dermoscopy), far-OOD BUSI (Breast Ultrasound Images Dataset) and CBIS-DDSM (Curated Breast Imaging Subset of the Digital Database for Screening Mammography). We show that adaptation improves performance on IN and close-OOD data but often reduces performance on far

---

### [344] Object-Uni: A Unified Model for Object-Centric Spatial Understanding and Controllable Generation

**链接**: https://arxiv.org/abs/2608.22757
**作者**: Mining Tan, Yinuo Wang, Ziqi Zhou, Weize Quan, Sifei Li, Jingdong Chen 等 (9 人)
**来源**: cs.CV cs.AI
**匹配关键词**: Unified Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Unified models for visual understanding and generation have made rapid progress, yet they still lack the ability to understand and manipulate the spatial states of object instances. Existing models can describe objects in natural language, but they struggle to precisely represent continuous object poses and generate geometrically consistent images under target viewpoints. To mitigate this, we propose \emph{Object-Uni}, a unified model for object-centric spatial understanding and controllable generation. Specifically, we formulate object-centric spatial intelligence as a unified problem connecting pose perception, spatial reasoning, pose-conditioned generation, and object-centric novel view synthesis. We treat object pose as an explicit geometric variable shared by understanding and generation, rather than merely a prediction label or control signal. To make pose usable by multimodal large language models, we propose a viewpoint-based orientation abstraction that maps orientation into s

---

### [345] RIBOSPAN: A Long-Context RNA Foundation Model for Versatile RNA Modeling

**链接**: https://arxiv.org/abs/2608.22849
**作者**: Ziyuan Wang, Bohao Tang, Fei Zhang, Shuo Han, Pengfei Liu
**来源**: cs.LG q-bio.GN
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Full-length RNAs, particularly messenger RNAs, often exceed the context lengths used to pretrain existing RNA foundation models, limiting complete-transcript modeling at single-nucleotide resolution. We present RIBOSPAN, a 1.61-billion-parameter bidirectional RNA foundation model natively pretrained with context lengths up to 10,240 nt. RIBOSPAN combines dense bidirectional self-attention, single-nucleotide tokenization, and attention-isolated sequence packing to enable high-resolution modeling of complete long RNAs. We evaluate the model through nucleotide reconstruction, a controlled long-context representation benchmark, and frozen RNA-type representation analysis. Native 10K pretraining preserves strong reconstruction at 10,240 tokens, while continued pretraining with 40% masking improves recovery under heavy corruption while preserving representation quality. The long-context benchmark further shows that native 10K models maintain strong contextual responsiveness and context-speci

---

### [346] Mitigating Speaker Leakage in Cascaded Multi-talker ASR with Diarization-based Transcript Correction

**链接**: https://arxiv.org/abs/2608.22196
**作者**: Hermann Yepdjio Nkouanga, Minwei Luo, Maggie Wigness, Suresh Singh
**来源**: eess.AS cs.CL
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> While cascaded multi-talker ASR (MT-ASR) leverages state-of-the-art foundation models, its performance is often capped by speaker leakage during separation. Prior correction strategies primarily focus on lexical re-labeling for speaker attribution. We propose a complementary pruning-based paradigm that robustly identifies and removes leakage artifacts. Our method utilizes a pre-trained speaker diarization model as a multimodal verifier to prune transcribed segments satisfying a tripartite consensus of temporal containment, lexical cross-validation, and temporal alignment. Results on LibriMix, LibriSpeechMix, and the AMI Meeting corpus show our algorithm consistently reduces cpW ER across diverse overlap conditions. Specifically, on subsets with high speaker leakage, our method achieves relative cpW ER reductions of up to 29%, highlighting its effectiveness in enhancing the reliability of cascaded MT-ASR transcripts in complex acoustic environments.

---

### [347] M2Depth: Unifying Monocular Depth Foundation Priors with Multi-View Stereo

**链接**: https://arxiv.org/abs/2608.20788
**作者**: Byeonggwon Lee, Sanggi Lee, Siwoo Lee, Khang Truong Giang, and Soohwan Song
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Deep learning-based Multi-View Stereo (MVS) has advanced significantly but often generalizes poorly to unseen scenes, particularly in occluded areas or regions with limited view overlap. To mitigate this, recent approaches integrate Depth Foundation Models (DFMs) into MVS pipelines to provide monocular depth priors. However, existing methods typically rely on a static, one-way fusion scheme, which fails to fully exploit the complementary strengths of both modalities. We propose a novel framework that overcomes this limitation by tightly coupling a DFM with a cascade MVS pipeline through a bidirectional mutual refinement strategy. Our method leverages MVS depth to resolve the scale ambiguity in monocular predictions, while the monocular depth, in turn, enhances the structural completeness and fine-grained detail of the MVS estimate. Furthermore, we introduce a prior-guided cost volume refinement mechanism that effectively integrates multi-view and monocular information via attention-bas

---

### [348] Geo-VLA: Geometry-Aware Vision-Language-Action Planning via Internalization of Map Semantics

**链接**: https://arxiv.org/abs/2608.21440
**作者**: Ran Chen, Jiaxing Ren, Zhikun Zhang, Yunhao Hou, Junbao Zhuo, Bochao Zou
**来源**: cs.RO cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Vision-language-action (VLA) models have advanced end-to-end autonomous driving by leveraging foundation models for semantic reasoning and long-tail generalization. However, their planning performance remains limited in complex driving environments because image-only representations inadequately capture planning-relevant road geometry and topology. In this paper, we propose Geo-VLA, a plug-and-play framework that enhances VLA models by learning geometry-aware visual representations. During training, Geo-VLA internalizes geometric map semantics to strengthen road-structure representations, while requiring no HD maps or additional lane information during inference. To support this approach, we introduce Geo-QA, a geometry-focused question-answering dataset that injects road geometry into vision-language representations through contrastive learning and instruction tuning. Experiments on NAVSIM v1 demonstrate that Geo-VLA consistently improves VLA planners with distinct action-generation a

---

### [349] WildFin: An In-the-Wild Dataset for Fish Behavioral Recognition

**链接**: https://arxiv.org/abs/2608.21281
**作者**: Abigail G. Grassick, Jerome Tze-Hou Hsu, Ethan Lin, Ziang Liu, Max Whitton, Madelyn Hair 等 (10 人)
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent advances in field technology have led to a massive influx of in-the-wild video data for ecological science. The primary bottleneck in leveraging this data is the high cost of expert annotation. While computer vision offers a potential solution, current models frequently fail when deployed in complex marine environments. To characterize these failures, we introduce WildFin, a novel benchmark for fish behavior recognition collected and annotated by ecologists.WildFin spans two critical real-world paradigms: stationary cameras monitoring groups of fish and dynamic divers following individual subjects. The dataset represents a massive curation effort, involving 1,350 hours of fieldwork and 600 hours of expert annotation to produce 9 hours of behavioral data with over 2 million frame-by-frame labels. We benchmark modern vision foundation models and quantify tradeoffs between static and spatiotemporal architectures, revealing the substantial gap that remains between current model capa

---

### [350] Lift, Associate, and Fuse: A Decision-Centric Framework for 2D-to-3D Foundation Model Transfer

**链接**: https://arxiv.org/abs/2608.20659
**作者**: Wentao Sun, Yiping Chen, John S. Zelek, Jonathan Li
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Methods that transfer predictions from two-dimensional foundation models into three-dimensional segmentation are commonly grouped by task or representation. Those groupings obscure the decisions that determine whether a system remains coherent across views: where image evidence is grounded, when observations become one identity, how semantic and granularity conflicts are handled, which information is fused, and what state survives for later queries. We introduce \textbf{Lift, Associate, and Fuse (LAF)}, a decision-centric framework that represents a transfer system as five operators: \textbf{Generate, Associate, Reconcile, Fuse, and Persist/Query}. LAF defines an explicit contract for the persistent carrier---its spatial support, semantic state, identity state, uncertainty, provenance, and supported operations---and identifies the first stage at which discarded evidence becomes unrecoverable. We operationalize the framework as a structured audit protocol and apply it to 161 systems ava

---

### [351] Interpretable AI with Local Distillation

**链接**: https://arxiv.org/abs/2608.23538
**作者**: Erin Craig and Yiling Huang and Snigdha Panigrahi
**来源**: stat.ME cs.LG stat.ML
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Modern AI models such as tabular foundation models and gradient-boosted ensembles can outpredict classical methods, but provide little basis for reasoning about their predictions. High-stakes decisions call for models that are both accurate and interpretable as built. Local linear modeling offers a path forward: a smooth regression function is locally well approximated by a linear one, allowing a linear fit near each query point to achieve high accuracy without sacrificing transparency. The challenges lie in learning what is "local" and developing statistical tools for interpretation. Here, we propose local distillation, in which a black-box "teacher" guides a regularized linear "student" model at each query point. The teacher (1) defines locality by upweighting training observations with similar predicted outcomes, and (2) anchors the fit with its prediction at the query point, included as a pseudo-observation whose weight is estimated from the data. For interpretation, we add a small

---

### [352] Tydra: An Efficient Hybrid Model for Tabular Data

**链接**: https://arxiv.org/abs/2608.21199
**作者**: Mieszko Komisarczyk, Saurabh Mathur, Maurice Kraus, Sriraam Natarajan, Kristian Kersting
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Transformer-based tabular foundation models such as TabPFN achieve strong predictive performance but incur quadratic computational cost with context length. On the other hand, subquadratic SSM-based alternatives such as Hydra trade away accuracy for efficiency. To balance both, we introduce Tydra, a hybrid Transformer-State Space Model (SSM) architecture for tabular in-context learning that interleaves attention and SSM layers. Across 30 OpenML datasets, Tydra reduces inference time by 30% relative to TabPFN while retaining much of its predictive performance. Tydra also outperforms an approximately ten-times-larger Hydra model while providing faster inference. The results indicate that hybrid architectures are a promising direction for tabular foundation models.

---

### [353] A2DINOv3: Rethinking Multi-Modal Object Detection via Socialized Collaboration

**链接**: https://arxiv.org/abs/2608.21099
**作者**: Jiekang Feng, Zhihe Fan, Yunqi Zhu, Xinjie Yao, Yueying Zhang, Yike Gao 等 (8 人)
**来源**: cs.CV cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-modal object detection is essential for robust scene understanding in challenging conditions, including low-light and adverse environments. Recent vision foundation models (e.g., DINOv3) have exhibited strong representation capabilities, yet adapting them to multi-modal scenarios remains challenging. Existing dense cross-modal fusion strategies often force heterogeneous modalities to interact indiscriminately, which may introduce redundant information and disrupt the valuable pre-trained representations. To address this issue, we revisit multi-modal fusion from the perspective of socialized learning and propose adapter to DINOv3 (A2DINOv3), a multi-expert collaboration framework with a Socialized Collaboration Protocol (SCP). Specifically, RGB and infrared branches are modeled as heterogeneous experts that independently preserve their specialized knowledge while exchanging complementary information through selective and constrained interactions. This design mitigates harmful cros

---
